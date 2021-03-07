# Football Analytics Project

## Adam McMurchie & Craig Skelly 
  
This is our football project.
  
![](https://www.heraldscotland.com/resources/images/11514179/)  


This project gets the latest football statistics and saves to database and shares in a weekly email update.


```
import requests

url = "https://api-football-v1.p.rapidapi.com/v2/predictions/157462"

headers = {
    'x-rapidapi-key': "d4146c6ae2msh0bdf98ae0cb9609p1815abjsn0c6fdc333c65",
    'x-rapidapi-host': "api-football-v1.p.rapidapi.com"
    }

response = requests.request("GET", url, headers=headers)

print(response.text)
```

