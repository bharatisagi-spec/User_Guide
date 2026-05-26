# SourceParts: User Guide
User Guide for SourceParts
## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Placing an Order](#placing-an-order)
4. [Tracking and Managing Orders](#tracking-and-managing-orders)
5. [Managing Your Account](#managing-your-account)
6. [Working with Suppliers](#working-with-suppliers)
7. [Troubleshooting](#troubleshooting)

## Introduction
This section introduces SourceParts.
### 1.1 About SourceParts
SourceParts is an AI-powered, on-demand manufacturing marketplace that connects you - engineers, designers, and procurement professionals - with a global network of vetted manufacturing suppliers. With SourceParts, you upload your design file, configure your specifications, and receive an instant quote in seconds. You no longer spend days negotiating with suppliers or chasing delivery timelines.

SourceParts supports the full manufacturing lifecycle, from rapid prototyping to large-scale production runs. The platform uses AI algorithms to match your job to the best-fit supplier, verify quality, and track your order from placement to delivery - all within a single, unified dashboard.

### 1.2 Who Uses SourceParts
SourceParts serves three primary user types:
- Buyers - You source custom-manufactured parts or assemblies for your projects. You range from early-stage startups to Fortune 500 procurement teams.
- Suppliers - You are a manufacturer or machine shop that receives job opportunities through the marketplace, fills your production capacity, and grows your customer base.
- Administrators - You manage your organization's SourceParts account, set user permissions, view spend analytics, and configure company-wide preferences.

### 1.3 Key Features
| Feature | Description |
|----------|-------------|
| Instant Quoting Engine | Receive accurate pricing and lead times within seconds of uploading your CAD file. |
| AI Supplier Matching | The platform routes your job to the optimal supplier based on capability, location, and capacity. |
| Order Dashboard | Track every order from quote to delivery in one centralized view. |
| Quality Assurance | All suppliers in the network meet verified quality standards before they receive your jobs. |
| All suppliers in the network meet verified quality standards before they receive your jobs. | Order CNC machining, 3D printing, sheet metal fabrication, injection molding, and more from one platform. |
| Team Collaboration | Invite team members, assign roles, and share order history across your organization. |

### 1.4 How This Guide Is Organized
This guide walks you through every aspect of the SourceParts platform. Use the table of contents to jump to the section that is most relevant to your role and task.
- Chapters 1–2: Introduction and getting started
- Chapters 3–4: Placing orders and tracking them
- Chapters 5–6: Managing your account and working with suppliers
- Chapters 7: Troubleshooting
  
## 2. Getting Started
### 2.1 System Requirements
Before you create your account, confirm that your environment meets the following requirements:
| Requirement | Minimum Specification |
|------------|-----------------------|
| Operating System | Windows 10 / macOS 12 / Ubuntu 20.04 or later | 
| Web Browser | Google Chrome 110+, Mozilla Firefox 110+, Microsoft Edge 110+ |
| Internet Connection | Broadband (5 Mbps or faster recommended) |
| CAD File Formats Supported | STEP, IGES, STL, OBJ, SolidWorks (.sldprt), DXF |
| Maximum File Size | 100 MB per file upload |

**Note:** 
SourceParts does not support Internet Explorer. Use one of the supported browsers listed above for the best experience.
### 2.2 Creating Your Account
Follow these steps to create your SourceParts account:
1.	Download and install the application.
2.	Click **Sign Up** button.
3.	Enter your work email address and create a strong password of at least 12 characters.
4.	Select your account type: Buyer, Supplier, or Administrator.
5.	Complete your company profile by entering your company name, industry, and billing address.
6.	Click **Create Account**. SourceParts sends a verification email to the address you entered.
7.	Open the verification email and click Verify My Email. Your account is now active.
**Note:**
Use your work email address when you register. SourceParts uses your email domain to associate your account with your organization's team plan, if one exists.
### 2.3 Signing In
To sign in to your SourceParts account:
1.	Open the application and click **Sign In**.
2.	Enter your registered email address and password.
3.	Click **Continue**.
4.	If two-factor authentication is enabled on your account, enter the verification code received on Okta.
### 2.4 Navigating the Dashboard
After you sign in, the SourceParts dashboard appears. The dashboard contains five primary areas:
- Navigation Bar - Access your order history, account settings, notifications, and help center.
- Quick Actions Panel - Start a new quote, view active orders, or browse supplier capabilities.
-	Order Summary - View a snapshot of your recent and in-progress orders.
-	Spend Analytics - Monitor your spending trends, part counts, and delivery performance.
## 3. Placing an Order
### 3.1 Uploading Your Design File
SourceParts accepts 3D CAD files and 2D drawings. To upload a file:
1.	From your dashboard, click **New Quote**.
2.	Click **Upload File** or drag and drop your design file into the upload area.
3.	Wait for the file analysis to complete. The Instant Quoting Engine analyzes your geometry, identifies the manufacturing features, and prepares the configuration options. This takes under 30 seconds for most files.
4.	Do the part preview that appears on the right side of the screen. Confirm the geometry renders correctly before proceeding.
**Note:** If your part preview shows missing faces or incorrect geometry, your file may contain errors. Use your CAD tool to repair the model and re-upload.
### 3.2 Configuring Your Order
After uploading your file, configure the manufacturing parameters:
#### 3.2.1 Selecting a Manufacturing Process
Choose the process that matches your design requirements. SourceParts supports the following processes:
| Process | Best For | Typical Lead Time |
| ---------|----------|-------------------|
| CNC Machining | Precision metal and plastic parts | 3–7 business days |
| 3D Printing (FDM/SLA/SLS) | Rapid prototypes and complex geometries | 1–5 business days |
| Sheet Metal Fabrication | Enclosures, brackets, and panels | 5–10 business days |
| Injection Molding | High-volume plastic parts | 15–25 business days |
| Die Casting | Metal parts requiring high strength | 10–20 business days |
| Direct Metal Laser Sintering | Metal prototypes with complex features | 5–10 business days |
#### 3.2.2 Choosing Material and Finish
Select the material for your part from the dropdown list. Available materials depend on the process you selected. Then choose a surface finish. Common finish options include:
-	As Machined - No additional finishing; tool marks are visible.
-	Bead Blasted - Uniform matte texture; removes machine marks.
-	Anodized (Type II or Type III) - Corrosion-resistant coating for aluminum parts.
-	Powder Coated - Durable color coating available for metal parts.
-	Painted - Custom color finish; specify color code.
#### 3.2.3 Setting Quantity and Tolerances
Enter the quantity you need. The unit price updates automatically as you adjust the quantity to reflect volume pricing. If your design has tight tolerances, enter the required tolerance values in the Tolerance field.
### 3.3 Reviewing Your Quote
After you configure all parameters, SourceParts displays your instant quote. The quote includes:
- Unit price and total order price
-	Estimated lead time (standard and expedited options)
-	Recommended supplier match and supplier rating
-	Shipping options and estimated delivery date
Compare lead time options side by side. Select the option that balances cost and speed for your project. Click on **Add to Cart** to proceed, or click on **Save Quote** to return to this quote later.
**Note:** Saved quotes remain valid for 30 days. After 30 days, re-upload your file to generate a new quote, as material prices and supplier availability may change.
### 3.4 Checking Out
To complete your **View Cart** order:
1.	Click from the navigation bar.
2.	Review all items in your cart. Edit quantities or remove items as needed.
3.	Select your shipping address or add a new one.
4.	Choose your payment method.
5.	Click **Place Order**. SourceParts confirms your order and sends an order confirmation email to your registered address.

## 4. Tracking and Managing Orders
### 4.1 Viewing Order Status
To track your order, click **Orders** in the navigation bar. Each order displays one of the following statuses:
| Status | Meaning |
|---------|---------|
| Order Confirmed | SourceParts has received your order and assigned it to a supplier.|
| In Production | The supplier is actively manufacturing your part. |
| Quality Inspection | The finished part is undergoing quality checks before shipment.|
| Shipped | Your order is on its way. A tracking number appears in the order details. |
| Delivered | The carrier has delivered your package to the specified address. |
| On Hold | Action is required from you or the supplier. Check the Notes in your order detail page. |
### 4.2 Communicating with Your Supplier
You can send messages directly to your assigned supplier from the order detail page. To do so:
1.	Click **Orders**, then select the relevant order.
2.	Scroll to the Messages section at the bottom of the order detail page.
3.	Type your message and attach any supporting files if needed.
4.	Click **Send**. The supplier receives your message and responds within one business day.
**Note:** Keep all project communication within the SourceParts messaging system. This ensures your conversation is logged and accessible if a dispute arises.
### 4.3 Requesting a Revision
If you need to revise your design or specifications after placing an order, contact your supplier through the messaging system as soon as possible. Revisions are only possible before the order enters the In Production status. If your order is already In Production, click **Request Change** and describe the change. SourceParts reviews the request and notifies you whether the supplier can accommodate it and whether additional charges apply.
### 4.4 Approving Delivery
After your order arrives, inspect the parts against your specifications. Log in to SourceParts and mark the order as Delivery Approved within 5 business days. If you identify a quality issue:
1.	Click **Report an Issue** on the order detail page.
2.	Select the issue type: Dimensional Nonconformance, Surface Defect, Wrong Material, Wrong Quantity, or Other.
3.	Upload photos of the defective parts and describe the issue in the text field.
4.	Click **Submit**. SourceParts opens a quality case and contacts the supplier on your behalf within one business day.

## 5. Managing Your Account
### 5.1 Updating Your Profile
To update your personal or company information:
1.	Click your profile icon in the top-right corner of the dashboard.
2.	Select Account Settings from the dropdown menu.
3.	Edit the relevant fields in the Profile or Company tabs.
4.	Click **Save Changes**.
### 5.2 Managing Team Members
If you are an Administrator, you manage your organization's user accounts from the Team Management page. To access it, go to Account Settings and click the Team tab.
#### 5.2.1	Inviting a New User
1.	Click **Invite User**.
2.	Enter the new user's email address and select their role: Viewer, Buyer, or Administrator.
3.	Click **Send Invitation**. The new user receives an email with a link to activate their account.

#### 5.2.2 Modifying User Roles
1.	Locate the user in the Team Members list.
2.	Click the three-dot menu next to their name and select Edit Role.
3.	Choose the new role from the dropdown and click **Save**.

#### 5.2.3	Removing a User
1.	Click the three-dot menu next to the user's name and select Remove User.
2.	Confirm the action in the dialog box. The user immediately loses access to your organization's account.

**Note:** When you remove a user, their order history remains visible to Administrators. The data is not deleted.
### 5.3 Configuring Notifications
You control which email and in-app notifications SourceParts sends you. Go to Account Settings and click **Notifications** to see the full list. Toggle each notification type on or off based on your preferences. Common notification types include order status changes, quote expiry reminders, supplier messages, and invoice availability.
### 5.4 Billing and Invoices
To view and download invoices, click **Billing** in the navigation bar. SourceParts generates an invoice for each completed order. You download invoices as PDF files. If you pay by purchase order, upload your PO document under Billing > Purchase Orders before placing your first order.
## 6. Working with Suppliers
### 6.1 Understanding Supplier Profiles
Every supplier in the SourceParts network has a public profile that shows their certifications, manufacturing capabilities, customer rating, and on-time delivery rate. To view a supplier profile, click the supplier name on any quote or order detail page.
### 6.2 Approving and Blocking Suppliers
As an Administrator or Buyer, you manage your preferred supplier list from Account Settings > Supplier Preferences:
-	Preferred Suppliers - SourceParts gives these suppliers priority when matching jobs from your account.
-	Blocked Suppliers - SourceParts never assigns jobs from your account to these suppliers.
To add a supplier to either list, search for their name in the Supplier Preferences page and click **Prefer** or **Block**.
### 6.3 Requesting Custom Capabilities
If you need a manufacturing process or material that does not appear in the standard SourceParts catalog, submit a custom capability request:
1.	Click **New Quote** and upload your file as usual.
2.	On the configuration page, click **Request Custom Process**.
3.	Describe your requirements in the text field and attach any supporting documentation (e.g., material datasheets, process specifications).
4.	Click **Submit Request**. A SourceParts sourcing specialist contacts you within two business days to discuss options.

## 7. Troubleshooting
### 7.1 File Upload Issues
| Problem | Likely Cause | Resolution |
| ---------|--------------|------------|
| File upload fails| File exceeds 250 MB limit or is in an unsupported format| Reduce the file size or export it in STEP or STL format.|
| Part preview is blank | File contains geometry errors or is empty | Check the model in your CAD tool and repair any errors before re-uploading.|
| No processes are available for my file | Part dimensions exceed process limits | Review the design guidelines for each process or click **Request Custom Process**.|
| Instant quote takes longer than 60 seconds | Complex geometry or high server load| Wait a few minutes and refresh the page. If the issue persists, contact support.|
### 7.2 Account and Sign-In Issues
| Problem | Resolution |
|----------|------------|
| Forgot password | Click **Forgot Password** on the sign-in page and follow the email instructions. |
| Verification email not received | Check your spam folder. If not there, click **Resend Verification Email** on the sign-in page. |
| Account locked after multiple failed sign-in attempts | Wait 15 minutes and try again, or contact your Administrator to unlock the account.|
| SSO sign-in fails| Contact your IT Administrator to confirm your identity provider settings are correctly configured for SourceParts.|
### 7.3 Payment and Billing Issues
If a payment fails, verify that your card details are current under Billing > Payment Methods. For ACH transfers, confirm that your bank account is correctly linked. If an invoice appears incorrect, click **Dispute Invoice** on the invoice detail page and describe the discrepancy. The SourceParts billing team responds within two business days.
## Appendix A: Glossary
| Term | Definition |
|-------|------------|
| Instant Quoting Engine | The AI system that analyzes your uploaded part and generates pricing and lead time options in real time.|
| Lead Time | The number of business days from order placement to shipment of your finished parts. |
| CAD File | A Computer-Aided Design file that contains the 3D geometry of your part (e.g., STEP, STL, IGES). |
| Tolerance | The permissible deviation from a specified dimension in your part design.|
| Supplier Matching | The process by which SourceParts AI assigns your job to the most suitable supplier in the network.|
## Appendix B: Supported File Formats
| Format | Extension |
|---------|-----------|
|STEP | .step, .stp |
| IGES | .iges, .igs|
| STL | .stl|
| OBJ | .obj|
| SolidWorks Part | .sldprt|
| DXF | .dxf|
| PDF Drawing | .pdf|

##<p align="center"> [Company Logo]

End of SourceParts User Guide  |  Version 1.0  |  May 2026 </p>
