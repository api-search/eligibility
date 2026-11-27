---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals, companies, or other entities located in the United States. You may not use the Service if you are a resident of a country embargoed by the United States
  entity_types:
  - text: If you are entering this Agreement on behalf of your employer or other company, you hereby represent, warrant, and covenant that you have the ability and agency to bind such employer or company to this Agreement.
    type: business
  - text: If you are an individual using the Service for non-commercial purposes
    type: individual
  minimum_age:
    text: Any use or access to the Service by anyone under the age of 13 is strictly prohibited and in violation of this Agreement.
    value: '13'
  restricted_uses:
  - summary: No sensitive data submission
    text: You will not submit, or cause to be submitted, any Sensitive Data to the Service.
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
name: Hum Capital
provenance_date: '2026-11-09'
provider_name: Hum Capital
provider_slug: hum-capital
slug: hum-capital-eligibility
source_date: '2026-11-09'
source_filename: hum-capital-eligibility.yml
source_heading: Eligibility
source_page: https://humcapital.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hum Capital\naid: hum-capital\nurl: https://humcapital.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals,\n    companies, or other entities located in the United States. You may not use the Service if you are a resident\n    of a country embargoed by the United States\nentity_types:\n- type: business\n  text: If you are entering this Agreement on behalf of your employer or other company, you hereby represent, warrant,\n    and covenant that you have the\
  \ ability and agency to bind such employer or company to this Agreement.\n- type: individual\n  text: If you are an individual using the Service for non-commercial purposes\nrestricted_uses:\n- summary: No sensitive data submission\n  text: You will not submit, or cause to be submitted, any Sensitive Data to the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access to the Service by anyone under the age of 13 is strictly prohibited and in violation of\n    this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/hum-capital/eligibility/hum-capital-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Hum Capital's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Capital Markets
- Fintech
- Lending
- Alternative Financing
- Investment
- Marketplace
---
