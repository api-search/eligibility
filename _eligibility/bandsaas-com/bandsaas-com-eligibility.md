---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to create an account and use the Platform as a Band Owner.
    type: individual
  - text: If you are using the Platform on behalf of a band, organisation, or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to create an account and use the Platform as a Band Owner.
    value: '18'
  restricted_uses:
  - summary: Prohibited merchandise
    text: Use the merchandise shop or print-on-demand features to sell items that are illegal, counterfeit, infringing, or otherwise prohibited by applicable law
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
name: BandSaaS
provenance_date: '2026-11-09'
provider_name: BandSaaS
provider_slug: bandsaas-com
slug: bandsaas-com-eligibility
source_date: '2026-11-09'
source_filename: bandsaas-com-eligibility.yml
source_heading: Eligibility
source_page: https://bandsaas.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BandSaaS\naid: bandsaas-com\nurl: https://bandsaas.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to create an account and use the Platform as a Band Owner.\n- type: business\n  text: If you are using the Platform on behalf of a band, organisation, or other legal entity, you represent and\n    warrant that you have the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Prohibited merchandise\n  text: Use the merchandise shop or print-on-demand features to sell\
  \ items that are illegal, counterfeit, infringing,\n    or otherwise prohibited by applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to create an account and use the Platform as a Band Owner.\n"
source_yaml_url: https://artifacts.apis.io/bandsaas-com/eligibility/bandsaas-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BandSaaS's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Music
- Licensing
- Artists
- Platform
---
