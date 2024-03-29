import requests
api_url = "https://data.covid19india.org/v4/min/timeseries.min.json"
response = requests.get(api_url)
dict_a = response.json()
dict_a
