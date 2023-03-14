# Make_Program_Language_Memo
프로그램 언어 만들기 메모장  
생각나는거 대로 써보는 메모장이다.  

<br>

# 해야 할것

- C, C++, C#와 같은 컴파일러 분석 및 제작
- java, python, ruby 같은 인터프리터 분석 및 제작
- markdown, mermaid, HTML, 수학식 만들기 등등 원리 분석


# 만들 목록

- Math Programming
- 논리 사건 Programming > 작가전용 프로그래밍 만들기
- \- programming
- 한글 프로그래밍

<br>

# 한글 프로그래밍

만약 ( ) 이라면, ( ) 하라.  
( )를 3번 반복하라.  

if ( a == 1 ) Console.WriteLine("WOW");  
만약 (ㅁ == 1 ) 콘솔.띄어쓰기("와우");
만약 ( ㅁ == 1 ) 이라면, 콘솔에 "와우"를 띄어 써라.

print "안녕하세요"
print "반갑습니다"
print "박주형 이라고 합니다"

상수 ㅁ = 1


This looks Beautiful. ( S V S.C )
이거 예뻐 보인다. ( S S.C V )
That ice cream was very delicious. ( S V S.C )
저 아이스크림은 매우 맛있었다. ( S S.C V ) ( S는 S.C하다(V) )
I ate the ramyeon at lunch ( S V O )
나는 점심에 라면을 먹었다. ( S O V ) (S는 O(을)를 V하다)
Could you suggest me a restaurant around here? ( S V I.O D.O )
(S I.O D.O V ) (S는 I.O에게 D.O를 V하다)
익

a is 10
ㅁ은 10이다.
a + b
a plus b
ㅁ 더하기 ㄴ

부레[ㄴ]
아이스 크림
우리의 이름은 무엇인가

while(a <= 1){
    a = a + 1;
}

반복(a <= 1){
    a = a + 1;
}

void A(){
    int a = 0;
    return a;
}

(a <= 1)까지 반복하라.
Repeat until (a <= 1)
while (a <= 1)
(ㅁ <= 1 )부터 반복하라
(ㅁ <= 1 )까지 반복하라

{
    //실행내용
} 를 (ㅁ < 10 )까지 반복


(ㅁ < 10 )까지 {
    //실행내용
}를 반복

(ㅁ < 10 )까지 반복 {
    //실행내용
}

(a <= 1)까지 (a + 1)을 반복합니다.
Repeat (a + 1) until (a <= 1).
반복하라 ~까지 {}을


Repeat until (a+1), (a <= 1).
(a+1), (a <= 1)까지 반복합니다.

 "사진1"에 "사과 사진"을 띄어라.

콘솔에 1 부터 10까지 순서대로 출력

ThereIsAFire() <- There is a Fire
fire, Fire : 불, 불
불이 있다. -> 불이있다. -> 불이_있다.
EventHandler() <- Event Handler
이벤트헨들러() , 이벤트_핸들러(), 이벤트 헨들러()
Calculrate() <- Calculrate
DoSomething() <- Do Something


콘솔에 1~10까지 순서대로 출력
콘솔에 1~10 까지 순서대로 출력
콘솔에 1 ~ 10 까지 순서대로 출력
콘솔에 1부터10까지 순서대로 출력
콘솔에 1부터10 까지 순서대로 출력
콘솔에 1 부터 10 까지 순서대로 출력

콘솔에 "Hello, World!" 출력
콘솔에"Hello, World!"출력
콘솔에 Hello, World! 출력
콘솔에  Hello, World! 출력

<br>

# 기본 지식

## 영어와 한글의 차이

- 영어
  - 축약이 쉽다. (PMP : Phase Measuring Profilometry)
  - 단락 구분이 쉽다. ( Apple is delicious)
- 한글
  - 띄어쓰기가 중요하다. (띄어쓰기만으로 구분 가능) 
    - (띄어쓰기만으로 구분가능) (o)
    - (띄어쓰기만으로구분가능) (x)
    - Action action = new Action(); (이런거 불가능)
    - ThereIsAFire -> There Is A Fire (구분가능)
    - 저기에불이있다. (구분 어려움)
  - 동작을 맨 뒤에 서술한다. (동사가 마지막)
    - 한국어는 마지막까지 들어야 한다.
  - 보조설명이 간단하고 다양하다.
    - 콘솔 사용
    - 콘솔을 사용
    - 콘솔을 사용한다
    - 콘솔을 사용하자
    - 콘솔을 사용함
    - 콘솔을 사용한다.
    - 콘솔을(를) 사용한다.

<br><br>

# 기본 형식


## Hellow, World!

- Hello, World!를 출력하는 소스는 다음과 같다.
  ```cs
  콘솔을 사용한다
  
  콘솔에 Hello, World! 출력
  ```
  ```cs
  콘솔을 사용
  
  콘솔에 Hello, World! 출력
  ```
- 콘솔을 생략할 수 있다.
  ```cs
  콘솔 생략하여 사용

  Hello, World! 출력
  ```
- 다른 출력 기능과 혼동방지 가능( 기본 기능 부여 )
  ```cs
  기본적으로 콘솔을 생략하여 사용

  Hello, World! 출력
  ```
- 이때 `기본적으로 콘솔을 생략하여 사용`을 다양하게 변형할 수 있다.
  - `기본적으로 콘솔을 생략하여 사용한다.`
  - `기본적으로 콘솔을 생략하여 사용`
  - `콘솔을 기본적으로 생략하여 사용`
  - `콘솔을 생략하여 사용 (기본적으로)`
  - `콘솔을 생략하여 사용 (기본적)`
  - `콘솔을 생략 사용 (기본적)`
  - `콘솔 기본적 생략 사용`
  - `기본적 생략 사용 : 콘솔`
  - `기본적 생략 사용 (콘솔)`
- 사용이라는 동사 이후에는 쓰레기 취급 또는 특수문자가 올 땐 빈 형식에 대입

## Hellow, World!를 나타내는 다양한 방법 모음

- Hello, World! 정석 출력
  ```cs
  콘솔을 사용한다.
  
  콘솔에 문장 "Hello, World!"를 출력한다.
  ```
- Hello, World! 생략 출력
  ```cs
  콘솔을 사용한다.
  콘솔을 사용한다
  콘솔을 사용.
  콘솔을 사용
  콘솔 사용
  
  콘솔에 문장 "Hello, World!"를 출력한다.
  콘솔에 문장"Hello, World!"를 출력한다.
  콘솔에 "Hello, World!"를 출력한다.
  콘솔에 "Hello, World!"를 출력한다
  콘솔에 "Hello, World!"를 출력
  콘솔에 "Hello, World!" 출력
  콘솔에 Hello, World! 출력
  콘솔, Hello, World! 출력
  ```
- Hello, World! 확장 출력
  ```cs
  콘솔을 사용한다.
  
  콘솔에 문장 "Hello, World!"를 출력한다.
  ```
  ```
  
  
- 구현 예상 코딩

```cs
콘솔을 생략해서 사용

1~10까지 순서대로 출력
// 12345678910
```

```cs
콘솔을 생략해서 사용

1~45사이 숫자로 난수를 8번 출력 //1 7 35 30 17 22 21 40 
8번 1~45사이 숫자로 난수를 출력 //
```

```cs
콘솔 생략 사용

ㅁ = 10, ㄴ = 20
ㄷ = ㅁ + ㄴ
ㄷ 값 출력
```

```cs
콘솔 생략 사용

변수 ㅁ = 0
{
  ㅁ++
  ㅁ 출력 후 다음줄
}을 무한 반복
```


```cs

```


## Math Programming

- Math Programming은 수학적인 계산을 프로그래밍으로 활용하는 언어이다.
- 각종 수학적 연산을 프로그래밍 할 수 있다.
- 각종 공식과 더불어 각종 상수를 제안 받을 수 있다.

```cs
k_1
integral
sigma
```



# 프로그래밍 전용 엑셀 툴

- 프로그래밍을 활용하면서 자료 및 문서를 만든는 툴


### 활용 예시

- 다음 문서의 리뷰 뒷부분을 지우고 싶을 때
  ```
  ## 목표 (문서를 분석하여 업데이트 하겠습니다.)
  - [x] [Dockerfile **개발 방법 리뷰**](http://wish.mirero.co.kr/mirero/project/mls/1.0/h18-mirero-mls10-rd/mls-application/-/issues/2133#note_402936)
    - [x] [Docker in Visual Studio Code](https://code.visualstudio.com/docs/containers/overview) 리뷰 (http://wish.mirero.co.kr/mirero/education/newface-group/newface/juhyung.park/-/issues/23#note_428472)
    - [x] [Docker - Dockerfile 작성 / Build (이미지 제작)](https://blog.d0ngd0nge.xyz/docker-dockerfile-write/) 리뷰 (http://wish.mirero.co.kr/mirero/education/newface-group/newface/juhyung.park/-/issues/23#note_428587)
    - [x] [DockerDocs - docker build](https://docs.docker.com/engine/reference/commandline/build/) 리뷰 (http://wish.mirero.co.kr/mirero/education/newface-group/newface/juhyung.park/-/issues/23#note_428767)
  - [ ] docker base image를 Dockerfile 활용하여 **개발**
    - [ ] [Dockerfile Build with Visual Studio Code](http://wish.mirero.co.kr/mirero/project/mls/1.0/h18-mirero-mls10-rd/mls-application/-/issues/2133#note_404113)
    - [ ] mirero/adc40:cuda11.3.0-cudnn8-devel-ubuntu20.04-2 설치 확인
  - [ ] docker image를 **docker hub에 업로드**
  - [ ] dockerfile 개발 - **ADC 프로파일 dockerfile 분석**
  - [ ] vscode git 사용 시 id/pass 저장 방법 (ubuntu) 분석
  ```
- CODE에 다음과 같이 기입한다.
  - FIND " 리뷰" While( Next != ENTER ) Del
  - FIND " 리뷰" Del.AT(ENTER)
    ```bash
    FIND
     리뷰
    Del.AT(ENTER)

    # or
    \f
     리뷰
    \d.at(ENTER)
    ```
- 다음과 같이 변환된다.
  ```
  ## 목표 (문서를 분석하여 업데이트 하겠습니다.)
  - [x] [Dockerfile **개발 방법 리뷰**](http://wish.mirero.co.kr/mirero/project/mls/1.0/h18-mirero-mls10-rd/mls-application/-/issues/2133#note_402936)
    - [x] [Docker in Visual Studio Code](https://code.visualstudio.com/docs/containers/overview) 리뷰
    - [x] [Docker - Dockerfile 작성 / Build (이미지 제작)](https://blog.d0ngd0nge.xyz/docker-dockerfile-write/) 리뷰
    - [x] [DockerDocs - docker build](https://docs.docker.com/engine/reference/commandline/build/) 리뷰
  - [ ] docker base image를 Dockerfile 활용하여 **개발**
    - [ ] [Dockerfile Build with Visual Studio Code](http://wish.mirero.co.kr/mirero/project/mls/1.0/h18-mirero-mls10-rd/mls-application/-/issues/2133#note_404113)
    - [ ] mirero/adc40:cuda11.3.0-cudnn8-devel-ubuntu20.04-2 설치 확인
  - [ ] docker image를 **docker hub에 업로드**
  - [ ] dockerfile 개발 - **ADC 프로파일 dockerfile 분석**
  - [ ] vscode git 사용 시 id/pass 저장 방법 (ubuntu) 분석
  ```
- 다음과 같은 일을 간단히 구축할 수 있어야 한다.
  - "mirero"가 기입된 링크 앞뒤 () 및 내용 삭제
  - \[x] > [ ]
  ```bash
  [x]
  >
  [ ]
  ```

### 활용법

- 바꾸기 (예 \[x]를 [ ]로 변환)
  ```bash
  [x]
  />
  [ ]
  ```
- 특정 문자에서 부터 특정 문자까지 지우기
  ```bash
  단어
  /d.at
  단어2
  ```
- 특정 문자 지우기
  ```bash
  단어
  /bl # backspace 를 길이 l 만큼 실행
  ```
- 특정 단어 앞앞에 2개 지우기
  ```bash
  단어
  /l2
  /b2
  ```
- 특정키 실행
  ```bash
  /'LEFT'/'RIGHT'/'UP'/'DOWN'
  ```


# 한글 OS

- 처음부터 끝까지 인공지능 전부 활용
- 코딩 공유 : 원하는 기능을 지원하는 코딩을 바로 받아서 사용해볼 수 있다.
- 바로 눈에 보일 수 있는 코딩 (이미지코딩 등등)
- 틀이 없는 구조 : 0,0~다시 0,0 (무한순환 화면)


# 한글 프로그래밍 

ㅁ만약
ㄱ만약
자음과 모음이 만나 기본형이 완성이 된다
자음 다음 모음
ㅅ시작은 자음 마지막은 모음이 커버가느으
그건 어려울 듯하다
ㅅ시작만 자음으로 구성하기 쉽다
ㅁ만약
이렇게 구성하는순간
변수는 완전한 형태의 단어
변수와 특수조건문자를 결정짓는 간단한 방법은
자음을 활용하는 것
ㅂㅈㄷㄱㅅㅁㄴㅇㅎㅋㅌㅊㅍ
생각해보니 먼저 모음이 들어와도 구성 가능하다
ㅛㅕㅑㅐㅔㅗㅓㅏㅣㅠㅜㅡ
함수의 사용법
한글의 장점은 한번에 가능하다는 점
동사가 나중에 나오는 만큼, 마지막이 중요 하다
마지막이 결정되어 있다.
한글는 구분해 놓지 않으면 헷갈린다.
ㅎ함수
ㅂ변수
ㅈ조건
빨간 오토바이 -> 정보 대입
오토바이를 세워줘 -> 함수 세워줘
오토바이를 세워줘/멈춰줘
멈춰줘는 속도가 10이상일경우 세워줘와 같다
조건문
그리그, 또는, 아니면, 같으면
우리나라의
울나라의
울 뒤에 단어가 붙으면 우리와 같다
한글의 본질
프로그래밍의 본질
오토바이는 탈것이다. (인터페이스 주입)
ㅎ숫자를 주입하면 : 오토바이, 탈것(인터페이스)
   만약 연료기반 탈 것이라면, 연료에 숫자 추가
ㅎ
ㅈ만약 오토바이의 연료 < 10이라면
   실행내용
ㅈ
ㅗ #region 아니면 주석
ㅜ
ㅓㅏ 주석
ㅕ ㅑ
ㅛ
ㅠ
ㅢ
ㅔㅖㅐ
사과 ㅇ 수박
사과 ㅁ 수박