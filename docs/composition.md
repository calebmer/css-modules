## Composition

It's possible to compose selectors using the at rule `@composes`.

``` css
.className {
  color: green;
  background: red;
}

.otherClassName {
  @composes className;
  color: yellow;
}
```
