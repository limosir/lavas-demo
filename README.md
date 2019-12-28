# lavas-demo
练习demo
import { Message,Progress } from 'element-ui';
import 'element-ui/lib/theme-chalk/index.css';
export default {
    install: function(Vue,potions) {
        Object.defineProperty(Vue.prototype, '$message', { value: Message });
        Vue.use(Progress);
    }
  }
