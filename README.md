###Get First 30 Records from DB
request **GET**
`http://localhost:8080/server/list`

###Get Records with ID
request **GET** 
`http://localhost:8080/server/get/2`

###Save Server on DB
request **POST** 
`http://localhost:8080/server/save
` {

            "ipAddress": "192.168.1.195",
            "name": "Ubuntu Linux",
            "memory": "32 GB",
            "type": "Lenova",
            "status": "SERVER_DOWN"
}


### PING
request GET 'http://localhost:8080/server/ping/192.168.1.21' 
`{

            "ipAddress": "192.168.1.195",
            "name": "Ubuntu Linux",
            "memory": "32 GB",
            "type": "Lenova",
            "status": "SERVER_DOWN"
}`



