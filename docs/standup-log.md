# FindThatCream – Sprint 1 Daily Standup Log

---

## Day 1 – Monday, May 1
**What I did yesterday:** Completed sprint planning, finalized story selection and task breakdown
**What I'm doing today:** Starting US-010 – designing admin login page UI mockup and planning the Admin database table
**Blockers:** None

---

## Day 2 – Tuesday, May 2
**What I did yesterday:** Completed admin login UI mockup, started Admin entity design
**What I'm doing today:** Creating Admin entity and setting up the database table, implementing login form validation
**Blockers:** Need to decide whether to use session-based auth or JWT for admin login — leaning toward JWT to align with future security plans

---

## Day 3 – Wednesday, May 3
**What I did yesterday:** Admin entity created, login form validation implemented, decided on JWT for auth
**What I'm doing today:** Finishing token handling for admin login (US-010), then starting US-006 – Add New Product form
**Blockers:** None

---

## Day 4 – Thursday, May 4
**What I did yesterday:** Completed US-010 admin login with JWT. Starting US-006 product creation
**What I'm doing today:** Creating Product entity and database table, connecting dietary flag fields (soy-free, gluten-free, nut-free)
**Blockers:** Need to confirm which dietary flags to support at launch — confirmed: soy-free, gluten-free, nut-free

---

## Day 5 – Friday, May 5
**What I did yesterday:** Product entity and dietary flags implemented, save product logic working
**What I'm doing today:** Writing unit tests for product creation (US-006), then beginning US-007 retailer assignment
**Blockers:** None

---

## Day 6 – Monday, May 8
**What I did yesterday:** Finished US-006 including unit tests. Started US-007 Retailer entity design
**What I'm doing today:** Designing the product-retailer many-to-many relationship and creating the Retailer table
**Blockers:** Clarifying whether retailers like Trader Joe's and Target should be included at launch — decided yes as optional

---

## Day 7 – Tuesday, May 9
**What I did yesterday:** Retailer entity and product-retailer relationship table created
**What I'm doing today:** Building retailer assignment UI in admin panel, implementing save and update logic
**Blockers:** None

---

## Day 8 – Wednesday, May 10
**What I did yesterday:** Retailer assignment UI completed, save/update logic working
**What I'm doing today:** Testing retailer assignment and removal, then starting US-008 New Drop toggle
**Blockers:** None

---

## Day 9 – Thursday, May 11
**What I did yesterday:** US-007 fully tested and complete. Added isNewDrop field to Product entity
**What I'm doing today:** Building New Drop toggle UI in admin panel (US-008), implementing update logic
**Blockers:** None

---

## Day 10 – Friday, May 12
**What I did yesterday:** US-008 complete. New Drop flag working correctly
**What I'm doing today:** Starting and completing US-009 – Edit Product form with pre-filled data and confirmation step
**Blockers:** None