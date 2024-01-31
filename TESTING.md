| Area                                     | GAMP 5 Category | Applicability                                   | Testing Procedure                                                                     |
|-|-|-|-|  
| Validation and Testing                   | Category 3, 4, 5 | Automated Systems                               | - Develop and execute installation, operational, and performance qualification protocols |                                                                                                             | - Perform periodic revalidation based on risk                                         | - Document and investigate deviations, take CAPA if needed
| Data Integrity                           | Category 3, 4, 5 | Throughout the Lifecycle of Automated Systems   | - Implement data integrity controls like audit trails, electronic signatures per ALCOA+ |
|                                          |                 |                                                 | - Conduct data integrity risk assessment to identify critical data attributes and implement appropriate controls |                                                                                                             | - Perform periodic data integrity audits and review audit trails proactively  
| Audit Trail                              | Category 3, 4, 5 | Automated Systems                               | - Validate audit trail functionality as per applicable regulations (21 CFR Part 11, Annex 11 etc.)|                                                                                                             | - Review audit trails regularly during internal audits to identify unauthorized or improper activities|                                                                                                             | - Retain audit trails as per data retention SOPs in secure, immutable manner
| Validation Protocols                     | Category 3, 4, 5 | Automated Systems                               | - Develop detailed test protocols during specification phase |                                                                                                             | - Execute protocols during qualification testing                                                                                     | - Document and investigate any deviations, resolve through change control process
| Periodic Review                          | Category 3, 4, 5 | Ongoing Suitability and Effectiveness            | - Conduct periodic review at least annually based on risk                                             | - Assess functionality, calculate system metrics like availability, data integrity breaches etc.                                                                                                            | - Implement corrective actions for any issues identified
| Calibration and Maintenance              | Category 3      | Equipment and Instruments Integrated into System | - Follow vendor recommended calibration and maintenance procedures                                           | - Deviations to be documented and equipment removed from use if calibration fails. Take corrective action.  
| Software Configuration Management       | Category 4, 5    | Software Configurations                         | - Use a Configuration Management System for version control and manage software changes |                                                                                                             | - Any discrepancies in configuration to be addressed through change control process
| Compliance with Regulatory Requirements | Category 3, 4, 5 | Automated System Compliance                     | - Regularly review updates to regulations and assess impact on system                                                                                                   | - Implement required changes in system through change control process
| Validation of Automated System Upgrades  | Category 3, 4, 5 | Upgrades and Patches                            | - Test upgrades in staging environment. Deploy only after validation testing passes                                                                                                      | - Validation testing to include integration testing, user acceptance testing etc.

---

# Validation and Testing for Automated Systems (Category 3, 4, 5)

For Automated Systems falling under GAMP® Categories 3, 4, and 5, the validation and testing process involves the development and execution of installation, operational, and performance qualification protocols. Below are the key steps for this process:

## Installation Qualification (IQ)
- **Objective:** Verify the proper installation of hardware, software, and infrastructure according to vendor specifications.
- **Activities:**
  - Check system components and perform an inventory check.
  - Verify equipment calibration status.
  - Review system configurations and ensure security controls are in place.
  - Generate a baseline for operational qualification.

## Operational Qualification (OQ)
- **Objective:** Execute test cases to ensure that the software functions as per user requirements and specifications.
- **Activities:**
  - Test interface functionality and integration with other systems.
  - Validate editing, retrieving, processing, and reporting of data.
  - Test error handling, alarms, and audit trails.
  - Run tests in different operating environments if applicable.

## Performance Qualification (PQ)
- **Objective:** Validate the performance of the system under various conditions.
- **Activities:**
  - Perform stress and load testing to verify stability under peak conditions.
  - Determine system bottlenecks and hardware limitations.
  - Assess system behavior during failure scenarios.
  - Measure system metrics like uptime and response time.
  - Optimize system performance and configurations.

## General
- **Traceability:** Ensure traceability to requirements and risk assessment.
- **Data Integrity:** Test data integrity, reliability, and accuracy checks.
- **Deviations:** Address deviations, investigate failures, and document resolutions.
- **Verification:** Implement independent verification of testing as applicable.
- **Compliance:** Ensure compliance with applicable regulations (GxP, 21 CFR Part 11, etc.).


# Data Integrity for Automated Systems (Category 3, 4, 5)

For Automated Systems falling under GAMP® Categories 3, 4, and 5, ensuring data integrity is paramount. The process involves implementing data integrity controls throughout the lifecycle of the system, including audit trails and electronic signatures per ALCOA+ principles.

## Data Integrity Controls

- **Objective:** Implement robust controls to ensure data integrity and compliance with ALCOA+ principles.

- **Activities:**
  - **Audit Trails:** Establish comprehensive audit trails that capture relevant system activities, providing a detailed record of changes and interactions.
  - **Electronic Signatures:** Implement electronic signatures in accordance with ALCOA+ principles:
    - **Attributable:** Each action is traceable to an individual.
    - **Legible:** Signatures are clear and readable.
    - **Contemporaneous:** Actions are recorded in real-time.
    - **Original:** The record is the true and unaltered representation of the activity.
    - **Accurate:** Ensuring accuracy and reliability of the recorded information.

## Implementation Across the Lifecycle

- **Development Phase:**
  - Define and incorporate data integrity controls in the system design and coding.
  - Ensure that audit trail functionalities are well-integrated from the early stages.

- **Validation Phase:**
  - Verify the effectiveness of audit trails and electronic signatures during validation protocols.
  - Confirm that data integrity controls align with user requirements.

- **Operation Phase:**
  - Regularly review and monitor audit trails for any anomalies or deviations.
  - Conduct periodic checks to ensure electronic signatures remain compliant.
  - Address and investigate any issues related to data integrity promptly.

- **Change Management:**
  - Implement data integrity assessments for any system changes.
  - Ensure that modifications adhere to ALCOA+ principles.

## Compliance and Reporting

- **Documentation:** Maintain comprehensive documentation related to data integrity controls.
- **Reporting:** Include data integrity compliance in regular reports and audits.
- **Training:** Provide training to personnel involved in utilizing and maintaining data integrity controls.


# Audit Trail Validation for Automated Systems (Category 3, 4, 5)

For Automated Systems falling under GAMP® Categories 3, 4, and 5, the validation of audit trail functionality is a critical step to ensure compliance with applicable regulations, such as 21 CFR Part 11, Annex 11, and others.

## Objectives

- **Validate Audit Trail Functionality:** Confirm that the audit trail system operates effectively and meets the specified requirements.

- **Compliance with Regulations:** Ensure that the audit trail functionalities align with relevant regulations, including 21 CFR Part 11 and Annex 11.

## Validation Activities

- **Audit Trail Protocol:**
  - Develop a comprehensive audit trail validation protocol outlining the testing procedures and criteria.

- **Testing Procedures:**
  - Execute validation protocols to verify the proper functioning of audit trail functionalities.
  - Include tests to ensure that all critical events are captured and recorded accurately.

- **Electronic Signatures (if applicable):**
  - If electronic signatures are utilized, validate their integration with the audit trail system.

## Applicable Regulations

- **21 CFR Part 11:**
  - Ensure the audit trail complies with the requirements outlined in 21 CFR Part 11, which governs electronic records and signatures.

- **Annex 11:**
  - Align the audit trail functionalities with the principles outlined in Annex 11, specifically related to computerized systems.


# Validation Protocols for Automated Systems (Category 3, 4, 5)

For Automated Systems falling under GAMP® Categories 3, 4, and 5, the development of detailed test protocols during the specification phase is crucial to ensure the system's functionality aligns with user requirements.

## Objectives

- **Ensure Specification Compliance:** Develop test protocols to verify that the Automated Systems meet the specified user requirements.

- **Risk Mitigation:** Address identified risks through comprehensive testing during the specification phase.

## Validation Activities

- **Detailed Test Protocols:**
  - Develop detailed and exhaustive test protocols outlining specific test cases and procedures.
  
- **Specification Verification:**
  - Execute the test protocols to systematically verify that each aspect of the system adheres to the specifications.

- **Risk-Based Testing:**
  - Prioritize testing based on identified risks to focus on critical functionalities.

