# Oracle v Google -- new decision (2018-03-28)

- 2010년
  - Oracle이 Google을 상대로 저작권 침해 소송 제기 (이유 : Google이 Android를 만들면서 Java API 37개를 무단 도용)
- 2012년 5월,
  - 1심 (캘리포니아 북부 지역 법원) : Google 승리. Java API를 쓴 것은 저작권 침해가 아니라는 판결
  - 곧바로 Oracle 항소
- 2014년 5월
  - 2심 (연방 항소 법원) : Oracle 승리. Java API도 저작권 보호 대상이라고 판결
    - 한가지 유예 조건 추가 : Google의 저작권 침해 행위가 저작권법상의 공정 이용 (Fair Use)에 해당되는지 논의해보라면서 사건을 1심 법원으로 되돌려 보냄.
  - Google이 대법원에 상고
- 2015년 6월
  - 연방 대법원 : Google의 상고 신청을 받아들이지 않음.
- 2016년 5월
  - 캘리포니아 북부 지역 법원 : Google의 Java API 이용은 저작권법상의 공정 이용에 해당된다는 취지의 판결
  - Oracle 항소 (2016년 10월)
- 2018년 3월
  - 연방 항소 법원 : Google의 Java API 이용은 공정 이용으로 인정할 수 없다는 판결
- (추후)
  - 샌프란시스코 지역법원으로 무대를 옮겨 Google이 Oracle에 지불할 배상금 액수를 산정하는 또 다른 재판을 하게 됨 (Oracle은 그 동안 저작권을 침해한 Google에 90억 달러를 배상해달라고 요구해옴)

- References :  [http://www.zdnet.co.kr/news/news\_view.asp?artice\_id=20180328141031](http://www.zdnet.co.kr/news/news_view.asp?artice_id=20180328141031)

# Google vs. Oracle, 제2라운드

출처  :  [http://www.helloiplaw.com/598](http://www.helloiplaw.com/598)

(아래  내용은  위  출처의  글을  개인  학습을  위해  단순히  정리한  내용입니다.  내용에  대한  저작권은  위  출처  글의  작성자에게  있음을  알립니다.)  

## 1. 배경

- Java2  SE  (Standard  Edition)
    - Sun  Microsystems가  개발
    - Oracle이  매입

- API  (Application  Programming  Interface)  :  공통적이고  반복적인  컴퓨터  기능들을  구현

- Java  Programming  언어  자체는  누구든지  허락을  받을  필요  없이  무료로  사용  가능
- Oracle은  경쟁  Platform이나  Embedded  기기에  Java  API를  사용하는데에는  License  비용을  부과하고  있음

- Google
    - 2005년  Android  인수하여  Mobile  기기를  위한  새로운  Software  Platform  개발  착수
    - Java  Platform  사용에  관한  License  계약  체결을  위해  Sun  Microsystems와  협상  돌입  -&gt;  결론  없이  무산
    - 자체적으로  API  개발  시도  -&gt;  그  성과가  여의치  않았음
    - License를  체결하지  않은채  Java  채택
    - 37개의  Java  API  package에서  11,500줄에  달하는  declaring  code를  그대로  차용
    - Java  API  package의  SSO  (Structure,  Sequence,  Organization)을  그대로  베껴서  Android  운영체제  개발  및  공개

## 2.  법적  논쟁

- 2010년
    - Oracle은  Java에  관한  특허와  저작권법을  근거로  캘리포티아  주  북부  연방지방법원에  Google을  대상으로  침해의  소를  제기
    - Google은  저작권  침해에  관하여는  fair  use의  방어  법리를  들며  Java  API  사용이  정당함을  주장
    - 특허에  관한  부분은  비침해로  결론
    - 저작권에  관해서도  API  package는  저작권의  대상이  아니라는  법적  결론
        - 저작권  자체가  성립을  하지  않는다고  결론이  내려짐에  따라  fair  use인지에  관한  판단도  미뤄짐

- 2013년
    - Oracle  항소
    - 연방순회항소법원에서  Oracle  첫  승리
    - 항소법원은  Program  code와  SSO  역시  저작권의  보호를  받을  수  있다고  판결  (하위심의  판결을  뒤집음)

- Google은  연방대법원에  저작권  문제에  관하여  항소  신청  (petition  for  certiorari)  -&gt;  대법원은  이  신청을  거절

- 결국  이  사건은  1심으로  다시  환송이  되어  다음  issue인  fair  use에  관한  사항이  쟁점이  됨

- 두번째  사실심
    - Google  승리
    - Java  API  사용이  정당한  것으로  인정을  받음
    - Oracle  두번째  항소  (첫번째  항소와는  다른  사안)
        - Computer  code와  SSO가  저작권의  보호  대상이냐의  문제에  관한것이기  때문에  fair  use에  관한  별개의  문제로  재차  항소하는  것이  가능했음

- 결론  :  연방순회항소법원은  두번째  항소심에서도  하위심의  판결을  번복하며  Oracle의  손을  들어줌
    - 즉,  Google의  사용이  fair  use에  관한  방어  법리로  정당화  될  수  없다는  것이  그  요지

## 3.  Fair  Use

- Fair  use  (공정이용,  공정사용)
    - 미국에서  저작권  침해에  관해  가장  많이  사용되는  방어  수단  중  하나
    - 저작권  침해의  다른  모든  요소가  성립하는  경우에도  저작권물의  사용이  fair  use의  요건을  충족할  경우에  그  사용을  허용

- 적극적  방어시에만  효력
    - 연방대법원과  연방순회항소법원  등에서는  fair  use의  성격을  적극적  방어(affirmative  defense)라고  보고  있음
    - 즉,  fair  use의  범주에  해당한다고  해서  그  사용이  자동으로  비침해로  간주되는  것이  아니라  피고가  fair  use를  주장하여  이에  성공할  경우에만  손해배상  등의  책임을  면할  수  있는  것

- 연방법(17  U.S.C.  §  107)
    - fair  use는  원래  판사들의  재량에  의해  보통법(common  law)으로  발전해  옴
    - 1976년에  연방법(17  U.S.C.  §  107)으로  성문화
    - “저작권물을  “비평,  논평,  뉴스  보도,  교육,  .  .  .  ,  학술  혹은  연구”의  목적으로  사용하는  행위를  보호하는  것을  그  목적으로  삼는다”

- 보호  분야
    - 연방법  107조에  의한  fair  use의  방어  법리는  카테고리  별로  무조건  보호가  되는  분야가  정해져  있는  것이  아니라  각  사건  별로  개개의  사안을  통해(case-by-case)  인정
    - 위에  명시된  비평,  논평,  보도,  교육  등에  해당한다고  자동으로  보호가  되는  것이  아님 
    - 상기  카테고리에  속하지  않는다고  보호가  불가능한  것도  아님
    - 오로지  법원의  판단을  통해서만  적용이  되는  예외  사항

- 네가지  비배타적인  사항
    - 연방법  107조에는  다음  네  가지의  비배타적인  사항들을  고려해야  한다고  명시
    - 이  네  가지  사항을  모두  만족시켜야  하는  것은  아니며  법원은  네  가지의  요소를  모두  고려하고  저울질하여  종합적인  판단을  내려야  함
    - 이러한  사용이  상업적  성질의  것인지  또는  비영리적  교육목적을  위한  것인지의  여부를  포함한,  그  사용의  목적  및  성격;
    - 저작권이  있는  저작물의  성격;
    - 저작권이  있는  저작물  전체에서  사용된  부분이  차지하는  양과  상당성;  및
    - 이러한  사용이  저작권이  있는  저작물의  잠재적  시장이나  가치에  미치는  영향.

### A. 항소심에서 법적 판단 기준

- 연방대법원에  의하면  fair  use에  관한  사건에는  법과  사실의  판단이  섞여  있음(a  mixed  question  of  law  and  fact)
    - 그  중에서도  법적  판단이  좀  더  우선적

- 연방순회항소법원은  본  사건을  de  novo  판단기준을  적용하여  1심의  판결에  구속되지  않고  새로운  법적  판단
- 1심의  배심원들이  과거  사실에  관하여  내린  결론들은  오로지  참고  자료로만  사용했을  뿐  아무런  법적  구속력도  부여하지  않음

### B. Fair Use 고려 사항 제1요소 : 사용의 목적 및 성격

- Fair  use의  적용  여부를  가리는  데  있어서  판단해야  하는  첫  번째  요소는  사용의  목적  및  성격
- 여기에는  저작물의  사용이  상업적  성질의  것인지  혹은  비영리  교육적  목적의  것인지에  관한  판단  포함 
- 이  제1요소를  판단하는  데에는  크게  두  가지를  따짐
    - 첫  번째는  “상업적(commercial)  성질”에  관한  것  :  사실에  관한  것
    - 두  번째는  새로운  저작물이  “변화를  가져오는  것인지(transformative)”를  따지는  것  :  법에  관한  질의

#### (i)  상업적  성질

- 새로운  저작물(침해물)을  통해서  돈을  번다고  해서  무조건  상업적  성질로  보는  것은  아님
    - 대법원은  2차  저작물을  만드는  모든(적어도  대부분의)  사람들은  그와  같은  행위를  통해  금전적  수익을  얻으려고  한다는  사실을  이미  인지하고  있음
    - 따라서  상업적  성질을  인정받기  위해서는  단순히  기타  상업적  행위를  하면서  부차적으로  따르는  사용(incidental  use  as  part  of  a  commercial  enterprise)이  아니라  금전적  수익을  얻기  위한  행위의  정도가  얼마나  되는지를  고려하게  됨

- 본  사건에서  구글이  37개의  자바  API  패키지를  사용한  것이  상업적  목적이라는  데에는  양측의  이견이  없었음
    - 하지만  구글은  자사가  안드로이드  플랫폼을  무료로  공개했기  때문에  배심원들이  이를  비상업적  사용으로  볼  수  있는  여지가  존재
    - 구글이  벌어들인  광고수익은  안드로이드  운영체제가  공개되기  이전부터  이미  존재했던  검색을  통한  광고수익의  일부라고  간주할  수  있다고  주장

- 이에  대해  항소법원은  안드로이드가  무료라는  사실은  구글이  자바  API  패키지를  비상업적으로  사용했는가와는  전혀  별도의  사안이라고  판단
    - 즉,  냅스터(Napster)  사건에서  냅스터가  비록  불법으로  복제된  음원들을  돈을  받고  판매한  것은  아니었음에도  불구하고  냅스터의  사용  행위의  성질이  상업적인  것으로  보았듯이,  구글이  설령  비상업적인  목적으로  사용을  했다고  하더라도  이것은  법적인  관점에서는  아무런  효과가  없다는  것(“[Google’s]  non-commercial  motives  is  irrelevant  as  a  matter  of  law”).  

- 더군다나  항소법원은  상업적  성질을  입증하기  위해서는  직접적인  경제적  이익이  있었음을  밝힐  필요는  없으며,  상업적  성질을  밝히는  데  있어서  구글이  돈을  어떻게  벌었느냐는  중요하지  않다고  했음
    - 이와  같은  이유로  법원은  상업적  성질  측면만  보았을  때에는  일단  fair  use를  인정하기  어렵다고  판단

#### (ii)  변화

- Fair  use의  첫  번째  고려  요소인  사용의  목적  및  성격  중에서도  이  “변화(transformative)”에  관한  요소가  으뜸이라고  대법원은  밝힌  바  있음 
    - 기존의  저작물을  변화시켜  탄생시킨  새로운  창작물에  대한  사용을  인정해  주는  것이야말로  fair  use  법리의  핵심(“heart  of  the  fair  use  doctrine’s  guarantee  of  breathing  space”)이기  때문

- 저작물의  사용이  변화를  가져오는  것이냐의  문제는  그  새로운  저작물이  무언가  새롭거나  발전된  목적이나  다른  성질을  부여하거나  기존의  것을  새로운  표현,  의미,  메시지  등으로  재해석하는지(“adds  something  new,  with  a  further  purpose  or  different  character,  altering  the  first  with  new  expression,  meaning  or  message”)  여부를  가리는  것
    - 107조에  명시되어  있는  예외들(비평,  논평,  뉴스  보도  등)이  공정한  사용으로  인정받는  이유도  결국은  이  “변화를  가져다주는  사용”의  요건을  충족시키기  때문이라고  볼  수  있음
    - 따라서  변화를  동반한  사용으로  인정을  받기  위해서는  새로운  표현,  의미,  메시지를  통해  원래의  저작물을  바꾸어  놓거나(alter)  기존의  것과  다른  새로운  목적(new  purpose)을  가지고  사용해야  함

- 항소법원은  다음과  같은  이유로  구글의  API  사용이  변화를  수반하지  않았다고  판단
    - 첫째,  107에  명시된  어떠한  카테고리에도  해당하지  않았음.  
    - 둘째,  안드로이드에  들어있는  API  패키지는  기존  자바  플랫폼에  포함된  패키지와  완전히  동일한  목적으로  사용되었음.  
    - 셋째,  구글은  저작물의  표현이나  메시지를  아무런  가감  없이  그대로  차용했음
        - 여기서  구글이  자신의  안드로이드  API에  새로운  내용을  추가했는지  여부는  전혀  중요하지  않음,  
        - 즉  침해자는  자신의  창작물의  대부분이  순수창작물임을  근거로  일부  도용한  부분에  대해  용서를  받을  수  없음

    - 넷째,  스마트폰은  새로운  사용법이  아님
        - 즉,  안드로이드  플랫폼  이전에도  자바가  이미  모바일  기기에  널리  사용되었다는  증거가  제시됨

    - 여기서  특기할  만한  점으로  법원은  만약  구글이  API를  동일한  목적이  아닌  다른  목적,  예를  들어  API를  어떻게  설계하는지를  교육할  목적으로  자바  API를  복사해서  사용했다면  그것은  fair  use로  인정  받을  가능성이  높았으리라는  점을  시사했음

#### (iii)  악의  (bad  faith)

- 캘리포니아  주  북부  지방법원의  법정관할은  제9순회항소법원(Ninth  Circuit)의  소속이기  때문에  연방순회항소법원(Federal  Circuit)은  fair  use의  법리를  적용함에  있어서  제9순회항소법원의  판례를  따랐음
    - 제9순회항소법원의  판례에  의하면  상업적  성질과  변화  수반  여부에  추가로  침해자의  침해행위가  악의를  갖고  한  것인지,  즉  침해사실을  인지했음에도  불구하고  그  행위를  한  것인지를  고려한다고  함
    - 반면  선의의  침해행위는  고려대상이  아님
        - 즉,  침해사실을  알았을  경우에는  fair  use가  인정될  가능성이  낮아지지만,  침해사실을  몰랐다고  해서  반대로  fair  use가  인정될  가능성이  높아지는  것은  아님

- 본  사건에서는  구글이  시장진입을  서두르는  과정에서  자바  API가  썬마이크로시스템의  소유라는  사실을  알면서도  라이선스  계약을  체결하지  않았으므로  fair  use의  인정을  받는  데  불리하게  작용

### C. Fair Use 고려 사항 사항 제2요소 : 저작물의 성격

- 이  요소의  판단의  핵심은  저작물이  단순히  정보전달을  위한  것인지(informational)  혹은  창의적인  것인지(creative)를  가리는  것임
    - 예를  들어  전화번호부나  요리책  등은  정보전달의  성격이  강하고 
    - 소설이나  음악  등은  창의적  성격이  강하다고  볼  수  있음

- 소프트웨어는  문학작품  등과는  달리  순수한  창의성의  발현으로  보기는  어려운  점이  있지만  저작권법의  대상에  해당된다는  데에는  법적인  이견이  없음
- 제9순회항소법원의  판례에  의하면  창의성의  요소는  fair  use  판단에  있어서  크게  중요하지  않은  요소임(“not  .  .  .  terribly  significant  in  the  overall  fair  use  balancing”)
    - 즉,  네  가지  요소  중에서  가장  비중이  낮은  요소라고도  볼  수  있음

- 본  항소심에서  오라클은  API를  설계하는  것은  매우  창의적인  작업(highly  creative  process)이며  그  기능에만  구애  받는  것이  아님을  강조
    - 자바의  37개  API  패키지의  코드와  SSO가  저작권의  보호의  대상이  된다는  사실은  오라클의  첫  번째  항소심에서  이미  인정된  바  있음
    - 하지만  이는  저작권을  인정받기  위한  “최소한의  창의성(minimal  degree  of  creativity)”에  불과
    - 따라서  항소법원은  비록  배심원단이  이  창의성의  요소를  fair  use에  유리한  쪽으로  해석하기는  했지만  전체적으로  봤을  때는  그  영향이  상대적으로  미미하다고  보았음 

### D. Fair Use 고려 사항 제3요소 : 저작물 전체에서 사용된 부분이 차지하는 양과 상당성

- 세  번째  요소에서  양과  상당성의  기준은  2차  저작물,  즉  침해물이  아니라  원래의  저작물,  즉  저작권의  대상이  되는  저작물임
    - 즉,  본  사건으로  치면  안드로이드  API  안에서  베낀  코드가  차지하는  비중이  아니라  원래의  자바  API  전체  중에서  구글이  베껴간  코드의  비중이  얼마나  되느냐를  보는  것

- 제9순회항소법원은  이  세  번째  요소가  단순히  산술적으로  퍼센티지를  비교하는  것이  아니라  “유동성  있게(flexible)”  재단이  가능한  잣대라고  표현한  바  있음
- 캘리포니아  법원  1심에서  배심원단은  구글이  도용한  1만1500  줄의  코드는  286만  줄에  달하는  자바  SE  라이브러리의  1  퍼센트도  안  되는  극히  작은  부분(“tiny  fraction”)이라고  보았음
    - 이  중에서  자바  언어를  사용하기  위해서  반드시  사용할  수밖에  없는  필수적인  코드는  오직  170줄뿐이었음
    - 그러므로  오라클은  구글이  반드시  필요한  170줄의  코드  이외에도  1만1330  줄을  더  베꼈으므로  이것이  “상당한(substantial)”  양에  해당한다고  주장
    - 또한  37개  API에  대한  SSO  전체를  도용했다는  사실  역시  잊지  않고  강조
    - 구글은  이것이  시스템  간의  통일성을  유지하고  자바  프로그래머들에게  혼란을  야기하지  않기  위해서  필수적인  조치라고  항변

- 항소법원은  저작물의  인기를  등에  업거나  고객의  기대에  부응하기  위해서  저작물을  불법으로  도용할  권리가  주어지는  것은  아님을  역설하며  구글의  주장을  일축
    - 또한  구글의  전문가  증인(expert  witness)이  기존의  개발자들이  새로운  지식을  습득하지  않고도  새로운  플랫폼에  적응할  수  있도록  구글이  기존의  자바  모델을  대거  차용하였으며  동일한  기능을  구현하기  위해  전혀  새로운  API를  개발하는  것이  불가능하지  않았음을  시인한  점  역시  구글에게  불리하게  작용

- 결론적으로  법원은  이  세  번째  요소는  fair  use를  인정하는  데  있어  잘해도  중립(neutral)  요소밖에  안  되며  되려  불리하게  작용할  수도  있다고  판단을  내림

### E. Fair Use 고려 사항 제4요소 : 잠재적 시장이나 가치에 미치는 영향

- 네  번째  요소는  타인의  침해를  통해  저작물이  시장에서  입을  수  있는  가치  하락까지  감수하며  fair  use를  인정하는  것은  곤란하다는  내용을  그  골자로  함 
- 대법원은  이  네  번째  요소야말로  “의심의  여지  없이  fair  use의  가장  중요한  요소(undoubtedly  the  single  most  important  element  of  fair  use)”라고  치켜세운  바  있음
    - 여기에서  “잠재적  시장”이라  함은  피고뿐  아니라  다른  모든  사람의  잠재적  침해행위를  포함하며  저작권자가  이미  판매  중이거나  판매할  계획이  없는  제품에  대한  잠재력까지도  고려
    - 다시  말해  본  사건의  경우,  단순히  구글이  안드로이드  API를  통해  시장에  미치는  영향뿐  아니라  만약  본  사건에서  fair  use가  인정될  경우  비슷한  사례로  다른  경쟁업체들(예를  들어  애플,  삼성,  LG,  블랙베리  등)이  너도나도  비슷한  침해  행위를  할  시에  오라클이  입게  될  피해까지  모두  따지는  것

- 따라서  법원은  침해  행위가  전형적이거나  합리적이거나  생겨날  가능성이  높은  시장(“traditional,  reasonable,  or  likely  to  be  developed  markets”)을  통해  얻을  수  있는  잠재적  라이선스  수입에  미치는  영향을  고려할  수  있음
    - 여기에는  저작권자가  저작물을  언제  어떤  방식으로  유통할지에  관한  독점적인  결정권을  가진다는  사실  역시  고려  대상에  들어감

### F. 네가지 요소의 저울질

- 본  사건에서  항소법원은  안드로이드가  출시되기  이전에  자바  SE가  이미  시장에  본격적으로  진출을  했었으며  블랙베리,  노키아  등의  스마트폰에  이미  널리  사용되었고  안드로이드가  자바  SE의  직접적인  경쟁상품이  되었다는  점에서  오라클이  시장에서  실제로  피해(actual  market  harm)를  입었음을  인정
- 법원은  특히  아마존이  자사의  킨들  파이어  태블릿을  개발할  때  자바  SE와  안드로이드  중에서  어느  플랫폼을  선택할지  기로에  놓여  있었다가  결국은  안드로이드를  택했을  뿐아니라  안드로이드가  무료라는  사실을  오라클과의  라이선스  체결  협상에서  자신에게  유리하도록  협상  카드로  사용하여  라이선스  비용  할인을  유도하려  했다는  사실을  인용
    - 이에  대해  구글은  오라클이  직접  스마트폰을  제작  및  판매하지  않았고  자신만의  스마트폰  플랫폼을  구축하지  않았었기  때문에  자바  SE와  안드로이드는  직접적인  경쟁  상대가  아니었다고  항변
    - 항소법원은  그와  같은  사실은  잠재적  시장에  미치는  영향이라는  법적  판단에  있어서  아무런  영향을  미치지  않는다(irrelevant)고  선을  그었음
        - 그  이유인즉슨  저작권자가  당장  해당  시장에  진입할  의지가  없거나  시장에서  성공을  하지  못했다고  하더라도  “잠재적”  시장에  미치는  영향에는  변함이  없으며  오라클은  언제든지  변심을  할  권리가  있다는  것

- 따라서  법원은  네  번째  요소에  관한  한은  구글이  저작물의  잠재적  시장에  지대한  부정적  영향(“substantially  adverse  impact”)을  끼쳤다고  결론을  내림

## 4.  맺음말

- 추후  당연한  수순
    - Google이  연방순회항소법원에서  전원합의체(en  banc)판결을  신청하거나
    - 대법원에  항소  신청  (petition  for  certiorari)

- 그러나,  이러한  신청이  받아들여질  가능성은  미미해보임
- fair  use가  모든  저작권  침해  방어에  사용할  수  있는  만병통치약이  아님을  확인
- fair  use의  법리만  믿고  악의의  침해  사용을  하는  것은  매우  위험
- fair  use에  관한  결론은  재판관의  재량과  각  사건의  사실관계에  따라  예측하기가  어려움
    - 소송  지역에  따라  적용되는  법리가  미묘하게  달라서  결과  역시  조금씩  달라질  수  있음

- 본  사건의  판례로  인해  computer  code에  fair  use의  방어  법리를  사용할  수  없다는  뜻은  아님.  
    - 연방순회항소법원  역시  본  판례는  “computer  code를  도용하는  경우에  fair  use  defense가  절대로  성립할  수  없다는  것은  아니다.”  라고  분명히  못을  박고  있음

