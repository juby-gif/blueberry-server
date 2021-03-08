# blueberry-server
## Usage
 1. Register to the blueberry-server
```bash
curl -X POST -d '{"email":"a@a.com","password":"123pass"}' "http://127.0.0.1:3000/api/v1/register"
```
2. Login to the blueberry-server
```bash
curl -X POST -d '{"email":"a@a.com","password":"123pass"}' "http://127.0.0.1:3000/api/v1/login"
```