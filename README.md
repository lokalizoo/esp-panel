## How To

1. Clone repo
2. `npm install`
3. `npm run build` to build into `www/`
4. `npm run watch` to run server

## API

```http
POST /api/config HTTP/1.1
Content-Type: application/x-www-form-urlencoded

wifi_ssid=...&
wifi_passwd=...&
port=...&
start_server=...&
start_ap=...&
cfg_url=...&
cfg_json=...
```
