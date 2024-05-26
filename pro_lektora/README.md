# Informace pro lektora akademie

Tento dokument popisuje obsah a zamýšlenou výuku akademie. Neobsahuje žádné vyloženě tajné informace, které by
účastníci kurzu nesměli vědět, ale pokud toto čteš právě jako účastník, je možné, že se zbytečně připravíš o řadu
doplňujících informací, které v rámci výuky právě lektor dodá. :-)

## Struktura akademie

Akademie se aktuálně skládá z pěti lekcí:

1. _HTML 1._ Úvodní představení základní struktury HTML dokumentů.
1. _CSS 1._ Úvodní představení stylování.
1. _HTML 2._ Návrat k HTML a představení další sady elementů.
1. _CSS 2._ Návrat k CSS a ukázka mírně pokročilejších vlastností.
1. _Projekt._ Samostatná práce účastníků.

Přeskakování od HTML k CSS tam a zpátky může působit zvláštně, ale není zvoleno náhodně. Jakkoliv by bylo možné dát obě
povídání o HTML za sebou, aby lépe navazovala, druhá hodina nijak nestylovaného HTML by působila vizuálně dost
nezáživně. Proto je jí předřazeno první povídání o CSS, kde se naberou znalosti aspoň základních úprav vzhledu.

## Použité ukázky a jejich předpokládané využití

Ukázky pro tuto akademii (tedy především soubory _index.html_ a _styles.css_) jsou poněkud specifické, a to v tom, že
použité texty jsou do určité míry samopopisné. Ne snad v tom smyslu, že by mohly působit jako samostatný výukový text,
ale zároveň platí, že velká část vlastností je demonstrována na textech, které dané vlastnosti zároveň stručně
připomínají.

Myšlenka je taková, že lektor na začátku první lekce vytvoří v kořenovém adresáři repository (tj. adresáři o jeden
nadřazeném tomuto) prázdný soubor _index.html_ (a na začátku druhé lekce prázdný soubor _styles.css_) a postupně jej
plní ukázkami odpovídajícími obsahu _index.html_ (a _styles.css_) v tomto adresáři. Ty ukázky pochopitelně nemusejí být
shodné doslova, to by ani nebylo možné, ale svojí myšlenkou by se měly těm zde přítomným podobat.

Předpokládá se, že po skončení lekce vyučující vždy do své repository přidá aktuální obsah tvořených _index.html_ a
_styles.css_, ať už svůj vlastní, nebo klidně právě zkopírovaný ze souborů v tomto adresáři, a tento obsah následně
účastníkům zpřístupní. Jinými slovy po skončení všech lekcí by budované soubory měly mít obsah obdobný jako soubory v
tomto adresáři (případně zcela stejný).

## Popis lekcí

### HTML 1

Jak už bylo zmíněno, v této lekci se vytvoří (v adresáři nadřazeném tomuto) nový soubor _index.html_, který se postupně
plní, a to ukázkami odpovídajícími první části souboru _index.html_ v tomto adresáři.

Před lekcí je potřeba vzít adresář _podklady_ a ten účastníkům poskytnout v zazipované podobě přes Google Drive
(neočekáváme u nich větší znalost ani Gitu, ani GitHubu). V okamžiku výkladu o odkazech (a konkrétně o relativních
odkazech na jinou stránku téhož webu) budou tyto podklady využity. Lektor ještě ukáže, jak vytvořit na začátku znovu
prázdný soubor _povidani_o_pejskovi_a_kocicce/obsah.html_ (a jak na něj udělat odkaz z _index.html_), ale pak už
nastává první větší samostatná práce účastníků. Jejich úkolem je vzít texty jednotlivých povídek a vytvořit pro ně
samostatné HTML soubory (ne nezbytně pro všechny, alespoň pro pár). Zároveň přidat odkazy na jednotlivé povídky do
souboru _povidani_o_pejskovi_a_kocicce/obsah.html_ (a naopak zpětné odkazy z povídek zpět na obsah). Jak by výsledek
mohl vypadat, je vidět právě zde v souboru _povidani_o_pejskovi_a_kocicce/obsah.html_.

_Domácí úkol:_ dokončení výše zmíněného cvičení tak, aby v jednotlivých HTML souborech byly všechny povídky a soubor
_povidani_o_pejskovi_a_kocicce/obsah.html_ sloužil jako jednoduchý rozcestník. Není potřeba, aby účastnici tento úkol
dokončili před druhou lekcí, ale bylo by dobré, aby jej měli zpracován před třetí lekcí.

### CSS 1

V rámci lekce se pokračuje v budování souboru _index.html_ (v nadřazeném adresáři), a to opět ukázkami odpovídajícími
patřičné části souboru _index.html_ v tomto adresáři. Pochopitelně zároveň vznikne (v nadřazeném adresáři) i soubor
_styles.css_.

V této lekci jsou představeny jenom ty zcela nejjednodušší selektory, a tedy ukázky pravidel pro selektory jako `h2`
nebo `p` mají tendenci ovlivnit zobrazení celého dokumentu. Proto ukázky v souboru _styles.css_ odpovídající této lekci
hodně používají selektory přes atribut `id`, aby bylo možné snadno předvést jednu izolovanou vlastnost. V rámci výkladu
lekce není potřeba postupovat tímto způsobem, jenom je potřeba počítat s tím, že některé ukázky mohou mít dost neblahý
vliv na vzhled celého dokumentu.

Během lekce je vhodné představit vývojářské nástroje, a to jak z hlediska zobrazení DOMu (není potřeba zabíhat do
detailů, stačí předvést, že pro náš dokument prohlížeč zobrazí v podstatě přesně to, co jsme do HTML souboru napsali),
tak z hlediska CSS pravidel aplikovaných na jednotlivé elementy.

Konkrétní domácí úkol z této lekce aktuálně neexistuje. Neformální doporučení zní doma samostatně experimentovat s
představenými vlastnostmi (například zkusit si i další jejich hodnoty, o kterých nebyla řeč) a především si pohrát s
box modelem, čili vlastnostmi _margin_, _border_, _padding_, _width_ a _height_. (V budoucnu můžeme vymyslet i
konkrétnější zadání.)

### HTML 2

V rámci lekce se pokračuje v budování souboru _index.html_ (v nadřazeném adresáři), a to opět ukázkami odpovídajícími
patřičné části souboru _index.html_ v tomto adresáři.

Velkou součástí je samostatná práce poté, co jsou představeny elementy jako `main`, `nav`, `aside` a podobné. Cílem je
připravit si (zatím tedy pouze z pohledu HTML) půdu pro závěrečný projekt v páté lekci. Výchozím bodem řešení domácího
úkolu z první lekce. Účastníci by tedy měli mít soubor _povidani_o_pejskovi_a_kocicce/obsah.html_ obsahující jednoduchý
odrážkový seznam odkazů na jednotlivé povídky. Nyní je úkolem přetvořit jej ve stránku představující úvodní stránku
fiktivních novin (jejichž jednotlivými články jsou právě ony povídky). Jak by mohl výsledek zhruba vypadat, je k vidění
v souboru _noviny/index.html_, ovšem s následujícími poznámkami (jelikož ten soubor obsahuje celkové řešení, tedy i
věci, které se do něj přidávají v páté lekci):

- Neočekává se žádné stylování. Cílem je skutečně pouze stvořit samotnou HTML strukturu úvodní stránky novin.
  Pochopitelně to neznamená, že by účastníci měli zakázáno si nějaké styly vytvořit, ale není to obsahem tohoto cvičení
  (a rozhodně by tím neměli trávit mnoho času).
- Soubor _noviny/index.html_ obsahuje na některých místech `div`y, jejichž potřeba přichází právě až z hlediska
  výsledného stylování. V rámci toho cvičení by tam tedy tyto `div`y ještě vzniknout neměly.
- Nedá se očekávat, že by všichni účastníci velmi rychle dokázali dát dohromady takovouto strukturu pro odkazy na všech
  deset článků (povídek). Určitě nemá smysl čekat, až to všichni budou mít, to by se už na hodině nic dalšího nestihlo.
  Bylo by dobré, aby všichni (většina) měli zpracovánu strukturu pro odkazy na dva až tři články (s tím, že ti
  rychlejší toho budou mít víc).
- Pokud by se někdo z účastníků vyloženě nudil, může si o společnou navigaci rozšířit i jednotlivé články. Idea je opět
  k vidění v adresáři _noviny_.

_Domácí úkol:_ dokončení výše zmíněného cvičení. Není potřeba, aby účastníci tento úkol dokončili před čtvrtou lekcí,
ale bylo by dobré, aby jej měli zpracován před pátou lekcí.

### CSS 2

V rámci lekce se pokračuje v budování souborů _index.html_ a _styles.css_ (v nadřazeném adresáři), a to opět ukázkami
odpovídajícími patřičným částem souborů _index.html_ a _styles.css_ v tomto adresáři.

Popis použití webových fontů začíná obecnou ukázkou toho, jak tu funguje, aby to nevypadalo jako přílišná magie,
nicméně konkrétní ukázka následně spočívá v předvedení služby Google Fonts a využití jednoho takto poskytovaného písma.
Rovněž je vhodné v tomto místě pohovořit o licencích při používání děl třetích stran (ať už jsou to fonty, obrázky
nebo cokoliv jiného).

Mezi ukázkami pozicování je je hodnota `sticky` použita jako jedna z mála cíleně tak, že ovlivňuje chování celého
dokumentu (konkrétně všech nadpisů `h2`), protože to docela dobře demonstruje situaci, kdy tato vlastnost není
nastavena jedinému elementu na stránce (což jinak bývá časté).

U media queries a použití `max-width` je záměrně použita poněkud fiktivní ukázka, aby důraz zůstal na samotném
principu a aby pozornost okamžitě neutíkala k tomu, jaké se v kterém roce považují ty správné maximální rozměry v
pixelech pro mobily, jaké pro tablety a podobně.

Složitá situace je kolem flexboxu a gridu. Ať jsem nad tím přemýšlel jakkoliv, dospěl jsem k závěru, že žádný vlastní výklad, který bych k tomu zvolil, by nebyl lepší než povídání ve článcích z materiálů odkázaných. Nakonec jsem se tedy rozhodl použít právě ty a základní prvky flexboxu a gridu popsat s jejich použitím.

Kromě ukázky stylování odrážkového seznamu pomocí flexboxu jsem ještě hledal příklad, kde bych naprosto stejného
vzhledu dosáhl jednou flexboxem a podruhé gridem. Napadla mě jednoduchá galerie, ale v detailech se ukázalo, že ten
efekt nakonec není takový, jaký bych si představoval. Například ta flexboxová varianta nakonec stojí na tom, že počet
použitých obrázků je přesně dělitelný počtem sloupců (a při jiném počtu obrázků nebude tak dobře fungovat). Bylo by
tedy do budoucna ideální tuhle ukázku buďto vylepšit, nebo najít jiný příklad, než je galerie, na kterém by se dalo
dobře demonstrovat to, jak téhož dosáhnout flexboxem i gridem a kde jsou tam rozdíly.

V průběhu lekce je vhodné občas připomenout a ukazovat vývojářské nástroje (hlavně z pohledu stylování).

### Projekt

Obsahem této lekce je už pouze samostatná práce účastníků. Ideální situace je ta, kdy účastníci vyjdou ze svého vlastního obsahu adresáře _povidani_o_pejskovi_a_kocicce_ tvořeného na třetí lekci, který před touto pátou lekcí dotáhli za domácí úkol. Doporučuji, aby si jeho obsah zkopírovali do nového adresáře, _noviny_, a práci této lekce dělali v něm. Je ale potřeba připravit se i na situaci, kdy část účastníků nebude mít tento výchozí bod v dostatečně použitelném stavu.

Je vhodné tedy vzít očekávaný výsledek, který se nachází zde v adresáři _noviny_, odstranit z něj obsah stylů (ale se
zachováním samotných souborů pro styly), ze souboru _noviny/index.html_ odstranit všechny `div`y potřebné čistě kvůli
právě stylování (účastníci by v rámci cvičení měli přijít na to, že tam někde nějaké `div`y navíc potřebovat budou) a
výsledek poskytnout v zazipované podobě přes Google Drive pro ty účastníky, kteří budou chtít vyjít spíš z něj než ze
svých vlastních předchozích řešení.

## Poznámky

- Jakkoliv účastnicím v rámci této akademie Prettier neukazujeme, veškeré ukázkové HTML a CSS soubory jsou jím
  formátovány. To v řadě míst vede k poněkud jinému formátování, než bych si třeba sám představoval, ale na druhou
  stranu je to jediný rozumný způsob, jak zajistit nějakou celkovou konzistenci.
