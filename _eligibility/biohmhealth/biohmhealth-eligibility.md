---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are for use only in the country to which your Sample collection kit was shipped from BIOHM. BIOHM ships orders to US, Army Post Office (APO), and Diplomatic Post Office (DPO) addresses.
  entity_types:
  - text: you must be eighteen (18) years of age or older to agree to these TOS on behalf of yourself or those for whom you have legal authority to agree.
    type: individual
  minimum_age:
    text: you must be eighteen (18) years of age or older to agree to these TOS on behalf of yourself or those for whom you have legal authority to agree.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: You are warranting that any Service you purchase, or any Sample you provide is for personal, non-commercial, non-legal or non-journalistic purposes only
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
name: Biohmhealth
provenance_date: '2026-11-09'
provider_name: Biohmhealth
provider_slug: biohmhealth
slug: biohmhealth-eligibility
source_date: '2026-11-09'
source_filename: biohmhealth-eligibility.yml
source_heading: Eligibility
source_page: https://www.biohmhealth.com/pages/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Biohmhealth\naid: biohmhealth\nurl: https://www.biohmhealth.com/pages/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are for use only in the country to which your Sample collection kit was shipped from BIOHM.\n    BIOHM ships orders to US, Army Post Office (APO), and Diplomatic Post Office (DPO) addresses.\nentity_types:\n- type: individual\n  text: you must be eighteen (18) years of age or older to agree to these TOS on behalf of yourself or those for\n    whom you have legal authority to agree.\nrestricted_uses:\n- summary:\
  \ Personal non-commercial use only\n  text: You are warranting that any Service you purchase, or any Sample you provide is for personal, non-commercial,\n    non-legal or non-journalistic purposes only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be eighteen (18) years of age or older to agree to these TOS on behalf of yourself or those for\n    whom you have legal authority to agree.\n"
source_yaml_url: https://artifacts.apis.io/biohmhealth/eligibility/biohmhealth-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Biohmhealth's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Probiotics
- Supplements
- Gut Health
- E-Commerce
---
