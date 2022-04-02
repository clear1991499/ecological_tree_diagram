```mermaid
graph LR

classDef rank fill:#0000cc, color:#eeeeee
classDef research fill:#cc5555, color:#eeeeee
classDef new fill:#5555cc, color:#eeeeee
classDef hide fill:#666666, color:#eeeeee
classDef _order fill:#cc0000, color:#eeeeee

Or---subOr---iOr---supFa---Fa---Ge---Sp

Or["目"]:::rank
subOr["亜目"]:::rank
iOr["下目"]:::rank
supFa["上科"]:::rank
Fa["科"]:::rank
Ge["属"]:::rank
Sp["種"]:::rank

a---aa---aaa---aaaa---aaaaa---aaaaaa---aaaaaaa
    aa---aab---aaba---aabaa---aabaaa---aabaaaa
a---ab---aba---abaa---abaaa---abaaaa---abaaaaa
    ab---abb---abba---abbaa---abbaaa---abbaaaa
a---ac---aca---acaa---acaaa---acaaaa---acaaaaa
a---ad---ada---adaa---adaaa---adaaaa---adaaaaa
a---ae---aea---aeaa---aeaaa---aeaaaa---aeaaaaa
    ae---aeb---aeba---aebaa---aebaaa---aebaaaa
a---af---afa---afaa---afaaa---afaaaa---afaaaaa
a---ag---aga---agaa---agaaa---agaaaa---agaaaaa
a---ah---aha---ahaa---ahaaa---ahaaaa---ahaaaaa
a---ai---aia---aiaa---aiaaa---aiaaaa---aiaaaaa
a---aj---aja---ajaa---ajaaa---ajaaaa---ajaaaaa
    aj---ajb---ajba---ajbaa---ajbaaa---ajbaaaa
a---ak---aka---akaa---akaaa---akaaaa---akaaaaa
a---al---ala---alaa---alaaa---alaaaa---alaaaaa
a---am---ama---amaa---amaaa---amaaaa---amaaaaa
a---an---ana---anaa---anaaa---anaaaa---anaaaaa
a---ao---aoa---aoaa---aoaaa---aoaaaa---aoaaaaa
a---ap---apa---apaa---apaaa---apaaaa---apaaaaa
a---aq---aqa---aqaa---aqaaa---aqaaaa---aqaaaaa
a---ar---ara---araa---araaa---araaaa---araaaaa
a---as---asa---asaa---asaaa---asaaaa---asaaaaa
a---at---ata---ataa---ataaa---ataaaa---ataaaaa
a---au---aua---auaa---auaaa---auaaaa---auaaaaa
a---av---ava---avaa---avaaa---avaaaa---avaaaaa
a---aw---awa---awaa---awaaa---awaaaa---awaaaaa

b---ba---baa---baaa---baaaa---baaaaa---baaaaaa
b---bb---bba---bbaa---bbaaa---bbaaaa---bbaaaaa

Primates["霊長目"]:::_order
Primates---Haplorrhini[" "]---Simiiformes[" "]---Hominoidea[" "]---Hominidae["ヒト科"]---Homo[" "]---H._sapiens["ホモサピエンス"]

c---ca---caa---caaa---caaaa---caaaaa---caaaaaa
         caa---caab---caaba---caabaa---caabaaa
         caa---caac---caaca---caacaa---caacaaa
c---cb---cba---cbaa---cbaaa---cbaaaa---cbaaaaa
    cb---cbb---cbba---cbbaa---cbbaaa---cbbaaaa
    cb---cbc---cbca---cbcaa---cbcaaa---cbcaaaa
    cb---cbd---cbda---cbdaa---cbdaaa---cbdaaaa
    cb---cbe---cbea---cbeaa---cbeaaa---cbeaaaa
    cb---cbf---cbfa---cbfaa---cbfaaa---cbfaaaa
c---cc---cca---ccaa---ccaaa---ccaaaa---ccaaaaa
    cc---ccb---ccba---ccbaa---ccbaaa---ccbaaaa

d---da---daa---daaa---daaaa---daaaaa---daaaaaa
d---db---dba---dbaa---dbaaa---dbaaaa---dbaaaaa

e---ea---eaa---eaaa---eaaaa---eaaaaa---eaaaaaa
e---eb---eba---ebaa---ebaaa---ebaaaa---ebaaaaa
e---ec---eca---ecaa---ecaaa---ecaaaa---ecaaaaa
e---ed---eda---edaa---edaaa---edaaaa---edaaaaa
e---ee---eea---eeaa---eeaaa---eeaaaa---eeaaaaa

Perissodactyla["奇蹄目"]:::_order
Perissodactyla---Hippomorpha[" "]---iOr_Hippomorpha[" "]---Equoidea[" "]---Equidae["ウマ科"]---Equus[" "]---E._caballus["ウマ"]:::research
Hippomorpha---iOr_Ramarada[" "]---supFa_Ramarada[" "]---Fa_Ramarada["ラマラダ科"]---Ge_Ramarada[" "]---Ramarada["ラマラダ"]:::research

f---fa---faa---faaa---faaaa---faaaaa---faaaaaa
         faa---faab---faaba---faabaa---faabaaa
f---fb---fba---fbaa---fbaaa---fbaaaa---fbaaaaa
    fb---fbb---fbba---fbbaa---fbbaaa---fbbaaaa
    fb---fbc---fbca---fbcaa---fbcaaa---fbcaaaa
         fbc---fbcb---fbcba---fbcbaa---fbcbaaa
    fb---fbd---fbda---fbdaa---fbdaaa---fbdaaaa
    fb---fbe---fbea---fbeaa---fbeaaa---fbeaaaa
    fb---fbf---fbfa---fbfaa---fbfaaa---fbfaaaa
    fb---fbg---fbga---fbgaa---fbgaaa---fbgaaaa
    fb---fbh---fbha---fbhaa---fbhaaa---fbhaaaa
         fbh---fbhb---fbhba---fbhbaa---fbhbaaa
    fb---fbi---fbia---fbiaa---fbiaaa---fbiaaaa
               fbia---fbiab---fbiaba---fbiabaa
    fb---fbj---fbja---fbjaa---fbjaaa---fbjaaaa

f---fc---fca---fcaa---fcaaa---fcaaaa---fcaaaaa
               fcaa---fcaab---fcaaba---fcaabaa
         fca---fcab---fcaba---fcabaa---fcabaaa
         fca---fcac---fcaca---fcacaa---fcacaaa
         fca---fcad---fcada---fcadaa---fcadaaa
         fca---fcae---fcaea---fcaeaa---fcaeaaa
         fca---fcaf---fcafa---fcafaa---fcafaaa
         fca---fcag---fcaga---fcagaa---fcagaaa
    fc---fcb---fcba---fcbaa---fcbaaa---fcbaaaa
    fc---fcc---fcca---fccaa---fccaaa---fccaaaa
                      fccaa---fccaab---fccaaba
         fcc---fccb---fccba---fccbaa---fccbaaa
               fccb---fccbb---fccbba---fccbbaa
               fccb---fccbc---fccbca---fccbcaa
         fcc---fccc---fccca---fcccaa---fcccaaa
               fccc---fcccb---fcccba---fcccbaa
               fccc---fcccc---fcccca---fccccaa
               fccc---fcccd---fcccda---fcccdaa
               fccc---fccce---fcccea---fccceaa

f---fd---fda---fdaa---fdaaa---fdaaaa---fdaaaaa
    fd---fdb---fdba---fdbaa---fdbaaa---fdbaaaa
    fd---fdc---fdca---fdcaa---fdcaaa---fdcaaaa
         fdc---fdcb---fdcba---fdcbaa---fdcbaaa
    fd---fdd---fdda---fddaa---fddaaa---fddaaaa
         fdd---fddb---fddba---fddbaa---fddbaaa
               fddb---fddbb---fddbba---fddbbaa
    fd---fde---fdea---fdeaa---fdeaaa---fdeaaaa
    fd---fdf---fdfa---fdfaa---fdfaaa---fdfaaaa
    fd---fdg---fdga---fdgaa---fdgaaa---fdgaaaa
f---fe---fea---feaa---feaaa---feaaaa---feaaaaa
    fe---feb---feba---febaa---febaaa---febaaaa
                      febaa---febaab---febaaba
                      febaa---febaac---febaaca
               feba---febab---febaba---febabaa
    fe---fec---feca---fecaa---fecaaa---fecaaaa
               feca---fecab---fecaba---fecabaa
               feca---fecac---fecaca---fecacaa
    fe---fed---feda---fedaa---fedaaa---fedaaaa
f---ff---ffa---ffaa---ffaaa---ffaaaa---ffaaaaa

g---ga---gaa---gaaa---gaaaa---gaaaaa---gaaaaaa
                      gaaaa---gaaaab---gaaaaba
                      gaaaa---gaaaac---gaaaaca
                      gaaaa---gaaaad---gaaaada
                      gaaaa---gaaaae---gaaaaea

h---ha---haa---haaa---haaaa---haaaaa---haaaaaa
h---hb---hba---hbaa---hbaaa---hbaaaa---hbaaaaa

i---ia---iaa---iaaa---iaaaa---iaaaaa---iaaaaaa
    ia---iab---iaba---iabaa---iabaaa---iabaaaa
    ia---iac---iaca---iacaa---iacaaa---iacaaaa
    ia---iad---iada---iadaa---iadaaa---iadaaaa
i---ib---iba---ibaa---ibaaa---ibaaaa---ibaaaaa
    ib---ibb---ibba---ibbaa---ibbaaa---ibbaaaa
i---ic---ica---icaa---icaaa---icaaaa---icaaaaa
i---|不明|id---ida---idaa---idaaa---idaaaa---idaaaaa
    id---idb---idba---idbaa---idbaaa---idbaaaa

j---ja---jaa---jaaa---jaaaa---jaaaaa---jaaaaaa
               jaaa---jaaab---jaaaba---jaaabaa
         jaa---jaab---jaaba---jaabaa---jaabaaa
j---jb---jba---jbaa---jbaaa---jbaaaa---jbaaaaa

k---ka---kaa---kaaa---kaaaa---kaaaaa---kaaaaaa
k---kb---kba---kbaa---kbaaa---kbaaaa---kbaaaaa
k---kc---kca---kcaa---kcaaa---kcaaaa---kcaaaaa
    kc---kcb---kcba---kcbaa---kcbaaa---kcbaaaa
    kc---kcc---kcca---kccaa---kccaaa---kccaaaa
    kc---kcd---kcda---kcdaa---kcdaaa---kcdaaaa
    kc---kce---kcea---kceaa---kceaaa---kceaaaa
k---kd---kda---kdaa---kdaaa---kdaaaa---kdaaaaa
k---ke---kea---keaa---keaaa---keaaaa---keaaaaa

l---la---laa---laaa---laaaa---laaaaa---laaaaaa
l---lb---lba---lbaa---lbaaa---lbaaaa---lbaaaaa

m---ma---maa---maaa---maaaa---maaaaa---maaaaaa
    ma---mab---maba---mabaa---mabaaa---mabaaaa
m---mb---mba---mbaa---mbaaa---mbaaaa---mbaaaaa
    mb---mbb---mbba---mbbaa---mbbaaa---mbbaaaa
m---mc---mca---mcaa---mcaaa---mcaaaa---mcaaaaa
         mca---mcab---mcaba---mcabaa---mcabaaa

n---n_---n__---n___---n____---n_____---n______
n---na---naa---naaa---naaaa---naaaaa---naaaaaa
n---nb---nba---nbaa---nbaaa---nbaaaa---nbaaaaa
n---nc---nca---ncaa---ncaaa---ncaaaa---ncaaaaa

o --- oa --- oaa --- oaaa --- oaaaa --- oaaaaa --- oaaaaaa
o --- ob --- oba --- obaa --- obaaa --- obaaaa --- obaaaaa

p---pa---paa---paaa---paaaa---paaaaa---paaaaaa
p---pb---pba---pbaa---pbaaa---pbaaaa---pbaaaaa
p---pc---pca---pcaa---pcaaa---pcaaaa---pcaaaaa

q---qa---qaa---qaaa---qaaaa---qaaaaa---qaaaaaa
         qaa---qaab---qaaba---qaabaa---qaabaaa
q---qb---qba---qbaa---qbaaa---qbaaaa---qbaaaaa

%% ------------------------------ 古龍目 ------------------------------

a["古龍目"]:::_order

aa["源龍亜目"]
aaa[" "]
aaaa[" "]
aaaaa["ミラオス科"]
aaaaaa[" "]
aaaaaaa["グラン・ミラオス"]
aab[" "]
aaba[" "]
aabaa["ミラボレアス科"]
aabaaa[" "]
aabaaaa["ミラボレアス"]

ab["山龍亜目"]
aba[" "]
abaa[" "]
abaaa["ラオシャンロン科"]
abaaaa[" "]
abaaaaa["ラオシャンロン"]
abb["熔龍下目"]
abba[" "]
abbaa["ゾラ科"]
abbaaa[" "]
abbaaaa["ゾラ・マグダラオス"]

ac["鋼龍亜目"]
aca[" "]
acaa[" "]
acaaa["クシャナ科"]
acaaaa[" "]
acaaaaa["クシャルダオラ"]

ad["炎龍亜目"]
ada[" "]
adaa[" "]
adaaa["テスカト科"]
adaaaa[" "]
adaaaaa["テオ・テスカトル / ナナ・テスカトリ"]

ae["不明"]
aea["霞龍下目"]
aeaa[" "]
aeaaa["ナズチ科"]
aeaaaa[" "]
aeaaaaa["オオナズチ"]
aeb["溟龍下目"]
aeba[" "]
aebaa["ネロミェール科"]
aebaaa[" "]
aebaaaa["ネロミェール"]

af["岳龍亜目"]
afa[" "]
afaa[" "]
afaaa["ヤマツカミ科"]
afaaaa[" "]
afaaaaa["ヤマツカミ"]

ag["幻獣亜目"]
aga[" "]
agaa[" "]
agaaa["キリン科"]
agaaaa[" "]
agaaaaa["キリン"]

ah["深龍亜目"]
aha[" "]
ahaa[" "]
ahaaa["ナバルデウス科"]
ahaaaa[" "]
ahaaaaa["ナバルデウス"]

ai["煌龍亜目"]
aia[" "]
aiaa[" "]
aiaaa["アルバトリオン科"]
aiaaaa[" "]
aiaaaaa["アルバトリオン"]

aj["峯龍亜目"]
aja[" "]
ajaa[" "]
ajaaa["ジエン科"]
ajaaaa[" "]
ajaaaaa["ジエン・モーラン"]
ajb[" "]
ajba[" "]
ajbaa["ダレン科"]
ajbaaa[" "]
ajbaaaa["ダレン・モーラン"]

ak["嵐龍亜目"]
aka[" "]
akaa[" "]
akaaa["アマツマガツチ科"]
akaaaa[" "]
akaaaaa["アマツマガツチ"]

al["廻龍亜目"]
ala[" "]
alaa[" "]
alaaa["マガラ科"]
alaaaa[" "]
alaaaaa["シャガルマガラ / ゴア・マガラ"]

am["蛇龍亜目"]
ama[" "]
amaa[" "]
amaaa["アマデュラ科"]
amaaaa[" "]
amaaaaa["ダラ・アマデュラ"]

an["戟龍亜目"]
ana[" "]
anaa[" "]
anaaa["ゴグマ科"]
anaaaa[" "]
anaaaaa["ゴグマジオス"]

ao["骸龍亜目"]
aoa[" "]
aoaa[" "]
aoaaa["オストガロア科"]
aoaaaa[" "]
aoaaaaa["オストガロア"]

ap["滅龍亜目"]
apa[" "]
apaa[" "]
apaaa["ネルギガンテ科"]
apaaaa[" "]
apaaaaa["ネルギガンテ"]

aq["冥灯龍亜目"]
aqa[" "]
aqaa[" "]
aqaaa["ジーヴァ科"]
aqaaaa[" "]
aqaaaaa["ゼノ・ジーヴァ / ムフェト・ジーヴァ"]

ar["屍纏龍亜目"]
ara[" "]
araa[" "]
araaa["ヴァルハザク科"]
araaaa[" "]
araaaaa["ヴァルハザク"]

as["爛輝龍亜目"]
asa[" "]
asaa[" "]
asaaa["マム・タロト科"]
asaaaa[" "]
asaaaaa["マム・タロト"]

at["冰龍亜目"]
ata[" "]
ataa[" "]
ataaa["イヴェルカーナ科"]
ataaaa[" "]
ataaaaa["イヴェルカーナ"]

au["地啼龍亜目"]
aua[" "]
auaa[" "]
auaaa["アン・イシュワルダ科"]
auaaaa[" "]
auaaaaa["アン・イシュワルダ"]

av["天彗龍亜目"]
ava[" "]
avaa[" "]
avaaa["バルファルク科"]
avaaaa[" "]
avaaaaa["バルファルク"]

aw["神龍亜目"]
awa[" "]
awaa[" "]
awaaa["不明"]
awaaaa[" "]
awaaaaa["イブシマキヒコ / ナルハタタヒメ"]:::new

%% ------------------------------ 長鼻目 ------------------------------

b["長鼻目"]:::_order

ba[" "]
baa[" "]
baaa["奇鼻上科"]
baaaa["ポポ科"]
baaaaa[" "]
baaaaaa["ポポ"]
bb["頭殻亜目"]
bba[" "]
bbaa[" "]
bbaaa["ガムート科"]
bbaaaa[" "]
bbaaaaa["ガムート"]

%% ------------------------------ 尖爪目 ------------------------------

c["尖爪目"]:::_order

ca["堅歯亜目"]
caa[" "]
caaa["鋭牙上科"]
caaaa["ブランゴ科"]
caaaaa[" "]
caaaaaa["ドドブランゴ / ブランゴ"]
caab["鈍牙上科"]
caaba["コンガ科"]
caabaa[" "]
caabaaa["ババコンガ / コンガ"]
caac["不明"]
caaca["ラージャン科"]
caacaa[" "]
caacaaa["ラージャン"]

cb["堅爪亜目"]
cba["熊獣下目"]
cbaa[" "]
cbaaa["アシラ科"]
cbaaaa[" "]
cbaaaaa["アオアシラ"]
cbb["兎獣下目"]
cbba[" "]
cbbaa["クスス科"]
cbbaaa[" "]
cbbaaaa["ウルクスス"]
cbc["甲獣下目"]
cbca[" "]
cbcaa["ラングロトラ科"]
cbcaaa[" "]
cbcaaaa["ラングロトラ"]
cbd["鬼獣下目"]
cbda[" "]
cbdaa["ゴシャハギ科"]
cbdaaa[" "]
cbdaaaa["ゴシャハギ"]:::new
cbe["犬獣下目"]
cbea[" "]
cbeaa["ガルク科"]
cbeaaa[" "]
cbeaaaa["ガルク"]:::new
cbf["狸獣下目"]
cbfa[" "]
cbfaa["ブンブジナ科"]
cbfaaa[" "]
cbfaaaa["ブンブジナ"]:::new

cc["飛膜獣亜目"]
cca[" "]
ccaa[" "]
ccaaa["ケチャワチャ科"]
ccaaaa[" "]
ccaaaaa["ケチャワチャ"]
ccb["天狗獣下目"]
ccba[" "]
ccbaa["ビシュテンゴ科"]
ccbaaa[" "]
ccbaaaa["ビシュテンゴ"]:::new

%% ------------------------------ 食雑目 ------------------------------

d["食雑目"]:::_order

da[" "]
daa[" "]
daaa[" "]
daaaa["アイルー科"]
daaaaa[" "]
daaaaaa["アイルー / メラルー"]

db[" "]
dba[" "]
dbaa["不明"]
dbaaa["チャチャブー科"]
dbaaaa[" "]
dbaaaaa["キングチャチャブー / チャチャブー"]

%% ------------------------------ 偶蹄目 ------------------------------

e["偶蹄目"]:::_order

ea[" "]
eaa[" "]
eaaa[" "]
eaaaa["ケルビ科"]
eaaaaa[" "]
eaaaaaa["ケルビ"]

eb[" "]
eba[" "]
ebaa[" "]
ebaaa["ガウシカ科"]
ebaaaa[" "]
ebaaaaa["ガウシカ"]

ec[" "]
eca[" "]
ecaa[" "]
ecaaa["ムーファ科"]
ecaaaa[" "]
ecaaaaa["ムーファ"]

ed[" "]
eda[" "]
edaa[" "]
edaaa["モス科"]
edaaaa[" "]
edaaaaa["モス"]

ee[" "]
eea[" "]
eeaa[" "]
eeaaa["ブルファンゴ科"]
eeaaaa[" "]
eeaaaaa["ドスファンゴ / ブルファンゴ"]

%% ------------------------------ 竜盤目 ------------------------------

f["竜盤目"]:::_order

fa[" "]
faa["不明"]
faaa[" "]
faaaa["アカム科"]
faaaaa[" "]
faaaaaa["アカムトルム"]
faab[" "]
faaba["ウカム科"]
faabaa[" "]
faabaaa["ウカムルバス"]

subgraph レックス
fb["竜脚亜目"]
end class レックス research

fba[" "]
fbaa[" "]
fbaaa["レックス科"]
fbaaaa[" "]
fbaaaaa["ティガレックス"]

subgraph シェルレウス
fbb["甲殻竜下目"]
end
class シェルレウス research
fbba["飛竜上科"]
fbbaa["リオス科"]
fbbaaa[" "]
fbbaaaa["リオレウス / リオレイア"]

subgraph クラグモス
fbc["重殻竜下目"]
end
class クラグモス research
fbca["鎧竜上科"]
fbcaa["グラビモス科"]
fbcaaa[" "]
fbcaaaa["グラビモス / バサルモス"]
fbcb["角竜上科"]
fbcba["ブロス科"]
fbcbaa[" "]
fbcbaaa["ディアブロス / モノブロス"]

fbd["電翼竜下目"]
fbda["電竜上科"]
fbdaa["ゼクス科"]
fbdaaa[" "]
fbdaaaa["ライゼクス"]

fbe[" "]
fbea["膨頸竜上科"]
fbeaa["パオウルムー科"]
fbeaaa[" "]
fbeaaaa["パオウルムー"]

fbf[" "]
fbfa["拡翼竜上科"]
fbfaa["レイギエナ科"]
fbfaaa[" "]
fbfaaaa["レイギエナ"]

fbg[" "]
fbga["爆鱗竜上科"]
fbgaa["バゼル科"]
fbgaaa[" "]
fbgaaaa["バゼルギウス"]

fbh["奇怪竜下目"]
fbha["毒怪竜上科"]
fbhaa["ネブラ科"]
fbhaaa[" "]
fbhaaaa["ギギネブラ / ギィギ"]
fbhb["稀白竜上科"]
fbhba["フルフル科"]
fbhbaa[" "]
fbhbaaa["フルフル"]

fbi["不明"]
fbia["前翼脚竜上科"]
fbiaa["ナルガ科"]
fbiaaa[" "]
fbiaaaa["ナルガクルガ"]
fbiab["ベリオ科"]
fbiaba[" "]
fbiabaa["ベリオロス"]

fbj["刃鱗竜下目"]
fbja[" "]
fbjaa["レギオス科"]
fbjaaa[" "]
fbjaaaa["セルレギオス"]

subgraph イグルエイビス
fc["鳥脚亜目"]
end
class イグルエイビス research

subgraph ボルドル
fca["鳥竜下目"]
end
class ボルドル research

fcaa["耳鳥竜上科"]
fcaaa["クック科"]
fcaaaa[" "]
fcaaaaa["イャンクック"]
fcaab["ガルルガ科"]
fcaaba[" "]
fcaabaa["イャンガルルガ"]

fcab[" "]
fcaba["ヒプノック科"]
fcabaa[" "]
fcabaaa["ヒプノック"]

fcac[" "]
fcaca["ゲリョス科"]
fcacaa[" "]
fcacaaa["ゲリョス"]

fcad[" "]
fcada["ホロロホルル科"]
fcadaa[" "]
fcadaaa["ホロロホルル"]

fcae["声鳥竜上科"]
fcaea["ペッコ科"]
fcaeaa[" "]
fcaeaaa["クルペッコ"]

fcaf[" "]
fcafa["プケプケ科"]
fcafaa[" "]
fcafaaa["プケプケ"]

fcag[" "]
fcaga["アケノシルム科"]
fcagaa[" "]
fcagaaa["アケノシルム"]:::new

fcb["真鳥下目"]
fcba[" "]
fcbaa["丸鳥科"]
fcbaaa[" "]
fcbaaaa["ガーグァ"]

subgraph ケプトス
fcc["走竜下目"]
end
class ケプトス research

fcca[" "]
fccaa["ヤック科"]
fccaaa["クルル属"]
fccaaaa["クルルヤック"]
fccaab["ツィツィ属"]
fccaaba["ツィツィヤック"]

fccb[" "]
fccba["ランポス科"]
fccbaa[" "]
fccbaaa["ドスランポス / ランポス<br/>/ドスギアノス / ギアノス"]
fccbb["ゲネポス科"]
fccbba[" "]
fccbbaa["ドスゲネポス / ゲネポス"]
fccbc["イーオス科"]
fccbca[" "]
fccbcaa["ドスイーオス / イーオス"]

fccc["狗竜上科"]
fccca["ジャギィ科"]
fcccaa[" "]
fcccaaa["ドスジャギィ / ジャギィ<br/>/ ジャギィノス"]
fcccb["バギィ科"]
fcccba[" "]
fcccbaa["ドスバギィ / バギィ"]
fcccc["フロギィ科"]
fcccca[" "]
fccccaa["ドスフロギィ / フロギィ"]
fcccd["マッカォ科"]
fcccda[" "]
fcccdaa["ドスマッカォ / マッカォ"]
fccce["イズチ科"]
fcccea[" "]
fccceaa["オサイズチ / イズチ"]:::new

fd["獣脚亜目"]

fda["不明"]
fdaa["暴竜上科"]
fdaaa["イビル科"]
fdaaaa[" "]
fdaaaaa["イビルジョー"]

fdb[" "]
fdba[" "]
fdbaa["アンジャナフ科"]
fdbaaa[" "]
fdbaaaa["アンジャナフ"]

fdc["鎚竜下目"]
fdca["鎚顎竜上科"]
fdcaa["ガンキン科"]
fdcaaa[" "]
fdcaaaa["ウラガンキン"]
fdcb[" "]
fdcba["バルキン科"]
fdcbaa[" "]
fdcbaaa["ラドバルキン"]

fdd[" "]
fdda["尾槌竜上科"]
fddaa["ドボルベルク科"]
fddaaa[" "]
fddaaaa["ドボルベルク"]
fddb["板角竜上科"]
fddba["バフバロ科"]
fddbaa[" "]
fddbaaa["バフバロ"]
fddbb["ケストドン科"]
fddbba[" "]
fddbbaa["ケストドン"]

fde[" "]
fdea["尾剣竜上科"]
fdeaa["ディノバルド科"]
fdeaaa[" "]
fdeaaaa["ディノバルド"]

fdf[" "]
fdfa["冠頭竜上科"]
fdfaa["ボルボロス科"]
fdfaaa[" "]
fdfaaaa["ボルボロス"]

fdg[" "]
fdga["前脚拳竜上科"]
fdgaa["ブラキ科"]
fdgaaa[" "]
fdgaaaa["ブラキディオス"]

fe["四脚亜目"]

fea[" "]
feaa["雷狼竜上科"]
feaaa["ジンオウガ科"]
feaaaa[" "]
feaaaaa["ジンオウガ"]

feb[" "]
feba["賊竜上科"]
febaa["ジャグラス科"]
febaaa["ジャグラス属"]
febaaaa["ドスジャグラス / ジャグラス"]
febaab["ギルオス属"]
febaaba["ドスギルオス / ギルオス"]
febaac["シャムオス属"]
febaaca["シャムオス"]
febab["ドドガマル科"]
febaba[" "]
febabaa["ドドガマル"]

fec[" "]
feca["凄爪竜上科"]
fecaa["トビカガチ科"]
fecaaa[" "]
fecaaaa["トビカガチ"]
fecab["オドガロン科"]
fecaba[" "]
fecabaa["オドガロン"]
fecac["ウルグ科"]
fecaca[" "]
fecacaa["ウルグ"]

fed[" "]
feda["怨虎竜上科"]
fedaa["マガイマガド科"]
fedaaa[" "]
fedaaaa["マガイマガド"]:::new

ff["奇首亜目"]
ffa[" "]
ffaa["首鳴竜上科"]
ffaaa["リモセトス科"]
ffaaaa[" "]
ffaaaaa["リモセトス"]

%% ------------------------------ 翼竜目 ------------------------------

g["翼竜目"]:::_order
ga[" "]
gaa[" "]
gaaa[" "]
gaaaa["翼竜科"]
gaaaaa["メルノス属"]
gaaaaaa["メルノス"]
gaaaab["ラフィノス属"]
gaaaaba["ラフィノス"]
gaaaac["ノイオス属"]
gaaaaca["ノイオス"]
gaaaad["バルノス属"]
gaaaada["バルノス"]
gaaaae["コルトス属"]
gaaaaea["コルトス"]

%% ------------------------------ 蛇竜目 ------------------------------

h["蛇竜目"]:::_order
ha["蛇竜亜目"]
haa[" "]
haaa[" "]
haaaa["ガララアジャラ科"]
haaaaa[" "]
haaaaaa["ガララアジャラ"]
hb["翼蛇竜亜目"]
hba[" "]
hbaa[" "]
hbaaa["ガブラス科"]
hbaaaa[" "]
hbaaaaa["ガブラス"]

%% ------------------------------ 海竜目 ------------------------------

i["海竜目"]:::_order

ia["海竜亜目"]
iaa["電殻竜下目"]
iaaa[" "]
iaaaa["ラギアクルス科"]
iaaaaa[" "]
iaaaaaa["ラギアクルス"]
iab["綿毛竜下目"]
iaba[" "]
iabaa["ロアル科"]
iabaaa[" "]
iabaaaa["ロアルドロス / ルドロス"]
iac["焔竜下目"]
iaca[" "]
iacaa["アグナコトル科"]
iacaaa[" "]
iacaaaa["アグナコトル / ウロコトル"]
iad["人魚竜下目"]
iada[" "]
iadaa["イソネミクニ科"]
iadaaa[" "]
iadaaaa["イソネミクニ"]:::new

ib["底足竜亜目"]
iba["灯魚竜下目"]
ibaa[" "]
ibaaa["チャナ科"]
ibaaaa[" "]
ibaaaaa["チャナガブル"]
ibb["潜口竜下目"]
ibba[" "]
ibbaa["ハプルボッカ科"]
ibbaaa[" "]
ibbaaaa["ハプルボッカ"]

ic["首長竜亜目"]
ica[" "]
icaa[" "]
icaaa["エピオス科"]
icaaaa[" "]
icaaaaa["エピオス"]

id["海獣竜亜目"]
ida["泡狐竜下目"]
idaa[" "]
idaaa["タマミツネ科"]
idaaaa[" "]
idaaaaa["タマミツネ"]
idb["泥翁竜下目"]
idba[" "]
idbaa["オロミドロ科"]
idbaaa[" "]
idbaaaa["オロミドロ"]:::new

%% ------------------------------ 鳥盤目 ------------------------------

j["鳥盤目"]:::_order

ja["鎚尾亜目"]
jaa["地竜下目"]
jaaa[" "]
jaaaa["トノス科"]
jaaaaa[" "]
jaaaaaa["アプトノス"]
jaaab["ケロス科"]
jaaaba[" "]
jaaabaa["アプケロス"]
jaab["垂皮竜上科"]
jaaba["ロポス科"]
jaabaa[" "]
jaabaaa["ズワロポス"]

jb["周飾頭亜目"]
jba[" "]
jbaa[" "]
jbaaa["リノプロス科"]
jbaaaa[" "]
jbaaaaa["リノプロス"]

%% ------------------------------ 魚竜目 ------------------------------

k["魚竜目"]:::_order

ka["古魚亜目"]
kaa["古蛇下目"]
kaaa[" "]
kaaaa["エンシェントサーペント科"]
kaaaaa[" "]
kaaaaaa["エンシェントサーペント"]:::research

kb["陸魚亜目"]
kba[" "]
kbaa[" "]
kbaaa["デルクス科"]
kbaaaa[" "]
kbaaaaa["デルクス"]

kc["有脚魚竜亜目"]
kca[" "]
kcaa["泥魚竜上科"]
kcaaa["ジュラトドス科"]
kcaaaa[" "]
kcaaaaa["ジュラトドス"]
kcb[" "]
kcba["水竜上科"]
kcbaa["トトス科"]
kcbaaa[" "]
kcbaaaa["ガノトトス"]
kcc[" "]
kcca["砂竜上科"]
kccaa["ガレオス科"]
kccaaa[" "]
kccaaaa["ドスガレオス / ガレオス"]
kcd[" "]
kcda["溶岩竜上科"]
kcdaa["ヴォルガノス科"]
kcdaaa[" "]
kcdaaaa["ヴォルガノス"]
kce[" "]
kcea["凍魚竜上科"]
kceaa["ブラントドス科"]
kceaaa[" "]
kceaaaa["ブラントドス"]

kd["熱魚亜目"]
kda[" "]
kdaa[" "]
kdaaa["アロワナ科"]
kdaaaa[" "]
kdaaaaa["バクレツアロワナ / ハレツアロワナ"]:::hide

ke["核魚亜目"]
kea[" "]
keaa[" "]
keaaa["デメキン科"]
keaaaa[" "]
keaaaaa["バクサンデメキン / カクサンデメキン"]:::hide

%% ------------------------------ 古虫目 ------------------------------

l["古虫目"]:::_order
la[" "]
laa[" "]
laaa[" "]
laaaa["フシチュウ科"]
laaaaa[" "]
laaaaaa["不死虫"]:::hide
lb["閃虫亜目"]
lba[" "]
lbaa[" "]
lbaaa["ヒカリムシ科"]
lbaaaa[" "]
lbaaaaa["光蟲"]:::hide

%% ------------------------------ 殻虫目 ------------------------------

m["殻虫目"]:::_order
ma["棘虫亜目"]
maa[" "]
maaa[" "]
maaaa["カンタロス科"]
maaaaa[" "]
maaaaaa["カンタロス"]
mab[" "]
maba[" "]
mabaa["オルタロス科"]
mabaaa[" "]
mabaaaa["オルタロス"]
mb["針尾亜目"]
mba[" "]
mbaa[" "]
mbaaa["ランゴスタ科"]
mbaaaa[" "]
mbaaaaa["ランゴスタ"]
mbb[" "]
mbba[" "]
mbbaa["ブナハ科"]
mbbaaa[" "]
mbbaaaa["ブナハブラ"]
mc["閃虫亜目"]
mca[" "]
mcaa[" "]
mcaaa["ライコウチュウ科"]
mcaaaa[" "]
mcaaaaa["大雷光虫 / 雷光虫"]
mcab[" "]
mcaba["ホタル科"]
mcabaa[" "]
mcabaaa["（釣り）ホタル"]:::hide

%% ------------------------------ 甲虫目 ------------------------------

n["甲虫目"]:::_order

n_[" "]
n__[" "]
n___[" "]
n____["コガネムシ科<br/>カブトムシ亜科"]
n_____[" "]
n______["ドスヘラクレス"]:::hide
na["食肉亜目"]
naa[" "]
naaa[" "]
naaaa["セルタス科"]
naaaaa[" "]
naaaaaa["アルセルタス / ゲネル・セルタス"]
nb["盾虫亜目"]
nba[" "]
nbaa[" "]
nbaaa["クンチュウ科"]
nbaaaa[" "]
nbaaaaa["クンチュウ"]
nc["閣螳螂亜目"]
nca[" "]
ncaa[" "]
ncaaa["アトラル科"]
ncaaaa[" "]
ncaaaaa["アトラル・カ"]

%% ------------------------------ 鋏角目 ------------------------------

o["鋏角目"]:::_order
oa[" "]
oaa[" "]
oaaa[" "]
oaaaa["スキュラ科"]
oaaaaa[" "]
oaaaaaa["ネルスキュラ"]
ob[" "]
oba[" "]
obaa[" "]
obaaa["ヤツカダキ科"]
obaaaa[" "]
obaaaaa["ヤツカダキ / ツケヒバキ"]:::new

%% ------------------------------ 有尾目 ------------------------------

p["有尾目"]:::_order
pa["鬼蛙亜目"]
paa[" "]
paaa[" "]
paaaa["カブラ科"]
paaaaa[" "]
paaaaaa["テツカブラ"]
pb["化鮫亜目"]
pba[" "]
pbaa[" "]
pbaaa["ザボアザギル科"]
pbaaaa[" "]
pbaaaaa["ザボアザギル / スクアギル"]
pc["河童蛙亜目"]
pca[" "]
pcaa[" "]
pcaaa["ヨツミワドウ科"]
pcaaaa[" "]
pcaaaaa["ヨツミワドウ"]:::new

%% ------------------------------ 十脚目 ------------------------------

q["十脚目"]:::_order
qa[" "]
qaa["短尾下目"]
qaaa["盾蟹上科"]
qaaaa["ザザミ科"]
qaaaaa[" "]
qaaaaaa["ダイミョウザザミ / ヤオザミ"]
qaab["鎌蟹上科"]
qaaba["ギザミ科"]
qaabaa[" "]
qaabaaa["ショウグンギザミ / ガミザミ"]
qb[" "]
qba["不明"]
qbaa[" "]
qbaaa["ガオレン科"]
qbaaaa[" "]
qbaaaaa["シェンガオレン"]

```
