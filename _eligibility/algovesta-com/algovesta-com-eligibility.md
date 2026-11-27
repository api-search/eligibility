---
api_specs:
- filename: algovesta-com-openapi-generated.yml
  format: yaml
  label: AlgoVesta API
  slug: algovesta-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algovesta-com/openapi/_ae-authored/algovesta-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age, or the legal age of majority in your jurisdiction, whichever is greater.
    type: individual
  - text: If you are accessing or using the Services on behalf of a company, organization, or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years of age, or the legal age of majority in your jurisdiction, whichever is greater.
    value: '18'
  restricted_uses:
  - summary: Jurisdictional restrictions
    text: Using the platform in jurisdictions where cryptocurrency trading, automated trading services, or financial software of this nature is prohibited or restricted by law.
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
name: AlgoVesta
provenance_date: '2026-11-09'
provider_name: AlgoVesta
provider_slug: algovesta-com
slug: algovesta-com-eligibility
source_date: '2026-11-09'
source_filename: algovesta-com-eligibility.yml
source_heading: Eligibility
source_page: https://algovesta.com/terms-of-service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AlgoVesta\naid: algovesta-com\nurl: https://algovesta.com/terms-of-service.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age, or the legal age of majority in your jurisdiction, whichever is greater.\n- type: business\n  text: If you are accessing or using the Services on behalf of a company, organization, or other legal entity,\n    you represent and warrant that you have the authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Jurisdictional restrictions\n  text: Using\
  \ the platform in jurisdictions where cryptocurrency trading, automated trading services, or financial\n    software of this nature is prohibited or restricted by law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age, or the legal age of majority in your jurisdiction, whichever is greater.\n"
source_yaml_url: https://artifacts.apis.io/algovesta-com/eligibility/algovesta-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AlgoVesta's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Trading
- Automation
- Cryptocurrency
- Software-as-a-Service
---
