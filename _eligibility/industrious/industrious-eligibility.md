---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The products and services available through the Site may not be available in your country.
  entity_types:
  - text: you are at least 18 years old
    type: individual
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You may not download or export any software or content from the Site (i) into any country subject to a U.S. or U.N. embargo or sanction
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
name: Industrious
provenance_date: '2026-11-09'
provider_name: Industrious
provider_slug: industrious
slug: industrious-eligibility
source_date: '2026-11-09'
source_filename: industrious-eligibility.yml
source_heading: Eligibility
source_page: https://www.industriousoffice.com/site-portal-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Industrious\naid: industrious\nurl: https://www.industriousoffice.com/site-portal-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The products and services available through the Site may not be available in your country.\nentity_types:\n- type: individual\n  text: you are at least 18 years old\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: You may not download or export any software or content from the Site (i) into any country subject to a U.S.\n    or U.N. embargo or sanction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n \
  \ text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/industrious/eligibility/industrious-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Industrious's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Flex Office
- Co-Working
- Workspace
- Commercial Real Estate
- Office Space
---
