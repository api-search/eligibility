---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: Whether personally or on behalf of an entity
    type: individual
  minimum_age:
    text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Site.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: you will not use the Site for any illegal or unauthorized purpose
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
name: FundMiner
provenance_date: '2026-11-09'
provider_name: FundMiner
provider_slug: fundminer
slug: fundminer-eligibility
source_date: '2026-11-09'
source_filename: fundminer-eligibility.yml
source_heading: Eligibility
source_page: https://www.fundminer.com/terms-of-service-agreement-fundminer
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FundMiner\naid: fundminer\nurl: https://www.fundminer.com/terms-of-service-agreement-fundminer\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: Whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: you will not use the Site for any illegal or unauthorized purpose\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Site.\n"
source_yaml_url: https://artifacts.apis.io/fundminer/eligibility/fundminer-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from FundMiner's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fund Management
- Donor Engagement
- Non-Profit
- Higher Education
- Fundraising
- Compliance
- Financial Services
---
