# 기초 CLI 명령어

> CLI : Command Line Interface
>
> GUI 환경인 윈도우와는 다른 인터페이스를 지닌다.

* ls : 현재 목록

  ```bash
  $ ls
  1.txt
  ```

* touch : 파일 만들기

  ```bash
  $ touch <파일명>
  $ touch README.md
  ```

* pwd : 현재 작업 디렉토리 출력 (print working directory)

  ```bash
  $ pwd
  /c/Users/lec/Desktop/실습1

* mkdir : 디렉토리 만들기 (make directory)

  ```bash
  $ mkdir test
  ```

* cd : 디렉토리 이동 (change directory)

  ```bash
  $ cd test
  ~/Desktop/실습1/test $ cd ..
  ~/Desktop/실습1 $ 
  ```

  * `..` : 상위 디렉토리
  * `.` : 현재 디렉토리
  
* cp:  파일복사 

  ```bash
  Usage: cp [OPTION]... [-T] SOURCE DEST
    or:  cp [OPTION]... SOURCE... DIRECTORY
    or:  cp [OPTION]... -t DIRECTORY SOURCE...
  Copy SOURCE to DEST, or multiple SOURCE(s) to DIRECTORY.
  $ cp xxx.md 새폴더 --> 새폴더에 xxx.md 파일 생성!
  ```

* mv: 파일 이동

  ```bash
  $ mv hi.txt a --> a 폴더에 hi.txt 이동!
  ```

* rm : 파일 제거 

  ```bash
  $ rm hi.txt --> hi.txt 제거!
  $ rm -r a --> a폴더 제거!
  
  ```

* cat: 파일내용 화면 출력 파일 생성

  ```bash
  $ cat hi.txt
  hello
  
  ```

* redirection : 화면에 출력되는 결과를 파일로 저장

  ```bash
  $ cat say.txt>hi.txt --> say.txt 의 내용을 hi.txt 로 저장
  $ cat say.txt hi.txt>bye.txt --> say.txt 와 hi.txt의 내용을 bye.txt로 저장
  ```

* alias : 자주 수행하는 명령어들을 쉽게 사용할수있도록 설정하는 명령어

  ```bash
  $ alias : 현재 alias 목록 출력
  $ alias new = 'command' : command를 실행하는 새 명령어 new 를 만듦
  	ex) $alias ls='ls-l' : ls를 실행하면 -l 옵션을 갖는 ls를 실행
  $ unalias new : new 라는 alias 를 해제
  ```

  
