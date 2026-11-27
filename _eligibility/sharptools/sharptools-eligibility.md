---
api_specs:
- filename: sharptools-openapi-generated.yml
  format: yaml
  label: SharpTools API
  slug: sharptools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharptools/openapi/_ae-authored/sharptools-openapi-generated.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Services are intended for users who are at least 18 years old.
    type: individual
  - text: whether personally or on behalf of an entity (“you”)
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Services.
    value: '18'
  restricted_uses:
  - summary: No illegal or unauthorized use
    text: you will not use the Services for any illegal or unauthorized purpose
  - summary: No use to compete with provider
    text: Use the Services as part of any effort to compete with us
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SharpTools
provenance_date: '2026-11-10'
provider_name: SharpTools
provider_slug: sharptools
slug: sharptools-eligibility
source_date: '2026-11-10'
source_filename: sharptools-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.sharptools.io/policies/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SharpTools\naid: sharptools\nurl: https://cdn.sharptools.io/policies/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Services is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: The Services are intended for users who are at least 18 years old.\n- type: business\n  text: whether personally or on behalf of an entity (“you”)\nrestricted_uses:\n- summary: No illegal or unauthorized\
  \ use\n  text: you will not use the Services for any illegal or unauthorized purpose\n- summary: No use to compete with provider\n  text: Use the Services as part of any effort to compete with us\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with the Services.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Services.\n"
source_yaml_url: https://artifacts.apis.io/sharptools/eligibility/sharptools-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from SharpTools's own page on 2026-11-10.
synthetic: false
tags:
- Smart Home
- Dashboards
- Automation
- Rule Engine
- Hub Integration
- Device Monitoring
- Custom Tiles
---
