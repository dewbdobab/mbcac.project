# mbcac.project
team project test
## team project information
* 주제 : 열심히 하자
* 기간 : 3개월
  + 1 month : 분석
  + 2 month : 설계
  + 3 month : 구현
    - 1 week : 로그인
    - 2 week : 게시판
    - 3 week : 뉴스

#코드참고
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcac.board.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcac.board.BoardVO">
	<jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.addBoard(board)}"/>

{"added":${added}, "bnum":${added}}
