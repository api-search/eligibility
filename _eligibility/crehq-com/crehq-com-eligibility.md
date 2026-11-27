---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use CREHQ.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use CREHQ.
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: Use the Service for illegal purposes including fraud, harassment, or infringement
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
name: CREHQ
provenance_date: '2026-11-09'
provider_name: CREHQ
provider_slug: crehq-com
slug: crehq-com-eligibility
source_date: '2026-11-09'
source_filename: crehq-com-eligibility.yml
source_heading: Eligibility
source_page: https://crehq.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CREHQ\naid: crehq-com\nurl: https://crehq.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use CREHQ.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\nrestricted_uses:\n- summary: Illegal purposes\n  text: Use the Service for illegal purposes including fraud, harassment, or infringement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use CREHQ.\n"
source_yaml_url: https://artifacts.apis.io/crehq-com/eligibility/crehq-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CREHQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commercial Real Estate
- Location Intelligence
- Location Data
- Datasets
- Franchise Data
- Site Selection
- MCP
- Data Licensing
---
