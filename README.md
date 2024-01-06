# Routers-Vue.js
<br>

```javascript
import { createRouter, createWebHistory } from 'vue-router';

const routes = [
  {path: '/login', component: Login}
];

const router = createRouter({
  history: createWebHistory(),
  routes,
});

export default router;
```
