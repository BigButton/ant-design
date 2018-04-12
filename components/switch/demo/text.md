---
order: 2
title:
  zh-CN: 文字和图标
  en-US: Text & icon
---

## zh-CN

带有文字和图标。

## en-US

With text and icon.

````jsx
import { Switch, Icon } from 'antd';

ReactDOM.render(
  <div>
    <Switch checkedChildren="正序" unCheckedChildren="倒序" defaultChecked />
    <br />
    <Switch checkedChildren="1" unCheckedChildren="1" />
    <br />
    <Switch checkedChildren={<Icon type="check" />} unCheckedChildren={<Icon type="cross" />} defaultChecked />
  </div>
, mountNode);
````
