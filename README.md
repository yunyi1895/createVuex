# createVuex
## 渐进的实现vuex的基本功能

### step1
   step1里面实现了一个Vuex的工厂函数，使用Vue.use()插件方法放入将new Vuex()储存的Vue的prototype里面，全局就可以获取和调用了。

### step2
   step2里面主要是给Vuex添加了commit方法来触发mutation改变state的数据

### step3
   step3里面主要是添加了createdGetters方法来监控数据的变化，返回getters对象。

### step4
   step4里面主要是给Vuex添加了dispatch方法来触发actions异步的处理数据，并且可以dispatch其他函数和commit其他函数。

### step5
   step5里面新增mapGetters和mapActions方法，可以方便的使用getters的数据和触发action