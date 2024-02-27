### 240227
## 가상 클래스(pseudo-class), 가상 요소(pseudo element)
### <br/><br/><br/>

## 가상 클래스
### 코드 간소화를 위해서 특정 조건이 추가되어 실행되게 한다.
### '::'을 붙여서 쓴다. 또는 ':'을 붙여서 쓰기도 하는데, 이는 CSS2에서 썼었던 문법이고 현재는 CSS3라 '::'를 사용한다.
### ex)
```
.styled-table tbody tr:nth-of-type(even) {
    background-color: #f3f3f3;
}
```
