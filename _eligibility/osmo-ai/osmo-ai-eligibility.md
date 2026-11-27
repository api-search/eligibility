---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Services may not be legal by certain persons or in certain countries. If you access the Services from outside the United States, you do so on your own initiative and are responsible for compliance with local laws.
  entity_types:
  - text: The Services are offered and available to users who are 18 years of age or older.
    type: individual
  - text: If you are accessing or using the Services on behalf of your employer, you represent and warrant that you have sufficient authority to bind your employer to these Terms.
    type: business
  minimum_age:
    text: The Services are offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: You may use the Services only for lawful purposes and in accordance with these Terms.
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
name: Osmo
provenance_date: '2026-11-10'
provider_name: Osmo
provider_slug: osmo-ai
slug: osmo-ai-eligibility
source_date: '2026-11-10'
source_filename: osmo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.osmo.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Osmo\naid: osmo-ai\nurl: https://www.osmo.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Services may not be legal by certain persons or in certain countries. If you access the Services\n    from outside the United States, you do so on your own initiative and are responsible for compliance with local\n    laws.\nentity_types:\n- type: individual\n  text: The Services are offered and available to users who are 18 years of age or older.\n- type: business\n  text: If you are accessing or using the Services on behalf of your employer, you represent\
  \ and warrant that you\n    have sufficient authority to bind your employer to these Terms.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: You may use the Services only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/osmo-ai/eligibility/osmo-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Osmo's own page on 2026-11-10.
synthetic: false
tags:
- Fragrance
- Artificial Intelligence
- Product Development
- Manufacturing
- Packaging
---
