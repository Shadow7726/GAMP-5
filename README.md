
# GAMP® 5 and Computer System Validation 

## **Introduction:**

- **GAMP® Definition:**
  - GAMP® stands for Good Automated Manufacturing Practice.
  - Introduced in 1991 to address gaps between regulatory expectations and industry practices.
  - GAMP® 5 is the current version, introduced in 2008 by ISPE.

## **Key Concepts of GAMP® 5:**

- Product and process understanding
- Lifecycle approach within a QMS
- Scalable lifecycle activities
- Science-based quality risk management
- Leveraging supplier involvement

## **System Development Lifecycle (SDLC):**

### The System Development Lifecycle (SDLC) is a structured process for planning, creating, testing, deploying, and maintaining information systems. It typically consists of four major phases:

1. **Concept Phase:**
   - **Scope Definition:**
     - Clearly define the scope of the computerized system, identifying boundaries and interfaces with other systems.

2. **Project Phase:**
   - **Crucial for Validation and System Release:**
     - This phase is pivotal for the validation of the system and its subsequent release.
   - **Activities:**
     - Planning, specification, verification, and reporting are key activities during this phase.

3. **Operation Phase:**
   - **Post-Release Operations:**
     - Involves the day-to-day operations of the system after it has been released.
   - **Activities:**
     - Security management, incident or problem management, backup and restoration, disaster recovery, user management review, and periodic audits.

4. **Retirement Phase:**
   - **End-of-Life Considerations:**
     - Addresses the processes associated with retiring a system.
   - **Activities:**
     - Data retention, migration, or destruction, and the overall management of the retirement process.
     - 

## **GAMP® 5 Categorization:**

1. **Infrastructure Software:**
   - Includes operating systems, database engines, middleware, programming languages, and antivirus software.
   - Forms the foundational software infrastructure for computerized systems.

2. **Non-configured Software:**
   - Also known as Commercial Off-The-Shelf (COTS) software.
   - Ready-made software available in the market without configuration.
   - Examples include laboratory software like chromatography systems.

3. **Configured Software:**
   - Involves software that is configured based on specific requirements.
   - Examples include Laboratory Information Management Systems (LIMS), Data Dashboards, and Process Control Systems.

4. **Custom Applications (Bespoke Software):**
   - Internally or externally developed IT applications.
   - Tailored to meet the specific business needs of an organization.
   - Examples include custom-developed pharmaceutical production tracking software.

Note: Category 2 (firmware) from GAMP® 4 was removed in GAMP® 5 and merged with other categories based on the nature of the software.

## **Data Integrity (ALCOA+):**

- Focuses on data accuracy, completeness, legibility, originality, and accessibility.
- Applies to paper, hybrid, and electronic systems.

----

# GAMP® Assessment Guide for Computerized Systems Validation

A GAMP assessment is a crucial step in the validation process for computerized systems, especially in regulated industries such as pharmaceuticals. The goal is to determine the appropriate level of validation and documentation needed based on the system's impact on product quality and patient safety. Below is a comprehensive guide on what needs to be done as part of a GAMP assessment:

## 1. **Understand the System:**
   - **Scope Definition:**
     - Clearly define the scope of the computerized system, identifying boundaries and interfaces with other systems.

## 2. **Gather Information:**
   - **User Requirements:**
     - Collect and document user requirements, understanding the intended use of the system.
   - **System Functionality:**
     - Document the intended functions of the system and how it will be used in the production process.

## 3. **Categorize the System:**
   - **GAMP Categories:**
     - Use the GAMP categorization framework to classify the system into Categories 1, 3, 4, or 5.
     - Consider the impact on product quality and patient safety when assigning categories.

## 4. **Risk Assessment:**
   - **Perform Risk Analysis:**
     - Conduct a risk assessment to identify potential risks associated with the system.
     - Consider factors such as data integrity, system complexity, criticality, and impact on the final product.
     - Evaluate the likelihood and severity of identified risks.

## 5. **Validation Approach:**
   - **Determine Validation Approach:**
     - Based on categorization and risk assessment, determine the appropriate validation approach.
     - Define the level of documentation and testing required.

## 6. **Documentation:**
   - **Validation Plan:**
     - Develop a validation plan outlining strategy, responsibilities, deliverables, and timelines.
   - **User Requirement Specification (URS):**
     - Develop a URS document stating user requirements for the system.
   - **Functional Specifications:**
     - Create detailed functional specifications describing how the system meets user requirements.
   - **Traceability Matrix:**
     - Develop a traceability matrix to ensure each requirement is traced back to test cases.

## 7. **Testing:**
   - **Test Protocols:**

### Installation Qualification (IQ)

- Verify installation of hardware, software, infrastructure against vendor specifications.
- Check system components, conduct inventory checks, and assess equipment calibration status.
- Review system configurations and security controls.
- Generate a baseline for operational qualification.

### Operational Qualification (OQ)

- Execute test cases to verify software functions according to user requirements.
- Test interface functionality and integration with other systems.
- Validate editing, retrieving, processing, and reporting of data.
- Test error handling, alarms, and audit trails.
- Run tests in different operating environments if applicable.

### Performance Qualification (PQ)

- Perform stress and load testing to verify stability under peak conditions.
- Determine system bottlenecks and assess hardware limitations.
- Evaluate system behavior during failure scenarios.
- Measure system metrics such as uptime and response time.
- Fine-tune system performance and configurations.

### General

- Ensure traceability to requirements and risk assessment.
- Test data integrity, reliability, and accuracy.
- Address deviations, investigate failures, and document resolutions.
- Conduct independent verification of testing as applicable.
- Ensure compliance with applicable regulations (GxP, 21 CFR Part 11, etc.).


## 8. **Change Control:**
   - **Implement Change Control:**

- Establish a documented change control procedure for managing system changes post-validation.

- Categorize changes based on impact - major vs minor.

- Major changes require revalidation per the original protocol. Examples:
  - New software version/upgrade.
  - Hardware architecture changes.
  - New interfaces or functionality.
  - Modification to critical algorithms.
  - Changes affecting data integrity.

- Minor changes can be validated through a supplemental protocol. Examples:
  - Patches, bug fixes.
  - Configuration changes.
  - Minor enhancements or changes to non-critical functions.

- Set up a change control board for reviewing and approving changes.
- Maintain a change control log of all changes. Document change details, justification, and approvals.
- Perform a risk assessment of proposed changes regarding impact on product quality, safety, and effectiveness.
- Develop a test protocol focusing on areas affected by the change, and execute tests.
- Update all relevant validation documents post-change implementation.
- Retain evidence of revalidation testing and reporting.
- Ensure changes are communicated to all relevant stakeholders.
- Monitor changes during regular walkthroughs and audits to ensure adherence to procedures.

## 9. **Periodic Review:**
   - **Conduct Periodic Reviews:**
     - Implement a process for periodic reviews to ensure continued validation of the system.
     - Reassess risks and update documentation as needed.

## 10. **Documentation Maintenance:**
   - **Document Maintenance:**
     - Maintain accurate and up-to-date documentation throughout the system's lifecycle.
     - Ensure documentation reflects any changes or updates.

## 11. **Training:**
   - **Training Programs:**
     - Implement training programs for personnel involved in system operation, maintenance, and validation.

## 12. **Supplier Involvement:**
   - **Supplier Assessment:**
     - If applicable, assess and involve suppliers in the validation process, especially for Categories 3 and 5 systems.

## 13. **Compliance with Regulations:**
   - **Adherence to Regulations:**
     - Ensure validation activities adhere to relevant regulations and standards, such as GxP requirements.

## 14. **Audit Trail and Data Integrity:**
   - **Audit Trail Review:**
     - Include an audit trail review as part of the validation process to ensure data integrity.

## 15. **Record Keeping:**
   - **Maintain Records:**
     - Keep detailed records of all validation activities, testing results, and change control processes.

## 16. **Documentation Review:**
   - **External Documentation Review:**
     - Ensure external documentation, such as supplier documentation, is reviewed and considered in the validation process.

## 17. **Continuous Improvement:**
   - **Continuous Monitoring:**
     - Continuously monitor and assess the performance of the validated system.
     - Implement continuous improvement initiatives based on lessons learned.
