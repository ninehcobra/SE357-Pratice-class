# Requirements Traceability Matrix (RTM)

| Requirement ID | Functional Requirement                  | Non-Functional Requirement                            | Source                         | Stakeholder  | Test Case ID | Proposed Change                            | Release Version |
| -------------- | --------------------------------------- | ----------------------------------------------------- | ------------------------------ | ------------ | ------------ | ------------------------------------------ | --------------- |
| REQ-001        | User registration and account creation  | Security: User authentication                         | User Stories                   | User         | TC-001       | Implement multi-factor authentication    | 1.0             |
| REQ-002        | Browse and enroll in courses             | Accessibility: User-friendly navigation               | Business Requirements Document | User         | TC-002       | Add search functionality for courses     | 1.0             |
| REQ-003        | Access learning materials and resources  | Scalability: Support for a large number of users       | User Stories                   | User         | TC-003       | Integrate a document preview feature      | 2.0             |
| REQ-004        | Take quizzes and assessments             | Performance: Low-latency quiz loading                  | User Stories                   | User         | TC-004       | Enhance quiz submission process          | 1.0             |
| REQ-005        | Track and manage progress                | Data Privacy: Secure storage of user progress data     | User Stories                   | User         | TC-005       | Implement a progress visualization dashboard | 2.0             |
| REQ-006        | Forum for student interaction                      | Social: Platform for student communication             | User Stories                   | Student      | TC-006       | Add comment and reply functionality      | 2.0             |
| REQ-007        | Instructor dashboard for course management         | Performance: Real-time data updates                     | User Stories                   | Instructor   | TC-007       | Enhance dashboard features                | 1.0             |
| REQ-008        | Mobile responsiveness for learning on the go        | Accessibility: Usable on various devices               | User Stories                   | User         | TC-008       | Improve mobile interface                  | 2.0             |
| REQ-009        | Gamification features to enhance student engagement | Engagement: Incorporate gamified learning elements     | User Stories                   | Student      | TC-009       | Integrate badges and rewards system      | 1.0             |
| REQ-010        | Automated course evaluation and feedback            | Efficiency: Streamline the feedback process            | User Stories                   | Student      | TC-010       | Implement automated feedback system      | 2.0             |
| REQ-011        | Integration with external learning resources        | Compatibility: Support integration with third-party   | Business Requirements Document | User         | TC-011       | Connect with external learning platforms | 1.0             |
| REQ-012        | Advanced search and filtering options for courses    | Usability: Improve user experience with enhanced search| User Stories                   | User         | TC-012       | Add advanced search features              | 2.0             |
| REQ-013        | Real-time progress tracking for instructors         | Performance: Instant updates on student progress       | User Stories                   | Instructor   | TC-013       | Enable real-time progress monitoring     | 1.0             |
| REQ-014        | Integration with video conferencing tools           | Compatibility: Seamless integration with video tools  | Business Requirements Document | User         | TC-014       | Connect with video conferencing platforms | 2.0             |
| REQ-015        | Peer review system for assignments                  | Quality Assurance: Enhance assignment evaluation        | User Stories                   | Student      | TC-015       | Implement peer review functionality       | 1.0             |

| **Use Case**                   | **Requirement** | **REQ-001** | **REQ-002** | **REQ-003** | **REQ-004** | **REQ-005** |
| ------------------------------ | --------------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| User Registration              | User            | R           |             |             |             | U           |
| Browse Courses                 | User            | R           |             |             |             |             |
| Access Learning Materials      | User            | R           |             | R           |             |             |
| Take Quizzes                   | User            | R           |             |             | R           |             |
| Track and Manage Progress      | User            | R           |             |             |             | R           |
| Forum Interaction              | Student         | U           |             |             |             | R           |
| Instructor Dashboard           | Instructor      |             |             |             |             | R           |
| Mobile Responsiveness          | User            | R           |             |             |             | R           |
| Gamification                   | Student         |             |             |             |             | R           |
| Automated Evaluation           | Student         | U           |             | R           |             |             |
| External Integration           | User            |             |             | R           |             | R           |
| Advanced Search                | User            |             | R           |             |             |             |
| Real-time Tracking             | Instructor      |             | U           |             |             | R           |
| Video Conferencing             | User            |             |             | R           |             |             |
| Peer Review                    | Student         | U           |             |             |             | U           |

| **Use Case**                   | **Requirement** | **REQ-006** | **REQ-007** | **REQ-008** | **REQ-009** | **REQ-010** | **REQ-011** | **REQ-012** | **REQ-013** | **REQ-014** | **REQ-015** |
| ------------------------------ | --------------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| User Registration              | User            | U           |             | R           |             |             |             |             |             |             |             |
| Browse Courses                 | User            |             |             | R           |             |             |             |             |             |             |             |
| Access Learning Materials      | User            |             |             |             |             |             |             |             |             |             |             |
| Take Quizzes                   | User            |             |             |             |             |             |             |             |             |             |             |
| Track and Manage Progress      | User            |             |             |             |             |             |             |             |             |             |             |
| Forum Interaction              | Student         |             |             |             |             |             |             |             |             |             |             |
| Instructor Dashboard           | Instructor      |             |             |             |             |             |             |             |             |             |             |
| Mobile Responsiveness          | User            |             |             | R           |             |             |             |             |             |             |             |
| Gamification                   | Student         |             | U           |             |             |             |             |             |             |             |             |
| Automated Evaluation           | Student         |             |             |             |             |             |             |             |             |             |             |
| External Integration           | User            |             | R           |             |             |             |             |             |             |             |             |
| Advanced Search                | User            |             |             |             |             |             |             |             |             |             |             |
| Real-time Tracking             | Instructor      |             | U           |             |             |             |             |             |             |             |             |
| Video Conferencing             | User            |             |             | R           |             |             |             |             |             |             |             |
| Peer Review                    | Student         |             | U           |             |             |             |             |             |             |             |             |







## Use Case Matrix
| **Use Case**                               | **Actor**                          | **Description**                    | **Steps**                                                | **Alternative Paths**              | **Exceptions**                     | **Post-conditions**                | **Business Rules**                 | **Related Requirements**           |
| ------------------------------------------- | ---------------------------------- | ---------------------------------- | -------------------------------------------------------- | ---------------------------------- | ---------------------------------- | ---------------------------------- | ---------------------------------- | ---------------------------------- |
| REQ-001 (User Registration)                 | User                               | User registers an account          | 1. Provide details and submit                           | -                                  | -                                  | User account created               | Provide valid and unique info      | REQ-001                            |
| REQ-002 (Browse Courses)                    | User                               | User browses courses               | 1. Navigate to courses                                   | -                                  | -                                  | Courses displayed                  | -                                  | REQ-002                            |
| REQ-003 (Access Learning Materials)         | User                               | User accesses learning materials  | 1. Select a course, access materials                    | -                                  | -                                  | Learning materials accessible      | User must be logged in              | REQ-003                            |
| REQ-004 (Take Quizzes)                      | User                               | User takes quizzes                 | 1. Select a quiz                                       | -                                  | -                                  | Quiz results recorded              | User must complete quiz            | REQ-004                            |
| REQ-005 (Track and Manage Progress)         | User                               | User tracks and manages progress  | 1. View progress dashboard                             | -                                  | -                                  | Progress updated                   | -                                  | REQ-005                            |
| REQ-006 (Forum Interaction)                 | Student                            | Student interacts in forum         | 1. Comment on posts                                     | -                                  | -                                  | Forum interaction recorded         | Appropriate forum etiquette        | REQ-006                            |
| REQ-007 (Instructor Dashboard)             | Instructor                         | Instructor manages courses         | 1. View course analytics                                | -                                  | -                                  | Analytics displayed                 | Instructors manage courses         | REQ-007                            |
| REQ-008 (Mobile Responsiveness)             | User                               | User learns on mobile device       | 1. Access platform on mobile                            | -                                  | -                                  | Platform accessible on mobile      | Compatible on mobile devices       | REQ-008                            |
| REQ-009 (Gamification)                      | Student                            | Student engages in gamified content| 1. Complete gamified activities                        | -                                  | -                                  | Rewards and badges earned           | Gamification activities completed | REQ-009                            |
| REQ-010 (Automated Evaluation)              | Student                            | Assignments submitted for review   | 1. Submit assignment for evaluation                     | -                                  | -                                  | Feedback recorded and provided      | Integration with external tools     | REQ-010                            |
| REQ-011 (External Integration)              | User                               | User accesses external resources   | 1. Explore external resources                           | -                                  | -                                  | External resources accessible       | Integration with external tools     | REQ-011                            |
| REQ-012 (Advanced Search)                   | User                               | User searches and filters           | 1. Use advanced search                                 | -                                  | -                                  | Search results displayed             | Efficient search performed          | REQ-012                            |
| REQ-013 (Real-time Tracking)                | Instructor                         | Instructor monitors progress       | 1. View real-time progress                              | -                                  | -                                  | Progress updated in real-time       | Real-time updates enabled           | REQ-013                            |
| REQ-014 (Video Conferencing)                | User                               | User uses video conferencing        | 1. Join virtual meeting                                | -                                  | -                                  | Video session joined                 | Compatible video tools used          | REQ-014                            |
| REQ-015 (Peer Review)                       | Student                            | Student participates in peer review | 1. Review and evaluate peers' work                    | -                                  | -                                  | Peer reviews completed              | Honest and constructive feedback    | REQ-015                            |


## Requirements Source Traceability Matrix

| **Requirement ID** | **Source**                         |
| ------------------- | ---------------------------------- |
| REQ-001             | User Stories                       |
| REQ-002             | Business Requirements Document     |
| REQ-003             | User Stories                       |
| REQ-004             | User Stories                       |
| REQ-005             | Business Requirements Document     |
| REQ-006             | User Stories                       |
| REQ-007             | User Stories                       |
| REQ-008             | User Stories                       |
| REQ-009             | User Stories                       |
| REQ-010             | User Stories                       |
| REQ-011             | Business Requirements Document     |
| REQ-012             | User Stories                       |
| REQ-013             | User Stories                       |
| REQ-014             | Business Requirements Document     |
| REQ-015             | User Stories                       |


## Requirements Stakeholder Traceability Matrix

| **Requirement ID** | **Stakeholder**  |
| ------------------- | ---------------- |
| REQ-001             | User             |
| REQ-002             | User             |
| REQ-003             | User             |
| REQ-004             | User             |
| REQ-005             | Organization     |
| REQ-006             | Student          |
| REQ-007             | Instructor       |
| REQ-008             | User             |
| REQ-009             | Student          |
| REQ-010             | Student          |
| REQ-011             | User             |
| REQ-012             | User             |
| REQ-013             | Instructor       |
| REQ-014             | User             |
| REQ-015             | Student          |


## Requirements Test Traceability Matrix

| **Requirement ID** | **Test Case ID** |
| ------------------- | ---------------- |
| REQ-001             | TC-001           |
| REQ-002             | TC-002           |
| REQ-003             | TC-003           |
| REQ-004             | TC-004           |
| REQ-005             | TC-005           |
| REQ-006             | TC-006           |
| REQ-007             | TC-007           |
| REQ-008             | TC-008           |
| REQ-009             | TC-009           |
| REQ-010             | TC-010           |
| REQ-011             | TC-011           |
| REQ-012             | TC-012           |
| REQ-013             | TC-013           |
| REQ-014             | TC-014           |
| REQ-015             | TC-015           |


## Requirements Change Traceability Matrix

| **Requirement ID** | **Proposed Change**                            |
| ------------------- | --------------------------------------------- |
| REQ-001             | Implement multi-factor authentication         |
| REQ-002             | Add search functionality for courses          |
| REQ-003             | Integrate a document preview feature           |
| REQ-004             | Enhance quiz submission process               |
| REQ-005             | Implement a progress visualization dashboard |
| REQ-006             | Add comment and reply functionality           |
| REQ-007             | Enhance dashboard features                    |
| REQ-008             | Improve mobile interface                      |
| REQ-009             | Integrate badges and rewards system           |
| REQ-010             | Implement automated feedback system           |
| REQ-011             | Connect with external learning platforms      |
| REQ-012             | Add advanced search features                   |
| REQ-013             | Enable real-time progress monitoring          |
| REQ-014             | Connect with video conferencing platforms      |
| REQ-015             | Implement peer review functionality            |


## Requirements Release Traceability Matrix

| **Requirement ID** | **Release Version** |
| ------------------- | ------------------- |
| REQ-001             | 1.0                 |
| REQ-002             | 2.0                 |
| REQ-003             | 1.0                 |
| REQ-004             | 2.0                 |
| REQ-005             | 1.0                 |
| REQ-006             | 2.0                 |
| REQ-007             | 1.0                 |
| REQ-008             | 2.0                 |
| REQ-009             | 1.0                 |
| REQ-010             | 2.0                 |
| REQ-011             | 1.0                 |
| REQ-012             | 2.0                 |
| REQ-013             | 1.0                 |
| REQ-014             | 2.0                 |
| REQ-015             | 1.0                 |

