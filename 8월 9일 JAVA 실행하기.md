# JAVA



###  환경설정

JAVA_HOME : jdk의 설치 폴더 경로

path : jdk의 bin디렉토리 경로



----------------

### 자바실행 ( java로 프로그램 실행하기 위한 순서)

**[컴파일]**

> 자바언어로 작성된 명령어를 컴퓨터에서 실행하기 위해서 컴퓨터가 이해할 수 있는 명령어로 변경



**[인터프리터]**

> 컴파일러로 번역한 명령어를 한 줄씩 번역해서 자바에서 실행
>
> 중간에 오류가 있어도 오류가 발생하기 전까지 실행

  



1) 자바언어로 소스 코드를 작성

* 자바 명령어로 구성

* `.java` -> 확장자

* 소스파일은 소스파일 내부에서 선언된 클래스명과 동일한 이름으로 작성

  ex) 클래스명 -> `Hello`

  ​       파일명 : `Hello.java`

  



2. 자바소스 파일을 컴파일

* 컴파일러 : `javac.exe`

   `javac 자바소스파일명.java`

   `javac Hello.java`

  

3. 컴파일의 결과 파일이 생성

​        cdm -> dir/w 로 확인

* `.class` (클래스파일, 바이트코드(byte code))
* `Hello.class`



4. 자바실행

* 인터프리터 : `java.exe`
  * java 컴파일결과로 생성된 클래스파일의 파일명
  * `java Hello`











