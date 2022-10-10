# 全部书籍
```dataview
table type as 类型, rate as 个人评分, word_count as 字数, read_times as 阅读次数
where file_type="book_summary" and file.folder!="Template" 
sort rate desc
```

# 短篇小说

```dataview
table type as 类型, rate as 个人评分, word_count as 字数, read_times as 阅读次数
from #短篇小说 
sort rate desc
```
