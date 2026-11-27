---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may enter into this Agreement on behalf of yourself or on behalf of a legal entity.
    type: individual
  - text: If you enter into this Agreement on behalf of a legal entity, you represent that you are a duly authorized representative with the authority to bind that legal entity to this Agreement.
    type: business
  minimum_age:
    text: VXT is not intended for use by individuals under the age of sixteen (16) years old.
    value: '16'
  restricted_uses:
  - summary: Emergency services
    text: Our Services are intended for business use and not intended for use (i) in connection with 111 or other emergency, public safety or similar services
  - summary: High-risk environments
    text: The services and software are not designed for use in hazardous or high-risk environments requiring fail-safe controls
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
name: VXT
provenance_date: '2026-11-10'
provider_name: VXT
provider_slug: vxt
slug: vxt-eligibility
source_date: '2026-11-10'
source_filename: vxt-eligibility.yml
source_heading: Eligibility
source_page: https://www.vxt.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VXT\naid: vxt\nurl: https://www.vxt.ai/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may enter into this Agreement on behalf of yourself or on behalf of a legal entity.\n- type: business\n  text: If you enter into this Agreement on behalf of a legal entity, you represent that you are a duly authorized\n    representative with the authority to bind that legal entity to this Agreement.\nrestricted_uses:\n- summary: Emergency services\n  text: Our Services are intended for business use and\
  \ not intended for use (i) in connection with 111 or other\n    emergency, public safety or similar services\n- summary: High-risk environments\n  text: The services and software are not designed for use in hazardous or high-risk environments requiring fail-safe\n    controls\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: VXT is not intended for use by individuals under the age of sixteen (16) years old.\n"
source_yaml_url: https://artifacts.apis.io/vxt/eligibility/vxt-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from VXT's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Legal Tech
- Call Automation
- Software-as-a-Service
---
