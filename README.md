# <h2>Thailand-s_Budget_Explanatory_Analysis_and_Visualization</h2>
# <h3>Mini project dads5001: สำรวจงบประมาณประเทศไทย ใช้เงินไปกับอะไรบ้าง?</h3>
โดยงานชิ้นนี้ต้องการค้นหาและตอบคำถามว่างบประมาณถูกจัดสรรอย่างไร โดยประกอบด้วย n ส่วน
# <h3>งบประมาณถูกจัดสรรอย่างไรในแง่หน่วยงาน?</h3>

![image](https://github.com/user-attachments/assets/e3167d81-0e01-4cc5-8644-c64a0feeb579)


จากข้อมูลงบประมาณปี 2566-2568 ในภาพรวม งบประมาณถูกจัดสสรเพิ่มทุกปีประมาณ 3 แสนล้านบาท
โดยถ้าดูในภาพรวมของการจัดสรรงบประมาณในหน่วยงานระดับกระทรวงทั้ง 3 ปี จะเห็นได้ว่างบประมาณจะกระจุกตัวอยู่ใน 12 หน่วยงานระดับกระทรวง ซึ่งได้รับงบประมาณเกินเส้นค่าเฉลี่ยของการจัดสรรงบประมาณ (เส้นสีแดงค่าเฉลี่ย 3.15 แสนล้าน)
ซึ่งจากทั้ง 12 หน่วยงานดังกล่าว จะสังเกตุได้ว่า งบกลางจะถูกจัดสรรมากเป็นพิเศษ ถึง 2 ล้านล้าน บาท เมื่อเทียบกับหน่วยงานที่เหลือที่ได้รับการจะสรรงบอยู่ในช่วง 3.67 แสนล้าน ถึง 1 ล้านล้าน

                                            
|MINISTRY|2023|2024|2025|Mean\_of\_Absolute\_change|
|---|---|---|---|---|
|งบกลาง|1|1|1|0\.0|
|กระทรวงศึกษาธิการ|2|3|3|0\.5|
|กระทรวงมหาดไทย|3|2|4|1\.5|
|กระทรวงการคลัง|4|4|2|1\.0|
|ทุนหมุนเวียน|5|5|5|0\.0|
|กระทรวงกลาโหม|6|6|6|0\.0|
|กระทรวงคมนาคม|7|7|8|0\.5|
|รัฐวิสาหกิจ|8|9|10|1\.0|
|กระทรวงสาธารณสุข|9|8|9|1\.0|
|กระทรวงเกษตรและสหกรณ์|10|12|13|1\.5|
|ส่วนราชการไม่สังกัดสำนักนายกรัฐมนตรี กระทรวง หรือทบวง และหน่วยงานภายใต้การควบคุมดูแลของนายกรัฐมนตรี|11|11|11|0\.0|
|กระทรวงการอุดมศึกษา วิทยาศาสตร์ วิจัยและนวัตกรรม|12|10|12|2\.0|
|องค์กรปกครองส่วนท้องถิ่น|13|13|7|3\.0|
|กระทรวงแรงงาน|14|14|14|0\.0|
|สำนักนายกรัฐมนตรี|15|15|15|0\.0|
|กระทรวงทรัพยากรธรรมชาติและสิ่งแวดล้อม|16|16|16|0\.0|
|กระทรวงยุติธรรม|17|17|17|0\.0|
|กระทรวงการพัฒนาสังคมและความมั่นคงของมนุษย์|18|18|18|0\.0|
|หน่วยงานของศาล|19|19|19|0\.0|
|จังหวัดและกลุ่มจังหวัด|20|20|21|0\.5|
|หน่วยงานขององค์กรอิสระและองค์กรอัยการ|21|21|20|0\.5|
|สภากาชาดไทย|22|23|23|0\.5|
|ส่วนราชการในพระองค์|23|25|26|1\.5|
|หน่วยงานของรัฐสภา|24|26|27|1\.5|
|กระทรวงการต่างประเทศ|25|22|24|2\.5|
|กระทรวงดิจิทัลเพื่อเศรษฐกิจและสังคม|26|24|22|2\.0|
|กระทรวงวัฒนธรรม|27|27|25|1\.0|
|กระทรวงพาณิชย์|28|28|28|0\.0|
|กระทรวงการท่องเที่ยวและกีฬา|29|29|29|0\.0|
|กระทรวงอุตสาหกรรม|30|30|30|0\.0|
|กระทรวงพลังงาน|31|31|31|0\.0|
|หน่วยงานอื่นของรัฐ|32|32|32|0\.0|

โดยเมื่อพิจารณาถึงลำดับของหน่วยงานระดับกระทรวงที่ได้รับจัดสรรงบประมาณมากที่สุด จะเห็นได้ว่าลำดับดังกล่าวไม่ได้มีการเปลี่ยนแปลงมาก โดยมี 15 จาก 32 หน่วยงานที่ลำดับการได้รับจัดสรรงบประมาณไม่ได้มีการเปลี่ยนแปลงเลยในรอบ 3 ปีงบประมาณ (2566-2568)
และหน่วยงานที่เหลือก็มีการเปลี่ยนแปลงโดยเฉลี่ยเล็กน้อยในช่วง 0.5-3 ลำดับ แต่อย่างไรก็ตามจะเห็นได้ว่า องค์กรปกครองส่วนท้องถิ่น	เป็นหน่วยงานที่มีการเปลี่ยนแปลงในแง่ของลำดับมากที่สุด โดยจากในปีงบประมาณ 2566 และ 2567 ได้รับการจัดสรรมากเป็นลำดับ 13 
แต่ในปี 2568  ได้รับการจัดสรรมากเป็นลำดับ 7

![image](https://github.com/user-attachments/assets/8eba8f2b-acc6-474d-8911-4213b5f39769)

แต่อย่างไรก็ตามถึงแม้ลำดับของหน่วยงานระดับกระทรวงที่ได้รับจัดสรรงบประมาณ ไม่ค่อยมีการเปลี่ยนแปลงนัก แต่การเปลี่ยนแปลงของจำนวนงบประมาณในแง่สัดส่วนมีการเปลี่ยนแปลงที่เห็นได้ชัด โดยจากตาราง จะเห็นได้ว่าในการเปลี่ยนแปลงของงบประมาณของหน่วยงานในแง่สัดส่วน ปี 2566-2567 ได้รับการจัดสรรงบลดลงมากสุด -11.78% ได้รับการจัดสรรงบเพิ่มมากสุด +29.4% ปี 2567-2568 ได้รับการจัดสรรงบลดลงมากสุด -16.5% ได้รับการจัดสรรเพิ่มมากสุด +93.12% ซึ่งสามารถเห็นการเปลี่ยนของงบประมาณในแง่สัดส่วนอย่างชัดเจน โดยมีหน่วยงานที่การเปลี่ยนแปลงอย่างมีนัยสำคัญเช่น องค์กรปกครองส่วนท้องถิ่น ซึ่ง ในปี2568 ได้รับการจัดสรรงบประมาณเพิ่มขึ้นจากปีที่แล้วถึง 93.12% กระทรวงมหาดไทย ในปี2568 ได้รับการจัดสรรงบลดลงมากสุด โดยลดลงถึง -16.5%


![image](https://github.com/user-attachments/assets/e4c8daf9-a336-4c4b-b659-11a07978ff4a)

โดยจากตารางแสดงการเปลี่ยนแปลงของจำนวนงบประมาณในแง่จำนวนเงิน สามารถเห็นได้ จำนวนเงิน ที่ องค์กรปกครองส่วนท้องถิ่น  ในปี2568 ได้รับการจัดสรรงบประมาณเพิ่มถึง 9.4 หมื่นล้านบาท ซึ่งก็เห็นได้ชัดว่าเป็นการโยก งบประมาณที่มาจากการตัดงบประมาณของกระทรวงมหาดไทยในปี2568 ที่ถูกจัดสรรงบประมาณลดลงถึง 5.8 หมื่นล้านบาท ก็เห็นได้ชัดในเบื้องต้นว่าในปีงบประมาณ 2568 มีการกระจายงาน ภารกิจ ส่วนนึงของกระทรวงมหาดไทย ไปสู่ องค์กรปกครองส่วนท้องถิ่น

ซึ่งโดยสรุปจากทั้งสองตาราง จะแสดงให้เห็นว่า หน่วยงานส่วนใหญ่ได้รับจากจัดสรรงบประมาณเพิ่ม ในปี 2567 มีเพียง 4 หน่วยงานที่ถูกลดงบประมาณลง  ในปี 2568 มีเพียง 2 หน่วยงานที่ถูกลดงบประมาณลง และงบประมาณที่ถูกลดก็จะถูกจัดสรรไปให้หน่วยงานอื่น ๆ ตามนโยบายของรัฐบาล 

# <h3>งบประมาณถูกจัดสรรอย่างไรในแง่พื้นที่?</h3>
<h4>งบประมาณถูกจัดสรรอย่างไรในแง่พื้นที่ (ส่วนภูมิภาค)</h4>

![image](https://github.com/user-attachments/assets/a6732e2c-43c6-4a1f-a66d-e427df126c0d)


|index|BUDGETARY\_UNIT|2023|2024|2025|2023\_rank|2024\_rank|2025\_rank|2023\_2024\_change|2024\_2025\_change|Mean\_of\_Absolute\_change|
|---|---|---|---|---|---|---|---|---|---|---|
|17|นครราชสีมา|362960200\.0|380655300\.0|413379600\.0|1|2|1|4\.875217723596141|8\.596832882663135|1\.0|
|70|เชียงใหม่|345875600\.0|351464100\.0|353106200\.0|2|4|3|1\.6157543347955161|0\.46721699314382326|1\.5|
|7|ชลบุรี|335446300\.0|372738500\.0|381302100\.0|3|3|2|11\.117189249069076|2\.2974820148710156|0\.5|
|41|ระยอง|306798200\.0|331647100\.0|331129500\.0|4|5|5|8\.099428223503267|-0\.15606950882428944|0\.5|
|51|สมุทรปราการ|303646300\.0|309680500\.0|330573800\.0|5|8|6|1\.9872463455013283|6\.746727675781976|2\.5|
|67|อุบลราชธานี|302771600\.0|313669400\.0|342509700\.0|6|7|4|3\.5993468343794466|9\.194489484788763|2\.0|
|24|บุรีรัมย์|299779800\.0|305308900\.0|310861800\.0|7|9|9|1\.8443871134746235|1\.818780913363482|1\.0|
|4|ขอนแก่น|286774400\.0|320491400\.0|327336200\.0|8|6|7|11\.757325619023176|2\.1357203344613924|1\.5|
|64|อุดรธานี|285616600\.0|431610400\.0|293212300\.0|9|1|14|51\.11530632323191|-32\.065515566816735|10\.5|
|69|เชียงราย|276841000\.0|302635800\.0|317242000\.0|10|10|8|9\.317550507330923|4\.826329204938742|1\.0|
|2|กาฬสินธุ์|267758000\.0|270845000\.0|300677800\.0|11|16|11|1\.1529067292107054|11\.01471321235393|5\.0|
|18|นครศรีธรรมราช|264106100\.0|300142200\.0|298624500\.0|12|11|12|13\.644554215143081|-0\.5056603170097373|1\.0|
|49|สงขลา|263025700\.0|296173200\.0|294996400\.0|13|12|13|12\.602380679910747|-0\.39733507285601805|1\.0|
|75|แม่ฮ่องสอน|254269900\.0|280116100\.0|284982600\.0|14|13|15|10\.164868118483549|1\.7373153488856943|1\.5|
|47|ศรีสะเกษ|248395400\.0|275513200\.0|308153300\.0|15|15|10|10\.917190898060108|11\.84701858204979|2\.5|
|21|นราธิวาส|246273200\.0|239378600\.0|242708700\.0|16|26|31|-2\.7995738066505003|1\.3911435692246508|7\.5|
|59|สุรินทร์|244997400\.0|249997400\.0|262551200\.0|17|20|20|2\.0408379844030997|5\.021572224351133|1\.5|
|13|ตาก|242506600\.0|244312500\.0|251960400\.0|18|24|22|0\.7446807633276785|3\.130376055257099|4\.0|
|48|สกลนคร|241208200\.0|243835400\.0|259500200\.0|19|25|21|1\.0891835352197812|6\.424333792386175|5\.0|
|28|ปัตตานี|238382400\.0|276119000\.0|282754600\.0|20|14|16|15\.830279416601226|2\.40316675056769|4\.0|
|19|นครสวรรค์|237608000\.0|259035200\.0|268950500\.0|21|17|18|9\.017878185919665|3\.827780934791874|2\.5|
|1|กาญจนบุรี|237604100\.0|248615600\.0|251102700\.0|22|21|24|4\.634389726439906|1\.0003797026413468|2\.0|
|39|ยโสธร|234101000\.0|214596300\.0|213150400\.0|23|44|52|-8\.331745699505769|-0\.6737767612955116|14\.5|
|6|ฉะเชิงเทรา|230421000\.0|256080000\.0|267718300\.0|24|18|19|11\.135703776999492|4\.544790690409247|3\.5|
|42|ราชบุรี|225709200\.0|226458500\.0|239047200\.0|25|32|33|0\.33197583439221795|5\.55894347087877|4\.0|
|58|สุราษฎร์ธานี|224701100\.0|247509100\.0|247901600\.0|26|22|27|10\.150373095636827|0\.1585800279666485|4\.5|
|9|ชัยภูมิ|224564200\.0|229420900\.0|250071400\.0|27|30|25|2\.1627222860990307|9\.001141569926716|4\.0|
|29|พระนครศรีอยุธยา|224145300\.0|225501000\.0|243744100\.0|28|33|30|0\.6048308842523131|8\.090030642879633|4\.0|
|43|ร้อยเอ็ด|223015000\.0|253979700\.0|275919400\.0|29|19|17|13\.884581754590497|8\.638367554572275|6\.0|
|25|ปทุมธานี|219732500\.0|232079800\.0|247478900\.0|30|28|28|5\.6192415778275855|6\.635260802534301|1\.0|
|55|สระแก้ว|218482100\.0|222910100\.0|233107300\.0|31|37|36|2\.026710655014759|4\.5745796175229385|3\.5|
|38|ยะลา|217309500\.0|234787600\.0|245309700\.0|32|27|29|8\.042952563049475|4\.481539910966338|3\.5|
|72|เพชรบูรณ์|215438700\.0|216659000\.0|232716300\.0|33|41|37|0\.5664256236228681|7\.411323785303173|6\.0|
|32|พัทลุง|215243000\.0|220030700\.0|220026100\.0|34|38|46|2\.2243232067941814|-0\.0020906173547600403|6\.0|
|20|นนทบุรี|214041200\.0|218367100\.0|238250700\.0|35|39|34|2\.0210594969566604|9\.105584128744669|4\.5|
|53|สมุทรสาคร|210566900\.0|247166900\.0|249659700\.0|36|23|26|17\.38164925256534|1\.0085492839049242|8\.0|
|44|ลพบุรี|209856200\.0|202830000\.0|218366200\.0|37|50|48|-3\.3481021766333328|7\.659715032293053|7\.5|
|27|ปราจีนบุรี|207240700\.0|227762600\.0|226754900\.0|38|31|42|9\.902446768419523|-0\.44243435928462355|9\.0|
|16|นครพนม|203919600\.0|206511300\.0|224975200\.0|39|48|44|1\.2709420771715911|8\.940866674123885|6\.5|
|15|นครปฐม|203766700\.0|208915400\.0|231669500\.0|40|47|38|2\.5267622236606866|10\.891537914390227|8\.0|
|36|มหาสารคาม|201789500\.0|217789000\.0|218248800\.0|41|40|49|7\.9288069993731085|0\.21112177382696093|5\.0|
|62|หนองบัวลำภู|201562200\.0|231272900\.0|236913700\.0|42|29|35|14\.740214186985456|2\.4390233356350874|9\.5|
|22|น่าน|200748400\.0|224746700\.0|230621900\.0|43|35|39|11\.954416573183149|2\.6141429440343282|6\.0|
|3|กำแพงเพชร|198529200\.0|223030800\.0|223507800\.0|44|36|45|12\.341559830997154|0\.21387180604651915|8\.5|
|11|ตรัง|193642200\.0|199166300\.0|218375800\.0|45|53|47|2\.852735612382012|9\.644954994896224|7\.0|
|8|ชัยนาท|193063900\.0|214908900\.0|213149400\.0|46|43|53|11\.314906619000238|-0\.8187190014001281|6\.5|
|5|จันทบุรี|192677500\.0|200995100\.0|203800300\.0|47|52|57|4\.316850696111378|1\.3956559139998934|5\.0|
|45|ลำปาง|189858100\.0|194307400\.0|239674000\.0|48|57|32|2\.3434870569125046|23\.347849850288767|17\.0|
|30|พะเยา|188918900\.0|214322000\.0|227617700\.0|49|45|41|13\.4465635783397|6\.203609522120921|4\.0|
|60|สุโขทัย|185882400\.0|201067300\.0|227663300\.0|50|51|40|8\.169089704027924|13\.227411916308618|6\.0|
|73|เลย|185828300\.0|205513300\.0|210373300\.0|51|49|54|10\.593112028684544|2\.3648104526568354|3\.5|
|37|มุกดาหาร|185089500\.0|190563200\.0|190851600\.0|52|59|64|2\.9573260503702263|0\.15134086749172979|6\.0|
|54|สระบุรี|184369000\.0|187838900\.0|207541200\.0|53|61|55|1\.8820409070939257|10\.488934933072969|7\.0|
|65|อุตรดิตถ์|183591700\.0|215508400\.0|215966600\.0|54|42|50|17\.38460943495812|0\.2126135222571371|10\.0|
|50|สตูล|182909100\.0|195903000\.0|194437600\.0|55|56|62|7\.104020521668961|-0\.7480232564075078|3\.5|
|66|อุทัยธานี|182477100\.0|191745000\.0|197166500\.0|56|58|61|5\.078938672304634|2\.8274531278520953|2\.5|
|12|ตราด|180976700\.0|179830900\.0|177696800\.0|57|65|70|-0\.6331201751385676|-1\.1867259742346838|6\.5|
|26|ประจวบคีรีขันธ์|178466600\.0|176917800\.0|190102800\.0|58|66|65|-0\.8678374552997591|7\.452613586648715|4\.5|
|34|พิษณุโลก|178222600\.0|224874000\.0|225505500\.0|59|34|43|26\.17591708346753|0\.28082392806638384|17\.0|
|71|เพชรบุรี|176188400\.0|197855500\.0|206411100\.0|60|55|56|12\.29768815654152|4\.324165868525262|3\.0|
|10|ชุมพร|175792400\.0|197949200\.0|199013100\.0|61|54|59|12\.603957850282493|0\.5374611263900031|6\.0|
|74|แพร่|171344400\.0|190328000\.0|203335900\.0|62|60|58|11\.079206557086197|6\.834464713547139|2\.0|
|68|อ่างทอง|171144000\.0|172221300\.0|197618300\.0|63|69|60|0\.6294699200673117|14\.746724127619522|7\.5|
|61|หนองคาย|168579200\.0|184530000\.0|189003900\.0|64|62|66|9\.461902773295876|2\.424483823768493|3\.0|
|23|บึงกาฬ|167270300\.0|169270300\.0|173365700\.0|65|71|71|1\.195669524117551|2\.4194439308018003|3\.0|
|0|กระบี่|166745700\.0|175281800\.0|188479500\.0|66|67|67|5\.119232459967484|7\.529418342349291|0\.5|
|46|ลำพูน|166558300\.0|183030000\.0|187973900\.0|67|63|68|9\.889450120468329|2\.7011418893077637|4\.5|
|33|พิจิตร|165416500\.0|182316500\.0|185402500\.0|68|64|69|10\.216634978977309|1\.6926608398033092|4\.5|
|14|นครนายก|165240700\.0|161877400\.0|162463300\.0|69|73|73|-2\.0353944276440368|0\.361940579722679|2\.0|
|40|ระนอง|163791100\.0|168067200\.0|214077800\.0|70|72|51|2\.610703511973483|27\.376311380209824|11\.5|
|63|อำนาจเจริญ|163498200\.0|170315200\.0|190931400\.0|71|70|63|4\.169464862610108|12\.104732871757776|4\.0|
|35|ภูเก็ต|163063000\.0|174195900\.0|169365500\.0|72|68|72|6\.827361203951847|-2\.772969972312781|4\.0|
|31|พังงา|159499200\.0|161284700\.0|151162100\.0|73|74|75|1\.1194413514299757|-6\.276230789405318|1\.0|
|56|สิงห์บุรี|148800200\.0|150260000\.0|160417900\.0|74|75|74|0\.9810470684851229|6\.760215626247837|1\.0|
|57|สุพรรณบุรี|140349900\.0|211322500\.0|251203300\.0|75|46|23|50\.56832958199472|18\.87200842314472|26\.0|
|52|สมุทรสงคราม|128180200\.0|147392300\.0|151031100\.0|76|76|76|14\.988352335228061|2\.4687856828341777|0\.0|


การจัดสรรปีงบประมาณในแง่พื้นที่ (ส่วนภูมิภาค)ทั้ง 3 ปีงบประมาณ เห็นได้ชัดว่าส่วนใหญ่จะมีการจัดสรรงบประมาณเพิ่มขึ้นทุกปี และลำดับการจัดสรรงบประมาณในจังหวัดขนาดใหญ่จะไม่ค่อยมีการเปลี่ยนแปลงหรือเปลี่ยนแปลงเพียงเล็กน้อย ต่างจากจังหวัดขนาดเล็กจะมีความผันผวนของลำดับการจัดสรรงบประมาณมากกว่า ตัวอย่างเช่น นครราชสีมาที่เป็นจังหวัดที่ได้รับการจัดสรรงบประมาณมากที่สุดในปี 2566 และ 2568 จังหวัดสุพรรณบุรี ที่ได้รับการจัดสรรงบมากที่สุดลำดับ 75 46 23 ในปี 2566 2567 2568 ตามลำดับ

![image](https://github.com/user-attachments/assets/2d8053d1-0f77-4215-b981-8da820f5c82b)


