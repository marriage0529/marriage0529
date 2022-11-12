### 웹(Back-End) 개발자 장찬양을 소개 합니다!

```java
public class Developer {
  private String name         = "장찬양";
  private String nickName     = "Doritos"; // 좋아하는 과자..
  private String gender       = "남자";
  private String email        = "wognsl34@daum.net";
  private String birth        = "19931018";
  private String [] techStack = {"Java", "Spring-Framework", "Oracle", "MySQL", "Javascript"};
  private String [] hobbys    = {"영화감상", "맛있는 음식먹기", "맨몸운동", "기타연주"};
  private String goal         = "더 나은 개발자 되기";
  private String career       = "2017.12 ~";
  
  private void introduce() {
    StringBuffer printbuff = new StringBuffer();
    printbuff
        .append(String.format("이름\t: %s%n", this.name))
	.append(String.format("닉네임\t: %s%n", this.nickName))
	.append(String.format("성별\t: %s%n", this.gender))
	.append(String.format("이메일\t: %s%n", this.email))
	.append(String.format("생년월일\t: %s%n", this.birth))
	.append(String.format("사용기술\t: %s%n", Arrays.asList(techStack)))
	.append(String.format("취미\t: %s%n", Arrays.asList(hobbys)))
      	.append(String.format("목표\t: %s%n", goal))
      	.append(String.format("경력\t: %s%n", career))
    ;
	  
    System.out.println(printbuff.toString());
  }

public static void main(String [] args) {
  Developer cyjang = new Developer();
  cyjang.introduce();
}
  ```
