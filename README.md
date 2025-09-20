# 

# \## Project Overview

# This project involves comprehensive manual testing of the Guru99 Banking application based on the Software Requirements Specification (SRS) version 1.3. The banking system provides net banking facilities with role-based access for Managers and Customers.

# 

# \## Document Information

# \- \*\*Project\*\*: Guru99 Banking Project

# \- \*\*SRS Version\*\*: 1.3 (Final)

# \- \*\*Last Updated\*\*: 19/07/2024

# 

# \## System Roles \& Capabilities

# 

# \### Manager Role

# \*\*Customer Management:\*\*

# \- New Customer creation

# \- Edit Customer details

# \- Delete Customer (only if no active accounts)

# 

# \*\*Account Management:\*\*

# \- New Account creation (Savings/Current)

# \- Edit Account details

# \- Delete Account

# 

# \*\*Transaction Operations:\*\*

# \- Deposit money into any account

# \- Withdrawal from any account

# \- Fund Transfer between any accounts

# \- Balance Enquiry for all supervised accounts

# \- Mini Statement access for any account

# \- Customized Statement generation

# 

# \*\*Security:\*\*

# \- Change own password

# \- Login \& Logout

# 

# \### Customer Role

# \*\*Account Operations:\*\*

# \- Balance Enquiry (own accounts only)

# \- Fund Transfer (from own accounts to any destination)

# \- Mini Statement (own accounts only)

# \- Customized Statement (own accounts only)

# 

# \*\*Security:\*\*

# \- Change own password

# \- Login \& Logout

# 

# \## Key Testing Areas

# 

# \### Functional Testing Modules

# 

# \#### 1. Authentication \& Authorization

# \- Login/Logout functionality

# \- Role-based access control

# \- Password change operations

# 

# \#### 2. Customer Management (Manager Only)

# \- Customer creation with validation

# \- Customer profile editing

# \- Customer deletion with business rules

# 

# \#### 3. Account Management (Manager Only)

# \- Account creation (Savings/Current types)

# \- Account modification

# \- Account deletion with constraints

# 

# \#### 4. Transaction Processing

# \- Fund transfers with validation

# \- Deposit operations

# \- Withdrawal operations

# \- Balance inquiries

# 

# \#### 5. Reporting \& Statements

# \- Mini statements (last 5 transactions)

# \- Customized statements with filters

# \- Transaction history validation

# 

# \### Technical Validation Requirements (110+ Test Cases)

# 

# \#### Form Validation Categories:

# \- \*\*Field Mandatory Checks\*\*: All required fields must be filled

# \- \*\*Data Type Validation\*\*: Numeric fields accept only numbers

# \- \*\*Special Character Restrictions\*\*: Most fields reject special characters

# \- \*\*Format Validation\*\*: Email format, PIN code (6 digits), etc.

# \- \*\*Business Logic Validation\*\*: Account balance checks, duplicate email prevention

# 

# \#### Critical Business Rules:

# \- Minimum initial deposit: ₹500

# \- PIN code must be exactly 6 digits

# \- Customers can only access their own accounts

# \- Managers can only manage accounts under their supervision

# \- Source and destination accounts cannot be the same in transfers

# \- Sufficient balance required for withdrawals/transfers

# 

# \## Browser Compatibility

# \- \*\*Supported\*\*: Chrome version 27 and above only

# \- \*\*Note\*\*: Limited browser support as per project scope

# 

# \## Testing Scope

# 

# \### In Scope:

# \- Functional testing of all specified modules

# \- External interface testing

# \- Form validation testing

# \- Business rule validation

# \- Role-based access testing

# 

# \### Out of Scope:

# \- Non-functional testing (stress, performance)

# \- Automation testing

# \- Cross-browser testing (except Chrome 27+)

# 

# \## Test Environment Setup

# 

# \### Prerequisites:

# \- Chrome browser version 27 or higher

# \- Access to Guru99 Banking demo application

# \- Test data for both Manager and Customer roles

# \- Understanding of banking domain workflows

# 

# \### Test Data Requirements:

# \- Valid customer profiles

# \- Multiple account types (Savings/Current)

# \- Transaction test scenarios

# \- Invalid data sets for negative testing

# 

# \## Quality Assurance Approach

# 

# \### Testing Strategy:

# 1\. \*\*Positive Testing\*\*: Verify all valid scenarios work correctly

# 2\. \*\*Negative Testing\*\*: Ensure proper error handling for invalid inputs

# 3\. \*\*Boundary Testing\*\*: Test field limits and constraints

# 4\. \*\*Role-based Testing\*\*: Validate access controls for different user types

# 5\. \*\*End-to-end Testing\*\*: Complete user workflows from login to logout

# 

# \### Expected Deliverables:

# \- Test case execution reports

# \- Defect logs with severity classification

# \- Functional validation results

# \- Technical requirement compliance report

# \- Final testing sign-off document

# 

# \## Project Constraints

# \- System designed for users with limited computer knowledge

# \- Interface must be intuitive and easy to understand

# \- All changes require approval from Development Lead, QA Lead, and Client

# 



