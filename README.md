 Naija Nest: AI-Powered Real Estate Agent for Nigeria

Naija Nest is an intelligent real estate platform designed to solve the critical challenges of property discovery, verification, and agent trust in the Nigerian market. 

Focusing on the unique landscapes of Lagos, Abuja, Port Harcourt, and Owerri, Naija Nest leverages AI to create a transparent, efficient, and secure environment for property seekers and verified agents.


 Product Vision
In a market often plagued by "ghost listings" and verification hurdles, Naija Nest prioritizes Trust-First Architecture. Our mission is to bridge the gap between credible property listings and safe, informed decision-making for every Nigerian user, whether they are local professionals, students, or diaspora investors.

 Documentation Suite
The core strategy and architecture for Naija Nest are captured in the following documentation, located in the `/docs` directory:

[Product Strategy & PRD](./docs/NAIJA_NEST_PRODUCT_DOCS.pdf): Defines user personas, core pain points (Trust, Time, Affordability), and our Unique Value Proposition.
[System Architecture & Strategy](./docs/NAIJA_NEST_SYSTEM_ARCHITECTURE.pdf): Outlines the Java-based backend, event-driven architecture, and the "Trust Framework" used for document verification and data security.

 Tech Stack (Backend Architecture)
Naija Nest is built for enterprise-grade scalability and security.
* **Language:** Java
* **Framework:** Spring Boot (Modular Monolith / Microservices-ready)
* **Database:** PostgreSQL (Transactional) + Vector Database (AI Search/Embeddings)
* **Key Philosophy:** Event-Driven Architecture to handle asynchronous verification and real-time trust-score calculations.

 Roadmap
Phase 1: Foundation & Identity (KYC/Verification Logic)
Phase 2: Property Listing Engine & Conversational AI Integration
Phase 3: Trust Score Service & External API Integrations (BVN/NIN/Maps)
Phase 4: Beta Launch (Lagos/Abuja focus)

 Commit Guidelines
 
We use Conventional Commits to maintain a clean project history. Every commit message should be structured as follows:

<type>(<scope>): <short description>

Types:

feat: A new feature (e.g., feat(auth): add login functionality)

docs: Changes to documentation (e.g., docs(readme): update roadmap)

fix: A bug fix (e.g., fix(verification): correct BVN validation regex)

refactor: Code changes that neither fix a bug nor add a feature

chore: Maintenance tasks (e.g., chore: update dependencies)

Example:
feat(kyc): implement NIN verification API integration


This repository currently contains the structural and architectural documentation for the Naija Nest project. It does not currently contain executable source code. It is designed to serve as the definitive source of truth for the development team.*

Built with focus for the Nigerian Real Estate Ecosystem.
