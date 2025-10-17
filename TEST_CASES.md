# 🧪 Test Cases – Agile Final Project: E-commerce Product Catalog

This document outlines the test cases created to validate key functionalities of the backend product catalog system. Each test case follows a standard template and is linked to a specific requirement.

---

### Test Case ID: TC-001
**Title**: Create a new product in the catalog  
**Requirement ID**: REQ-001  
**Preconditions**: Admin user is authenticated  
**Test Steps**:
1. Navigate to the product creation endpoint
2. Submit a POST request with valid product data (name, price, description)  
**Expected Result**: Product is successfully created and returned with a unique ID  
**Test Type**: Functional  
**Priority**: High  
**Status**: Planned

---

### Test Case ID: TC-002
**Title**: Retrieve product details by ID  
**Requirement ID**: REQ-002  
**Preconditions**: Product exists in the catalog  
**Test Steps**:
1. Send a GET request to `/products/{id}`
2. Observe the response payload  
**Expected Result**: Product details are returned with correct attributes  
**Test Type**: Functional  
**Priority**: High  
**Status**: Planned

---

### Test Case ID: TC-003
**Title**: Update product information  
**Requirement ID**: REQ-003  
**Preconditions**: Product exists and admin is authenticated  
**Test Steps**:
1. Send a PUT request with updated product data  
2. Verify response status and updated fields  
**Expected Result**: Product is updated and reflects new data  
**Test Type**: Functional  
**Priority**: Medium  
**Status**: Planned

---

### Test Case ID: TC-004
**Title**: Like a product  
**Requirement ID**: REQ-005  
**Preconditions**: Product exists and user is authenticated  
**Test Steps**:
1. Send a POST request to `/products/{id}/like`
2. Check response and updated like count  
**Expected Result**: Product receives a like and count is incremented  
**Test Type**: Functional  
**Priority**: Low  
**Status**: Planned

---

### Test Case ID: TC-005
**Title**: Deploy catalog to cloud  
**Requirement ID**: REQ-009  
**Preconditions**: Application is packaged and ready  
**Test Steps**:
1. Trigger deployment pipeline  
2. Monitor logs and endpoint availability  
**Expected Result**: Application is deployed and accessible via cloud URL  
**Test Type**: Integration  
**Priority**: High  
**Status**: Planned

---
