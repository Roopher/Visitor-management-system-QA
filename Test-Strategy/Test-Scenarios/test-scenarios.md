# Test Scenarios

## 1. Overview

This document contains the high-level test scenarios identified for the Visitor Management System.

The scenarios are based on the core workflows and functionalities available within the system. Detailed test cases will be developed from these scenarios.

---

## 2. User Authentication and Roles

| ID     | Test Scenario                                                                 | Priority |
| ------ | ----------------------------------------------------------------------------- | -------- |
| TS-001 | Verify that an authorized user can log into the system                        | High     |
| TS-002 | Verify that invalid login credentials are rejected                            | High     |
| TS-003 | Verify that required authentication fields are validated                      | High     |
| TS-004 | Verify that users can access functionality based on their assigned roles      | High     |
| TS-005 | Verify that restricted functionality cannot be accessed by unauthorized roles | High     |
| TS-006 | Verify that users can log out successfully                                    | Medium   |

---

## 3. Visitor Registration

| ID     | Test Scenario                                                              | Priority |
| ------ | -------------------------------------------------------------------------- | -------- |
| TS-007 | Verify that a user can successfully register a visitor                     | High     |
| TS-008 | Verify that mandatory visitor information is validated                     | High     |
| TS-009 | Verify that invalid visitor information is rejected                        | High     |
| TS-010 | Verify that incomplete visitor registration cannot be submitted            | High     |
| TS-011 | Verify that a successfully registered visitor is stored in the system      | High     |
| TS-012 | Verify that the system handles duplicate visitor information appropriately | Medium   |

---

## 4. Calendar and Scheduling

| ID     | Test Scenario                                                                              | Priority |
| ------ | ------------------------------------------------------------------------------------------ | -------- |
| TS-013 | Verify that a visitor appointment can be scheduled                                         | High     |
| TS-014 | Verify that scheduled visitor information appears correctly on the calendar                | High     |
| TS-015 | Verify that the correct date and time are associated with a scheduled visit                | High     |
| TS-016 | Verify that users can view scheduled visitor appointments                                  | High     |
| TS-017 | Verify that appointment information is displayed accurately                                | Medium   |
| TS-018 | Verify that the system handles conflicting or invalid scheduling information appropriately | Medium   |

---

## 5. Visitor Approval

| ID     | Test Scenario                                                                | Priority |
| ------ | ---------------------------------------------------------------------------- | -------- |
| TS-019 | Verify that a pending visitor request can be reviewed                        | High     |
| TS-020 | Verify that an authorized user can approve a visitor request                 | High     |
| TS-021 | Verify that an authorized user can reject a visitor request where applicable | High     |
| TS-022 | Verify that the visitor status changes appropriately after approval          | High     |
| TS-023 | Verify that unauthorized users cannot perform restricted approval actions    | High     |
| TS-024 | Verify that the approved visitor information remains accurate after approval | Medium   |

---

## 6. QR Code Functionality

| ID     | Test Scenario                                                               | Priority |
| ------ | --------------------------------------------------------------------------- | -------- |
| TS-025 | Verify that a QR code is generated for an eligible visitor or appointment   | High     |
| TS-026 | Verify that the generated QR code corresponds to the correct visitor record | High     |
| TS-027 | Verify that the QR code can be scanned successfully                         | High     |
| TS-028 | Verify that scanning the QR code retrieves the expected visitor information | High     |
| TS-029 | Verify that an invalid or unrecognized QR code is handled appropriately     | Medium   |
| TS-030 | Verify that QR code functionality respects applicable user permissions      | High     |

---

## 7. Visitor Check-In

| ID     | Test Scenario                                                                           | Priority |
| ------ | --------------------------------------------------------------------------------------- | -------- |
| TS-031 | Verify that an eligible visitor can be checked in                                       | High     |
| TS-032 | Verify that visitor information is displayed correctly during check-in                  | High     |
| TS-033 | Verify that the visitor status is updated after successful check-in                     | High     |
| TS-034 | Verify that unauthorized users cannot perform restricted check-in actions               | High     |
| TS-035 | Verify that the system handles invalid or incomplete check-in information appropriately | Medium   |

---

## 8. Visitor Tracking

| ID     | Test Scenario                                                                   | Priority |
| ------ | ------------------------------------------------------------------------------- | -------- |
| TS-036 | Verify that visitor activity can be tracked                                     | High     |
| TS-037 | Verify that visitor status reflects the appropriate stage of the visit          | High     |
| TS-038 | Verify that authorized users can view visitor tracking information              | High     |
| TS-039 | Verify that tracking information corresponds to the correct visitor             | High     |
| TS-040 | Verify that visitor tracking information is updated when relevant actions occur | High     |

---

## 9. Search and Retrieval

| ID     | Test Scenario                                                                  | Priority |
| ------ | ------------------------------------------------------------------------------ | -------- |
| TS-041 | Verify that users can search for visitor records                               | High     |
| TS-042 | Verify that search results correspond to the entered search criteria           | High     |
| TS-043 | Verify that the system handles searches with no matching results appropriately | Medium   |
| TS-044 | Verify that authorized users can retrieve relevant visitor information         | High     |
| TS-045 | Verify that search and retrieval respect user access permissions               | High     |

---

## 10. Usability and Interface

| ID     | Test Scenario                                                             | Priority |
| ------ | ------------------------------------------------------------------------- | -------- |
| TS-046 | Verify that users can navigate between major visitor management functions | Medium   |
| TS-047 | Verify that system labels and instructions are clear                      | Medium   |
| TS-048 | Verify that important system actions provide appropriate feedback         | Medium   |
| TS-049 | Verify that forms and workflows are logically organized                   | Medium   |
| TS-050 | Verify that information is presented consistently across relevant screens | Medium   |

---

## 11. Regression Testing

| ID     | Test Scenario                                                                      | Priority |
| ------ | ---------------------------------------------------------------------------------- | -------- |
| TS-051 | Verify that visitor registration continues to function after system changes        | High     |
| TS-052 | Verify that scheduling and calendar functionality remains functional after changes | High     |
| TS-053 | Verify that approval workflows remain functional after changes                     | High     |
| TS-054 | Verify that QR code functionality remains functional after changes                 | High     |
| TS-055 | Verify that check-in and tracking functionality remains functional after changes   | High     |
| TS-056 | Verify that search functionality remains functional after changes                  | High     |
| TS-057 | Verify that role-based access continues to work correctly after changes            | High     |

---

## Summary

A total of **57 high-level test scenarios** have been documented across the core functional areas of the Visitor Management System.

These scenarios provide the basis for detailed test case design, execution, defect identification, and regression testing.

The scenarios have been generalized for portfolio purposes to protect confidential project information.
