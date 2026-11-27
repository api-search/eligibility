---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Due to policy, this service is not available in mainland China.
  entity_types:
  - text: Croxy users must be natural persons with full capacity for civil conduct.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Legal compliance of use
    text: You should ensure that your use of this service complies with the requirements of laws and regulations.
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
name: Croxy
provenance_date: '2026-11-09'
provider_name: Croxy
provider_slug: croxy
slug: croxy-eligibility
source_date: '2026-11-09'
source_filename: croxy-eligibility.yml
source_heading: Eligibility
source_page: https://croxy.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Croxy\naid: croxy\nurl: https://croxy.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Due to policy, this service is not available in mainland China.\nentity_types:\n- type: individual\n  text: Croxy users must be natural persons with full capacity for civil conduct.\nrestricted_uses:\n- summary: Legal compliance of use\n  text: You should ensure that your use of this service complies with the requirements of laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/croxy/eligibility/croxy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Croxy's own page on 2026-11-09.
synthetic: false
tags:
- Proxy
- Residential Proxy
- Web Scraping
- Developer Tools
---
