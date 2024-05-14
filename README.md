# Not A Protocol

這不是一個協議，人類可讀，使用方便，性能優異，數據壓縮。靈感來源於yaml、md，但更注重數據傳輸。

[not-a-protocol](https://github.com/lizongying/not-a-protocol)

## 使用

* 包括配置和數據
* 支持命名空間（組織/資源）

### 配置

後綴名為“.nap”
如：

```
組名【字符串】
    標題【字符串】
    別名【字符串】
    圖標【列表｜資源】
    鏈接【列表｜資源】
```

* 縮進符號表示屬性

### 數據

後綴名為“.na”
如：

```
我的視頻
    · CCTV1
      CCTV1 綜合

      https://tv.cctv.com/live/cctv1

    · CCTV2
      CCTV2 財經

      https://tv.cctv.com/live/cctv2
```

* · * - +表示列表開始
* 列表後面可以有空行，但最多只能有一行

### 數據類型

可以多種格式，中間以｜管道符分割，如【字符串｜zip｜aes】、【字符串｜掛六十四】等
支持中文等任意unicode編碼文字

* 列表
* 字符串
* 數字
    * int
    * int32
    * int64
    * uint
    * int32
    * int64
* ···
* 其他數據類型
    * 手機號碼
    * 資源
    * 鏈接
    * json
    * xml
    * toml
    * yaml
    * js
    * javascript
    * java
    * php
    * go
    * golang
    * ···
* 自定義
