# 📇 CRM PowerApp voor Gemeenten

De CRM PowerApp is een herbruikbare low-code oplossing voor het beheren van gemeentelijke contacten, relaties en communicatie. De app is ontwikkeld om versnipperde contactgegevens binnen gemeenten te centraliseren en biedt gebruikersvriendelijke functies voor relatiebeheer, communicatiehistorie en opvolging van acties. Dit project is ontwikkeld door ITRLBS in opdracht van  gemeente Gooise Meren, en is beschikbaar gesteld voor hergebruik door andere overheden.

## Informatie Algemeen
De App is ontwikkeld door ITRBLS in opdracht van gemeente Gooise Meren, voor meer informatie neem contact op met [Mark Mulder - Informatiemanager Gooise Meren] (https://www.linkedin.com/in/mark-mulder/)

## 🎯 Doel van de app

De CRM PowerApp biedt:
- **Centrale opslag van contacten** (personen en organisaties)
- **Relaties leggen tussen entiteiten** (bijv. ondernemers, ketenpartners)
- **Communicatie- en interactiehistorie** per contact
- **Follow-ups en actiebeheer**
- **Inzicht in betrokken interne collega’s**

De app sluit aan op de gemeentelijke behoefte aan een lichtgewicht CRM-systeem, en kan eenvoudig worden aangepast of uitgebreid.

## 🏗️ Architectuur

Deze oplossing is ontwikkeld met:
- **PowerApps App** (front-end)
- **Dataverse** (gegevensopslag)
- **Power Automate** (flows voor logica en integratie)
- **Standaard connectoren** naar Microsoft 365
- **Rolgebaseerde toegang** via Power Platform security-rollen

> 💡 De app is gebaseerd op Microsoft Power Platform en vereist licenties die toegang geven tot Dataverse-functionaliteit.

## 🚀 Installatie-instructies

### 📦 Voorbereiding

Je hebt nodig:
- Het .zip-bestand met de solution (niet uitpakken!)
- Toegang tot [https://make.powerapps.com](https://make.powerapps.com)
- Een account met rol **System Administrator** of **Environment Maker**
- Een geschikte Power Platform **environment**

### 🛠️ Installatiestappen

1. Ga naar [make.powerapps.com](https://make.powerapps.com)
2. Selecteer rechtsboven de juiste environment
3. Navigeer naar **Solutions**
4. Klik op **Import**
5. Upload het .zip-bestand (niet uitpakken!)
6. Klik op **Next**
7. Vul indien gevraagd:
   - **Connection references**: koppel bestaande verbindingen
   - **Environment variables**: controleer of waarden correct zijn
8. Klik op **Import**
9. Wacht tot de status **Succeeded** is 

### ✅ Na installatie

1. Open de geïmporteerde solution
2. Controleer of alle Power Automate flows zijn **ingeschakeld**
3. Test de app(s) en flows
4. Richt eventuele **rollen, toegangsrechten en instellingen** in met hulp van je interne ICT-afdeling

Bij problemen: neem contact op met de ontwikkelaar via [m.vankol@itrbls.com](mailto:m.vankol@itrbls.com)

## 🔐 Licentie

Deze PowerApp staat onder de **Apache License Version 2.0**. Je mag de code vrij hergebruiken, wijzigen en verspreiden onder dezelfde voorwaarden. Voor meer informatie, zie het `LICENSE`-bestand.

## 🤝 Bijdragen

Bijdragen aan dit project zijn welkom! 
Neem contact op met Mark Mulder (Informatiemanager Gemeente Gooise Meren).

---

*Ontwikkeld door gemeente Gooise Meren (DPI-team), i.s.m. iTRBLS.*
