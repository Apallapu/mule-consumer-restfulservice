# mule-consumer-restfulservice




http://training-american-ws.cloudhub.io/api/flights/1
/{flightId}



DELETE:http://training-american-ws.cloudhub.io/api/flights/ID

/deleteFlightTicketById/{flightId}



post: 
http://training-american-ws.cloudhub.io/api/flights

{
  "ID": "55",
  "code": "rerd23",
  "price": "1234",
  "departureDate": "2019-01-25T00:00:00",
  "origin": "MUB",
  "destination": "HYD",
  "emptySeats": "7",
  "plane": {
    "type": "Boeing 700",
    "totalSeats": 345
  }
}

