---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Eligibility requirements may include factors such as industry, company size, use case, or geographic location
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or unauthorized use
    text: Unlawful use of the Platform or data obtained through the Platform
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Lifetime Deal is available exclusively to customers who meet Customers.ai’s then-current Ideal Customer Profile (“ICP”) criteria, as determined by Customers.ai in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Customersai
provenance_date: '2026-11-09'
provider_name: Customersai
provider_slug: customersai
slug: customersai-eligibility
source_date: '2026-11-09'
source_filename: customersai-eligibility.yml
source_heading: Eligibility
source_page: https://customers.ai/inboxer-lifetime-deal-terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Customersai\naid: customersai\nurl: https://customers.ai/inboxer-lifetime-deal-terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Eligibility requirements may include factors such as industry, company size, use case, or geographic location\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or unauthorized use\n  text: Unlawful use of the Platform or data obtained through the Platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Lifetime Deal is available exclusively to customers who meet Customers.ai’s then-current Ideal Customer\n\
  \    Profile (“ICP”) criteria, as determined by Customers.ai in its sole discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/customersai/eligibility/customersai-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Customersai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Marketing
- E-Commerce
- Data
- Identity Resolution
- Data Enrichment
- Software-as-a-Service
- B2B
---
