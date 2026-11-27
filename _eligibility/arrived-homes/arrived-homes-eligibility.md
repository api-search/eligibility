---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are available for residents of the United States only in the states where we or our authorized broker-dealer(s) are registered.
  entity_types:
  - text: You must be 18 years or older to use the Services.
    type: individual
  minimum_age:
    text: You must be 18 years or older to use the Services.
    value: '18'
  restricted_uses:
  - summary: Commercial purposes
    text: For any commercial purpose, except as expressly permitted under these Terms
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
name: Arrived Homes
provenance_date: '2026-11-09'
provider_name: Arrived Homes
provider_slug: arrived-homes
slug: arrived-homes-eligibility
source_date: '2026-11-09'
source_filename: arrived-homes-eligibility.yml
source_heading: Eligibility
source_page: https://arrived.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arrived Homes\naid: arrived-homes\nurl: https://arrived.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are available for residents of the United States only in the states where we or our authorized\n    broker-dealer(s) are registered.\nentity_types:\n- type: individual\n  text: You must be 18 years or older to use the Services.\nrestricted_uses:\n- summary: Commercial purposes\n  text: For any commercial purpose, except as expressly permitted under these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You must be 18 years or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/arrived-homes/eligibility/arrived-homes-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Arrived Homes's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- PropTech
- Real Estate
- Real Estate Investing
- Fractional Ownership
- Passive Income
---
