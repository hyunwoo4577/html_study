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
  <p>inline-block 요소 특징</p>
  <p>CSS display 명령으로 적용할 수 있다.
  크기, 여백 적용이 가능하다.
  줄바꿈이 되지 않고 옆으로 나열된다.
  인라인-블록 요소 사이 기본 공백이 포함된다.
  margin 바깥쪽 여백, padding 안쪽 여백
  * padding, margin 안쪽/바깥쪽 의미만 다를 뿐 작성방법이 동일합니다.
  * 속성의 값을 몇개로 작성하느냐에 따라 인식하는 방향이 다릅니다.
  * 값이 0일때는 단위를 생략해도 됩니다. 1 이상일 경우는 반드시 단위를 작성해야 한다.
  * 값을 1개 작성할 경우 
  *상/하/좌/우에 모두 동일한 값이 적용된다.<p>
  <h2>23.02.26-CSS_HTML</h2> 
  <p>border ex)
  border-top:1px solid #aaa;
  border-bottom:1px solid #aaa;  
  border-left:1px solid #aaa;
  border-right:1px solid #aaa;</p>
 <h2>23.02.24-CSS_HTML</h2>
  <p>white-space:nowrap;/*한줄처리*/
    overflow:hidden; /*정해진 크기 안에서만 보이기*/
    text-overflow:ellipsis;}
    /*외부처리를 말줄임...*/
    /* 글이 넓이가 넘으면 말줄임    
    text-overflow: ellipsis;
    white-space:nowrap;
    overflow: hidden; */
    /* 태그에 순서와 상관없이 보낼때 position을 쓴다 */</p>
    <p>width:1px; height:15px; background-color: red; content:''; display:inline-block; position: relative; right:-5px; top:2px}
    /* {content: '|';display: inline; padding-left: 10px;} 위 방법 단점 : 글자크기보다 작거나 크게 할 수 없다.
    (디자인다양성부족) 움직일때는 position으로 움직인다 */</p>
 <h2>23.03.20-CSS_HTML</h2>
  <p>자바스크립트의 데이터 종류
 
1. 원시 데이터
* 참조를 이루지 않고 특정 변수에 바로 데이터값이 저장되어있는 경우를 뜻합니다.
* 각 원시데이터 특징에 따라 한 가지 값만 담을 수 있습니다.
* String, Number, Boolean, Null, Undefined, Symbol(ES6) 총 6개로 이루어져 있습니다.
* String(문자)
* number(숫자)
* boolean(논리형)
* null(없음)
* undefined(정의되지 않음)
2. 참조 데이터
* 객체, 배열, 함수 등과 같은 Object 형식의 타입입니다.
* 변수의 크기가 동적으로 변합니다.
* 원시 데이터와 다르게 여러 속성의 모음을 저장할 수 있습니다.
* 원시 데이터 타입을 제외한 나머지는 모두 참조 데이터입니다.
3. (ES5) 변수 선언 var
* ES5 이전버전부터 사용하던 변수 지정방법입니다.
* 데이터를 저장하는 장소 or 읽고 쓰고 할 수 있는 장소
* 변수는 한번에 한가지 값만 저장할 수 있습니다.
* 새로운 값을 대입하면 기존 값은 삭제되게 됩니다.
   다른 연산자 등을 이용하면 다른 결과를 낼 수도 있습니다.
변수는 이럴 때 사용해요!
 특정 사이트의 로그인 유무를 변수에 저장합니다.
 사용자가 선택한 메뉴 항목도 변수에 저장합니다.
 출력되는 메뉴 항목도 변수에 저장합니다.
 게임에서 현재 기록 점수도 변수에 저장됩니다.
 쇼핑몰 장바구니에 담겨있는 상품목록도 변수에 저장됩니다.
 게시판에 게시물 목록 들도 변수에 저장되있는 내용을 출력한겁니다.
 변수 이름을 위한 규칙들
변수의 이름은 반드시 문자, 달러기호($) 언더스코어(_) 시작합니다.
절대로 숫자로 시작해서는 안되요!
변수의 이름은 대시(-)나 마침표(.)같은 기호들을 사용할 수 없습니다.
키워드나 예약어는 사용할 수 없어요. 
break, case, catch, continue, default, delete, do, else, finally, for,if, instanceof, new, reutrn, switch, this, throw, try, function, typeof, var, void, while, with, preventDefault, length, click, mouseover, setInterval, css 등..
모든 변수는 대/소문자를 구별합니다. score와 Score는 다른 변수에요!
변수가 저장할 정보의 종류를 잘 표현하는 단어를 사용합시다
사람의 이름은 firstName 성은 lastName 나이는 age
변수의 이름에 두 개이상의 단어를 사용할 때에는 뒷 단어의 첫 글자를
대문자로 사용하자 또는 단어를 언더스코어(_)로 연결해도 됩니다
ex) firstname X firstName O first_name O

1. 변수(let)
* 기존 변수 선언 키워드 var 의 단점을 해결한 새로운 ES6 이후의 변수 선언 키워드 let
* 특정 데이터를 저장할 때 사용한다.
* 한번 선언된 변수명은 중복 사용할 수 없다.
2. 상수(const)
* 변하지 않는 값 상수를 담는다.
* 선언과 동시에 대입 값을 작성해야 한다.
* 초기 데이터 외에 다른 데이터를 대입할 수 없다.
* 중복된 상수명은 사용할 수 없다.
