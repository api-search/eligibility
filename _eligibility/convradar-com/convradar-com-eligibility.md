---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 16 years of age to use the Service.
    value: '16'
  restricted_uses:
  - summary: No unlawful or rights-violating use
    text: Use the Service to violate any third-party rights or applicable laws.
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
name: Conversion Radar
provenance_date: '2026-11-09'
provider_name: Conversion Radar
provider_slug: convradar-com
slug: convradar-com-eligibility
source_date: '2026-11-09'
source_filename: convradar-com-eligibility.yml
source_heading: Eligibility
source_page: https://convradar.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conversion Radar\naid: convradar-com\nurl: https://convradar.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\nrestricted_uses:\n- summary: No unlawful or rights-violating use\n  text: Use the Service to violate any third-party rights or applicable laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must\
  \ be at least 16 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/convradar-com/eligibility/convradar-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Conversion Radar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Google Analytics 4
- MCP
- Conversion Rate Optimization
- E-Commerce
- Benchmarks
- AI Agents
---
