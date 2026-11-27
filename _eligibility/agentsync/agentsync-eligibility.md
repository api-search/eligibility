---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By signing an Order Form, Customer agrees to these Standard Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No AI or automated access restrictions stated
    text: Customer will use the Software Services in compliance with these Terms, the Software Service documentation, all applicable laws, and regulations, including the requirements of FCRA
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
name: Agentsync
provenance_date: '2026-11-09'
provider_name: Agentsync
provider_slug: agentsync
slug: agentsync-eligibility
source_date: '2026-11-09'
source_filename: agentsync-eligibility.yml
source_heading: Eligibility
source_page: https://agentsync.io/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agentsync\naid: agentsync\nurl: https://agentsync.io/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By signing an Order Form, Customer agrees to these Standard Terms\nrestricted_uses:\n- summary: No AI or automated access restrictions stated\n  text: Customer will use the Software Services in compliance with these Terms, the Software Service documentation,\n    all applicable laws, and regulations, including the requirements of FCRA\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentsync/eligibility/agentsync-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Agentsync's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Compliance
- Producer Management
- Licensing
- NIPR
- REST
- OAuth
- Authentication
---
