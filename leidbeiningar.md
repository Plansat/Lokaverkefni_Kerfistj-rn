#Áslaug

Til að búa til áslaugu þarf að gera alveg eins og með alla notendur

> useradd -m -c "Fullt nafn" -G "Hóparnir sem hún er í muna að hafa **SUDO** með hér líka" -s /usr/bin/"Skelin sem hún vill nota"

Skelin sem hún vill nota er ZSH til að setja hana upp þarf að fylgja leiðbeiningunum hér að neðan

##ZSH
------

Fyrst þarf að fara hingað [oh my Zsh](https://ohmyz.sh)

svo er ýtt á gula takkan install oh my zsh
eftir það þarf að velja *install with wget* sem er ekki default þegar er ýtt á install eins og sést hér á myndinni fyrir neðan

![ohmyzshdownload](/Pictures/Screenshots/oh_my_zsh_download.png

svo þarf að kópera kóðan og keyra í terminallinu sem ásluag þannig skrá sig inn á hana og downloada zsh.

Ef þetta virkar ekki þá er hægt að fylgja þessum leiðbeiningum hér fyrir neðan


##ZSH ekki að virka
------

Ef zsh virkar ekki þá ef þið eruð búin að búa til áslaugu þarf að fara inn á etc möppuna og svo gera 

> nano passwd

fara neðst niður og breyta skelinni hennar áslaugu í bash

eins og hér 

![Aslaug](/Pictures/Screenshots/Aslaug_zsh.png

------ 

ef ekki er búið að búa hana til þá hafa skelina bash þegar er verið að gera hana til.

Þegar það er búið að installa zsh þá getiði farið aftur í Áslaugu í gegnum passwd skránna og breytt skelinni aftur í zsh
eftir það þegar þið skráið ykkur inn á áslaugu gæti komið skilaboð sem segja
**"Þessar skrár eru ekki að fylgja með"**
svo er hægt að velja eitthvað það sem þið viljið velja er tölustafurinn 1 sem ætti að segja "continue to main menu" eftir það gæti hún spurt ykkur um að breyta stillingum það þarf ekki að gera það
ég breytti stillingunum um history svo ég fái history um skipanirnar þegar ég er inn á áslaugu og þið fylgjið bara þeim leiðbeiningum og veljið svo continu and save changes og haldið áfram og þá ætti 
zsh verið sett upp fyrir áslaugu.


### Áslaug sett upp

Núna ætti Áslaug að vera sett upp og með sudo réttindi og allt ef ekki þá þarf að skoða leiðbeiningarnar betur.





