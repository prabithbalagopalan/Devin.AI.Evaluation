# Enterprise Full-Stack Application Development: SupplyChain Pro

I need you to develop a comprehensive enterprise supply chain management system called "SupplyChain Pro" using modern full-stack technologies. This project will evaluate your capabilities across the complete Software Development Life Cycle (SDLC).

## Technology Stack Requirements
- **Frontend**: React 18 with TypeScript
- **Backend**: Java Spring Boot 3.2+ with Java 17+
- **Database**: PostgreSQL 15+
- **Build Tools**: Maven for backend, Vite for frontend
- **Testing**: JUnit 5 + Mockito (backend), Jest + React Testing Library (frontend)

## Application Overview
Build an enterprise-grade supply chain management platform with the following core modules:
1. **Vendor Management System** - Registration, onboarding, performance tracking
2. **Procurement Management** - Purchase requisitions, RFQ/RFP, purchase orders
3. **Inventory & Warehouse Management** - Multi-location tracking, automated reordering
4. **Order Management & Fulfillment** - Order processing, shipping, returns
5. **Financial Integration** - Accounts payable, cost centers, budget management
6. **Analytics & Business Intelligence** - Dashboards, reporting, KPIs

## SDLC Phase Requirements

### Phase 1: Requirement Gathering
- Create user personas for different roles (Procurement Manager, Warehouse Staff, Finance Team, Admin)
- Develop comprehensive Business Requirements Document (BRD)
- Define Non-Functional Requirements (NFRs) including performance, security, scalability
- Establish accessibility requirements (WCAG 2.1 AA compliance)
- Document security and compliance requirements (audit trails, data encryption)

### Phase 2: Planning & Technology Selection
- Create detailed product roadmap with MVP scope definition
- Document technology stack decisions with justifications
- Plan microservices architecture vs monolithic approach
- Define DevOps toolchain and development workflow
- Create release planning with feature prioritization (MoSCoW method)

### Phase 3: Analysis & Domain Modeling
- Implement Domain-Driven Design (DDD) with clear bounded contexts
- Create comprehensive Entity Relationship Models
- Design user story mapping and user flow diagrams
- Develop API resource modeling for all business entities
- Conduct event storming sessions for business process mapping

### Phase 4: System & UI/UX Design
- Design microservices architecture with proper service boundaries
- Create React component architecture using Atomic Design principles
- Implement state management strategy (Redux Toolkit + RTK Query)
- Design RESTful API contracts with OpenAPI 3.0 specifications
- Create comprehensive database schema with proper indexing
- Design authentication/authorization system (JWT + Spring Security)
- Develop UI mockups and design system with reusable components

### Phase 5: Sprint Planning & Development Coordination
- Plan vertical slice development (full-stack features)
- Establish frontend-backend API contract agreements
- Create mock API/stub planning for parallel development
- Design database migration strategy using Flyway
- Define Definition of Done (DoD) checklist

### Phase 6: Full-Stack Development
**Backend Development (Spring Boot):**
- Implement microservices with proper layered architecture
- Create JPA entities with relationships and constraints
- Develop Spring Data repositories with custom queries
- Implement Spring Security with JWT authentication and RBAC
- Create comprehensive REST APIs with validation and error handling
- Write unit tests with JUnit 5 and Mockito
- Implement caching strategy with Spring Cache

**Frontend Development (React):**
- Build responsive React components with TypeScript
- Implement Redux Toolkit for state management
- Create forms with React Hook Form and validation
- Develop data grids with sorting, filtering, and pagination
- Implement real-time features and notifications
- Create comprehensive component library with Storybook
- Write unit and integration tests with Jest and React Testing Library

**Database Implementation:**
- Design normalized PostgreSQL schema with proper constraints
- Implement database migrations with Flyway
- Create optimized indexes for performance
- Implement audit trails and data versioning
- Design multi-tenant data isolation

### Phase 7: Comprehensive Testing
- Implement End-to-End testing with Cypress or Playwright
- Create API integration tests with TestContainers
- Perform visual regression testing
- Conduct performance testing and Core Web Vitals optimization
- Execute security testing following OWASP guidelines
- Implement accessibility testing (WCAG compliance)
- Conduct cross-browser and mobile responsive testing

### Phase 8: Review & Quality Assurance
- Create comprehensive API documentation with OpenAPI
- Implement code quality metrics and analysis
- Conduct performance benchmarking and optimization
- Perform security audit and vulnerability assessment
- Create technical debt assessment and improvement plan

### Phase 9: Deployment & DevOps
- Set up CI/CD pipeline with automated testing and deployment
- Implement containerization with Docker
- Create deployment scripts and configuration management
- Set up monitoring and health checks
- Implement feature flags and configuration management
- Create comprehensive deployment documentation

### Phase 10: Monitoring & Maintenance
- Implement application monitoring and logging
- Set up error tracking and alerting
- Create performance monitoring dashboards
- Implement backup and disaster recovery procedures
- Document operational procedures and runbooks

## Key Evaluation Criteria

### Technical Excellence
- Clean, maintainable code following best practices
- Proper implementation of design patterns and architectural principles
- Comprehensive testing strategy with high coverage (>85%)
- Performance optimization and scalability considerations
- Security implementation throughout the application

### Enterprise Features
- Multi-tenant architecture support
- Comprehensive audit trails and compliance features
- Advanced search and filtering capabilities
- Real-time notifications and updates
- Responsive design for mobile and desktop
- Internationalization (i18n) support

### Documentation & Communication
- Clear technical documentation and API specifications
- Comprehensive README with setup instructions
- Architecture Decision Records (ADRs)
- User guides and operational documentation

## Deliverables Expected
1. Complete source code for frontend and backend
2. Database schema and migration scripts
3. Comprehensive test suites (unit, integration, E2E)
4. API documentation (OpenAPI/Swagger)
5. Technical architecture documentation
6. Deployment and operational guides
7. Performance and security test reports

## Success Metrics
- Application handles 1000+ concurrent users
- API response times < 200ms for standard operations
- 99.9% uptime with proper error handling
- Zero critical security vulnerabilities
- Full accessibility compliance (WCAG 2.1 AA)
- Comprehensive test coverage (>85%)

Please start with Phase 1 (Requirement Gathering) and proceed systematically through each SDLC phase. Focus on enterprise-grade quality, scalability, and maintainability throughout the development process.
