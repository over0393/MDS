﻿마크다운
=
해당 파일은 개인 저장용으로 작성되는 파일임을 주의해주세요.

목차
-
- [마크다운?](#1-마크다운?)
- [마크다운 사용문법(syntax)](#2-마크다운-사용-문법-Syntax) 
	- [제목 Headers](#21-제목-Headers)
	- [목록 List](#22-목록-List)
- [참고문서](#3-참고문서)


# 1. 마크다운?

# 2. 마크다운 사용 문법 Syntax
마크다운 사용법에 관한 내용입니다.<br>
상단부의 내용은 ``` code ```로 
## 2.1. 제목 Headers

- 제목

Header 1
==
```
H1
==
```

- 부제목

Header2
-
```
H2
-
```
해당 부분에서 길이는 상관 없이 하나 이상으로만 작성해도 Header로 작성됩니다.<br>
단, 상단에 Text가 존재할 시 해당 Text 모두 Header로 작성되며 이후 작성되는 '목록 List'의 바로 하단에 붙여 작성할 시 Text로 적용됩니다.<br>
이 부분들은 '제목'과 '부제목' 공통적인 사항입니다.<br>

- 글머리
# H1
## H2
### H3
#### H4
##### H5
###### H6
####### H7
```
# H1
## H2
### H3
#### H4
##### H5
###### H6
####### H7
```
H1 ~ H6까지 지원하며 이후로는 text취급되어 작성됩니다.<br>

## 2.2. 목록 List

- 순서가 필요한 목록

1. List 1
1. List 2
1. List 3
	1. List 3-1
	1. List 3-2
1. List 4

```
1. List 1
1. List 2
1. List 3
	1. List 3-1
	1. List 3-2
1. List 4
```

- 순서가 필요하지 않은 목록

- List 1
	- List 1-1
	* List 1-2
	+ List 1-3

```
- List 1
	- List 1-1
	* List 1-2
	+ List 1-3
```



# 3. 참고문서
- [Heropy님의 'MarkDown 사용법 총정리'](https://heropy.blog/2017/09/30/markdown/)
- [ihoneymon님의 '[공통] 마크다운 markdown 작성법'](https://gist.github.com/ihoneymon/652be052a0727ad59601)
