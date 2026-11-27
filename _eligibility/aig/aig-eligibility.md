---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website and all information and functionalities contained therein are not directed at or intended for use by any person resident or located in any jurisdiction where the distribution of such information or functionality is contrary to the laws of such jurisdiction.
  minimum_age:
    text: you are of legal age in your country to form a binding contract
    value: legal age in your country
  restricted_uses:
  - summary: Unlawful or malicious use
    text: use the Website for any unlawful, unauthorized, fraudulent or malicious purpose.
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
name: AIG
provenance_date: '2026-11-09'
provider_name: AIG
provider_slug: aig
slug: aig-eligibility
source_date: '2026-11-09'
source_filename: aig-eligibility.yml
source_heading: Eligibility
source_page: https://www.aig.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIG\naid: aig\nurl: https://www.aig.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website and all information and functionalities contained therein are not directed at or intended for\n    use by any person resident or located in any jurisdiction where the distribution of such information or functionality\n    is contrary to the laws of such jurisdiction.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or malicious use\n  text: use the Website for any unlawful, unauthorized, fraudulent or malicious purpose.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: legal age in your country\n  text: you are of legal age in your country to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/aig/eligibility/aig-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AIG's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Financial Services
- Property and Casualty
- Cyber Insurance
- Enterprise
- Fortune 100
---
