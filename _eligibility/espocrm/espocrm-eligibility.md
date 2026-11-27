---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Unlawful and abusive uses
    text: 'You may not do, or try to do, the following: use the Services for any unlawful purpose or for promotion of illegal activities'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: EspoCRM reserves the right to request written confirmation regarding your authority to enter into this contract.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: EspoCRM
provenance_date: '2026-11-09'
provider_name: EspoCRM
provider_slug: espocrm
slug: espocrm-eligibility
source_date: '2026-11-09'
source_filename: espocrm-eligibility.yml
source_heading: Eligibility
source_page: https://www.espocrm.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EspoCRM\naid: espocrm\nurl: https://www.espocrm.com/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful and abusive uses\n  text: 'You may not do, or try to do, the following: use the Services for any unlawful purpose or for promotion\n    of illegal activities'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: EspoCRM reserves the right to request written confirmation regarding your authority to enter into this contract.\nminimum_age:\n  value: '18'\n  text: if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/espocrm/eligibility/espocrm-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from EspoCRM's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CRM
- Open Source
- Sales
- Marketing
---
