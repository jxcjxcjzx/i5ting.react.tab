# i5ting.react.tab

用法

```
var TabItem  = require('./tab_item.jsx');
var Tab      = require('./tab.jsx');

var callback = function(key){

}

React.render(
  <Tab tab_changed={callback}>
    <TabItem title="tab说明" current>
      <p>tab说明</p>
    </TabItem>
    <TabItem title="'特性'">
      特性
    </TabItem>
    <TabItem title="开源协议">
      开源协议
    </TabItem>
    <TabItem title="源码">
      源码
    </TabItem>
    <TabItem title="张婷作品">
      <p>张婷作品</p>
    </TabItem>
  </Tab>
  ,
  document.getElementById('wrap1')
);
```