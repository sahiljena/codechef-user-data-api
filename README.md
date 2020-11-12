# Codechef User Data API
Get data like user global rank, country rank , rating and stars from this api

# Requests

URL : https://api-base-sahil.herokuapp.com/codechef
| Request Type | Parameters |
| --- | --- |
| POST | "username" - > Codechef Username  |
| GET | "username" - > Codechef Username |

<b>Example Request POST </b>
```
import requests

URL = "https://api-base-sahil.herokuapp.com/codechef"

parameters={
  "username":"username"
}

r = requests.post(URL,params=parameters)

print(r.text)
```
<b>Example Request GET </b>
```
import requests

URL = "https://api-base-sahil.herokuapp.com/codechef"

parameters={
  "username":"username"
}

r = requests.get(URL,params=parameters)

print(r.text)
```
