---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AE
    text: This Platform is intended for use only by UAE residents. If you choose to use the Platform from locations outside the UAE, you do so at your sole risk.
  minimum_age:
    text: be legally capable of entering into binding contracts and be 21 years of age or over.
    value: '21'
  restricted_uses:
  - summary: Lawful purposes only
    text: You agree to use our Platform and the Services for lawful purposes only and in a way that does not infringe on the rights of any third party
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We reserve the right to reject or approve any request to create an account, to suspend your account and/or to delete your account at our sole discretion without any liability for the same.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: huspy
provenance_date: '2026-11-09'
provider_name: huspy
provider_slug: huspy
slug: huspy-eligibility
source_date: '2026-11-09'
source_filename: huspy-eligibility.yml
source_heading: Eligibility
source_page: https://huspy.com/ae/content/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: huspy\naid: huspy\nurl: https://huspy.com/ae/content/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AE\n  excluded: []\n  text: This Platform is intended for use only by UAE residents. If you choose to use the Platform from locations\n    outside the UAE, you do so at your sole risk.\nentity_types: []\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You agree to use our Platform and the Services for lawful purposes only and in a way that does not infringe\n    on the rights of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We\
  \ reserve the right to reject or approve any request to create an account, to suspend your account and/or\n    to delete your account at our sole discretion without any liability for the same.\nminimum_age:\n  value: '21'\n  text: be legally capable of entering into binding contracts and be 21 years of age or over.\n"
source_yaml_url: https://artifacts.apis.io/huspy/eligibility/huspy-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from huspy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mortgage
- Real Estate
- PropTech
- Fintech
- Lending
- United Arab Emirates
- Dubai
---
