# Student Project Repository Management

National Association of Computing Students

AKSU Chapter

Friday, October 13th 2023

<hr>

# Project Analysis Report

## Introduction

The project under analysis is the development of a Student Project Database Management Platform. This platform is designed to serve as a comprehensive repository for students, enabling them to search for and access information about projects completed by their peers in the past. This initiative has three primary objectives:

1. **Future Project Confirmation**: One of the main goals of this project is to provide a valuable resource for students. It allows them to verify whether a similar project has been undertaken in the past. This confirmation aids students in determining the uniqueness of their project ideas and informs their next steps.

2. **Project Analysis and Evaluation**: The platform facilitates the analysis of previous student projects, enabling users to evaluate the strengths and weaknesses of these projects. By examining the work of their peers, students can gain insights and valuable lessons, contributing to the enhancement of project quality and outcomes.

3. **Comprehensive Project Repository**: In addition to serving as a resource for past projects, the platform will also store information about the projects of future students. This ensures a growing and evolving database, enriching the learning experience for all students.

This project analysis report will focus on the critical phases of Requirement Gathering, Problem Definition, Validation, and Requirement Specification, shedding light on how these elements are essential for the successful realization of the platform's objectives.

## Requirement Gathering

Given the information that the platform is primarily intended for school administrators to add projects, and students will access the project, the requirements will be adjusted accordingly. Here's a list of modified requirements:

**Functional Requirements:**

1. **Administrative Dashboard**:
   - A user-friendly dashboard for school administrators to add, edit, and manage projects.
   - Ability to create, update, or delete project records.

2. **Search and Browsing**:
   - A search function for students to search for projects by keywords, subjects, or relevant criteria.
   - Filter options for refining search results.
   - Project categorization by subject, date, and other relevant parameters.

3. **Project Viewing**:
   - Ability for students to view project details, including project descriptions, authors, and project-related information.

4. **Reporting and Analytics**:
   - Analytics to track user interactions, such as views.
   - Reporting mechanisms for administrators to monitor platform usage.

**Non-Functional Requirements:**

1. **Security**:
   - Strong security measures to protect user data and ensure that only authorized school administrators can add and modify projects.
   - Encryption for sensitive data and secure access controls.

2. **Scalability**:
   - The system should be able to handle a growing number of students and projects as the database expands.
   - Scalability measures for high traffic periods, such as during peak usage times.

3. **Performance**:
   - Fast response times for searches and project viewing.
   - Efficient database management to ensure speedy data retrieval.

4. **Usability and User Experience**:
   - An intuitive and user-friendly interface for easy navigation and project discovery by students.
   - Responsive design to accommodate various devices and screen sizes.

5. **Data Backup and Recovery**:
   - Regular data backups and a disaster recovery plan in case of data loss.

6. **Compliance and Regulations**:
   - Compliance with relevant data protection and privacy regulations.
   - Accessibility compliance to ensure the platform can be used by all students.

7. **Documentation and Training**:
   - User documentation for school administrators on how to manage projects.
   - Training for administrators to use the platform effectively.

8. **Support and Maintenance**:
   - Ongoing support for school administrators.
   - Regular maintenance to update the platform, address issues, and enhance features.


   - Describe the methods and techniques used for gathering requirements.
   - Summarize key requirements and findings.
   - Discuss any challenges encountered and their resolution.

## Problem Definition

In educational institutions, particularly within our school, students often embark on academic projects with the desire to explore uncharted territories, push the boundaries of their knowledge, and address real-world problems. While these projects reflect the culmination of their educational experiences, they often operate in isolation, lacking a comprehensive platform to catalog, share, and learn from their collective knowledge. Consequently, we face the following challenges:

1. **Lack of Project Visibility**: Without a centralized platform, there's no effective means for students to showcase and share their completed projects. This results in the underutilization of valuable insights and knowledge generated during the project's lifecycle.

2. **Limited Learning Opportunities**: Students' ability to learn from one another's successes and failures remains underutilized. The absence of a central repository hampers our students' opportunities to analyze past projects, identify best practices, and ultimately enhance the quality and effectiveness of their own academic projects.

3. **Difficulty in Project Validation**: As students formulate project ideas, they often lack the means to verify whether similar projects have been executed in the past. This can lead to redundant efforts and hinders our students' capacity to refine and improve their project proposals effectively.

4. **Manual and Fragmented Data Handling**: Managing project information in a manual and decentralized manner is time-consuming and can lead to data inaccuracies, making it challenging for administrators to monitor and support students in their project-related endeavors.

5. **Inefficiency in Project Discovery**: Students face difficulties in discovering projects that align with their areas of interest and study. The absence of an efficient search and categorization system complicates the process of locating relevant projects.

Addressing these challenges is pivotal to nurturing a culture of knowledge sharing and collaboration among our students and administrators. It is in response to these problems that we are developing the Student Project Database Management Platform, a solution that will enable efficient project cataloging, seamless project visibility, and enhanced learning experiences for our students. This platform aims to facilitate a holistic approach to managing student projects, fostering a more enriched and collaborative educational environment.

## Validation

Validation is the process of evaluating the final product to determine whether it fulfills the intended purpose and satisfies the needs of the users. In the context of the Student Project Database Management Platform, validation involves confirming that the system aligns with the project's objectives and effectively addresses the identified problems. This includes:

1. **Functional Validation**: Ensuring that the platform's features, such as project submission, search, and project viewing, work as expected and fulfill the specified requirements.

2. **User Validation**: Collecting feedback from both school administrators and students to ensure that the system meets their expectations and is user-friendly.

3. **Objective Alignment**: Verifying that the platform effectively supports the objectives, such as providing project visibility and enhancing learning opportunities, as outlined in the problem definition.

4. **Data Accuracy**: Confirming that the data stored in the platform, including project information, is accurate and up-to-date.

## Verification

Verification is the process of checking that the project adheres to its specified requirements, design, and standards. For the Student Project Database Management Platform, verification involves ensuring that the platform is built according to the defined requirements and standards. This includes:

1. **Requirement Verification**: Checking that the system's features and functionalities align with the initial set of requirements, including administrative dashboard, project search, and project viewing.

2. **Design Verification**: Verifying that the system's architecture and design align with the specified project objectives and that the structure and flow of the platform are consistent with the requirements.

3. **Compliance Verification**: Ensuring that the platform adheres to relevant regulations, standards, and best practices, such as data protection and accessibility standards.

4. **Testing**: Conducting thorough testing, including unit testing, integration testing, and user acceptance testing, to identify and resolve any issues or deviations from the requirements.

The validation and verification process aims to confirm that the Student Project Database Management Platform is not only built correctly but also serves the intended purpose effectively. It ensures that the platform delivers the expected functionality, usability, and performance, ultimately aligning with the objectives outlined in the problem definition. Verification is about building the system right, and validation is about building the right system.

## Requirement Specification for the Student Project Database Management Platform

**1. User Roles and Access Control**

- **Administrators**: School staff members with the authority to add, edit, and manage projects.
- **Students**: Users with read-only access to view project information.

**2. Administrative Dashboard**

- An intuitive administrative dashboard for administrators to manage projects.
- Authentication and authorization for administrators to ensure secure access.

**3. Project Submission**

- Ability for administrators to add, edit, and delete project records.
- Fields for project title, description, subject area, and project files.
- Support for multiple file formats, such as PDFs and documents.
- Option to categorize projects by subject, date, and other relevant parameters.

**4. Search and Browsing**

- A search function for students to find projects using keywords, subjects, or criteria.
- Filter options for refining search results, such as sorting by date or subject.
- Project categorization by subject and date.

**5. Project Viewing**

- Capability for students to view project details, including project descriptions and author information.
- Secure access control to prevent unauthorized changes to project records.

**6. Reporting and Analytics**

- Analytics to track user interactions, such as views and searches.
- Reporting mechanisms for administrators to monitor platform usage and evaluate its effectiveness.

**7. Security**

- Robust security measures, including user authentication and encryption, to protect user data and maintain data integrity.
- Authorization controls to ensure that only authorized administrators can add, edit, and delete projects.

**8. Usability and User Experience**

- An intuitive and user-friendly interface for students and administrators.
- Responsive design for access on various devices and screen sizes.

**9. Data Backup and Recovery**

- Regular data backups to safeguard against data loss.
- A disaster recovery plan to recover data in case of system failures.

**10. Compliance and Regulations**

- Compliance with data protection and privacy regulations, ensuring the privacy and security of user data.
- Accessibility compliance to accommodate users with disabilities.

**11. Documentation and Training**

- User documentation for school administrators on how to manage projects.
- Training for administrators to use the platform effectively.

**12. Support and Maintenance**

- Ongoing support for administrators and users to address any issues or questions.
- Regular maintenance to update the platform, fix issues, and enhance features.

This requirement specification serves as a foundation for the development of the Student Project Database Management Platform, ensuring that the project aligns with the objectives outlined in the problem definition and the specific needs of school administrators and students. The actual specification may be more detailed and may involve collaboration with relevant stakeholders to ensure the platform meets their expectations.


## Conclusion

The analysis phase of the Student Project Database Management Platform project has provided valuable insights into the objectives, requirements, and challenges associated with the development of this crucial educational tool. It is evident that this project aims to address significant issues within our academic community, offering solutions that will positively impact both school administrators and students. 

The identified problem of limited project visibility, the lack of efficient learning opportunities, the difficulty in project validation, and manual data handling has prompted the development of a well-structured and accessible platform. The system will not only streamline the process of project management but will also empower students to enhance the quality of their academic projects by learning from the experiences of their peers.

The requirement specification further outlines the specific functionalities and features that will make this platform a reality. The inclusion of roles, user access control, an administrative dashboard, search and browsing capabilities, and security measures ensure that the platform addresses the needs of both school administrators and students.

In closing, the Student Project Database Management Platform is poised to transform the way we manage and interact with academic projects. By enabling the efficient cataloging of projects, enhancing project visibility, and providing students with the tools to learn from their peers' achievements and challenges, this platform is set to become a cornerstone of our educational community. The requirements specified will guide the development process, and the subsequent phases of design, development, and testing will work towards realizing the objectives outlined in this analysis.

The success of this project will not only streamline project management within the school but will also contribute to a collaborative learning environment where knowledge sharing and peer learning are at the forefront. As we move forward, we are committed to ensuring that this platform fulfills its promise, providing both students and administrators with the tools they need to excel in their educational endeavors.

## Next Steps

With the completion of the analysis phase, we are now poised to transition into the subsequent stages of the project's development lifecycle. The following steps provide an overview of what to expect:

**1. Design Phase**

The design phase is the next critical step in the development process. During this phase, we will create detailed design specifications for the Student Project Database Management Platform based on the requirements identified in this analysis. This phase will encompass both the system's architecture and its user interface, ensuring that the platform is both functional and user-friendly. The design phase will also involve creating wireframes, mockups, and other design artifacts to guide the development team.

**2. Development Phase**

Following the design phase, development work will commence. Our development team will translate the design specifications into a working platform. This phase involves coding, integration, and testing to ensure that the platform's features and functionalities are implemented according to the defined requirements. Regular progress updates and quality assurance checks will be a priority during this phase.

**3. Testing and Quality Assurance**

The testing phase is vital for ensuring the reliability and functionality of the Student Project Database Management Platform. Rigorous testing, including unit testing, integration testing, and user acceptance testing, will be conducted to identify and rectify any issues or bugs. We will strive to provide a robust and error-free system for our users.

**4. User Training and Documentation**

Before the platform's deployment, we will provide training sessions for school administrators who will be responsible for managing the platform. Additionally, comprehensive user documentation will be created to guide both administrators and students on how to effectively use the system.

**5. Deployment and Rollout**

Once the system has passed rigorous testing and quality checks, it will be ready for deployment. The rollout will be planned and executed to ensure a seamless transition to the new platform. This phase will also involve monitoring system performance and addressing any post-deployment issues promptly.

**6. Ongoing Support and Maintenance**

After the platform goes live, our commitment to its success continues. We will provide ongoing support and maintenance to address any technical issues, optimize performance, and implement updates as necessary. Our aim is to ensure the long-term effectiveness and reliability of the Student Project Database Management Platform.

As we proceed into these next phases, we will remain aligned with the objectives and requirements outlined in this analysis, keeping a strong focus on delivering a platform that effectively addresses the identified problems and meets the needs of our academic community.


<br>
Ubongabasi Jerome

Backend Developer
