---
api_specs:
- filename: oecd-data-api-openapi.yml
  format: yaml
  label: OECD Data API
  slug: oecd-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oecd/openapi/oecd-data-api-openapi.yml
- filename: oecd-structure-api-openapi.yml
  format: yaml
  label: OECD Structure API
  slug: oecd-structure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oecd/openapi/oecd-structure-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: encourages its use by external entities and individuals
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: OECD logo requires written permission
    text: The OECD logo is legally protected and may not be used without express written permission, which will only be granted when appropriate and in extremely limited circumstances.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Requests for permission to reproduce must be obtained from the OECD by submitting a request to comrights@oecd.org.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OECD
provenance_date: '2026-11-10'
provider_name: OECD
provider_slug: oecd
slug: oecd-eligibility
source_date: '2026-11-10'
source_filename: oecd-eligibility.yml
source_heading: Eligibility
source_page: https://www.oecd.org/en/about/terms-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OECD\naid: oecd\nurl: https://www.oecd.org/en/about/terms-conditions.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: encourages its use by external entities and individuals\nrestricted_uses:\n- summary: OECD logo requires written permission\n  text: The OECD logo is legally protected and may not be used without express written permission, which will only\n    be granted when appropriate and in extremely limited circumstances.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Requests for permission to\
  \ reproduce must be obtained from the OECD by submitting a request to comrights@oecd.org.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/oecd/eligibility/oecd-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from OECD's own page on 2026-11-10.
synthetic: false
tags:
- Data
- Statistics
- Economics
- SDMX
---
