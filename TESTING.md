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

# Periodic Review for Automated Systems (Category 3, 4, 5)

For Automated Systems falling under GAMP® Categories 3, 4, and 5, conducting periodic reviews is essential to assess ongoing suitability and effectiveness, with a frequency of at least annually.

## Objectives

- **Continuous Assessment:** Regularly evaluate the performance and compliance of the Automated Systems.

- **Risk-Based Approach:** Conduct the review based on identified risks and potential impact.

## Review Activities

- **Annual Assessment:**
  - Perform a thorough review of the system at least once a year.

- **Risk Reassessment:**
  - Reassess risks associated with the system and its components.

- **Compliance Check:**
  - Verify ongoing compliance with relevant regulations and standards.

- **Effectiveness Evaluation:**
  - Evaluate the effectiveness of implemented controls and measures.

# Calibration and Maintenance for Category 3 Automated Systems

## Objective

The objective of the Calibration and Maintenance process for Category 3 Automated Systems is to ensure the reliable and accurate performance of integrated equipment and instruments throughout their operational lifecycle. This involves adherence to vendor-recommended procedures, preventive measures, and continuous improvement initiatives.

## Test Cases

1. **Calibration Procedures:**
   - **Objective:** To verify compliance with vendor-recommended calibration procedures.
   - **Test Case:** Execute the calibration process according to the vendor guidelines.
   - **Expected Result:** Calibration activities align with specified vendor procedures.

2. **Maintenance Procedures:**
   - **Objective:** To ensure adherence to vendor-recommended maintenance procedures.
   - **Test Case:** Implement preventive maintenance measures as per vendor guidelines.
   - **Expected Result:** Preventive maintenance activities are in line with vendor specifications.

3. **Timely Inspections:**
   - **Objective:** To confirm the implementation of regular inspections for identifying potential issues.
   - **Test Case:** Conduct a mock inspection to identify and address hypothetical issues.
   - **Expected Result:** Inspection process identifies and addresses simulated issues effectively.

4. **Record Keeping:**
   - **Objective:** To validate the maintenance of comprehensive records for all calibration and maintenance activities.
   - **Test Case:** Review records for a sample period to ensure completeness and accuracy.
   - **Expected Result:** Records provide a clear and accurate history of all maintenance and calibration activities.

5. **Compliance with Vendor Specifications:**
   - **Objective:** To verify that all activities align with the specifications provided by the vendors.
   - **Test Case:** Cross-check recent activities against vendor specifications.
   - **Expected Result:** Activities are in accordance with the specified vendor guidelines.

6. **Continuous Improvement Initiatives:**
   - **Objective:** To assess the integration of feedback into continuous improvement measures.
   - **Test Case:** Analyze recent maintenance and calibration feedback and identify implemented improvements.
   - **Expected Result:** Feedback has been incorporated into optimization measures.

# Software Configuration Management for Category 3, 4, 5 Automated Systems

## Objective

The objective of Software Configuration Management is to establish robust procedures for managing software configurations, ensuring version control, release management, and timely identification and rectification of discrepancies. This process aims to maintain the integrity and traceability of the software components throughout the lifecycle of Category 3, 4, and 5 Automated Systems.

## Test Cases

1. **Version Control:**
   - **Objective:** Verify the implementation of version control measures for software components.
   - **Test Case:** Modify a software component and validate the system's ability to track and control the version.
   - **Expected Result:** The system accurately identifies and controls the modified software version.

2. **Release Management:**
   - **Objective:** Ensure effective release management procedures are in place.
   - **Test Case:** Simulate a software release, including documentation updates and version tracking.
   - **Expected Result:** The release process is executed seamlessly with updated documentation and version tracking.

3. **Discrepancy Identification:**
   - **Objective:** Validate the capability to identify discrepancies in software configurations.
   - **Test Case:** Introduce a deliberate discrepancy in the software configuration and check for detection.
   - **Expected Result:** The system promptly identifies and reports the introduced discrepancy.

4. **Discrepancy Rectification:**
   - **Objective:** Confirm the process for rectifying identified discrepancies.
   - **Test Case:** Introduce a discrepancy and validate the correction process.
   - **Expected Result:** Discrepancies are rectified following established procedures.

5. **Change Management Board:**
   - **Objective:** Ensure the existence and functionality of a Change Management Board.
   - **Test Case:** Simulate a change request and validate the board's review and decision-making process.
   - **Expected Result:** Change requests are reviewed, categorized, and decisions are documented.

6. **Documentation Updates:**
   - **Objective:** Validate the procedure for updating documentation after software changes.
   - **Test Case:** Implement a software change and verify the accuracy and completeness of updated documentation.
   - **Expected Result:** Documentation is updated accurately to reflect software changes.

7. **Security Measures:**
   - **Objective:** Confirm the implementation of security measures for software configurations.
   - **Test Case:** Attempt unauthorized access to software configurations and assess the system's response.
   - **Expected Result:** Unauthorized access attempts are detected and prevented.

8. **Periodic Audits:**
   - **Objective:** Ensure routine audits are conducted on software configurations.
   - **Test Case:** Simulate a periodic audit and verify adherence to configuration management procedures.
   - **Expected Result:** The audit identifies compliance with established configuration management practices.

# Validation of Automated System Upgrades

## Objective

The objective of the Validation of Automated System Upgrades is to ensure that upgrades and patches applied to the automated system do not adversely impact the validated state. This process aims to validate the compatibility, functionality, and performance of the system following upgrades, maintaining compliance with regulatory requirements.

## Test Cases

1. **Upgrade Impact Assessment:**
   - **Objective:** Evaluate the impact of an automated system upgrade on the existing validated state.
   - **Test Case:** Apply a system upgrade and assess its impact on critical functions and data integrity.
   - **Expected Result:** The impact assessment identifies any deviations from the validated state, and necessary actions are determined.

2. **Validation Protocol Execution:**
   - **Objective:** Execute validation protocols specific to the applied upgrade.
   - **Test Case:** Develop and execute validation protocols tailored for the upgraded system components.
   - **Expected Result:** Validation protocols confirm the continued compliance and functionality of the upgraded system.

3. **Regression Testing:**
   - **Objective:** Ensure that regression testing is performed post-upgrade.
   - **Test Case:** Execute regression tests to verify that existing functionalities are not adversely affected by the upgrade.
   - **Expected Result:** Regression testing validates the stability and reliability of the system after the upgrade.

4. **Backup and Recovery Validation:**
   - **Objective:** Validate the effectiveness of backup and recovery procedures post-upgrade.
   - **Test Case:** Implement a simulated failure scenario and assess the system's recovery using backup procedures.
   - **Expected Result:** Backup and recovery procedures successfully restore the system to its pre-failure state.

5. **Validation Documentation Update:**
   - **Objective:** Ensure documentation is updated to reflect the changes introduced by the upgrade.
   - **Test Case:** Validate the accuracy and completeness of documentation after the upgrade.
   - **Expected Result:** Documentation reflects the upgraded system, including changes in configurations and functionalities.

6. **User Training and Awareness:**
   - **Objective:** Confirm that users are trained and made aware of changes resulting from the upgrade.
   - **Test Case:** Assess the effectiveness of user training programs and awareness campaigns related to the upgrade.
   - **Expected Result:** Users demonstrate understanding and proficiency in utilizing the upgraded system.

7. **Periodic Review Post-Upgrade:**
   - **Objective:** Conduct a periodic review after the upgrade to assess the system's ongoing suitability and effectiveness.
   - **Test Case:** Perform a review at defined intervals to ensure the continued validation of the upgraded system.
   - **Expected Result:** Periodic reviews confirm the sustained compliance and effectiveness of the upgraded system.

8. **Change Control Verification:**
   - **Objective:** Validate that the upgrade process adheres to established change control procedures.
   - **Test Case:** Evaluate the upgrade against documented change control processes.
   - **Expected Result:** The change control process is followed, and all relevant documentation is updated.

## Examples of Successful Validation Following System Upgrades

1. **Software Version Update:**
   - **Scenario:** An automated system utilized a new software version.
   - **Outcome:** Validation protocols were executed, and the impact assessment showed no critical deviations. Documentation was updated, and user training ensured a smooth transition.

2. **Hardware Architecture Changes:**
   - **Scenario:** Changes were made to the hardware architecture of the automated system.
   - **Outcome:** Rigorous testing confirmed system stability post-upgrade. The change control process was followed, and periodic reviews affirmed ongoing compliance.

3. **Integration of New Functionality:**
   - **Scenario:** New functionality was added to the system through an upgrade.
   - **Outcome:** User training covered the new features, and validation protocols demonstrated that existing functionalities were not compromised.

4. **Security Patch Implementation:**
   - **Scenario:** A security patch was applied to address vulnerabilities.
   - **Outcome:** Impact assessment revealed no adverse effects on system functionality. Regression testing confirmed the patch's successful implementation.

# 17. Electronic Records and Signatures

## Objective

The objective of managing electronic records and signatures is to meet regulatory requirements, ensuring the integrity, authenticity, and security of electronic records throughout their lifecycle. Additionally, robust controls are implemented to prevent unauthorized access to electronic records.

## Test Cases

### Electronic Records Management

1. **Regulatory Compliance:**
   - **Objective:** Ensure electronic records adhere to relevant regulatory requirements (e.g., 21 CFR Part 11).
   - **Test Case:** Review electronic records to verify compliance with regulatory specifications.
   - **Expected Result:** Electronic records meet the criteria outlined in applicable regulations.

2. **Record Integrity:**
   - **Objective:** Confirm the integrity of electronic records throughout their lifecycle.
   - **Test Case:** Perform periodic checks on electronic records to detect and rectify any signs of data corruption or unauthorized alterations.
   - **Expected Result:** Electronic records maintain integrity, and any anomalies are promptly addressed.

3. **Data Retention and Archiving:**
   - **Objective:** Validate the procedures for data retention and archiving of electronic records.
   - **Test Case:** Execute the data archiving process and verify the retrievability of archived records.
   - **Expected Result:** Archiving procedures are effective, and archived records are accessible as needed.

### Electronic Signatures Management

4. **Authentication of Electronic Signatures:**
   - **Objective:** Ensure the authentication of electronic signatures to verify the identity of signatories.
   - **Test Case:** Review electronic signatures against established authentication methods.
   - **Expected Result:** Electronic signatures are reliably linked to the authorized individuals.

5. **Non-Repudiation:**
   - **Objective:** Verify that electronic signatures provide non-repudiation, preventing signatories from denying their actions.
   - **Test Case:** Evaluate the system's ability to track and associate electronic signatures with specific actions.
   - **Expected Result:** Non-repudiation measures are effective, ensuring accountability.

6. **Electronic Signature Timestamps:**
   - **Objective:** Validate the inclusion of timestamps in electronic signatures to record the date and time of signing.
   - **Test Case:** Review electronic signatures to confirm the accurate recording of timestamps.
   - **Expected Result:** Electronic signatures include reliable timestamps for audit trail purposes.

### Controls Against Unauthorized Access

7. **Access Control Policies:**
   - **Objective:** Ensure the implementation of access control policies for electronic records.
   - **Test Case:** Review and validate access control settings, including user roles and permissions.
   - **Expected Result:** Access control policies prevent unauthorized users from accessing sensitive electronic records.

8. **Encryption Measures:**
   - **Objective:** Verify the use of encryption to protect electronic records from unauthorized interception.
   - **Test Case:** Assess the encryption mechanisms in place for stored and transmitted electronic records.
   - **Expected Result:** Encryption safeguards electronic records against unauthorized access during storage and transmission.

9. **Audit Trail Monitoring:**
   - **Objective:** Confirm that audit trails are actively monitored to detect and respond to unauthorized access attempts.
   - **Test Case:** Simulate unauthorized access attempts and verify the effectiveness of the audit trail in capturing such events.
   - **Expected Result:** Unauthorized access attempts trigger alerts, and appropriate actions are taken.

## Performance Monitoring

### Performance Metrics and Objectives

10. **System Response Time:**
    - **Objective:** Monitor and maintain optimal system response times for accessing electronic records.
    - **Test Case:** Measure the time taken to access electronic records under normal operating conditions.
    - **Expected Result:** System response times meet predefined performance objectives.

11. **Scalability Testing:**
    - **Objective:** Assess the system's scalability to handle an increasing volume of electronic records.
    - **Test Case:** Gradually increase the volume of electronic records and evaluate system performance.
    - **Expected Result:** The system scales efficiently without significant degradation in performance.

12. **Availability and Uptime:**
    - **Objective:** Ensure high availability and uptime of the system for continuous access to electronic records.
    - **Test Case:** Monitor system availability over an extended period, including peak usage times.
    - **Expected Result:** The system remains consistently available, meeting defined uptime targets.

13. **Data Backup and Recovery:**
    - **Objective:** Validate the effectiveness of data backup and recovery procedures.
    - **Test Case:** Simulate a data loss scenario and execute the recovery process.
    - **Expected Result:** Data is successfully restored, ensuring minimal impact on electronic records.

These test cases collectively aim to verify the compliance, security, and performance aspects of electronic records and signatures within the automated system.

# 18. Validation Traceability

## Objective

The objective of validation traceability is to ensure a clear and consistent linkage between user requirements, design specifications, and test cases throughout the validation process. This practice facilitates transparency, accountability, and the ability to demonstrate that all requirements are met through well-defined testing procedures.

## Test Cases

1. **Traceability Matrix Creation:**
   - **Objective:** Ensure the creation of a comprehensive traceability matrix linking user requirements, design specifications, and corresponding test cases.
   - **Test Case:** Review the traceability matrix to verify that each requirement is clearly mapped to design elements and associated test cases.
   - **Expected Result:** The traceability matrix is well-structured, covering all relevant requirements and test cases.

2. **Traceability Tool Usage:**
   - **Objective:** Validate the effectiveness of traceability tools or software in maintaining the linkage between requirements, design, and testing.
   - **Test Case:** Utilize the traceability tool to navigate through user requirements, design specifications, and associated test cases.
   - **Expected Result:** The traceability tool provides an efficient and accurate means of tracking traceability relationships.

3. **Bi-Directional Traceability:**
   - **Objective:** Confirm that traceability is bi-directional, allowing for easy navigation from requirements to tests and vice versa.
   - **Test Case:** Select a random set of requirements and verify the corresponding links to design specifications and test cases. Repeat the process in reverse.
   - **Expected Result:** Bi-directional traceability is evident, ensuring a complete linkage between requirements, design, and tests.

4. **Impact Analysis:**
   - **Objective:** Assess the system's ability to perform impact analysis when changes occur in user requirements or design.
   - **Test Case:** Introduce a simulated change in a user requirement or design element and observe how the system identifies and communicates the impact on associated test cases.
   - **Expected Result:** The system accurately identifies and communicates the impact of changes, aiding in decision-making during the validation process.

5. **Requirement Coverage:**
   - **Objective:** Verify that all user requirements are covered by corresponding test cases.
   - **Test Case:** Cross-reference each user requirement with the associated test cases to confirm full coverage.
   - **Expected Result:** Test cases exist for each user requirement, ensuring comprehensive coverage.

6. **Traceability During Audits:**
   - **Objective:** Confirm that traceability is readily accessible and visible during internal or external audits.
   - **Test Case:** Simulate an audit scenario and request traceability information for a specific set of requirements, designs, and tests.
   - **Expected Result:** Traceability information is promptly provided, demonstrating transparency and adherence to validation processes.

7. **Demonstrate a Crucial Traceability Instance:**
   - **Objective:** Illustrate a specific instance where traceability played a crucial role in ensuring the system's compliance.
   - **Test Case:** Present a real-world scenario where traceability was instrumental in identifying and rectifying a potential issue or ensuring a specific requirement was met.
   - **Expected Result:** The demonstration highlights the tangible benefits of traceability in maintaining compliance and addressing challenges effectively.

The execution of these test cases aims to validate the effectiveness of the traceability process, ensuring that all elements of the system, from user requirements to design specifications and test cases, are intricately linked and easily traceable throughout the validation lifecycle.

# 19. Risk Management

## Objective

The objective of risk management in the context of automated systems is to identify, assess, prioritize, and mitigate potential risks that may impact the system's functionality, data integrity, and compliance with regulatory requirements. The goal is to establish a systematic approach to proactively manage and minimize risks throughout the system lifecycle.

## Test Cases

1. **Risk Identification Methodology:**
   - **Objective:** Assess the methodology used for identifying risks related to automated systems.
   - **Test Case:** Review documentation and interview key personnel to understand the processes employed to identify potential risks.
   - **Expected Result:** Clearly defined methodologies for identifying risks, involving stakeholders and subject matter experts.

2. **Risk Assessment Process:**
   - **Objective:** Evaluate the process of assessing identified risks.
   - **Test Case:** Select a sample of identified risks and review the assessment criteria, considering factors such as impact, likelihood, and detectability.
   - **Expected Result:** The risk assessment process is well-documented and consistently applied, considering both qualitative and quantitative aspects.

3. **Risk Prioritization Criteria:**
   - **Objective:** Verify the criteria used to prioritize identified risks.
   - **Test Case:** Examine the documentation to understand how risks are prioritized based on their potential impact and likelihood.
   - **Expected Result:** Clearly defined criteria for prioritizing risks, ensuring focus on the most critical aspects.

4. **Risk Mitigation Strategies:**
   - **Objective:** Assess the strategies in place for mitigating identified risks.
   - **Test Case:** Review risk mitigation plans and interview stakeholders to understand the actions taken to address specific risks.
   - **Expected Result:** Well-documented and effective risk mitigation strategies tailored to the nature and severity of each identified risk.

5. **Risk Monitoring and Review:**
   - **Objective:** Evaluate the ongoing monitoring and review of identified risks.
   - **Test Case:** Review records and reports to assess how regularly risks are monitored and whether adjustments are made based on changing circumstances.
   - **Expected Result:** Evidence of regular monitoring and periodic reviews, with adjustments to risk management plans as necessary.

6. **Documentation of Risk Management:**
   - **Objective:** Verify the completeness and accuracy of documentation related to risk management.
   - **Test Case:** Review risk management documents to ensure that all identified risks, assessments, prioritizations, and mitigation plans are well-documented.
   - **Expected Result:** Comprehensive and well-maintained documentation providing a clear overview of the risk management process.

# 20. Documentation Retrieval and Archiving

## Objective

The objective of this section is to assess the efficiency of retrieving relevant documentation during an audit and to evaluate the procedures in place for archiving documentation. Additionally, the objective is to verify the existence of safeguards that ensure the integrity and accessibility of archived documentation.

## Test Cases

1. **Documentation Retrieval Speed:**
   - **Objective:** Determine how quickly relevant documentation can be retrieved during an audit.
   - **Test Case:** Simulate an audit scenario by requesting specific documents and measure the time it takes to retrieve them.
   - **Expected Result:** Documentation is promptly retrieved, demonstrating an efficient and organized retrieval process.

2. **Archiving Procedures Review:**
   - **Objective:** Evaluate the procedures in place for archiving documentation.
   - **Test Case:** Review documentation that outlines the archiving procedures, including versioning, approvals, and storage locations.
   - **Expected Result:** Well-documented archiving procedures are in place, ensuring systematic and organized archiving.

3. **Safeguards for Document Integrity:**
   - **Objective:** Verify the existence of safeguards to ensure the integrity of archived documentation.
   - **Test Case:** Assess the documented safeguards in place, such as encryption, access controls, and periodic integrity checks.
   - **Expected Result:** Clearly defined safeguards are documented, providing assurance of document integrity.

4. **Accessibility of Archived Documentation:**
   - **Objective:** Evaluate the accessibility of archived documentation.
   - **Test Case:** Attempt to access randomly selected archived documents to ensure they are readily available when needed.
   - **Expected Result:** Archived documentation is easily accessible, promoting efficient retrieval during audits or other relevant scenarios.

5. **Archiving Storage Environment:**
   - **Objective:** Assess the storage environment for archived documentation.
   - **Test Case:** Review the storage conditions, including physical and digital storage, to ensure they meet standards for preservation.
   - **Expected Result:** Storage conditions align with best practices, ensuring the longevity and preservation of archived documentation.

6. **Verification of Archiving Compliance:**
   - **Objective:** Confirm that archiving procedures comply with relevant standards and regulatory requirements.
   - **Test Case:** Review a sample of archived documents to ensure compliance with established archiving procedures.
   - **Expected Result:** Archived documentation complies with relevant standards, ensuring consistency and conformity.

7. **Documentation Retrieval Track Record:**
   - **Objective:** Assess the historical track record of documentation retrieval during previous audits.
   - **Test Case:** Interview personnel involved in past audits to gather feedback on the speed and efficiency of documentation retrieval.
   - **Expected Result:** Positive feedback indicates a consistent and reliable track record of documentation retrieval.

8. **Periodic Archiving Audits:**
   - **Objective:** Verify the existence of periodic audits to assess the effectiveness of the archiving process.
   - **Test Case:** Review records of periodic audits conducted on archived documentation.
   - **Expected Result:** Evidence of regular audits, demonstrating a commitment to maintaining the quality and integrity of archived documentation.

The execution of these test cases aims to ensure that relevant documentation can be efficiently retrieved during audits, archiving procedures are systematic, and safeguards are in place to maintain the integrity and accessibility of archived documentation.

# 21. Validation of Software Tools

## Objective

The objective of this section is to assess how software tools used in the development and maintenance of the automated system are validated. Additionally, the objective is to gain insights into examples of successfully validated tools and their impact on system performance.

## Test Cases

1. **Validation Procedure Review:**
   - **Objective:** Evaluate the documented procedure for validating software tools.
   - **Test Case:** Review the procedure that outlines how software tools are validated, including the criteria, testing methods, and validation frequency.
   - **Expected Result:** Well-defined validation procedures are in place, ensuring a systematic approach to software tool validation.

2. **Examples of Validated Software Tools:**
   - **Objective:** Identify examples of software tools that have been successfully validated.
   - **Test Case:** Request a list of software tools used in the development and maintenance of the automated system and assess their validation status.
   - **Expected Result:** A comprehensive list of validated software tools is provided, showcasing a commitment to ensuring the reliability of tools.

3. **Impact Assessment on System Performance:**
   - **Objective:** Understand the impact of validated software tools on the performance of the automated system.
   - **Test Case:** Interview relevant personnel to gather insights into how the validation of software tools has positively influenced system performance.
   - **Expected Result:** Positive feedback is received, highlighting instances where validated tools have contributed to enhanced system performance.

4. **Validation Records for Software Tools:**
   - **Objective:** Verify the existence of validation records for each software tool.
   - **Test Case:** Review the documentation that serves as evidence of successful validation for selected software tools.
   - **Expected Result:** Validation records are available, demonstrating a thorough validation process for each software tool.

5. **Tool Impact Analysis:**
   - **Objective:** Conduct an impact analysis to understand how each validated software tool contributes to the overall functionality and efficiency of the automated system.
   - **Test Case:** Analyze the documented impact assessment for each validated software tool.
   - **Expected Result:** A clear understanding of the positive impact of each tool on system development and maintenance.

6. **Regular Tool Validation Updates:**
   - **Objective:** Confirm the frequency of updates to software tool validations.
   - **Test Case:** Review records to determine how often software tool validations are updated to align with changes in tool versions or functionalities.
   - **Expected Result:** Evidence of regular updates to software tool validations, indicating a proactive approach to maintaining validation status.

7. **Mitigation of Tool-Related Issues:**
   - **Objective:** Assess the documented procedures for mitigating issues related to software tools.
   - **Test Case:** Review procedures outlining how issues arising from software tools are identified, reported, and addressed.
   - **Expected Result:** Well-documented procedures are in place to address and mitigate issues related to software tools promptly.

8. **Feedback Mechanism from End Users:**
   - **Objective:** Gather feedback from end users regarding the usability and effectiveness of validated software tools.
   - **Test Case:** Conduct interviews or surveys with end users to collect feedback on their experience with validated tools.
   - **Expected Result:** Positive feedback indicates that validated tools are user-friendly and contribute positively to system operations.

The execution of these test cases aims to ensure that software tools used in the development and maintenance of the automated system are systematically validated, contributing positively to system performance and reliability.

# 22. Interfacing with Other Systems

## Objective

The objective of this section is to understand how the automated system interfaces with other systems and how the integrity of data exchanges is ensured. Additionally, the objective is to gain insights into the measures in place to handle changes or updates in interfacing systems.

## Test Cases

1. **Interfacing Mechanism Documentation:**
   - **Objective:** Evaluate the documentation outlining how the automated system interfaces with other systems.
   - **Test Case:** Review documentation, such as system architecture diagrams and interface specifications, to understand the mechanism of interfacing.
   - **Expected Result:** Clearly documented information detailing how the automated system interacts with other systems.

2. **Data Exchange Integrity Measures:**
   - **Objective:** Assess the measures implemented to ensure the integrity of data exchanges between the automated system and interfacing systems.
   - **Test Case:** Review documented procedures and protocols related to data exchange to verify the existence of integrity checks.
   - **Expected Result:** Clearly defined measures are in place to ensure the accuracy and integrity of data exchanged between systems.

3. **Handling Changes or Updates:**
   - **Objective:** Understand the procedures in place for handling changes or updates in interfacing systems.
   - **Test Case:** Review documented change control procedures specifically addressing changes or updates in interfacing systems.
   - **Expected Result:** Well-defined procedures are available, outlining how changes or updates in interfacing systems are identified, assessed, and implemented.

4. **Impact Assessment for Interfacing Changes:**
   - **Objective:** Verify the existence of an impact assessment process for changes in interfacing systems.
   - **Test Case:** Review documentation to confirm that impact assessments are conducted before implementing changes in interfacing systems.
   - **Expected Result:** Evidence of impact assessments, ensuring that potential effects on data exchanges and system functionality are thoroughly evaluated.

5. **Testing Protocols for Interface Functionality:**
   - **Objective:** Assess the testing protocols in place to validate the functionality of interfaces after changes or updates.
   - **Test Case:** Review testing protocols specifically designed for interfacing functionality.
   - **Expected Result:** Clearly defined testing procedures that ensure interfaces perform accurately after changes or updates.

6. **Communication Mechanism with External Systems:**
   - **Objective:** Understand the communication mechanism between the automated system and external systems.
   - **Test Case:** Interview relevant personnel to gather insights into the communication protocols and mechanisms.
   - **Expected Result:** Clear communication mechanisms are established and understood by personnel involved in interfacing.

7. **Monitoring and Surveillance of Interfaces:**
   - **Objective:** Verify the existence of monitoring and surveillance mechanisms for interfacing systems.
   - **Test Case:** Review documented procedures for continuous monitoring of interfaces to identify any anomalies.
   - **Expected Result:** Evidence of ongoing monitoring practices to detect and address issues promptly.

8. **Documentation for Interface Changes:**
   - **Objective:** Confirm the documentation practices for changes made to interfacing systems.
   - **Test Case:** Review records to ensure that changes in interfacing systems are thoroughly documented.
   - **Expected Result:** Documentation evidencing comprehensive records for all changes made to interfacing systems.

The execution of these test cases aims to ensure that the automated system's interfacing mechanisms are well-documented, and measures are in place to maintain the integrity of data exchanges, handle changes effectively, and conduct thorough testing after updates.

# 23. Electronic Batch Records

## Objective

The objective of this section is to understand how electronic batch records are managed to ensure accuracy and compliance with regulatory requirements. Additionally, the objective is to gather insights into experiences related to the successful use of electronic batch records during production.

## Test Cases

1. **Electronic Batch Record (EBR) Documentation:**
   - **Objective:** Evaluate the documentation outlining the management of electronic batch records.
   - **Test Case:** Review documented procedures, manuals, or guidelines related to the creation, storage, and retrieval of electronic batch records.
   - **Expected Result:** Clearly documented information detailing the process for managing electronic batch records.

2. **Accuracy and Compliance Measures:**
   - **Objective:** Assess the measures implemented to ensure the accuracy and compliance of electronic batch records with regulatory requirements.
   - **Test Case:** Review documented procedures and protocols to verify the existence of measures such as data integrity checks, version control, and compliance with regulatory standards (e.g., GxP, 21 CFR Part 11).
   - **Expected Result:** Clearly defined measures are in place to ensure the accuracy and compliance of electronic batch records.

3. **Training Program for EBR Users:**
   - **Objective:** Understand the training program in place for personnel involved in the creation and management of electronic batch records.
   - **Test Case:** Review training documentation and interview relevant personnel to assess the adequacy of training programs.
   - **Expected Result:** Evidence of a well-established training program ensuring the competency of personnel handling electronic batch records.

4. **Validation of Electronic Batch Record System:**
   - **Objective:** Verify the validation status of the electronic batch record system.
   - **Test Case:** Review validation documentation to ensure that the electronic batch record system has been appropriately validated.
   - **Expected Result:** Evidence of a validated electronic batch record system with documented validation protocols and results.

5. **Integration with Production Processes:**
   - **Objective:** Assess how electronic batch records are integrated into the overall production processes.
   - **Test Case:** Interview relevant personnel to understand how electronic batch records are used and integrated during production.
   - **Expected Result:** Clear insights into how electronic batch records support and integrate with production activities.

6. **Monitoring and Surveillance of EBR Usage:**
   - **Objective:** Verify the existence of monitoring and surveillance mechanisms for the usage of electronic batch records.
   - **Test Case:** Review documented procedures for continuous monitoring of electronic batch record usage.
   - **Expected Result:** Evidence of ongoing monitoring practices to detect and address any issues related to electronic batch record usage.

7. **Experiences with Electronic Batch Records:**
   - **Objective:** Gather insights into experiences related to the successful use of electronic batch records during production.
   - **Test Case:** Conduct interviews or surveys with relevant personnel to capture their experiences and feedback on using electronic batch records.
   - **Expected Result:** Positive experiences and feedback demonstrating the effectiveness of electronic batch records in production.

8. **Audit Trail Review for EBRs:**
   - **Objective:** Understand how audit trails for electronic batch records are managed and reviewed.
   - **Test Case:** Review procedures and documentation related to the audit trail functionality of electronic batch records.
   - **Expected Result:** Evidence of a well-defined process for reviewing audit trails associated with electronic batch records.

The execution of these test cases aims to ensure that electronic batch records are effectively managed, comply with regulatory standards, and contribute positively to the production processes, with a focus on accuracy, integrity, and compliance.

# 24. Critical System Components

## Objective

The objective of this section is to identify critical components within the automated system and understand how these components are monitored and maintained to ensure continuous operation. Additionally, the objective is to gather insights into the contingency plans in place in case of failure in critical system components.

## Test Cases

1. **Identification of Critical System Components:**
   - **Objective:** Identify and list critical components within the automated system.
   - **Test Case:** Review documentation, system architecture, or interviews with relevant personnel to compile a list of components considered critical to system operation.
   - **Expected Result:** A documented list of identified critical system components.

2. **Monitoring Mechanisms for Critical Components:**
   - **Objective:** Evaluate the monitoring mechanisms in place for critical system components.
   - **Test Case:** Review procedures and documentation related to the monitoring of critical components. Interview relevant personnel to understand the monitoring processes.
   - **Expected Result:** Clear documentation outlining monitoring mechanisms, including tools, frequency, and responsible personnel.

3. **Maintenance Procedures for Critical Components:**
   - **Objective:** Assess the maintenance procedures for critical system components.
   - **Test Case:** Review documentation and procedures related to the maintenance of critical components. Evaluate the frequency and methods employed for maintenance.
   - **Expected Result:** Clearly defined maintenance procedures for critical system components.

4. **Continuous Operation Assurance:**
   - **Objective:** Verify measures in place to ensure continuous operation of critical components.
   - **Test Case:** Review documentation and procedures to understand how continuous operation is assured for critical components, including redundancy or failover mechanisms.
   - **Expected Result:** Evidence of measures that mitigate the risk of disruption to continuous operation.

5. **Contingency Plans for Component Failures:**
   - **Objective:** Understand the contingency plans in place to address failures in critical system components.
   - **Test Case:** Review contingency plans, including documented procedures and strategies for responding to and recovering from failures in critical components.
   - **Expected Result:** Well-documented contingency plans outlining steps for resolution and recovery in the event of component failures.

6. **Testing of Contingency Plans:**
   - **Objective:** Verify that contingency plans for critical components are periodically tested.
   - **Test Case:** Review documentation related to the testing of contingency plans. Evaluate the frequency and thoroughness of testing.
   - **Expected Result:** Evidence of periodic testing of contingency plans, with documented results and lessons learned.

7. **Communication of Contingency Measures:**
   - **Objective:** Assess how information about contingency measures is communicated within the organization.
   - **Test Case:** Interview relevant personnel to understand the communication strategy for contingency measures. Review documentation related to communication.
   - **Expected Result:** Evidence of effective communication channels and methods for contingency measures.

8. **Documentation of Critical System Components:**
   - **Objective:** Verify that critical system components are adequately documented.
   - **Test Case:** Review documentation to ensure that critical system components are well-documented, including specifications, configurations, and dependencies.
   - **Expected Result:** Comprehensive documentation for critical system components.

The execution of these test cases aims to ensure that critical components are identified, monitored, and maintained effectively to support continuous system operation. Additionally, the assessment of contingency plans ensures preparedness for potential failures, with a focus on resilience and recovery.

# 25. Validation of Custom Code or Scripts

## Objective

The objective of this section is to understand how custom code or scripting is validated when utilized in the configuration or operation of the automated system. Additionally, the goal is to gather information on the measures taken to ensure the security and integrity of custom code.

## Test Cases

1. **Validation Procedures for Custom Code:**
   - **Objective:** Assess the procedures in place for the validation of custom code or scripts.
   - **Test Case:** Review documentation related to the validation process for custom code. Evaluate whether there are established procedures and criteria for validating custom code.
   - **Expected Result:** Clear documentation outlining the validation procedures for custom code.

2. **Verification of Custom Code Security Measures:**
   - **Objective:** Verify the security measures implemented for custom code.
   - **Test Case:** Review security documentation and assess the security measures integrated into custom code or scripts. Evaluate encryption, access controls, and other security features.
   - **Expected Result:** Evidence of robust security measures incorporated into custom code.

3. **Integrity Checks for Custom Code:**
   - **Objective:** Assess measures taken to ensure the integrity of custom code.
   - **Test Case:** Review documentation to understand how integrity checks are performed on custom code. Evaluate checksums, version control, or other mechanisms to prevent unauthorized alterations.
   - **Expected Result:** Documentation demonstrating the implementation of integrity checks for custom code.

4. **Validation Frequency for Custom Code:**
   - **Objective:** Determine how frequently custom code is validated.
   - **Test Case:** Interview relevant personnel and review documentation to understand the frequency of validation for custom code. Evaluate whether there are scheduled validation processes.
   - **Expected Result:** Information on the validation frequency for custom code, aligned with industry best practices.

5. **Change Control for Custom Code:**
   - **Objective:** Evaluate the change control process for modifications to custom code.
   - **Test Case:** Review change control documentation and procedures related to custom code. Assess how changes are categorized, reviewed, and validated.
   - **Expected Result:** Clearly defined change control procedures for custom code modifications.

6. **Documentation of Custom Code Validation:**
   - **Objective:** Verify that the validation of custom code is adequately documented.
   - **Test Case:** Review documentation to ensure that there is comprehensive documentation for the validation of custom code. Evaluate whether validation results are recorded.
   - **Expected Result:** Comprehensive documentation demonstrating the validation of custom code.

7. **Security Audits and Reviews:**
   - **Objective:** Assess whether security audits and reviews are conducted for custom code.
   - **Test Case:** Review documentation related to security audits and assessments. Evaluate whether external reviews or audits are performed.
   - **Expected Result:** Evidence of regular security audits and reviews for custom code.

8. **Training for Personnel Handling Custom Code:**
   - **Objective:** Understand the training program for personnel involved in handling custom code.
   - **Test Case:** Interview personnel and review training documentation to assess whether there is a structured training program for those dealing with custom code.
   - **Expected Result:** Evidence of a training program that enhances the skills and awareness of personnel working with custom code.

The execution of these test cases aims to ensure that custom code or scripts are validated effectively, with a focus on security, integrity, and compliance with established procedures. Additionally, assessing the frequency of validation and change control procedures helps maintain the reliability of custom code in the automated system.
