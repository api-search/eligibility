---
api_specs:
- filename: scripthaul-com-openapi.json
  format: json
  label: ScriptHaul API
  slug: scripthaul-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scripthaul-com/openapi/scripthaul-com-openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use the Service. If you have not reached the age at which you can enter a binding contract where you live, a parent or legal guardian must review and agree to these Terms for you.
    type: individual
  - text: If you use the Service for an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Infringing or unlawful use
    text: infringe copyright, privacy, publicity, contractual, or other rights, or violate applicable law
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
name: scripthaul-com
provenance_date: '2026-11-10'
provider_name: scripthaul-com
provider_slug: scripthaul-com
slug: scripthaul-com-eligibility
source_date: '2026-11-10'
source_filename: scripthaul-com-eligibility.yml
source_heading: Eligibility
source_page: https://scripthaul.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: scripthaul-com\naid: scripthaul-com\nurl: https://scripthaul.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service. If you have not reached the age at which you can enter\n    a binding contract where you live, a parent or legal guardian must review and agree to these Terms for you.\n- type: business\n  text: If you use the Service for an organization, you represent that you have authority to bind that organization.\nrestricted_uses:\n- summary: Infringing or unlawful use\n \
  \ text: infringe copyright, privacy, publicity, contractual, or other rights, or violate applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/scripthaul-com/eligibility/scripthaul-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from scripthaul-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- YouTube
- Transcripts
- Free
- Bulk
---
