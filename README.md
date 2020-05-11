# MaxMSP_If_Objects

### 左インレットと右インレットを比較するifオブジェクト

+ 左インレットから入力される値:f1
+ 右インレットから入力される値:f2

```
If($f1 < -140.0 & $f2 > 10.0) then $f2 else 0.0
```

f1 < -140.0 且 つf2 > 10.0の場合は
f2を出力 
それ以外の場合は0.0を出力する
という意味です。
![if object](https://github.com/hiwasawa0715/MaxMSP_If_Objects/blob/master/img/ifobjpct.png "サンプル")
