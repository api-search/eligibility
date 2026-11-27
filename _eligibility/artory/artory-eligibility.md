---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Site or the Platform if you are a resident of a country embargoed by the United States
  entity_types:
  - text: If you open a User Account or are otherwise granted access or use of the Site or the Platform on behalf of a company, organization, or other entity
    type: business
  minimum_age:
    text: Any use or access to the Site or the Platform by anyone under 18 is strictly prohibited
    value: '18'
  restricted_uses:
  - summary: Unlawful or commercial use
    text: you agree that you will not use the Site, the Platform, or any element thereof for any purpose that is unlawful, commercial in nature, prohibited by this Agreement
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
name: Artory
provenance_date: '2026-11-09'
provider_name: Artory
provider_slug: artory
slug: artory-eligibility
source_date: '2026-11-09'
source_filename: artory-eligibility.yml
source_heading: Eligibility
source_page: https://www.wag-art.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Artory\naid: artory\nurl: https://www.wag-art.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Site or the Platform if you are a resident of a country embargoed by the United States\nentity_types:\n- type: business\n  text: If you open a User Account or are otherwise granted access or use of the Site or the Platform on behalf\n    of a company, organization, or other entity\nrestricted_uses:\n- summary: Unlawful or commercial use\n  text: you agree that you will not use the Site, the Platform, or any element thereof for any\
  \ purpose that is unlawful,\n    commercial in nature, prohibited by this Agreement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Any use or access to the Site or the Platform by anyone under 18 is strictly prohibited\n"
source_yaml_url: https://artifacts.apis.io/artory/eligibility/artory-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Artory's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Art
- Marketplace
- Data
- Asset Management
---
