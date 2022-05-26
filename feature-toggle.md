feature toggle 介绍
- https://martinfowler.com/articles/feature-toggles.html
- https://www.flagship.io/feature-flags-react-app/

feature toggle 框架
- https://www.npmjs.com/package/react-feature-flags --> 这种不好用,tech debt处理麻烦
- https://www.npmjs.com/package/feature-toggle-api --> 看着就头疼
- https://www.npmjs.com/package/react-unleash-flags --> 这种要有对应的服务器作为中心，难用
- https://www.npmjs.com/package/react-feature-toggles --> 比较容易用，tech debt也相对好处理

feature toggle demo
- https://stackblitz.com/edit/reactor-feature-toggle-sample?file=index.tsx,Page.tsx
- 

自己思考：
组件怎么做toggle，css是否需要做toggle,例如SearchButton里面我需要改样式，如何处理。要考虑怎么降低tech debt和能友好的处理tech debt.
精力应放在设计上面（怎么降低tech debt和能开发人员能够友好的处理tech debt.）
两个不同的样式，调用的函数都不一样，当我新版要上，旧的版如何处理？ --> 这种我目前觉得只能靠Eslint提示去删除这些东西）
