# 前端路由

- 路由跳转不发起服务端请求
- 也就是前端劫持路由的变化，这样就可以根据前端路由变化发起一些前端无刷新渲染
- 可以将用户状态保存在 URL 中，刷新时候做出针对性渲染

## hash 路由

- 通过`location.hash`能够拿到`#`+`路径`
- 一个简单的[示例](./hash路由.html)

## history 路由

- 不再通过`<a href="#home"></a>`进行切换，而是要`pushState`手动切换
- 一个简单的[示例](./history路由.html)
