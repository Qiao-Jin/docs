# getCommittee 方法

获取委员会成员。

## 所属合约

	NeoToken

## 调用示例

请求正文：

```
var result = Contract.Call(neoHash, "getCommittee", new object[] { });
```

响应正文：

```
{
	"type": "Array",
	"value": [{
		"type": "Struct",
		"value": [{
			"type": "ByteString",
			"value": "AkuBfvN/L8PUoz/jZoflktnzD\u002BJLPigYfcjxKzs7K4Oe"
		}, {
			"type": "Integer",
			"value": "0"
		}]
	}]
}
```

响应说明：

- Array类型：成功获取委员会成员。

- 其他：失败。