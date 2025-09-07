# my-fifth-repo
my test
import requests

amount = 100
from_currency = "USD"
to_currency = "EUR"

url = f"https://api.exchangerate.host/convert?from={from_currency}&to={to_currency}&amount={amount}"
response = requests.get(url).json()

print(f"{amount} {from_currency} = {response['result']} {to_currency}")
________________________________________
