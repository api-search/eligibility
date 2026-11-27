---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is directed solely to individuals residing in jurisdictions in which provision of the Site's content is legal.
  minimum_age:
    text: You affirm that you are over the age of 18, as the Site is not intended for children under 18.
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: Use the Site for any unlawful purpose;
  - summary: Money laundering and terrorism financing
    text: You may not use the Site in a manner which violates our anti-money laundering, counter terrorist financing or similar regulatory obligations.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may require you to provide additional information or documents to verify your identity, including your date of birth, physical address, taxpayer or other identification number
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SeekingAlpha
provenance_date: '2026-11-10'
provider_name: SeekingAlpha
provider_slug: seekingalpha
slug: seekingalpha-eligibility
source_date: '2026-11-10'
source_filename: seekingalpha-eligibility.yml
source_heading: Eligibility
source_page: https://about.seekingalpha.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SeekingAlpha\naid: seekingalpha\nurl: https://about.seekingalpha.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site is directed solely to individuals residing in jurisdictions in which provision of the Site's content\n    is legal.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use the Site for any unlawful purpose;\n- summary: Money laundering and terrorism financing\n  text: You may not use the Site in a manner which violates our anti-money laundering, counter terrorist financing\n    or similar regulatory obligations.\nverification:\n\
  \  kyc: true\n  kyb: null\n  approval_required: null\n  text: We may require you to provide additional information or documents to verify your identity, including your\n    date of birth, physical address, taxpayer or other identification number\nminimum_age:\n  value: '18'\n  text: You affirm that you are over the age of 18, as the Site is not intended for children under 18.\n"
source_yaml_url: https://artifacts.apis.io/seekingalpha/eligibility/seekingalpha-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from SeekingAlpha's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social
- Finance
- Investing
- Stock Market
- Financial Research
- Media
---
