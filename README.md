# brukernotifikasjon-public-topic-iac

Repo med konfigurasjon for hvem som kan produsere og konsumere fra DittNAV sine åpne topics.

## Hvordan kobler jeg meg på interne-dittnav-topics?

**For skrivetilgang**

```
        - team: myTeam
          application: myApplication
          access: write 
```
**For lesetilgang**

```
        - team: myTeam
          application: myApplication
          access: read 
```

Når en skal spesifisere topic-navn i sin app må man også ha med navn på namespace der topic ligger. 

For alle topicer i dette repoet vil dette være `min-side`.

For eksempel: `min-side.aapen-brukernotifikasjon-beskjed-v1`

# Henvendelser

Spørsmål knyttet til koden eller prosjektet kan rettes mot https://github.com/orgs/navikt/teams/min-side


## For NAV-ansatte

Interne henvendelser kan sendes via Slack i kanalen #brukernotifikasjoner.
