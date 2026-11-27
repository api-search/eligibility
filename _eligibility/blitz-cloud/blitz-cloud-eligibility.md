---
api_specs:
- filename: blitz-cloud-openapi-generated.yml
  format: yaml
  label: BlitzWorks API
  slug: blitz-cloud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-cloud/openapi/_ae-authored/blitz-cloud-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - 'NO'
    - IS
    - LI
    - GB
    - CH
    text: The free plan is open without a time limit to accounts from the EU, the EEA (Norway, Iceland, Liechtenstein), the United Kingdom and Switzerland.
  entity_types:
  - text: You must be at least 16 to sign up.
    type: individual
  - text: Only adults, or people acting for a business, can buy Pro.
    type: business
  minimum_age:
    text: You must be at least 16 to sign up.
    value: '16'
  restricted_uses:
  - summary: Prohibited content and activities
    text: You may not use blitz.cloud to offer content that breaks the law or infringes other people's rights
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Signup is open and there is no waiting list.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BlitzWorks
provenance_date: '2026-11-09'
provider_name: BlitzWorks
provider_slug: blitz-cloud
slug: blitz-cloud-eligibility
source_date: '2026-11-09'
source_filename: blitz-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://blitz.cloud/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlitzWorks\naid: blitz-cloud\nurl: https://blitz.cloud/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - 'NO'\n  - IS\n  - LI\n  - GB\n  - CH\n  excluded: []\n  text: The free plan is open without a time limit to accounts from the EU, the EEA (Norway, Iceland, Liechtenstein),\n    the United Kingdom and Switzerland.\nentity_types:\n- type: individual\n  text: You must be at least 16 to sign up.\n- type: business\n  text: Only adults, or people acting for a business, can buy Pro.\nrestricted_uses:\n- summary: Prohibited content and activities\n  text: You may not use blitz.cloud to offer content that\
  \ breaks the law or infringes other people's rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Signup is open and there is no waiting list.\nminimum_age:\n  value: '16'\n  text: You must be at least 16 to sign up.\n"
source_yaml_url: https://artifacts.apis.io/blitz-cloud/eligibility/blitz-cloud-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from BlitzWorks's own page on 2026-11-09.
synthetic: false
tags:
- Hosting
- EU
- Application
- Bots
- Artificial Intelligence
- Company
---
