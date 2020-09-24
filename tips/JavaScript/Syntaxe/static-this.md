# Static `this`

The `this` keyword can be used inside static methods to call static properties and methods of his own class.

## Example

```js
class FooBar {
  static foo = "Hello World"

  static bar() {
    return this.foo 
  }
}
```

### Output

```js
"Hello World"
```

## Specification

- ES6+

## Annexes

- https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Classes/static

## Contributors

- [Ayfri](https://github.com/Ayfri)
