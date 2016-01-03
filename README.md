# opentutorialsCSS
생활코딩 css 수업

**CSS란?**

HTML이 웹페이지의 '뼈'라면 CSS는 '살'이라고 할 수 있습니다. 즉 HTML이 웹페이지의 정보를 표현한다면, CSS는 HTML을 보기 좋게 디자인하는 역할을 하는 언어입니다.

따라서 CSS를 공부하려면 선행지식으로 HTML을 요구합니다. 물론 HTML을 많이 알고 있을 필요는 없습니다. HTML이 무엇이고, 태그는 어떻게 사용하는지만 알고 있으면 CSS를 배울 수 있습니다. 하지만, CSS의 대상이 HTML이라는 점에서 CSS에게 있어서 HTML은 필연적입니다. 

**코스소개**

**수업**

CSS에 대한 기본적인 내용을 전달합니다. 선택자나 박스모델과 같은 중요한 내용을 포함합니다. 특히 HTML이 정보를 CSS가 디자인을 담당하게 된 맥락과 그에 따른 적합한 사용방법에 유의하면서 청강해주세요.

**LESS**

CSS의 미덕은 간결한 문법구조입니다만, 간단한 것은 자유롭지 못합니다. 다시 말해서 기능성이 떨어진다는 것이죠. LESS는 CSS의 부족한 기능성을 보강해서 javascript와 같이 동적인 프로그래밍 언어의 기능인 변수, 함수와 같은 기능을 제공합니다. 유지보수의 공수가 드라마틱하게 줄어듭니다.

**SASS**

SASS는 LESS의 동일한 기능을 제공하는 다른 솔루션입니다. LESS에 대한 설명을 참조하세요. (바로가기)

**Twitter Bootstrap**

트위터에서 자신들의 웹서비스를 위해서 사용하던 UI 프래임웍을 오픈소스로 공개한 것이 Bootstrap입니다. 이것을 이용하면 HTML의 엘리먼트에 CSS 클래스 네임만 부여하면 그에 해당하는 디자인이나, 컴포넌트가 생성됩니다.

# CSS 수업

코스소개

CSS는 HTML을 꾸며주는 언어입니다.  CSS를 이용하면 HTML로 만들어진 웹페이지를 질서정연한 문서로 만들수도 있고, 복잡한 UI(User Interface)들의 결합체인 웹에플리케이션으로 만들수도 있습니다.

공부방법

HTML이 이해할 것은 별로 없는데 외울 것이 많다면,  CSS는 외울 것도 많고, 이해해야 할 것도 조금 많은 편입니다.  선택자나 박스모델 같은 것은 처음에는 이해하기 조금 어려울수도 있습니다. 

이러한 개념들을 이해했다고 해도 실제로 다양한 개념들이 복합적으로 얽혀 있어서 당분간은 안개속에 있는 것 같은 느낌이 들수도 있습니다.

따라서, 강의만 보고 CSS를 마스터 했다고 생각하면 안타깝게도 오해입니다.

직접 코딩을 하면서 여러가지 문제에 부딪쳐봐야 합니다.(머는 안 그렇겠어요? ^^) 그러다보면 CSS의 선택자들을 이용해서 재활용성을 높이는 것에 관심을 갖게 되고, 또 브라우저 간의 특성들에 익숙해지면서 자유자재로 웹페이지를 디자인할 수 있게 됩니다. 

특히, 정보 표현 언어로서의 HTML과 정보를 디자인하는 언어로서의 CSS라는 관계를 이해하는 것이 중요합니다. 이 둘의 역활을 질서정연하게 조화시키면 검색엔진 최적화, 코드의 재활용성, 협업능력의 향상과 같은 목표들에 도달할 수 있을꺼에요. 

무엇보다 중요한 것은 사전찾는 법, 검색하는 법, 질문하는 법입니다. 

이것들이야 말로 생활코딩의 커리큘럼들이 여러분에게 알려드리고 싶은 것들입니다. 

그 시작점이 한글화된 CSS 사전입니다. 생활코딩 CSS 사전은 지금 만들고 있습니다.

생활코딩 밖에서 CSS에 대한 정보를 얻을 수 있는 곳을 소개해드리면 이렇습니다. 

* css 한글 레퍼런스 (http://nsyang-textcube.blogspot.com/2009/06/css-%EC%82%AC%EC%A0%84.html)
* w3schools.com css reference (http://www.w3schools.com/cssref/default.asp)
* MDN CSS reference (https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

실습방법

타이핑해보지 않는 지식은 이론으로 머물뿐 경험이 되지 못합니다. 수업에서 등장하는 예제를 직접 타이핑해보세요. HTML 소개에서 했던 말을 그대로 옮겨봅니다. 

컴퓨터라는 것이 획 하나만 틀려도 엉뚱한 결과를 출력하기 때문에 이런 문제에 직면하면 당황하게 됩니다.

공부에 할애하려고 스스로에게 약정했던 시간을 훌쩍 넘어가면서 초조해집니다.

그런데 바로 그 순간에도 뇌는 HTML코드를 주시하면서 로직의 흐름,

문법적인 용법을 내 안으로 받아들이고 있다는 것을 기억하세요.

그 순간을 이겨내면 실력의 계단을 한칸 오른겁니다. 

## CSS란?

HTML이 정보를 표현한다면 CSS는 HTML을 시각적으로 꾸며주는 역할을 한다.

CSS를 통해서 기대되는 효과들

* 정보(HTML)과 디자인(CSS)를 분리할 수 있다.
* 정보를 수정하지 않고 디자인만 변경할 수 있다. (참고 : css Zen Garden)
* 검색엔진이 HTML을 해석 가능하도록 하기 때문에 더 많은 방문자들이 방문하도록 유도할 수 있다.
* HTML에서 디자인 분리함으로서 시각장애인을 위한 프로그램인 스크린리더가 HTML을 해석할 수 있도록 할 수 있다.

css Zen Garden http://www.csszengarden.com/

CSS는 HTML을 꾸며줌. HTML을 꾸며주는 언어가 별도로 존재하고 그 언어가 CSS 이다. 그러므로 HTML에 대한 어느 정도의 지식이 필요함.

전혀 모르면 html 공부를 해라.

## 실습방법과 개발도구

개발도구란?

개발도구란? 개발을 하는데 필요한 도구와 개발된 결과를 실행할 환경을 의미한다. HTML 수업에서 개발도구란 웹페이지의 소스를 만드는 에디터와 웹페이지를 실행할 웹브라우저와 같은 일련의 도구를 의미한다.

개발도구

**웹브라우저**
구글 크롬 사용(개발자 도구)

**인스펙터(inspector)**
* 웹페이지의 코드를 분석하고, 조작할 수 있는 도구
* 구글 개발자 도구 (Elements) 사용 https://opentutorials.org/course/580/2866

**에디터(editor)**
* 소스코드를 작성하는데 필요한 도구
* Aptana 사용 (http://www.aptana.com/) , 생활코딩 개발 도구 중 Aptana 편 참고 (https://opentutorials.org/course/128/2548)

**예제 사용법**

본 수업은 두가지 형태의 예제를 제공한다. 아래와 같다.

JSFIDDLE
라이브로 예제를 실행해 볼 수 있는 서비스다. 직접 코드를 변경 하면서 결과를 실시간으로 확인해볼 수 있다. 특별한 개발도구가 필요 없다는 것이 장점이다. 자세한 사용법은 생활코딩 수업을 참고하자.

생활코딩 jsfiddle 수업 바로가기(https://opentutorials.org/course/128/2833)
jsfiddle 바로가기 (https://jsfiddle.net/)

github.com
소스코드를 저장할 수 있는 서비스로 본 수업의 모든 예제 파일이 저장되어 있다. html 수업의 저장소 페이지로 이동한 후에 ZIP 파일을 다운로드하면 전체 코드를 다운받을 수 있다. (저장소로 바로가기)

## CSS의 사용

HTML에서 CSS 사용하기

1. inline 방식 (예제1)
    * 엘리먼트에 스타일을 직접 기술하는 방식
    * 셀렉트가 필요 없다.
    * CSS 선언이 분명해서 style tag 방식에 비해 엘리먼트에 영향을 주고 있는 CSS를 추적하기가 쉽다.
    * 코드가 많아지고, 의미와 디자인의 분리라는 CSS의 취지와 벗어난다.   
2. style tag 방식 (예제2)
    * style 태그에 기술하는 방식
    * inline 방식 대비 경제적으로 코딩할 수 있다.
    * 의미와 디자인의 분리라는 CSS의 취지에 부합한다.
3. 외부 파일 방식 (예제3)
    * CSS를 별도의 파일로 분리해서 링크하는 방식
    * 문법적으로는 style tag와 동일
    * 파일의 교체로 디자인을 변경할 수 있다는 점에서 유지보수가 편리하다.

html과 css서로 다른 문법 체계를 가지고 있음. 그러므로 브라우저에게 구별할수있는 규칙이 있음.

그 규칙을 배울 예정.

언제 무슨 방식을 쓰는가?? 제대로 된 코딩을하고 규모가 있는 것을 사용할때 style tag를 사용.

## 선택자

CSS의 효과가 적용될 태그를 지정
<pre>
Selector Declaration 
h1 {color:blue; font-size:12px; }

h1 = selector
괄호안 = Declaration

color = property
blue = value;
font-size = property
12px = value;
</pre>

Id 선택자

* id 속성은 전체 문서에서 하나의 태그를 식별하기 위해서만 사용됨
* 우선순위가 가장 높음
* css 선택자에서는 #을 사용해서 id임을 표시
* 다음 예제는 id값이 memo인 태그의 컨텐츠를 빨간색으로 표시하도록 함

Class 선택자

* class 속성은 일련의 태그를 그룹핑해서 하나처럼 제어하기 위해서 사용
* class 속성에는 공백으로 구분된 여러개의 class가 표시될 수 있음
* css선택자에서는 '.'을 사용해서 class임을 표시

type 선택자

* 특정 태그명을 가진 엘리먼트 전체를 제어하기 위해서 사용
* css선택자에서는 태그의 이름을 사용함

## 선택자의 조합

하위 선택자

* 특정 엘리먼트의 하위에 나오는 엘리먼트를 선택하는데 사용
* 부모가 먼저 나오고 자식이 나중에 나옴
* 공백을 통해서 부모와 자식을 구분

하나의 CSS선언을 여러개의 선택자에 적용하기

* 하나의 css선언을 여러 엘리먼트 셀렉터에 적용하고 싶을 때 사용
* 선택자와 선택자를 ',(콤마)'로 구분

자식선택자 -child selector

* 특정 엘리먼트의 직접적인 하위 엘리먼트에 대해서만 선택할 때 사용(하위 선택자와 다름)
* ie6는 지원되지 않음

## 스타일링

CSS는 웹페이지를 꾸며주는 언어다. 이를 위해서 다양한 효과들이 사용된다. 그 중에는 모든 엘리먼트에 공통적으로 적용되는 효과도 있고, 특정한 엘리먼트와 컨텐츠를 꾸며주는 효과도 있다. 스타일링의 하위토픽에서는 엘리먼트와 컨텐츠 별로 꾸미는 방법에 대해서 알아본다.

### 텍스트 꾸미기

**span 태그**

텍스트는 태그가 아니라 컨텐트이기 때문에 텍스트를 꾸며주기 위해서는 텍스트를 감싸는 태그가 필요하다. 줄바꿈 없이 일부 텍스트를 꾸며주기 위해서는 꾸미려는 텍스트를 <span> 태그로 감싸고 여기에 효과를 준다. 

**색**

텍스트에 컬러를 부여할 때는 color 효과를 사용한다. CSS에서는 색상을 지정하는 3가지 방법이 있는데 아래와 같다. 

* Hex       16진수로 색상 값을 표현, #ff0000 (붉은색), #00ff00(초록), #0000ff(파랑)
* RGB       붉은색, 초록, 파랑의 값을 조합해서 색상 값을 표현,  RGB(255,0,0), RGB(0,255,0), RGB(0,0,255)
* 별명       red, blue, green등 칼러코드 (http://www.somacon.com/p142.php)

**정렬**

텍스트를 정렬하기 위해서는 정렬하고자 하는 텍스트를 태그로 감싸고 이 태그에 text-align 효과를 지정한다. CSS에서는 4가지 형태의 정렬방식을 지원한다.

* left	    왼쪽 정렬
* right	    오른쪽 정렬
* center	가운데 정렬
* justify	양쪽 정렬, 텍스트 간의 간격을 조정해서 행의 간격을 일치시킴

**텍스트 장식**

**text-decoration**
* overline	     윗줄	예제
* line-through	 취소선	예제
* underline	     밑줄	예제

**기타 태그**
* line-height = 행간격을 지정한다                     http://www.w3schools.com/cssref/playit.asp?filename=playcss_line-height
* letter-spacing = 문자와 문자사이의 간격을 지정한다.   http://www.w3schools.com/cssref/playit.asp?filename=playcss_letter-spacing
* vertical-align = 텍스트의 수직 정렬을 지정한다.      http://www.w3schools.com/cssref/playit.asp?filename=playcss_vertical-align&preval=baseline
* white-space = 줄바꿈되는 방식을 지정한다.            http://www.w3schools.com/cssref/playit.asp?filename=playcss_white-space

### 폰트 꾸미기

**Font**

폰트는 글꼴을 의미하는데, 글자의 서체를 의미한다. 

**Font Family**

일반적인 방법으로는 웹페이지에는 글꼴을 포함할 수 없다. 

그렇기 때문에 웹페이지에 지정된 글꼴을 사용자가 보기 위해서는 사용자의 디바이스에도 해당 글꼴이 포함되어 있어야 한다. 그래서 CSS에서는 font family라는 개념이 있는데, 글꼴의 우선순위를 정해서 여러개 지정하면 그 중에서 사용할 수 있는 폰트를 반영하게 된다. 

예를들어 아래의 구문은 사용자 컴퓨터에 Times New Roman 글꼴이 있다면 적용하고 없다면 Times를 적용한다. 

p{font-family:"Times New Roman", Times, serif;}

**고정폭, 가변폭?**

일반적으로 글꼴을 디자인 할 때 문자의 폭을 문자의 모양에 따라서 다른 넓이를 갖게 된다.

이를테면 숫자 1과 문자 m의 폭을 같게 디자인하면 어색하게 느껴질 수 있기 때문이다. 이러한 방식을 가변폭이라고 한다. 

반대로 데이터 분석이나 코딩과 같은 일을 하는데는 미려함 보다는 정확함을 더 중시하기 때문에 글자의 폭을 같게 디자인하는데 이러한 방식을 고정폭이라고 한다.

일반적으로 고정폭 글꼴은 굴림체처럼 폰트의 이름 뒤에 '체'를 붙인다. 

**Sans-serif VS serif**

serif(세리프)란 문자의 디자인에 포함된 장식적인 요소로 아래 그림의 붉은색에 해당된다. 대표적인 글꼴로 바탕체, 궁서체, Time New Roman이 있다. 

sans-serif(산세리프)란 세리프의 장식적인 요소가 없는 디자인으로 굴림체, 돋음체, Arial, Verdana가 대표적이다.

font-family에 serif나 sans-serif를 지정하면 운영체제 내부적인 기준에 따라서 적당한 글꼴이 표시된다.

**Font Size**

글꼴의 크기를 지정할 때는 font-size 효과를 사용한다. font-size 효과에서 자주 사용되는 단위는 px와 em이 있고,

W3C에서는 em의 사용을 권장하고 있다. em은 상대적인 크기인데, 폰트의 대문자 M의 폭을 16px로 계산하기 때문에 1em은 기본적으로 16px과 같다고 생각하면 된다.

하지만 em은 현재 엘리먼트가 상속하고 있는 폰트 크기를 기준으로 상대적으로 결정된다. (참고:em과 px를 변환해주는 서비스 http://pxtoem.com/ ) 

**Font Weight**

글꼴의 두께를 지정할 때는 font-weight를 사용한다. 

### 링크 꾸미기

링크의 상태

링크는 아래와 같이 4가지의 상태를 가지고 있고, 각 상태에 따라서 시각적으로 다른 모양을 가질 수 있다.

상태                |css        |	 
--------------------|-------------|----------------
방문하지 않은 링크   |a:link{}     |	 
방문했던 링크	       |a:visited{}  |	 
마우스를 오버한 링크	 |a:hover{}	   |a:link과 a:visited 뒤에 와야 함
마우스를 누른 상태의 링크|	a:active{}|	a:hover 뒤에 와야 함

html 링크 수업 https://opentutorials.org/course/11/64

### 표 꾸미기

**표의 특징**

표에 대한 HTML의 기본 디자인은 표 전체의 테두리와 셀(cell) 사이에 여백이 기본적으로 지정되어 있다. 

이 여백을 무시하려면 table 태그에 border-collapse 효과의 값으로 collapse를 주면 된다. 

HTML 표 수업 (https://opentutorials.org/course/11/70)

### 배경 꾸미기

**엘리먼트의 배경**

엘리먼트의 배경에 색상을 부여하거나 이미지를 표시하고 싶을 때 background 효과를 사용한다. 

이 효과를 이용하면 배경에 사용된 이미지의 위치를 지정하거나, 반복 할 수 있다. 

**배경색**

background-color:색상값

* Hex	        16진수로 색상 값을 표현, #ff0000 (붉은색), #00ff00(초록), #0000ff(파랑)
* RGB	        붉은색, 초록, 파랑의 값을 조합해서 색상 값을 표현,  RGB(255,0,0), RGB(0,255,0), RGB(0,0,255)
* 별명	       red, blue, green등

**배경 이미지**

background-image: url('이미지의 URL');

**배경 이미지의 반복**

background-repeat: 반복방식

* repeat	     수직, 수평 모두 반복함
* repeat-x	     수평만 반복함
* repeat-y	     수직만 반복함
* no-repeat	     반복하지 않음

배경 이미지의 위치

* left top, left center, left bottom, right top, right center, right bottom, center top, center center, center bottom	배경 위치를 지정
* x% y%	            x%는 수평위치를 y%는 수직 위치를 의미하고, 이미지의 상대적인 위치를 지정한다.
* xpos ypos	        이미지의 절대적인 위치를 지정한다.

**단축속성**

<pre>
body {background:#00ffff url('image.png') no-repeat right top;}
</pre>

## 박스모델

HTML의 엘리먼트들은 (사각형 모양을 의미하는)박스의 형태를 가지고 있는데 이것을 가르켜 박스모델이라고 하고, 박스의 크기와 박스간의 간격을 정의하는 다양한 속성이 있다.

* margin : border를 기준으로 박스의 여백을 지정, 시각적인 요소는 없음
* border : 박스의 테두리
* padding : 테두리와 content간의 간격
* content : 엘리먼트 안에 포함되는 컨텐츠

**content(컨텐츠)**

* 엘리먼트안에 포함되는 컨텐츠로 예를들어 <div>test</div>라고 태그를 기술했을 때 div앨리먼트의 content는 test임
* content는 폭(width)과 높이(height)를 지정할 수 있다.

**border(보더), 테두리**

* 엘리먼트의 테두리
* 테두리는 margin과 padding의 경계가 된다.
* 테두리의 굵기와 색상과 스타일을 지정할 수 있다.

**padding(패딩)**

* 테두리와 컨텐츠 간의 여백

**margin(마진)**

* 엘리먼트와 엘리먼트 간의 여백
* 위 아래에 인접한 엘리먼트 간에는 margin의 값이 더 큰 쪽의 margin이 적용됨(좌우는 아님)


**margin, padding 표기법**

* margin:10px - 상우하좌의 margin값이 10px
* margin:10px 20px - 상하 10px, 좌우 20px,
* margin:10px 20px 30px - 상 10px, 좌우 20px, 하 30px
* margin:10px 20px 30px 40px - 상우하좌의 순으로 값이 지정됨

파이어버그사용법 https://opentutorials.org/course/128/883

### 마진 겹침

마진겹침(margin collapsing) 규칙이란?

마진이 세로 방향으로 겹쳤을 때 마진 값이 더 큰 쪽을 따르게 되는 현상

* 형제 엘리먼트 간 (예제1)
* 부모/자식 엘리먼트 간 (예제2)
* 시각적인 요소가 없는 엘리먼트 자체적으로 (예제3)

### 박스모델의 종류

블록 레벨 엘리먼트(block-level element)
* 한줄에 하나의 엘리먼트만 표시되는 종류의 엘리먼트 (예제1)
* 다른 인라인 엘리먼트 뿐 아니라 블록 레벨 엘리먼트도 컨텐츠로 포함할 수 있다.
* DIV, H1~H6, P, FORM, UL, LI, ADDRESS, BLOCKQUOTE, FIELDSET, TABLE, HR 등
 
인라인 엘리먼트(inline element)
* 한줄에 여러개의 엘리먼트가 표시되는 종류의 엘리먼트 (예제2)
* 인라인 엘리먼트만 포함 할 수 있고, 블록레벨 엘리먼트의 자식이어야 한다.
* a, img, em, strong등
 
display 속성을 이용해서 블록레벨 엘리먼트를 인라인 엘리먼트로 바꿀 수 있고, 반대경우도 가능하다.
 
display 속성의 값을 none으로 하면 엘리먼트를 화면에서 보이지 않게 할 수 있다.

인라인 엘리먼트도 박스모델의 적용을 받지만 상하 관계는 무시됨(좌우는 적용)

### float

* 엘리먼트를 원하는 위치로 이동시키고, 엘리먼트 뒤에 따라오는 앨리먼트들이 엘리먼트를 피해서 표시 되도록 한다.
* float는 원래 이미지를 둘러싸고 흘러가는 텍스트를 표시하기 위해서 고안된 것이다. example1.html
* 레이아웃을 구성할 때도 사용된다.example2.html
* float를 해제하기 위해서는 clear 속성을 사용한다. example3.html

## 포지셔닝

positioning, CSS를 이용해서 HTML 엘리먼트들의 위치를 제어하는 방법

포지셔닝의 종류

엘리먼트에 CSS 속성으로 position을 지정하면 여러가지 방법으로 위치를 지정할 수 있다.

**상대위치(relative positioning)**
* position:relative
* 자신의 위치를 기준으로 한 상대위치 값을 지정한다.
* 자식 엘리먼트의 크기에 따라서 부모 엘리먼트의 크기가 자동으로 변경되지만, 엘리먼트의 위치에 따라서는 변경되지 않는다.

positioning.html - position의 값이 relative인 경우, me의 속성으로 top을 주었을 때 me의 원래 위치에서 10px아래로 내려온다.이 때 parent의 크기가 변하지 않기 때문에 me가 parent위에 표시된다. (jsfiddle, github)

**절대위치(absolute positioning)**
* position:absolute
* 문서를 기준으로 위치가 정해지기 때문에 부모 엘리먼트의 위치와는 무관하다.
* 엘리먼트의 크기가 부모 엘리먼트의 크기에 반영되지 않는다. 

positioning2.html - position의 값을 absolute로 했을 때 me의 offset은 기본적으로 원래 위치의 값을 가지고, parent와의 관계가 완전히 사라지기 때문에 parent는 me의 크기가 전혀 반영되지 않는다.


**고정위치(fixed positioning)**
* position:fixed
* 문서를 기준으로 위치가 정해지기 때문에 부모 엘리먼트의 위치와는 무관하다.
* 엘리먼트의 크기가 부모 엘리먼트의 크기에 반영되지 않는다.
* 스크롤의 영향을 받지 않는다.

positioning3.html - me가 절대위치와 동일한 성격을 갖지만, 화면을 스크롤해도 고정된 위치에 위치함 

**정적위치(static positioning)**
* position:static
* 자식 엘리먼트의 크기에 따라서 부모 엘리먼트의 크기가 자동으로 변경된다.
* position 속성의 값을 지정하지 않으면 기본적으로 static의 값이 주어진다.
* left, top, right, bottom과 같은 offset이 무시된다.

positioning4.html - position의 값이 static인 경우 class가 me인 엘리먼트가 parent 엘리먼트 안에 포함되어 있고, parent는 me의 크기에 따라서 사이즈가 변함 

**포지셔닝 비교**
        
        | 정적위치(static) | 상대위치(relative) | 절대위치(absolute) | 고정위치(fixed)
--------|-----------------|-------------------|--------------------|---------------
기준위치|자기위치|자기위치|문서(html), 시작 위치는 static 기준으로 원래의 위치에 맞춰져 있음.|절대위치와 동일
부모의크기|자식의 크기에 따라 변경|자식의 크기에 따라 변경되지만 위치를 변경함에 따라 부모의 크기가 변경되지는 않음|부모의 크기에 영향을 끼치지 않음|절대위치와 동일
자신의크기|width:100%로 부모의 크기를 따름|width:100%로 부모의 크기를 따름|포함하고 있는 컨텐트의 크기 만큼 늘어남|절대위치와 동일
offset 사용(left,right.top,bottom)|불가|가능|가능|가능
스크롤|따라감|따라감|따라감|고정

## 상속

* 상위 엘리먼트의 속성을 하위 엘리먼트가 물려 받음
* 속성 중에는 상속이 되는 것과 되지 않는 것이 있음
* http://www.w3.org/TR/CSS21/propidx.html  inHerited? 가 yes인 경우만 상속됨
* 속성의 값으로 inhert를 지정하면 상속되지 않는 속성도 강제로 상속할 수 있음

extend.html - 상속의 일반적인 모습과 상속의 우선순위 (jsfiddle, github)

extend2.html - 상속되지 않는 속성(border) (jsfiddle, github)

extend3.html - 강제상속 (jsfiddle, github)

## 캐스케이딩

* 엘리먼트는 다양한 CSS 선언의 영향을 받는다. 이 때 충돌을 피하기 위해서 우선순위를 정하는데 이를 캐스케이딩이라고 함.
* 캐스케이딩에는 다음과 같이 세가지 규칙이 있음.
    * 중요도  - css가 어디에 선언 되었는지에 따라서 우선순위가 달라짐
    * 명시도  - 대상을 명확하게 특정할수록 명시도가 높아지면서 우선순위가 높아짐
    * 소스순서 - css 선언을 나중에 할수록 우선순위가 높아짐
    
**중요도**

css는 다양한 위치에서 기술될수 있는데, 그 위치에 따라서 우선순위가 달라진다. css가 기술될 수 있는 위치는 아래와 같고, 우선순위는 아래로 내려갈수록 높다. (저작자 CSS의 !important가 제일 높음)

1. 브라우저의 CSS - 기본적으로 가지고 있는 속성 
2. 사용자 CSS 일반선언 - 웹 브라우저를 보고 있는 사람.(오페라에서 제한적으로 제공되는 기능)
3. 저작자 CSS 일반선언 - 지금까지 한 것들..
4. 저작자 CSS의 !important

cascading.html - 중요도에 따라서 엘리먼트에 적용되는 CSS 효과가 달라진다. (jsfiddle, github)

**명시도**

css선언이 엘리먼트를 상세하게 특정할수록 우선순위가 높아진다. 대상을 지정하는 방법은 아래와 같고 아래로 내려갈수록 우선순위가 높다. (style을 이용하는 것이 제일 높음)

1. type
2. class
3. id
4. inline으로 엘리먼트에 직접 css를 기술

아래는 css 선택자에 따른 우선순위 규칙.(출처) https://stuffandnonsense.co.uk/archives/css_specificity_wars.html

cascading2.html - <div>example</div>의 color 값에 여러개의 css선언이 영향을 주고 있음. 아래로 갈수록 우선순위가 높아짐.  (jsfiddle, github)

**소스순서**

cascading3.html - 소스 상에서 css 선언이 나중에 나올수록 우선순위가 높아짐  (jsfiddle, github)


## CSS 활용 - ATOM 에디터의 디자인 변경

웹 이라는 것은 웹 바깥에서도 사용 되는 경우가 많음.. 모바일 에서도 사용이 됨.

데스크탑에서 돌아가는 프로그램을 만들때도 웹 기술을 사용해서 프로그램을 만들 수 있는 기술들이 존재함.

아톰 에디터는 HTML, CSS 등의 기술을 사용해서 만든 에디터..

아톰이 구글 크롬의 기반의 위에서 만듬.

Atom 에디터 수업 : https://opentutorials.org/module/1579

크롬 개발자 도구 수업 : https://opentutorials.org/module/306/2865

# SASS

소개

**SASS의 등장배경**

CSS는 HTML을 디자인하는 언어다. 엘리먼트(태그)를 선택하고, 선택된 태그를 꾸며주는 단순한 원리를 가지고 있다. 

이런 단순성은 CSS의 미덕이지만, 규모가 조금만 커져도 CSS 유지보수하는 것은 어렵거나 불가능한 일이 된다. 

자바스크립트와 같은 동적인 언어는 변수나 함수를 이용해서 코드의 재활용성을 높이고 코드의 양을 줄여주는데 반해서 CSS는 효율이 떨어진다.

**SASS란?**

위에서 언급한 CSS의 단점을 보완하기 위한 기술로, SASS 자체를 그대로 사용할수는 없고, SASS의 문법에 맞게 SASS파일을 만들면 컨버터를 이용해서 CSS를 생성한다.

**SASS 홈페이지**

http://sass-lang.com/

**Sass 학습을 위한 도서**

http://books.webactually.com/sass-for-web-designers/

