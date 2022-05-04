# read-me-practice

연습사이트 : 화라리님의 web-to

[https://github.com/leehwarang/javascript-web-todo](https://github.com/leehwarang/javascript-web-todo)

## 1. 글씨크기

1. ‘#’ 은 볼드, 큰 텍스트를 의미, ‘#’이 앞에 많이 붙을 수록 글씨가 작아진다

# hi  #

## hi ##

### hi ###

## 2. 글씨스타일

1.  ‘** 글자 **’ :  **볼드 체** 
2. ‘* 글자*’: *italic*
3. ‘_글씨_’ : *기울어진 글씨*
4. ‘~~글씨~~’: ~~글씨에 선긋기~~
5.  ‘``` ': 소스코드 작성 

```jsx
console.log(`sourceCode`)
```

## 3. 꾸미기

1.  ‘>’     토글  
- 📝리액트로 구현한 할 일 관리 웹 어플리케이션
1. ‘-’ : 불렛 
    - 안녕
    - 안녕
    - 안녕
2. ‘*’: 이것도 불렛
- 안녕
    - 안녕
        - 
1. ‘—-’ ‘-’3개 : 회색 라인 
    
    ---
    

---

## 4. 링크

1. ‘[링크 이름](링크주소)’:링크   예 )  ‘[데모 링크]([https://michelle-todo.herokuapp.com/](https://michelle-todo.herokuapp.com/))’
    
    [데모 링크](https://michelle-todo.herokuapp.com/)
    
    [데모 링크](https://michelle-todo.herokuapp.com/)
    
    
    [데모 링크](https://michelle-todo.herokuapp.com/)
    
2. ‘![할 일 관리 앱](링크 주소)’ : 서버에 저장되어있는 이미지를 링크해서 보여줌



## 5. 인용구문

‘>’ ‘따옴표 안에 글자’ : 인용구문
> '공부합시다'

> 'Tip: 주로 Tip을 주고 싶을때 사용하면 최고로 좋습니다'


나중에 필요한거 있으면 더 찾아보기

틀린거 있을 수 있음

## 6. 테이블

'|Header|Description|'  
'|----|----|'  

까지만 입력하면 한 테이블이 완성된다 

|Header|Description|
|----|-- |
|Cell1|Cell2|

이때 짝대기 안의 '-'개수는 상관없고, 스페이스바 유무도 상관없다 
 
 
여기서

'|:----|:-- |'
왼쪽에 ':'을 넣어주면 왼쪽정렬


'|----:|--:|'
오른쪽에 ':'을 넣어주면 오른쪽정렬


'|:----:|:--:|'
양쪽에 ':'을 넣어주면 가운뎃정렬이 된다 

가운뎃 정렬 하는 또다른 방법:

|버전| <div align="center">업데이트 내용</div> | 업데이트 날짜 |
| :-------: | :---- | :-----------: |



불행하게도 markdown의 테이블은 셀 병합이라든지 안된다

The remainder of the table’s rows may vary in the number of cells. 
If there are a number of cells fewer than the number of cells in the header row, empty cells are inserted.
If there are greater, the excess is ignored:

이럴땐 raw html로 작성해야함 (구글에 'markdown 셀 병합' 검색 ㄱ)




## 7. 문장 안에서 코드 보여주기 

- 코드인 부분만 백틱으로 감싸면 된다 
    hello hi `console.log('hello hi')`
    


## 8. 이외 기본

- 개행(new line) 방법 세 가지
    1. 한 줄만 개행: 문장의 끝에 스페이스바를 두번 넣고 엔터를 입력
    2. 문단 단위 구분을 위한 개행: 엔터를 두번 누름
    3. 브롤테그 이용 (<br/) 
   
- 띄어쓰기 하기 2가지
    1. &nbsp; 근데 너무 작음
    2. ' ' : 전각문자, ' '안에있는 이거 그대로 복사해서 쓰면 됨 
    3. '   ': [여기 클릭해서 받아오면 되는데 또 안되니...](https://kimasill.tistory.com/entry/MarkDown-%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4-%EB%9D%84%EC%96%B4%EC%93%B0%EA%B8%B0%EA%B3%B5%EB%B0%B1-%EC%A4%84%EB%B0%94%EA%BF%88-%EC%82%AC%EC%9A%A9%EB%B2%95)
    4. '  ': 보니까 전각문자 2개면 tab들여쓰기 구현 충분히 할수 있음. 이거 그대로 복사해서 쓰면 됨 


- 글씨에 색 집어 넣는건 안된다 ㅠㅠㅠㅠㅠ 빨간색 글씨로 강조하고 싶어도 못함 


- visual studio의 markdown preview이용하기
    - 이 extension은 이미 visual studio에 깔려있는거라 설치할 필요 없음
    - preview보고자 하는 readme.md파일을 클릭하고 ctrl+shift+v를 누르면 바로 튀어나옴

- readMe 는 html을 지원하지만 아래의 스펙은 지원하지 않는다 
<title> <textarea> <style> <xmp> <iframe> <noembed> <noframes> <script> <plaintext>
    아쉽다...
