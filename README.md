# sts3
1. STS3를 신규로 설치 실행 했을경우 Spring Legacy Project의 템플릿에서 Spring MVC  project가 없음.   
2. 해결을 위해 STS3 종료 후 해당 워크스페이스의   
.metadata\.plugins\org.springsource.ide.eclipse.commons.content.core\폴더에   
[https-content.xml](https://raw.github.com/xguest7/sts3/main/https-content.xml) 을 https-content.xml로 저장하여 복사   
4. ST3 재실행
