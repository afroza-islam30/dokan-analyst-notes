## Feature Request
**Title**: Allow vendors to pause their store temporarily while being unavailable.

**Context**: Vendors on a Dokan marketplace may need to take short breaks for holidays, illness, travel, or personal reasons. During this time, they may not be able to process, pack, or ship new orders. Currently, if a vendor is unavailable but their store remains active, customers can still place new orders. This may cause customer complaints, refund requests, and a poor marketplace experience.
This feature is needed so vendors can temporarily pause their store without permanently closing it or removing products.

**User**: Dokan marketplace vendor

**Scope**:
In scope for v1

•	Vendor can enable “Pause Store” from their vendor dashboard. 

•	Vendor can select a start date and end date. 

•	Vendor can add an optional message, such as: “This store will reopen on May 15.” 

•	Customers cannot place new orders from the paused vendor. 

•	Existing orders remain visible and manageable by the vendor.

•	Store automatically reopens after the selected end date.

•	Vendor can manually resume store before the end date.

Explicitly out of scope for v1:

•	Pausing only specific products.

•	Allowing pre-orders during the pause period. 

•	Admin approval before a vendor can pause their store. 

•	Cancelling or modifying existing orders automatically. 
**Value**:
**User value:** Vendors can take planned breaks without worrying about receiving orders they cannot fulfill.

**Customer value:** Customers get a clear message before trying to order, reducing confusion and disappointment.

**Business value:** The marketplace can reduce delayed orders, refund requests and negative customer experiences.

# Bug Report:
**Title:** Vendor store banner upload completes, but the updated banner is not saved after refresh
**Context:** A vendor is trying to update their store banner image from the Dokan vendor dashboard. The upload progress bar reaches 100%, which makes the vendor believe the new banner has been uploaded successfully.
However, after refreshing the store page or viewing the storefront, the old banner image is still displayed. This creates confusion because the UI indicates success, but the actual store banner does not change.
**User:** Dokan marketplace vendor who attempts to replace their existing store banner image.
Expected behavior: When the vendor uploads a new store banner image and the upload completes, the new image should be saved and displayed on:
•	Vendor store settings page

•	Vendor storefront 

•	Page refresh 

•	Later visits to the store 

**Actual behavior:**
The upload progress bar completes, but the old banner image remains visible after refreshing the page. The new banner does not appear to be saved or applied.
**Steps to reproduce:**

Preconditions:

•	Dokan marketplace is active. 

•	A vendor account exists. 

•	The vendor already has an existing store banner image.

•	Vendor is logged in and has access to the vendor dashboard. 

•	A valid replacement banner image is available, for example: .jpg or .png. 

**Steps**
1. Log in as a vendor.

2. Go to Vendor Dashboard.
	
3. Open Store Settings.
		
4. Locate the Store Banner upload section.
	
5. Upload a new valid banner image.
	
6. Wait until the upload progress bar reaches 100%.
	
7. Save/update the store settings, if a save button is required.
	
8. Refresh the store settings page.
	
9. Open the vendor storefront in the browser.

10. Check which banner image is displayed

**Value:**

Severity: Medium

The issue does not block checkout or order processing, but it prevents vendors from updating important store branding.

Priority: High

Store appearance is important for vendor trust and marketplace presentation. The misleading upload success state should be fixed quickly because vendors may assume the system is broken.

## Enhancement request:
**Title:** Improve vendor earnings visibility with product details and time-based breakdowns

**Context:** The current Dokan vendor earnings page shows total earnings as a single number. While this gives vendors a basic overview, it does not help them understand where their earnings are coming from. Vendors need more detailed earnings visibility to understand which products are performing well, which time periods generate the most revenue, and how their store is performing over days, weeks, or months.

The current state is insufficient because vendors cannot easily analyze earnings patterns or make informed business decisions from one total number alone.

User who benefits: Dokan marketplace vendor who sells multiple products and wants to understand which products are generating the most earnings over a selected time period.

Vendors should be able to view their earnings broken down by:

•	Product 

•	Time period 

•	Total earnings within the selected period

**Measurable outcome:** Vendors should be able to answer “Which product earned how much during this time period?” directly from the earnings page without checking individual orders manually.

**Scope:** The enhancement should improve visibility only. It must not change the existing earnings calculation or payment-related behavior.

**Value:** This enhancement turns the earnings page from a simple summary into a more useful business insight page, without changing the actual earnings calculation.

**Vendor value:** Vendors can better understand their store performance and make smarter decisions about pricing, inventory, and product focus.

**Business value:** A clearer earnings page makes Dokan more useful for serious vendors, improves vendor satisfaction, and reduces confusion.

