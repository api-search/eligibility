---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are 18 years of age or older or are at least of the legally required age in the jurisdiction in which you reside
    type: individual
  - text: If you accept or agree to these Terms of Service on behalf of your employer or another legal entity, you represent and warrant that (i) you have full legal authority to bind your employer or such entity
    type: business
  minimum_age:
    text: you are 18 years of age or older or are at least of the legally required age in the jurisdiction in which you reside
    value: '18'
  restricted_uses:
  - summary: Journalistic, investigative or unlawful purpose
    text: if you are using or will or intend to use the Services for any journalistic, investigative, or unlawful purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Liberate has the right to restrict anyone from completing registration as a user if Liberate believes such person may threaten the safety and integrity of the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Liberate
provenance_date: '2026-11-09'
provider_name: Liberate
provider_slug: liberate
slug: liberate-eligibility
source_date: '2026-11-09'
source_filename: liberate-eligibility.yml
source_heading: Eligibility
source_page: https://www.liberate.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Liberate\naid: liberate\nurl: https://www.liberate.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are 18 years of age or older or are at least of the legally required age in the jurisdiction in which\n    you reside\n- type: business\n  text: If you accept or agree to these Terms of Service on behalf of your employer or another legal entity, you\n    represent and warrant that (i) you have full legal authority to bind your employer or such entity\nrestricted_uses:\n- summary: Journalistic, investigative\
  \ or unlawful purpose\n  text: if you are using or will or intend to use the Services for any journalistic, investigative, or unlawful\n    purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Liberate has the right to restrict anyone from completing registration as a user if Liberate believes such\n    person may threaten the safety and integrity of the Services\nminimum_age:\n  value: '18'\n  text: you are 18 years of age or older or are at least of the legally required age in the jurisdiction in which\n    you reside\n"
source_yaml_url: https://artifacts.apis.io/liberate/eligibility/liberate-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Liberate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Insurance
- Insurtech
- Voice AI
- AI Agents
- Workflow Orchestration
- Claims Automation
- Low-Code
- Contact Center
---
