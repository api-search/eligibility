---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept for an organization, you confirm that you have authority to bind it.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Programmatic use of interactive surfaces
    text: Routing programmatic workloads through interactive surfaces in order to avoid the metered billing that applies to API and Automations usage.
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
name: Replicas
provenance_date: '2026-11-10'
provider_name: Replicas
provider_slug: replicas-dev
slug: replicas-dev-eligibility
source_date: '2026-11-10'
source_filename: replicas-dev-eligibility.yml
source_heading: Eligibility
source_page: https://replicas.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Replicas\naid: replicas-dev\nurl: https://replicas.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept for an organization, you confirm that you have authority to bind it.\nrestricted_uses:\n- summary: Programmatic use of interactive surfaces\n  text: Routing programmatic workloads through interactive surfaces in order to avoid the metered billing that applies\n    to API and Automations usage.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/replicas-dev/eligibility/replicas-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Replicas's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Cloud
- Platform
- Development
---
