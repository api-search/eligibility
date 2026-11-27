---
api_specs:
- filename: forcepoint-openapi-generated.yml
  format: yaml
  label: Forcepoint DLP REST API
  slug: forcepoint-dlp-rest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forcepoint/openapi/_ae-authored/forcepoint-openapi-generated.yml
claim_count: 1
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
  - summary: Prohibited forum submissions
    text: Offers to sell any products or services (whether or not for profit) or solicits others (including solicitations for contributions or donations).
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
name: Forcepoint
provenance_date: '2026-11-09'
provider_name: Forcepoint
provider_slug: forcepoint
slug: forcepoint-eligibility
source_date: '2026-11-09'
source_filename: forcepoint-eligibility.yml
source_heading: Eligibility
source_page: https://www.forcepoint.com/legal/website-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Forcepoint\naid: forcepoint\nurl: https://www.forcepoint.com/legal/website-terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited forum submissions\n  text: Offers to sell any products or services (whether or not for profit) or solicits others (including solicitations\n    for contributions or donations).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/forcepoint/eligibility/forcepoint-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Forcepoint's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Security
- Data Loss Prevention
- SASE
- Security Service Edge
- Firewall
- Data Security
- Cloud Security
---
