# 條件判斷

## 判斷變數是否為空值


```shell
variable=""
if [ -z "$variable" ]
then
      echo "\$variable Is NULL"
else
      echo "\$variable is NOT NULL"
fi
```

## 判斷目錄是否存在

```shell
if [ -d "$DIRECTORY" ]; then
  # 目錄存在執行此 script
fi
```

```shell
if [ ! -d "$DIRECTORY" ]; then
  # 目錄不存在執行此 script
fi
```


## 判斷檔案是否存在


```shell
file_path="/my/file/path"
if [ -f "$file_path" ]
then
    # 檔案存在
	echo "$file_path found."
else
    # 檔案不存在
	echo "$file_path not found."
fi
```

## 參考資料
* [Bash shell find out if a variable has NULL value OR not - nixCraft](https://www.cyberciti.biz/faq/bash-shell-find-out-if-a-variable-has-null-value-or-not/)
* [unix - Check if a directory exists in a shell script - Stack Overflow](https://stackoverflow.com/questions/59838/check-if-a-directory-exists-in-a-shell-script)
* [Bash Shell: Check File Exists or Not - nixCraft](https://www.cyberciti.biz/faq/unix-linux-test-existence-of-file-in-bash/)
