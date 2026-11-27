---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - SA
    text: تقدم صادق الخدمات المتعلقة بالتحقق من الهوية عبر منصة النفاذ الوطني الموحد للمستخدمين الذين مقر إقامتهم المملكة العربية السعودية
  entity_types:
  - text: تنطبق هذه الشروط والأحكام على استخدام المنصة وخدماتها من قبل الكيانات التجارية والمؤسسية
    type: business
  - text: في حال كان المستخدم جهة تجارية أو حكومية أو أي كيان اعتباري
    type: government
  - text: ولا تمتد لتشمل الاستخدام الشخصي أو الاستهلاكي من قبل الأفراد.
    type: individual
  minimum_age:
    text: القاصر غير مخول له الدخول أو التسجيل كمستخدم
    value: null
  restricted_uses:
  - summary: Legal capacity required
    text: مصرح باستخدامه أو الوصول إليه فقط بواسطة أشخاص لهم أهلية التعاقد القانوني
  - summary: Minors may not register
    text: القاصر غير مخول له الدخول أو التسجيل كمستخدم على التطبيق/المنصة/الموقع الإلكتروني.
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
name: Sadq Holding Limited
provenance_date: '2026-11-10'
provider_name: Sadq Holding Limited
provider_slug: sadq-sa-com
slug: sadq-sa-com-eligibility
source_date: '2026-11-10'
source_filename: sadq-sa-com-eligibility.yml
source_heading: Eligibility
source_page: https://sadq.sa/ar/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sadq Holding Limited\naid: sadq-sa-com\nurl: https://sadq.sa/ar/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SA\n  excluded: []\n  text: تقدم صادق الخدمات المتعلقة بالتحقق من الهوية عبر منصة النفاذ الوطني الموحد للمستخدمين الذين مقر إقامتهم\n    المملكة العربية السعودية\nentity_types:\n- type: business\n  text: تنطبق هذه الشروط والأحكام على استخدام المنصة وخدماتها من قبل الكيانات التجارية والمؤسسية\n- type: government\n  text: في حال كان المستخدم جهة تجارية أو حكومية أو أي كيان اعتباري\n- type: individual\n  text: ولا تمتد لتشمل الاستخدام الشخصي أو الاستهلاكي من قبل الأفراد.\nrestricted_uses:\n\
  - summary: Legal capacity required\n  text: مصرح باستخدامه أو الوصول إليه فقط بواسطة أشخاص لهم أهلية التعاقد القانوني\n- summary: Minors may not register\n  text: القاصر غير مخول له الدخول أو التسجيل كمستخدم على التطبيق/المنصة/الموقع الإلكتروني.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: القاصر غير مخول له الدخول أو التسجيل كمستخدم\n"
source_yaml_url: https://artifacts.apis.io/sadq-sa-com/eligibility/sadq-sa-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Sadq Holding Limited's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
