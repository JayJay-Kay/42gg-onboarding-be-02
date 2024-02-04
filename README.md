## 42gg-onboarding-be-02

### EX00 게시판 CRUD 만들기

**jpa entity class 만들기**
@Entity (JPA 찍먹)
Post entity class 생성
db에 해당 Post 클래스와 매핑되는 table insert query문 만들기 (post table 생성)
매핑이 잘되었는지 validate 옵션으로 확인(ddl auto로 table 생성 x)

**@RestController**
GET 매핑
POST 매핑
DELETE 매핑
PUT 매핑

### EX01  DB 공부

참고 자료

https://opentutorials.org/course/3883

https://opentutorials.org/course/3161


# 게시판 주요기능

1. 글쓰기 (/borad/save)
2. 글목록 (/board/)
3. 글조회 (/board/{id})
4. 글수정 (/board/update/{id})
   - 상세화면에서 수정 버튼 클릭
   - 서버에서 해당 게시글의 정보를 가지고 수정 화면 출력
   - 제목, 내용 수정 입력 받아서 서버로 요청
   - 수정 처리
5. 글삭제 (/board/delete/{id})
6. 페이징처리 (/board/paging)
