---
api_specs:
- filename: clearancesearchengine-com-openapi-generated.yml
  format: yaml
  label: CASE API
  slug: clearancesearchengine-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearancesearchengine-com/openapi/_ae-authored/clearancesearchengine-com-openapi-generated.yml
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
  - summary: Uploads limited to documents the user has right to share
    text: You may upload only documents you have the right to possess and share, typically your own Statement of Reasons.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Uploading documents requires an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CASE
provenance_date: '2026-11-09'
provider_name: CASE
provider_slug: clearancesearchengine-com
slug: clearancesearchengine-com-eligibility
source_date: '2026-11-09'
source_filename: clearancesearchengine-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.clearancesearchengine.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CASE\naid: clearancesearchengine-com\nurl: https://www.clearancesearchengine.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Uploads limited to documents the user has right to share\n  text: You may upload only documents you have the right to possess and share, typically your own Statement of Reasons.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Uploading documents requires an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clearancesearchengine-com/eligibility/clearancesearchengine-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from CASE's own page on 2026-11-09.
synthetic: false
tags:
- Security Clearance
- Legal Research
- Knowledge Base
---
