
# project

```
|-src
|--asset -> 共用componet
   |--ui
    |--simulate
|--components -> 共用componet
|--views
    |--Home.vue
|--router -> 路由
    |--index.js
    |--ListRouter.js
|--store -> Vuex
    |--index.js
    |--list
        |--action.js
        |--getter.js
        |--mutation.js
        |--state.js
        |--index.js
|--api
    |--api-url.js
    |--request-param.js
    |--telegram.js -> 共用的rq、rs,包括是否要用模擬電文
    |--error_code.js  -> API回傳錯誤mapping表
|--utils 
    |--config.js ->參數檔
|--i18n
    |--lang.js
|--environments -> SIT、UAT、PROD
|--RESOURCES -> CI/CD
|--DEPLOY -> CI/CD
└── prettierrc.json -> prettier
└── .eslintrc.json -> eslint
└── .gitignore
└── tsconfig.json -> typescript 設定
└── vue.config.js
└── index.html
