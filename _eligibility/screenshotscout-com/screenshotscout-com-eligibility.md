---
api_specs:
- filename: screenshotscout-com-openapi-generated.yml
  format: yaml
  label: screenshotscout-com API
  slug: screenshotscout-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenshotscout-com/openapi/_ae-authored/screenshotscout-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.
  entity_types:
  - text: '"you" refers both to you as an individual and to the entity you represent.'
    type: individual
  minimum_age:
    text: null
    value: null
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
name: screenshotscout-com
provenance_date: '2026-11-10'
provider_name: screenshotscout-com
provider_slug: screenshotscout-com
slug: screenshotscout-com-eligibility
source_date: '2026-11-10'
source_filename: screenshotscout-com-eligibility.yml
source_heading: Eligibility
source_page: https://screenshotscout.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: screenshotscout-com\naid: screenshotscout-com\nurl: https://screenshotscout.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is not intended for distribution to or use by any person or entity in any jurisdiction or country\n    where such distribution or use would be contrary to law or regulation.\nentity_types:\n- type: individual\n  text: '\"you\" refers both to you as an individual and to the entity you represent.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/screenshotscout-com/eligibility/screenshotscout-com-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from screenshotscout-com's own page on 2026-11-10.
synthetic: false
tags:
- Screenshots
- Browser Automation
- Developer Tools
- Software-as-a-Service
---
