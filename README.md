# mbcac.project
team project test
## team project information
* 주제 : $\color{#ff0000}{\textsf{열심히 하자}}$
* 기간 : 3개월
  + 1 month : 분석
  + 2 month : 설계
  + 3 month : 구현
    - 1 week : 로그인
    - 2 week : 게시판
    - 3 week : 뉴스


 <a name="top"></a>목차  
1. [code1](#code1)  
2. [code2](#code2)  	
3. [code3](#code3)  	
4. [code4](#code4)  

## code
```jsp
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
```  
[github마크다운으로 색상 설정하기](https://gist.github.com/luigiMinardi/4574708d404cdf4fe0da7ac6fe2314db)  

<a name="code1">code1</a>  
```jsp
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
```  

```jsp
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
```  

```jsp
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
```  

<a name="code2">code2</a>

```jsp
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
```  	
```jsp
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
```  
<a name="code3">code3</a>

```jsp
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
```  	
```jsp
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
```  
<p>
<a name="code4">code4</a>

```jsp
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
```  
 [go to top](#top)

