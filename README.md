# What is UPLX
UPLX is a blockchain powered health data network designed to securely record and store patient consultation, prescription and treatment data. Data recorded in UPLX is securely anonymized using blockchain encryption methodology, enabling unprecedented access to patient data without exposing patient identity and confidentiality. UPLX is designed to be interoperable and easily integrated with any hospital system via API or data entry process.

# UPLX API
UPLX data operations is divided into two phases, **WRITE** and **READ** phase. 
* **WRITE phase** enables medical institutions to record patient information via API integration to HIS (Hospital Information Systems) or EMR (Electronic Medical Record) systems or via manual integration using database extraction or excel files. Data recorded during Write phase is encrypted and anonymized using blockchain private and public key infrastructure. Anonymizing patient data is the process of removing personal identity information such as patient name, NRIC or passport. 
* **READ phase** enables recorded data to be accessed by third parties to perform various data analytics such as big data analytics, machine learning and even AI. Read access to the UPLX network is provided via API integration. Secure API keys are provided to third parties for them to perform read operations of various stages of anonymized patient data.

This combination of **Write** and **Read** operations allows almost real-time access to patient data and enables medical institutions to perform data analytics and inference on a daily basis, on ever changing medical conditions. Developers can build their own application or program to interact with UPLX platform via API to read or write data.

# UPLX Write API
Currently there are 5 wwrite APIs:
- [POST Create a patient](https://github.com/LedgerX-Code/demoapi.uplx.io/wiki/POST--Create-Patient)
- [POST Create Consultation](https://github.com/LedgerX-Code/demoapi.uplx.io/wiki/POST--Create-Consultation)
- [POST Create Issue](https://github.com/LedgerX-Code/demoapi.uplx.io/wiki/POST--Create-Issue)
- [POST Create Prescription](https://github.com/LedgerX-Code/demoapi.uplx.io/wiki/POST--Create-Prescription)
- [PUT Update Patient Details](https://github.com/LedgerX-Code/demoapi.uplx.io/wiki/PUT--Update-Patient-Details)

# UPLX Read API
Currently there are 5 read APIs: 
- [GET Patient Detail](https://github.com/LedgerX-Code/demoapi.uplx.io/wiki/GET--Patient-Detail)
- [GET Prescription_getbypatient](https://github.com/LedgerX-Code/demoapi.uplx.io/wiki/GET--Prescription_getbypatient)
- [GET Consultation_getbypatient](https://github.com/LedgerX-Code/demoapi.uplx.io/wiki/GET--Consultation_getbypatient)
- [GET List Of Patient](https://github.com/LedgerX-Code/demoapi.uplx.io/wiki/GET--List-Of-Patient)
- [GET List Of Issue](https://github.com/LedgerX-Code/demoapi.uplx.io/wiki/GET--List-Of-Issue)

# API Guidelines
**How to get your API Key?**
Before you started with using our API services, you will need to obtain your API key via:
- Request your API key via email.
- Create your own user account. *Not yet available (will be available in future)

# API Guidelines
Click on [Basic API Guideline](https://github.com/LedgerX-Code/API-Guidelines) for basic implmentation of API guidelines.







