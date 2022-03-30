# Commit 基础格式

## 分类

|Type|Description|
|:-|:-|
|feat|A new feature|
|fix|A bug fix|
|docs|Documentation only changes|
|style|Changes that do not affect hte meaning of the code (white-space, formatting, missing semi-colons, etc)|
|refactor|A code change that neither fixes a bug nor adds a feature|
|perf|A code change that improves performance|
|test|Adding missing tests or correcting existing tests|
|build|Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)|
|ci|Changes to our CI configuration files and scripts (example scopes: Travis, Circle, Jenkins)|
|chore|Other changes that don't modify src or test files|
|revert|Reverts a previous commit|

## 格式

```
{type}({scope}): simple message

commit detail

BREAKING CHANGE: ......

Closes #1234
Closes #1235
```