Android在C/C++封装了许多好用的API，记录一下，方便阅读

### 1.android::base::Split 
分割字符串，用法
```C
std::vector<std::string> pieces = android::base::Split(entry, "=");
        if (pieces.size() == 2) {
            fn(pieces[0], pieces[1], in_qemu);
        } 
```
