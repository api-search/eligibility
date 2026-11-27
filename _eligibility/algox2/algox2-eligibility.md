---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Site on behalf of an organization, you agree to these Terms for that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use of the Site
    text: Use the Site in a way that violates any law or the rights of any person
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
name: AlgoX2
provenance_date: '2026-11-09'
provider_name: AlgoX2
provider_slug: algox2
slug: algox2-eligibility
source_date: '2026-11-09'
source_filename: algox2-eligibility.yml
source_heading: Eligibility
source_page: https://www.algox2.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AlgoX2\naid: algox2\nurl: https://www.algox2.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Site on behalf of an organization, you agree to these Terms for that organization.\nrestricted_uses:\n- summary: Unlawful use of the Site\n  text: Use the Site in a way that violates any law or the rights of any person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/algox2/eligibility/algox2-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from AlgoX2's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Streaming
- Infrastructure
- Real-Time
- Market Data
- Analytics
- Messaging
---
