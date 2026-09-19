# Kanban ja automaatika

Staatus: allpool on GitHub Projects-tahvli seadistusplaan. Automaatikat ei ole veel GitHubis aktiveeritud.

## Veerud

Ideed / Tegemata / Töös / Ülevaatamisel / Valmis

Igal ülesandel on vastutaja, etapp ja valmisoleku tingimused. Takistuse korral lisage silt `takistus` ja kommentaar selle kohta, millist abi vajate.

## Kavandatud automaatika

| Sündmus | Tegevus |
|---|---|
| Repos luuakse issue või pull request | Projects lisab selle automaatselt tahvlile |
| Uus element jõuab tahvlile | Algolek „Tegemata” |
| Issue suletakse | Olek „Valmis” |
| Pull request ühendatakse | Olek „Valmis” |

„Töös” ja „Ülevaatamisel” valib õpilane ise. See väldib olukorda, kus pelk vastutaja määramine näitab tööd ekslikult alustatuna.

Issue sulgemiseks koodimuudatuse kaudu lisage põhiharusse suunatud pull request'i kirjeldusse näiteks `Closes #12`. Asendage 12 tegeliku ülesandenumbriga. Märksõna seob kooditöö ülesandega. Uurimisülesande sulgeb ülevaatuse järel vastutaja.

Automaatset arhiveerimist ei ole vaja: valmis ülesanded jäävad loovtöö panuse ja käigu tõendiks nähtavale. Suletud, kuid ühendamata pull request ei tähenda, et seotud töö sai valmis. Ülesande olukord tuleb üle vaadata.

## Seadistamise kontroll

1. Lisage algülesanded tahvlile. Automaatne lisamine peab katma ka tulevased ülesanded.
2. Looge prooviks issue ja kontrollige tahvlile ilmumist.
3. Sulgege prooviülesanne ja kontrollige olekut „Valmis”.
4. Kontrollige seotud proovimuudatusega ülesande sulgumist põhiharusse ühendamisel.
5. Veenduge, et õpilased saavad ülesandeid liigutada ja muuta.

[GitHub Projects automaatika juhend](https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/using-the-built-in-automations)
