---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 and give accurate information.
    type: individual
  - text: If you use SitesAI on behalf of a company, you confirm you're authorised to accept them for that company.
    type: business
  minimum_age:
    text: You must be at least 16 and give accurate information.
    value: '16'
  restricted_uses:
  - summary: Spam and unlawful content
    text: no unlawful content, no attempting to access other companies' data, no reselling without our agreement, no reverse engineering except as law permits, no interfering with the service's operation, and no using it to send spam.
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
name: sitesai-net
provenance_date: '2026-11-10'
provider_name: sitesai-net
provider_slug: sitesai-net
slug: sitesai-net-eligibility
source_date: '2026-11-10'
source_filename: sitesai-net-eligibility.yml
source_heading: Eligibility
source_page: https://sitesai.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: sitesai-net\naid: sitesai-net\nurl: https://sitesai.net/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 and give accurate information.\n- type: business\n  text: If you use SitesAI on behalf of a company, you confirm you're authorised to accept them for that company.\nrestricted_uses:\n- summary: Spam and unlawful content\n  text: no unlawful content, no attempting to access other companies' data, no reselling without our agreement,\n    no reverse engineering except as law permits, no interfering with\
  \ the service's operation, and no using it to\n    send spam.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 and give accurate information.\n"
source_yaml_url: https://artifacts.apis.io/sitesai-net/eligibility/sitesai-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from sitesai-net's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Construction
- Earthworks
- Estimating
- Field-Software
---
