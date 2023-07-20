# Dart Basics

## Function Types

Syntax:

```
T Function(params)
```

Note `Function` is a special word here.

Example:

```
void Function()? callback;
```

## Type Alias

```
typedef N2 = N1;
```

## Destructuring

You can use destructuring everywhere a binding is used, but may often need to use `a = initial` or `a?` when destructuring in a lambda.
