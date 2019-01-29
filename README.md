# SimplePay API

Unofficial Python bindings for Simple Pay's API.

https://www.simplepay.co.za/api-docs/


## Installation
```bash
$ pipenv install simplepay
```

Or if you are using pip:

```bash
$ pip install simplepay
```

## Usage
```python

from simplepay import SimplePay

api = SimplePay("simple-pay-api-key")
print(api.get_clients())
print(api.get_employees("client_id"))
```

## Documentation

Documentation can be found here: https://cstranex.github.io/simplepay
