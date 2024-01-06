# Routers-Vue.js
<br>

```javascript
import { createRouter, createWebHistory } from 'vue-router';
import Login from '.page/Login.vue';
import Signup from '.page/Signup.vue';

const routes = [
  {path: '/login', component: Login}
  {path: '/signup', component: Signup}
];

const router = createRouter({
  history: createWebHistory(),
  routes,
});

export default router;
```
