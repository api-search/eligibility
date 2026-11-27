---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You can only use Spike if you can form a legally binding contract with us under the laws that apply to you, according to wherever you are.
    type: individual
  - text: If you are using Spike on behalf of a group or organization, you agree to these Terms on behalf of that group or organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or abusive conduct
    text: Violate any applicable law in any way, or violate the privacy of others, or defame or disparage others.
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
name: Spike
provenance_date: '2026-11-10'
provider_name: Spike
provider_slug: spike
slug: spike-eligibility
source_date: '2026-11-10'
source_filename: spike-eligibility.yml
source_heading: Eligibility
source_page: https://www.spikenow.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spike\naid: spike\nurl: https://www.spikenow.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You can only use Spike if you can form a legally binding contract with us under the laws that apply to you,\n    according to wherever you are.\n- type: business\n  text: If you are using Spike on behalf of a group or organization, you agree to these Terms on behalf of that\n    group or organization\nrestricted_uses:\n- summary: Unlawful or abusive conduct\n  text: Violate any applicable law in any way, or violate\
  \ the privacy of others, or defame or disparage others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/spike/eligibility/spike-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Spike's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email
- Collaboration
- Team Chat
- Productivity
- Communications
- Artificial Intelligence
---
