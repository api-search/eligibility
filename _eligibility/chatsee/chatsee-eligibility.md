---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “you” means you and any organization on whose behalf you sign up for a subscription
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing data
    text: use the Platform or SDK to store or transmit any infringing, unlawful, or tortious material, or any data for which you lack the necessary rights or consents
  - summary: Export law compliance
    text: You will not use or export the Platform, SDK, or Your Data in violation of Export Laws or for any prohibited purpose
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
name: ChatSee
provenance_date: '2026-11-09'
provider_name: ChatSee
provider_slug: chatsee
slug: chatsee-eligibility
source_date: '2026-11-09'
source_filename: chatsee-eligibility.yml
source_heading: Eligibility
source_page: https://www.chatsee.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChatSee\naid: chatsee\nurl: https://www.chatsee.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “you” means you and any organization on whose behalf you sign up for a subscription\nrestricted_uses:\n- summary: Unlawful or infringing data\n  text: use the Platform or SDK to store or transmit any infringing, unlawful, or tortious material, or any data\n    for which you lack the necessary rights or consents\n- summary: Export law compliance\n  text: You will not use or export the Platform, SDK, or Your Data in violation\
  \ of Export Laws or for any prohibited\n    purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chatsee/eligibility/chatsee-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from ChatSee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Observability
- Enterprise
- Governance
- Monitoring
---
