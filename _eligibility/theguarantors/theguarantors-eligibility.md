---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: By accessing and using the Site you represent and warrant that you are the age of majority in your respective jurisdiction and are seeking the services of Company as they relate to activities within the United States of America.
  minimum_age:
    text: you are the age of majority in your respective jurisdiction
    value: age of majority
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
name: TheGuarantors
provenance_date: '2026-11-10'
provider_name: TheGuarantors
provider_slug: theguarantors
slug: theguarantors-eligibility
source_date: '2026-11-10'
source_filename: theguarantors-eligibility.yml
source_heading: Eligibility
source_page: https://www.theguarantors.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TheGuarantors\naid: theguarantors\nurl: https://www.theguarantors.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: By accessing and using the Site you represent and warrant that you are the age of majority in your respective\n    jurisdiction and are seeking the services of Company as they relate to activities within the United States of\n    America.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you are the age of majority in your respective jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/theguarantors/eligibility/theguarantors-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from TheGuarantors's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Insurance
- Real Estate
- Rentals
- PropTech
- Lease Guarantee
- Renters Insurance
---
