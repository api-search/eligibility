---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents that neither it nor any of its Users is located in, organized under the laws of, or ordinarily resident in a country or region subject to comprehensive U.S. sanctions
  entity_types:
  - text: The Services are offered only to businesses and other organizations for their internal business purposes, and not to consumers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited data
    text: Customer must not submit Prohibited Data to the Services, including protected health information regulated by HIPAA.
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
name: Infera Health
provenance_date: '2026-11-09'
provider_name: Infera Health
provider_slug: infera-health
slug: infera-health-eligibility
source_date: '2026-11-09'
source_filename: infera-health-eligibility.yml
source_heading: Eligibility
source_page: https://infera.com/docs/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Infera Health\naid: infera-health\nurl: https://infera.com/docs/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents that neither it nor any of its Users is located in, organized under the laws of, or\n    ordinarily resident in a country or region subject to comprehensive U.S. sanctions\nentity_types:\n- type: business\n  text: The Services are offered only to businesses and other organizations for their internal business purposes,\n    and not to consumers.\nrestricted_uses:\n- summary: Prohibited data\n  text: Customer must not submit Prohibited\
  \ Data to the Services, including protected health information regulated\n    by HIPAA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/infera-health/eligibility/infera-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Infera Health's own page on 2026-11-09.
synthetic: false
tags:
- Compliance
- Medical Devices
- Artificial Intelligence
- Software
- Risk Management
- Verification
- Release Management
- Document Control
---
