GCHA WBS Dictionary

Purpose
This dictionary defines the Definition of Done (DoD) for key work packages.

---

BAN-001: Nurse Login Screen Development

Description:
Develop secure login screen for nurses via mobile app. Must support biometric authentication (fingerprint, Face ID) and username/password. Integration with Cairo's authentication API required.

Assigned To: Bangalore Mobile Team

Estimated Effort: 40 hours

Dependencies: None

Definition of Done:
1. Code peer-reviewed and approved by Berlin architect
2. UI matches London design specifications
3. Unit test coverage ≥90%
4. Integration tests pass against Cairo auth API
5. Passes security audit
6. iOS and Android versions both functional
7. User documentation uploaded to GitHub
8. Code merged to main branch

Acceptance Criteria:
- Login succeeds with valid credentials in <2 seconds
- Biometric authentication functional on compatible devices
- Invalid login attempts properly logged and rate-limited
- Accessibility requirements met (WCAG 2.1 AA)
- Works on both iOS and Android

---

CAI-002: Database Encryption Protocol Design

Description:
Design encryption architecture for patient medical records in Cairo data center. Comply with GDPR, HIPAA, and Egypt Data Sovereignty Law. Includes AES-256 encryption, key management, access control, and audit logging.

Assigned To: Cairo Security Team

Estimated Effort: 60 hours

Dependencies: None

Definition of Done:
1. Encryption design document (15+ pages) completed
2. Approved by Berlin security architect
3. Compliance checklist completed for GDPR, HIPAA, Egypt law
4. Peer review by external consultant
5. London PMO approval obtained
6. Document uploaded to GitHub
7. Threat model with mitigation strategies documented

 Acceptance Criteria:
- AES-256 encryption used
- Encryption-at-rest and encryption-in-transit implemented
- Key rotation strategy defined (90-day minimum)
- Audit logs capture all access
- Disaster recovery procedures documented

---

BER-003: AI Model Validation Against Test Set

Description:
Validate trained AI risk prediction model using held-out test dataset of 10,000 patient records. Measure accuracy, precision, recall, F1 score, and AUC-ROC. Document edge cases and failure modes.

Assigned To: Berlin AI Research Team

Estimated Effort: 40 hours

Dependencies: BER-002: Train Model on Historical Patient Data

 Definition of Done:
1. Validation complete with statistical analysis
2. Validation report published (10+ pages)
3. Model achieves ≥90% accuracy on test set
4. Confusion matrix analysis documented
5. Edge cases and failure modes identified
6. Peer review by external AI researcher
7. London PMO approval obtained
8. All code and results uploaded to GitHub

Acceptance Criteria:
- Accuracy ≥90%
- Precision ≥85%
- Recall ≥85%
- Model tested on noisy/incomplete data
- Failure cases categorized and explained
