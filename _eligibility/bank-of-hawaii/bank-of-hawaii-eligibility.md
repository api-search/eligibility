---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not all of the products or services described on the site are available in all geographic areas.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Bank reserves the right to determine the eligibility for any product or service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bank of Hawaii
provenance_date: '2026-11-09'
provider_name: Bank of Hawaii
provider_slug: bank-of-hawaii
slug: bank-of-hawaii-eligibility
source_date: '2026-11-09'
source_filename: bank-of-hawaii-eligibility.yml
source_heading: Eligibility
source_page: https://www.boh.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bank of Hawaii\naid: bank-of-hawaii\nurl: https://www.boh.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not all of the products or services described on the site are available in all geographic areas.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Bank reserves the right to determine the eligibility for any product or service.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bank-of-hawaii/eligibility/bank-of-hawaii-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from Bank of Hawaii's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Regional Bank
- Open Finance
- Hawaii
---
