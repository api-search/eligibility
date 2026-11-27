---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a terrorist-supporting country
  entity_types:
  - text: You may use the Services only if you are 18 years or older, capable of forming a binding contract (i.e. these Terms) with the Company and are not barred from using the Services under applicable law.
    type: individual
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: No solicitation for brokerage
    text: You agree that, whether you are a real estate agent or not, you may not use the Services to directly or indirectly solicit for real estate brokerage or other related services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Company has no obligation to verify the identity of the persons using its services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FSBO.com
provenance_date: '2026-11-09'
provider_name: FSBO.com
provider_slug: fsbo-com
slug: fsbo-com-eligibility
source_date: '2026-11-09'
source_filename: fsbo-com-eligibility.yml
source_heading: Eligibility
source_page: https://fsbo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FSBO.com\naid: fsbo-com\nurl: https://fsbo.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government\n    embargo, or that has been designated by the U.S. Government as a terrorist-supporting country\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 18 years or older, capable of forming a binding contract (i.e.\n    these Terms) with the Company and are not barred from using the Services under applicable law.\n- type: business\n  text: If you\
  \ are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that company or other legal entity to\n    these Terms.\nrestricted_uses:\n- summary: No solicitation for brokerage\n  text: You agree that, whether you are a real estate agent or not, you may not use the Services to directly or\n    indirectly solicit for real estate brokerage or other related services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Company has no obligation to verify the identity of the persons using its services\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/fsbo-com/eligibility/fsbo-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from FSBO.com's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Marketplace
- Software-as-a-Service
- Home Selling
- FSBO
---
