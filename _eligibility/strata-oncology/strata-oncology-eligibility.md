---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  entity_types:
  - text: The Website is intended only for users who can form legally binding contracts under applicable law.
    type: individual
  minimum_age:
    text: By using the Website, you represent and warrant that you are (i) at least eighteen (18) years of age and/or (ii) otherwise recognized as being able to form legally binding contracts under applicable law.
    value: '18'
  restricted_uses:
  - summary: Minors exploitation
    text: For the purpose of exploiting, harming or attempting to exploit or harm minors in any way by exposing them to inappropriate content, asking for personally identifiable information or otherwise.
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
name: Strata Oncology
provenance_date: '2026-11-10'
provider_name: Strata Oncology
provider_slug: strata-oncology
slug: strata-oncology-eligibility
source_date: '2026-11-10'
source_filename: strata-oncology-eligibility.yml
source_heading: Eligibility
source_page: https://strataoncology.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Strata Oncology\naid: strata-oncology\nurl: https://strataoncology.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: The Website is intended only for users who can form legally binding contracts under applicable law.\nrestricted_uses:\n- summary: Minors exploitation\n  text: For the purpose of exploiting, harming or attempting to exploit or harm minors in any way by exposing them\n    to inappropriate content, asking for personally identifiable\
  \ information or otherwise.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Website, you represent and warrant that you are (i) at least eighteen (18) years of age and/or\n    (ii) otherwise recognized as being able to form legally binding contracts under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/strata-oncology/eligibility/strata-oncology-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Strata Oncology's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Precision Medicine
- Oncology
- Genomics
- Diagnostics
- Laboratory
- Life Sciences
- Biomarkers
- Clinical Trials
---
