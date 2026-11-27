---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: we will not be providing Service (including the Consultation Facility) or access to the Platform outside the jurisdiction of India.
  entity_types:
  - text: The Platform is for personal use and the Service(s) are for individuals to use for supporting their personal health and wellness decisions.
    type: individual
  minimum_age:
    text: You must be 18 (eighteen) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Commercial use prohibited
    text: You may use the Platform for personal, but not for commercial purposes.
  - summary: Illegal purposes prohibited
    text: The information and Services shall not be used for any illegal purpose by You.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: the data and information as may be required by the Company for the purposes of registering/onboarding the User on the Platform and verifying the identity of the User
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 4baseCare
provenance_date: '2026-11-09'
provider_name: 4baseCare
provider_slug: 4basecare
slug: 4basecare-eligibility
source_date: '2026-11-09'
source_filename: 4basecare-eligibility.yml
source_heading: Eligibility
source_page: https://www.4basecare.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 4baseCare\naid: 4basecare\nurl: https://www.4basecare.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: we will not be providing Service (including the Consultation Facility) or access to the Platform outside\n    the jurisdiction of India.\nentity_types:\n- type: individual\n  text: The Platform is for personal use and the Service(s) are for individuals to use for supporting their personal\n    health and wellness decisions.\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: You may use the Platform for personal, but not for commercial\
  \ purposes.\n- summary: Illegal purposes prohibited\n  text: The information and Services shall not be used for any illegal purpose by You.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: the data and information as may be required by the Company for the purposes of registering/onboarding the\n    User on the Platform and verifying the identity of the User\nminimum_age:\n  value: '18'\n  text: You must be 18 (eighteen) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/4basecare/eligibility/4basecare-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from 4baseCare's own page on 2026-11-09.
synthetic: false
tags:
- Precision Oncology
- Genomics
- Healthcare
- Cancer
- Diagnostics
- Artificial Intelligence
- Life Sciences
- Clinical Decision Support
- Next-Generation Sequencing
- India
---
