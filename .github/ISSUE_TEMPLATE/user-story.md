---
name: User Story
about: Create a user story
title: ''
labels: ''
assignees: ''
---

**As a** customer
**I need** the ability to view product details
**So that** I can decide whether to make a purchase

### Details and Assumptions
* Products have name, price, description
* All products have a unique ID

### Acceptance Criteria

```gherkin
Given a product exists in the catalog
When I request the product by its ID
Then the product details are returned successfully
```
