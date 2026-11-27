---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access or use of the Internet or of certain websites may be prohibited in certain territories and/or certain restrictions may apply to you in such territories.
  entity_types:
  - text: Our Site is intended for use by natural persons.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial purposes
    text: Any use of the Site or any parts thereof or information therein for any commercial purposes is prohibited.
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
name: Nym
provenance_date: '2026-11-10'
provider_name: Nym
provider_slug: nym
slug: nym-eligibility
source_date: '2026-11-10'
source_filename: nym-eligibility.yml
source_heading: Eligibility
source_page: https://nym.health/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nym\naid: nym\nurl: https://nym.health/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access or use of the Internet or of certain websites may be prohibited in certain territories and/or certain\n    restrictions may apply to you in such territories.\nentity_types:\n- type: individual\n  text: Our Site is intended for use by natural persons.\nrestricted_uses:\n- summary: Commercial purposes\n  text: Any use of the Site or any parts thereof or information therein for any commercial purposes is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nym/eligibility/nym-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Nym's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Healthcare
- Medical Coding
- Revenue Cycle Management
- Health IT
- Clinical NLP
---
