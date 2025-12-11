# Commit格式
```txt=
[Ttile] <Title>

[<Type>] <SubTitle>
- <Detail>

...
```
## Example
```txt=
[Title] SqlTool優化

[Feat] 新增VarChar屬性標記Model的VarChar屬性

[Feat] ExecuteSQL新增回傳ModelList
- 新增DataTable轉ModelList方法

[Perf] BulkUpdate新增交易保護

[Perf] 屬性相關資訊改用快取
- 新增ModelMetadata儲存Model屬性相關資訊，不用每次都解析

[Chore] 補充註解

[Test] 測試專案新增對應單元測試
```

## Type
|Type    |說明                   |
|--------|-----------------------|
|Feat    |新功能                 |
|Release |版本相關資訊            |
|Update  |套件升級等動作          |
|Fix     |修 bug                 |
|Perf    |效能提升               |
|Refactor|重構、刪無用程式碼      |
|Style   |格式、風格（不含邏輯）   |
|Docs    |文件                   |
|Test    |測試                   |
|Build   |建置與依賴設定          |
|Ci      |CI/CD                  |
|Chore   |其他雜項                |
|Security|安全性修補              |

## Title

## SubTitle

## Detail