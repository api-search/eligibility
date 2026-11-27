---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: You may not use the Service if you are barred from doing so under the laws of your country or the United States, or if you are on a US government restricted-party or sanctions list.
  entity_types:
  - text: If you create an account on behalf of an organisation, you confirm that you are authorised to accept these terms for that organisation
    type: business
  minimum_age:
    text: You must be at least 13 years old to use Narrative.
    value: '13'
  restricted_uses:
  - summary: Deepfakes without consent
    text: creates a synthetic, altered or “deepfake” depiction of a real, identifiable person without that person's consent, or that is intended to deceive, defraud, defame, harass, or impersonate
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Usenarrative
provenance_date: '2026-11-10'
provider_name: Usenarrative
provider_slug: usenarrative-ai
slug: usenarrative-ai-eligibility
source_date: '2026-11-10'
source_filename: usenarrative-ai-eligibility.yml
source_heading: Eligibility
source_page: https://usenarrative.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Usenarrative\naid: usenarrative-ai\nurl: https://usenarrative.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  text: You may not use the Service if you are barred from doing so under the laws of your country or the United\n    States, or if you are on a US government restricted-party or sanctions list.\nentity_types:\n- type: business\n  text: If you create an account on behalf of an organisation, you confirm that you are authorised to accept these\n    terms for that organisation\nrestricted_uses:\n- summary: Deepfakes without consent\n  text: creates a synthetic, altered\
  \ or “deepfake” depiction of a real, identifiable person without that person's\n    consent, or that is intended to deceive, defraud, defame, harass, or impersonate\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use Narrative.\n"
source_yaml_url: https://artifacts.apis.io/usenarrative-ai/eligibility/usenarrative-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Usenarrative's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video Editing
- Software-as-a-Service
- Creator Tools
---
