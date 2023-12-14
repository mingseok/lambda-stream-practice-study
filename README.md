# lambda-stream-practice-study

람다, 스트림 문제 + 풀이 저장소


<br/>

## 🚀기간

- 일정 : 2023.12.14 ~ ing

- 매주 x요일 x시에 디스코드로 진행합니다.

    - 링크 : https://discord.gg/KC8deweW

<br/>

## ✏️참가 인원


| 김민석 | 이다원 | 조국현 | 전다빈
| --- | --- | --- | --- |
| [깃허브](https://github.com/mingseok) | [깃허브](https://github.com/dawonss) | [깃허브](https://github.com/epiphany1013) | [깃허브](https://github.com/BeenRepo) |



<br/>



### 🎯Rule

- 주단위로 각자 람다, 스트림 예제 3 ~ 5개를 만들어 온다.

### example

```java
문제) 
리스트의 모든 짝수를 선택하고 중복을 필터링을 하시오.


컬렉션) 
List<Integer> numbers = Arrays.asList(1, 2, 1, 3, 3, 2, 4);


정답) 
```java
List<Integer> numbers = Arrays.asList(1, 2, 1, 3, 3, 2, 4);
		numbers.stream()
		       .filter(i -> i % 2 == 0)
		       .distinct()
		       .forEach(System.out::println);
```

- 각 문제의 정답 코드는, 해당 파일 밑에 작성한다.

    - e.g.) 예시 링크 확인하기 : [📌링크](https://github.com/mingseok/lambda-stream-practice-study/blob/main/23.12_month/%EA%B9%80%EB%AF%BC%EC%84%9D/test.md)

- 자신의 문제에 대해 코드가 어떤식으로 돌아가는지에 대해서는 이해를 하고 깃허브에 올린다.

- 스터디 당일은 서로의 문제들을 풀어본다.

	- 서로의 문제를 풀면서, 모르는 부분이 생긴다면 해당 문제의 출제자에게 힌트를 구한다.

- 문제를 모두 클리어 했다면, 중요했던 부분들에 대해 서로 공유한다.

- 기록으로 남겨 두고 싶은 예제 등 자유로운 방식으로 이슈를 추가한다.



<br/><br/>


## 💬github 레포지토리 - issue 활용



`issue`의 기능은 간단합니다. 

모르는 내용, 공유하고 싶은 자료 등을 올리는 게시판입니다.

```
스터디 중 관련 질문
- 궁금한점
- 좋은 참고 자료
- 실수하기 쉬운 부분 공유
- 같이 알면 좋은 것들.
```
자유로운 게시판 느낌으로 생각해주시면 감사하겠습니다.


핵심은, 스터디 사이클에서 질문 & 답변을 한다는 것입니다.


많은 이용 부탁드립니다!

[📌issue 링크](https://github.com/mingseok/lambda-stream-practice-study/issues)




