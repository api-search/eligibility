---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    - US
    text: Vocca operates in France and in the United States.
  entity_types:
  - text: healthcare organization customers (“Practices”)
    type: business
  - text: and to patients receiving communications sent through the platform.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No marketing messages to patients
    text: No promotional, advertising or marketing Message is sent to Patients through the Platform.
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
name: Vocca Ai
provenance_date: '2026-11-10'
provider_name: Vocca Ai
provider_slug: vocca-ai
slug: vocca-ai-eligibility
source_date: '2026-11-10'
source_filename: vocca-ai-eligibility.yml
source_heading: Eligibility
source_page: https://vocca.com/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vocca Ai\naid: vocca-ai\nurl: https://vocca.com/en/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - FR\n  - US\n  excluded: []\n  text: Vocca operates in France and in the United States.\nentity_types:\n- type: business\n  text: healthcare organization customers (“Practices”)\n- type: individual\n  text: and to patients receiving communications sent through the platform.\nrestricted_uses:\n- summary: No marketing messages to patients\n  text: No promotional, advertising or marketing Message is sent to Patients through the Platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vocca-ai/eligibility/vocca-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Vocca Ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Voice AI
- Conversational AI
- Artificial Intelligence
- Medical
- Patient Communications
- Appointment Booking
- Agents
---
