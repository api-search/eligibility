---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - SA
    text: تُخصص سيولا الخدمات للمستخدمين في المملكة العربية السعودية فقط
  minimum_age:
    text: لا يُسمح لك باستخدام الخدمات إذا كان عمرك أقل من 18 عاماً أو لا تتمتع بالأهلية القانونية لإبرام عقد ملزم.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: تعتمد سيولا في ذلك على البيانات المقدمة من العميل لأغراض التحقق من الهوية.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Siolla
provenance_date: '2026-11-10'
provider_name: Siolla
provider_slug: siolla
slug: siolla-eligibility
source_date: '2026-11-10'
source_filename: siolla-eligibility.yml
source_heading: Eligibility
source_page: https://www.siolla.com/ar/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Siolla\naid: siolla\nurl: https://www.siolla.com/ar/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SA\n  excluded: []\n  text: تُخصص سيولا الخدمات للمستخدمين في المملكة العربية السعودية فقط\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: تعتمد سيولا في ذلك على البيانات المقدمة من العميل لأغراض التحقق من الهوية.\nminimum_age:\n  value: '18'\n  text: لا يُسمح لك باستخدام الخدمات إذا كان عمرك أقل من 18 عاماً أو لا تتمتع بالأهلية القانونية لإبرام عقد ملزم.\n"
source_yaml_url: https://artifacts.apis.io/siolla/eligibility/siolla-eligibility.yml
stated_fields:
- countries
- verification
- minimum_age
summary_line: 3 quoted statements, read from Siolla's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Investment
- Wealth Management
- Portfolio Management
- Sharia-Compliant
- Saudi Arabia
- Mobile App
---
