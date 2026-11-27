---
api_specs:
- filename: opsive-openapi-generated.yml
  format: yaml
  label: Opsive API
  slug: opsive-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opsive/openapi/_ae-authored/opsive-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person, geographic region or jurisdiction.
  entity_types:
  - text: By agreeing to these Terms and Conditions, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Prohibited uses list
    text: 'you are prohibited from using the site or its content: (a) for any unlawful purpose'
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: We reserve the right to refuse service to anyone for any reason at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Opsive
provenance_date: '2026-11-10'
provider_name: Opsive
provider_slug: opsive
slug: opsive-eligibility
source_date: '2026-11-10'
source_filename: opsive-eligibility.yml
source_heading: Eligibility
source_page: https://opsive.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Opsive\naid: opsive\nurl: https://opsive.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person,\n    geographic region or jurisdiction.\nentity_types:\n- type: individual\n  text: By agreeing to these Terms and Conditions, you represent that you are at least the age of majority in your\n    state or province of residence\nrestricted_uses:\n- summary: Prohibited uses list\n  text: 'you are prohibited from using the site or its content: (a) for any unlawful purpose'\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: We reserve the right to refuse service to anyone for any reason at any time.\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/opsive/eligibility/opsive-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Opsive's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Game Development
- Unity
- Artificial Intelligence
- Behavior Trees
- Character Controllers
- Inventory Systems
- Developer Tools
---
