## *__Quick Access__*
* [No_Auth_Header](https://impulseai.github.io/API-Error-Codes/#No_Auth_Header)
* [Bad_Authentication](https://impulseai.github.io/API-Error-Codes/#Bad_Authentication)

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
