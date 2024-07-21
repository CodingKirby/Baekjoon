### 문제

Hello World!를 출력하시오.

### 입력

없음

### 출력

Hello World!를 출력하시오.

### 풀이

```Python
print("Hello World!")
```

### 해설

`print`를 사용하여 문장을 출력한다.

문장을 정확하게 적어야 한다.

- hello world

- Hello World

- HelloWorld!

등... 다 안된다. 띄어쓰기와 문장 부호까지 정확하게 입력해야 한다.

파이썬에서 만장을 출력하는 방법에는 여러가지가 있으나 가장 기본적인 방법은 `print`이다.

<br>

아래는 참고로 알아두도록 하자.

1. print() 함수 사용
    가장 기본적인 방법은 print() 함수를 사용하는 것이다. 이 함수는 콘솔에 문자열을 출력한다.

    ```Python
    print("Hello, World!")
    ```

2. 문자열 연결
    여러 문자열을 연결해서 출력할 수 있다. `+ 연산자`를 사용하거나 `쉼표`로 구분하여 연결할 수 있다.

    ```Python
    name = "Alice"
    print("Hello, " + name + "!")
    print("Hello,", name, "!")
    ```

3. `str.format()` 메서드 사용
    `str.format()` 메서드는 중괄호 `{}`를 사용하여 문자열 내에 변수를 삽입할 수 있게 해준다.
    
    ```Python
    age = 25
    print("I am {} years old.".format(age))
    ```

4. `f-string` (포맷 문자열)
    `파이썬 3.6` 이상에서는 `f-string`을 사용하여 더 간결하고 읽기 쉬운 형식으로 문자열을 포맷할 수 있다.

    ```Python
    name = "Bob"
    age = 30
    print(f"Hello, my name is {name} and I am {age} years old.")
    ```

5. 백슬래시 이스케이프 시퀀스
    문자열 내에서 특수 문자를 표현하거나 줄바꿈을 할 때 백슬래시(\)를 사용할 수 있다.

    ```Python
    print("Hello\nWorld")  # 줄바꿈
    print("He said, \"Hello!\"")  # 따옴표 이스케이프
    ```

6. 여러 줄 문자열 (Triple Quotes)
    세 개의 따옴표(`'''` 또는 `"""`)를 사용하여 여러 줄에 걸쳐 문자열을 작성할 수 있다.
    
    ```Python
    print("""This is a
    multi-line
    string.""")
    ```

7. `repr()`와 `str()` 함수
   `repr()` 함수는 문자열의 표현을, `str()` 함수는 문자열의 인쇄용 표현을 반환한다. `print()`와 함께 사용할 수 있다.

    ```Python
    value = 123.456
    print("Using repr: ", repr(value))  # '123.456'
    print("Using str: ", str(value))    # '123.456'
    ```

<br>

이 방법들을 적절히 활용하면 다양한 상황에서 유연하고 가독성 좋은 문자열 출력을 할 수 있다.
