---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our platform provides AI-powered SEO and GEO analysis tools for professionals and businesses.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: Use the service for any illegal or unauthorized purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use most features, you'll need to create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Citedy
provenance_date: '2026-11-09'
provider_name: Citedy
provider_slug: citedy-com
slug: citedy-com-eligibility
source_date: '2026-11-09'
source_filename: citedy-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.citedy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Citedy\naid: citedy-com\nurl: https://www.citedy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Our platform provides AI-powered SEO and GEO analysis tools for professionals and businesses.\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: Use the service for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use most features, you'll need to create an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/citedy-com/eligibility/citedy-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Citedy's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- SEO
- Content Automation
- Agents
- Platform
---
