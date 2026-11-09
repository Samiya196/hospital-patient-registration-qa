# Hospital Patient Registration – QA Testing Project

## Project Overview

This is a self-created Quality Assurance (QA) portfolio project based on a hospital patient registration workflow. It demonstrates requirement understanding, test planning, test case design, test data preparation, and end-to-end test scenario design.

The hypothetical system allows staff to register a patient, capture demographic and contact information, record an emergency contact, and generate an invoice after registration.

> **Project type:** Self-created portfolio project for demonstrating QA skills. This is not a production hospital application and is not affiliated with a real healthcare provider.

## Project Objectives

- Understand business requirements and break them into testable features.
- Identify positive, negative, mandatory-field, and boundary-value scenarios.
- Create detailed test cases with steps, test data, and expected results.
- Validate patient registration and invoice-generation workflows.
- Design end-to-end scenarios covering the complete registration journey.

## Modules Covered

| Module | Testing focus |
|---|---|
| Patient Registration | Registration workflow, required fields, successful submission, invalid input handling |
| Demographics | Patient details, field formats, mandatory fields, and validation |
| Contact Details | Phone, email, address, and contact-field validation |
| Emergency Contact | Emergency contact information and required-field validation |
| Invoice Generation | Invoice creation after registration and verification of invoice details |
| End-to-End Testing | Full patient registration journey through invoice generation |

## Test Deliverables

The test case workbook is organized into separate worksheets for each module, plus an E2E automation-scenario worksheet.

- Detailed test cases with preconditions, steps, test data, and expected results
- Priority and test-type classifications
- Execution status, actual result, defect ID, and comments fields
- End-to-end automation scenarios

### Test Case Workbook

After uploading the workbook to this repository under `Test-Cases/`, this link will work:

[Hospital Patient Registration Test Cases.xlsx](Test-Cases/Hospital_Patient_Registration_Test_Cases.xlsx)

If you use a different folder or filename, update the link to match.

## Suggested Test Approach

1. Review the high-level requirements and identify testable requirements.
2. Prepare test scenarios for each functional module.
3. Create positive, negative, and boundary-value test cases.
4. Prepare fictional test data for valid and invalid inputs.
5. Execute test cases and record actual results.
6. Log defects with reproducible steps, expected results, and actual results.
7. Validate the complete registration-to-invoice workflow using E2E scenarios.

## Tools and Skills Demonstrated

- Manual and functional testing
- Test scenario and test case design
- Positive, negative, and boundary testing
- Test data preparation
- Requirement analysis
- End-to-end testing concepts
- Microsoft Excel / Google Sheets for test documentation
- JIRA concepts for defect tracking
- Selenium with Python: planned enhancement for executable UI automation

> The E2E worksheet currently documents automation scenarios. It is not a completed or executable Selenium automation suite.

## Example End-to-End Flow

1. Open the patient registration workflow.
2. Enter valid patient demographic information.
3. Enter contact details.
4. Enter emergency contact details.
5. Submit the registration.
6. Verify successful patient registration.
7. Verify that an invoice is generated and its details are correct.

## Test Data and Privacy

All sample patient information used in this portfolio must be fictional. Do not upload real patient records, protected health information (PHI), personal contact details, credentials, or confidential employer documents to this public repository.

## Project Status

**Current scope:** Requirements-based test documentation and E2E scenario design.

**Possible future enhancements:**
- Add a sample requirements document.
- Add sample defect reports and an execution summary.
- Implement selected UI scenarios using Selenium and Python.
- Add screenshots or execution evidence using fictional data.

## Disclaimer

This project is intended solely for learning and interview portfolio demonstration. It does not represent testing performed for an actual hospital, and it contains no real patient information.
