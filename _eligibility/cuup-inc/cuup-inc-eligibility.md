---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We ship to approximately 90 countries around the world.
  minimum_age:
    text: If you are under the age of 18, you may use the Site only with involvement of a parent or legal guardian.
    value: null
  restricted_uses:
  - summary: No commercial resale purchases
    text: Commercial purchases for resale are not permitted.
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
name: CUUP
provenance_date: '2026-11-09'
provider_name: CUUP
provider_slug: cuup-inc
slug: cuup-inc-eligibility
source_date: '2026-11-09'
source_filename: cuup-inc-eligibility.yml
source_heading: Eligibility
source_page: https://www.shopcuup.com/c/terms-of-use-ca.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CUUP\naid: cuup-inc\nurl: https://www.shopcuup.com/c/terms-of-use-ca.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We ship to approximately 90 countries around the world.\nentity_types: []\nrestricted_uses:\n- summary: No commercial resale purchases\n  text: Commercial purchases for resale are not permitted.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: If you are under the age of 18, you may use the Site only with involvement of a parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/cuup-inc/eligibility/cuup-inc-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CUUP's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Retail
- E-Commerce
- Apparel
- Intimates
- Direct to Consumer
- Fashion
---
