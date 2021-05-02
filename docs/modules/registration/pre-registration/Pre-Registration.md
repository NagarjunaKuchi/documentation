# Overview
This module enables a resident to:

* Enter demographic data & upload supporting documents
* Book an appointment for one or many users for registration by choosing a suitable registration center and time slot
* Receive appointment notifications
* Reschedule and cancel appointments

Resident data is sent to the designated registration center before the appointment that can be used during the registration process.

# Detailed functionality

Below are the links to detailed features of the pre-registration module,
* [Login/create a user account](Login-or-create-a-user-account.md)
* [Creating an application](Creating-an-application.md)
* [Attaching documents to an application](Attaching-documents-to-an-application.md)
* [Booking an appointment](Booking-an-appointment.md)
* [Appointment acknowledgment](Appointment-acknowledgment.md)
* [Batch jobs](Batch-jobs.md)
* [Data sync](Data-sync.md)

# Process flow

Process flow diagram for creating and update flows in Pre-registration.

![](_images/pre_registration_process_flow-create_or_update_applications.png)

Process flow diagram for cancel and discard flow is Pre-registration.

![](_images/pre_registration_process_flow-cancel_or_discard_applications.png)

# Services

For detailed description of Pre-registration services refer to [pre-registration repo](https://github.com/mosip/pre-registration).

For high level and low level design refer to [pre-registration repo/design](https://github.com/mosip/pre-registration/design)

# Logical View

Below is the diagram depicts the logical architecture of Pre-registration,

![](_images/pre_registration-logic_architecture_diagram.png)

# Build and deploy
Refer to build and deploy instructions in [pre-registration repo](https://github.com/mosip/pre-registration).

# APIs
For detailed functionality of Pre-registration APIs please view our page, [Pre-registration APIs](../../../api-reference/Pre-Registration-APIs.md)

# UI Reference Implementation
MOSIP provides a reference implementation of the Pre-registration UI that may be customized as per country needs. The implementation is available on [reference implementation repository](https://github.com/mosip/mosip-ref-impl).

# Configurations
Refer to the [pre-registration configuration](Pre-Registration-Configuration.md) document for details about the configurations in pre-registration.