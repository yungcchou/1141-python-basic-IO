# Python 常見錯誤類型

## `SyntaxError`
- 說明：語法錯誤
- 範例：`if True print("hi")`

## `IndentationError`
- 說明：縮排錯誤
- 範例：
  ```python
  def f():
  print("hi")
  ```

## `NameError`
- 說明：使用了未定義的變數或函式名稱
- 範例：`print(x)`

## `TypeError`
- 說明：型別不符
- 範例：`"5" + 3`

## `ValueError`
- 說明：資料型態正確但值不合法
- 範例：`int("abc")`

## `IndexError`
- 說明：索引超出序列範圍
- 範例：`[1,2,3][5]`

## `KeyError`
- 說明：字典中找不到指定鍵
- 範例：`{"a": 1}["b"]`

## `AttributeError`
- 說明：屬性或方法不存在
- 範例：`(5).append(3)`

## `ZeroDivisionError`
- 說明：除以零錯誤
- 範例：`10 / 0`

## `ImportError`
- 說明：模組匯入失敗（模組存在但匯入失敗）
- 範例：`from math import dontexist`

## `ModuleNotFoundError`
- 說明：模組不存在
- 範例：`import fake_module`
