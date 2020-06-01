# ledger
记录我的账单

# vscode 模板添加
> 设置=>用户代码判断=>ledger
> 此时会出现一个 `ledger.json`
> 添加一下内容

```
"ledger to record": {
		"prefix": "ledger_add",
		"body": [
			"$CURRENT_YEAR/$CURRENT_MONTH/$CURRENT_DATE * ",
			"	费用:		CNY "
			"	资产:		CNY "
		],
		"description": "Ledger add a count"
	}
```
