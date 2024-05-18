# website
![image](https://github.com/seyoki/website/assets/159132449/4a8cead5-a2c1-4298-b3e3-90ad13fa3075)
게시글 조회
게시글 수정
게시글 삭제
댓글 
댓글 수정
댓글 삭제
프로필 이미지
회원가입
회원 정보수정
로그인
회원탈퇴
카테고리

springboot 를 처음다뤄보면서 수업때와는 또다른 느낌을 받았습니다. 저혼자서 하다보니 어려움도많았고 물어볼 사람도 없었기에 혼자 헤쳐나가면서 많은 도움이 되었습니다.
겪은 만큼 성장했다고 생각됩니다.
현황: html은 완성해논상태 , 멤버는 아직 수정중, 게시판은 다 만들었음, 댓글은 아직 확인못해봄, 쇼핑몰 이미지도 만들어야하는데...
큰일이다
DB: tablename= notice
table object 공지사항/게시글 데이터가 저장된페이지
name
id int 
reg_emp_no varchar(6)
reg_dttm datetime
upd_emp_no varchar(25)
upd_dttm datetime
category varchar(20)
title varchar(200)
content text 
