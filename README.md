Definition: 
Make a Todo List Using Vue JS
1. There should be a Textbox and Button

![alt text](https://github.com/poojathakor/TodoListUsingVue/blob/master/todoNormal/a.png)

2. Once we enter Text and Click on Add Button, It should be added in the List having Checkbox.

![alt text](https://github.com/poojathakor/TodoListUsingVue/blob/master/todoNormal/b.png)

3. If checkbox is checked, the item should be striked out
Make use of Vue-CLI and Bootstrap-Vue

![alt text](https://github.com/poojathakor/TodoListUsingVue/blob/master/todoNormal/b.png)

## Build Setup
[VUE CLI](https://cli.vuejs.org/guide/installation.html)

``` bash
# install VUE CLI
npm install -g @vue/cli

# you can check version
vue --version

# set name, version, description, author as per requirement

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# to install Bootstrap
npm i vue bootstrap-vue bootstrap
```

## Integrate Bootstrap
[Bootstrap Vue](https://bootstrap-vue.js.org/docs)
``` bash
# add in main.js
import BootstrapVue from 'bootstrap-vue'
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap-vue/dist/bootstrap-vue.css"
 
Vue.use(BootstrapVue);

```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
