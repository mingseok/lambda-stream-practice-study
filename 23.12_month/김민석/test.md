## e.g. 파일 입니다.


<br/>


## 문제 1)

리스트의 모든 짝수를 선택하고 중복을 필터링 하시오.

```java
List<Integer> numbers = Arrays.asList(1, 2, 1, 3, 3, 2, 4);
```


<br/><br/>

## 문제 2)

ArrayList에서 removeIf “w” 로 되어 있는 것을 빼고 출력해주세요.

```java
List<String> name = new ArrayList<>();
        name.add("keesum");
        name.add("whiteship");
        name.add("toby");
        name.add("foo");
```

<br/><br/>

## 문제 3)

ArrayList에서 문자열이 지정된 접두사로 시작한걸 가져 올 수 있나요?

```java
List<String> list = Arrays.asList("a1", "a2", "b1", "b2", "c1", "c2");
```


<br/><br/>



## 정답 코드


### 문제 1

```java
List<Integer> numbers = Arrays.asList(1, 2, 1, 3, 3, 2, 4);
							numbers.stream()
							       .filter(i -> i % 2 == 0)
							       .distinct()
							       .forEach(System.out::println);
```

<br/>


### 문제 2

```java
public class PersonApplication {
    public static void main(String[] args) {
        List<String> name = new ArrayList<>();
        name.add("keesum");
        name.add("whiteship");
        name.add("toby");
        name.add("foo");

        name.removeIf(str -> str.startsWith("w"));
        name.forEach(System.out::println);
    }
}
```



<br/>


### 문제 3

```java
class Main {
	public static void main(String[] args) {
      List<String> list = Arrays.asList("a1", "a2", "b1", "b2", "c1", "c2");
      list.stream().filter(s -> s.startsWith("c")).forEach(System.out::println);
	}
}
```



