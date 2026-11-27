---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of a business or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Website and Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: 'you are prohibited from using the Website and Services or Content: (a) for any unlawful purpose'
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
name: Viewlocity
provenance_date: '2026-11-10'
provider_name: Viewlocity
provider_slug: viewlocity
slug: viewlocity-eligibility
source_date: '2026-11-10'
source_filename: viewlocity-eligibility.yml
source_heading: Eligibility
source_page: https://www.viewlocity.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Viewlocity\naid: viewlocity\nurl: https://www.viewlocity.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a business or other legal entity, you represent that\n    you have the authority to bind such entity\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: 'you are prohibited from using the Website and Services or Content: (a) for any unlawful purpose'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years of age to use the Website and Services.\n"
source_yaml_url: https://artifacts.apis.io/viewlocity/eligibility/viewlocity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Viewlocity's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Supply Chain
- Supply Chain Management
- Logistics
- Transportation
- Inventory
- Control Tower
- Manufacturing
- Software-as-a-Service
---
