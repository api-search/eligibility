---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: THIS WEBSITE IS INTENDED SOLELY FOR RESIDENTS OF THE UNITED STATES AND ITS TERRITORIES.
  minimum_age:
    text: The Sites are intended for users who are 18 years of age and above.
    value: '18'
  restricted_uses:
  - summary: Not medical advice or patient relationship
    text: USE OF OUR SITES DOES NOT CREATE A PATIENT RELATIONSHIP BETWEEN YOU AND BILLIONTOONE.
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
name: BillionToOne
provenance_date: '2026-11-09'
provider_name: BillionToOne
provider_slug: billiontoone
slug: billiontoone-eligibility
source_date: '2026-11-09'
source_filename: billiontoone-eligibility.yml
source_heading: Eligibility
source_page: https://www.billiontoone.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BillionToOne\naid: billiontoone\nurl: https://www.billiontoone.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: THIS WEBSITE IS INTENDED SOLELY FOR RESIDENTS OF THE UNITED STATES AND ITS TERRITORIES.\nentity_types: []\nrestricted_uses:\n- summary: Not medical advice or patient relationship\n  text: USE OF OUR SITES DOES NOT CREATE A PATIENT RELATIONSHIP BETWEEN YOU AND BILLIONTOONE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Sites are intended for users who are 18 years of age and\
  \ above.\n"
source_yaml_url: https://artifacts.apis.io/billiontoone/eligibility/billiontoone-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BillionToOne's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Molecular Diagnostics
- Healthcare
- Genomics
- Prenatal Testing
- Oncology
- Liquid Biopsy
- Diagnostics
---
