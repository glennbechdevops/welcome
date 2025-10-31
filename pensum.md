# Pensumliste PGR301 -2025

## Generelt 

* Codespaces - logge på AWS konto med egen bruker og passord gitt i klasseromet  
* Skin in the game, hvorfor virker DevOps? 


## AWS tjenester dere vil bli venn med i løpet av semesteret 

* AWS S3 - Simple Storage Service 
* AWS IAM - Identity and Acccess Management 
* AWS Lambda - Functions as a service 
* AWS Comprehend - tekstanalyse 
* AWS ECR - Elastic Container Service 
* AWS App Runner - Containers as a service 

## Flow - prinsipper 

- Kontinuerlig integrasjon
- Kontinuerlige leveranser
- De 4 devops metrikkene - Lead time (Tid fra commit til kunde), Deploymentfrekvens, Deployment feilrate , tid for gjenopprettin ved feil (MTTR) 
- Fjerne "waste" i prosessen for utvikling 
- One piece flow (vs Batch) - små kontinuerlige endringer  (CD)
- Færrest mulig overleveringer - Frontend/backend, Dev/Ops, Kunde/leverandør osv
- Gjøre arbeid synlig - Trello, JIRA osv 
- Deployment vs Release, hvordan release kode og ikke funksjonalitet 

## flow - ferdigheter

### GitHub Actions og SAM 

* GitHub actions workflows. Struktur på dokumentet og overordnet fårståelse av "Workflow", "jobb" og "steg".
* Kompilering, bygging og kjøring av tester i et Spring Boot prosjekt med Maven i GitHub Actions 
* AWS Lambda, function as service, grunnleggende forståelse 
* AWS SAM, grunleggende forståelse - kunne lage et nytt prosjekt, deploye, teste lokalt i CodeSpaces 
* AWS SAM, kunne lage en GitHub Actions Workflow for et SAM prosjekt 
* GitHub Actions hemmeligheter / Repository Secrets

### Docker 

* Forstå hva hva en Container er i kontekst av virtualisering, og gevinstene docker gir i mikrotjenestearkitektur
* Docker og Containere, kunne lage en Docker Container fra Spring Boot applikasjon 
* Docker bygge container image  fra GitHub Actions
* Fra egen maskin eller CodeSpaces - Publisere container image til Docker Hub
* Fra egen maskin eller CodeSpaces - Publisere container image til AWS Elastic Container Registry /ECR 
* Fra GitHub Actions workflow -  publisere container image til AWS Elastic Container Registry /ECR eller GitLab
* Deployment av Spring Boot apps/Containere til AWS AppRunner fra AWS UI  

### Infrastruktur som kode (IAC)

* Terraform - grunleggende forståelse for Infrastruktur som kode med AWS provider som eksempel
* Terraform State og livssyklus
* Terraform AWS provider, data, resource, variabler
* Deployment av Spring Boot apps/Containere til AWS AppRunner fra Terraform
* Terraform moduler
* Kjøre Terraform fra GitHub Actions

## Feedback - prinsipper 

- Se problemer tidlig, fange opp svake signaler før de blir store feil 
- Metrikker og telemetri
- Problemstorming 
- Kvalitet skal oppstå ved kilden 
- Optimalisering for neste ledd i verdikjeden

## Feeedback - ferdigheter 

* AWS CloudWatch
* Kunne bruke Micrometer, metrics-rammeverk i Spring Boot - ulike typer meter som counter, timer, distributonsummary, longtasktimer   
* Eksport av Metrics fra Spring Boot og Micrometer til AWS CloudWatch
* Lage Dashbord i AWS CloudWatch
* Lage Dashbord i AWS CloudWatch fra Terraform 
* CloudWatch Alarmer  
* Terraform, GitHub Actions for Alarmer og Dashbord 

## Kontinuerlig forbedring - prinsipper 

* Retrospespektiver: Gjennomfør jevnlige retrospektiver etter hver iterasjon eller prosjektsyklus for å evaluere hva som gikk bra, hva som gikk galt, og hvordan man kan forbedre prosessen.
* Kontinuerlig opplæring og kompetanseutvikling: Sørg for at teammedlemmene kontinuerlig lærer og utvikler seg for å holde tritt med nye teknologier og beste praksis innenfor DevOps.
* Måling og KPI-er: Definer nøkkelindikatorer for ytelse (KPI-er) og mål for å vurdere effektiviteten av DevOps-prosessene. Disse målene kan inkludere gjennomsnittlig leveringstid, feilrater, og kundetilfredshet.
* Kultur: Skap en kultur som oppmuntrer til åpen kommunikasjon, samarbeid og ansvarlighet. Kontinuerlig forbedring er avhengig av et team som er villig til å utfordre status quo og jobbe sammen mot felles mål
