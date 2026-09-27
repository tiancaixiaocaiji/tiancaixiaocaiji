# C++函数

1. `cout << fixed << setprecision(n) << 变量;` —— 保留几位小数

2. `std::sort(a.begin(), a.end());` —— 排序（默认为升序）

3. `std::stoi(char类型变量);` —— 将 `char` 类型的数字转换为 `int`

4. 对于 `vector` 数组：
   - `a.push_back(元素)` 可将元素加入到 `a` 的末尾；
   - `a.insert(a.begin() + n, 元素)` 可将元素加入到 `a` 的 n 位置上；

5. `reverse(a.begin(), a.end());` —— 可将字符串翻转

6. 定义一个字符串 `a`：
   - `a.push_back()` 可在末尾添加元素；
   - `a.pop_back()` 可删除末尾元素
