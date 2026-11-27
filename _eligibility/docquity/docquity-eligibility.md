---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Docquity is a professional networking platform for licensed doctors, physicians, and other healthcare professionals across Asia.
  entity_types:
  - text: The Services are intended for use by licensed doctors, physicians, and other qualified healthcare professionals.
    type: individual
  - text: If you access or use certain Services for a commercial purpose on behalf of a company, hospital or other entity that has entered into a separate agreement with Docquity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Dx limited to medical professionals
    text: It is designed exclusively for use by qualified medical professionals and is not intended for use by the general public.
  - summary: Not for medical emergencies
    text: Dx and the Services are not intended, designed, or suitable for use in medical emergencies or time-critical clinical situations.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: To verify your identity and professional status, we may require you to provide supporting documentation
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Docquity
provenance_date: '2026-11-09'
provider_name: Docquity
provider_slug: docquity
slug: docquity-eligibility
source_date: '2026-11-09'
source_filename: docquity-eligibility.yml
source_heading: Eligibility
source_page: https://docquity.com/termsandconditions/en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Docquity\naid: docquity\nurl: https://docquity.com/termsandconditions/en\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Docquity is a professional networking platform for licensed doctors, physicians, and other healthcare professionals\n    across Asia.\nentity_types:\n- type: individual\n  text: The Services are intended for use by licensed doctors, physicians, and other qualified healthcare professionals.\n- type: business\n  text: If you access or use certain Services for a commercial purpose on behalf of a company, hospital or other\n    entity that has entered\
  \ into a separate agreement with Docquity\nrestricted_uses:\n- summary: Dx limited to medical professionals\n  text: It is designed exclusively for use by qualified medical professionals and is not intended for use by the\n    general public.\n- summary: Not for medical emergencies\n  text: Dx and the Services are not intended, designed, or suitable for use in medical emergencies or time-critical\n    clinical situations.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: To verify your identity and professional status, we may require you to provide supporting documentation\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/docquity/eligibility/docquity-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Docquity's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Medical Education
- Healthcare Professionals
- Professional Network
- Life Sciences
- Pharmaceuticals
- Artificial Intelligence
- Clinical Decision Support
- Mobile
- Southeast Asia
- Singapore
---
