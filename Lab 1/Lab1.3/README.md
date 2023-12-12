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

## Use Case Matrix

| Use Case                           | REQ-001 (User Registration) | REQ-002 (Browse Courses) | REQ-003 (Access Learning Materials) | REQ-004 (Take Quizzes) | REQ-005 (Track and Manage Progress) | REQ-006 (Forum Interaction) | REQ-007 (Instructor Dashboard) | REQ-008 (Mobile Responsiveness) | REQ-009 (Gamification) | REQ-010 (Automated Evaluation) | REQ-011 (External Integration) | REQ-012 (Advanced Search) | REQ-013 (Real-time Tracking) | REQ-014 (Video Conferencing) | REQ-015 (Peer Review) |
| ---------------------------------- | ---------------------------- | ------------------------ | ------------------------------------- | ---------------------- | ----------------------------------- | -------------------------- | ----------------------------- | ----------------------------- | ---------------------- | ------------------------ | ---------------------------- | ---------------------------- | ------------------------ | ---------------------------- | ------------------------------ | ------------------------ |
| **Actor**                          | User                         | User                   | User                                | User                 | User                              | Student                    | Instructor                   | User                        | Student                 | User                       | User                         | User                         | User                   | Instructor                  | User                       | Student                |
| **Description**                    | User registers an account    | User browses courses   | User accesses learning materials    | User takes quizzes    | User tracks and manages progress  | Student interacts in forum  | Instructor manages courses   | User learns on mobile device  | Student engages in gamified content | Student receives automated feedback | User accesses external resources | User searches and filters | Instructor monitors progress | User uses video conferencing   | Student participates in peer review |
| **Steps**                          | 1. Provide details and submit | 1. Navigate to courses | 1. Select a course, access materials | 1. Select a quiz       | 1. View progress dashboard         | 1. Comment on posts         | 1. View course analytics      | 1. Access platform on mobile | 1. Complete gamified activities    | 1. Submit assignment for evaluation | 1. Access external learning content | 1. Use advanced search     | 1. View real-time progress   | 1. Join video session         | 1. Review and evaluate peers' work |
|                                    | 2. System validates details  | 2. Filter and search   | 2. View documents, videos, quizzes  | 2. System grades quiz  |                                | 2. Reply to comments         | 2. Modify course content      | 2. Navigate through content   | 2. Earn rewards and badges         | 2. Receive automated feedback    | 2. Explore external resources      | 2. Apply filters            | 2. Receive updates in real-time | 2. Join virtual meeting       | 2. Provide feedback to peers       |
| **Alternative Paths**              | -                            | -                      | -                                   | -                      | -                              | -                          | -                             | -                             | -                      | -                          | -                            | -                            | -                        | -                            | -                              | -                        |
| **Exceptions**                     | -                            | -                      | -                                   | -                      | -                              | -                          | -                             | -                             | -                      | -                          | -                            | -                            | -                        | -                            | -                              | -                        |
| **Post-conditions**                | User account created         | Courses displayed      | Learning materials accessible       | Quiz results recorded  | Progress updated                   | Forum interaction recorded | Analytics displayed           | Platform accessible on mobile | Rewards and badges earned       | Feedback recorded and provided   | External resources accessible     | Search results displayed  | Progress updated in real-time | Video session joined           | Peer reviews completed    |
| **Business Rules**                 | Provide valid and unique info | -                      | User must be logged in              | User must complete quiz| -                              | Appropriate forum etiquette | Instructors manage courses    | Compatible on mobile devices   | Gamification activities completed | Assignments submitted for review | Integration with external tools     | Efficient search performed | Real-time updates enabled     | Compatible video tools used    | Honest and constructive feedback |
| **Related Requirements**           | REQ-001                      | REQ-002                | REQ-003                             | REQ-004               | REQ-005                           | REQ-006                    | REQ-007                       | REQ-008                       | REQ-009               | REQ-010                     | REQ-011                      | REQ-012                      | REQ-013                    | REQ-014                      | REQ-015                        | REQ-016                  |

## Requirements Source Traceability Matrix

| Requirement ID | Source                           |
| -------------- | -------------------------------- |
| REQ-001        | User Stories                     |
| REQ-002        | Business Requirements Document   |
| REQ-003        | User Stories                     |
| REQ-004        | User Stories                     |
| REQ-005        | User Stories                     |

## Requirements Stakeholder Traceability Matrix

| Requirement ID | Stakeholder  |
| -------------- | ------------ |
| REQ-001        | User         |
| REQ-002        | User         |
| REQ-003        | User         |
| REQ-004        | User         |
| REQ-005        | User         |

## Requirements Test Traceability Matrix

| Requirement ID | Test Case ID |
| -------------- | ------------ |
| REQ-001        | TC-001       |
| REQ-002        | TC-002       |
| REQ-003        | TC-003       |
| REQ-004        | TC-004       |
| REQ-005        | TC-005       |

## Requirements Change Traceability Matrix

| Requirement ID | Proposed Change                              |
| -------------- | -------------------------------------------- |
| REQ-001        | Implement multi-factor authentication        |
| REQ-002        | Add search functionality for courses         |
| REQ-003        | Integrate a document preview feature          |
| REQ-004        | Enhance quiz submission process              |
| REQ-005        | Implement a progress visualization dashboard |

## Requirements Release Traceability Matrix

| Requirement ID | Release Version |
| -------------- | --------------- |
| REQ-001        | 1.0             |
| REQ-002        | 1.0             |
| REQ-003        | 2.0             |
| REQ-004        | 1.0             |
| REQ-005        | 2.0             |
