### explain

* required params
 

* optional params
    disabled: boolean --组件设置成灰色，但是方法中自己处理
    className:  string  -- 样式, 
    type: -- primary(蓝色框白底蓝字), default(蓝底白字), warning(橙色底白字)

* method
    onClick: function  -- 回调函数

### demo

```js

import { Footer } from '../../Common/main';

let topicLists =  [1, 3, 4, 6] 

<Footer>
    <Footer.Item
        type="primary"
        onClick={() => {}}></Footer.Item>
    <Footer.Item
        callback=""
        onClick={true}></Footer.Item>  
</Footer>

```  


### Author
If you encounter any questions, please call me. 
my mail address is 348560971@qq.com.
@ziran.liu