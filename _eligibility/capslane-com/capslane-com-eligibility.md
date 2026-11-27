---
api_specs:
- filename: capslane-com-transcript-api-openapi.yml
  format: yaml
  label: capslane-com Transcript API
  slug: capslane-com-transcript-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capslane-com/openapi/capslane-com-transcript-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Capslane is intended for professionals and organisations acting for business purposes.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or rights-infringing use
    text: You may not use Capslane to break the law, infringe third-party rights, bypass access controls, distribute malware, disrupt the service or evade quotas.
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
name: capslane-com
provenance_date: '2026-11-09'
provider_name: capslane-com
provider_slug: capslane-com
slug: capslane-com-eligibility
source_date: '2026-11-09'
source_filename: capslane-com-eligibility.yml
source_heading: Eligibility
source_page: https://capslane.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: capslane-com\naid: capslane-com\nurl: https://capslane.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Capslane is intended for professionals and organisations acting for business purposes.\nrestricted_uses:\n- summary: Unlawful or rights-infringing use\n  text: You may not use Capslane to break the law, infringe third-party rights, bypass access controls, distribute\n    malware, disrupt the service or evade quotas.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/capslane-com/eligibility/capslane-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from capslane-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- YouTube
- Transcript
- Artificial Intelligence
---
