---
api_specs:
- filename: disqo-audience-api-postman.json
  format: json
  label: DISQO Audience Projects API
  slug: disqo-audience-projects-api
  spec_type: Postman
  url: https://artifacts.apis.io/disqo/postman/disqo-audience-api-postman.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export controls and sanctions
    text: Client further represents that the Service shall not be used in any way that would violate U.S. export controls or economic sanctions laws or regulations.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: DISQO reserves the right to accept or reject each Order Form in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DISQO
provenance_date: '2026-11-09'
provider_name: DISQO
provider_slug: disqo
slug: disqo-eligibility
source_date: '2026-11-09'
source_filename: disqo-eligibility.yml
source_heading: Eligibility
source_page: https://www.disqo.com/legal/api-managed-services-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DISQO\naid: disqo\nurl: https://www.disqo.com/legal/api-managed-services-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export controls and sanctions\n  text: Client further represents that the Service shall not be used in any way that would violate U.S. export controls\n    or economic sanctions laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: DISQO reserves the right to accept or reject each Order Form in its sole discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/disqo/eligibility/disqo-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from DISQO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Audiences
- Market Research
- Surveys
- Consumer Insights
- Advertising Measurement
- Panel
- Brand Lift
- Data
- Analytics
---
