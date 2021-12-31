# ID Lifecycle Management

Identity Lifecycle management refers to the **process of issuing and managing user identities** in a given system. 
The various life cycle events are briefly explained below:

* New ID issuance (for adults and infants).
* ID data update/update individual’s information.
* De-activate/re-activate individual’s ID.
* Lost ID.

## New ID Issuance 

### Pre-Registration
Pre-registration fundamentally helps the residents and Government organizations by saving the time and efforts required for basic data collection of the residents at the registration centers. The resident can visit the pre-registration portal and do the following:
* Enter demographic data and upload supporting documents
* Book an appointment for one or many users for registration by choosing a suitable registration center and a convinient time slot
* Receive appointment notifications
* Reschedule and Cancel appointments

Once the resident completes the above process, their data will be downloaded at the respective registration centers prior to their appointment.

#### For Adults
-	Resident/individual needs to visit a registration center
-	Provide required information to register themselves in MOSIP (first time)
-	Registration officer captures’ individual’s information
-	The captured information is sent to the Registration Processor
-	Various checks like biometrics quality, de-duplication, etc. performed in the Registration Processor with the individual's demographic data and biometrics
-	If no duplicate is found, a Unique Identification Number(UIN) is allocated and ID credentials are sent to the individual via the country's configured printing and postal service.
-	Registration receipt(acknowledgement) containing the Registration Identity(RID), labels and data in the configured language, QR code (of the RID) provided to the resident at the center.
-	Notifications sent to the resident using the email ID and mobile number provided as a apart of demographic data collection

#### For Infants/Children

-	Child needs to visit the Registration center along with a guardian/parent.
-	Child does not have to give biometrics but need to capture the child' photograph.
-	Parent/guardian' UIN or RID and biometrics needed for authentication.
-	Additionally, a **Proof of Relationship** document to be provided at the center.
-	An acknowledgement receipt will be provided to the infant' parent/guardian.

## ID Data Update/ Updating individual’s information

-	Residents can update their information in two ways:
    * By visiting the registration center: The demographic and biometric information can be updated at the centers.
    * Using Resident services: Update of only the demographic information.
-  Registration receipt containing the Registration Identity(RID)), labels and data in the configured language, QR code (of the RID) provided to the resident at the center.
-	Updated ID credentials sent to the resident via the country’ configured printing and postal service.
-	Notifications sent to the resident using the email ID and mobile number provided as a apart of demographic data collection

## De-activate\Re-activate individual’s ID

-	De-activate authentication against user' ID. <<check>>
-	Individual will not be able to authenticate themselves by using UIN or VID in case of deactivation or vice-versa for re-activation.
-	If a country wants to deactivate an individual’s ID for any specific reason, the system deactivates the individual’s ID after certain validations performed in Registration Processor. Likewise, a country can also re-activate an individual’ ID.

## Finding a Lost ID
-	Individual to provide their biometric information in the Registration center.
-  De-duplication performed to find the individual' ID.
-  Registration receipt containing Registration Identity(RID)), labels and data in the configured language, QR code (of the RID) provided to the resident.
-  ID credentials sent to the resident via the country’ configured printing and postal service.
- Notifications sent to the resident using the email ID and mobile number provided as a apart of demographic data collection
   


