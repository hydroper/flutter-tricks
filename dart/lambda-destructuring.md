# Lambda Destructuring

You can use destructuring in lambdas, but may often need to use `a = initial` when destructuring in a lambda, as you may get a non-null diagnostic:

```dart
F f = ([a = 0]) {};
```

Using `required` or `?` isn't supported in Dart's destructuring.
