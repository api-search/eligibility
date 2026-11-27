---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The products and services described in the pages of this site are only available in jurisdictions where they can legally be offered.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Any application for a credit product or service is subject to credit approval by Laurentian Bank.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Laurentian Bank of Canada
provenance_date: '2026-11-09'
provider_name: Laurentian Bank of Canada
provider_slug: laurentian-bank
slug: laurentian-bank-eligibility
source_date: '2026-11-09'
source_filename: laurentian-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.laurentianbank.ca/en/personal/legal-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Laurentian Bank of Canada\naid: laurentian-bank\nurl: https://www.laurentianbank.ca/en/personal/legal-notice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The products and services described in the pages of this site are only available in jurisdictions where\n    they can legally be offered.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Any application for a credit product or service is subject to credit approval by Laurentian Bank.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/laurentian-bank/eligibility/laurentian-bank-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from Laurentian Bank of Canada's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- Canada
- Schedule I Bank
- Consumer Banking
- Quebec
- Interac
---
