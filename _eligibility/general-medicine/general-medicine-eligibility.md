---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served:
    - US
    text: Access to and use of the Service is limited exclusively to users located in states within the United States where the Service is available. The Service may not be used or otherwise provided or made available, either directly or indirectly, (a) in Cuba, Iran, North Korea, Syria, Crimea region of Ukraine
  entity_types:
  - text: In order to access the Service, you represent and warrant that you are at least 18 years old or older.
    type: individual
  minimum_age:
    text: you represent and warrant that you are at least 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: Prescription products for personal use only
    text: You agree that any prescriptions that you acquire from an Emerald Provider will be solely for your personal use.
  - summary: Not for emergencies
    text: Our Service is not for medical emergencies or urgent situations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: General and Emerald Providers may request further information from you, and you agree to provide such further information to ensure that you have not fraudulently used the Services.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: General Medicine
provenance_date: '2026-11-09'
provider_name: General Medicine
provider_slug: general-medicine
slug: general-medicine-eligibility
source_date: '2026-11-09'
source_filename: general-medicine-eligibility.yml
source_heading: Eligibility
source_page: https://generalmedicine.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: General Medicine\naid: general-medicine\nurl: https://generalmedicine.co/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: Access to and use of the Service is limited exclusively to users located in states within the United States\n    where the Service is available. The Service may not be used or otherwise provided or made available, either\n    directly or indirectly, (a) in Cuba, Iran, North Korea, Syria, Crimea region of Ukraine\nentity_types:\n- type: individual\n  text: In order to access the Service, you represent\
  \ and warrant that you are at least 18 years old or older.\nrestricted_uses:\n- summary: Prescription products for personal use only\n  text: You agree that any prescriptions that you acquire from an Emerald Provider will be solely for your personal\n    use.\n- summary: Not for emergencies\n  text: Our Service is not for medical emergencies or urgent situations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: General and Emerald Providers may request further information from you, and you agree to provide such further\n    information to ensure that you have not fraudulently used the Services.\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/general-medicine/eligibility/general-medicine-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from General Medicine's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Telehealth
- Healthcare
- Digital Health
- Marketplace
---
