# FindThatCream – Product Backlog

## US-001: Browse Ice Cream Products
As a user, I want to browse all available ice cream products so that I can discover new flavors.

Acceptance Criteria:
- [ ] User can see a list of all products on the homepage
- [ ] Each product shows brand name, flavor name, and thumbnail image
- [ ] Products load within 2 seconds
- [ ] User can scroll through all available products

Story Points: 3
Priority: High

---

## US-002: Search for a Flavor
As a user, I want to search for a specific ice cream flavor so that I can quickly find what I'm looking for.

Acceptance Criteria:
- [ ] User can type in a search bar on the homepage
- [ ] Results update to show matching flavors by name or brand
- [ ] If no results found, a friendly message is displayed
- [ ] Search is case-insensitive

Story Points: 3
Priority: High

---

## US-003: Filter by Dietary Preference
As a user with dietary restrictions, I want to filter products by soy-free, gluten-free, or nut-free so that I only see products safe for me.

Acceptance Criteria:
- [ ] Filter options are visible on the browse page
- [ ] User can select one or more filters at a time
- [ ] Product list updates based on selected filters
- [ ] Filter selections persist while browsing

Story Points: 5
Priority: High

---

## US-004: See Retailer Availability
As a user, I want to see which retailers carry a specific flavor so that I know where to go buy it.

Acceptance Criteria:
- [ ] Each product page shows a list of retailers that carry it
- [ ] Retailer name and location type (local vs national) is shown
- [ ] Information is accurate and up to date
- [ ] At least one retailer is shown per product

Story Points: 5
Priority: High

---

## US-005: View New Drops
As a user, I want to see the latest new flavor releases so that I never miss a new drop.

Acceptance Criteria:
- [ ] Homepage has a "New Drops" section
- [ ] Products added within the last 30 days are shown here
- [ ] Each new drop shows brand, flavor, and available retailers
- [ ] Section is sorted by most recently added

Story Points: 3
Priority: High

---

## US-006: Admin – Add New Product
As an admin, I want to add a new ice cream product to the app so that users can discover it.

Acceptance Criteria:
- [ ] Admin can enter brand name, flavor name, description, and image URL
- [ ] Admin can tag dietary flags (soy-free, gluten-free, nut-free)
- [ ] Product is saved to the database upon submission
- [ ] Success message is shown after saving

Story Points: 3
Priority: High

---

## US-007: Admin – Assign Retailers to a Product
As an admin, I want to assign which retailers carry a product so that users know where to find it.

Acceptance Criteria:
- [ ] Admin can select one or more retailers from a list
- [ ] Admin can add a new retailer if it doesn't exist
- [ ] Retailer assignments are saved and linked to the product
- [ ] Admin can update or remove retailer assignments

Story Points: 5
Priority: High

---

## US-008: Admin – Mark a Product as a New Drop
As an admin, I want to mark a product as a "New Drop" so that it appears in the featured section on the homepage.

Acceptance Criteria:
- [ ] Admin can toggle a "New Drop" flag on any product
- [ ] Flagged products appear in the New Drops section
- [ ] Admin can remove the New Drop flag when it's no longer new
- [ ] Change takes effect immediately

Story Points: 2
Priority: Medium

---

## US-009: Admin – Edit Existing Product
As an admin, I want to edit an existing product's details so that information stays accurate.

Acceptance Criteria:
- [ ] Admin can search for and select an existing product
- [ ] All fields are editable (name, description, image, dietary flags)
- [ ] Changes are saved and reflected immediately
- [ ] Admin sees a confirmation before saving changes

Story Points: 3
Priority: Medium

---

## US-010: Admin – Secure Login
As an admin, I want to log in securely so that only authorized users can manage the app's content.

Acceptance Criteria:
- [ ] Admin login page requires username and password
- [ ] Invalid credentials show an error message
- [ ] Successful login redirects to the admin dashboard
- [ ] Session expires after inactivity

Story Points: 5
Priority: High

---

## US-011: View Product Detail Page
As a user, I want to click on a product and see its full details so that I can learn more about it before buying.

Acceptance Criteria:
- [ ] Clicking a product opens a detail page
- [ ] Page shows flavor name, brand, description, dietary info, and retailers
- [ ] Page includes a back button to return to browsing
- [ ] Page loads within 2 seconds

Story Points: 3
Priority: Medium