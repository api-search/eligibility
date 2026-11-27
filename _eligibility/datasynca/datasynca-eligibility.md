---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: DataSynca is offered to businesses and public bodies, not to consumers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk environments
    text: The Software and Website are not designed for use in nuclear facilities, aircraft navigation, air-traffic control, life-support, or other environments where failure could cause death, personal injury, or severe physical or environmental damage.
  - summary: Sole basis for significant decisions
    text: You must not use the Software as the sole basis for decisions with legal or similarly significant effects on individuals without human review appropriate to the risk.
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
name: DataSynca
provenance_date: '2026-11-09'
provider_name: DataSynca
provider_slug: datasynca
slug: datasynca-eligibility
source_date: '2026-11-09'
source_filename: datasynca-eligibility.yml
source_heading: Eligibility
source_page: https://datasynca.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DataSynca\naid: datasynca\nurl: https://datasynca.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: DataSynca is offered to businesses and public bodies, not to consumers.\nrestricted_uses:\n- summary: High-risk environments\n  text: The Software and Website are not designed for use in nuclear facilities, aircraft navigation, air-traffic\n    control, life-support, or other environments where failure could cause death, personal injury, or severe physical\n    or environmental damage.\n- summary: Sole basis for significant\
  \ decisions\n  text: You must not use the Software as the sole basis for decisions with legal or similarly significant effects\n    on individuals without human review appropriate to the risk.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/datasynca/eligibility/datasynca-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from DataSynca's own page on 2026-11-09.
synthetic: false
tags:
- Integration
- Automation
- Artificial Intelligence
- Enterprise
- Platform
---
