# Nordvik Fastigheter AB – Azure-examination

## Projektbeskrivning
Detta projekt är en examinationsuppgift i kursen Microsoft Azure (MOV25).

Målet är att bygga en säker hyresgästportal för Nordvik Fastigheter AB. Hyresgäster ska kunna logga in, skicka felanmälningar och ladda upp bilder.

## Planerade Azure-tjänster
- Azure App Service – webbportal
- Microsoft Entra ID – autentisering och roller
- Azure Virtual Network och NSG – nätverkssäkerhet
- Azure Blob Storage – lagring av anmälningar och bilder
- Azure Managed Identity och RBAC – säker åtkomst
- ARM-templates – infrastruktur som kod
- Power Automate – automatisering
- SharePoint och Outlook – Microsoft 365-integration

## Projektstruktur
- `app/` – applikationskod
- `arm/` – ARM-templates och parametrar
- `docs/` – dokumentation och bilder
- `automation/` – beskrivning av Power Automate-flödet

## Driftsättning
Instruktioner för återskapande av miljön läggs till när ARM-mallarna är implementerade och testade.

## Säkerhet
Inga lösenord, API-nycklar eller anslutningssträngar ska lagras i detta publika repository.

## Status
Projektet är under utveckling. Målet är Godkänt.
