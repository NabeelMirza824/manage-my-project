# FindThatCream – Sprint 1 Review & Retrospective

---

## Sprint Review

### Sprint Goal
Enable admins to securely log in and manage ice cream products, brands, and retailer assignments so the app has real data ready for users to browse.

### Completed Stories

| Story ID | Title                         | Points | Demo Notes                                                                 |
|----------|------------------------------|--------|----------------------------------------------------------------------------|
| US-010   | Admin Secure Login            | 5      | Admin can log in with username/password. JWT token issued on success. Invalid credentials return error message. |
| US-006   | Admin – Add New Product       | 3      | Admin can add a new product with brand, flavor, description, image URL, and dietary flags. Product saves to DB. |
| US-007   | Admin – Assign Retailers      | 5      | Admin can assign Whole Foods, Wegmans, Trader Joe's, and other retailers to any product. Many-to-many relationship working. |
| US-008   | Admin – Mark as New Drop      | 2      | Admin can toggle New Drop flag on any product. Flag saves correctly. |
| US-009   | Admin – Edit Existing Product | 3      | Admin can edit all product fields. Confirmation step works. Changes persist in database. |

**Total Completed: 18 points**

### Not Completed
None — all sprint stories were completed within the 2-week window.

### Stakeholder Feedback
1. **Feedback from product owner:** "Love that the admin can assign multiple retailers to one product — that's the core value of the app."
2. **Feedback from test user:** "Would be great if the admin dashboard showed a count of how many products are marked as New Drops at a glance."
3. **Feedback from advisor:** "Make sure the JWT token expiration is configurable — we may want shorter sessions for security."

---

## Sprint Retrospective

| What Went Well | What Could Improve | Action Items |
|---|---|---|
| JWT auth was implemented cleanly and ahead of schedule | Retailer assignment UI took longer than estimated | Add time buffer for UI tasks in future sprints |
| Many-to-many relationship between products and retailers worked on first try | Daily standups could be more specific about blockers | Create a blockers section in standup template |
| All 5 stories completed with no carry-over | Unit test coverage could be broader | Set a minimum of 3 unit tests per story next sprint |