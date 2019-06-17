# 路徑

## 目前路徑


```shell
current_dir=$(pwd)
echo "$current_dir"
```

```shell
BASEDIR=$(dirname "$0")
echo "$BASEDIR"
```


## 傳入變數

```shell
$0 : script_name    # Script 名稱
$1 : parameter 1    # 變數 1
$2 : parameter 2    # 變數 2
$3 : parameter 3    # 變數 3
```

```shell
./variable.sh var1 var2 var3
```

```shell
#!/bin/sh
echo "parameter 1: ${$1}"   # var1
echo "parameter 2: ${$2}"   # var2
echo "parameter 3: ${$3}"   # var3
```
