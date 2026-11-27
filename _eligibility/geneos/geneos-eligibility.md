---
api_specs:
- filename: geneos-rest-api-api-openapi.yml
  format: yaml
  label: Geneos REST API
  slug: geneos-rest-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geneos/openapi/geneos-rest-api-api-openapi.yml
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
  - summary: Internal business use only for site materials
    text: you must not use any part of the materials on our site other than for your own internal business purposes, without obtaining a licence to do so from us.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: From time to time, we may restrict access to some parts of our site, or our entire site, to users who have registered with us and/or to members.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Geneos
provenance_date: '2026-11-09'
provider_name: Geneos
provider_slug: geneos
slug: geneos-eligibility
source_date: '2026-11-09'
source_filename: geneos-eligibility.yml
source_heading: Eligibility
source_page: https://www.itrsgroup.com/legal/terms-of-web-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Geneos\naid: geneos\nurl: https://www.itrsgroup.com/legal/terms-of-web-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Internal business use only for site materials\n  text: you must not use any part of the materials on our site other than for your own internal business purposes,\n    without obtaining a licence to do so from us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: From time to time, we may restrict access to some parts of our site, or our entire site, to users who have\n    registered\
  \ with us and/or to members.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/geneos/eligibility/geneos-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Geneos's own page on 2026-11-09.
synthetic: false
tags:
- APM
- Capital Markets
- Infrastructure
- ITRS
- Monitoring
- Observability
- Real-Time
- Trading Systems
- XML-RPC
- OpenAPI
---
