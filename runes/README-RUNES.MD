# RUNES PROTOCOL

## 铸造 (MINT)

![](./runes-mint-process.png)

### 流程
- 1.铸造的RuneId
- 2.铸造数量（一般固定的，因为etch时已设定，不可修改）
- 3.重复次数，以来server发起
- 4.签名，后端Rust对ScriptPubKey编码，客户端签名
- 5.Server负责广播交易，和监听铸造状态



