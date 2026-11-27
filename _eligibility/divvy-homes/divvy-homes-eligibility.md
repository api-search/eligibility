---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: This website may not be used by persons under the age of majority in their jurisdiction.
    value: age of majority
  restricted_uses:
  - summary: No securities offer
    text: None of the content on divvyhomes.com is an offer to sell, or a solicitation of an offer to buy, any securities of any Divvy Homes affiliate or any other company.
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
name: Divvy Homes
provenance_date: '2026-11-09'
provider_name: Divvy Homes
provider_slug: divvy-homes
slug: divvy-homes-eligibility
source_date: '2026-11-09'
source_filename: divvy-homes-eligibility.yml
source_heading: Eligibility
source_page: https://www.divvyhomes.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Divvy Homes\naid: divvy-homes\nurl: https://www.divvyhomes.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No securities offer\n  text: None of the content on divvyhomes.com is an offer to sell, or a solicitation of an offer to buy, any securities\n    of any Divvy Homes affiliate or any other company.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: This website may not be used by persons under the age of majority in their jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/divvy-homes/eligibility/divvy-homes-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Divvy Homes's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Rent-to-Own
- Homeownership
- Fintech
- Housing
---
