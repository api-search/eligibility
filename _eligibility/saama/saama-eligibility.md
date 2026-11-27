---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is intended for business and professional audiences.
    type: business
  minimum_age:
    text: You may not use the Website if you are under the age of 18 or otherwise lack legal capacity to agree to these Terms.
    value: '18'
  restricted_uses:
  - summary: No PHI or sensitive data via public forms
    text: Do not submit protected health information, patient information, clinical trial subject data, special-category or sensitive personal information, credentials, confidential business information, regulated data, or customer data through public Website forms
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
name: Saama
provenance_date: '2026-11-10'
provider_name: Saama
provider_slug: saama
slug: saama-eligibility
source_date: '2026-11-10'
source_filename: saama-eligibility.yml
source_heading: Eligibility
source_page: https://www.saama.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Saama\naid: saama\nurl: https://www.saama.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Website is intended for business and professional audiences.\nrestricted_uses:\n- summary: No PHI or sensitive data via public forms\n  text: Do not submit protected health information, patient information, clinical trial subject data, special-category\n    or sensitive personal information, credentials, confidential business information, regulated data, or customer\n    data through public Website forms\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not use the Website if you are under the age of 18 or otherwise lack legal capacity to agree to\n    these Terms.\n"
source_yaml_url: https://artifacts.apis.io/saama/eligibility/saama-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Saama's own page on 2026-11-10.
synthetic: false
tags:
- Life Sciences
- Clinical Trials
- Clinical Data Management
- Analytics
- Artificial Intelligence
- Machine Learning
- Pharmaceuticals
- Healthcare
- Data Platform
- CDISC
---
