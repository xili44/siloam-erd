# HIS.PatientTrx to SDA class mappings


## Admission.cls --> HS.SDA3.Address, H3.SDA3.ContactInfo, H3.SDA3.Encounter
| HIS                                   | SDA3                          |
| ------------------------------------- | ----------------------------- |
| Address                               |                               |
| AdmissionCoverageTypeDR               |                               |
| AdmissionCoverageTypeId               |                               |
| AdmissionDate                         |                               |
| AdmissionDependencyTypeDR             |                               |
| AdmissionDependencyTypeId             |                               |
| AdmissionDiscountTypeDR               |                               |
| AdmissionDiscountTypeId               |                               |
| AdmissionId                           |                               |
| AdmissionNo                           |                               |
| AdmissionStatusDR                     |                               |
| AdmissionStatusId                     |                               |
| AdmissionSubDischargeStatusDR         |                               |
| AdmissionSubDischargeStatusId         |                               |
| AdmissionSubTypeDR                    |                               |
| AdmissionSubTypeId                    |                               |
| AdmissionTypeDR                       |                               |
| AdmissionTypeId                       | Encounter.AdmissionType.ID    |
| ArInvoiceDR                           |                               |
| ArInvoiceId                           |                               |
| BedArItemId                           |                               |
| BedTransferDR                         |                               |
| BirthDate                             |                               |
| CancelDate                            |                               |
| CancelNotes                           |                               |
| CancelReasonId                        |                               |
| CancelUserId                          |                               |
| CityDR                                |                               |
| CityId                                | Address.City.ID               |
| ClassDR                               |                               |
| CodingDate                            |                               |
| ContactAddress                        |                               |
| ContactCityDR                         |                               |
| ContactCityId                         |                               |
| ContactEmailAddress                   |                               |
| ContactMobileNo                       |                               |
| ContactName                           |                               |
| ContactPhoneNo                        |                               |
| CoverageDR                            |                               |
| CoverageId                            |                               |
| CreateDate                            |                               |
| CreateUserId                          |                               |
| DefaultLimitNumericFactor             |                               |
| DefaultLimitTypeId                    |                               |
| DepositBalanceAmount                  |                               |
| DischargeDR                           |                               |
| DischargeDate                         |                               |
| DischargeId                           |                               |
| DischargeRequestDR                    |                               |
| DischargeRequestId                    |                               |
| DiseaseClassificationDR               |                               |
| DiseaseClassificationId               |                               |
| EmailAddress                          | ContactInfo.EmailAddress      |
| EmailTypeDR                           |                               |
| EmailTypeId                           |                               |
| EmployeeId                            |                               |
| ExternalDoctorDR                      |                               |
| InvoiceClassId                        |                               |
| IsPatientRegistered                   |                               |
| LimitTypeDR                           |                               |
| MedicalOrderItemDR                    |                               |
| MedicalOrderItemId                    |                               |
| Name                                  |                               |
| Notes                                 |                               |
| OrganizationDR                        |                               |
| OrganizationId                        |                               |
| ParentAdmissionDR                     |                               |
| ParentAdmissionId                     |                               |
| PatientDR                             |                               |
| PatientId                             | Encounter.AccountNumber       |
| PatientOrganizationDR                 |                               |
| PatientOrganizationId                 |                               |
| PatientTypeDR                         |                               |
| PatientTypeId                         |                               |
| PayerDR                               |                               |
| PayerEligibilityId                    |                               |
| PayerEligibilityNo                    |                               |
| PayerId                               |                               |
| PayerIdNo                             |                               |
| PayerLimitAmount                      |                               |
| PhoneNo                               | ContactInfo.MobilePhoneNumber |
| PrimaryDoctorUserDR                   |                               |
| PrimaryDoctorUserId                   |                               |
| ProcedureRoomId                       |                               |
| ReferralAdmissionId                   |                               |
| ReferralAdmissionIdDR                 |                               |
| ReferralAdmissionNo                   |                               |
| ReferralAdmissionTypeDR               |                               |
| ReferralAdmissionTypeId               |                               |
| ReferralDoctorUserId                  |                               |
| ReferralExternalDoctorId              |                               |
| ReferralExternalOrganizationDR        |                               |
| ReferralExternalOrganizationId        |                               |
| ReferralInterOrganizationDoctorUserDR |                               |
| ReferralInterOrganizationDoctorUserId |                               |
| ReferralName                          |                               |
| ReferralOnlineAggregatorId            |                               |
| ReferralPhoneNo                       |                               |
| ReferralTypeDR                        |                               |
| ReferralTypeId                        |                               |
| SalesDiscountDR                       |                               |
| SalesDiscountId                       |                               |
| SexDR                                 |                               |
| SexId                                 |                               |
| UpdateDate                            |                               |
| UpdateUserId                          |                               |


## BedTransfer.cls --> ?


## Discharge.cls --> ?


## DischargeRequest.cls --> ?


## SubDischarge.cls --> ?