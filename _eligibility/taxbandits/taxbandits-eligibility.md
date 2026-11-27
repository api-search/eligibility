---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Services and the Website are offered to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Non-commercial use unless Tax Preparer
    text: Unless you are a Tax Preparer, this Agreement permits you to use the Website and Services for non-commercial, personal or internal business use only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access and use the Services, you will be required to register for a TaxBandits' account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TaxBandits
provenance_date: '2026-11-10'
provider_name: TaxBandits
provider_slug: taxbandits
slug: taxbandits-eligibility
source_date: '2026-11-10'
source_filename: taxbandits-eligibility.yml
source_heading: Eligibility
source_page: https://www.taxbandits.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TaxBandits\naid: taxbandits\nurl: https://www.taxbandits.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use unless Tax Preparer\n  text: Unless you are a Tax Preparer, this Agreement permits you to use the Website and Services for non-commercial,\n    personal or internal business use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access and use the Services, you will be required to register for a TaxBandits' account.\nminimum_age:\n  value: '18'\n  text: The Services\
  \ and the Website are offered to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/taxbandits/eligibility/taxbandits-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from TaxBandits's own page on 2026-11-10.
synthetic: false
tags:
- Tax
- Efiling
- IRS
- Automation
- Finance
---
