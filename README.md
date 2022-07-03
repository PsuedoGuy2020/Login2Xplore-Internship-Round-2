# Title:
JSONPOWER DB FORM
# Description:
This is a web based project on form validation and data storage in database using JsonPowerDb.
# Benefits Of Using JsonPowerDB:
1) JsonPowerDB is a Database Server with Developer friendly REST API services.
2) It has High Performance.
3) It is a Real-time Database.
4) It is Light Weight, Ajax Enabled & Serverless architecture.
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
# Status:
Ongoing
![json](https://user-images.githubusercontent.com/76483737/177031000-e1cb8493-ffd3-411a-ae3a-c95400a985b4.png)

