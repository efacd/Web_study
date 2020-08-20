# 마크다운 문법

## 제목(heading)

`(backtick)을 사용해서 inline codeblock을 만들 수 있다.

예시 : 제목은 `#` 으로 표현이 가능하다. `H1`~`H6` 까지 표현이 가능하다.

### 제목3

#### 제목4

##### 제목5

###### 제목6

# 목록

* 목록은
* 순서가 없는
* 목록이 있다.
  * 탭을 눌러서 목록 수준을 표현할 수 있다.
* 엔터를 눌러서 이전 수준으로 돌아갈 수 있다.

1. 순서가 있는

2. 목록도 있다.

   1. 엔터를 누르고 *을 하면

   * 섞어서 쓸 수도 있다.

## 코드 블록

`을 3번 누르고 python을 적고 엔터를 누르면 python codeblock을 만들 수 있다.

```python
print('hello!')
# 이것은 주석입니다.
```

```html
<!-- 주석 -->
# 주석 아님
<h1>
    Hello!
</h1>
```

## 링크

[google](http://google.com)

([보이게할문구] (링크주소) 형태로 작성한다.)

[README](./README.md)

(특정 파일을 외부 URL이 아닌 상대 경로로 표현할 수도 있다.)

## 이미지 파일

![back](C:\Users\i\Desktop\back.JPG)

* GitHub에는 C드라이브가 없기 때문에 상대 경로로 표현하는 것이 좋다.
* 위와 같이 절대경로로 표현하면, Github 등에서 파일이 존재하지 않아 이미지가 제대로 출력되지 않는다.
* 따라서, typora에 다음과 같은 설정을 해보자.
* 파일 -> 환경설정 -> 이미지 탭 -> copy image to custom folder 로 바꾸고, 온라인 이미지에 위 설정 적용, 가능하다면 상대적 위치 사용 체크

![bash](markdown-images/bash.JPG)



## 표

| 이름   | 나이 | 비고 |
| ------ | ---- | ---- |
| 홍길동 |      |      |
| 김철수 |      |      |
|        |      |      |

## 기타 문법

기울임 이탤릭체 : * 로 감싸기 (*기울임 이탤릭체*)

굵게 볼드체 : ** 로 감싸기 (**굵게 볼드체**)

취소선 : ~~ 로 감싸기 (~~취소선~~)

인라인코드블록 : ` 으로 감싸기 (인라인코드블록)

수직선 : --- 으로 작성



