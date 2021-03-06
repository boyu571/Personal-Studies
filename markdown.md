# MD 배우기

개발자의 문서양식 markdown을 배우기

## 제목

'#'의 개수에 따라 제목의 중요도가 달라집니다.

h1 => 문서에서 가장 큰 제목

문서에 h1과 h3만 있다. => 문서 잘못작성.

## 본문

본문은 그냥 적으면 본문이에요



## 리스트

### 순서 있는 리스트(1.)

1. 식용유를 두른다.
2. 파를 넣고 파기름을 낸다.
3. 계란을 풀어서 익힌다.
4. 당근을 넣는다.
5. 간장을 볶는다.



### 순서 없는 리스트(-space)

- cli 학습
  - 폴더
    - `mkdir`
    - `rm, -r`
    - `cd`
  - 파일
    - `touch`
    - `rm`
    - `start`
- git 복습
- md 작성 익숙해지기



## 인라인 코드(`)

파일을 생성하기 위해서 `touch` 명령어를 사용한다.

`cd`를 통해 폴더간 이동을 한다.



## 볼드처리(**)





### 코드블럭(```)

```
$ touch a.txt
$ rm a.txt
$ mkdir test
$ cd test
```



## 표(|)

cli 단축키

| 단축키     | 설명             | 사용예시                 |
| ---------- | ---------------- | ------------------------ |
| `ctrl + c` | 취소             | 뭔가 안될때 누르기       |
| `ctrl + l` | 비우기           | 기존 화면을 위로 밀기    |
| `ctrl + w` | 단어단위로지우기 | 한글자씩 지우면 힘들어요 |



## 수식($$)

$$
\begin{align*}
y = y(x,t) &= A e^{i\theta} \\
&= A (\cos \theta + i \sin \theta) \\
&= A (\cos(kx - \omega t) + i \sin(kx - \omega t)) \\
&= A\cos(kx - \omega t) + i A\sin(kx - \omega t)  \\
&= A\cos \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big) + i A\sin \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big)  \\
&= A\cos \frac{2\pi}{\lambda} (x - v t) + i A\sin \frac{2\pi}{\lambda} (x - v t)
\end{align*}
$$

