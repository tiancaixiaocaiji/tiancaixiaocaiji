# unordered_map 和 set

## unordered_map

### 定义
`unordered_map<int, int> m;` 或 `unordered_map<string, int> m;` 等

### 插入数据
- `m.insert({3, 1})`
- `m[3] = 1`
- `m[3]++` —— 无需初始化

### 删除数据
`m.erase(3)`

### 查找数据
`m.count(3)` —— 返回 bool

**注意**：假如 `m[3] = 0`，使用 `m.count(3)` 返回的也是 `true`。

---

## set

基本相同，只是没有值，只能单纯判断是否存在这样的数据。
