---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an entity, organization, or company, you represent and warrant that you have the authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: Illegal or fraudulent use
    text: perform any fraudulent activity including impersonating any person or entity, claiming a false affiliation
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
name: Knowde
provenance_date: '2026-11-09'
provider_name: Knowde
provider_slug: knowde
slug: knowde-eligibility
source_date: '2026-11-09'
source_filename: knowde-eligibility.yml
source_heading: Eligibility
source_page: https://privacy.knowde.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Knowde\naid: knowde\nurl: https://privacy.knowde.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an entity, organization, or company, you represent and warrant\n    that you have the authority to bind that organization to these Terms\nrestricted_uses:\n- summary: Illegal or fraudulent use\n  text: perform any fraudulent activity including impersonating any person or entity, claiming a false affiliation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/knowde/eligibility/knowde-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Knowde's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Chemicals
- Ingredients
- Marketplace
- Master Data Management
- Product Information Management
- Manufacturing
- Distribution
- B2B Commerce
- GraphQL
- Artificial Intelligence
---
