# Misc04

```
nc misc04.grandprix.whitehatvn.com 1337

Hint:
After get the message "It's a friendly point", you should send the friendly point value.
```

The challenge presents us with a netcat for `misc04.grandprix.whitehatvn.com` on port `1337`. We can see that the formula for solving this challenge is 
`(lip point**nose point)**(eyes point**forehead point) mod Face_index`

```
                   Wellcom to Friendly face challenge
According to experts, the formula for measuring the friendliness of a face is
    (lip point**nose point)**(eyes point**forehead point) mod Face_index
                              Now play!
------------------------------Stage 1--------------------------------------
Face_index: 7248018
Face           Lip point      Nose point     Eyes point     Forehead point 
:-)            62515187       598438853      660009102      481080550      
(';')          175759867      714568841      32981249       684691754      
(=^..^=)       622615728      464944962      498708321      644287332      
:)             484519977      959633453      303159569      715280904      
:-]            312163080      374934651      157066371      898411433      
:]             294038489      50668182       422919091      887812239      
:-3            43758801       109335341      208705517      209116125      
:3             807144739      983150934      658411607      711272803      
:->            291674872      850237750      635517071      41123075       
:>             994531066      335574467      155217665      95045648       
:-*            813339768      489919164      115430198      563529898      
:*             294248508      825966183      575141364      333348565      
(>_<)          540757221      355248454      108960356      460286411      
(>_<)>         203659968      460026756      501332832      392769727      
(';')          759605074      139340597      302829849      152339252      
(^_^;)         547347609      27416273       564988005      15265700       
(-_-;)         891448624      635274921      863904803      128388754      
(~_~;)         669309614      860724722      646393937      762228537      
(...;)         404597104      174515231      984402945      364195097      
(._.;)         731982818      555587008      216057409      863926686      
^_^;           515180356      44388960       682398720      130071450      
(#^.^#)        179191819      891278487      642309894      133961941      
(^^;)          264570121      220167478      25770237       687393144      
(-_-)zzz       536449106      677870488      448148568      301058499      
(^_-)          1449579        939713979      77087868       764317024      
((+_+))        563621971      397452328      346563346      359886691      
(+o+)          553280913      580708016      620566112      321178588      
^_^            262992575      861459515      799080565      788622498      
(^_^)/         181513760      543177240      412430699      709008444      
(=_=)          792565507      782710869      773187691      803977138      
(?_?)          862837453      527595100      948699084      161350077      
(^_^)          76904816       506278055      208002595      188487722      
(~o~)          401447836      808967031      554556845      95166086       
(~_~)          194821956      845417377      910279958      473749869      
o.O            964255251      505320991      828235214      265057106      
(o.o)          452506438      770172663      636600612      75825049       
oO             108538909      522262785      154424924      521818071      
<_<            85076346       258471035      514462521      214654174      
>_>            251863671      977679627      446953711      729551028      
<o?o>          784104046      338681054      253357785      776842972      
(>^.^)         884339970      445852653      283960762      141434967      
(^.^<)         39040832       614932857      345148954      510279936      
>,<            186249125      294289889      157928505      671765221      
;-(            155841247      405226390      165145018      370845680      
>:-(           759148378      588374352      210789096      391250005      
@(-_-)@        188378043      895281968      225053513      683882184      
@(^_^)@        29661599       841740695      322045420      786383713      
~O-O~          14318933       593983655      234361974      862862385      
:)]            997625182      902904300      835916701      845580156      
.-]            157472900      971865775      663780707      875923619      
.-)            892441429      521596795      618919979      224566960      
,-)            852672599      553701799      337079242      357748800      
':-(           613255409      322185686      457425663      629491686      
'-)            260749671      741548568      751634165      59987381       
:-D            814627743      588829831      595094492      347103175      
:=)            111719536      76082729       677885742      769761939      
:@             674768155      329442113      664939309      863750106      
<:-P           590806689      726115557      113117914      732110976      
:)>-           770533742      314060732      265437700      896175739      
:^)            683590337      44298378       692438861      609560067      
3:]            200913409      989590105      293626173      203923931      
(o^-^o)        700591797      10685471       840412495      215251883      
:-<            955901752      496457625      976356091      410525677      
:-[            938221059      233256728      682152980      650476217      
=:-)           791779936      230840750      625405718      247020636      
:-))           290130431      171902023      814968783      725786710      
<(-_-)>        982629735      900435883      11737125       354828505      
9_9            290762540      456570619      772097756      426236828      
=))            580067011      897044530      490743436      478865624      
7:)            170389374      620030288      521743745      791891742      
(<_>)          246623502      887156834      102128243      848758603      
:-(            630534471      618439377      426638392      951032334      
/:-)           254530269      191272921      547291081      664713894      
(-_-)          761959473      547847348      574262324      591758664      
:-*            634472142      668843229      29667027       411979202      
::=))          729958148      815719233      247960725      361241411      
o_o            804705582      976918875      526732391      864173300      
(*^_^*)        488724108      350432535      877699808      533943750      
(-::-)         167530830      760218309      589015434      593217428      
(^o^)          307014286      101134566      253848704      974719401      
:o)            136036506      475811709      868995840      87680913       
:|)            121554571      655764804      679169990      220188318      
:)             78073926       488664939      54819097       852768044      
:-)            527711116      106873777      116191472      555124527      
+:-)           431403103      702106441      887027081      671612975      
(:-)           666214107      443213072      456321193      294083995      
{:-)           253594405      401993310      744623018      184819387      
^&^            580595586      941801907      512299744      304532429      
=.=            526205363      657455568      564196109      16345817       
*~*            557657984      765709563      675767494      148195800      
(:>-<          793249052      300452738      704490135      444749818      
:-)---         164425027      375466046      968173017      732338903      
*-)            365062327      617894424      813251935      601354964      
>:*            731146014      722351363      893458024      762304778      
>.<            565124980      976419505      922697478      249535801      
:-@            964269966      653396270      62619899       118291015      
(:)-)          888475415      414321731      571726302      295159245      
::-)           401422142      556688217      756737481      450820563      
:-@            817966518      700464782      613844120      969912246      
@,.,@          527008235      540173314      676200735      348855597      
:-E            107987442      506772505      507183936      929076775      
:-[            229116446      663228616      554779025      953622579      
:-))           84875333       860560665      735292087      729614520      
:-[]           143704034      450096820      332195728      603001302      
:-)))          609836329      692768487      189791384      396478768      
(:-            486776775      548973652      609541515      135065657      
$_$            172140442      627220622      609491746      510340778      
(^:^)          762242726      117959542      737820165      127370021      
|___|          452943456      491591596      840494146      372118679      
:-)            72231956       664441176      564461990      967436724      
>O<            426544193      349482728      994566318      258644660      
:=)            962095939      781710036      755412830      522986301      
-:-)           346676885      20277385       200414459      48067414       
|:-)           242695162      59964554       604193492      111467599      
<(^.^<)        743103602      844349171      559355812      952873446      
<(*.*<)        776993911      906720290      946010258      550118481      
(*_*)          897406241      296194516      219168664      666720505      
._.            122023992      838009549      989319590      734638619      
@:-)           823551766      479431767      511051498      890103720      
<('.')>        688824487      745522053      88001906       542583893      
<('.'<)        170014871      987616528      337475329      551431578      
<(^.^)>        941942664      490649615      488630191      913968148      
<('.'<)        918084239      857521709      636405623      581050955      
:-*            343324777      892091243      809747909      96553787       
(:-*           315273670      710835895      859448771      644004667      
=^.^=          892038788      641561425      636798190      519779337      
<{::}>         58136399       208719026      338059182      394003262      
:-D            204444791      634174962      699799654      263424180      
:))            943211298      575730019      563285003      138422486      
:.-)           918879720      358084055      878178492      80341981       
(-:            159914327      234454729      165368931      852969122      
>;->           718138022      977402219      696484608      505886102      
:^o            328523901      697383788      373828641      388063761      
:-9            533967630      731447132      170156919      543663362      
So, what is the most friendly face?
```

The numbers for the formula `(lip point**nose point)**(eyes point**forehead point) mod Face_index` are too large to compute in Python or C, so an alternative approach is needed to solve this challenge. The issue with solving this challenge is that we are dealing with integers larger than 64 bit which takes too much processing power in C or Python. In order to solve this problem we must understand modular exponentiation and the algorithms needed to implement it. Through a bit of searching we were able to find an approach of how to solve big integer math that followed the pattern of [a^b^c^d mod m](https://stackoverflow.com/questions/4223313/finding-abc-mod-m). Since the numbers are coprime we can use Euler's totient function along with chinese remainder theorem to solve the challenge. See the full python script on this implementation.


Finally we get the flag...
` "Congrats! Flag, flag, flag!: WhiteHat{^.^_M4th_Math_Chin3se_Rema1nder_The0rem_&_Euler's_ThEorem_M@th_MAth_^/^}\n"`
Yet this flag was still incorrect, what's the issue?? It turns out we need to compute the SHA-1 of the message digest.


```
echo -n "^.^_M4th_Math_Chin3se_Rema1nder_The0rem_&_Euler's_ThEorem_M@th_MAth_^/^" | sha1sum
883e8e59798f1884c3873ff5f47aaeea089097f9  -
```

WhiteHat{883e8e59798f1884c3873ff5f47aaeea089097f9}


