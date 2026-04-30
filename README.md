# Ola Eriksen Wold

Utvikler med fokus på fullstack — Spring Boot på backend og React/TypeScript på frontend.
Studerer informatikk og bygger prosjekter på fritiden for å lære og prøve ut nye ting.

## Stack

**Backend:** Java 21, Spring Boot, Spring Data JPA, Hibernate, PostgreSQL

**Frontend:** React, TypeScript, Vite, Tailwind CSS, shadcn/ui

**Verktøy:** Maven, Git, IntelliJ, VS Code

## Prosjekter

### [CRM-system](https://github.com/OlaWold/CRM-system)
Webbasert CRM for håndtering av kunder, tickets, kontakter og notater.
Videreutvikling av et studieprosjekt med fokus på en realistisk domene-modell og ryddig REST-API.

- **Backend:** Spring Boot 4 (Java 21), Spring Data JPA, PostgreSQL
- **Frontend:** React 19, TypeScript, Vite, Tailwind, shadcn/ui

### [Portfolio](https://github.com/OlaWold/Portfolio)
Personlig porteføljeside med kontaktskjema via EmailJS.

- React 19, TypeScript, Vite, Tailwind

## Kjøre prosjektene lokalt

Fullstack-prosjektet har samme oppsett: Spring Boot i rota, React-frontend i `frontend/`. Her er fellesoppskriften.

### Forutsetninger

- Java 21
- Node.js 20+ og npm
- PostgreSQL (kun prosjekter med database, f.eks. CRM-system)

### Backend

```bash
git clone https://github.com/OlaWold/<prosjekt>.git
cd <prosjekt>
./mvnw spring-boot:run
```

Backend kjører på `http://localhost:8080`.

For prosjekter med database: start en lokal PostgreSQL-instans og oppdater `src/main/resources/application.properties` med dine credentials før første oppstart. CRM-systemet forventer en database `crm_project` på port `5433`.

### Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend kjører på `http://localhost:5173` og snakker med backend via `http://localhost:8080`.

### Rene React-prosjekter (Portfolio)

```bash
git clone https://github.com/OlaWold/Portfolio.git
cd Portfolio/mitt-prosjekt
npm install
npm run dev
```

## Kontakt

- GitHub: [@OlaWold](https://github.com/OlaWold)
