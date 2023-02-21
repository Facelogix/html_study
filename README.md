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

  
