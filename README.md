# angular-5tdzmz-be2vnv

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/angular-5tdzmz-be2vnv)

### 遇到难题

`import {Product} from '../products`

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在学习 `Angular` 示例的时候，明明是按教程所写，但是依旧报错。在 `products.ts` 中，并没有 `Product` 。这实在是令人无奈，教程也没有说，无奈只能自己想办法。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`@Input() product !: Product;`，可以看到，`Product` 应该是一种类型。没办法，只能在 `products.ts` 中写入一个类型。

```javascript
export Interface Product{
  id:Number,
  name: String,
  price: Number,
  description: String
}
```
