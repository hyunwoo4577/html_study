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
    <h2>23.02.17-HTML- 시멘틱태그</h2>
   <dl>
     <dt>레이아웃,이미지,비디오 기본&활용 공부</dt>
     <dd>span 2개 이상의 인라인 요소를 묶을 때 사용하며 의미없는 디자인 위치를 묶을 때 사용한다.</dd>
     <dd>a href=" " 링크 주소 속성 href 속성 안 값은 링크 목적지 주소를 정확히 입력해야 한다.</dd>
     <dd>a href=" " 절대경로와 상대경로</dd>
   <dl/>
    <h2>23.02.19 -HTML- 시멘틱태그</h2>
     <a href=" "> 링크 주소 속성
   <dl>
      <dt>href 속성 안 값은 링크 목적지 주소를 정확히 입력해야 한다.</dt>
      <dd>링크주소는 일반적으로 '**절대경로**', '**상대경로**' 로 나뉜다.</dd>
      <dd>크주소로 메일, 전화번호를 작성한다.</dd>
      <dd>메일은 mailto:메일아이디@메일주소 로 작성한다.</dd>
      <dd>전화번호는 tel:국가번호.전화번호앞자리.전화번호뒷자리로 작성한다.</dd>
   </dl>
  <hr>
  <h2>23.02.21-HTML-form_</h2>
  <form action="#" method="get">
  <fieldset>
  <legend>form 퀴즈</legend>
  <span>다음 중 label for 와 연관된 input 속성은?</span><br>
  <label><input type="radio name"quiz" value="id">1. id</label><br>
  <label><input type="radio name"quiz" value="class">2. class</label><br>
  <label><input type="radio name"quiz" value="name">3. name</label>
  
   <legend>form퀴즈2</legend>
   <span> 다음 중 활성화 시 제거되는 미리 제시된 텍스트는?</span><br>
   <label><input type="radio name"quiz" value="id">1. id</label><br>
  <label><input type="radio name"quiz" value="class">2. class</label><br>
  <label><input type="radio name"quiz" value="name">3. name</label>
  </fieldset>
  </form>
  <hr>
  <h2>23.02.22-HTML-form_</h2>
  
  <hr>
  <h2>23.02.23-CSS_기초_</h2>
  <h3>css진행 전 주의사항</h3>
  <p>사용자가 css로 웹을 디자인 하기 전 HTML 이 먼저 디자인된 모습을 가져선 안된다.
    => css 초기화 작업(reset css) </p>

  <p>내부스타일시트(HTML head 내에 style태그)-그 파일에서만 사용가능
    외부스타일시트(css별도파일생성 head내에 link연결)-외부이기 때문에 다른 파일에도 링크해서 반복 사용가능</p>
  <p> block : 기본w100%, 줄바꿈, 크기를 가질 수 있다.
      inline : 내용크기만큼 너비인식, 줄바꿈x, 크기x </p>
  <h3> 자식 선택자 </h3>
  <p>특정 태그에 묶인 자식 요소를 선택 시 사용한다. +(꺽새)로 표현한다</p>
  <h3> 자손 선택자 </h3>
  <p>특정 태그에 묶인 자손 요소를 선택 시 사용한다. 한 칸 공백으로 표현한다(상황에 따라 자식과 자손을 모두 인식)</p>
  <h3> 인접형제선택자 </h3>
  <p>특정 태그의 다음 형제 요소를 선택한다. +(더하기)로 표시한다</p>
  <h3> 그룹선택자 </h3>
  <p>- 2개 이상의 선택자를 묶을 때 사용한다. ,(콤마)로 표시한다.</p>
  <h3> 형제선택자 </h3>
  <p>- 특정태그에 다음에 오는 모든 형제들을 선택한다.~(물결)로 표시한다.</p>
  <h3> 글꼴지정 </h3>
  <p>글꼴적용방법1. 사용자 컴퓨터에 내장된 글꼴 불러오기
     (위)주의사항 : 해당글꼴이 접속한 사용자에게 없을 경우 글꼴이 임의의 다른 글꼴로 대체될 수 있다.
     font-family: '맑은 고딕','sans-serif';
     font-family: '궁서체','serif';

     글꼴적용방법2. 웹 주소 글꼴을 가져오는 방법
    https://fonts.google.com/
    @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500;700&display=swap');-위치:가장 위
    font-family: 'Noto Sans KR', sans-serif;-위치:CSS초기화 작업 상단
    폰트 사이즈 px=>em 후에 {font-size:1.375em;}</p>
  <h2>23.02.24-CSS_HTML</h2>
      
       
