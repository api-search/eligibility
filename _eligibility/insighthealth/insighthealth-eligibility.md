---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents it is not located in an embargoed country or territory, and Trade Restrictions list Cuba, the Crimea region of the Ukraine, Sudan, Iran, North Korea and Syria.
  entity_types:
  - text: If you use the Services on behalf of an entity or another individual, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful or high-risk use
    text: use the Services in a way that would create risk to an individual’s life, health, safety, property, or other rights or interests
  - summary: No sensitive personal info storage
    text: store or transmit through the Services any sensitive personal information except as explicitly authorized in these Terms or an Order Form
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
name: Insight Health
provenance_date: '2026-11-09'
provider_name: Insight Health
provider_slug: insighthealth
slug: insighthealth-eligibility
source_date: '2026-11-09'
source_filename: insighthealth-eligibility.yml
source_heading: Eligibility
source_page: https://www.insighthealth.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Insight Health\naid: insighthealth\nurl: https://www.insighthealth.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents it is not located in an embargoed country or territory, and Trade Restrictions list\n    Cuba, the Crimea region of the Ukraine, Sudan, Iran, North Korea and Syria.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of an entity or another individual, you represent and warrant that you\n    have the authority to bind that entity\nrestricted_uses:\n- summary: No unlawful or high-risk use\n  text: use the\
  \ Services in a way that would create risk to an individual’s life, health, safety, property, or other\n    rights or interests\n- summary: No sensitive personal info storage\n  text: store or transmit through the Services any sensitive personal information except as explicitly authorized\n    in these Terms or an Order Form\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/insighthealth/eligibility/insighthealth-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Insight Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Clinical Documentation
- Voice Agents
- Electronic Health Records
- HIPAA
- FHIR
- Medical
- Patient Engagement
---
