# HIS.MedicalTrx to SDA class mappings

## DiseaseClassificationRecord --> HS.SDA3.Diagnosis

This class can be roughly mapped to HS.SDA3.Diagnosis
| HIS                           | SDA3                   |
| ----------------------------- | ---------------------- |
| AdmissionDR                   |                        |
| AdmissionId                   |                        |
| CreateDate                    | EnteredOn              |
| CreateUserId                  | EnteredBy.ID           |
| DiseaseClassificationDR       | Diagnosis              |
| DiseaseClassificationId       |                        |
| DiseaseClassificationRecordId | ID                     |
| DoctorUserId                  | DiagnosingClinician.ID |
| IsNewCase                     |                        |
| IsPrimary                     |                        |
| UpdateDate                    |                        |
| UpdateUserId                  |                        |

## MedicalEncounter --> HS.SDA3.Encounter

| HIS                         | SDA                                                                |
| --------------------------- | ------------------------------------------------------------------ |
| AdmissionDR                 |                                                                    |
| AdmissionId                 |                                                                    |
| ArItemDR                    |                                                                    |
| ArItemId                    |                                                                    |
| CreateDate                  | EnteredOn                                                          |
| CreateUserId                | EnteredBy.ID                                                       |
| Date                        |                                                                    |
| EncounterDate               | FromTime                                                           |
| EncounterUserDR             | AdmittingClinician/AttendingClinician/ConsultingClinician          |
| EncounterUserId             | AdmittingClinician.ID/AttendingClinician.ID/ConsultingClinician.ID |
| MedicalEncounterID          | EncounterNumber                                                    |
| MedicalEncounterTypeDR.Code | EncounterType                                                      |
| MedicalEncounterTypeId      |                                                                    |
| OrganizationDR              | HealthCareFacility/EnteredAt                                       |
| OrganizationId              | HealthCareFacility.ID/EnteredAt.ID                                 |
| PatientDR                   |                                                                    |
| PatientId                   | AccountNumber(?)                                                   |
| PatientOrganizationDR       |                                                                    |
| PatientOrganizationId       |                                                                    |
| SalesRequestItemDR          |                                                                    |
| SalesRequestItemId          |                                                                    |
| UpdateDate                  |                                                                    |
| UpdateUserId                |                                                                    |
| UserDR                      |                                                                    |
| UserId                      |                                                                    |

## MedicalOrder --> HS.SDA3.AbstractOrder

## MedicalOrderItem

## ProcedureClassificationRecord
