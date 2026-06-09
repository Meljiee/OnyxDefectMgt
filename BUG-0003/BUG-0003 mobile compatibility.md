## BUG-003: Chainventory 1.0.0: Photo upload functionality fails on mobile device


**[Summary]**
When attempting to upload a photo via a mobile device, the upload process fails. This appears to be a device or browser compatibility issue, as the exact same upload process completes successfully when performed on a desktop environment.

**[Precondition]**
* Software version: 1.0.0
* Software configuration: Opera GX Mobile browser
* Hardware specifications: TECNO SPARK 10
* Network configuration: Wi-Fi

**[Steps to reproduce]**
1. Access the Opera GX Mobile application using a mobile device.
2. Navigate to Dashboard and find "New Registration".
3. Navigate to the page containing the "Proof of Ownership" or "Inspection Images" form.
4. Tap the upload button and select a photo from the device's media gallery.
5. Attempt to submit or complete the upload process.

**[Actual Results]**: The photo fails to upload, it does not display the selected photo.

**[Expected Results]**: The photo should upload successfully and display a confirmation, matching the behavior experienced on the desktop platform.

**[Is this Breakage?]**: No, new implementation


**[Previous code tested]** N/A

**[Severity: How does this problem impact the customer/user?]**: Crash or hang cleared by restart / Severe GUI, usability, and accessibility issue (6) 

**[Likelihood: How often will a customer/user use this feature/function?]**: High (8)  

**[Repeatability: Is this problem easily reproducible?]**: 100% Reproducible (10)  

**[Impacted Test Cases]**: RES-0002


**[Impact Sizing (in days)]**: Less than a day
