# ✅ Test Plan – Agile Final Project: E-commerce Product Catalog

## 📌 1. Test Context

- **Scope**: Validate the backend functionalities of an e-commerce product catalog, including CRUD operations, like/dislike features, product listing and filtering, and cloud deployment.
- **Objectives**:
  - Ensure all functional requirements are correctly implemented.
  - Confirm system stability and accessibility after deployment.
  - Validate user stories through acceptance criteria.
- **Constraints**:
  - Backend-only testing (no frontend interface).
  - Simulated test environment with mock data.
- **Test Basis**:
  - Prioritized user stories from the Product Backlog.
  - Gherkin-style acceptance criteria.
  - Technical documentation in the repository.

---

## 📌 2. Assumptions and Constraints

- The test environment will mirror the production cloud setup.
- Test data will be created manually or via scripts.
- Test execution is limited to the sprint duration (2 weeks).
- No end-to-end automation tools will be used in this cycle.

---

## 📌 3. Stakeholders

| Role            | Responsibilities                                  | Training Needs              |
|------------------|----------------------------------------------------|------------------------------|
| Product Owner    | Validate acceptance criteria                       | None                         |
| Scrum Master     | Ensure testing is part of sprint planning          | None                         |
| Developer        | Execute unit and manual tests                      | Gherkin syntax familiarity   |
| QA (simulated)   | Validate stories based on defined criteria         | Kanban board usage           |

---

## 📌 4. Communication

- **Frequency**: Daily stand-ups and sprint review meetings.
- **Channels**: GitHub Issues, task comments, video calls.
- **Documentation Templates**:
  - Acceptance criteria in Gherkin (within issues)
  - Test checklists per story
  - Bug reports as GitHub issues

---

## 📌 5. Risk Register

- **Product Risks**:
  - CRUD failures may compromise data integrity.
  - Like/dislike logic errors may affect user experience.
- **Project Risks**:
  - Limited time for full test coverage.
  - Dependency on correct cloud environment setup.

---

## 📌 6. Test Approach

- **Test Levels**:
  - Unit tests (individual functions)
  - Integration tests (API flows)
  - Acceptance tests (based on Gherkin)
- **Test Types**:
  - Functional, regression, smoke
- **Techniques**:
  - Equivalence partitioning, boundary value analysis, behavior-driven testing (BDD)
- **Test Artifacts**:
  - Test scripts, execution logs, validation checklists
- **Entry Criteria**:
  - Code committed and versioned
  - Acceptance criteria defined
- **Exit Criteria**:
  - All critical tests passed
  - No blocking bugs remain
- **Test Independence**:
  - Developer executes tests; PO validates outcomes
- **Metrics Collected**:
  - Stories tested
  - Bugs per story
  - Average test execution time
- **Test Data Requirements**:
  - Sample products with varied attributes
- **Test Environment Requirements**:
  - Cloud-hosted backend with accessible endpoints
- **Deviations from Organizational Policy**:
  - Manual testing instead of full automation due to educational scope

---

## 📌 7. Budget and Schedule

- **Budget**: Not applicable (academic project)
- **Timeline**:
  - Planning and preparation: 1 day
  - Test execution: 4 days
  - Fixes and revalidation: 2 days
  - Total: 1 week within the 2-week sprint

---
