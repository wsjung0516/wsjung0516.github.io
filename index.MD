<div class="WordSection1">

<span lang="EN-US">XXX</span> 프로젝트 <span lang="EN-US">(</span>심사상세 모듈<span lang="EN-US">)</span>테스트 프로그램

실행프로그램 <span lang="EN-US">: <a name="OLE_LINK4"></a><a name="OLE_LINK3"></a>[https://ocr-elements-q2mwwrlwo.now.sh](https://ocr-elements-q2mwwrlwo.now.sh/)<span class="MsoHyperlink"><span style="text-decoration:none"></span> </span></span><span class="MsoHyperlink"><span lang="EN-US" style="font-size:8.0pt;line-height:107%;
font-family:Wingdings;text-decoration:none">ß</span></span><span class="MsoHyperlink"><span lang="EN-US" style="font-size:8.0pt;line-height:107%;
text-decoration:none">’</span></span><span class="MsoHyperlink"><span style="font-size:8.0pt;line-height:107%;text-decoration:none">심사상세 적용테스트<span lang="EN-US">’</span> 라는 글씨를 마우스 클릭</span></span>

소스프로그램 <span lang="EN-US">: [https://github.com/wsjung0516/ocr-detail190528](https://github.com/wsjung0516/ocr-detail190528)</span>

<span lang="EN-US">![](프로그램설명190807-2.files/image001.jpg)</span>

<span lang="EN-US">1.<span style="font:7.0pt &quot;Times New Roman&quot;"></span> </span>개요<span lang="EN-US">.  
</span>이 프로그램은 모 은행에서 프로젝트 시행중인 수출입물품제재<span lang="EN-US">(</span>미국의 적대국가에 수출입을 못하도록 제한을 목적으로 함<span lang="EN-US">)</span>기능으로<span lang="EN-US">,</span> 수출입 문서가 <span lang="EN-US">OCR(Optical Character Recognition)</span> 문서의 이미지 형태의 데이터에서 <span lang="EN-US">AI</span> 기술 적용으로 이미지에 포함된 글자를 판독한 결과를 조회<span lang="EN-US">,</span> 수정<span lang="EN-US">,</span> 수<span lang="EN-US">/</span>출입 제재항목 심사<span lang="EN-US">,</span> 심사내용 결재 등의 핵심기능 수행하는 프로그램<span lang="EN-US">.  
</span>이 프로그램은 <span lang="EN-US">Angular Element</span> 기술을 적용하여 실제 실행되는 프로그램이 한 개의 <span lang="EN-US">JavaScript ( xxx.js file)</span>로 생성되어 필요한 프로젝트에서 바로 <span lang="EN-US">JavaScript Component</span>처럼 적용할 수 있도록 개발함<span lang="EN-US">.  
</span>이 파일을 적용하는 프로젝트는 이 파일의 <span lang="EN-US">input/output, property, event</span> 정보를 참조하여 바로 적용<span lang="EN-US">(Embed)</span>할 수 있음<span lang="EN-US">.  
</span>개발기술은 <span lang="EN-US">Angular</span>의 <span lang="EN-US">Elements Material, Cdk,</span> 그리고 <span lang="EN-US">Reactive X Library</span>인 <span lang="EN-US">RxJS</span>를 활용하여 개발함<span lang="EN-US">.</span>

<span lang="EN-US">2.<span style="font:7.0pt &quot;Times New Roman&quot;"></span> </span>프로그램설명<span lang="EN-US">  
-------- Dynamic Tabs  
</span>실제의 각 거래건수별로 국적과 물품이 틀리기 때문에 <span lang="EN-US">OCR</span> 판독한 데이터가 약 <span lang="EN-US">20</span>장 내외가 여러 세트<span lang="EN-US">(</span>가로축 <span lang="EN-US">Tab)</span>로 구분되고<span lang="EN-US">,</span> 각 세트당 여러<span lang="EN-US">(</span>세로축 <span lang="EN-US">Tab)</span> 페이지의 <span lang="EN-US">OCR</span>문서가 구분되어 접수됨<span lang="EN-US">  
</span>그러므로 프로그램에서는 각 거래건수별로 가로<span lang="EN-US">Tab,</span> 세로<span lang="EN-US">Tab</span>을 <span lang="EN-US">Dynamic</span>하게 구성 해야함<span lang="EN-US">.  
--------</span> 문서분류명<span lang="EN-US">,  
</span>분류된 각 <span lang="EN-US">OCR</span>에 이미지에서 읽은 문서제목이 잘못 표기되어 세로 <span lang="EN-US">Tab</span> 메뉴가 된 경우 이를 즉석에서 수정 반영하는 기능<span lang="EN-US">.  
Dropdown</span>기능<span lang="EN-US">, Editing</span>기능<span lang="EN-US">,</span> 메뉴 이동기능이 포함됨<span lang="EN-US">.  
--------- Image Zoom in/Zoom out  
</span>각 세로<span lang="EN-US">Tab</span>에 연결된 이미지는 <span lang="EN-US">Zoom-in/Zoom-out</span> 기능 및 이미지에 특정 항목을 <span lang="EN-US">Rectangular</span>로 <span lang="EN-US">Marking</span>하는 기능이 포함됨<span lang="EN-US">.  
Marking</span>하는 이유는 문서에서 데이터가 추출된 위치를 알려주기 위함<span lang="EN-US">.  
---------- Sanction Rule  
OCR Image</span>파일에서 추출한 제재항목을 표현하고<span lang="EN-US">,</span> 잘 못 추출한 부분이 있으면 직접 입력하는 기능이 포함됨<span lang="EN-US">.  
</span>모든 페이지의 포함된 데이터<span lang="EN-US">,</span> 각 페이지별로 포함된 데이터<span lang="EN-US">,</span> 각 페이지의 특정 항목의 다른 페이지의 데이터와 중복된 경우 알람 기능 등이 포함됨<span lang="EN-US">.</span>

<span lang="EN-US">3.<span style="font:7.0pt &quot;Times New Roman&quot;"></span> </span>프로그램 소스 설명<span lang="EN-US">  

</span>화면을 설계한 구조는<span lang="EN-US">ocr-image-board</span> <span lang="EN-US" style="font-size:8.5pt;line-height:107%">├──</span> <span lang="EN-US">h-tabs</span> <span lang="EN-US" style="font-size:8.5pt;
line-height:107%">├──</span> <span lang="EN-US">h-tab</span> <span lang="EN-US" style="font-size:8.5pt;line-height:107%">├──</span> <span lang="EN-US">v-tabs</span> <span lang="EN-US" style="font-size:8.5pt;
line-height:107%">├──</span> <span lang="EN-US">v-tab</span> <span lang="EN-US" style="font-size:8.5pt;line-height:107%">├──</span> <span lang="EN-US">ocr-zoom-panel</span> <span lang="EN-US" style="font-size:8.5pt;line-height:107%">├──</span> <span lang="EN-US">s-rule-panel</span> <span lang="EN-US" style="font-size:8.5pt;
line-height:107%">├──</span> <span lang="EN-US">appr-info</span> <span lang="EN-US" style="font-size:8.5pt;
line-height:107%">├──</span> <span lang="EN-US">s-rule  
-----------  
ocr-image-board</span>가 최상위 컴포넌트로 전체화면의 배경 역할 및 하위의 모든 컴포넌트가 포함됨<span lang="EN-US">.  
h-tabs, v-tabs</span>는 세로 및 가로 메뉴로 구성됨<span lang="EN-US">.  
ocr-zoom-panel, s-rule-panel</span>은 앞 부분의 좌측과 우측의 배경 컴포넌트임<span lang="EN-US">.  
ocr-zoom-panel:</span> 이미지를 조작<span lang="EN-US">(</span>확대<span lang="EN-US">,</span> 축소<span lang="EN-US">)</span> 및 이미지에 마킹하는 컴포넌트 포함됨<span lang="EN-US">.  
s-rule-panel:</span> 제재항목을 표시하고<span lang="EN-US">,</span> 잘 못 판독된 데이터를 입력하는 컴포넌트 포함됨<span lang="EN-US">  
![](프로그램설명190807-2.files/image002.png)  

![](프로그램설명190807-2.files/image003.png)  
</span>상기 그림의 <span lang="EN-US">output directory</span>는 <span lang="EN-US">Angular Element</span>기능으로 생성된 파일이 존재하는 부분임<span lang="EN-US">.  
ocr-elements.js</span> 파일이 실제 타 시스템에서 적용할 하나의 파일이고<span lang="EN-US">,</span> 이 파일 하나만 실행 테스트 하려면 아래의 <span lang="EN-US">index.html</span> 파일처럼 적용<span lang="EN-US">(Embed)</span>하면 됨<span lang="EN-US">.  
</span>참고로 <span lang="EN-US">style.css</span>이 필요한 경우는 아래의 파일에서 적용한 것처럼 적용함<span lang="EN-US">.  
assets directory</span>는 <span lang="EN-US">index.html</span>과 같은 <span lang="EN-US">directory</span>에 위치함<span lang="EN-US">.  
![](프로그램설명190807-2.files/image004.png)  

</span>

<span lang="EN-US" style="font-size:10.0pt;line-height:107%;font-family:&quot;맑은 고딕&quot;">  
</span>

<span lang="EN-US"> </span>

피자오더 프로그램

실행프로그램 <span lang="EN-US">: <a name="OLE_LINK2"></a>[https://ngxs-pizza1226-3b498ncxo.now.sh](https://ngxs-pizza1226-3b498ncxo.now.sh/)</span>

소스프로그램 <span lang="EN-US">: [https://github.com/wsjung0516/ngxs-pizza181226](https://github.com/wsjung0516/ngxs-pizza181226)<span class="MsoHyperlink">  
</span>![](프로그램설명190807-2.files/image005.jpg)</span>

<span lang="EN-US">1.<span style="font:7.0pt &quot;Times New Roman&quot;"></span> </span>개요<span lang="EN-US">  
</span>이 프로그램은 본인이 처음부터 설계하고 디자인한 것이 아니라 <span lang="EN-US">Angular</span>로 개발된 샘플프로그램 <span lang="EN-US">(Angular source: https://github.com/cypress-io/angular-pizza-creator)</span>을 두명의 다른 개발자가 <span lang="EN-US">Redux(NgXS), RxJS</span>를 조합하여 재 작성한 것인데<span lang="EN-US">,</span> 이 프로그램이 <span lang="EN-US">([https://github.com/tommythongnguyen/Ngxs-Pizza-Order](https://github.com/tommythongnguyen/Ngxs-Pizza-Order))</span>미완성 상태로 정상 동작이 불가하여<span lang="EN-US">,</span> 중요 부분을 수정한 것입니다<span lang="EN-US">.</span> 원래는 <span lang="EN-US">DB</span>와 연결되어 동작하지만<span lang="EN-US">,</span> 온라인 데모용으로 <span lang="EN-US">Redux</span> 기능으로 대신하여 동작합니다<span lang="EN-US">.  
</span>소스는 체계적으로 설계되어<span lang="EN-US">,</span> 쉽게 내용을 파악할 수 있으며 유지보수가 쉽게 구성되어 있습니다<span lang="EN-US">.</span>

<span lang="EN-US">2.<span style="font:7.0pt &quot;Times New Roman&quot;"></span> </span>프로그램설명<span lang="EN-US">New Pizza :</span> 피자를 새로 생성할 수 있음<span lang="EN-US">.  
View Pizza :</span> 이미 만들어진 피자의 토핑을 바꾸거나 삭제할 수 있음<span lang="EN-US">.</span>

<span lang="EN-US" style="font-size:12.0pt;line-height:107%;font-family:굴림">3.<span style="font:7.0pt &quot;Times New Roman&quot;"></span> </span>프로그램 소스 설명<span lang="EN-US">![](프로그램설명190807-2.files/image006.jpg)  

pizza-display ;</span> 피자가 토핑이 추가된 상태를 표시한 프로그램<span lang="EN-US">.  
pizza-form:</span> 토핑을 선택하는 기능 <span lang="EN-US">Angular</span> 의 <span lang="EN-US">ControValueAccess</span> 기능 적용하여 <span lang="EN-US">form  control</span>은 별도의 파일<span lang="EN-US">(pizza-topping)</span>에서 반영함<span lang="EN-US">.  
pizza-item:</span> 생성된 피자를 조회 하여 토핑 내용 수정 및 피자를 삭제 명령 기능<span lang="EN-US">.  
pizza-toppings:</span> 피자의 토핑을 선택하는 기능<span lang="EN-US">.</span> 선택한 결과를 <span lang="EN-US">pizza-form</span>에 전달함<span lang="EN-US">  
--------- Router  
Router</span>는 <span lang="EN-US">product.component</span>와 <span lang="EN-US">product-item.componet</span>로 구분됨<span lang="EN-US">.  
product-item.componet:</span> 새로 생성하는 경우와 수정하는 경우 담당<span lang="EN-US">.  
product.component:</span> 생성된 피자를 전시하는 경우 담당<span lang="EN-US">  
![](프로그램설명190807-2.files/image007.jpg)  

</span>주요 모듈에 대한 설명은<span lang="EN-US">  
</span><span lang="EN-US" style="font-size:8.0pt;line-height:107%;font-family:
굴림">product-item :</span> <span style="font-size:8.0pt;line-height:107%;
font-family:굴림">이미 생성된 피자<span lang="EN-US">(1</span>개<span lang="EN-US">)</span> 이거나<span lang="EN-US">,</span> 새로 만드는 경우<span lang="EN-US">pizza-form  
        pizza-diplay  
pizza-form :</span> 이미 생성되었거나 새로 만들 때<span lang="EN-US">,</span> 토핑을 추가하는 경우<span lang="EN-US">pizza-toppings  
products :</span> 이미 생성된 모든 피자를 전시하는 경우<span lang="EN-US">,</span> 각 피자의 상세로 이동할 수 있음<span lang="EN-US">.  
    pizza-item  
        pizza-display</span></span>

<span lang="EN-US">.  
![](프로그램설명190807-2.files/image008.jpg)  

---------- Guard  
</span>생성된 피자와 토핑의 데이터를 <span lang="EN-US">DB</span>로 읽어와 초기화 하는 기능 수행함<span lang="EN-US">.  
pizza-exists.guard, pizzas.guard. otppings.guard  
---------- models  
pizza, toppings</span>의 데이터 모델 선언<span lang="EN-US">  
----------- Services  
DB</span>로부터 데이터를 <span lang="EN-US">CRUD</span> 기능<span lang="EN-US">----------- Store  
Redux</span> 기능을 적용하기 위한 <span lang="EN-US">Action Define</span> 및 <span lang="EN-US">State</span>의 생성을 위한 기능<span lang="EN-US">.  

</span>

<span lang="EN-US">--</span> 끝 <span lang="EN-US">--</span>

<span lang="EN-US" style="font-size:10.0pt;line-height:107%;font-family:&quot;맑은 고딕&quot;">  
</span>

<span lang="EN-US"> </span>

<span lang="EN-US"> </span>

<div style="border:none;border-bottom:solid #141414 1.5pt;padding:0cm 0cm 4.0pt 0cm">

<span lang="EN-US" style="font-size:
26.0pt;font-family:&quot;Cambria&quot;,serif;color:#141414"><span lang="EN-US" style="font-family:&quot;맑은 고딕&quot;"><span lang="EN-US">이력서</span></span>(<span lang="EN-US" style="font-family:&quot;맑은 고딕&quot;"><span lang="EN-US">정원섭</span></span>)</span>

</div>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;맑은 고딕&quot;;
color:windowtext"><span lang="EN-US">[</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;맑은 고딕&quot;;color:windowtext"><span lang="EN-US">주소</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;맑은 고딕&quot;;color:windowtext"><span lang="EN-US">,</span> </span><span lang="EN-US" style="font-size:10.0pt;font-family:
&quot;맑은 고딕&quot;;color:windowtext"><span lang="EN-US">우편</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;맑은 고딕&quot;;color:windowtext"> <span lang="EN-US"></span> </span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;맑은 고딕&quot;;
color:windowtext"><span lang="EN-US">번호</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;맑은 고딕&quot;;color:windowtext"><span lang="EN-US">]</span></span></span><span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"> | </span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;맑은 고딕&quot;;color:windowtext"><span lang="EN-US">[</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:
&quot;맑은 고딕&quot;;color:windowtext"><span lang="EN-US">전화</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;맑은 고딕&quot;;color:windowtext"> <span lang="EN-US"></span> </span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;맑은 고딕&quot;;
color:windowtext"><span lang="EN-US">번호</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;맑은 고딕&quot;;color:windowtext"><span lang="EN-US">]</span></span></span><span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"> 010-5014-6735, | </span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;맑은 고딕&quot;;
color:windowtext"><span lang="EN-US">[</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;맑은 고딕&quot;;color:windowtext"><span lang="EN-US">전자</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;맑은 고딕&quot;;color:windowtext"> <span lang="EN-US"></span> </span><span lang="EN-US" style="font-size:10.0pt;font-family:
&quot;맑은 고딕&quot;;color:windowtext"><span lang="EN-US">메일</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;맑은 고딕&quot;;color:windowtext"><span lang="EN-US">]</span></span> wonsup.jung@gmail.com</span>

**<span style="font-size:12.0pt;color:#4E4E4E">활용기술</span>****<span lang="EN-US" style="font-size:12.0pt;font-family:&quot;Cambria&quot;,serif;color:#4E4E4E">.</span>**

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">[</span><span style="font-size:9.0pt;color:#404040">프로그램</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">]</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">1\. Angular: 3</span><span style="font-size:9.0pt;color:#404040">개의</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">프로젝트를</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">직접</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">수행한</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">경험이</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">있음</span><span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#404040">. </span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">주로</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"><span lang="EN-US">Third Party Library</span></span><span style="font-size:9.0pt;
color:#404040">를</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">사용하여</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">개발하기도</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">하고</span><span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;
color:#404040">필요시에서</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"><span lang="EN-US">JavaScript</span></span><span style="font-size:9.0pt;color:#404040">로</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">직접</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">개발도</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">가능함</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">.</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">2\. Redux(Ngxs)</span><span style="font-size:9.0pt;color:#404040">를</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">적용하여</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">개발</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">가능하므로</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">프로젝트의</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">전체</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">중요</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">상태를</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">관리할</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">수</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">있음</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">.</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">3\. Rxjs</span> <span style="font-size:9.0pt;color:#404040">기술을</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">적절히</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">조합하여</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">간결하고</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">오류</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">발생을</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">최소화할</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">수</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">있고</span><span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;
color:#404040">프로그램</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">가독력을</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">높여</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">유지보수가</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">용이한</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">프로그램이</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">가능함</span><span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#404040">.</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">5\.</span> <span style="font-size:9.0pt;color:#404040">서버는</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"><span lang="EN-US">Nodejs</span></span><span style="font-size:9.0pt;color:#404040">를</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">적용하여</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">개발</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">가능함</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">. (Express</span> <span style="font-size:9.0pt;color:#404040">등</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">사용</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">)</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">6,</span> <span style="font-size:9.0pt;color:#404040">하이브리드</span> <span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">framework,  ionic</span><span style="font-size:9.0pt;color:#404040">을</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">사용하여</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">실무</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">프로그램을</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">개발할</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">수</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">있음</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">. (</span><span style="font-size:9.0pt;color:#404040">경험</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"><span lang="EN-US">1</span></span><span style="font-size:9.0pt;color:#404040">년</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">)</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">7\.</span> <span style="font-size:9.0pt;color:#404040">최근에는</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"><span lang="EN-US">firebase DB</span></span><span style="font-size:9.0pt;color:#404040">를</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">사용한</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">경험이</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">있음</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">. (firebase</span> <span style="font-size:9.0pt;color:#404040">서버함수</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">(server-function)</span><span style="font-size:9.0pt;color:#404040">를</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">활용하여</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"><span lang="EN-US">REST Api</span></span><span style="font-size:
9.0pt;color:#404040">를</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">구현하여</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">)</span> <span style="font-size:9.0pt;color:#404040">모바일</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"><span lang="EN-US">app</span></span><span style="font-size:9.0pt;color:#404040">의</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">서버</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">기능을</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">구현하였음</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">.</span>

**<span lang="EN-US" style="font-size:12.0pt;font-family:&quot;Cambria&quot;,serif;
color:#4E4E4E"> </span>**

**<span style="font-size:12.0pt;color:#4E4E4E">교육</span>**

**<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">석사</span>****<span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase">|1994.8 ~ 1998.2|</span> ****<span style="font-size:9.0pt;
color:#191919;text-transform:uppercase">연세대학교</span>**** <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase"></span> ****<span style="font-size:9.0pt;color:#191919;
text-transform:uppercase">산업대학원</span>**

<span style="font-size:9.0pt;line-height:75%;color:#404040">전공</span><span style="font-size:9.0pt;line-height:75%;font-family:&quot;Cambria&quot;,serif;color:#404040">:</span> <span style="font-size:9.0pt;line-height:75%;color:#404040">전자계산학</span>

**<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">학사</span>****<span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase">| 1984.2 ~</span> ****<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase">1988.2</span>****<span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#191919;text-transform:uppercase"> | </span>****<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">서강대학교</span>**

<span style="font-size:9.0pt;color:#404040">전공</span><span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">:</span> <span style="font-size:9.0pt;color:#404040">화화공학과</span>

**<span style="font-size:12.0pt;color:#4E4E4E">자격</span>**** <span style="font-size:12.0pt;font-family:&quot;Cambria&quot;,serif;color:#4E4E4E"></span> ****<span style="font-size:12.0pt;color:#4E4E4E">및</span>**** <span style="font-size:
12.0pt;font-family:&quot;Cambria&quot;,serif;color:#4E4E4E"></span> ****<span style="font-size:12.0pt;color:#4E4E4E">기술</span>**

**<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">기술자격사항</span>**

<span style="font-size:9.0pt;line-height:75%;color:#404040">정보통신기술사</span><span lang="EN-US" style="font-size:9.0pt;line-height:75%;font-family:&quot;Cambria&quot;,serif;
color:#404040">, 2002</span><span style="font-size:9.0pt;line-height:75%;
color:#404040">년</span> <span style="font-size:9.0pt;line-height:75%;font-family:
&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;line-height:
75%;color:#404040">취득</span><span lang="EN-US" style="font-size:9.0pt;line-height:
75%;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:
9.0pt;line-height:75%;color:#404040">한국산업인력공단</span><span lang="EN-US" style="font-size:9.0pt;line-height:75%;font-family:&quot;Cambria&quot;,serif;color:#404040">.</span>

**<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">어학자격</span>**

<span style="font-size:9.0pt;line-height:75%;color:#404040">구사능력</span><span lang="EN-US" style="font-size:9.0pt;line-height:75%;font-family:&quot;Cambria&quot;,serif;
color:#404040">(</span><span style="font-size:9.0pt;line-height:75%;color:#404040">상</span><span lang="EN-US" style="font-size:9.0pt;line-height:75%;font-family:&quot;Cambria&quot;,serif;
color:#404040">),</span> <span style="font-size:9.0pt;line-height:75%;
color:#404040">비즈니스</span> <span style="font-size:9.0pt;line-height:75%;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
line-height:75%;color:#404040">커뮤니케이션</span> <span style="font-size:9.0pt;
line-height:75%;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;line-height:75%;color:#404040">가능</span>

**<span style="font-size:12.0pt;line-height:75%;color:#4E4E4E">경력</span>**

**<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">부장</span>****<span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase"> | </span>****<span style="font-size:9.0pt;color:#191919;
text-transform:uppercase">㈜티쓰리큐</span>****<span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:uppercase"> | 2019</span>****<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;
text-transform:uppercase">.1 ~2019.7 (7</span>****<span style="font-size:
9.0pt;color:#191919;text-transform:uppercase">개월</span>****<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase">)</span>**

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">1\.</span> <span style="font-size:9.0pt;color:#404040">이미지데이터</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">시사문서</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">(</span><span style="font-size:9.0pt;color:#404040">신문</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">매체</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">등</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">)</span> <span style="font-size:9.0pt;color:#404040">들을</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">인공지능</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">방법으로</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">분석한</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">결과</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">데이터를</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">조회하는</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"><span lang="EN-US">UI</span></span><span style="font-size:9.0pt;color:#404040">개발</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">   [</span><span style="font-size:9.0pt;color:#404040">개발환경</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">] :</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">   Angular, RxJS</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">   </span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"> </span>

**<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">프리랜서</span>****<span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase"> |   2018.5</span>****<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase">.1 ~ 2018\. 12\. 30 (8</span>****<span style="font-size:9.0pt;
color:#191919;text-transform:uppercase">개월</span>****<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase">)</span>**

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">1\.</span> <span style="font-size:9.0pt;color:#404040">골프장</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">예약</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">관리</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">프로그램</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"><span lang="EN-US">app(ionic)</span></span><span style="font-size:9.0pt;color:#404040">및</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">서버</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">(Angular)</span> <span style="font-size:9.0pt;color:#404040">개발</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">   [</span><span style="font-size:9.0pt;color:#404040">담당업무</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">]</span> <span style="font-size:9.0pt;color:#404040">프로그램</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">직접</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">개발</span>

**<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#191919;text-transform:uppercase"> </span>**

**<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">프리랜서</span>****<span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase"> |   2017.10</span>****<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase">.1 ~2017.10.30 (1</span>****<span style="font-size:9.0pt;
color:#191919;text-transform:uppercase">개월</span>****<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase">)</span>**

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">1\.</span> <span style="font-size:9.0pt;color:#404040">한화</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">SNC BIGDATA</span> <span style="font-size:9.0pt;color:#404040">프로그램</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">자동운용환경</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">구축</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">프로젝트</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">   [</span><span style="font-size:9.0pt;color:#404040">담당업무</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">] Angular</span><span style="font-size:9.0pt;color:#404040">를</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">사용하여</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"><span lang="EN-US">BIGDATA</span></span><span style="font-size:
9.0pt;color:#404040">분석을</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">위한</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">다양한</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">응용프로그램을</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">자동</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">설치하는</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"><span lang="EN-US">GUI</span></span><span style="font-size:9.0pt;color:#404040">개발</span>

**<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#191919;text-transform:uppercase"> </span>**

**<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">프리랜서</span>****<span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase"> |   2017.7</span>****<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase">.3 ~2017.9.30 (3</span>****<span style="font-size:9.0pt;
color:#191919;text-transform:uppercase">개월</span>****<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase">)</span>**

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">1\. Tryus&Company</span> <span style="font-size:9.0pt;
color:#404040">홈페이지</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">구축</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">및</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"><span lang="EN-US">Dashboard</span></span><span style="font-size:9.0pt;color:#404040">개발</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">   [</span><span style="font-size:9.0pt;color:#404040">개발환경</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">]</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">  Angular</span><span style="font-size:9.0pt;color:#404040">를</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">사용하여</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">Dashboard</span><span style="font-size:9.0pt;color:#404040">개발</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">(Download</span><span style="font-size:9.0pt;color:#404040">수</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">제품등록수</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">사용고객수</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">, Retention</span> <span style="font-size:9.0pt;color:#404040">등</span><span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span>

<span style="font-size:9.0pt;color:#404040">다양한</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">정보를</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">실시간</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">전시</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">기능</span>

**<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#191919;text-transform:uppercase"> </span>**

**<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">부장</span>****<span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase"> | </span>****<span style="font-size:9.0pt;color:#191919;
text-transform:uppercase">㈜도전하는사람들</span>****<span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:uppercase"> | 201</span>****<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;
text-transform:uppercase">5.12 ~2016.10 (11</span>****<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">개월</span>****<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;
text-transform:uppercase">)</span>**

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">1\.</span> <span style="font-size:9.0pt;color:#404040">개인정보보호</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">솔루션</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">개발</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">   [</span><span style="font-size:9.0pt;color:#404040">개발환경</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">] :</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">Spring, Java</span> <span style="font-size:9.0pt;
color:#404040">및</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">다양한</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"><span lang="EN-US">Third part</span></span><span style="font-size:9.0pt;color:#404040">솔루션을</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">적용하여</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">개발</span><span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">   [</span><span style="font-size:9.0pt;color:#404040">제품설명</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">] :</span>

<span style="font-size:9.0pt;color:#404040">개인정보를</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">취급하는</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">공공기관이나</span><span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;
color:#404040">일반</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">업체에서</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">개인정보를</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">무단으로</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">사용하는</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">것을</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">방지하기</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">위한</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">솔루션</span>

**<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">부장</span>****<span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase"> | </span>****<span style="font-size:9.0pt;color:#191919;
text-transform:uppercase">삼성</span>****<span lang="EN-US" style="font-size:
9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:uppercase">SDS</span>****<span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase"> | </span>****<span lang="EN-US" style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:uppercase">1995.4 ~2014.5 (19</span>****<span style="font-size:9.0pt;color:#191919;text-transform:
uppercase">년</span>****<span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#191919;text-transform:uppercase">2</span>****<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">개월</span>****<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;
text-transform:uppercase">)</span>**

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">1\.</span> <span style="font-size:9.0pt;color:#404040">전투기</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">관제</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">시스템</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">개발</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">프로젝트</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">기간</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">: 2007.7 ~ 2009.10</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">   [</span><span style="font-size:9.0pt;color:#404040">담당업무</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">]PL</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">2\.</span> <span style="font-size:9.0pt;color:#404040">탄도탄</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">방어시스템</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">체계</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">개발</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">프로젝트</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">기간</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">: 2009.10 ~ 2014.5</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">   [</span><span style="font-size:9.0pt;color:#404040">담당업무</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">]PM</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">   [</span><span style="font-size:9.0pt;color:#404040">퇴사사유</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">]</span><span style="font-size:9.0pt;color:#404040">정년퇴임</span>

**<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">과장</span>****<span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase"> | </span>****<span lang="EN-US" style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:uppercase">SKC&C</span>****<span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:
uppercase"> | </span>****<span lang="EN-US" style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#191919;text-transform:uppercase">1991.2 ~ 1995.3 (4</span>****<span style="font-size:9.0pt;color:#191919;text-transform:
uppercase">년</span>**** <span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#191919;text-transform:uppercase">2</span>****<span style="font-size:9.0pt;color:#191919;text-transform:uppercase">개월</span>****<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#191919;
text-transform:uppercase">)</span>**

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">[</span><span style="font-size:9.0pt;color:#404040">주요</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">수행</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">프로젝트</span><span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#404040">]</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">1\.</span> <span style="font-size:9.0pt;color:#404040">주유소</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">저유소</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">유류</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">판매</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">자동화</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">시스템</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">개발</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">프로젝트</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">   [</span><span style="font-size:9.0pt;color:#404040">담당업무</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">]</span><span style="font-size:9.0pt;color:#404040">프로그램개발</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">(C++, C)</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"> </span>

**<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040;text-transform:uppercase"> </span>**

**<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040;text-transform:uppercase"> </span>**

**<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040;text-transform:uppercase">    </span>**

<a name="OLE_LINK1"></a>**<span style="font-size:12.0pt;line-height:
75%;color:#4E4E4E">개발자로서</span>**** <span style="font-size:12.0pt;line-height:
75%;font-family:&quot;Cambria&quot;,serif;color:#4E4E4E"></span> ****<span style="font-size:12.0pt;line-height:75%;color:#4E4E4E">각오</span>**** <span style="font-size:12.0pt;line-height:75%;font-family:&quot;Cambria&quot;,serif;color:#4E4E4E"></span> ****<span style="font-size:12.0pt;line-height:75%;color:#4E4E4E">한마디</span>**

<span style="font-size:9.0pt;color:#404040">저는</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">소프트웨어</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">개발을</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">천직으로</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">생각하고</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">있던</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">차에</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">더</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">개발을</span><span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">잘</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">하려고</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">삼성</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">SDS</span>

<span style="font-size:9.0pt;color:#404040">입사를</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">했다가</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">삼성</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">SDS</span><span style="font-size:9.0pt;color:#404040">는</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">프로젝트</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">관리를</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">주로</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">하고</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">프로그램</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">개발을</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">협력업체가</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">전담하는</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">구조로</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">거기서</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">머물러</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">정년퇴임까지</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">세월을</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">보냈습니다</span><span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#404040">.</span>

<span style="font-size:9.0pt;color:#404040">그리고</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">정년퇴임</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">후</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">저의</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">아내와</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">결사적으로</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">내</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">의견을</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">논의한</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">결과</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">내가</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">하고</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">싶은</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">일을</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">다시</span>

<span style="font-size:9.0pt;color:#404040">하게</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">된</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">사람입니다</span><span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#404040">.</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">2014</span><span style="font-size:9.0pt;color:#404040">년부터</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">다시</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">시작했고</span><span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#404040">, Angular</span><span style="font-size:9.0pt;
color:#404040">를</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">시작</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">(2016</span><span style="font-size:9.0pt;color:#404040">년</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"><span lang="EN-US">8</span></span><span style="font-size:9.0pt;color:#404040">월</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">)</span><span style="font-size:9.0pt;color:#404040">한지는</span> <span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">3</span><span style="font-size:9.0pt;color:#404040">년이</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">되었습니다</span><span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#404040">.</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">Angular</span><span style="font-size:9.0pt;color:#404040">의</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">왠만한</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">기능을</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">구현하는데</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">어려움은</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">없고</span><span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;
color:#404040">대규모</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">프로젝트를</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">위해서</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">최근에는</span> <span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#404040">Redux</span><span style="font-size:9.0pt;
color:#404040">를</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">Angular</span><span style="font-size:9.0pt;color:#404040">에</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">적용한</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">경험이</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">있습니다</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">. Rxjs, Async, Await, Promise</span><span style="font-size:9.0pt;color:#404040">를</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">적절히</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">적용할</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">수</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">있습니다</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">.</span>

<span style="font-size:9.0pt;color:#404040">저는</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">현재</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">개발자</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">마인드로</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">단단히</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">무장되어</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">있으므로</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">저와</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">같이</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">일하면서</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">전혀</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">부담이</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">없이</span>

<span style="font-size:9.0pt;color:#404040">일하시어도</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">된다고</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">말씀드리고</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">싶고</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">매일</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">아침</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">미팅에서</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">자연스럽게</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">개발자의</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">일원으로</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">회의에</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">참석할</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">것이므로</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span>

<span style="font-size:9.0pt;color:#404040">나이와</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">관련된</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">어떠한</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">선입견이</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">없으시어도</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">됨을</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">말씀드립니다</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">.</span>

<span style="font-size:9.0pt;color:#404040">과거의</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">저의</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">이력과</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">경험을</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">비추어</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">제가</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">맡은</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">바</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">일은</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">잘</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">할</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">것으로</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">믿어</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">주시</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">길</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">부탁드립니다</span><span lang="EN-US" style="font-size:9.0pt;font-family:
&quot;Cambria&quot;,serif;color:#404040">. </span>

<span style="font-size:9.0pt;color:#404040">실제로</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">만나서</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">이야기하면</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">더</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">자세히</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">저의</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">열정을</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">보여</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">드릴</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">수</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;color:#404040">있으니</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">,</span> <span style="font-size:9.0pt;color:#404040">기회를</span> <span style="font-size:9.0pt;
font-family:&quot;Cambria&quot;,serif;color:#404040"></span> <span style="font-size:9.0pt;
color:#404040">주시면</span> <span style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"></span> <span style="font-size:9.0pt;color:#404040">고맙겠습니다</span><span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040">.</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040">.</span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;color:#404040"> </span>

<span lang="EN-US" style="font-size:9.0pt;font-family:&quot;Cambria&quot;,serif;
color:#404040"> </span>

<span lang="EN-US"> </span>

</div>
