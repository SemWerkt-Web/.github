# Semwerkt | Shopify

Welcome to the central GitHub organization of **Semwerkt**. As a full-service online marketing agency based in Hoorn, we deliver scalable e-commerce solutions where technical excellence and data-driven results are at the core of everything we do.

## About Semwerkt
Semwerkt supports organizations in translating commercial ambitions into measurable online growth. With a team of specialists in SEO, SEA, Data, and E-commerce, we build sustainable partnerships. This GitHub organization serves as the central repository for our Shopify projects and custom-built solutions.

## Development Workflow & Standards
To ensure the continuity and quality of our stores, we maintain a strict version control protocol:

### 1. Branching Strategy
* **`main`**: Contains the stable production code currently live on the webshop. Direct pushes to this branch are strictly prohibited.
* **`staging`**: The acceptance environment used for quality assurance (QA) and content management by stakeholders.
* **`feature/*`**: Branches dedicated to individual functional developments and bug fixes.

### 2. Quality Assurance
* **Pull Requests**: Every code change is subject to a peer review before being merged into the staging environment.
* **Shopify GitHub Integration**: We utilize the native integration between GitHub and Shopify for seamless synchronization between our codebase and the Theme Editor.
* **Local Development**: Development takes place in isolated environments using the Shopify CLI to prevent any interference with the live production environment.

## Collaboration & Roles
Within this organization, we work closely in multi-disciplinary teams:
* **Developers**: Responsible for technical architecture, performance optimization, and the implementation of new functionalities.
* **Strategists & Stakeholders**: Responsible for content management, visual configuration via the Shopify Customizer, and functional acceptance testing.

## Contribution Guidelines
1. Create a new branch originating from the most recent version of `staging`.
2. Implement changes and test them thoroughly in a local preview environment.
3. Open a Pull Request to `staging` including a clear description of the modifications.
4. Following technical approval and functional validation, the code will be promoted to `main`.

---

## Contact & Information
**Semwerkt B.V.** Willemsweg 73, 1623 JB Hoorn  
[www.semwerkt.nl](https://www.semwerkt.nl)  
info@semwerkt.nl  

*Semwerkt – Together, we translate ambitions into measurable online growth.*
