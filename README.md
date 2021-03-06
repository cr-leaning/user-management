# user-management

https://github.com/google/styleguide

## 主な機能
- ユーザー（社員）の基本的な情報を保持します。

## 概要
|Category | | Category | | Category | |
| --- | --- | --- | --- |
|API | :white_check_mark: | Database(R/W) | | Database(R/O) | :white_check_mark: |
|External API | | Storage | | Migration SQL | :white_check_mark: |
|Scheduler | | Batch Job | | Consumer | |
|Producer | | Unit Test | :white_check_mark: | Functional Test | |

## 使用技術
|Category | |
|---|---|
| Language | Java 14 |
| DB(RDB) | mariaDB |
| Test FW | JUnit5 |
| DB(UT) | h2DB |
| Exec Env | docker |
