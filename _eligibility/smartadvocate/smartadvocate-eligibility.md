---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only Subscriber’s employees may use the Software and only for Subscriber’s own law firm business use.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use prohibited
    text: Subscriber represents and warrants that it will not (a) use the Software in a manner that is prohibited by any law or regulation
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
name: SmartAdvocate
provenance_date: '2026-11-10'
provider_name: SmartAdvocate
provider_slug: smartadvocate
slug: smartadvocate-eligibility
source_date: '2026-11-10'
source_filename: smartadvocate-eligibility.yml
source_heading: Eligibility
source_page: https://www.smartadvocate.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SmartAdvocate\naid: smartadvocate\nurl: https://www.smartadvocate.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Only Subscriber’s employees may use the Software and only for Subscriber’s own law firm business use.\nrestricted_uses:\n- summary: Unlawful use prohibited\n  text: Subscriber represents and warrants that it will not (a) use the Software in a manner that is prohibited\n    by any law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/smartadvocate/eligibility/smartadvocate-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from SmartAdvocate's own page on 2026-11-10.
synthetic: false
tags:
- Legal Tech
- Case Management
- Software
- Litigation
- Cloud
---
