---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using our Services on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No credit/employment/insurance decisions
    text: it must not be used to make decisions about credit, employment, housing, insurance, or eligibility for any benefit
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
name: misar-io
provenance_date: '2026-11-10'
provider_name: misar-io
provider_slug: misar-io
slug: misar-io-eligibility
source_date: '2026-11-10'
source_filename: misar-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.misar.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: misar-io\naid: misar-io\nurl: https://www.misar.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using our Services on behalf of an organization, you represent and warrant that you have the\n    authority to bind that organization to these Terms\nrestricted_uses:\n- summary: No credit/employment/insurance decisions\n  text: it must not be used to make decisions about credit, employment, housing, insurance, or eligibility for any\n    benefit\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/misar-io/eligibility/misar-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from misar-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Startups
- Software-as-a-Service
- Automation
---
