---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use of the website is available only to persons who can form a legally binding contract.
    type: other
  minimum_age:
    text: If you are a minor i.e. under the age of 18 years, you may use the SOFTWARE SUGGEST website only with the involvement of a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: Unlawful, fraudulent or abusive use
    text: You must not use the Website for any fraudulent purposes, or in connection with a criminal offense or other unlawful activity
  - summary: Interference with the website
    text: You shall not use the Website in any way that causes, or is likely to cause, the Website or access to it to be interrupted, damaged or impaired in any way.
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
name: SoftwareSuggest
provenance_date: '2026-11-10'
provider_name: SoftwareSuggest
provider_slug: softwaresuggest
slug: softwaresuggest-eligibility
source_date: '2026-11-10'
source_filename: softwaresuggest-eligibility.yml
source_heading: Eligibility
source_page: https://www.softwaresuggest.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SoftwareSuggest\naid: softwaresuggest\nurl: https://www.softwaresuggest.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: Use of the website is available only to persons who can form a legally binding contract.\nrestricted_uses:\n- summary: Unlawful, fraudulent or abusive use\n  text: You must not use the Website for any fraudulent purposes, or in connection with a criminal offense or other\n    unlawful activity\n- summary: Interference with the website\n  text: You shall not use the Website in any way that causes, or is likely to\
  \ cause, the Website or access to it\n    to be interrupted, damaged or impaired in any way.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are a minor i.e. under the age of 18 years, you may use the SOFTWARE SUGGEST website only with the\n    involvement of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/softwaresuggest/eligibility/softwaresuggest-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from SoftwareSuggest's own page on 2026-11-10.
synthetic: false
tags:
- Software Discovery
- Business Software
- Software-as-a-Service
- Software Reviews
- B2B
---
