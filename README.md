  <h1>반응형 웹디자인&웹퍼블리셔 양성과정 버전기록</h1>
   <p>23.02.13 시작 - HTML</p>
   <p>H1~H6, p, br, inline, block</p>
   <p>H1~H3는 검색키워드로 활용가능하다. H4~H6 꼭필요한 경우만 이용하거나 권장안함<p>
   <p>block과 inline 태그는 의미에 맞게 외부/내부 구조로 구성해서 사용해야 한다.(의미 중첩되지 않도록)</p>
   <hr>
   <h2>23.02.14 - HTML - 문서태그 + 내비게이션 </h2>
   <p><em>em</em>,<strong>strong</strong>, blockquote, q, address, code, hr, del, s, sub, sup</p>
   <p>gnb, lnb, snb, fnb, Breadcrumbs</p>
   <p>유나쌤 블로그 참조 - https://webty.tistory.com/85</p> <blockquote cite="https://webty.tistory.com/85"> 
   <hr>
   <h2>23.02.15 - HTML - 문단태그</h2>
   <ul>
      <li>ul,ol,li 순서있는 목록 없는 목록 구분 확실히 해야함.<li>
      <li>li의 <em>형제태그</em> 은 li만 올 수 있으니 나머지 태그는 그 자식, 자손태그에 삽입해야한다.</li>
      <li>ol과 li사이에는 다른 태그를 넣으면 안된다.</li>
      <li>li태그의 자식은 블록, 인라인 모두 가능하다.</li>
      <li>h태그의 경우에도 연속되는 목록이면 li로 대체 가능하다.</li>
      <li>li의 형제는 li만 가능하고 다른 태그를 쓰려면 자식으로 사용한다.</li>
   </ul>
  <p>정의형태그인 dt,dd는 dl의 자식으로만 올 수 있다.</p>
  <p>낮은 레벨의 h를 대체해서 사용 할 수 있다.</p>
  <p>다른 태그는 dl안에 들어갈 수 없고 dt,dd에 넣어야 한다.</p>
  <div class="study">
   <h2>23.02.16 -HTML- 시멘틱태그, 그룹태그</h2>
   <dl>
    <dt>레이아웃태그 기본&활용 공부</dt>
    <dd>div는 2개 이상의 블록이나 인라인을 묶어 주는 태그이다.</dd>
    <dd>div는 구역임으로 반드시 class를 이용해서 이름을 지정해야한다. ex)div class="title_path_top"/div class="contents_btm"</dd>
    <dd>dt를 보이지 않게 숨길 수 있다 <dt class="skip"></dd>
   </dl>
