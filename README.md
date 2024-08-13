# vue-指令

### 模板语法

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

- 综合案例-小黑记事本  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/16-%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B-%E5%B0%8F%E9%BB%91%E8%AE%B0%E4%BA%8B%E6%9C%AC/03-%E5%B0%8F%E9%BB%91%E8%AE%B0%E4%BA%8B%E6%9C%AC%E5%8A%9F%E8%83%BD%E5%AE%9E%E7%8E%B0-%E5%BA%95%E9%83%A8%E5%8A%9F%E8%83%BD.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/01-%E6%8C%87%E4%BB%A4/01-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E4%B8%83%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B-%E5%B0%8F%E9%BB%91%E8%AE%B0%E4%BA%8B%E6%9C%AC)
    
    功能：删除、添加、统计多少个任务、清空任务
    

### **Class 与 Style 绑定**

指令修饰符，监听键盘回车事件  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/01-%E6%8C%87%E4%BB%A4%E4%BF%AE%E9%A5%B0%E7%AC%A6.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/02-%E7%AC%94%E8%AE%B0.md#%E4%BA%8C%E6%8C%87%E4%BB%A4%E4%BF%AE%E9%A5%B0%E7%AC%A6)

指令修饰符-事件修饰符和 v-model 修饰符  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/02-%E6%8C%87%E4%BB%A4%E4%BF%AE%E9%A5%B0%E7%AC%A6-%E4%BA%8B%E4%BB%B6%E4%BF%AE%E9%A5%B0%E7%AC%A6%E5%92%8Cv-model%E4%BF%AE%E9%A5%B0%E7%AC%A6.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/02-%E7%AC%94%E8%AE%B0.md#3v-model%E4%BF%AE%E9%A5%B0%E7%AC%A6)

v-bind 对于样式 class 的控制  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/03-v-bind%E5%AF%B9%E4%BA%8E%E6%A0%B7%E5%BC%8Fclass%E7%9A%84%E6%8E%A7%E5%88%B6.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/02-%E7%AC%94%E8%AE%B0.md#%E4%B8%89v-bind%E5%AF%B9%E6%A0%B7%E5%BC%8F%E6%8E%A7%E5%88%B6%E7%9A%84%E5%A2%9E%E5%BC%BA-%E6%93%8D%E4%BD%9Cclass)

案例-tab 栏切换的 active 效果  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/04-%E6%A1%88%E4%BE%8B-tab%E6%A0%8F%E7%9A%84active%E6%95%88%E6%9E%9C.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/02-%E7%AC%94%E8%AE%B0.md#%E5%9B%9B%E4%BA%AC%E4%B8%9C%E7%A7%92%E6%9D%80-tab%E6%A0%8F%E5%88%87%E6%8D%A2%E5%AF%BC%E8%88%AA%E9%AB%98%E4%BA%AE)

v-bind 对于样式 style 的控制  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/06-%E6%A1%88%E4%BE%8B-%E8%BF%9B%E5%BA%A6%E6%9D%A1%E6%95%88%E6%9E%9C.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/02-%E7%AC%94%E8%AE%B0.md#%E4%BA%94v-bind%E5%AF%B9%E6%9C%89%E6%A0%B7%E5%BC%8F%E6%8E%A7%E5%88%B6%E7%9A%84%E5%A2%9E%E5%BC%BA-%E6%93%8D%E4%BD%9Cstyle)

v-model在其他表单元素的使用  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/07-v-model%E5%BA%94%E7%94%A8%E4%BA%8E%E5%85%B6%E4%BB%96%E8%A1%A8%E5%8D%95%E5%85%83%E7%B4%A0.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/02-%E7%AC%94%E8%AE%B0.md#%E5%85%ADv-model%E5%9C%A8%E5%85%B6%E4%BB%96%E8%A1%A8%E5%8D%95%E5%85%83%E7%B4%A0%E7%9A%84%E4%BD%BF%E7%94%A8)

### 计算属性和侦听器

computed计算属性  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/09-%E8%AE%A1%E7%AE%97%E5%B1%9E%E6%80%A7vs%E6%96%B9%E6%B3%95Methods.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/02-%E7%AC%94%E8%AE%B0.md#3%E8%AE%A1%E7%AE%97%E5%B1%9E%E6%80%A7%E7%9A%84%E4%BC%98%E5%8A%BF)

- 综合案例-成绩案例  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/11-%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B-%E6%88%90%E7%BB%A9%E6%A1%88%E4%BE%8B/03-%E6%88%90%E7%BB%A9%E6%A1%88%E4%BE%8B%E5%AE%9E%E7%8E%B0-%E8%AE%A1%E7%AE%97%E5%B1%9E%E6%80%A7.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/02-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B-%E6%88%90%E7%BB%A9%E6%A1%88%E4%BE%8B)
    
    思路分析：
    
    1.渲染功能 v-for :key v-bind:动态绑定class的样式
    
    2.删除功能 v-on绑定事件， 阻止a标签的默认行为
    
    3.v-model的修饰符 .trim、 .number、 判断数据是否为空后 再添加、添加后清空文本框的数据
    
    4.使用计算属性computed 计算总分和平均分的值
    

watch侦听器  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/14-watch%E4%BE%A6%E5%90%AC%E5%99%A8-%E5%AE%8C%E6%95%B4%E5%86%99%E6%B3%95.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/02-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E4%B8%89watch%E4%BE%A6%E5%90%AC%E5%99%A8)

- 综合案例-购物车  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/15-%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B-%E8%B4%AD%E7%89%A9%E8%BD%A6/05-%E6%8C%81%E4%B9%85%E5%8C%96%E5%88%B0%E6%9C%AC%E5%9C%B0.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/02-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E5%9B%9B%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B)
    
    实现思路：
    
    1.基本渲染： v-for遍历、:class动态绑定样式
    
    2.删除功能 ： v-on 绑定事件，获取当前行的id
    
    3.修改个数 ： v-on绑定事件，获取当前行的id，进行筛选出对应的项然后增加或减少
    
    4.全选反选
    
    1. 必须所有的小选框都选中，全选按钮才选中 → every
    2. 如果全选按钮选中，则所有小选框都选中
    3. 如果全选取消，则所有小选框都取消选中
    
    声明计算属性，判断数组中的每一个checked属性的值，看是否需要全部选
    
    5.统计 选中的 总价 和 总数量 ：通过计算属性来计算**选中的**总价和总数量
    
    6.持久化到本地： 在数据变化时都要更新下本地存储 watch
    

### **生命周期**

Vue生命周期钩子  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/15-%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B-%E8%B4%AD%E7%89%A9%E8%BD%A6/05-%E6%8C%81%E4%B9%85%E5%8C%96%E5%88%B0%E6%9C%AC%E5%9C%B0.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/02-%E5%9F%BA%E7%A1%80/02-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E5%9B%9B%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B)

- 案例-小黑记账清单  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/03-%E5%9F%BA%E7%A1%80/04-%E5%B0%8F%E9%BB%91%E8%AE%B0%E8%B4%A6%E6%B8%85%E5%8D%95/04-%E5%B0%8F%E9%BB%91%E8%AE%B0%E8%B4%A6%E6%B8%85%E5%8D%95-%E9%A5%BC%E5%9B%BE%E6%B8%B2%E6%9F%93.html)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/03-%E5%9F%BA%E7%A1%80/03-%E7%AC%94%E8%AE%B0.md#%E4%BA%94%E6%A1%88%E4%BE%8B-%E5%B0%8F%E9%BB%91%E8%AE%B0%E8%B4%A6%E6%B8%85%E5%8D%95)
    
    实现思路：
    
    1.基本渲染
    
    - 立刻发送请求获取数据 created
    - 拿到数据，存到data的响应式数据中
    - 结合数据，进行渲染 v-for
    - 消费统计 —> 计算属性
    
    2.添加功能
    
    - 收集表单数据 v-model，使用指令修饰符处理数据
    - 给添加按钮注册点击事件，对输入的内容做非空判断，发送请求
    - 请求成功后，对文本框内容进行清空
    - 重新渲染列表
    
    3.删除功能
    
    - 注册点击事件，获取当前行的id
    - 根据id发送删除请求
    - 需要重新渲染
    
    4.饼图渲染
    
    - 初始化一个饼图 echarts.init(dom) mounted钩子中渲染
    - 根据数据试试更新饼图 echarts.setOptions({...})

普通组件的注册使用-局部注册  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/03-%E5%9F%BA%E7%A1%80/05-%E8%84%9A%E6%89%8B%E6%9E%B6%E7%9B%B8%E5%85%B3%E4%BB%A3%E7%A0%81/vue-demo1/02-%E6%99%AE%E9%80%9A%E7%BB%84%E4%BB%B6%E7%9A%84%E5%B1%80%E9%83%A8%E6%B3%A8%E5%86%8C/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/03-%E5%9F%BA%E7%A1%80/03-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E6%99%AE%E9%80%9A%E7%BB%84%E4%BB%B6%E7%9A%84%E6%B3%A8%E5%86%8C%E4%BD%BF%E7%94%A8-%E5%B1%80%E9%83%A8%E6%B3%A8%E5%86%8C)

普通组件的注册使用-全部注册  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/03-%E5%9F%BA%E7%A1%80/05-%E8%84%9A%E6%89%8B%E6%9E%B6%E7%9B%B8%E5%85%B3%E4%BB%A3%E7%A0%81/vue-demo1/03-%E6%99%AE%E9%80%9A%E7%BB%84%E4%BB%B6%E7%9A%84%E5%85%A8%E5%B1%80%E6%B3%A8%E5%86%8C/main.js)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/03-%E5%9F%BA%E7%A1%80/03-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E4%B8%80%E6%99%AE%E9%80%9A%E7%BB%84%E4%BB%B6%E7%9A%84%E6%B3%A8%E5%86%8C%E4%BD%BF%E7%94%A8-%E5%85%A8%E5%B1%80%E6%B3%A8%E5%86%8C)

综合案例-分析页面，按模块拆分组件，搭架子 (局部或全局注册)  [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/03-%E5%9F%BA%E7%A1%80/03-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E4%BA%8C%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B)

### **组件通信**

- props父子组件之间的通信  [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/04-%E7%AC%94%E8%AE%B0.md#6%E7%88%B6%E5%90%91%E5%AD%90%E9%80%9A%E4%BF%A1%E4%BB%A3%E7%A0%81%E7%A4%BA%E4%BE%8B)
    
    父向子通信代码  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/03-%E7%88%B6%E7%BB%84%E4%BB%B6%E5%90%91%E5%AD%90%E7%BB%84%E4%BB%B6%E4%BC%A0%E5%80%BC/App.vue)     子向父通信代码  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/04-%E5%AD%90%E7%BB%84%E4%BB%B6%E6%83%B3%E7%88%B6%E7%BB%84%E4%BB%B6%E4%BC%A0%E5%80%BC/components/Son.vue)
    
- props的类型校验  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/07-props%E7%B1%BB%E5%9E%8B%E6%A3%80%E6%9F%A5/components/BaseProgress.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/04-%E7%AC%94%E8%AE%B0.md#3%E8%AF%AD%E6%B3%95)
    
    为组件的 prop 指定**验证要求**，不符合要求，控制台就会有**错误提示** → 帮助开发者，快速发现错误
    
- props&data、单向数据流  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/09-%E5%B0%8F%E9%BB%91%E8%AE%B0%E4%BA%8B%E6%9C%AC/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/04-%E7%AC%94%E8%AE%B0.md#3%E8%AF%AD%E6%B3%95)
    
    **1.共同点:**都可以给组件提供数据
    
    **2.区别:**
    
    - data 的数据是**自己**的 → 随便改
    - prop 的数据是**外部**的 → 不能直接改，要遵循 **单向数据流**
    - **谁的数据谁负责**
- 综合案例小黑记事本  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/07-props%E7%B1%BB%E5%9E%8B%E6%A3%80%E6%9F%A5/components/BaseProgress.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/04-%E7%AC%94%E8%AE%B0.md#2%E6%8B%86%E5%88%86%E5%9F%BA%E7%A1%80%E7%BB%84%E4%BB%B6)
    
    **列表渲染-**思路分析：
    
    1. 提供数据：提供在公共的父组件 App.vue
    2. 通过父传子，将数据传递给TodoMain
    3. 利用v-for进行渲染
    
    **添加功能-**思路分析：
    
    1. 收集表单数据 v-model
    2. 监听时间 （回车+点击 都要进行添加）
    3. 子传父，将任务名称传递给父组件App.vue
    4. 父组件接受到数据后 进行添加 **unshift**(自己的数据自己负责)
    
    **删除功能-**思路分析：
    
    1. 监听时间（监听删除的点击）携带id
    2. 子传父，将删除的id传递给父组件App.vue
    3. 进行删除 **filter** (自己的数据自己负责)
    
    **底部功能及持久化存储-**思路分析：
    
    1. 底部合计：父组件传递list到底部组件 —>展示合计
    2. 清空功能：监听事件 —> **子组件**通知父组件 —>父组件清空
    3. 持久化存储：watch监听数据变化，持久化到本地

### **非父子通信事件总线**

- 非父子通信-event bus 事件总线  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/10-%E4%BA%8B%E4%BB%B6%E6%80%BB%E7%BA%BF/components/BaseB.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/04-%E7%AC%94%E8%AE%B0.md#3%E4%BB%A3%E7%A0%81%E7%A4%BA%E4%BE%8B)
    
    非父子组件之间，进行简易消息传递。(复杂场景→ Vuex)
    
- 非父子通信-provide&inject  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/11-provide%E5%92%8Cinject/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/04-%E7%AC%94%E8%AE%B0.md#3%E8%AF%AD%E6%B3%95-1)
    
    跨层级共享数据
    

v-model原理  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/12-v-model%E5%8E%9F%E7%90%86/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/04-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E5%85%ADv-model%E5%8E%9F%E7%90%86)

- 表单类组件封装  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/13-v-model%E5%B0%81%E8%A3%85%E4%B8%8B%E6%8B%89%E6%A1%86/components/BaseSelect.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/04-%E7%AC%94%E8%AE%B0.md#2%E4%BB%A3%E7%A0%81%E6%BC%94%E7%A4%BA-2)
    
    实现子组件和父组件数据的双向绑定
    
- .sync修饰符  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/14-sync%E4%BF%AE%E9%A5%B0%E7%AC%A6/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/04-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E4%B9%9Dsync%E4%BF%AE%E9%A5%B0%E7%AC%A6)
    
    可以实现 **子组件**与**父组件数据**的**双向绑定**，简化代码
    

利用ref 和 $refs 可以用于 获取 dom 元素 或 组件实例  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/15-%24refs%E8%8E%B7%E5%8F%96DOM%E6%A0%87%E7%AD%BE/components/BaseChart.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/04-%E7%AC%94%E8%AE%B0.md#5%E4%BB%A3%E7%A0%81%E7%A4%BA%E4%BE%8B-1)

编辑标题, 编辑框自动聚焦  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/src/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/04-%E5%9F%BA%E7%A1%80/04-%E7%AC%94%E8%AE%B0.md#1%E9%9C%80%E6%B1%82)

### **自定义指令**   [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#%E4%BA%8C%E8%87%AA%E5%AE%9A%E4%B9%89%E6%8C%87%E4%BB%A4)

**1.指令介绍**

- 内置指令：**v-html、v-if、v-bind、v-on**... 这都是Vue给咱们内置的一些指令，可以直接使用
- 自定义指令：同时Vue也支持让开发者，自己注册一些指令。这些指令被称为**自定义指令**
    
    每个指令都有自己各自独立的功能
    

**2.自定义指令**

概念：自己定义的指令，可以**封装一些DOM操作**，扩展额外的功能

指令全局注册  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/01-%E6%8C%87%E4%BB%A4%E5%85%A8%E5%B1%80%E6%B3%A8%E5%86%8C-%E5%B1%80%E9%83%A8%E6%B3%A8%E5%86%8C/main.js)    局部注册  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/01-%E6%8C%87%E4%BB%A4%E5%85%A8%E5%B1%80%E6%B3%A8%E5%86%8C-%E5%B1%80%E9%83%A8%E6%B3%A8%E5%86%8C/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#%E4%BA%8C%E8%87%AA%E5%AE%9A%E4%B9%89%E6%8C%87%E4%BB%A4)

自定义指令-指令的值  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/02-%E8%87%AA%E5%AE%9A%E4%B9%89%E6%8C%87%E4%BB%A4-%E6%8C%87%E4%BB%A4%E7%9A%84%E5%80%BC/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#%E4%B8%89%E8%87%AA%E5%AE%9A%E4%B9%89%E6%8C%87%E4%BB%A4-%E6%8C%87%E4%BB%A4%E7%9A%84%E5%80%BC)

自定义指令-v-loading指令的封装  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/03-v-loading%E6%8C%87%E4%BB%A4%E5%B0%81%E8%A3%85/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#%E5%9B%9B%E8%87%AA%E5%AE%9A%E4%B9%89%E6%8C%87%E4%BB%A4-v-loading%E6%8C%87%E4%BB%A4%E7%9A%84%E5%B0%81%E8%A3%85)

插槽-默认插槽  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/04-%E6%8F%92%E6%A7%BD-%E9%BB%98%E8%AE%A4%E6%8F%92%E6%A7%BD/components/MyDialog.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#%E4%BA%94%E6%8F%92%E6%A7%BD-%E9%BB%98%E8%AE%A4%E6%8F%92%E6%A7%BD)

插槽-后备内容（默认值）[代码](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E6%8F%92%E6%A7%BD-%E5%90%8E%E5%A4%87%E5%86%85%E5%AE%B9/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#%E5%85%AD%E6%8F%92%E6%A7%BD-%E5%90%8E%E5%A4%87%E5%86%85%E5%AE%B9%E9%BB%98%E8%AE%A4%E5%80%BC)

插槽-具名插槽  [代码](https://github.com/biji-ziliao/vue2-biji/tree/master/05-%E5%9F%BA%E7%A1%80/06-%E6%8F%92%E6%A7%BD-%E5%85%B7%E5%90%8D%E6%8F%92%E6%A7%BD)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#%E4%B8%83%E6%8F%92%E6%A7%BD-%E5%85%B7%E5%90%8D%E6%8F%92%E6%A7%BD)

作用域插槽  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/07-%E6%8F%92%E6%A7%BD-%E4%BD%9C%E7%94%A8%E5%9F%9F%E6%8F%92%E6%A7%BD/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#%E5%85%AB%E4%BD%9C%E7%94%A8%E5%9F%9F%E6%8F%92%E6%A7%BD)

### 综合案例 - 商品列表-MyTag组件抽离

1. **my-tag 标签组件封装**

 (1) 双击显示输入框，输入框获取焦点

 (2) 失去焦点，隐藏输入框

 (3) 回显标签信息

 (4) 内容修改，回车 → 修改标签信息

1. **my-table 表格组件封装**

 (1) 动态传递表格数据渲染

 (2) 表头支持用户自定义

 (3) 主体支持用户自定义

my-tag组件封装-创建组件  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/07-%E6%8F%92%E6%A7%BD-%E4%BD%9C%E7%94%A8%E5%9F%9F%E6%8F%92%E6%A7%BD/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#3my-tag%E7%BB%84%E4%BB%B6%E5%B0%81%E8%A3%85-%E5%88%9B%E5%BB%BA%E7%BB%84%E4%BB%B6)

MyTag组件控制显示隐藏  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/07-%E6%8F%92%E6%A7%BD-%E4%BD%9C%E7%94%A8%E5%9F%9F%E6%8F%92%E6%A7%BD/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B-mytag%E7%BB%84%E4%BB%B6%E6%8E%A7%E5%88%B6%E6%98%BE%E7%A4%BA%E9%9A%90%E8%97%8F)

MyTag组件进行v-model绑定  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/07-%E6%8F%92%E6%A7%BD-%E4%BD%9C%E7%94%A8%E5%9F%9F%E6%8F%92%E6%A7%BD/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E4%B8%80%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B-mytag%E7%BB%84%E4%BB%B6%E8%BF%9B%E8%A1%8Cv-model%E7%BB%91%E5%AE%9A)

封装MyTable组件-动态渲染数据  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/07-%E6%8F%92%E6%A7%BD-%E4%BD%9C%E7%94%A8%E5%9F%9F%E6%8F%92%E6%A7%BD/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E4%BA%8C%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B-%E5%B0%81%E8%A3%85mytable%E7%BB%84%E4%BB%B6-%E5%8A%A8%E6%80%81%E6%B8%B2%E6%9F%93%E6%95%B0%E6%8D%AE)

封装MyTable组件-自定义结构  [代码](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/07-%E6%8F%92%E6%A7%BD-%E4%BD%9C%E7%94%A8%E5%9F%9F%E6%8F%92%E6%A7%BD/App.vue)     [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E4%B8%89%E7%BB%BC%E5%90%88%E6%A1%88%E4%BE%8B-%E5%B0%81%E8%A3%85mytable%E7%BB%84%E4%BB%B6-%E8%87%AA%E5%AE%9A%E4%B9%89%E7%BB%93%E6%9E%84)

单页应用程序介绍   [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E5%9B%9B%E5%8D%95%E9%A1%B5%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F%E4%BB%8B%E7%BB%8D)

### 路由介绍   [笔记](https://github.com/biji-ziliao/vue2-biji/blob/master/05-%E5%9F%BA%E7%A1%80/05-%E7%AC%94%E8%AE%B0.md#%E5%8D%81%E4%BA%94%E8%B7%AF%E7%94%B1%E4%BB%8B%E7%BB%8D)
