# 例外


## 顯示例外訊息並中斷執行

```shell
echo "Error!" 1>&2
exit 64
```


## 記錄例外訊息至 Log 檔案並中斷執行

```shell
echo "Error!" > logfile.log
exit 125
```

## 參考資料
* [linux - Raise error in a Bash script - Stack Overflow](https://stackoverflow.com/questions/30078281/raise-error-in-a-bash-script)
