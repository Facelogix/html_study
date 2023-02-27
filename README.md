<h1>반응형 웹디자인&웹퍼블리셔 양성과정 버전기록</h1>
<h2>ex) 날짜 - 제목 - 요약</h2>
<h2>23.02.13 시작- HTML</h2>
<p>H1~H6, p, br, inline, block</p>
<p>H1~H3은 검색키워드로 활용가능하다. H4~H6 꼭필요한 경우만 이용하거나 권장안함</p>
<p>block과 inline태그는 의미에 맞게 외부/내부 구조로 구성해서 사용해야 한다.(의미 중첩되지 않도록)</p>
<hr>
<h2>23.02.14 - html - 문서태그</h2>
<p> &lt;,&gt;,<em>em</em>,<strong>strong</strong>, <sub>sub</sub>, <sup>sup</sup>, <del>del</del>, blockquote, q, address, code</p>
<p>gnb, lnb, snb, fnb, breadcrum</p>
<blockquote cite="html-다양한 문서 구조 태그+블록과 인라인 기본&활용 공부"> 유나쌤블로그 참조 - https://webty.tistory.com/85</blockquote>
<hr>
<h2>23.02.15 - html - 목록태그</h2>
<ul>
  <li>ul, ol, li 순서있는 목록 없는 목록 구분 확실히 해야함.</li>
  <li> ol 순서가 있는 목록 </li>
  <li> ul 순서가 없는 목록 </li>
  <li> 형제 유형은 일치해야 한다 </li>
  <li> 나머지 태그는 그 자식, 자손 태그에 삽입해야함</li>
</ul>
<dl>
  <dt><strong>정의형 목록태그</strong></dt>
    <dd>dl, dt, dd</dd>
    <dd>dl은 dt, dd 의 부모태그로만 사용</dd>
    <dd>dt가 먼저 쓰고 뒤로 dd를 쓴다</dd>
</dl>

<hr>
<div class="study">
  <h2>23.02.16 - html - 레이아웃태그</h2>
  <dl>
    <dt>레이아웃태그</dt>
    <dd>div</dd>
    <dd>span</dd>
    <dd>시멘틱태그</dd>
      <ul>
        <li>header : </li>
        <li>section</li>
        <li>nav</li>
        <li>aside</li>
        <li>arcticle</li>
        <li>footer</li>
        <li>main</li>  
      </ul>
  </dl>
</div>

<hr>
  <h2>23.02.17 - html - 링크태그 </h2>
  <p>절대경로, 상대경로(주로쓰임) : 끝에 확장자를 반드시 붙여야함
  </p>

  <hr>
  <h2>23.02.20-Table</h2>
<hr>
  <table>
  <thead>
    <tr>
      <th>구분</th>
      <th>태그명</th>
      <th>의미</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="3">block</td>
      <td>&lt;tr&gt;</td>
      <td>가로행 태그</td>
    </tr>
    <tr>
      <td>&lt;td&gt;</td>
      <td>내용(열)태그</td>
    </tr>
    <tr>
      <td>&lt;th&gt;</td>
      <td>제목(열)태그</td>
    </tr>
  </tbody>
  </table>
      
<hr>
<h2>23.02.21-html-form </h2>
<form action="#" method="get">
  <fieldset>
    <legend>form 퀴즈</legend>
    <span>1. 다음 중 label for 와 연관된 input 속성은?</span><br>
    <label><input type="radio" name="quiz" value="id">1.  id</label>
    <label><input type="radio" name="quiz" value="class">2.  class</label>
    <label><input type="radio" name="quiz" value="name">3.  name</label><br>
    <hr>
    <span>2. 다음 중 옵션의 목록이 부주제로 크게 분리될 경우 옵션을 묶는데 사용하는 태그는 무엇인가?</span><br>
    <label><input type="radio" name="quiz2" value="optgroup">1. optgroup </label>
    <label><input type="radio" name="quiz2" value="submit">2. submit</label>
    <label><input type="radio" name="quiz2" value="select">3. select</label>
  </fieldset>
</form>
<hr>
<h2>23.02.22-css-style</h2>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500;700&display=swap');

html,body,h1,h2,h3,h4,h5,h6,p,blockquote,ul,ol,li,dl,dt,dd,address,video,/* block */
strong,s,del,em,sub,sup,q,code,img,a, /* inline */
table,tr,th,td,thead,tbody,tfoot,/* table */
form,fieldset,legend,input,button,label,textarea,select,option,/* form */
header,main,footer,section,article,aside,nav,figure,figcaption,div,span{
    /* 글꼴적용방법 1. 사용자 컴퓨터에 내장된 글꼴 불러오기 */
    /* (위)주의사항 : 해당글꼴이 접속한 사용자에게 없을경우 글꼴이 임의의 다른 글꼴로 대체될 수 있다. */
    /* font-family:'맑은 고딕',sans-serif; */
    /* font-family:'궁서체',serif; */

    /* 글꼴적용방법 2. 웹 주소 글꼴을 가져오는 방법 */
    font-family: 'Noto Sans KR', sans-serif;    
    margin:0; padding:0;
    font-size:1.0rem;
    font-weight:normal;
    font-style:normal;
    line-height:1.0;
    list-style:none;
}
a {text-decoration:none; color:#000;}
table,tr,th,td {border-collapse:collapse;}
button {cursor:pointer; border:none; background:none;}
/hr
/* header------------------------------------------------------------------ */
header {}
header h1 {}
header h1 a {}
header h1 a img {}
header nav {}
header nav a {font-size:1.063em;}
header .lnb {}
header .lnb a {}
/* footer -------------------------------------------------------------------*/
footer {}
footer .ft_top {}
footer .ft_top .ft_left {}
footer .ft_top .ft_left a {}
footer .ft_top .ft_right {}
footer .ft_top .ft_right a {}
footer address {}
footer address+p {}
/* main ---------------------------------------------------------------------*/
main {}
/* 공통 배경-------------------------------------- */
main .bg {background-color:#f1f1f1}
main .bg_w {}
/* 현재 페이지 경로 ----------------------------------*/
main .bg .top {}
main .bg .top dt {}
main .bg .top dd {}
main .bg .top dd span {}
main .bg .top dd em {}
/* 경영이념 제목 -------------------------------*/
main .bg_w .title {}
main .bg_w .title h1 {font-size:2.5em;}
main .bg_w .title p {}
/* 경영이념 내용 ---------------------------------*/
main .bg .contents {}
main .bg .contents p {}
/* 경영이념 vision------------------------------- */
main .bg_w .contents {}
main .bg_w .contents h2 {font-size:1.375em;}
main .bg_w .contents p {}
/* rudduddlsua goal, strategy---------------- */
main .bg .contents h2 {}
main .bg .contents ul {}
main .bg .contents ul li {}
main .bg .contents ul li h3 {}
main .bg .contents ul li p {}
<hr>
<h2>23.02.24 - css -  </h2>
  CSS : 크기/여백/테두리 속성 + 인라인, 블록, 인라인-블록 개념
  CSS : 글자 표현 속성(글꼴, 크기, 자간, 행간, 색상)
  CSS : 폰트어썸(Font-awesome) 연결과 사용법
  
 <hr>
<h2>23.02.27 - css - float </h2>
  .warp {
    background-color: aqua;
    width:500px; 
    /* 자식에 float적용 시 생기는 부모 오류 해결법 */
    /* 1. 높이강제부여 */
    /* height:100px; */
    /* 2. 자식높이재인식 */
    /* overflow:hidden; */
}
    /* 3. 가상자식생성 */
.warp::after {clear:both; display:block; content:'d';}
.warp .a {
    border:5px solid red;
    float:left;
}
.warp .b {
    border:5px solid blue;
    float:right;
}
.warp .c {
    border:5px solid green;
    clear:both;/* 이전 형제 float 위치 제거 -> 새로운 행 선언 */
    /* css는 html 순서와 상관없이 디자인에 필요한 순서를 재창조 할 수 있다 */
}

.warp .z {
    width:100px; height:100px;
    background-color: yellow;
}
.next {
    width:500px; height:250px;
    background-color: gold;
}
<hr>
  
