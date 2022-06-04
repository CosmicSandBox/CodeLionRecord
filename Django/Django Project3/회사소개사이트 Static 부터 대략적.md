[→ Open in Slid](https://app.slid.cc/docs/ad2b5de9f8ed4a20aa1a281b87fe2ead)


---

# STEP 6 Static -이론

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/fb5d8909-b203-4277-8c60-eed62a067778.png)](undefined)


웹서비스의 내부 데이터 종류

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/ec5f7dfe-9eb4-4c70-84e0-ce7cce77fdaa.png)](undefined)


이 두가지가 있따.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/6eac3544-3e28-4fd2-b37d-3326f3347b46.png)](undefined)


Static - 웹서비스 내부에서 미리 준비한 데이터 css, javascript, img파일


Media- 사용자가 업로드한 사용자에 의한 데이터라고 보면 된다.


‏‏‎ ‎


브라우저에 구글을 딱 입력헀을때 뜨는 화

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/e51a8fc3-2b50-4d94-8c51-42ed49c96030.png)](undefined)


이런 사진들은 구글에서 미리 입력한 화면이겠찌?

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/45d8be62-6393-46c5-b8c2-e29e8a861509.png)](undefined)


이런 구글 검색창이나 컨텐츠 이런 것들은 css 통해서 작성되었다고 짐작 가능함.


이런 css, javascript, img 파일들을 static 파일이라고 한다.


‏‏‎ ‎


media는 나중에 말해줄 것.


오늘으 ㄴstatic 파일을 다루는 법에 대해서 말해줄 것임.


장고에서는 settings.py에서

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/f8557562-c392-4bbb-9399-1e4ba8af62a4.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/1230c026-d065-44a3-a525-b9e45820fd0e.png)](undefined)


이 세가지 설정으로 static 파일을 관리한다.


‏‏‎ ‎


잘 기억해둬야한다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/8ed16f51-72ee-41ac-8e51-788d691aef92.png)](undefined)


개발과정에서 static 파일들이 내 개발환경내에 어디에 위치해있느지 알려주는 역할을 한다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/685fbdfc-781e-4109-9a87-02d04d5d6038.png)](undefined)


우리가 사용할 static 파일들이 위치한 경로는 여기에 써주면 된다.


‏‏‎ ‎


‏‏‎ ‎


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/fd2d602b-ac8e-4c50-b409-62f409cda68f.png)](undefined)


나중에 배포했을 때 프로젝트 폴더에 staticfiles 라고하는 폴더 안에 모조리 몰아넣고 static file들을 복사해서 몰아넣게 된다.


자세한건 나중에 보여줄 것.


어떤 폴더 어떤 경로에 static 파일들을 몰아넣을지를 적어주면 된다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/abd3922d-53e1-472d-ba09-2747f8bba49e.png)](undefined)


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/53446d70-64b4-4724-bb1e-282426a1502f.png)](undefined)


‏‏‎ ‎


‏‏‎ ‎


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/c12c13c3-fbd4-49a8-81c4-2cce4e4f6da9.png)](undefined)


이 명령어를 통해서 static root에 적어놓은 경로에 스태틱 파일들을 모조리 모아놓을 수 있다. static 경로 안에 모조리 몰아넣는 과정은 배포를 할 때 쓰는거고


개발을 하는 과정에선 굳이 이 collectstattic 명령어 쓸 필요없이 그냥 static file들을 runserver해도 알아서 인식을 한다.


그냥 static이라고 하는 폴더 안에다가 static file들을 모조리 밀어넣고 거기 안에서 runserver를 해도 알아서 인식이 된다.


이 배포를 할 때


스태틱 파일들을 설정하는 자세한 내용들은 나중에 배포를 진행할 때 조금 더 자세하게 말씀을 드릴게요. 지금은 static file은 뭐고 기본 세팅은 어떻게 해야하는지만 건저가면 될듯.


‏‏‎ ‎


이 static root는 배포할 때만 쓰인다고 하지만 이 개념이 너무 중요하기 떄문에


미리 말씀 드린 것임.


‏‏‎ ‎


‏‏‎ ‎


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/94ace542-a8d6-4ff8-8a8b-aeb57d5c6b7a.png)](undefined)


static 파일을 제공할 url을 써주면 된다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/cace217d-a7c4-4bac-ba9f-c7776c92608b.png)](undefined)


이렇게 설정되어있다면,


우리들의 웹서비스주소/static/스태틱파일이름


하면 브라우저 딴에서 접근할 수 있는 것임. 자 근데 여기서 이렇게 궁금해 하는 사람도 있을 것.


웹서비스 내부에서 미리 준비한 css, javascript같은게 static 파일이라고요?


근데 html안에서

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/8b4ba5a2-447f-4515-90ac-cd40795d2f42.png)](undefined)


이런식으로 이미 css나 image 파일들을 가지고 올 수 있는 방법이 있잖아


굳이 static file들을 굳이 settings.py에 등록하고 관리를 해줄 필요가 있나요?

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/abec868d-30c1-4b1b-9526-ca51f0daefdd.png)](undefined)


나중에 정말 규모있는 웹서비스를 만들게 된다면


수많은 css, js, img 파일들을 사용하게 된다.


찾기 어렵고 성능이 안좋아질 수도 있음.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/1c2bb96a-ce7b-497f-a7de-13a2dba90136.png)](undefined)


해당 static file들을 좀 더 효율적으로 찾을 수 있게 하기 위해서


미리 이렇게 관리하고 모아둔다고 보면 된다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/f05a0c22-40e7-46be-be7b-4996fd380829.png)](undefined)


‏‏‎ ‎


‏‏‎ ‎

# STEP 7 Static -실습(1)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/9958be0f-cf49-48ce-90c7-b837453205b7.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/4c729f6c-bad0-4776-9a5c-7e869c2a53ec.png)](undefined)


한번 실습으로 다뤄보자


가상환경 ㅁ나들고


장고 설치하고


어떤 프로젝트를 만들었다 (static\_ex 스태틱 엑서사이즈라는 연습용 프로젝트)를 만들었따.


‏‏‎ ‎


그 안에 manage.py를 통해서 staticapp이라는 어플리케이션을 만들었다.


그리고


이제 settings.py에다가

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/4b65bc6b-13ea-4313-974b-83c72810e927.png)](undefined)


만들어준 applciation을 등록해줘야겠쬬?


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/fb73ba11-b9e4-4fec-b109-e9e258e121e1.png)](undefined)


이 녀석이


아까전에 설명드렸던 static 파일과 관련된 여러기능들


static 파일들을 모아주거나 찾아주거나 하는 그런 기능들을 제공해주는


staticfile들에 대한 관리를 전담하는 녀석이라고 볼 수 있음.


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/462fafaa-364d-4b03-85d6-2ecc3ae84c3d.png)](undefined)


staticapp에서 views.py를 가져오고


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/b9419f8a-6823-42ca-8572-35a152712720.png)](undefined)


‏‏‎ ‎


아무것도 입력하지 않았을 떄 views.py에서 home이라고 하는 함수를 실행시키는 것으로 하자.


‏‏‎ ‎


그리고 그 home이라고 하는 녀석은 request를 받고 home.html을 띄워주는 녀석이라고


함수를 작성해볼 것.


그리고 start app에다가

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/57457899-67d9-43c1-81f3-21f99669b5d1.png)](undefined)


항상 그래왔뜻 templates 라는 폴더를 만들어주고 여기서 띄우기로 한 home.html을 만들어주면 되곘쬬?

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/2c9d0a3a-a009-4271-ae51-1393d00f2709.png)](undefined)


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/fa34f8bc-3fb7-4aa9-87ee-5a85a12a57f1.png)](undefined)


html : 5 에 커서 갖다대고 tab 누르면

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/a6e62cb4-7507-46e5-9180-166ab9d37d57.png)](undefined)


형식이 자동완성 된다.


여기까지 이해 됐죠?


Stati Practice라고 이름을 짓고


div 태그 안에다가


Hello Static!!이라고 하고 runserverㄹ를 해볼게요.


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/e942b7b7-f5e0-472a-9ba8-5864f8f3e40c.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/da1f37e9-bf0b-466d-bd7c-f33dd1eac9bb.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/65767019-ebb5-42bb-a5d8-24949b564c84.png)](undefined)


‏‏‎ ‎


이런식으로 잘 뜨는 것을 볼 수 있음.


‏‏‎ ‎


서버 끄고

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/cd3faad0-6ff7-47bb-962a-ae1f19b71535.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/7049255b-b678-48e8-90ed-d7b2b001f6fe.png)](undefined)


‏‏‎ ‎


static file 관련 설정은 settings.py에서 진행한다.


밑으로 내려보면 static files 라는 부분이 있는데


여기 밑에서 static files와 관련된 설정을 진행한다고 볼 수 있음.


여기 보면 공식 문서 링크가 있는데 여기 가보면 static file들과 관련된 정보가 쭉 있는 것을 볼 수 있음.


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/c5ef1d7fe96c40049f9a5ab5f9657149/3dbf5642-de3f-4690-a01d-23f02b83f6cb.png)](undefined)


‏‏‎ ‎


그냥 관심 있으면 보세요.


바로 실습으로 보겠습니다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/a4c2bd1c-2451-40d1-b1ac-0f12e30e9ad1.png)](undefined)


얘는 뭘까요? static file을 제공해주는 url이라고 말씀 드렸쬬.


/static/ 이라고 되어있쬬?


우리의 웹서비스/static/static 파일이름


이런식으로 브라우저 딴에서 우리들의 스태틱 파일에 접근할 수 있다고 말씀드렸쬬.


‏‏‎ ‎


스태틱 url이 뭔지 아셔야 합니다.


‏‏‎ ‎


‏‏‎ ‎


‏‏‎ ‎


이제 static file directory를 설명해보겠습니다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/86f6f63e-03d7-4772-8a2f-459f823f50db.png)](undefined)


라고 적은 다음에 리스트나 튜플 형식으로 static file directory라고 작성해주면 된다.


우리들이 개발을 하는데 있어서 static file들이 위치한 경로를


적어주는 곳이다라고 말씀을 드렸죠.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/4ac41cc2-dbf8-4997-9e4b-6f17cd95b1fc.png)](undefined)


여기 이 최상위 디렉토리에다가


static이라고 디렉토리를 만들어보도록 하겠습니다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/88006f86-c040-4858-a29c-dcdc76766956.png)](undefined)


참고로 중요한 내용 -> 최상위 디렉토리 있쬬


가장 윗부분에 있는 최상위 디렉토리를


base directory라고 부릅니다.


즉, 우리는 static file들을 이 베이스 디렉토리 (최상위 폴더 바로 아래에 static이라는 폴더 안에다가 static 파일들을 넣고 관리를 해줄 것임)


‏‏‎ ‎


베이스 디렉토리 안에 스태틱 폴더 만들고 그 안에 스태틱 파일넣고 관리할거라고 말을 해야겠찌/

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/c1e0c7f9-22c8-4838-827c-1e81169215b4.png)](undefined)


참고로 베이스 디렉토리는 어떤 경로인지 이렇게 4번째 행에 적혀있는 것을 볼 수있음.


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/592627fe-d914-4156-8619-36cb6c4c26ea.png)](undefined)


‏‏‎ ‎


어쨌든 우리는 이번 프로젝트에 최상위 폴더에 static 폴더를 만들고 여기에다가 style.css 아니면 이미지, js 들을 넣어줄거임.


‏‏‎ ‎


참고로 보통 static 파일을 만들고


static 폴더를 만들고 여기에다가 여기에다가 바로 css js img를 넣는다기 보다는


css js img

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/e8a71d33-1684-4e4d-a277-ab55b0e7c227.png)](undefined)


이런식으로 폴더를 만들어주고 그 안에다가 이렇게 넣어서 관리를 해주는 것이 국룰이긴 하다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/5cc5f7a9-0c0b-4f50-aeef-2c67b372f7db.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/8b30b810-7598-467a-8822-dc75b78a79a7.png)](undefined)


이 style.css 안에다가는 이렇게 작성을 해볼게요.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/0e2131e3-b0dd-4727-9650-8ab2ee71f730.png)](undefined)


이 html 파일에


바디 태그를


전부다 가운데로 정렬해주세요

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/1e28d984-b68b-4acd-8e11-85d3e2dde23d.png)](undefined)


라고 해주세요.


여기까지 이해가 가셨죠?


이렇게 static file들을 작성을 해보도록 하겠습니다.


‏‏‎ ‎


‏‏‎ ‎

# STEP 8 Static-실습(2)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/cb2cc275-acc4-43dc-9053-c7aca648ac6e.png)](undefined)


‏‏‎ ‎


이제 실제로 html에 우리가 설정하고 만든 static 파일들을 가져와 줘야 겠죠?


html에 우리가 만든 static 파일들을 가져와 보도록 하겠습니다.


‏‏‎ ‎

---

# 중


얘들을 가져오는 방법은

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/0262cbcb-488f-49cc-9e8e-83de2d90ee3f.png)](undefined)


{% %} 이걸로 감싸주고


load static 이라고 적어주면

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/b0f980cb-ae52-4894-941d-30107d7ad9a8.png)](undefined)


‏‏‎ ‎


‏‏‎ ‎


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/20d5ad62-c625-4a21-b739-d71c980a7d2a.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/15373920-71bb-4ca2-8f81-e6881cc68acf.png)](undefined)


이 static 경로에 있는 static 파일을 이 html에다가 ㅏㄱ져와주세요, 로드해주세요 이런 뜻이 된다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/d2a06849-0e9e-4625-9e98-a51ba03cbaba.png)](undefined)


‏‏‎ ‎


이런 형식 얘네는 장고의 기능중 하나인데 이거를 템플릿 언어라고 부른다.


html에서 쓸 수 있는 장고의 언어라는 뜻이다.


우리가 설정해주고 만들어줬떤 그 static을 가져와 주는 것임.


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/a4c2b8b6-ec4f-43ac-b187-f9643bf94683.png)](undefined)


다른 파일들 말고 저녀석 css를 가져오고 싶은데

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/bb1941f2-ba67-437f-9e00-d510121ea0bf.png)](undefined)


요녀석은 마찬가지로 템플릿 언어로써

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_markup_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/7f4cdfda-4fe4-4fdf-9c09-aba0b47cf2d8.png)](undefined)


가져올 수 있다.


여러분들이 주목해야할 부분은 저기 뒤에 저부분.


그냥 html 했다가는 style.css 경로만 써주면 될텐데


요것도 쌍따옴표로 감싸주고 템플릿 어넝로써 저렇게 가져오면됨.


스태틱 아래 있는 css 아래 있는 style.css를 가져올 것이다


라고 템플릿 언어로 감싸준채 가져오면 된다.


‏‏‎ ‎


즉 우리는 settings.py에서 어디에다가 스태틱 파일을 설정할건지 설정해주고

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/66e42b3b-6c55-4954-99a2-cf65284873aa.png)](undefined)


‏‏‎ ‎

# **여기서 부터 힘들어서 메모 대략적으로**


‏‏‎ ‎


그리고 실제로 스태틱 파일을 만들고 html에 html에서 쓸 수 있는 장고의 언어인 템플릿 언어로써 스태틱 파일들을 가지고 와주세요 해서 href로 css 폴더, 스태틱 디렉토리 안에 있는 style.css를 가져와달라고 할 수 있는 것.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/83091e24-9e00-4b69-836b-552348fb5123.png)](undefined)


이런식으로 가운데 정렬이 잘 된것을 확인할 수 있음.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/6619928a-525d-45df-9d84-1f9755a18d0f.png)](undefined)


이미지 파일 가져와볼게

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/37e70865-4af6-4be3-9bdb-93b039ee4ff9.png)](undefined)


url 적어주면 된다.


여기도 템플릿 언어로 저렇게 해준다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/012ae428-42c3-41de-beb5-d0e3c9404e12.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/abe0df55-ad4c-4dce-8491-99d1baaab74f.png)](undefined)


크기가 클 수 있으니 width 저렇게 해서 줄여서 가져온다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/123a0ab2-22f5-4201-8f99-f978d78f37c2.png)](undefined)


이렇게 잘 가져와짐.


‏‏‎ ‎


조금 아리송 할 수도 있는데 조금만 연습하면 익숙해진다.


‏‏‎ ‎


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/4bdd08aa-cb93-4133-85f6-45a121c5c0e6.png)](undefined)


여기 이렇게 경로 작성해주는 방법 말고


다른 방법도 있음


다른 방법에 대해서 말해줄게


‏‏‎ ‎


지금은 우리가 베이스 디렉토리 안에 스태틱 파일에 담고 관리를 했음.


근데 만약에

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/35428233-5178-4b73-af6b-9f275a1933b9.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/9235ce31-7c71-4ade-9cb2-fbfd99dfc2b7.png)](undefined)


‏‏‎ ‎


만약에 어플리케이션 안에 static 디렉토리 만들고


그 안에서만 쓸 static 파일이니까


이 안에서만 static 파일을 관리하고 싶어 하는 사람도 있을 것임.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/22a66cef-6608-482d-9a98-ce5c5964ee5d.png)](undefined)


이 application 밑에 static 폴더를 만드는 것 만으로도 장고는 runserver하면 인식을 하긴 함.


‏‏‎ ‎


다른 방식을 알려준다면 이런 것도 있음..


베이스 디렉토리 안에 있는 스태틱 앱 안에 있는 스태틱 이라고 하는 폴더를 관리하겠다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/8a9a4a52-0ab8-4612-aa67-e9e9aa3a321e.png)](undefined)


이런식으로도 작성할 수 있음.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/b6bdabed-8fdb-415d-9e80-91ef1ba73688.png)](undefined)


물론


112행처럼 쓸 수도 있지만


113처럼 작성할 수도 있음.


‏‏‎ ‎


참고로 os는 import 해줘야 한다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/79efd5fe-b987-42b3-8fc9-d399594da596.png)](undefined)


왜냐

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/341e3e0b-dbf5-4db1-9a3e-aea7e6f53bce.png)](undefined)


이런식ㅇ로 표현하는게 옛날 장고 (1년 전이긴 한데)


이런식으로 썼었기 때문이다.


이런 것을 보고 당황하지 말라는 의미에서 알려준 것임.


이런식으로도 static file 경로를 작성할 수 있는데


베이스 디렉토리 안에 스태틱 앱이라는 디렉토리가 있는데


그 아래에 static이라느 녀석에다가 static 폴더를 관리하겠다고 작성을 한 것임. 이런식으로 경로를 작성한 것임.


‏‏‎ ‎


만약 여기에다가

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/6b29d4b7-837d-4d85-8d2e-2865c745b5fa.png)](undefined)


이런식으로 만들어서 작성을 해볼까요?


‏‏‎ ‎


div 태그로 감싸는 border 테두리를 만들어 볼게요.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/13364d38-ac2e-4bf6-b17c-cd96f0eb81d3.png)](undefined)


그리고 home.html에 static file들을 가져오라고 하면 이 경로에 있는 모든 static 파일들이 갖고와 지겠죠?

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/c1e3def8-cdd0-496e-91fe-751b7574d7b9.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/d05e3f28-9c40-480d-936e-154b554c7b6a.png)](undefined)


‏‏‎ ‎


근데 우리가 갖고오고 싶은 것

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/1096ba54-016f-4c66-a2b8-5c9e0f853034.png)](undefined)


‏‏‎ ‎


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/47d05f75-9b98-44a2-bc82-5d347d4ce672.png)](undefined)


은 static 폴더 안에 있는 style2.css 였죠?


‏‏‎ ‎


‏‏‎ ‎


이런식으로 하면 요녀석도 잘 먹게 되겠쬬?

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/cf141c96-7535-419c-a293-f34a3cd50958.png)](undefined)


‏‏‎ ‎


런서버 돌리

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/ecf497ca-540b-4c8b-9815-7ddef9f076f7.png)](undefined)


style2.css도 잘 적용이 된 것을 확인할 수 있음.


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/a3834271-760f-47fa-82bd-9e13bfad2b0e.png)](undefined)


만약 여기 mycss라고 만들어 보겠습니다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/bb8f2667-69b2-40b1-adc4-b6a95b9c6265.png)](undefined)


'


그리고 이렇게

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/50c06202-ba03-4933-af83-19656bf1a926.png)](undefined)


담아주면

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/ebf86359-d226-4d48-8f6e-c5ede5c0e8e9.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/785f888c-aa5d-4ec2-a402-4106f665d1d0.png)](undefined)


‏‏‎ ‎


이렇게 적용해주면 되겠죠?'


‏‏‎ ‎


그럼 마찬가지로 이게 잘 적용이 되겠죠


여기까지 이해가 잘 됐죠?


어렵진 않죠?


‏‏‎ ‎


‏‏‎ ‎


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/a32f0603-e3d4-421f-bf3a-aa8971251661.png)](undefined)


그리고 STATIC\_ROOT는 우리가 배포를 할 때 결과적으로 어떤 경로에


static file들을 모을 것인지.


우리가 개발을 할 때는 (DEBUG=True)일떄는 이 runserver하는 것 만으로도


static file들을 브라우저에서 자동으로 모아주지만,


‏‏‎ ‎


배포를 할 때는 runserver를 통해서 static file들을 모으는 것이 아니기 때문에 이렇게 한 곳에 모으는 작업이 필요하다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/1f7935c8-8929-4ccb-8ff2-e2b25dd4b9d0.png)](undefined)


이런식으로 경로를 작성해주면 우리가 배포를 할 때


staticfiles라는 폴더에다가 우리는 static 파일들을 모조리 모아줄 것이라는 것으로 이해하면 된다.


‏‏‎ ‎


그리고 여기 모조리 다 모으는 명령어는 뭐라고 했냐면


(아직은 쓸일은 없지만)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/a7ec0a9d-353f-4448-90e8-1f3a04133a64.png)](undefined)


‏‏‎ ‎


python manage.py collectstatic


이다


staticfiles라고 만든 폴더안에 지금까지 만들어준 static 파일들이 잘 모아질 것임.


복사가 될 것임.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/6b46a5af-632a-4962-9fe1-1ec934dc9ec6.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/be7cd432-51f5-4091-93b5-1e3ff7ad3345.png)](undefined)


‏‏‎ ‎


staticfiles가 자동으로 생성이 된 것을 볼 수 있다.


그리고 admin 요거는 장고에서 기본적으로 제공하는 static file


admin 페이지 같은거.


그리고 아까 만들었던 styl

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/c818bc62-e416-42f2-992e-c2972f748f78.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/7dbecd73-884d-45ed-9db7-315f6282fd0d.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/74baf883-a43f-4c6d-bcad-82e97c19ec9f.png)](undefined)


‏‏‎ ‎


‏‏‎ ‎


우리가 아까 만들었던 css, img mycss가 staticfiles라고 하는 곳에


잘 모아진 것을 볼 수 있음.


이런식으로 배포를 할 떄는 staticfile들을 모을 수 있다.


‏‏‎ ‎


‏‏‎ ‎

# STEP 9 Bootstrap(1)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/b50df09b-697e-40fe-b552-724dd6c1b2d5.png)](undefined)


‏‏‎ ‎


우리가 만든 웹서비스를 조금 더 그럴 듯하게 쉽게쉽게 꾸밀 수 있는 서비스인 bootstrap에 대해서 알려줄 것임


이번시간에 배우는 것은 다음 시간까지 이어진다.


일단은 bootstrap.ex

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_markup_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/57ca7ae9-bda8-4577-9f72-8a070e53eb06.png)](undefined)


들어가기에 앞서 기본 세팅을 해두었음.


‏‏‎ ‎


이런 프로젝트 폴더를 만들어 줬다 (bootstrap\_ex)


그 안에서

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/c86e9940-65c7-4706-a970-6118dac33852.png)](undefined)


‏‏‎ ‎


bootapp이라는 어플리케이션을 만들어 줬고


템플릿 안에 home.html

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/9f4ddf9c-9436-427a-97ff-7bbe19e10a6e.png)](undefined)


Hello, Bootstrap이라고 하느 ㄴ글자를 띄우는


걸 만들고


‏‏‎ ‎


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/e766fce2-9e46-406c-8132-e8d72cd510ce.png)](undefined)


home이라는 함수를 통해서 화면에다 출력을 하는 것 까지 만들어 놓았다.


그래서 이 부분은 너무 많이 반복한 내용이니까 설명을 생략하고 들어갈게.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/272113e1-5d03-41d1-b1b9-4f97805d9205.png)](undefined)


이렇게 잘 뜨는 홤녀까지 만들었따.


‏‏‎ ‎


그리고 수업을 진행한다.


‏‏‎ ‎


bootstrap

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/97241410-50b5-4e4d-97a0-b5e9ff81e079.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/6aac01e6-46e9-478a-802b-866fb3698e13.png)](undefined)


‏‏‎ ‎


웹사이트의 꾸밈요소들, 버튼들 이런 꾸밈 요소들이 미리 만들어져있고


조금의 설정만 해주면


이 코드들 복붙하면 꾸밈 요소를 그대로 사용하게 해주는 서비스임.


‏‏‎ ‎


부트 스트랩은 우리가 한 번 쯤 볼 수 있는 웹사이트 꾸밈 요소들을 쉽게 쓰 수 있도록 많이 씌는 요소들을 만들어 놓음.


이 코드들을 프로젝트에 복붙하는 것만으로도


이 요소들을 갖다 쓸 수 있게 해주는 서비스라고 보면 된다.


자 그래서 결과적으로 bootstrap은 이런 요소를 그냥 갖다쓸 수 있게 해주는 서비스임


이걸 복붙하는 것으로 쓸 수 있게 해주려면


어떤 설정을 좀 해주어야 한다.


‏‏‎ ‎


인식이 되게끔 설정을 해주어야 하는데 그것부터 시작을 해보도록 할게요.


다른 프로젝트도 마찬가지 이지만


우리들의 프로젝트, 부트스트랩을 특정 프로젝트에 활용할 수 있는


방식은 크게 두가지


‏‏‎ ‎


**1\. 다운로드**

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/8e1f0061-fcdf-4d17-b16a-208fe4a77734.png)](undefined)


‏‏‎ ‎


**2.**


CDN 방식은 link 하고 http

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/83a0a2b8-09e4-4527-9979-361cca6ffd43.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/3d159cfc-f979-4898-a07d-428638d13ef9.png)](undefined)


뭐 이런 url이 있는데


직접 들어가보

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/d2d883bb-4595-4c1a-8b5a-761f3aca14f5.png)](undefined)


css 코드 뭉치가 있는 것을 볼 수 있음.


얘도 url 처럼 되어있지만


결국 그냥 js 문법인 것을 볼 수 있음.


부트스트랩 관련 css와 js 관련 문법을 네트워크 상으로 실시간으로


우리들의 웹서비스에 가져와서 쓰는 방법이 있음. CDN 방법이 있음.


다운로드 받지 않고 네트워크 상으로 꾸밈 요소에 해당하는


css와 js를 다운받는 것을 CDN 방식이라고 한다.


‏‏‎ ‎


‏‏‎ ‎


우리는 그냥 다운받아 버릴거임.


이거는 강의 영상 그냥 보면 될듯!


‏‏‎ ‎


부트스트랩으로 다운 받는 것들도 결국 static file들임


이것들의 static 설정을 통해서

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/cf50e643-cb05-423f-bbf3-a122a67bca44.png)](undefined)


베이스 디렉토리에


static을 만들고


이 static 폴더 하에

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/4367b2a6-ce18-4260-9cff-f948c2fbb350.png)](undefined)


이걸 넣어서 활용을 해볼 것.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_markup_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/aeea31cb-6594-4fd6-a8b3-b9576fab79af.png)](undefined)


이런식으로 베이스 디렉토리 하에 있는 스태틱 폴더에 잘 담아주었음


‏‏‎ ‎


저번 시간 말했던 것 처럼


static file 들을 쓰기 위해서


static 관련된 설정들을 settings.py에다가 해줘야한다고 말씀드렸죠.


base 디렉토리 하에 static이라는 폴더에다 static file들을 관리하겠다는 뜻으로

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/d17e3341-32d9-4211-bcbb-668458c101b6.png)](undefined)


이렇게 쓰고 리스트 형식으로

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/df38db5a-c653-48c5-91b0-ceb069ae69e9.png)](undefined)


base 디렉토리 하에 있는 static이라고 하는 폴더에다가 static 파일들을 담아서 관리할거라고 작성을 해준다.


‏‏‎ ‎


그리고 설정해준 static file

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/e2d0f143-4d42-4ac1-97c6-b0cb6e23cd3f.png)](undefined)


이 경로에 맞는 이 static 파일들을 html에 가져와주기 위해서


장고에서 쓸 수 있는, template에서 쓸 수 있는 기능. 장고가 제공하는 템플릿에서 쓸 수 있는 언어인 template 언어를 통해서 static을 가지고 와주세요


이렇게

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/025fa3cd-beb1-4317-aee2-5db9421ecf8c.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/ecd024db-6cb4-46a0-98bf-fa2996f3a9cd.png)](undefined)


이런식으로 가져와준다고도 말을 했죠.


‏‏‎ ‎


여기있는 static 요소들 중에

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/2ea02b35-6264-4ce5-b5f2-855e380ae755.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/8f9e608c-4195-4bdc-90e5-839443cf1512.png)](undefined)


요녀석을 가져와 보도록 할게요.


‏‏‎ ‎


‏‏‎ ‎


‏‏‎ ‎


link rel="stylesheet" type="text/css" href="{% st %}"


href 안에도 쌍 따옴 안에다가 이런식으로 template 언어로써 링크를 남긴다


static으로 내가 가지고 오고자 하는 static file에 해당하는 링크를 남긴다.


라고 말씀 드렸죠? static 파일들을 가지고 올건데.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/13f2abcb-63a5-4a07-b042-cb9e5ee922dc.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/6b57ca30-46ac-44da-9079-1f956cd82c91.png)](undefined)


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/268bd380-a34c-4f9b-bc7b-cfc9d533a19f.png)](undefined)


여기 이렇게 써준 static을 가지고 올건데


뭘 가지고 오고 싶냐면


css 폴더 안에있는 요녀석을 가지고올거다.


라고 템플릿 언어로써 작성한다고 말씀 드렸어요

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/b451ec2e-5863-4796-ae5f-905c79f487f5.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/d63c9b80-8744-465f-b3bf-5d61b688b8d7.png)](undefined)


이런식으로 쓰면 bootstrap와 관련된 것을 쓸 수 있는 것.


‏‏‎ ‎


script도 한 번 가지고 와볼까요?

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/9b3b678d-61d3-448a-861a-d14d21f5b9d7.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/edd95552-0d39-4b7f-8382-5a91c5990dbe.png)](undefined)


‏‏‎ ‎


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/79fce636-90f8-4083-b029-0433e81706fe.png)](undefined)


스크립트 민. js 를 가져와 보도록 할게요.


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/5ea79bb4-e703-4d29-8c20-8358fea554cc.png)](undefined)


javascript안에 있는 요녀석을 가지고 올거다


이런 식으로 가지고와보겠습니다.


아 href가 아니고 src겠쬬?

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/24aec02e-d78f-4f68-b9ec-3687ed496e82.png)](undefined)


이런식으로 bootstrap을


다운로드 받아서 static으로써 가지고 왔습니다.


이렇게 되면 부트 스트랩을 사용할 수 있게 되는 것인데,


꾸밈 요소들을 복 붙 하는 것 만으로도 쓸 수 있게 된 것입니다.


‏‏‎ ‎


일단 뭘 가지고 와볼가요?


간단하게 뱃지?

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/df28f6b0-15f7-4935-b455-30e7da981490.png)](undefined)


파란색을 가져와볼게.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/9186d62e-95da-4b99-a36a-89fcfa0fa11c.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/eb44d39f-b0ee-4ff0-952d-be12138c0bc2.png)](undefined)


이렇게 가지고 와주고


runserver를 통해서 확인을 해보자.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/d1064559-8fcd-4af0-999f-721cf28291c3.png)](undefined)


이렇게 해서 primary라고 하는 뱃지가 잘 가지고 와졌다라고


확인할 수 있음.


‏‏‎ ‎


자 근데 우리가 가지고 온 이 코드를 잘 보세요.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/9930ef76-9b81-48f5-a893-077130252567.png)](undefined)


라고 쓰여있죠? 참고로 이 부트스트랩은 대부분의 컴포넌트들의 어떤 설정들을 이 class를 통해서 지정을 해주는데, 우리가 가져온 이 코드에서는 클래스가 badge 그리고 bg(백그라운드)-primary라고 되어있음.


badge -> 우리가 가져온 component가 뱃지입니다. 라는 뜻


bg-primary -> 우리가 가져온 컴포넌트의 색깔이라고 보면 됨.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/25af7142-0818-437c-ab83-580258eacf56.png)](undefined)


저렇게 색상마다 이름을 붙여준 것임.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/676ee2ee-4fcd-4439-ba94-b7140adbeeea.png)](undefined)


이렇게 하면

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/52263e3e-ec43-43f9-99b5-d9f56200eae8.png)](undefined)


‏‏‎ ‎


빨간색이 뜨겠쬬?


‏‏‎ ‎


다른 컴포넌트도 가져와볼까?


카드라는 것도 있음.


카드도 한 번쯤 봤을만한 컴포넌트라고 보면 된다.


쭉 내려보면 카드 자체도 종류가 꽤 있는데 image에 대한 간략한 설

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/cd987d6a-fa06-40a6-8856-468b1c134711.png)](undefined)


이미지 글 버튼 이렇게 하나의 박스에 들어있는 것을 카드라고 한다.


이거도 그냥 코드 복붙하는 것 만으로도 쉽게 가져올 수 있음.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/6daaf770-870e-4d4a-93f5-371d017a619d.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/043dd9c8-048e-48bd-b320-de366f555b17.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/50fc5eb9-d7a6-4089-a4ad-7308c7d83192.png)](undefined)


‏‏‎ ‎


당연히 아직까지는 이미지를 설정 안해주고 어떤 이미지도 안가져왔기 떄문에


이런식으로 이미지가 깨지지만


아무튼 이렇게 가져올 수 있따는 것임.


‏‏‎ ‎


alert도 가져와볼까?

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/8f12720b-3395-4f28-b4eb-9f86543f58e9.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/aa0bce3c-1282-44a4-9c79-acc0d20b4863.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/226059cc-3573-4982-b65d-f22996cc2a00.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/c6019fc9-a81d-4af5-8635-c7f3d68c7659.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/3bd4209a-e8b0-4622-8d0e-e91664e584ce.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/23ed69a5-0054-4913-8afd-e1ba2df58b17.png)](undefined)


‏‏‎ ‎


이런식으로 잘 가져와진 것을 확인할 수 있음.


‏‏‎ ‎


‏‏‎ ‎


‏‏‎ ‎


‏‏‎ ‎

# STEP 11 Bootstrap (3)


여기서 부턴 진짜 간략한 메모 들어갑니다.


‏‏‎ ‎


왼쪽으로 너무 치우처져 있음.


'


부트스트랩은 정렬기능도 제공함.


container라는 것이 있음.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/c6becd41-d54e-4423-883f-0828698d1624.png)](undefined)


이 컨테이너 클래값만 주어도


이 div 태그로 감싸져 있는 것을 자동으로 정렬시켜준다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/e635d707-dee6-433a-8c06-978dbbe92b96.png)](undefined)


얘네를 통으로 깜싸주어

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/a5b267d0-1977-4274-b9cf-285a872b365e.png)](undefined)


보기 편해짐.


‏‏‎ ‎


부트스트랩으로 레이아웃 정렬도 할 수 있다는 얘기다.


‏‏‎ ‎


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/b0cbecbf-0f54-4db5-bf31-360cc2e02b49.png)](undefined)


이건 그냥 필요한 사람만 듣고 흘려들어도 된다.


부트스트랩이 컴넌트 어떻게 배치하는지에 대한 원리라고 보면 된다.


부트 스트랩은 예를 들어서

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-ohio.s3.us-east-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/17173a80-9fc1-458f-8a15-bf341fd8ebdb.png)](undefined)


‏‏‎ ‎


이거는 총 12등분으로 나뉘어져 있다고 한다.


‏‏‎ ‎


그리고 CDN 방식으로 bootstrap 쓰는 방법을 알려줌.


‏‏‎ ‎


CDN 보다는 static 파일을 찍어주는 것이 더 좋음.


(다운로드 받아서)


‏‏‎ ‎

# STEP 12 Template 언어

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-ohio.s3.us-east-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/8b108af5-a719-47b3-a25e-6d1b426694a7.png)](undefined)


여기까지가 개념적인 내용.


‏‏‎ ‎


템플릿 언어를 통해서


html을 통해서 어떻게 url 사이를 이동할지를 알려줄 것


그리고 template 상속을 통해 어떻게 더 적은 양으로 코딩할 수 있는지를


알려드릴게요.


프로그램의 기본 세팅은 bootstrap을 static으로 가져오고


container로 감싼 hello, bootstrap으로 띄우는 것 까지 해봤음.


‏‏‎ ‎


저희가 원하느 ㄴ컴포넌트를 복붙해서 ㅏ져와봤죠.


Navbar라는 녀석을 가져와볼게요.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-ohio.s3.us-east-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/2097233f-9758-408d-bd9d-dd3dc74e5c48.png)](undefined)


위에 저거를 Navbar라고 함.


척 보면 아시겠죠?


어디서 본 적이 있죠?


이걸 Nav bar 라고 하는데 가져와볼게요.


복붙 하는 것 만으로도 프로젝트에 잘 적용이 된다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-ohio.s3.us-east-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/c33cb2ff-483a-4587-906e-608ffcfd06a8.png)](undefined)


Nav bar 색깔 바꾸기

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/585fe2ae-5ecb-40ac-929b-fd6108e4a83c.png)](undefined)


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-ohio.s3.us-east-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/5000d2e7-7bb9-4674-8e8e-a9a6f438023c.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-ohio.s3.us-east-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/7376a11e-bafc-499d-991b-574accbf8690.png)](undefined)


검은색으로 하고싶으니 bg-dark로 할 것임.


‏‏‎ ‎


이번 수업시간에는 저런 위에 버튼들은 안할거임.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-ohio.s3.us-east-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/f525c26b-6da2-4c97-8dcd-68250739a6a6.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-ohio.s3.us-east-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/5bd8f219-3cd4-4411-9264-41498107c793.png)](undefined)


이렇게 코드들을 날려준다.


너무 많이 날렸

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-ohio.s3.us-east-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/52901781-fd1d-4e4e-92e0-7590b7edd76d.png)](undefined)


몇개만 남기고


다시 해보자.


그러면 Home Link 두개가 잘 남은 것을 볼 수 있음.


문자도 좀 바꿔볼까? About 페이지를 하면 About

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-ohio.s3.us-east-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/bbc59671-5764-4a91-a011-d3280e6143d5.png)](undefined)


About 버튼을 만들고


Navbar는 My Site로 바꿀거임.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/6537c256-b657-4180-8553-7e5924942566.png)](undefined)


이런식으로 바뀌었다.


‏‏‎ ‎


자 다른 것도 가져와 볼게요.


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-ohio.s3.us-east-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/87734654-3369-4a31-b3c4-37ad11827ef6.png)](undefined)


alert additional content도 가져와볼

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-ohio.s3.us-east-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/63185626-4b2b-47a2-aede-94a22874e114.png)](undefined)


‏‏‎ ‎


홈페이지니까 페이지 입니다. 이런식으로 간단하게 만들어 보도록 할게요.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-ohio.s3.us-east-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/1bc94c73-d3eb-4a45-a94b-dda4aaaa1437.png)](undefined)


‏‏‎ ‎


home이랑 about 눌렀을 떄 원하는 페이지로 이동하게 해주는 것이


template 태그임.


이런식으로 간단하게 만들었음.


이렇게 만들었는데 우리가 원하느 ㄴ것은 이 About을 눌렀을 때 /about url통해서 얻을 수 있느 ㄴhtml로 이동하길 원하

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/3a7c256d-01bc-43b8-b92c-1718c6a3759e.png)](undefined)


‏‏‎ ‎


home 눌렀을 때 이 url로 가길 원함.


이걸 해주는게 template 태그라고 보면 된다.


‏‏‎ ‎


지금까지 알고있는 지식으로 about 페이지를 만들어보자.


‏‏‎ ‎


이번시간에는 url 패턴에 이름도 지정해주어야함.


name space를 지정해준다.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/0b0c940f-03b5-4dae-80a8-68f86bc96c20.png)](undefined)


‏‏‎ ‎


views.py의 about을 만들어 줘야겠죠?

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/ff202618-e4f9-4ca4-bb7b-525bca6e893e.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/bd5a363b-f3d6-4936-9877-7ad6dec92b21.png)](undefined)


복붙해서 고쳐준다.


‏‏‎ ‎

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/66e66f6d-c668-4469-b890-f1ece8e87f93.png)](undefined)


about은 그냥 about 페이지 입니

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/ca97d9af-8155-415e-a844-19a78c6626e9.png)](undefined)


about.html을 추가해준다.


(home.html을 그대로 가져왔음)


그리고 그 안에 글자들만 살짝 바꿔준다.


My

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/fc10f2e7-289c-4f9e-ad8d-54c684a8d5cc.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/d69659c1-b747-46eb-9c8d-b9b12bf672d4.png)](undefined)


‏‏‎ ‎


이런식으로.


그럼 실행을 시켜주자.


이렇게 하면 우리가 아는 선에서 /about을 설계한게 이정도가 될 것임.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/46860afc-177f-4946-923b-9ea26ac9437f.png)](undefined)


주소에 about을 입력했을 때 이렇게


‏‏‎ ‎


아무것도 입력 안하면

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/b3e946f4-b73a-47e5-b7e7-3828a50bde3a.png)](undefined)


이렇게


‏‏‎ ‎


home 눌렀을때 홈페이지 화면 뜨고 about 누르면


저 어바웃입니다 화면을 뜨게 만들고 싶은 거잖아


우리는 이것을 template 언어를 통해서 해보도록 하겠습니다.


‏‏‎ ‎


template 언어는 {% %}로 감싸준채 표현한다고 했음.

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/ebcd326c-ed94-4cbc-9894-eb5762179a70.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/3e7e5a09-ba47-429e-97fa-6311caedfa13.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/5a660a4e-a74e-4a64-a68e-5262bf40e5bb.png)](undefined)


어떤 이 a태그가 눌렸을때 어떤 url로 이동하고 싶어

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/6c797b4e-9d25-458a-8927-3abaad6ba062.png)](undefined)


어떤 url로 이동하고 싶은데, 그 url은 urls에서 이름으로 지정한 about이야!


라고 이런식으로 작성하면 됩니다.


어렵지 않죠?


‏‏‎ ‎


‏‏‎ ‎


home도 마찬가지

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/55db845f-e741-4a9d-8536-ce9d28b73ab5.png)](undefined)


이 about이라고 하는 녀석을 눌렀을 때 저기 a태그의 href 여기로 이동할건데 어디로 이동할거냐면 장고가 관리해주는 url중에서 about이라고 하는 name space를 가지고 있는

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/5dd91d3b-303b-4852-8106-a0325908a8dc.png)](undefined)

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/abca0d89-0976-403e-b52b-b5702de641f2.png)](undefined)


이 url로 이동할거야.


a태그의

[![회사소개사이트 Static 부터 대략적 image](https://slid-users-assets-v1-seoul.s3.ap-northeast-2.amazonaws.com/public/capture_images/ad2b5de9f8ed4a20aa1a281b87fe2ead/4a54c253-cae8-400c-8d60-eb24c6a139b8.png)](undefined)


‏‏‎ ‎
