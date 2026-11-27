---
api_specs:
- filename: birdsift-com-openapi.json
  format: json
  label: BirdSift API
  slug: birdsift-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/birdsift-com/openapi/birdsift-com-openapi.json
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
  - summary: Lawful use and third-party terms
    text: You agree to use the Service only for lawful purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need an account to run searches in the web app.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BirdSift
provenance_date: '2026-11-09'
provider_name: BirdSift
provider_slug: birdsift-com
slug: birdsift-com-eligibility
source_date: '2026-11-09'
source_filename: birdsift-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.birdsift.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BirdSift\naid: birdsift-com\nurl: https://www.birdsift.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use and third-party terms\n  text: You agree to use the Service only for lawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You need an account to run searches in the web app.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/birdsift-com/eligibility/birdsift-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from BirdSift's own page on 2026-11-09.
synthetic: false
tags:
- Lead Generation
- Web Design
- Software-as-a-Service
- Marketing
---
