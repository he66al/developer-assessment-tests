# PrimeKeeper Junior Backend Test.

Using any framework that you prefer and any language that you wish, do the following:

**Problem**: Create an API with the end-point `/listPrimes`. This API will list down all the primes from 2 to the value given to the `/listPrimes` end-point

* This API accepts an integer number `value` i.e.
```json
{
    "value": 123
}
```

* This API will respond with an array `primes`, containing prime numbers from 2 to `value` i.e.
```json
{
    "primes": [2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97, 101, 103, 107, 109, 113]
}
```

* In cases where an error has occured, this API will produce the following response instead. i.e. if the value is not an integer, it should have the following error:
```json
{
    "error": "Value should be an integer"
}
```

Please e-mail to `clayton@primekeeper.my` and `michael@primekeeper.my` with the answer.
