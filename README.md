# Geo App Backend
Backend for my geolocation app built in Swift by **Dhars**.

## How to use it
1. `npm install` the modules.
2. Create `config/config.env` with:
```
NODE_ENV=development
PORT=3000
MONGO_URI=mongodb://localhost:27017/geo-app
```
3. `npm run dev`

## Endpoints (GET & POST)
http://localhost:3000/api/v1/user
http://localhost:3000/api/v1/pins

## JSON Format - POST req

### User (example)
```json
{
    "userId": "Dhars",
    "location": {
        "coordinates": [20.774756, -50.076481]
    }
}
```

### Pins (example)
```json
{
    "pinId": "1",
    "location": {
        "coordinates": [20.774756, -50.076481]
    }
}
```
