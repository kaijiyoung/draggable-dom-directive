# draggable-dom-directive
create a draggable directive for vue, surpport check screen outrange inset

# 此项目代码是由chatGPT生成的代码片段，可直接在项目中使用

```javascript
import Vue from 'vue';
import App from './App.vue';
import Draggable from './directives/draggable';  // 路径根据你的项目结构进行调整

Vue.directive('draggable', Draggable);

new Vue({
  render: h => h(App),
}).$mount('#app');

```

```html
<template>
  <div v-draggable style="position: fixed;">
    This is a draggable element.
  </div>
</template>

```
