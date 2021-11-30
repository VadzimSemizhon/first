# first
❗️❗️❗️Важные атрибуты документации первого примера для тех, кто захочет повторить самостоятельно:
❇️ Base URL:  https://rahulshettyacademy.com    
❇️ Обязательный параметр для всех запросов: key =qaclick123
🔶POST:
➡️ Resource: /maps/api/place/add/json
➡️ Sample Body:
{
  "location": {
    "lat": -38.383494,
    "lng": 33.427362
  },
  "accuracy": 50,
  "name": "Frontline house",
  "phone_number": "(+91) 983 893 3937",
  "address": "29, side layout, cohen 09",
  "types": [
    "shoe park",
    "shop"
  ],
  "website": "http://google.com",
  "language": "French-IN"
}
🔶GET:
➡️ Resource: /maps/api/place/get/json
➡️ Query Parameters: key,  place_id ( place_id  value comes from Add place response)
🔶PUT:
➡️ Resource: /maps/api/place/update/json
➡️ Sample Body:
{
  "place_id":"8d2573bdf6ceec0e474c5f388fa917fb",
  "address":"70 Summer walk, USA",
  "key":"qaclick123"
}
🔶DELETE:
➡️ Resource: /maps/api/place/delete/json
➡️ Sample Body:
{
    "place_id":"928b51f64aed18713b0d164d9be8d67f"
}
=============================
Документация POSTMAN: 
https://learning.postman.com/docs/get...
