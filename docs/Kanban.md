# Kanban ja automaatika

[Tööde tahvel](https://github.com/orgs/parnu-digiloovtoo/projects/1/views/1) · [Ülesanded](https://github.com/parnu-digiloovtoo/silt/issues)

## Veerud

Ideed → Tegemata → Töös → Ülevaatamisel → Valmis

- **Ideed:** võimalikud lisatööd ja täpsustamist vajavad mõtted.
- **Tegemata:** kokkulepitud ülesanded koos valmimistingimustega.
- **Töös:** aktiivne töö; korraga kuni kolm põhiülesannet, üks iga õpilase kohta.
- **Ülevaatamisel:** kaaslane kontrollib tulemust.
- **Valmis:** kontrollitud ja lõpetatud töö.

Igal ülesandel määrake vastutaja ning leppige kokku tähtaeg. Takistuse korral lisage kommentaar. A01–A20 on loodud ülesannetena #1–#20.

## Seadistatud automaatika

- Repo silt uus või uuendatud avatud issue või pull request lisandub tahvlile (filter `is:open`).
- Lisatud töö saab staatuse **Tegemata**.
- Ülesandega seotud pull request viib ülesande staatusesse **Töös**.
- Suletud issue või pull request liigub **Valmis** veergu. Ühendamata suletud PR ei tähenda, et sellega seotud ülesanne on tehtud.
- Ühendatud pull request liigub **Valmis** veergu.
- Issue viimine **Valmis** veergu sulgeb selle automaatselt.
- Projektis oleva töö alamülesanded lisatakse samuti projekti.

Töö alustamisel määrab õpilane staatuse Töös. Ülevaatamisel määratakse käsitsi. PR-i kirjelduses `Closes #number` seob muudatuse ülesandega; põhiharusse ühendamisel sulgeb GitHub seotud ülesande. Sulgege või viige töö Valmis veergu alles pärast kaaslase kontrolli.

## Kontroll

19.09.2026: [kontrollülesanne #21](https://github.com/parnu-digiloovtoo/silt/issues/21) lisandus automaatselt veergu Tegemata ning sulgemisel liikus automaatselt veergu Valmis. PR-reeglid on seadistatud; eraldi katse-PR-i ei loodud.

Õpilaste ligipääs lisatakse pärast GitHubi kasutajanimede saamist. Seejärel kontrollib iga liige töö liigutamist ja muutmist.
