# `<z-rmb>`

A perticular tag name for display CNY price

## Attributes

- `value`
- `front` & `end`: prefix and suffix of the price
- `showfraction`: `"true"` | `"false"` | `"auto"`
- `del`: strike line

## Selectors

- `::shadow .front`
- `::shadow .integer`
- `::shadow .dot`
- `::shadow .fraction`
- `::shadow .end`
- `::shadow .strike`

## Examples

```
<style>z-rmb::shadow .integer {font-size: 1.5em;}</style>

<z-rmb value="100"></z-rmb><br>
<z-rmb front="￥" value="100"></z-rmb><br>
<z-rmb front="" end="元" value="100"></z-rmb><br>
<z-rmb showfraction="false" value="100"></z-rmb><br>
<z-rmb del showfraction="false" value="100.50"></z-rmb><br>
<z-rmb showfraction="true" value="100"></z-rmb><br>
<z-rmb showfraction="true" value="100.50"></z-rmb><br>
<z-rmb showfraction="auto" value="100"></z-rmb><br>
<z-rmb showfraction="auto" value="100.50"></z-rmb><br>
<z-rmb del value="100"></z-rmb><br>
```
