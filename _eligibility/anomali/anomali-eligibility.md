---
api_specs:
- filename: anomali-openapi-generated.yml
  format: yaml
  label: Anomali API
  slug: anomali-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomali/openapi/_ae-authored/anomali-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We operate the Service from our offices in California, and we make no representations that information and materials included in the Service are appropriate or available for use in other locations.
  entity_types:
  - text: You must be at least eighteen (18) years old to use the Service.
    type: individual
  - text: If you are using the Service on behalf of an entity, organization, or company (a “ Subscribing Organization ”), you represent and warrant that you have the authority to bind such Subscribing Organization to these Terms
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: 'BY USING THE SERVICE YOU AGREE NOT TO: use the Service for any illegal purpose, or in violation of any local, state, national, or international law;'
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
name: Anomali
provenance_date: '2026-11-09'
provider_name: Anomali
provider_slug: anomali
slug: anomali-eligibility
source_date: '2026-11-09'
source_filename: anomali-eligibility.yml
source_heading: Eligibility
source_page: https://www.anomali.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anomali\naid: anomali\nurl: https://www.anomali.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We operate the Service from our offices in California, and we make no representations that information and\n    materials included in the Service are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old to use the Service.\n- type: business\n  text: If you are using the Service on behalf of an entity, organization, or company (a “ Subscribing Organization\n    ”), you represent\
  \ and warrant that you have the authority to bind such Subscribing Organization to these Terms\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: 'BY USING THE SERVICE YOU AGREE NOT TO: use the Service for any illegal purpose, or in violation of any\n    local, state, national, or international law;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/anomali/eligibility/anomali-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Anomali's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Cybersecurity
- Threat Intelligence
- Security
- SIEM
- SOAR
- XDR
- Threat Intelligence Platform
---
