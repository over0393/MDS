C sharp ���� �ڵ�
=

����
-
- [String.Substring�� �̿��� ���ڿ� ���� ����](-String.Substring��-�̿���-���ڿ�-����-����)


- String.Substring�� �̿��� ���ڿ� ���� ����
```C#
String ReverseOrderString(string DefaultText)
{
    string tmptext;

    for (int i = DefaultText.Length; i > 0; i--)
        tmptext += DefaultText.Substring(i - 1, 1);
     
    return tmptext;
}
```

���ڿ��� �޾� �������� ������ ���� return�ϴ� �Լ� �ۼ�