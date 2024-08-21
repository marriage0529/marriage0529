### BackEnd 개발자 장찬양을 소개 합니다!

```java
public class DeveloperDoritos {
  private String nickName     = "Doritos"; // 좋아하는 과자..
  private String gender       = "남자";
  private String email        = "wognsl34@daum.net";
  private String birth        = "19931018";
  private String [] techStack = {"Java", "Spring", "Oracle", "MySQL", "Javascript", "TCP 통신(Socket[BIO/NIO/NETTY])"};
  private String [] hobbys    = {"영화감상", "맛있는 음식먹기", "맨몸운동", "기타연주"};
  private String goal         = "더 나은 개발자 되기";
  private String career       = "2017.12 ~";
  
  public void introduce() {
    StringBuilder builder = new StringBuilder();
    builder
	.append(String.format("닉네임\t: %s%n", this.nickName))
	.append(String.format("성별\t: %s%n", this.gender))
	.append(String.format("이메일\t: %s%n", this.email))
	.append(String.format("생년월일\t: %s%n", this.birth))
	.append(String.format("사용기술\t: %s%n", Arrays.asList(techStack)))
	.append(String.format("취미\t: %s%n", Arrays.asList(hobbys)))
      	.append(String.format("목표\t: %s%n", goal))
      	.append(String.format("경력\t: %s%n", career))
    ;
	  
    System.out.println(builder.toString());
  }

  public static void main(String [] args) {
    DeveloperDoritos doritos = new Developer();
    doritos.introduce();
  }
}
  ```


### Notion 이력서 링크
<a href="https://dev-doritos.notion.site/Back-End-4d6dff8c708745bb8a4e47df80199640" target="_blank">https://dev-doritos.notion.site/Back-End-4d6dff8c708745bb8a4e47df80199640</a>
