# ts-zustand

该项目用于演示zustand在TypeScript下的使用，包含常用用法介绍以及复杂store的组织方式

#### 运行
```
git clone git@github.com:chw1003/ts-zustand.git

npm install 

npm start
```

#### 项目目录结构
```
./ts-zustand

├─.gitignore 
├─README.md 
├─package-lock.json 
├─package.json 
├─src 
│ ├─App.css 
│ ├─App.test.tsx 
│ ├─App.tsx 
│ ├─components 
│ │ ├─cat 
│ │ │ └─index.tsx 
│ │ ├─dog 
│ │ │ └─index.tsx 
│ │ ├─token 
│ │ │ └─index.tsx 
│ │ └─user 
│ │   └─index.tsx 
│ ├─hooks 
│ │ └─useURLLoader.ts 
│ ├─index.css 
│ ├─index.tsx 
│ ├─logo.svg 
│ ├─pages 
│ │ ├─home 
│ │ │ └─index.tsx 
│ │ ├─login 
│ │ │ └─index.tsx 
│ │ └─shallow 
│ │   └─index.tsx 
│ ├─react-app-env.d.ts 
│ ├─reportWebVitals.ts 
│ ├─services 
│ │ ├─cat 
│ │ │ └─index.ts 
│ │ ├─dog 
│ │ │ └─index.ts 
│ │ ├─home 
│ │ ├─login 
│ │ │ └─index.ts 
│ │ └─user 
│ ├─setupTests.ts 
│ ├─store 
│ │ ├─createStore.ts ------ // 负责创建 Store 的方法与 Action 方法
│ │ ├─index.ts ------------ // 导出所有类型、状态与hooks
│ │ ├─initialState.ts ----- // 负责 State —— 添加状态类型与初始化状态值
│ │ └─useState.ts --------- // 自定义state hooks，方便复用与筛选查询
│ └─utils 
│   └─request.ts 
└─tsconfig.json 
```
