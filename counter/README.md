# counter-reset 사용방법

1. counter-reset을 ul, ol 등 부모에 지정해준다.
2. li:before에 counter-increment: num 1; 을 적어준다.  
   counter-reset의 num을 말하는 것이고 1씩 증가시킨다는 뜻이다.
3. li:before에 content: counter(num);을 사용하여 실제로 화면에 표기해준다.
