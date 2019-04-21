C sharp 범용 코드
=

목차
-
- [String.Substring을 이용한 문자열 역순 변경](#-StringSubstring을-이용한-문자열-역순-변경)


### String.Substring을 이용한 문자열 역순 변경
```C#
String ReverseOrderString(string DefaultText)
{
    string tmptext;

    for (int i = DefaultText.Length; i > 0; i--)
        tmptext += DefaultText.Substring(i - 1, 1);
     
    return tmptext;
}
```

문자열을 받아 역순으로 저장한 값을 return하는 함수 작성
