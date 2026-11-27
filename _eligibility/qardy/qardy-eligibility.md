---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - EG
    text: يجب أن يكون المتقدمون كيانات تجارية قانونية أو مُمثلين مفوضين رسميًا عن أنشطة تجارية مسجلة داخل جمهورية مصر العربية.
  entity_types:
  - text: يجب أن يكون المتقدمون كيانات تجارية قانونية أو مُمثلين مفوضين رسميًا عن أنشطة تجارية مسجلة داخل جمهورية مصر العربية.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: ويتعين على المتقدمين تقديم سجل تجاري ساري وبطاقة ضريبية صالحة وإثبات هوية المفوض بالتوقيع نيابة عن المنشأة.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Qardy
provenance_date: '2026-11-10'
provider_name: Qardy
provider_slug: qardy
slug: qardy-eligibility
source_date: '2026-11-10'
source_filename: qardy-eligibility.yml
source_heading: Eligibility
source_page: https://eqardy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qardy\naid: qardy\nurl: https://eqardy.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - EG\n  excluded: []\n  text: يجب أن يكون المتقدمون كيانات تجارية قانونية أو مُمثلين مفوضين رسميًا عن أنشطة تجارية مسجلة داخل جمهورية\n    مصر العربية.\nentity_types:\n- type: business\n  text: يجب أن يكون المتقدمون كيانات تجارية قانونية أو مُمثلين مفوضين رسميًا عن أنشطة تجارية مسجلة داخل جمهورية\n    مصر العربية.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: ويتعين على المتقدمين تقديم سجل تجاري ساري وبطاقة ضريبية صالحة وإثبات هوية المفوض بالتوقيع نيابة عن المنشأة.\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/qardy/eligibility/qardy-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from Qardy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Lending
- Fintech
- SME Financing
- Invoice Financing
- Supply Chain Financing
- Marketplace
- Egypt
- MENA
- Debt Financing
---
