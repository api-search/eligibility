---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: DocSpera makes no representations that the Site is appropriate or available for use outside of the United States.
  entity_types:
  - text: To use the App or any Materials, You must (a) either be (1) a currently licensed physician or (2) a member of a healthcare support team
    type: individual
  minimum_age:
    text: Any person who provides their personal information to DOCSPERA through the Site represents that they are 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: No medical advice or treatment through the app
    text: DocSpera or You are not permitted to advise, diagnose, or otherwise treat users of this App.
  - summary: No off-label promotion
    text: You covenant, represent and warrant that You will not promote "off-label" drug uses
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'Prior to the use of this Site, You must provide DocSpera with valid confirmation of (a), above, including all of the following: (i) Your name; (ii) Your mailing address; (iii) jurisdictions of licensure'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Docspera
provenance_date: '2026-11-09'
provider_name: Docspera
provider_slug: docspera
slug: docspera-eligibility
source_date: '2026-11-09'
source_filename: docspera-eligibility.yml
source_heading: Eligibility
source_page: https://docspera.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Docspera\naid: docspera\nurl: https://docspera.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: DocSpera makes no representations that the Site is appropriate or available for use outside of the United\n    States.\nentity_types:\n- type: individual\n  text: To use the App or any Materials, You must (a) either be (1) a currently licensed physician or (2) a member\n    of a healthcare support team\nrestricted_uses:\n- summary: No medical advice or treatment through the app\n  text: DocSpera or You are not permitted to advise, diagnose, or otherwise\
  \ treat users of this App.\n- summary: No off-label promotion\n  text: You covenant, represent and warrant that You will not promote \"off-label\" drug uses\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'Prior to the use of this Site, You must provide DocSpera with valid confirmation of (a), above, including\n    all of the following: (i) Your name; (ii) Your mailing address; (iii) jurisdictions of licensure'\nminimum_age:\n  value: '13'\n  text: Any person who provides their personal information to DOCSPERA through the Site represents that they are\n    13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/docspera/eligibility/docspera-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Docspera's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Software-as-a-Service
- Surgery
- Medical Technology
- Platform
- Compliance
---
