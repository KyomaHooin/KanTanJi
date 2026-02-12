
# Kan<sup>Tan</sup>Ji &nbsp; 漢<sup>単</sup>字

> Simple KanJi training platform for czech audience.

Jednoduchá aplikace na trénování Kanji. Projekt vznikl jako spolupráce dobrovolníků
a japanistů na FF MUNI. Cílem je nabídnout různé způsoby učení kanji s kompletními
informacemi přímo v češtině.

[Vaše zpětná vazba je pro nás cenná! Prosíme, kontaktujte nás na stránce projektu.](https://github.com/KanjiBase/KanTanJi/issues)
Uvedený odkaz lze použít i pro pispívání do databáze.
Pokud chcete pomoci s přípravou obsahu a nebo máte jiný nápad, neváhejte nám dát vědět.

Kan<sup>Tan</sup>Ji je open-source projekt, a nemá žádný vztah s existujícími profily na sociálních sítích.

### FAQ
<details>
<summary>Jaký je stav projektu?</summary>
Kan<sup>Tan</sup>Ji může obsahovat drobné nedostatky, typicky způsobené lidskou chybou při zadávání tisíců slovíček
a příkladových vět - dejte nám vědět, pokud nějaké najdete! Japonský školní systém je hotový vždy po poslední sadu, 
ve které typicky chybí pár znaků, které se v BKB pořadí ještě nevyskytují. BKB pořadí je kompletní dle existující sady.
V budoucnu plánujeme pokračovat v množství podporovaných kanji.
</details>
<details>
<summary>
Řazení znaků a velikosti sad
</summary>
Řazení a velikosti nejsou zcela vymyšleny tak, aby vyhovovaly všem. Pořadí jsou k dispozici 
dle níže uvedených kapitol. Ke každému pořadí jsou dostupné všechny typy materiálů (PDF, Anki, HTML stránky, atp.).
V budoucnu bychom rádi rozšířili počet nánstrojů, které kanji umožňují studovat, a umožnili uživatelům vytvářet vlastní 
pořadí a vlastní velikosti sad.
</details>
<details>
<summary>Filtrování karet Anki</summary>
Karty KanTanJi mohou obsahovat více, než se chcete učit. Karty lze snadno filtrovat pomocí **tagů**. V současnosti jsou k dispozici tagy:

 - **KanTanJi_Kanji** (karta s kanji)
 - **KanTanJi_Tango** (slovní zásoba související s kanji)
 - **KanTanJi_Learn_Now** (slovní zásoba obsahující pouze kanji, která již byla naučena)
 - **KanTanJi_Learn_Deck** (slovní zásoba obsahující kanji, která se bude učit v aktuálním balíčku)
 - **KanTanJi_Learn_Future** (slovní zásoba obsahující kanji, která ještě nebyla naučena)

Pokud chcete například odstranit všechny karty s kanji a příliš obtížnou slovní zásobu obsahující kanji, 
která ještě nebyla naučena podle pořadí KanTanJi, můžete **pozastavit** karty s tagy 
'KanTanJi_Kanji' a 'KanTanJi_Learn_Future'.

Nejprve v aplikaci Anki **otevřete Prohlížení karet (Browse Cards)**. Poté v možnostech vyberte **filtrovat podle tagu**.
Když jsou zobrazeny pouze požadované karty, opět v možnostech zvolte **vybrat všechny karty** 
a nakonec také v možnostech vyberte **pozastavit (suspend)**.

Doporučujeme slučovat studované sady do jedné velké sady, aby bylo možné využít výhod chytrého opakování v Anki.
</details>

## Pořadí: Japonský Školní Systém
Učte se pořadí kanji, jaký používá školní systém v Japonsku. Pořadí preferuje jednoduché znaky, může tak představovat časté a užitečné (ale složité) znaky později.
### PDF Materiály
PDF Soubory obsahují seznam znaků kanji a přidružených slovíček.
 - <a href="static/1/2/81-160.pdf">81-160</a>

 - <a href="static/1/3/161-240.pdf">161-240</a>

 - <a href="static/1/4/241-320.pdf">241-320</a>


### ANKI Balíčky
Balíčky lze importovat opakovaně do ANKI aplikace. Balíčky se řadí do kolekce 'KanTanJi' 
a umožňují chytré a interaktivní procvičování kanji. Balíček obsahuje jak kanji (poznáš podle
toho, že karta otázky obsahuje link na KanjiAlive), tak slovní zásobu ke kanji.
Furiganu zobrazíš kliknutím / tapnutím na kartičku.

 - <a href="static/1/2/81-160.apkg">81-160</a>

 - <a href="static/1/3/161-240.apkg">161-240</a>

 - <a href="static/1/4/241-320.apkg">241-320</a>


### HTML
HTML Stránky slouží pro vložení interaktivních informací o Kanji do externích webových služeb.

#### Kanji Stránky 81-160 2
<a href="static/1/2/毛.html">毛</a>  <a href="static/1/2/心.html">心</a>  <a href="static/1/2/雪.html">雪</a>  <a href="static/1/2/南.html">南</a>  <a href="static/1/2/角.html">角</a>  <a href="static/1/2/強.html">強</a>  <a href="static/1/2/北.html">北</a>  <a href="static/1/2/秋.html">秋</a>  <a href="static/1/2/高.html">高</a>  <a href="static/1/2/夏.html">夏</a>  <a href="static/1/2/少.html">少</a>  <a href="static/1/2/外.html">外</a>  <a href="static/1/2/兄.html">兄</a>  <a href="static/1/2/広.html">広</a>  <a href="static/1/2/矢.html">矢</a>  <a href="static/1/2/野.html">野</a>  <a href="static/1/2/曜.html">曜</a>  <a href="static/1/2/地.html">地</a>  <a href="static/1/2/時.html">時</a>  <a href="static/1/2/園.html">園</a>  <a href="static/1/2/頭.html">頭</a>  <a href="static/1/2/万.html">万</a>  <a href="static/1/2/内.html">内</a>  <a href="static/1/2/里.html">里</a>  <a href="static/1/2/交.html">交</a>  <a href="static/1/2/新.html">新</a>  <a href="static/1/2/東.html">東</a>  <a href="static/1/2/弟.html">弟</a>  <a href="static/1/2/雲.html">雲</a>  <a href="static/1/2/今.html">今</a>  <a href="static/1/2/長.html">長</a>  <a href="static/1/2/母.html">母</a>  <a href="static/1/2/海.html">海</a>  <a href="static/1/2/直.html">直</a>  <a href="static/1/2/多.html">多</a>  <a href="static/1/2/弱.html">弱</a>  <a href="static/1/2/細.html">細</a>  <a href="static/1/2/点.html">点</a>  <a href="static/1/2/昼.html">昼</a>  <a href="static/1/2/春.html">春</a>  <a href="static/1/2/岩.html">岩</a>  <a href="static/1/2/冬.html">冬</a>  <a href="static/1/2/顔.html">顔</a>  <a href="static/1/2/父.html">父</a>  <a href="static/1/2/後.html">後</a>  <a href="static/1/2/間.html">間</a>  <a href="static/1/2/数.html">数</a>  <a href="static/1/2/分.html">分</a>  <a href="static/1/2/朝.html">朝</a>  <a href="static/1/2/親.html">親</a>  <a href="static/1/2/国.html">国</a>  <a href="static/1/2/池.html">池</a>  <a href="static/1/2/古.html">古</a>  <a href="static/1/2/計.html">計</a>  <a href="static/1/2/前.html">前</a>  <a href="static/1/2/原.html">原</a>  <a href="static/1/2/京.html">京</a>  <a href="static/1/2/体.html">体</a>  <a href="static/1/2/線.html">線</a>  <a href="static/1/2/光.html">光</a>  <a href="static/1/2/妹.html">妹</a>  <a href="static/1/2/谷.html">谷</a>  <a href="static/1/2/近.html">近</a>  <a href="static/1/2/姉.html">姉</a>  <a href="static/1/2/西.html">西</a>  <a href="static/1/2/半.html">半</a>  <a href="static/1/2/同.html">同</a>  <a href="static/1/2/形.html">形</a>  <a href="static/1/2/遠.html">遠</a>  <a href="static/1/2/風.html">風</a>  <a href="static/1/2/場.html">場</a>  <a href="static/1/2/友.html">友</a>  <a href="static/1/2/首.html">首</a>  <a href="static/1/2/太.html">太</a>  <a href="static/1/2/方.html">方</a>  <a href="static/1/2/週.html">週</a>  <a href="static/1/2/市.html">市</a>  <a href="static/1/2/夜.html">夜</a>  <a href="static/1/2/丸.html">丸</a>

#### Kanji Stránky 161-240 3
<a href="static/1/3/話.html">話</a>  <a href="static/1/3/午.html">午</a>  <a href="static/1/3/米.html">米</a>  <a href="static/1/3/肉.html">肉</a>  <a href="static/1/3/行.html">行</a>  <a href="static/1/3/魚.html">魚</a>  <a href="static/1/3/元.html">元</a>  <a href="static/1/3/何.html">何</a>  <a href="static/1/3/楽.html">楽</a>  <a href="static/1/3/言.html">言</a>  <a href="static/1/3/汽.html">汽</a>  <a href="static/1/3/絵.html">絵</a>  <a href="static/1/3/思.html">思</a>  <a href="static/1/3/紙.html">紙</a>  <a href="static/1/3/理.html">理</a>  <a href="static/1/3/歌.html">歌</a>  <a href="static/1/3/鳴.html">鳴</a>  <a href="static/1/3/歩.html">歩</a>  <a href="static/1/3/書.html">書</a>  <a href="static/1/3/工.html">工</a>  <a href="static/1/3/戸.html">戸</a>  <a href="static/1/3/帰.html">帰</a>  <a href="static/1/3/黒.html">黒</a>  <a href="static/1/3/黄.html">黄</a>  <a href="static/1/3/家.html">家</a>  <a href="static/1/3/公.html">公</a>  <a href="static/1/3/社.html">社</a>  <a href="static/1/3/道.html">道</a>  <a href="static/1/3/読.html">読</a>  <a href="static/1/3/馬.html">馬</a>  <a href="static/1/3/羽.html">羽</a>  <a href="static/1/3/作.html">作</a>  <a href="static/1/3/茶.html">茶</a>  <a href="static/1/3/組.html">組</a>  <a href="static/1/3/寺.html">寺</a>  <a href="static/1/3/合.html">合</a>  <a href="static/1/3/室.html">室</a>  <a href="static/1/3/知.html">知</a>  <a href="static/1/3/毎.html">毎</a>  <a href="static/1/3/才.html">才</a>  <a href="static/1/3/刀.html">刀</a>  <a href="static/1/3/番.html">番</a>  <a href="static/1/3/買.html">買</a>  <a href="static/1/3/弓.html">弓</a>  <a href="static/1/3/科.html">科</a>  <a href="static/1/3/星.html">星</a>  <a href="static/1/3/語.html">語</a>  <a href="static/1/3/麦.html">麦</a>  <a href="static/1/3/色.html">色</a>  <a href="static/1/3/図.html">図</a>  <a href="static/1/3/活.html">活</a>  <a href="static/1/3/聞.html">聞</a>  <a href="static/1/3/鳥.html">鳥</a>  <a href="static/1/3/晴.html">晴</a>  <a href="static/1/3/記.html">記</a>  <a href="static/1/3/回.html">回</a>  <a href="static/1/3/通.html">通</a>  <a href="static/1/3/電.html">電</a>  <a href="static/1/3/止.html">止</a>  <a href="static/1/3/考.html">考</a>  <a href="static/1/3/牛.html">牛</a>  <a href="static/1/3/算.html">算</a>  <a href="static/1/3/門.html">門</a>  <a href="static/1/3/当.html">当</a>  <a href="static/1/3/明.html">明</a>  <a href="static/1/3/用.html">用</a>  <a href="static/1/3/船.html">船</a>  <a href="static/1/3/店.html">店</a>  <a href="static/1/3/食.html">食</a>  <a href="static/1/3/答.html">答</a>  <a href="static/1/3/来.html">来</a>  <a href="static/1/3/会.html">会</a>  <a href="static/1/3/台.html">台</a>  <a href="static/1/3/切.html">切</a>  <a href="static/1/3/教.html">教</a>  <a href="static/1/3/走.html">走</a>  <a href="static/1/3/売.html">売</a>  <a href="static/1/3/画.html">画</a>  <a href="static/1/3/声.html">声</a>

#### Kanji Stránky 241-320 4
<a href="static/1/4/悪.html">悪</a>  <a href="static/1/4/他.html">他</a>  <a href="static/1/4/品.html">品</a>  <a href="static/1/4/客.html">客</a>  <a href="static/1/4/使.html">使</a>  <a href="static/1/4/係.html">係</a>  <a href="static/1/4/乗.html">乗</a>  <a href="static/1/4/寒.html">寒</a>  <a href="static/1/4/問.html">問</a>  <a href="static/1/4/倍.html">倍</a>  <a href="static/1/4/局.html">局</a>  <a href="static/1/4/丁.html">丁</a>  <a href="static/1/4/和.html">和</a>  <a href="static/1/4/動.html">動</a>  <a href="static/1/4/始.html">始</a>  <a href="static/1/4/意.html">意</a>  <a href="static/1/4/投.html">投</a>  <a href="static/1/4/度.html">度</a>  <a href="static/1/4/員.html">員</a>  <a href="static/1/4/勝.html">勝</a>  <a href="static/1/4/事.html">事</a>  <a href="static/1/4/安.html">安</a>  <a href="static/1/4/去.html">去</a>  <a href="static/1/4/州.html">州</a>  <a href="static/1/4/世.html">世</a>  <a href="static/1/4/感.html">感</a>  <a href="static/1/4/対.html">対</a>  <a href="static/1/4/主.html">主</a>  <a href="static/1/4/区.html">区</a>  <a href="static/1/4/両.html">両</a>  <a href="static/1/4/反.html">反</a>  <a href="static/1/4/指.html">指</a>  <a href="static/1/4/勉.html">勉</a>  <a href="static/1/4/取.html">取</a>  <a href="static/1/4/商.html">商</a>  <a href="static/1/4/号.html">号</a>  <a href="static/1/4/代.html">代</a>  <a href="static/1/4/列.html">列</a>  <a href="static/1/4/所.html">所</a>  <a href="static/1/4/放.html">放</a>  <a href="static/1/4/具.html">具</a>  <a href="static/1/4/式.html">式</a>  <a href="static/1/4/急.html">急</a>  <a href="static/1/4/想.html">想</a>  <a href="static/1/4/仕.html">仕</a>  <a href="static/1/4/味.html">味</a>  <a href="static/1/4/医.html">医</a>  <a href="static/1/4/予.html">予</a>  <a href="static/1/4/幸.html">幸</a>  <a href="static/1/4/受.html">受</a>  <a href="static/1/4/実.html">実</a>  <a href="static/1/4/待.html">待</a>  <a href="static/1/4/君.html">君</a>  <a href="static/1/4/向.html">向</a>  <a href="static/1/4/全.html">全</a>  <a href="static/1/4/定.html">定</a>  <a href="static/1/4/平.html">平</a>  <a href="static/1/4/打.html">打</a>  <a href="static/1/4/助.html">助</a>  <a href="static/1/4/宿.html">宿</a>  <a href="static/1/4/写.html">写</a>  <a href="static/1/4/屋.html">屋</a>  <a href="static/1/4/島.html">島</a>  <a href="static/1/4/坂.html">坂</a>  <a href="static/1/4/持.html">持</a>  <a href="static/1/4/央.html">央</a>  <a href="static/1/4/悲.html">悲</a>  <a href="static/1/4/住.html">住</a>  <a href="static/1/4/化.html">化</a>  <a href="static/1/4/命.html">命</a>

### Datové Balíčky
Slouží pro import do dalších aplikací, například [Lively Wallpaper](https://github.com/KanjiBase/LivelyKanji).
 - <a href="static/1/2/81-160.json">81-160</a>

 - <a href="static/1/3/161-240.json">161-240</a>

 - <a href="static/1/4/241-320.json">241-320</a>





## Kanji Book: Japonské písmo (Japanistika MUNI)
Pořadí znaků dle BKB (Basic Kanji Book), dělené na sady dle průběhu kurzu Japanistiky na MUNI.
### PDF Materiály
PDF Soubory obsahují seznam znaků kanji a přidružených slovíček.
 - <a href="static/2/1/Písmo IV - Týden 1.pdf">Písmo IV - Týden 1</a>

 - <a href="static/2/2/Písmo IV - Týden 2.pdf">Písmo IV - Týden 2</a>

 - <a href="static/2/3/Písmo IV - Týden 3.pdf">Písmo IV - Týden 3</a>

 - <a href="static/2/6/Písmo IV - Týden 6.pdf">Písmo IV - Týden 6</a>


### ANKI Balíčky
Balíčky lze importovat opakovaně do ANKI aplikace. Balíčky se řadí do kolekce 'KanTanJi' 
a umožňují chytré a interaktivní procvičování kanji. Balíček obsahuje jak kanji (poznáš podle
toho, že karta otázky obsahuje link na KanjiAlive), tak slovní zásobu ke kanji.
Furiganu zobrazíš kliknutím / tapnutím na kartičku.

 - <a href="static/2/1/Písmo_IV_-_Týden_1.apkg">Písmo_IV_-_Týden_1</a>

 - <a href="static/2/2/Písmo_IV_-_Týden_2.apkg">Písmo_IV_-_Týden_2</a>

 - <a href="static/2/3/Písmo_IV_-_Týden_3.apkg">Písmo_IV_-_Týden_3</a>

 - <a href="static/2/6/Písmo_IV_-_Týden_6.apkg">Písmo_IV_-_Týden_6</a>


### HTML
HTML Stránky slouží pro vložení interaktivních informací o Kanji do externích webových služeb.

#### Kanji Stránky Písmo IV - Týden 1 1
<a href="static/2/1/辞.html">辞</a>  <a href="static/2/1/誌.html">誌</a>  <a href="static/2/1/紙.html">紙</a>  <a href="static/2/1/器.html">器</a>  <a href="static/2/1/願.html">願</a>  <a href="static/2/1/求.html">求</a>  <a href="static/2/1/知.html">知</a>  <a href="static/2/1/窓.html">窓</a>  <a href="static/2/1/取.html">取</a>  <a href="static/2/1/具.html">具</a>  <a href="static/2/1/服.html">服</a>  <a href="static/2/1/雑.html">雑</a>  <a href="static/2/1/用.html">用</a>  <a href="static/2/1/台.html">台</a>

#### Kanji Stránky Písmo IV - Týden 2 2
<a href="static/2/2/覚.html">覚</a>  <a href="static/2/2/心.html">心</a>  <a href="static/2/2/品.html">品</a>  <a href="static/2/2/忘.html">忘</a>  <a href="static/2/2/告.html">告</a>  <a href="static/2/2/泣.html">泣</a>  <a href="static/2/2/報.html">報</a>  <a href="static/2/2/頭.html">頭</a>  <a href="static/2/2/産.html">産</a>  <a href="static/2/2/資.html">資</a>  <a href="static/2/2/銀.html">銀</a>  <a href="static/2/2/感.html">感</a>  <a href="static/2/2/価.html">価</a>  <a href="static/2/2/笑.html">笑</a>  <a href="static/2/2/々.html">々</a>  <a href="static/2/2/考.html">考</a>  <a href="static/2/2/期.html">期</a>  <a href="static/2/2/個.html">個</a>  <a href="static/2/2/情.html">情</a>  <a href="static/2/2/悲.html">悲</a>

#### Kanji Stránky Písmo IV - Týden 3 3
<a href="static/2/3/苦.html">苦</a>  <a href="static/2/3/集.html">集</a>  <a href="static/2/3/曲.html">曲</a>  <a href="static/2/3/別.html">別</a>  <a href="static/2/3/並.html">並</a>  <a href="static/2/3/簡.html">簡</a>  <a href="static/2/3/驚.html">驚</a>  <a href="static/2/3/単.html">単</a>  <a href="static/2/3/脱.html">脱</a>  <a href="static/2/3/弱.html">弱</a>  <a href="static/2/3/重.html">重</a>  <a href="static/2/3/細.html">細</a>  <a href="static/2/3/軽.html">軽</a>  <a href="static/2/3/代.html">代</a>  <a href="static/2/3/眠.html">眠</a>  <a href="static/2/3/伝.html">伝</a>  <a href="static/2/3/喜.html">喜</a>  <a href="static/2/3/呼.html">呼</a>  <a href="static/2/3/焼.html">焼</a>  <a href="static/2/3/太.html">太</a>  <a href="static/2/3/狭.html">狭</a>

#### Kanji Stránky Písmo IV - Týden 6 6
<a href="static/2/6/共.html">共</a>  <a href="static/2/6/移.html">移</a>  <a href="static/2/6/賛.html">賛</a>  <a href="static/2/6/比.html">比</a>  <a href="static/2/6/加.html">加</a>  <a href="static/2/6/美.html">美</a>  <a href="static/2/6/増.html">増</a>  <a href="static/2/6/変.html">変</a>  <a href="static/2/6/減.html">減</a>  <a href="static/2/6/続.html">続</a>  <a href="static/2/6/以.html">以</a>  <a href="static/2/6/現.html">現</a>  <a href="static/2/6/直.html">直</a>  <a href="static/2/6/対.html">対</a>  <a href="static/2/6/初.html">初</a>  <a href="static/2/6/反.html">反</a>  <a href="static/2/6/進.html">進</a>  <a href="static/2/6/較.html">較</a>  <a href="static/2/6/過.html">過</a>  <a href="static/2/6/表.html">表</a>

### Datové Balíčky
Slouží pro import do dalších aplikací, například [Lively Wallpaper](https://github.com/KanjiBase/LivelyKanji).
 - <a href="static/2/1/Písmo_IV_-_Týden_1.json">Písmo_IV_-_Týden_1</a>

 - <a href="static/2/2/Písmo_IV_-_Týden_2.json">Písmo_IV_-_Týden_2</a>

 - <a href="static/2/3/Písmo_IV_-_Týden_3.json">Písmo_IV_-_Týden_3</a>

 - <a href="static/2/6/Písmo_IV_-_Týden_6.json">Písmo_IV_-_Týden_6</a>





## Neoborová Japonština
Učte se pořadí kanji, jaký používá školní systém v Japonsku. Pořadí preferuje jednoduché znaky, může tak představovat časté a užitečné (ale složité) znaky později.
### PDF Materiály
PDF Soubory obsahují seznam znaků kanji a přidružených slovíček.


### ANKI Balíčky
Balíčky lze importovat opakovaně do ANKI aplikace. Balíčky se řadí do kolekce 'KanTanJi' 
a umožňují chytré a interaktivní procvičování kanji. Balíček obsahuje jak kanji (poznáš podle
toho, že karta otázky obsahuje link na KanjiAlive), tak slovní zásobu ke kanji.
Furiganu zobrazíš kliknutím / tapnutím na kartičku.



### HTML
HTML Stránky slouží pro vložení interaktivních informací o Kanji do externích webových služeb.


### Datové Balíčky
Slouží pro import do dalších aplikací, například [Lively Wallpaper](https://github.com/KanjiBase/LivelyKanji).

