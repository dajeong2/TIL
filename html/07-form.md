```html
<form action="/register.php" method="POST" name="register_form" enctype="multipart/form-data">
</form>
```
action: 
method

|  | GET | POST |
| --- | --- | --- |
| 보안 | GET에 비해 보안  |   |
| 데이터제한 | 제한적,url허용길이만큼 | 제한x |
| 데이터 타입 | 아스키 문자만 | 제한x,바이너리도가능 |
| 뒤로가기,재전송 | 사용자가 다시 작성 | 사용자에게 지워짐을 알림 |
| 인코딩 | application-x-www-form-urlencoded | multipart/form-data, application-x-www-form-urlencoded |