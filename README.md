# yellow-api
Estudo de engenharia reversa da API do aplicativo Yellow 🚲🛴

# Métodos

### Configuration
```
GET /maps/configuration HTTP/1.1
```

```
Host: api.yellow.tech
Authorization: #REMOVEDFORSECURITY
Accept: */*
Accept-Encoding: gzip;q=1.0, compress;q=0.5
Accept-Language: en
platform: ios
X-Latitude: -23.596628888267958
X-Accuracy: 65.0
User-Agent: iOS/1.8.0
Connection: keep-alive
X-App-Version: 1.8.0
X-Longitude: -46.67795430276748
X-Location-Date: 2019-02-20T16:07:35.770-0300
os-version: 12.1.4
```
### Vehicles
```
GET /vehicles/viewport?bottomRightLat=-22.60200987169516&bottomRightlng=-46.67481355369091&topLeftLat=-23.59124778339138&topLeftlng=-46.68109528720379 HTTP/1.1
```
```
Host: api.yellow.tech
Authorization: #REMOVED FOR SECURITY ISSUES
Accept: */*
Accept-Encoding: gzip;q=1.0, compress;q=0.5
Accept-Language: en
platform: ios
X-Latitude: -23.596628888267958
X-Accuracy: 65.0
User-Agent: iOS/1.8.0
Connection: keep-alive
X-App-Version: 1.8.0
X-Longitude: -46.67795430276748
X-Location-Date: 2019-02-20T16:07:35.770-0300
os-version: 12.1.4
```
