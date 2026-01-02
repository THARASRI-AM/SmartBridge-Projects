# Metro Ticket Generating System in ServiceNow

## Project Overview
The Metro Ticket Generating System in ServiceNow is an automated service catalog application that enables users to book metro tickets digitally. The system uses ServiceNow Service Catalog and Flow Designer to automate ticket booking, fare processing, and backend data storage, reducing manual effort and improving efficiency.

---

## Objectives
- To automate metro ticket booking using ServiceNow
- To provide a user-friendly service catalog interface
- To calculate and capture ticket details accurately
- To store metro ticket data in a custom table for tracking
- To demonstrate workflow automation using Flow Designer

---

## Technologies Used
- ServiceNow Service Catalog  
- ServiceNow Flow Designer  
- Custom Tables (Metro Station’s Details)  
- UI Policies and Client Scripts  
- GitHub (for version control and documentation)

---

## System Features
- Metro ticket booking through Service Catalog
- Support for QR Ticket and Metro Card recharge
- Dynamic form behavior based on user selections
- Mandatory field validation
- Automated backend processing using Flow Designer
- Secure storage of booking details in custom tables
- Order confirmation and request tracking

---

## Workflow Description
1. User opens the **Book A Metro Ticket** catalog item.
2. User enters journey, station, and payment details.
3. Upon submission, the Flow Designer workflow is triggered.
4. Catalog variables are captured automatically.
5. Ticket details are stored in the Metro Station’s Details table.
6. User receives a confirmation with request number.

---

## Testing Summary
### Level 1 Testing
- Validated Flow Designer execution
- Verified catalog variable capture
- Confirmed record creation in backend table

### Level 2 Testing
- Validated end-to-end user flow
- Verified form submission and order confirmation
- Confirmed successful automation after user request

---

## Project Structure

