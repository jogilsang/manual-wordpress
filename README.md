# manual-wordpress
for me

### 사이트
https://kopress.kr/  

### 서비스(services)
그라바타(gravatar)  :  
프로필사진 공유, 만약 안나오면 이메일이 다른거임    

### 강좌   
https://www.inflearn.com   

### 기획
xMind : 마인드맵 그리는 SW  
https://www.xmind.net/download/  

### 기타 플러그인
라이브리, 디스커스(소셜 댓글시스템)  
contact form 7 : 문의하기 플러그인  

### Setting(세팅)
general(일반) -> anyone can register 회원가입받기, 태그라인(홈페이이지설명)  
Reading(읽기) -> Search Engine Visibility  
discusstion(토론) -> 댓글은 수동으로 승인돼야합니다. 체크해제  
                     다른 댓글 설정 -> 댓글 쓴사람, 이름 이메일 남기기  
                                      가입하여 로그인해야만 쓸수있기 체크해제  
 
### 시드니 테마 다운로드  
https://wordpress.org/themes/sydney/  

1. 테마를 다운받는다  
2. apeerance - add theme - upload 들어가서 zip 채로 집어넣는다  
3. 전체 필요한 플러그인을 install로 바꾼뒤 적용한다  
4. 플러그인 - 인스톨 플러그인으로 들어간다. 설치한걸 activate 한다  
   (elementor 페이지 빌드 하는 플러그인임)  
5. One Click Demo Import 플러그인 설치하기  
6. appearance - import demo data로 전체 다운로드  
   (홈페이지 화면이 바뀜)  
7. page - edit elementor  

### 설정(Settings)
post name  
time -> utc +9, Y년 m월 d일  
language -> korean  

### 한글고유주소가 연결이 안될경우  
.htaccess 로 해결하면됨  

### 쇼핑몰 만들기  
우커머스  
문서(docs) :   
https://docs.woocommerce.com/?utm_source=setupwizard&utm_medium=product&utm_content=videos&utm_campaign=woocommerceplugin  

테마(Theme) :  
mystile  
https://justfreethemes.com/mystile-free-wordpress-theme/  

플러그인(plugins) :  
beomps korea postcode search :  
한국형 주소  

Black Studio TinyMCE Widget :  
The visual editor widget for WordPress.  

KBoard 위젯 – 워드프레스 게시판 :  
최다 사용자 무료 워드프레스 게시판 KBoard 위젯 입니다.  

Loco Translate :  
Translate WordPress plugins and themes directly in your browser  

woocomerce :
워드프레스 쇼핑몰  

poedit, dummy data :  
우커머스 한글화  

Postcode Shipping Rates- WooCommerce :  
Postcode Shipping is a clean, powerful shipping rates plugin that helps you define multiple rates…  

theme my login :  
The ultimate login branding solution! Theme My Login offers matchless customization of your WordPress user  

Social Media Share Buttons & Social Sharing Icons :  
소셜미디어 아이콘, 버튼들  

WooCommerce Advanced Free Shipping :  
WooCommerce Advanced Free Shipping is an plugin which allows you to set up advanced free shipping conditions.  

SMNTCS WooCommerce Quantity Buttons  
or  
Quantity Increment Buttons for WooCommerce :  
증가버튼  

Woocommerce Quick Buy :  

Google Fonts for WordPress :  

우커머스용 아임포트 플러그인(모두) :  

우커머스 한글화 하기 :  
https://wpbox.kr/shop/woocommerce-po-file-in-wpbox/  

경로 :  
bitnami/apps/wordpress/htdocs/wp-content/language/plugins  


```
다운받은 압축파일을 압축 해제 합니다. 그러면 두개의 파일이 나옵니다.
FTP 클라이언트 프로그램 (파일질라 또는 알FTP 등)으로 내 웹서버에 접속합니다.
wp-content/languages/plugins/ 폴더안에 두개의 파일을 옮겨 넣습니다.
해당 폴더가 wp-content 폴더 안에 없다면 워드프레스언어를 한글로 바꾸면 됩니다.
plugins 폴더가 없다면 새로 만들면 됩니다.
plugins 폴더안에 예전에 사용하던 우커머스 한글 번역파일이 있다면 (woocommerce-admin-ko_KR.mo , woocommerce-admin-ko_KR.po , woocommerce-ko_KR.mo , woocommerce-ko_KR.po 4개) 모두 삭제한후 새로 받은 두개의 파일을 업로드 합니다.
관리자 단과 외부에서 모두 우커머스가 번역된 것을 볼 수 있습니다.
```

샘플파일 가져오기 :  

bitnami/apps/wordpress/htdocs/wp-content/woocomerse/sampledata.xml 머 이런느낌  
다운받자. 그리고 도구 - 워드프레스 설치후 파일 올려버리면됨. import 등 체크하고  


