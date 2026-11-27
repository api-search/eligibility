---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Our site, its content and any services provided in relation to the same are only targeted to, and intended for use by, individuals located in the United Kingdom (the Permitted Territory).
  entity_types:
  - text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms that may apply to our site or any content on it.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use by consumers
    text: You agree not to use our site for any commercial or business purposes
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
name: Reposit
provenance_date: '2026-11-10'
provider_name: Reposit
provider_slug: reposit
slug: reposit-eligibility
source_date: '2026-11-10'
source_filename: reposit-eligibility.yml
source_heading: Eligibility
source_page: https://reposit.co.uk/website-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reposit\naid: reposit\nurl: https://reposit.co.uk/website-terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Our site, its content and any services provided in relation to the same are only targeted to, and intended\n    for use by, individuals located in the United Kingdom (the Permitted Territory).\nentity_types:\n- type: business\n  text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms\n    that may apply to our site or any content on it.'\nrestricted_uses:\n- summary: Commercial use by consumers\n  text:\
  \ You agree not to use our site for any commercial or business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/reposit/eligibility/reposit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Reposit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- PropTech
- Insurance
- Rentals
- Deposits
- Real Estate
- United Kingdom
---
