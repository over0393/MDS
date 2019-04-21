독하게 시작하는 C
=

### 기계어

소스코드(High Level 언어)<br>
l<br>
l   - 번역(Compiler)<br>
v<br>
오브젝트파일(.obj)<br>
l<br>
l   - 링크(Linker)<br>
v<br>
실행파일(.exe)

### 파일의 종류
.c 파일 - 정의<br>
.h 파일 - 선언

### 형식
```C
#include <stdio.h>

int main(void)
{
}
```
`#include<>` = 전처리기. 컴파일 전처리기<br><br>

ㅣ `int` = 반환형식<br>
ㅣ `main` = 함수명<br>
ㅣ `(void)` = 매개변수<br>
ㅣ<br>
함수 + 선언 정의<br><br>

`{}` = 변위 Block Scope. Body<br>
`item;` = 항<br>
`item; item; item;` = 구문<br>
`int main(void) { item; item; item; }` = 함수<br><br>

### 
C언어에서의 프로그래밍은 절차지향적 프로그래밍으로<br>
함수 내부의 구문에 존재하는 항을 상단부터 순차적으로 진행한다.

### 함수의 호출
`main()` = 호출자<br>
`printf()` = 피호출자<br>
호출자 함수는 피호출자 함수를 호출하여 사용함.<br>
이때, 호출자 함수에서는 피호출자 `printf`의 `()` 부분에 들어갈 매개변수에는 초깃값(실인수)를 입력해야된다.<br>
`printf("Hello, World!\n");`에서 `"Hello, World!\n"`는 매개변수의 초깃값이며 예시의 내용은 문자배열(문자열)이다.
