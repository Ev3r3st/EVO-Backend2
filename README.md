# EVO Backend

Tento repozitář obsahuje backendovou část aplikace EVO – motivační platformy pro dosahování cílů a osobní rozvoj.

## 🌐 Odkazy na běžící aplikaci

- **Frontend aplikace**: [evo-theta.vercel.app](https://evo-theta.vercel.app)
- **Backend API**: [evo-backend-production-162e.up.railway.app/api](https://evo-backend-production-162e.up.railway.app/api)

## 🚀 Technologie

Projekt je postaven na následujících technologiích:

- **NestJS** – Node.js framework pro tvorbu škálovatelných serverových aplikací
- **TypeScript** – staticky typovaný JavaScript
- **JWT (JSON Web Tokens)** – autentizace
- **PostgreSQL** – relační databáze
- **Prisma ORM** – přístup k databázi
- **Swagger** – dokumentace API
- **Railway** – hostování backendu

## 📁 Struktura projektu


## 🔐 Autentizace

- Registrace a přihlášení probíhá pomocí username a hesla
- Po přihlášení je uživateli vrácen JWT token
- Token je nutné zasílat v hlavičce `Authorization: Bearer <token>` pro přístup k chráněným endpointům

