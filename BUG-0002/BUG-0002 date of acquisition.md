## BUG-002: Chainventory 1.0.0: date of acquisition field accepts non-date values





**[Summary]**
When attempting to input data into the "Contact Number" field, the system accepts random text strings (letters) instead of enforcing a valid date format or triggering a date picker UI.


**[Precondition]**
* Software version: 1.0.0
* Software configuration: Opera GX Browser
* Hardware specifications: MSI Thin A15 B7UCX
* Network configuration: Wi-Fi

**[Steps to reproduce]**
1. Navigate to Dashboard and find "New Registration".
2. Navigate to the page containing the "Date of Acquisition" input form.
3. Click or tap into the "Date of Acquisition" field.
4. Type alphabetical characters (e.g. "dasdasda") into the text box.

**[Actual Results]**: The field accepts the text string without any format validation or error warnings.

**[Expected Results]**: The field should strictly reject non-date inputs. It should only accept valid date formats (e.g., MM/DD/YYYY) and ideally utilize a native date picker calendar to prevent manual entry errors.

**[Is this Breakage?]**: No, new implementation


**[Previous code tested]** N/A

**[Severity: How does this problem impact the customer/user?]**: Specification issue (1)  

**[Likelihood: How often will a customer/user use this feature/function?]**: High (8)  

**[Repeatability: Is this problem easily reproducible?]**: 100% Reproducible (10)  

**[Impacted Test Cases]**: REG-0005


**[Impact Sizing (in days)]**: Less than a day
