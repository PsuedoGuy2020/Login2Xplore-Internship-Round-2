# Title:
JSONPOWER DB FORM
# Description:
This is a web based project on form validation and data storage in database using JsonPowerDb.
![Screenshot 2022-07-03 195305](https://user-images.githubusercontent.com/76483737/177044072-26731c09-9d45-49a9-8591-2bddfca56afc.png)
![Screenshot 2022-07-03 195423](https://user-images.githubusercontent.com/76483737/177044106-682cc28c-2bf8-425e-8f40-96c551f225ed.png)
# About JsonPowerDB:
1) JsonPowerDB is a Real-time, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. 
2) It is a ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality.
3) It supports and advocates for serverless and pluggable API development.
4) It is a DBMS with built in web / application server and embedded caching makes the performance lightning fast.
# Benefits Of Using JsonPowerDB:
1) JsonPowerDB is a Database Server with Developer friendly REST API services.
2) It has High Performance.
3) It is a Real-time Database.
4) It is Light Weight, Ajax Enabled & Serverless architecture.
5) It is Simple to use, Schema-free, Nimble and In-Memory database.
6) It is built on PowerIndeX which is fastest indexing engine.
7) It enhances the pace of development & reduces its cost. 
# JsonPowerDB Code Releases:
1) Student Database (PUT request):
Http method : POST
Base url : http://api.login2explore.com:5577
End-point url : /api/iml
{
    "token": "90939264|-31949286935901146|90939726",
    "cmd": "PUT",
    "dbName": "Student",
    "rel": "Student-Rel",
    "jsonStr": {
        "stuId": "1",
        "stuName": "rishank",
        "stuEmail": "rishank@gmail.com",
        "stuMbo": "1234567890"
    }
}
2) Student Database (GET request):
Http method : POST
Base url : http://api.login2explore.com:5577
End-point url : /api/irl
{
    "token": "90939264|-31949286935901146|90939726",
    "dbName": "Student",
    "cmd": "GET_BY_KEY",
    "rel": "Student-Rel",
    "createTime": true,
    "updateTime": true,
    "jsonStr": {
        "name": "rishank"
    }
}
3) Student Database (UPDATE request):
Http method : POST
Base url : http://api.login2explore.com:5577
End-point url : /api/iml
{
    "token": "90939264|-31949286935901146|90939726",
    "dbName": "Student",
    "cmd": "GET_BY_KEY",
    "rel": "Student-Rel",
    "jsonStr": {
      "1":{"name": "mohit"},
      "2":{"mobileno": "2323232323"}
    }
}
4) Student Database (REMOVE request):
Http method : POST
Base url : http://api.login2explore.com:5577
End-point url : /api/iml
{
    "token": "90939264|-31949286935901146|90939726",
    "cmd": "REMOVE",
    "dbName": "Student",
    "rel": "Student-Rel",
    "record": 1,
    "jsonStr" : {}
}
# Screesnhots:
![json](https://user-images.githubusercontent.com/76483737/177031000-e1cb8493-ffd3-411a-ae3a-c95400a985b4.png)
![Screenshot 2022-07-03 194818](https://user-images.githubusercontent.com/76483737/177043893-aec4fdff-c794-4705-bc98-d8b23b84a134.png)
![Screenshot 2022-07-03 194940](https://user-images.githubusercontent.com/76483737/177043926-d787c199-d0ce-4b94-893f-ff6375f32860.png)
![Screenshot 2022-07-03 195026](https://user-images.githubusercontent.com/76483737/177043954-d9841ef4-adb2-47a1-91e2-31e2a241f24e.png)
![Screenshot 2022-07-03 195108](https://user-images.githubusercontent.com/76483737/177043988-af171014-e951-46bf-a0d3-c2c116d3ae35.png)
![Screenshot 2022-07-03 195146](https://user-images.githubusercontent.com/76483737/177044016-6a074cc7-493f-436d-b527-77ec58610768.png)
# Steps To Run Project:
1) Go to documents section in PC.
2) Go to NetbeansProject folder.
3) Clone this repository, unzip and paste the WebFormExample folder project in above directory.
4) Open Netbeans->dashboard.html->run file.



