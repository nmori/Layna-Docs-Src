# 正規表現

!!! Info "対象の正義表現"
    [Visual C# でつかえる正規表現](https://learn.microsoft.com/ja-jp/dotnet/api/system.text.regularexpressions.regex.ismatch?view=net-7.0#system-text-regularexpressions-regex-ismatch(system-string-system-string-system-text-regularexpressions-regexoptions))が利用可能です
 
## 正規表現 例

|タグ|反応例|
|----|------|
|(Mr\.? \|Mrs\.? \|Miss \|Ms\.? )| `Mr` `Mr.` `Mrs` `Mrs. ` `Miss ` `Ms ` `Ms. `|
|[0-9]| `0` `1` `2`  ... `9` |
|^[ぁ-んー]+$| `あ` `い` ... `ん`|
|^[ァ-ンヴー]+$| `ア` `イ` ...|
