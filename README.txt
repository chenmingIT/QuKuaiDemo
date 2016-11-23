测试文档第二章 交易接口的2.1  查询所有交易

// Request
    curl -X POST --data '{"jsonrpc": "2.0", "method": "tx_getTransactions", "params": [{"from": 1, "to": 2}], "id": 71}'
