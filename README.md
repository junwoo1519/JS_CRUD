# JS_CRUD
자바스크립트로 만드는 CRUD

1 일차 CRUD 를 위한 테이블 구조 짜기
- scss를 사용하려 했는데 (index.html:1 Refused to apply style from 'http://localhost:63342/workspace/JS_CRUD/css/style.scss' because its MIME type ('text/x-scss') is not a supported stylesheet MIME type, and strict MIME checking is enabled.) 에러 발생 해결중 -> CSS경로를 SCSS가아닌 일반 CSS 파일료 변경하니까 해결됨 로컬 브라우저 자체가 SCSS를 인식 못한다고 생각함 SCSS로 작성하고 처리된 CSS 파일로 적용중

2 일차 CSS로 테이블 꾸미기 및 create 페이지 작성
- button 태그에다 link를 걸려면 onclick를 걸어 실행하자

3 일차
- 글작성을 해보려 했지만 아직 페이지가 이동하는 개념을 모르는 것 같다
일단 게시글작성 페이지 내에서 localStorage로 작성 된 것을 저장 해보고 응용 해보도록 하자 
