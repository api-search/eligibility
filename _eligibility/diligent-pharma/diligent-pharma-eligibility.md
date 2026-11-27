---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Website is intended for and directed to residents of the United States and all information, advertising, and claims contained on the Website are valid in and applicable only to the United States.
  minimum_age:
    text: The Site is not directed to children under the age of 18 years. By using the Site, you represent and warrant that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Lawful personal and informational use only
    text: You agree to use the Website only for lawful, personal, and informational purposes
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
name: Diligent Pharma
provenance_date: '2026-11-09'
provider_name: Diligent Pharma
provider_slug: diligent-pharma
slug: diligent-pharma-eligibility
source_date: '2026-11-09'
source_filename: diligent-pharma-eligibility.yml
source_heading: Eligibility
source_page: https://www.diligentpharma.com/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Diligent Pharma\naid: diligent-pharma\nurl: https://www.diligentpharma.com/website-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Website is intended for and directed to residents of the United States and all information, advertising,\n    and claims contained on the Website are valid in and applicable only to the United States.\nentity_types: []\nrestricted_uses:\n- summary: Lawful personal and informational use only\n  text: You agree to use the Website only for lawful, personal, and informational purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is not directed to children under the age of 18 years. By using the Site, you represent and warrant\n    that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/diligent-pharma/eligibility/diligent-pharma-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Diligent Pharma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Clinical Trials
- Life Sciences
- Pharmaceuticals
- Biotechnology
- Vendor Management
- Risk Management
- Quality Management
- Compliance
- GxP
- Auditing
- Software-as-a-Service
---
