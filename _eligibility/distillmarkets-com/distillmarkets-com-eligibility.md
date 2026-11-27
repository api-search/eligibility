---
api_specs:
- filename: distillmarkets-com-openapi-generated.yml
  format: yaml
  label: distillmarkets-com API
  slug: distillmarkets-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distillmarkets-com/openapi/_ae-authored/distillmarkets-com-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the service if you are, or act for, a person targeted by Australian, United States, United Kingdom or European Union sanctions, or if you are located in a country or region subject to comprehensive sanctions under those laws.
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract to use Distill Markets.
    type: individual
  - text: If you subscribe on behalf of a company or other entity, you confirm that you are authorised to bind it to these terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to use Distill Markets.
    value: '18'
  restricted_uses:
  - summary: Personal grant limits
    text: You may not use a Personal grant to manage money for any other person, or to produce data or outputs that are shown to third parties in a product or service.
  - summary: Commercial grant excludes supplying data to third parties
    text: A Commercial grant does not permit supplying our data, or data derived from it, to third parties as data.
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
name: distillmarkets-com
provenance_date: '2026-11-09'
provider_name: distillmarkets-com
provider_slug: distillmarkets-com
slug: distillmarkets-com-eligibility
source_date: '2026-11-09'
source_filename: distillmarkets-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.distillmarkets.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: distillmarkets-com\naid: distillmarkets-com\nurl: https://www.distillmarkets.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the service if you are, or act for, a person targeted by Australian, United States, United\n    Kingdom or European Union sanctions, or if you are located in a country or region subject to comprehensive sanctions\n    under those laws.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract to use Distill Markets.\n- type: business\n  text: If you subscribe on behalf of\
  \ a company or other entity, you confirm that you are authorised to bind it\n    to these terms.\nrestricted_uses:\n- summary: Personal grant limits\n  text: You may not use a Personal grant to manage money for any other person, or to produce data or outputs that\n    are shown to third parties in a product or service.\n- summary: Commercial grant excludes supplying data to third parties\n  text: A Commercial grant does not permit supplying our data, or data derived from it, to third parties as data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract to use Distill Markets.\n"
source_yaml_url: https://artifacts.apis.io/distillmarkets-com/eligibility/distillmarkets-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from distillmarkets-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Data
- SEC
- Artificial Intelligence
---
