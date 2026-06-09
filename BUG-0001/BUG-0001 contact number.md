## BUG-001: Chainventory 1.0.0: Contact Number field accepts alphabetical characters


**[Summary]**
When attempting to input data into the "Contact Number" field, the system accepts letters instead of restricting the input exclusively to numeric digits.

**[Precondition]**
* Software version: 1.0.0
* Software configuration: Opera GX Browser
* Hardware specifications: MSI Thin A15 B7UCX
* Network configuration: Wi-Fi

**[Steps to reproduce]**
1. Navigate to Dashboard and find "New Registration".
2. Navigate to the page containing the "Contact Number" input form.
3. Click or tap into the "Contact Number" field.
4. Type alphabetical characters (e.g. "abcd") into the text box.

**[Actual Results]**: The field accepts the letters and displays them as valid input.

**[Expected Results]**: The field should strictly reject non-numeric characters and only allow numbers (and optionally standard formatting symbols like +, -, or spaces).

**[Is this Breakage?]**: No, new implementation


**[Previous code tested]** N/A

**[Severity: How does this problem impact the customer/user?]**: Specification issue (1)  

**[Likelihood: How often will a customer/user use this feature/function?]**: High (8)  

**[Repeatability: Is this problem easily reproducible?]**: 100% Reproducible (10)  

**[Impacted Test Cases]**: REG-0002


**[Impact Sizing (in days)]**: Less than a day
