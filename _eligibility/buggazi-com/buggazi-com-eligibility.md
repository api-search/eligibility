---
api_specs:
- filename: buggazi-com-openapi-generated.yml
  format: yaml
  label: Buggazi API
  slug: buggazi-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buggazi-com/openapi/_ae-authored/buggazi-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A Tenant may be an individual developer, a software team, an organisation, or a manager acting on behalf of a development team.
    type: individual
  - text: If you are using the Platform on behalf of an organisation or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to create an account and use the Platform as a Tenant.
    value: '18'
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
name: Buggazi
provenance_date: '2026-11-09'
provider_name: Buggazi
provider_slug: buggazi-com
slug: buggazi-com-eligibility
source_date: '2026-11-09'
source_filename: buggazi-com-eligibility.yml
source_heading: Eligibility
source_page: https://buggazi.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buggazi\naid: buggazi-com\nurl: https://buggazi.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A Tenant may be an individual developer, a software team, an organisation, or a manager acting on behalf\n    of a development team.\n- type: business\n  text: If you are using the Platform on behalf of an organisation or other legal entity, you represent and warrant\n    that you have the authority to bind that entity to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to create an account and use the Platform as a Tenant.\n"
source_yaml_url: https://artifacts.apis.io/buggazi-com/eligibility/buggazi-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Buggazi's own page on 2026-11-09.
synthetic: false
tags:
- Project Management
- Bug Tracking
- Sprint Planning
- AI Coding Agents
- Collaboration
---
