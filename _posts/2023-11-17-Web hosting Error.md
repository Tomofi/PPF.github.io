---
title : 2023-11-17-Web hosting Error
date : 2023-11-17 15:19:11 +/09:00
categories : [Devlog, DevError]
tags : [DevError] #소문자만 가능
---

### 날짜: 2023-11-17 13:41
&nbsp;

### 주제: #Devlog 

&nbsp;

----

### 메모

#### (1) 에러 메세지
> - Github 메시지
> ![에러 원인](/assets/img/231117_Github_Webhosting_error1.png)


> - 에러 메시지 관련 파일
> ![에러 원인]({{'/assets/img/231117_Github_Webhosting_error2.png' | relative_url}})


> - /assets/js/dist 폴더가 없었기 때문에 dist 폴더를 해당 루트에 만들어주고, javascript폴더에 있던 6개 파일의 이름을 .min를 붙여 수정 후 dist폴더에 넣어주니까 build 에러 해결됨

> - build에러는 해결됐으나, 여전히 **---layout: home # Index page---** 에러가 나옴
> 	- [Chirpy 테마 적용](https://velog.io/@hashnsalt/Github-Blog-%EB%A7%8C%EB%93%A4%EA%B8%B0-2) 블로그 설명대로, 파일 지우고, main 설정해주고, Ruby 버전 맞춰주니 문제 해결됨!

&nbsp;

### 출처(참고문헌)
* [jekyll 테마 적용 문제 blog](https://velog.io/@lzlko/github-%EB%B8%94%EB%A1%9C%EA%B7%B8)
* [Chirpy 테마 적용](https://velog.io/@hashnsalt/Github-Blog-%EB%A7%8C%EB%93%A4%EA%B8%B0-2)

&nbsp;







