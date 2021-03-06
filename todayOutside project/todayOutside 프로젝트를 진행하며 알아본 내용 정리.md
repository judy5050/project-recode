### int ->string , string ->int 로 변환  
1) string->int 로 변환  
String string = "5";
int num = Integer.parseInt(string);

2) int -> string 로 변환  
int num = 5;
String string = Integer.toString(num); or string = String.valueOf(num);

3) hashMap 관련 정리하기 

### 시간 관련 알아본 내용
java version 8이상부터 가능
1) LocalDate  
로컬 날짜 클래스로 날짜 정보만 필요할 때 사용
2) LocalTime  
로컬 시간 클래스로 시간 정보만 필요할 때 사용 
3) LocalDateTime  
날짜와 시간 정보 모두가 필요할 때 사용
