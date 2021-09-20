GET 
curl -v localhost:8080/coasters

POST 
curl localhost:8080/coasters -X POST -d '{"name": "Taron", "inPark": "Phantasialand", "height": 30, "manufacturer": "Intamin"}' -H "Content-Type: application/json"

POST to Admin
curl localhost:8080/admin -u admin:1234

PUT 
curl -v localhost:8080/coasters -X PUT

# Golang-tutorial
# Golang-tutorial
# Golang-tutorial
