## *__Quick Access__*
* [No_Auth_Header](#no_auth_header)
* [Bad_Authentication](#bad_authentication)

---

### No_Auth_Header
You Have Not Provided An Api Key In The Header.
```python
import requests
headers = {"IMPULSE-API-KEY" : "<<YOUR-API-KEY>>"}
url = "<<YOUR-API-END-POINT>>"
response = requests.get(url, headers=headers).json()
print(response)
```

### Bad_Authentication
Provided API Key Is Wrong Check It Again Then Try.
