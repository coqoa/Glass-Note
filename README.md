# Glass-Note

#### 기획의도
1. 글래스모피즘 디자인을 적용시킨 웹애플리케이션을 하나 만들고싶었음.

2. 모바일퍼스트로 제작해보고 싶었음.

3. 내가 스마트폰으로 많이 사용하는 앱, 사용하는 목적을 생각해봤을 때  
   `영상을 목록화하고 그에 맞는 노트를 작성할 수 있는 앱`이 있으면 공부할 때 사용하기 좋겠다고 생각함.
4.  POMOTODO를 개발하면서 아쉬웠던 부분을 보완해서 좀 더 완성도 있는 웹 애플리케이션을 만들고 싶었음  
   (기획, 레이아웃, 상호작용, 애니메이션 등등)
 
#### 목표
1. 단순한 기능을 완성도 있게 개발하기

2. 데이터 베이스를 얻어서 다양하게 활용하기   
  (통계를 내거나, 사용자 패턴을 분석하거나, 데이터베이스를 기반으로 필요한 기능을 구현하거나 등등)
3. 애니메이션을 다양하게 사용해보기


---

## 모바일 환경


__1.로그인__  
![login](https://user-images.githubusercontent.com/81023768/140248832-56b1cb3b-8430-47aa-bce2-59997804d52c.png) 
<br>
<br>

__2. 회원가입__  
![sign up](https://user-images.githubusercontent.com/81023768/140248848-d3ed050e-af87-4fa3-82fe-cb7a3f581171.png)  
<br>
<br>

__3. 카테고리__  
![category contents](https://user-images.githubusercontent.com/81023768/140248890-e24a054b-6fa4-426e-b9c6-003bcb5c59c1.png)
![select category](https://user-images.githubusercontent.com/81023768/140248899-72b2be79-9049-4199-8c19-5e859934c7d0.png)
<br>
<br>

__4. 내용__  
![description - empty](https://user-images.githubusercontent.com/81023768/140248921-0d7af2d3-8c8c-4ebb-a1f4-f8eb618dc800.png)
![video url modal](https://user-images.githubusercontent.com/81023768/140248927-9ba78327-415f-475a-be7e-41f8bc842c38.png)  
![description - exam](https://user-images.githubusercontent.com/81023768/140248950-f6ab0074-38d3-4a66-acb4-4cdf4dae3ffb.png)
![text editor - exam](https://user-images.githubusercontent.com/81023768/140248960-2d73214a-7d13-403a-8ddd-b545b9a1fa83.png)  
<br>
<br>

__5. 모바일환경에서 키보드가 나왔을 때 레이아웃 예시__  
![appears keyboard -1](https://user-images.githubusercontent.com/81023768/140249085-4d5cceae-6c47-4863-a51c-451b232617f8.png)
![appears keyboard -2](https://user-images.githubusercontent.com/81023768/140249093-ba278cab-5844-403c-a89b-574ac678af9c.png)
![appears keyboard -3](https://user-images.githubusercontent.com/81023768/140249095-97feff76-50ea-4c92-a524-e2cbb4ea27c2.png)
![appears keyboard -4](https://user-images.githubusercontent.com/81023768/140249096-e27d02e1-28dd-41c4-820a-02d89fca1b1d.png)
![appears keyboard -5](https://user-images.githubusercontent.com/81023768/140249098-7471ee0b-bffd-479f-9078-bb1092597c73.png)
<br>
<br>


__6. 옵션을 통해 변경 가능한 부분 (화이트/블랙모드, 배경화면 변경, 로그아웃)__  
<br>
__option modal__  
![option modal   Background](https://user-images.githubusercontent.com/81023768/140249117-4871ae52-b207-4bbb-a08b-e798e30386e3.png) 
<br>

__white mode__  
![white mode](https://user-images.githubusercontent.com/81023768/140249165-a1e49915-8814-4a07-8ff0-a742890465af.png)
![white mode-1](https://user-images.githubusercontent.com/81023768/140249171-ff2793d1-f32b-4ca2-b5aa-78e20a25c522.png)  
<br>

__black mode__  
![black mode](https://user-images.githubusercontent.com/81023768/140249184-58ecd61f-4dd2-46a9-87ed-293799338b64.png)
![black mode-1](https://user-images.githubusercontent.com/81023768/140249185-018d449e-e8c0-465c-b491-7dacb3ed2a09.png)  
<br>
<br>

__7. 배경화면 변경 예시__  
![스크린샷 2021-11-04 오전 11 37 38](https://user-images.githubusercontent.com/81023768/140249201-36f1f62c-da91-42da-baad-37a533cc0260.png)  

---

<br>

## 웹 환경  
<br>

__1. 로그인__   
![login](https://user-images.githubusercontent.com/81023768/140249811-e8c14cdb-9754-4a42-8e95-332e8a70da20.png) 
<br>

__2. 회원가입__  
![sign up](https://user-images.githubusercontent.com/81023768/140249830-ca4b1908-f4b1-4685-bfcf-98f671f20346.png)  
<br>

__3. 카테고리__  
![category contents](https://user-images.githubusercontent.com/81023768/140249839-4aa017f0-0cf3-41be-970f-d411c13be9b0.png)  
<br>

__4. 내용__  
![description - empty](https://user-images.githubusercontent.com/81023768/140249872-db976c09-166a-464f-b361-d83f67c57b07.png)
![description - exam](https://user-images.githubusercontent.com/81023768/140249883-7ddf4f32-177e-4fd6-9751-4e8eb3347a1a.png) 
<br>

__5. 배경화면 변경 예시__  
![background-exam](https://user-images.githubusercontent.com/81023768/140249906-0c38eaed-e4ce-49cb-ae7e-296a24324eca.png) 
<br>

---
<br>

### 기술스택 (예상)   
- HTML / CSS   
- Javascript    
- AWS EC2 ubuntu + filezilla 활용   
- MySQL + MySQL workbench 활용   
- Node JS
