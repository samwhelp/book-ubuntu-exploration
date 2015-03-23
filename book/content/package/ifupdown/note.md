
# ifupdown note

## 案例討論

* [如何刪除非.txt檔](http://www.ubuntu-tw.org/modules/newbb/viewtopic.php?post_id=335000#forumpost335000)

## 探討文章

* [Ubuntu Linux 用 xargs 指令處理大量檔案](http://www.arthurtoday.com/2015/03/ubunut-linux-xargs-command-examples.html)
* [Ubunut Linux 利用 cp 指令和 {} 符號複製檔案](http://www.arthurtoday.com/2015/03/ubunut-linux-copy-files-with-cp-amd-curly-braces.html)

## 鳥哥的私房菜

* 第七章、Linux 檔案與目錄管理 / 5. 指令與檔案的搜尋：/ [find](http://linux.vbird.org/linux_basic/0220filemanager.php#find)

## 指令範例

```
$ find . ! -name '*.txt'
```

```
$ find . ! -name '*.txt' -type f -exec rm '{}' \;
```
