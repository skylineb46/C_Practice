# C_Practice
## week4
- 아스키 코드
- 증감연산자

### 아스키코드
문자는 컴퓨터에게 숫자로 인식된다.  

```c
#include <stdio.h>
int main(void)
{
  char code = 'A';
  printf("%d %d %d \n", code, code + 1, code + 2); // 65 66 67이 출력된다.
  printf("%c %c %c \n", code, code + 1, code + 2); // A B C가 출력된다.
  return 0;
}
````

### 증감연산자
++ -- 로 구성되어있다.  
x++은 x = x + 1로 표현할 수 있다.  
x++과 ++x의 차이에 주의하자.  
```c
#include <stdio.h>
int main(void)
{
  int x=10, y=10;
  printf("x=%d\n", x);
  printf("++x의 값=%d\n", ++x);
  printf("x=%d\n\n", x);
  printf("y=%d\n", y);
  printf("y++의 값=%d\n", y++);
  printf("y=%d\n", y);
  return 0;
}
```

