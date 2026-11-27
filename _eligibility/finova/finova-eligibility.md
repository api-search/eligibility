---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Confirms that he/she has completed 18 (eighteen) years of age and is not prohibited from entering into a valid contract under any applicable laws.
    type: individual
  minimum_age:
    text: FCPL does not accept agreements and payments from persons below the legal age of 18 years.
    value: '18'
  restricted_uses:
  - summary: Impersonation or misrepresentation
    text: Impersonate any person or entity, or falsely state or otherwise misrepresent your affiliation with any person or entity
  - summary: Fraudulent or illegal content
    text: Which promotes mail fraud, multi-level marketing (pyramid) schemes or other illegal or fraudulent activities
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
name: Finova Capital
provenance_date: '2026-11-09'
provider_name: Finova Capital
provider_slug: finova
slug: finova-eligibility
source_date: '2026-11-09'
source_filename: finova-eligibility.yml
source_heading: Eligibility
source_page: https://finova.in/terms-and-condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Finova Capital\naid: finova\nurl: https://finova.in/terms-and-condition\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Confirms that he/she has completed 18 (eighteen) years of age and is not prohibited from entering into a\n    valid contract under any applicable laws.\nrestricted_uses:\n- summary: Impersonation or misrepresentation\n  text: Impersonate any person or entity, or falsely state or otherwise misrepresent your affiliation with any person\n    or entity\n- summary: Fraudulent or illegal content\n  text: Which promotes\
  \ mail fraud, multi-level marketing (pyramid) schemes or other illegal or fraudulent activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: FCPL does not accept agreements and payments from persons below the legal age of 18 years.\n"
source_yaml_url: https://artifacts.apis.io/finova/eligibility/finova-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Finova Capital's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- NBFC
- Lending
- MSME
- Housing Finance
- India
- Fintech
---
