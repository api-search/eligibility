---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you confirm that you are at least 18 years old and have the legal capacity to enter into these Terms.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: you confirm that you are at least 18 years old and have the legal capacity to enter into these Terms.
    value: '18'
  restricted_uses:
  - summary: Unlawful purpose
    text: Use the Service for any unlawful purpose or in violation of any applicable laws or regulations.
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
name: Adrio
provenance_date: '2026-11-09'
provider_name: Adrio
provider_slug: adrio-ai
slug: adrio-ai-eligibility
source_date: '2026-11-09'
source_filename: adrio-ai-eligibility.yml
source_heading: Eligibility
source_page: https://adrio.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adrio\naid: adrio-ai\nurl: https://adrio.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you confirm that you are at least 18 years old and have the legal capacity to enter into these Terms.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\nrestricted_uses:\n- summary: Unlawful purpose\n  text: Use the Service for any unlawful purpose or in violation of any applicable laws or regulations.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you confirm that you are at least 18 years old and have the legal capacity to enter into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/adrio-ai/eligibility/adrio-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Adrio's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Advertising
- Creative
- Meta
- Marketing
---
