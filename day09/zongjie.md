在javascript 里，全局或局部变量，只以function函数的花括号为基准。

元素的切换会影响到mouseout的范围，即使定义它的范围为一个固定的元素，但会因为它与内部子元素的切换受到影响，这时使用mouseleave 事件只会在绑定它的元素上被调用，而不会在后代节点上被触发。

盒子居中：宽高，父元素的一半减去子元素的一半。
  用绝对定位，定位相对于最近的祖先元素
    top: 50%;
    left: 50%;
  继续偏移自身的一半
    margin-left: -300px;  //这是它自身的一半
    margin-top: -150px;


表单不能返回服务器的数据，ajax不能上传文件。但是各自都有应对方法，写回调函数、formdata..
