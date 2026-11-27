---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use it if you are barred from doing so under the laws of the United States or where you live, or if you are on a US government restricted-party list.
  entity_types:
  - text: The Service is intended for businesses, developers and professionals.
    type: business
  minimum_age:
    text: You must be at least 18 and able to enter a binding contract.
    value: '18'
  restricted_uses:
  - summary: Illegal content or content without rights
    text: process content that is illegal, including child sexual abuse material, or content you have no right to use
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
name: etchv
provenance_date: '2026-11-09'
provider_name: etchv
provider_slug: etchv
slug: etchv-eligibility
source_date: '2026-11-09'
source_filename: etchv-eligibility.yml
source_heading: Eligibility
source_page: https://etchv.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: etchv\naid: etchv\nurl: https://etchv.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use it if you are barred from doing so under the laws of the United States or where you live,\n    or if you are on a US government restricted-party list.\nentity_types:\n- type: business\n  text: The Service is intended for businesses, developers and professionals.\nrestricted_uses:\n- summary: Illegal content or content without rights\n  text: process content that is illegal, including child sexual abuse material, or content you have no right to\n    use\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to enter a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/etchv/eligibility/etchv-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from etchv's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Watermarking
- Media
- Security
- Developer Tools
---
