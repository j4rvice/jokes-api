# jokes-api

* This api returns a random jokes each time you call it

* link to the (jokes-api)[https://jokes-api.gamhcrew.repl.co]

* getting the response of the api in shell :
```shell
curl https://jokes-api.gamhcrew.repl.co
```

# using the api in python
* install requests library in python using the command below
```shell
pip install requests
```
* python code :
```py
import requests
api = 'https://jokes-api.gamhcrew.repl.co'
joke = requests.get(api).text
print(joke)
```
