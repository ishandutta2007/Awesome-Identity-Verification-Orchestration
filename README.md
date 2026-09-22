# Awesome-Identity-Verification-Orchestration

## Top Identity Verification Orchestration Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on KYC/IDV Workflows, Document Verification, Biometrics, Liveness, Orchestration & Compliance Onboarding*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Identity Verification Orchestration**. These systems combine document checks, face matching, liveness detection, database screening, and workflow orchestration to verify user identities for KYC, onboarding, and compliance.



**Examples** include Persona, Signicat, Incode, Jumio, Veriff, Onfido (Entrust IDV), Trulioo, ID-Pal, AU10TIX, and Sumsub (the category leaders).



**Open-source emphasis**: Full production IDV orchestration platforms are almost entirely commercial. Practical open options include **biometric APIs**, document OCR pipelines, face-matching libraries, and early-stage self-hosted KYC scaffolds. This section lists the strongest available open resources and is realistic about the gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Persona](https://withpersona.com/)**  

  Flexible identity verification and orchestration platform with composable modules for document checks, biometrics, database lookups, and no-code workflow building.



- **[Signicat](https://www.signicat.com/)**  

  European digital identity and verification platform offering eID schemes, document verification, and compliance-oriented identity services.



- **[Incode](https://incode.com/)**  

  AI-powered identity verification platform focused on biometrics, document authentication, and omnichannel verification experiences.



- **[Jumio](https://www.jumio.com/)**  

  Enterprise identity verification platform with document verification, biometric authentication, AML tools, and large-scale global coverage.



- **[Veriff](https://www.veriff.com/)**  

  Identity verification platform known for high automation rates, fast decisions, broad document coverage, and strong liveness/deepfake defenses.



- **[Onfido / Entrust IDV](https://www.entrust.com/)**  

  Identity verification solution (Onfido acquired by Entrust) providing document and biometric checks with orchestration and fraud detection capabilities.



- **[Trulioo](https://www.trulioo.com/)**  

  Global identity verification platform specializing in person and business verification, data sources, and compliance workflows.



- **[ID-Pal](https://www.id-pal.com/)**  

  Identity verification and KYC platform used for customer onboarding with document and biometric verification flows.



- **[AU10TIX](https://www.au10tix.com/)**  

  Identity verification and authentication platform focused on document intelligence, biometrics, and automated identity decisioning.



- **[Sumsub](https://sumsub.com/)**  

  Full-stack verification and compliance platform covering KYC, KYB, AML screening, monitoring, and identity orchestration in one suite.



## Open-Source GitHub Projects

- **[OpenBiometrics](https://openbiometrics.dev/)**  

  Open-source biometric platform (MIT) providing face recognition, liveness detection, document processing (OCR/MRZ), and identity verification APIs—self-hostable.



- **[KYC Beacon and self-hosted KYC scaffolds](https://github.com/bp-ventures/kyc-beacon)**  

  Early-stage open-source, self-hostable KYC/identity verification projects aiming to cover document checks, face match, liveness, and review workflows.



- **[FaceOnLive / OpenKYC community components](https://github.com/FaceOnLive/ID-Verification-OpenKYC)**  

  Open community resources for face recognition, liveness (anti-spoofing), and ID document recognition used in identity verification pipelines.



- **[Document OCR and MRZ open pipelines](https://github.com/)**  

  Open tools (Tesseract, EasyOCR, specialized MRZ parsers) for extracting data from passports, national IDs, and driver’s licenses.



- **[Face matching and embedding open libraries](https://github.com/)**  

  Open face recognition stacks (e.g., InsightFace, ArcFace-based projects) used for 1:1 selfie-to-document matching.



- **[Liveness / anti-spoofing open research models](https://github.com/)**  

  Academic and community models for passive and active liveness detection against photo, screen, and mask attacks.



- **[KYC/KYB automation open prototypes](https://github.com/)**  

  FastAPI and similar open projects combining OCR, face comparison, and basic business-document analysis for experimental KYC flows.



- **[Workflow orchestration open engines](https://github.com/)**  

  Open workflow tools used to sequence document, biometric, and screening steps in custom verification pipelines.



- **[Synthetic ID and test-data generators](https://github.com/)**  

  Open utilities for generating synthetic identity documents and faces for testing verification pipelines without real PII.



- **[Consent and audit-log open components](https://github.com/)**  

  Libraries supporting consent capture and audit trails around identity verification events.



### Additional Strong Open-Source Options

- Building experimental verification flows with **OpenBiometrics** or open OCR + face-match stacks.

- Using open liveness models as a first layer and escalating uncertain cases to commercial providers.

- Orchestrating commercial IDV vendors behind open workflow engines for multi-vendor strategies.

- Accepting that global document coverage, certified deepfake defense, regulated audit trails, and production SLAs still require commercial platforms (Persona, Veriff, Jumio, Onfido/Entrust, Sumsub, etc.).

- Focusing open-source efforts on data residency, transparency of models, and reducing vendor lock-in for non-regulated or internal use cases.



**Frameworks for building custom systems**: Capture document + selfie → run open OCR and face match → apply open liveness checks → orchestrate steps in an open workflow engine → escalate failures to a commercial IDV provider or manual review. Suitable for research, internal tools, and low-risk flows. Most regulated businesses rely on commercial identity verification platforms for compliance and accuracy at scale.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Identity verification involves highly sensitive personal data and is subject to KYC/AML and privacy regulations. Open-source or self-built systems require rigorous security, consent management, and legal review. Incorrect verification can create serious compliance and fraud risks. This list is not legal or compliance advice.



---

**Made for compliance, fraud, and product teams building trusted digital onboarding.**

Let's keep identity verification accurate, privacy-aware, and as open as practical.
