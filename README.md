# rmb

伟大的人民币

* 支持 `value`, `front`, `end`, `decimal`, `del` 五种特性
* `value` 是金额
* `front` 和 `end` 分别是前后缀
* `decimal` 是否显示角和分
* `del` 是否显示中划线

## Example

```
<jie-rmb value="100"></jie-rmb><br>
<jie-rmb front="￥" value="100"></jie-rmb><br>
<jie-rmb front="" end="元" value="100"></jie-rmb><br>
<jie-rmb decimal="false" value="100"></jie-rmb><br>
<jie-rmb del decimal="false" value="100.50"></jie-rmb><br>
<jie-rmb decimal="true" value="100"></jie-rmb><br>
<jie-rmb decimal="true" value="100.50"></jie-rmb><br>
<jie-rmb decimal="auto" value="100"></jie-rmb><br>
<jie-rmb decimal="auto" value="100.50"></jie-rmb><br>
<jie-rmb del value="100"></jie-rmb><br>
```
