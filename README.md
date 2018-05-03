# vue-bolierplate

기존 뷰의 folder hierarchy는 효율적이지 못해서 구조를 변형시켰습니다.

구조는 아래와 같습니다.

````
src   
├── App.vue 
├── assets
|   ├── css
|   |   └── main.css
|   ├── font 
|   └── img 
├── commons
|   ├── directives 
|   ├── functions 
|   ├── resources
|   └── validations
├── config 
|   ├── directives.js
|   ├── router.js
|   └── validations.js
├── shared-components 
|   ├── RangeCustom.vue 
|   ├── Sidebar.vue 
|   └── Toolbar.vue 
├── spa 
|   ├── Login 
|   |   ├── components
|   |   └── Login.vue
|   ├── Products 
|   |   ├── components
|   |   └── Products.vue
|   ├── components
|   ├── Home.vue 
|   └── NotFound.vue 
├── vuex 
|   ├── modules 
|   └── store.js 
└── main.js
````

자세한 설명들이 각 섹션별로 README.md 로 이루어져 있습니다.

설명을 보시면 이해가 빠를 것 입니다.
