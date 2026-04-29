# FindThatCream – Sprint 1 Plan

## Sprint Goal
Enable admins to securely log in and manage ice cream products, brands, and retailer assignments so the app has real data ready for users to browse.

## Sprint Duration
2 Weeks — May 1, 2026 to May 14, 2026

## Team Capacity
20 Story Points

## Sprint Backlog

| Story ID | Title                          | Points | Technical Tasks                                                                 |
|----------|-------------------------------|--------|---------------------------------------------------------------------------------|
| US-010   | Admin Secure Login             | 5      | - Design login page UI mockup                                                   |
|          |                               |        | - Create Admin entity and database table                                        |
|          |                               |        | - Implement login form and validation                                           |
|          |                               |        | - Add session/token handling                                                    |
|          |                               |        | - Test login with valid and invalid credentials                                 |
| US-006   | Admin – Add New Product        | 3      | - Design Add Product form                                                       |
|          |                               |        | - Create Product entity and database table                                      |
|          |                               |        | - Implement save product logic                                                  |
|          |                               |        | - Connect dietary flag fields to product                                        |
|          |                               |        | - Write unit tests for product creation                                         |
| US-007   | Admin – Assign Retailers       | 5      | - Create Retailer entity and database table                                     |
|          |                               |        | - Design product-retailer relationship (many-to-many)                           |
|          |                               |        | - Build retailer assignment UI in admin panel                                   |
|          |                               |        | - Implement save/update retailer assignment logic                               |
|          |                               |        | - Test retailer assignment and removal                                          |
| US-008   | Admin – Mark as New Drop       | 2      | - Add isNewDrop boolean field to Product entity                                 |
|          |                               |        | - Build toggle UI in admin panel                                                |
|          |                               |        | - Implement update logic for new drop flag                                      |
|          |                               |        | - Verify flagged products surface correctly                                     |
| US-009   | Admin – Edit Existing Product  | 3      | - Build edit product form pre-filled with existing data                         |
|          |                               |        | - Implement update logic in backend                                             |
|          |                               |        | - Add confirmation step before saving                                           |
|          |                               |        | - Test edits persist correctly in database                                      |

## Total Points Selected: 18
## Buffer: 2 points reserved for bug fixes and unexpected tasks