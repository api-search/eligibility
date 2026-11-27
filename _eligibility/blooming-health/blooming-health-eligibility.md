---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are offered and available to users who are 18 years of age or older and reside in the United States or any of its territories or possessions.
  entity_types:
  - text: The Services are offered and available to users who are 18 years of age or older
    type: individual
  minimum_age:
    text: The Services are offered and available to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Commercial use
    text: You must not access or use for any commercial purposes any part of the Website or materials available through the Website or our Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Blooming Health
provenance_date: '2026-11-09'
provider_name: Blooming Health
provider_slug: blooming-health
slug: blooming-health-eligibility
source_date: '2026-11-09'
source_filename: blooming-health-eligibility.yml
source_heading: Eligibility
source_page: https://gobloominghealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blooming Health\naid: blooming-health\nurl: https://gobloominghealth.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are offered and available to users who are 18 years of age or older and reside in the United\n    States or any of its territories or possessions.\nentity_types:\n- type: individual\n  text: The Services are offered and available to users who are 18 years of age or older\nrestricted_uses:\n- summary: Commercial use\n  text: You must not access or use for any commercial purposes any part of the Website or materials available through\n\
  \    the Website or our Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are offered and available to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/blooming-health/eligibility/blooming-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Blooming Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Care Management
- Community Engagement
- Patient Engagement
- Social Determinants of Health
- Medicaid
- FHIR
- HL7
- Interoperability
- HIPAA
---
