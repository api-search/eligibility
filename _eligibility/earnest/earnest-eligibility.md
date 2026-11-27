---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Site is available only to individuals who are permitted to use it under applicable law.
    type: individual
  minimum_age:
    text: The Site is not directed at children under the age of eighteen (18) and Earnest does not knowingly collect personal information from any child under the age of eighteen (18) at the Site.
    value: '18'
  restricted_uses:
  - summary: Use in furtherance of unlawful activity or export restrictions
    text: (e) use the Developer Application or data provided via the Developer Application in any way in furtherance of criminal, fraudulent, or other unlawful activity.
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
name: Earnest
provenance_date: '2026-11-09'
provider_name: Earnest
provider_slug: earnest
slug: earnest-eligibility
source_date: '2026-11-09'
source_filename: earnest-eligibility.yml
source_heading: Eligibility
source_page: https://www.earnest.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Earnest\naid: earnest\nurl: https://www.earnest.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Our Site is available only to individuals who are permitted to use it under applicable law.\nrestricted_uses:\n- summary: Use in furtherance of unlawful activity or export restrictions\n  text: (e) use the Developer Application or data provided via the Developer Application in any way in furtherance\n    of criminal, fraudulent, or other unlawful activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is not directed at children under the age of eighteen (18) and Earnest does not knowingly collect\n    personal information from any child under the age of eighteen (18) at the Site.\n"
source_yaml_url: https://artifacts.apis.io/earnest/eligibility/earnest-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Earnest's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Student Loans
- Personal Loans
- Consumer Finance
- Loan Refinancing
---
