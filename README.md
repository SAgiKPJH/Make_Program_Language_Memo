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
  ```
  콘솔을 생략해서 사용
  
  콘솔에 1~10까지 순서대로 출력
  ```
