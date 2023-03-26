# use-ES-build

## 安装 ES-build
   -  ```pnpm i esbuild```

## esbuild 使用方式
   -  命令行调用
       -  需要安装前置依赖
           - pnpm install react react-dom
       -    package.json中添加build脚本
           -  eg: 
             ```"build": "./node_modules/.bin/esbuild src/index.jsx --bundle --outfile=dist/out.js"```      
