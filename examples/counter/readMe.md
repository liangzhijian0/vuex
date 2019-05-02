#### getters
- 可以理解成store里面的computed属性

#### mutations
- 传入state作为参数，改变state里面的值
- 写法最特别，类似function

#### actions
- 对mutations作进一步操作，组件中通常调用的是actions，可处理异步逻辑
- 把commit，state作为参数传入

#### vue组件
- import mapGetters,mapActions等辅助