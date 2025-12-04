# BioCLIP – Privacy Policy
**Last updated:** December 2025

BioCLIP (“the App”, “we”, “our”) respects your privacy. This Privacy Policy explains what information is (and is not) collected, how the App works, and your rights as an Android user.

---

## 1) Overview
BioCLIP is an **on-device** species identification application. All processing—including image embedding generation, classification, and result display—occurs **locally on your device**.

- The App **does not collect, store, transmit, or share** any personal data.  
- The App contains **no analytics SDKs, no logging frameworks that export data, and no networking code** for telemetry or remote inference.

**Architecture notes (for transparency):**
- Images are selected from the camera, gallery, or Files app, processed only locally, and never uploaded to any server.
- Classification happens entirely on-device using the compressed model.
- The App does not make outbound network requests for identification.

> **Summary:** The App performs all species identification **offline**. We do not see, receive, or store your images or any personal information.

---

## 2) Information We Collect
**We do NOT collect personal information.** Specifically, we do not collect:

- Photos or media stored on your device  
- Names, email addresses, or contact information  
- Device identifiers (e.g., Advertising ID, IMEI)  
- Location data (foreground or background)  
- User behavior or analytics (usage events, session data)  
- IP address or any network metadata

### Local-Only Image Access
When you choose a photo (via camera, gallery, or file picker), the image is provided directly to the App’s on-device classification model and is **never transmitted** or stored externally. Images remain strictly on your device.

---

## 3) How Your Data Is Used
Because BioCLIP performs **on-device AI inference**, any image you select is used **only** to identify species.

Operationally, the App:
1. Loads the image into memory
2. Performs local inference
3. Displays the results
4. Discards the image when you return to the home screen

> **Summary:** There is **no data sharing, logging, or transmission**.

---

## 4) Data Sharing
We **do not share** any data with third parties.

- No servers receive your images  
- No analytics providers receive usage data  
- No advertisers, affiliates, or partners receive information  
- The App contains **no tracking technologies** (no cookies, no ad identifiers, no profiling)

---

## 5) Data Retention
The App **does not retain** your data.

- Images are stored in temporary memory only  
- When the App is closed or you return home, they are removed  
- Classification results are **not saved, uploaded, or cached**  
- No data persists beyond your immediate use of the App

---

## 6) Children’s Privacy
BioCLIP does **not** collect personal data from users of any age. The App is safe for children and is designed to be consistent with COPPA requirements because **no data is collected or transmitted**.

---

## 7) Permissions Used
BioCLIP requests **only** the permissions necessary for core functionality:

- **Camera (optional)**  
  Used only when you capture a photo for species identification. Images never leave the device.

- **Photos / Media (optional)**  
  Allows selecting an existing image for analysis. Images remain on-device only.

- **File Access (optional)**  
  Allows you to pick an image file from your device storage. No files are uploaded or shared.

The App **does not request** background location, contacts, microphone, SMS, call logs, calendar, or other sensitive permissions.

---

## 8) Security
Because images and results **never leave your device**, exposure risk is minimized. The App performs all inference locally and does not import or transmit data to servers, reducing typical network-based attack vectors. You remain responsible for the physical and OS-level security of your device (e.g., screen lock, OS updates).

---

## 9) Third-Party Services
BioCLIP uses **no third-party services** that process user data.

- No cloud inference  
- No analytics SDKs  
- No social media integrations  
- No advertising frameworks

---

## 10) International Users & Legal Bases
The App does not process personal data. If you are in a jurisdiction with specific privacy laws (e.g., GDPR, CCPA, LGPD), our data practices are simple: **we do not collect, retain, or share personal data**. Should this change in a future version, we will update this Policy and (where required) request consent.

---

## 11) Your Rights
Because the App does not collect or store personal data, there is **no personal data to access, correct, delete, or export**. If you have questions about this Policy or how the App works on-device, please contact us using the details below.

---

## 12) Changes to This Privacy Policy
We may update this Privacy Policy from time to time. Updates will be reflected in the **“Last updated”** date at the top of the document. Material changes will be described in the release notes and/or this page.

---

## 13) Contact Us
If you have any questions regarding this Privacy Policy or the App’s data practices, please contact:

- **Repository / Issue Tracker** (optional): [Link to GitHub Issue](https://github.com/Imageomics/bioclip-app/issues)

---

## 14) Data Safety Statement (for Google Play Console)
- **Data collected:** None  
- **Data shared:** None  
- **Data encrypted in transit:** Not applicable (no transmission)  
- **Data deletion:** Not applicable (no collection or retention)  
- **Location, Personal info, Financial info, Health & fitness, Messages, Photos & videos, Audio files, Files & docs, Calendar, Contacts, App activity, App info & performance, Device or other IDs:** **Not collected**

> If the App’s behavior changes in a future release (e.g., optional cloud features), this Policy and the Google Play Data Safety form will be updated **before** the changes take effect.
