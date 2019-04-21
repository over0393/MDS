독하게 시작하는 C
=

#### 기계어

소스코드(High Level 언어)<br>
l<br>
l   - 번역(Compiler)<br>
v<br>
오브젝트파일(.obj)<br>
l<br>
l   - 링크(Linker)<br>
v<br>
실행파일(.exe)

#### 파일의 종류
.c 파일 - 정의<br>
.h 파일 - 선언

#### 형식
```C
#include <stdio.h>

int main(void)
{
}
```
'#include<>' = 전처리기. 컴파일 전처리기<br><br>

ㅣ 'int' = 반환형식<br>
ㅣ 'main' = 함수명<br>
ㅣ '(void)' = 매개변수<br>
ㅣ<br>
함수+선언 정의<br><br>

'{}' = 변위 Block Scope. Body<br>
'item;' = 항<br>
'item; item; item;' = 구문<br>
'int main(void) { item; item; item; }' = 함수<br><br>
