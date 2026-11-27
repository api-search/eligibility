---
api_specs:
- filename: fyrn-openapi-generated.yml
  format: yaml
  label: Fyrn API
  slug: fyrn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fyrn/openapi/_ae-authored/fyrn-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Customer" or "you" means the individual or entity that creates an account and uses the Service.'
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: Use the Service for any unlawful purpose or in violation of applicable laws
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
name: Fyrn
provenance_date: '2026-11-09'
provider_name: Fyrn
provider_slug: fyrn
slug: fyrn-eligibility
source_date: '2026-11-09'
source_filename: fyrn-eligibility.yml
source_heading: Eligibility
source_page: https://fyrn.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fyrn\naid: fyrn\nurl: https://fyrn.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '\"Customer\" or \"you\" means the individual or entity that creates an account and uses the Service.'\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization to these Terms.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use the Service for any unlawful purpose or in violation of applicable laws\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fyrn/eligibility/fyrn-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Fyrn's own page on 2026-11-09.
synthetic: false
tags:
- Integration
- Artificial Intelligence
- Automation
- Enterprise
- Platform
- Company
---
