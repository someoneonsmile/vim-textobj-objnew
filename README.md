## 文本对象 for new object

## Plug

> `require vim-textobj-user`

```
  Plug 'someoneonsmile/vim-textobj-objnew', { 'for':['java'] }
```

## Example

在 `new String("string");` 上 按 `dao`:

`String s = new String("string");` => `String s = ;`

在 `new String("string");` 上 按 `dio`:

`String s = new String("string");` => `String s = new String();`
