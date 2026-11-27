---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - SA
    text: تسري أحكام هذه الاتفاقية لمستخدمي المنصة داخل المملكة العربية السعودية فقط.
  entity_types:
  - text: 'المستخدم: هو الشخص الطبيعي أو الاعتباري المستفيد من خدمات منصة صفقة المالية.'
    type: individual
  - text: 'المستخدم: هو الشخص الطبيعي أو الاعتباري المستفيد من خدمات منصة صفقة المالية.'
    type: business
  minimum_age:
    text: لا يجوز للقاصرين التسجيل في المنصة.
    value: not stated
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: تقوم شركة صفقة المالية– في بعض الأحيان – بالتحقق من المستخدم باستخدام خدمة "يقين" المقدمة من شركة "علم".
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Safqah
provenance_date: '2026-11-10'
provider_name: Safqah
provider_slug: safqah-holdings-limited
slug: safqah-holdings-limited-eligibility
source_date: '2026-11-10'
source_filename: safqah-holdings-limited-eligibility.yml
source_heading: Eligibility
source_page: https://safqah.co/ar/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Safqah\naid: safqah-holdings-limited\nurl: https://safqah.co/ar/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SA\n  excluded: []\n  text: تسري أحكام هذه الاتفاقية لمستخدمي المنصة داخل المملكة العربية السعودية فقط.\nentity_types:\n- type: individual\n  text: 'المستخدم: هو الشخص الطبيعي أو الاعتباري المستفيد من خدمات منصة صفقة المالية.'\n- type: business\n  text: 'المستخدم: هو الشخص الطبيعي أو الاعتباري المستفيد من خدمات منصة صفقة المالية.'\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: تقوم شركة صفقة المالية– في بعض الأحيان – بالتحقق من المستخدم\
  \ باستخدام خدمة \"يقين\" المقدمة من شركة \"علم\".\nminimum_age:\n  value: not stated\n  text: لا يجوز للقاصرين التسجيل في المنصة.\n"
source_yaml_url: https://artifacts.apis.io/safqah-holdings-limited/eligibility/safqah-holdings-limited-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from Safqah's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Real Estate
- Investment
- Financing
- Crowdfunding
- Saudi Arabia
- Sharia-Compliant
---
