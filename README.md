# Private Cloud

## 使用
项目使用了`yarn workspace`来统一管理各个子项目，子项目统一位于`apps/`下。开发时使用`yarn workspace <AppName> <your script>`执行对应项目中的脚本

例如
```
// 前端dev
yarn workspace frontend start

// 等价于在./apps/frontend下执行

npm run start


// 后端dev
yarn workspace backend dev
```
## 前端
+ typescript
+ react-hooks
+ immer

## 后端
+ typescript
+ egg.js
