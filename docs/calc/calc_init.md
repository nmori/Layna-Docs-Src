# 条件文

!!! Info "対象の条件文"
    [Visual C# でつかえる計算式](https://learn.microsoft.com/ja-jp/dotnet/api/system.data.datacolumn.expression?view=net-7.0)が利用可能です
 
## 計算式 例

|計算式|意味|
|----|------|
|Len('{#.last.comment}')>100|コメント文字数が100文字以上|
|SUBSTRING('{#.last.comment}',1,1) LIKE 'は'|「は」から始まるコメント|
|{live.time.countdown}<=0|カウントダウン時間を迎えたかどうか|
