# ₿ Coinhub.org
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FtheBashShell%2Fcoinbin.org.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FtheBashShell%2Fcoinbin.org?ref=badge_shield)


### The Human–Friendly API Service for Crypto Currency Information.

This free web service exists to provide information on "coins". Supports all crypto–currencies.

### Example API Endpoints

`$ curl https://coinbin.org/lbc`

```json
{
  "coin": {
    "name": "LBRY Credits", 
    "rank": "100", 
    "ticker": "lbc", 
    "value": 0.429737, 
    "value.currency": "USD"
  }
}
```
      

`$ curl https://coinbin.org/lbc/42.01`

```json
{
  "coin": {
    "exchange_rate": 0.429737, 
    "value": 18.053251369999998, 
    "value.currency": "USD"
  }
}
```
      

`$ curl https://coinbin.org/lbc/to/sc`

```
{
  "coin": {
    "exchange_rate": 61.98696034733942
  }
}
```
      

`$ curl https://coinbin.org/lbc/42.01/to/sc`

```json
{
  "coin": {
    "exchange_rate": 61.98696034733942, 
    "value": 2604.072204191729, 
    "value.coin": "sc"
  }
}
```

`$ curl https://coinbin.org/lbc/history`

```json
{
  "history": [
    {
      "timestamp": "2017-08-24T04:00:55.932092Z",
      "value": 0.3404,
      "value.currency": "USD",
      "when": "today"
    }, ...

... {
      "timestamp": "2016-07-12T04:01:09.167162Z",
      "value": 0.239634,
      "value.currency": "USD",
      "when": "Jul 12 2016"
    }
  ]
}
```

## Like this project?

Consider [tipping us](http://coinbin.org/thanks)! We have many wallets. 

## More Resources

- [Awesome Crypto Currency Tools & Algorithms (Guide)](https://github.com/kennethreitz/awesome-coins)


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FtheBashShell%2Fcoinbin.org.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FtheBashShell%2Fcoinbin.org?ref=badge_large)