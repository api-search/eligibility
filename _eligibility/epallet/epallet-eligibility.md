---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Epallet is business-to-business only. Please be prepared to provide a valid reseller's permit (business license)
    type: business
  - text: or tax-exempt certificate (for a non-profit organization)
    type: nonprofit
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: B2B purchasing only
    text: Epallet is business-to-business only.
  verification:
    approval_required: null
    kyb: true
    kyc: null
    text: Please be prepared to provide a valid reseller's permit (business license) or tax-exempt certificate (for a non-profit organization) and show proof that you are authorized to purchase for said business or organization.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ePallet
provenance_date: '2026-11-09'
provider_name: ePallet
provider_slug: epallet
slug: epallet-eligibility
source_date: '2026-11-09'
source_filename: epallet-eligibility.yml
source_heading: Eligibility
source_page: https://epallet.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ePallet\naid: epallet\nurl: https://epallet.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Epallet is business-to-business only. Please be prepared to provide a valid reseller's permit (business\n    license)\n- type: nonprofit\n  text: or tax-exempt certificate (for a non-profit organization)\nrestricted_uses:\n- summary: B2B purchasing only\n  text: Epallet is business-to-business only.\nverification:\n  kyc: null\n  kyb: true\n  approval_required: null\n  text: Please be prepared to provide a valid reseller's permit\
  \ (business license) or tax-exempt certificate (for\n    a non-profit organization) and show proof that you are authorized to purchase for said business or organization.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/epallet/eligibility/epallet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from ePallet's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- Wholesale
- Marketplace
- bulk-buying
- Logistics
- B2B
- Retail
---
