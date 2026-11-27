---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Orders are delivered to the territories indicated on the Website.
  entity_types:
  - text: Consumer - a natural person making a legal transaction with the trader not directly related to its business or professional activity within the meaning of relevant state or federal law.
    type: individual
  - text: made available by the Seller to the Users who are not Consumers
    type: business
  minimum_age:
    text: you confirm that you are a natural person at least 18 years of age, who can enter into legally binding contracts in accordance with the law
    value: '18'
  restricted_uses:
  - summary: Unlawful content
    text: The User is prohibited from providing unlawful content.
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
name: Packhelp
provenance_date: '2026-11-10'
provider_name: Packhelp
provider_slug: packhelp
slug: packhelp-eligibility
source_date: '2026-11-10'
source_filename: packhelp-eligibility.yml
source_heading: Eligibility
source_page: https://packhelp.com/en-us/terms_of_service/?auto_region_redirect=1
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Packhelp\naid: packhelp\nurl: https://packhelp.com/en-us/terms_of_service/?auto_region_redirect=1\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Orders are delivered to the territories indicated on the Website.\nentity_types:\n- type: individual\n  text: Consumer - a natural person making a legal transaction with the trader not directly related to its business\n    or professional activity within the meaning of relevant state or federal law.\n- type: business\n  text: made available by the Seller to the Users who are not Consumers\nrestricted_uses:\n- summary:\
  \ Unlawful content\n  text: The User is prohibited from providing unlawful content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you confirm that you are a natural person at least 18 years of age, who can enter into legally binding contracts\n    in accordance with the law\n"
source_yaml_url: https://artifacts.apis.io/packhelp/eligibility/packhelp-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Packhelp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Packaging
- Custom Packaging
- E-Commerce
- Fulfillment
- Logistics
- Procurement
- Marketplace
- Sustainability
---
