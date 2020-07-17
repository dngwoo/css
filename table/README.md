# table

테이블 태그는 레이아웃을 잡을 때 쓰지 않는 것이 좋다.  
ul, li를 사용하면 스크린 리더기에서 읽어줄때에도 요소 그대로 읽어주는 효과가 있다.

## table 사용 방법

- div, ul, li를 사용하는 것이 가장 좋으며

- thead, tbody, tr은 굳이 사용 할 필요 없다.

- 태그별 display 속성  
  div - table  
  ul - table-row  
  li - table-cell

## 주요 속성

- table  
  display: table  
  border-collapse : collapse를 사용하여 경계선에서 보더 겹침을 막아준다.

- th, td  
  display: table-cell  
  y축 정렬은 vertical-align: middle로 맞춰줄 수 있다.

- ul, li
  ul <- display: table-row (table)  
  li <- display: table-cell (td)

- div, ul, li
  div <- display: table (table)  
  ul <- display: table-row (tr)  
  li <- display: table-cell (td)
