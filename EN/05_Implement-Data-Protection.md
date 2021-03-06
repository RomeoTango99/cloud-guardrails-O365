# Implement Data Protection

## Objective

Safeguard information and assets hosted in cloud, from unauthorized access, use, disclosure, modification, disposal, transmission, or destruction throughout their life cycle. 

## Key Considerations

* [ ] Seek guidance from privacy and access to information officials within institutions before storing personal information in cloud-based environments.
* [ ] Verify location of service, in accordance with Section 4.4.1.10 of the [Directive on Service and Digital](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=32601)
* [ ] Ensure data in transit is encrypted by default (e.g. TLS v1.2, etc.).
* [ ] Leverage encryption mechanisms to protect the confidentiality and integrity of data hosted in the cloud service.
* [ ] Use CSE-approved cryptographic algorithms and protocols, in accordance with [40.111](https://cyber.gc.ca/en/guidance/cryptographic-algorithms-unclassified-protected-and-protected-b-information-itsp40111) and [40.062](https://www.cse-cst.gc.ca/en/system/files/pdf_documents/itsp.40.062-eng.pdf).
* [ ] Ensure DLP policies are enabled to protect GC Office 365 email and documents
* [ ] Leverage Office 365 Advanced Data Governance for data governance, retention, and expiration.
* [ ] Ensure Exchange Online Spam Policies are set correctly
* [ ] Use Azure Information Protection for classification and labelling and information protection of internal documents and emails 

## Validation

* [ ] TBD

## References

1. [SPIN 2017-01](https://www.canada.ca/en/treasury-board-secretariat/services/access-information-privacy/security-identity-management/direction-secure-use-commercial-cloud-services-spin.html), subsection 6.2.4
2. Refer to the cryptography guidance in [40.111](https://cyber.gc.ca/en/guidance/cryptographic-algorithms-unclassified-protected-and-protected-b-information-itsp40111) and [40.062](https://www.cse-cst.gc.ca/en/system/files/pdf_documents/itsp.40.062-eng.pdf).
3. Refer to the guidance in [Considerations for Cryptography in Commercial Cloud Services](https://www.canada.ca/en/government/system/digital-government/modern-emerging-technologies/cloud-services/government-canada-consideration-use-cryptography-in-cloud.html).
4. Refer to Section 4.4.1.10 of the [Directive on Service and Digital](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=32601)
5. Related security controls: SC‑8, SC‑8(1), SC‑12, SC‑13, SC‑17, SC‑28, SC‑28(1)
