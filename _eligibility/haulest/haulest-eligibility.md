---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    - GB
    text: haulest.com publishes moving research for the United States, Canada, and the United Kingdom
  entity_types:
  - text: You must be old enough to enter a contract where you live, and in any case at least 18 to send a quote request.
    type: individual
  - text: A moving company may register a free account at /for-movers to claim its listing.
    type: business
  minimum_age:
    text: in any case at least 18 to send a quote request
    value: '18'
  restricted_uses:
  - summary: Abuse of service
    text: Do not attack, overload, or impersonate the site.
  verification:
    approval_required: null
    kyb: true
    kyc: null
    text: We verify the claim against the licence record and may call the number on that record.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Haulest
provenance_date: '2026-11-09'
provider_name: Haulest
provider_slug: haulest
slug: haulest-eligibility
source_date: '2026-11-09'
source_filename: haulest-eligibility.yml
source_heading: Eligibility
source_page: https://haulest.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Haulest\naid: haulest\nurl: https://haulest.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  - GB\n  excluded: []\n  text: haulest.com publishes moving research for the United States, Canada, and the United Kingdom\nentity_types:\n- type: individual\n  text: You must be old enough to enter a contract where you live, and in any case at least 18 to send a quote request.\n- type: business\n  text: A moving company may register a free account at /for-movers to claim its listing.\nrestricted_uses:\n- summary: Abuse of service\n  text: Do not attack, overload, or impersonate the site.\n\
  verification:\n  kyc: null\n  kyb: true\n  approval_required: null\n  text: We verify the claim against the licence record and may call the number on that record.\nminimum_age:\n  value: '18'\n  text: in any case at least 18 to send a quote request\n"
source_yaml_url: https://artifacts.apis.io/haulest/eligibility/haulest-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Haulest's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Moving
- Relocation
- Cost Estimation
- MCP
- Movers
- Consumer
---
