2016.07.04
######Q `.child` 요소에 float을 줄 경우 알수 없이 발생하는 계단 현상
(2016.07.04-1.html 참고)

 A: 부모가 자식 요소를 감싸지 못하기 때문에 생기는 현상. 해결책을 찾아보자.

**1.<del>부모요소에게도 float을 적용 한다</del>**
    부모요소에게도 float을 주면 부모가 같이 부유하게 되면서 일시적으로 해결이 되는 듯하나, 이는 결국 **무한 플롯의 지옥**으로 들어가게 된다! 사용하지 않도록!!
**2.**class="clear"를 설정
    이 또한 무의미한 요소 (`p`, `div`와 같은) 사용되기에 권장하지 않는다.  
**3.**`overflow=hidden`
    부모 요소에 `overflow=hidden`을 사용하여 
**4.`class=clear-fix`**   
