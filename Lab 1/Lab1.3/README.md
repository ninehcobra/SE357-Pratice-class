<h3>Requirements Linkage Traceability Matrix</h3>

| Requirement ID | Functional Requirement                  | Non-Functional Requirement                            | Source                         | Stakeholder  | Test Case ID | Proposed Change                            | Release Version |
| -------------- | --------------------------------------- | ----------------------------------------------------- | ------------------------------ | ------------ | ------------ | ------------------------------------------ | --------------- |
| REQ-001        | User login                              | Security: User authentication                         | User Stories                   | User         | TC-001       | Change in login mechanism                  | 1.0             |
| REQ-002        | User can make donation                  | Security: User authentication and Bank authentication | Business Requirements Document | User         | TC-002       | Increase response time for making donation | 2.0             |
| REQ-003        | User can access events                  | Content: Information about the event                  | Business Requirements Document | User         | TC-003       | Add support for downloadable documents     | 1.0             |
| REQ-004        | User can participate in an organization | Content: Information about the organization           | User Stories                   | User         | TC-004       | Improve quiz navigation                    | 2.0             |
| REQ-005        | Organization can hold an event          | Scalability: Ability to handle large member           | Business Requirements Document | Organization | TC-005       | Fast update information and donation       | 1.0             |

|                              | Requirement | REQ-001 | REQ-002 | REQ-003 | REQ-004 | REQ-005 |
| ---------------------------- | ----------- | ------- | ------- | ------- | ------- | ------- |
| Usecase                      |             |         |         |         |         |         |
| Đăng ký                      |             |         |         |         |         |         |
| Xem bài viết                 |             | R       |         |         |         | R       |
| Quản lý thông tin người dùng |             | U       |         |         |         | R       |
| Đăng nhập                    |             | R       |         |         |         |         |
| Quản lý tài khoản ngân hàng  |             | U       | U       |         |         |         |
| Quản lý quỹ từ thiện         |             | U       | R       |         | U       | U       |
| Quản ký bài viết             |             | U       |         | U       | R       | U       |
| Thay đổi thông tin cá nhân   |             | U       |         |         |         |         |
| Lấy thông tin sao kê         |             | U       | U       | R       | R       | R       |
| Đăng ký gây quỹ              |             | U       | R       | U       | R       | U       |
| Thanh toán tiền gây quỹ      |             | U       | U       | R       | R       | U       |
| Ủng hộ                       |             | U       | U       | R       | R       | R       |
| Xóa bài viết                 |             | U       |         | U       | R       |         |

<h3>Requirements Source Traceability Matrix</h3>

| Requirement ID | Source                         |
| -------------- | ------------------------------ |
| REQ-001        | User Stories                   |
| REQ-002        | Business Requirements Document |
| REQ-003        | Business Requirements Document |
| REQ-004        | User Stories                   |
| REQ-005        | Business Requirements Document |

<h3>Requirements Stakeholder Traceability Matrix</h3>

| Requirement ID | Stakeholder  |
| -------------- | ------------ |
| REQ-001        | User         |
| REQ-002        | User         |
| REQ-003        | User         |
| REQ-004        | User         |
| REQ-005        | Organization |

<h3>Requirements Test Traceability Matrix</h3>

| Requirement ID | Test Case ID |
| -------------- | ------------ |
| REQ-001        | TC-001       |
| REQ-002        | TC-002       |
| REQ-003        | TC-003       |
| REQ-004        | TC-004       |
| REQ-005        | TC-005       |

<h3>Requirements Change Traceability Matrix</h3>

| Requirement ID | Proposed Change                            |
| -------------- | ------------------------------------------ |
| REQ-001        | Change in login mechanism                  |
| REQ-002        | Increase response time for making donation |
| REQ-003        | Add support for downloadable documents     |
| REQ-004        | Improve quiz navigation                    |
| REQ-005        | Fast update information and donation       |

<h3>Requirements Release Traceability Matrix</h3>

| Requirement ID | Release Version |
| -------------- | --------------- |
| REQ-001        | 1.0             |
| REQ-002        | 2.0             |
| REQ-003        | 1.0             |
| REQ-004        | 2.0             |
| REQ-005        | 1.0             |