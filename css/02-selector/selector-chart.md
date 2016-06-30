#selector chart

---

###

 설명 | 표현 
 -- | -- 
 전체(0) | * 
 요소(1) | Element 
 자손| space 
 자식 | > 
 일반형제 | ~ 
 인접형제  | + 
 아이디 | #id 
 클래스 | .class 
 멀티 클래스 | .class1.class2 

---

###속성선택자
- 기본형태:[attr="value"]
- 중복 적용 가능: img[class^="value"][alt*="value"] 

 설명 | 표현 
 -- | -- 
 시작하는 속성 값이 일치 할 경우 | [attr^="value"] 
 끝나는 속성 값이 일치 할 경우 | [attr$="value"] 
 속성 값을 포함할 경우 | [attr*="value"] 

---

###가상클래스
 설명 | 표현 
 -- | -- 
 :nth-child(n) | 부모요소의 자식 요소 중 수학 표현 식의 결과값 실행 
 :nth-last-child | .. 뒤에서부터 
 :only-child | 유일한 자식요소 
 :nth-of-type(n) | 동일한 요소 중 수학 표현 식의 결과값 실행 
 :nth-last-of-type(2) | .. 뒤에서부터 
 :not(selector) | ()안의 선택자를 제외한 나머지 대상 요소 선택 
 :link.hover.active.visited.focus | 
