# vue-指令

创建一个 Vue 实例 [代码](https://github.com/biji-ziliao/vue2-biji/blob/0545a7c1908b198d4e3fdda2fb5812823e07ff11/01-%E6%8C%87%E4%BB%A4/01-%E5%88%9B%E5%BB%BA%E4%B8%80%E4%B8%AAVue%E5%AE%9E%E4%BE%8B.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/0545a7c1908b198d4e3fdda2fb5812823e07ff11/01-%E6%8C%87%E4%BB%A4/01-%E7%AC%94%E8%AE%B0.md#%E4%B8%89%E5%88%9B%E5%BB%BAvue%E5%AE%9E%E4%BE%8B)

插值表达式是一种Vue的模板语法  [代码](https://github.com/biji-ziliao/vue2-biji/blob/0545a7c1908b198d4e3fdda2fb5812823e07ff11/01-%E6%8C%87%E4%BB%A4/02-%E6%8F%92%E5%80%BC%E8%A1%A8%E8%BE%BE%E5%BC%8F.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/0545a7c1908b198d4e3fdda2fb5812823e07ff11/01-%E6%8C%87%E4%BB%A4/01-%E7%AC%94%E8%AE%B0.md#%E5%9B%9B%E6%8F%92%E5%80%BC%E8%A1%A8%E8%BE%BE%E5%BC%8F-)

响应式  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/03-%E5%93%8D%E5%BA%94%E5%BC%8F.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/01-%E7%AC%94%E8%AE%B0.md#%E4%BA%94%E5%93%8D%E5%BA%94%E5%BC%8F%E7%89%B9%E6%80%A7)

内容渲染指令（v-html、v-text）[代码](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/04-Vue%20%E6%8C%87%E4%BB%A4%E4%BD%93%E9%AA%8C-v-html.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/01-%E7%AC%94%E8%AE%B0.md#%E5%85%AB%E5%86%85%E5%AE%B9%E6%B8%B2%E6%9F%93%E6%8C%87%E4%BB%A4)

- 条件渲染指令（v-show、v-if、v-else、v-else-if）[代码](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/05-Vue%20%E6%8C%87%E4%BB%A4-v-show%E3%80%81v-if.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/01-%E7%AC%94%E8%AE%B0.md#%E4%B9%9D%E6%9D%A1%E4%BB%B6%E6%B8%B2%E6%9F%93%E6%8C%87%E4%BB%A4)
    
    v-else、 v-else-if     [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/06-Vue%20%E6%8C%87%E4%BB%A4-v-else%E3%80%81v-else-if.html)
    
- 事件绑定指令（v-on:click简写为 **@**click）[代码](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/07-Vue%20%E6%8C%87%E4%BB%A4-v-on-%E5%86%85%E8%81%94%E8%AF%AD%E5%8F%A5.html)      [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/01-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E4%BA%8B%E4%BB%B6%E7%BB%91%E5%AE%9A%E6%8C%87%E4%BB%A4)
    
    @click="buy(5)”参数传递 [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/09-Vue%20%E6%8C%87%E4%BB%A4-v-on-%E5%8F%82%E6%95%B0%E4%BC%A0%E9%80%92.html)
    

属性绑定指令 （v-bind）[代码](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/10-Vue%20%E6%8C%87%E4%BB%A4-v-bind.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/01-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E4%B8%80%E5%B1%9E%E6%80%A7%E7%BB%91%E5%AE%9A%E6%8C%87%E4%BB%A4)

双向绑定指令（v-model）[代码](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/15-Vue%E6%8C%87%E4%BB%A4-v-model.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/01-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E5%85%AD%E5%8F%8C%E5%90%91%E7%BB%91%E5%AE%9A%E6%8C%87%E4%BB%A4)

列表渲染指令（v-for）[代码](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/14-Vue%E6%8C%87%E4%BB%A4-v-for-key.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/01-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E4%BA%94v-for%E4%B8%AD%E7%9A%84key)

- 综合案例-小黑记事本  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/16-%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B-%E5%B0%8F%E9%BB%91%E8%AE%B0%E4%BA%8B%E6%9C%AC/03-%E5%B0%8F%E9%BB%91%E8%AE%B0%E4%BA%8B%E6%9C%AC%E5%8A%9F%E8%83%BD%E5%AE%9E%E7%8E%B0-%E5%BA%95%E9%83%A8%E5%8A%9F%E8%83%BD.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/0545a7c1908b198d4e3fdda2fb5812823e07ff11/01-%E6%8C%87%E4%BB%A4/01-%E7%AC%94%E8%AE%B0.md#%E5%9B%9B%E6%8F%92%E5%80%BC%E8%A1%A8%E8%BE%BE%E5%BC%8F-)
    
    功能：删除、添加、统计多少个任务、清空任务
