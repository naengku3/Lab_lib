# Lab_lib

C언어로 가감승제를 할 수 있는 mymath.lib를 만들고
이를 이용하여 22와 33을 더하는 예제를 구현하시오.

위를 하는방법은, 
1. visual stdio를 실행하고, tool에서 개발자 명령 프롬프트로 들어간다.
2. 그러면 dos환경에서, notepad my.c 명령어를 통해 my.c파일을 코드를 적어 만들어준다. 더하는 함수는 add()로 하였다.
3. 그 후 가감승제를 할 라이브러리를 만들어 줄 것인데, 먼저 위의 notepad명령으로 math.c를 만들어 주었다.
4. 거기에 add(), subtract()등의 가감승제 함수들을 코딩해주었다.
5. 이제 dir 명령어로 디렉터리의 파일들을 보면 my.c, math.c 가 있을것이다.
6. cl /c *.c 명령어를 통해 모든 .c 파일들을 컴파일 해준다.
7. 그러면 각각의 .obj 파일들이 생겼을것이다.
8. lib /OUT:mymath.lib math.obj 명령어로 math.obj 파일을 라이브러리로 만들어준다.
9. 이제 link my mymath.lib 명령어로 my에 라이브러리를 링크해준다.
10. 그러면 명령행에 my나 my.exe를 적게되면 55가 출력이된다.
