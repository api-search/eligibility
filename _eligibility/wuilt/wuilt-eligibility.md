---
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - RU
    served: []
    text: بأنك لست مقيمًا في، أو ستستخدم خدمات ويلت في، بلد حظرته حكومة الولايات المتحدة، ولن تكون ويلت قادرًه على دعم الأنشطة أو الأفراد في شبه جزيرة القرم أو كوبا أو إيران أو كوريا الشمالية أو سوريا.
  entity_types:
  - text: يُحظر على الأشخاص ممن هم دون الثالثة عشرة أن ينشئوا حسابًا
    type: individual
  - text: تنطبق هذه الشروط على كل فرد أو مؤسسة
    type: business
  minimum_age:
    text: لكي تبيع من خلال ويلت، يجب أن يكون عمرك 15 عاما فما فوق، أو على الأقل بلغت سن الرشد في البلد الذي ستستخدم فيه موقعنا وخدماتنا.
    value: '15'
  restricted_uses:
  - summary: Illegal or deceptive products
    text: 'لا تستطيع عرض منتج أو خدمة إذا: إذا كانت الخدمة غير قانونية أو مشتبه في قانونيتها، بما في ذلك المنتجات المزيفة أو المسروقة أو الاحتيالية'
  - summary: Weapons products
    text: يتم تصنيعها أو يُنوى استخدامها كأسلحة، بما في ذلك الأسلحة النارية أو الأجهزة والذخيرة
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: لاستخدام خدماتنا، يجب عليك تقديم اسمك القانوني الكامل والصحيح وعنوانك الحالي وبريدك الإلكتروني الصالح
excluded_countries:
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wuilt
provenance_date: '2026-11-10'
provider_name: Wuilt
provider_slug: wuilt
slug: wuilt-eligibility
source_date: '2026-11-10'
source_filename: wuilt-eligibility.yml
source_heading: Eligibility
source_page: https://wuilt.com/ar/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wuilt\naid: wuilt\nurl: https://wuilt.com/ar/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - RU\n  text: بأنك لست مقيمًا في، أو ستستخدم خدمات ويلت في، بلد حظرته حكومة الولايات المتحدة، ولن تكون ويلت قادرًه على\n    دعم الأنشطة أو الأفراد في شبه جزيرة القرم أو كوبا أو إيران أو كوريا الشمالية أو سوريا.\nentity_types:\n- type: individual\n  text: يُحظر على الأشخاص ممن هم دون الثالثة عشرة أن ينشئوا حسابًا\n- type: business\n  text: تنطبق هذه الشروط على كل فرد أو مؤسسة\nrestricted_uses:\n- summary: Illegal or deceptive products\n  text: 'لا تستطيع عرض منتج أو خدمة إذا: إذا كانت\
  \ الخدمة غير قانونية أو مشتبه في قانونيتها، بما في ذلك المنتجات\n    المزيفة أو المسروقة أو الاحتيالية'\n- summary: Weapons products\n  text: يتم تصنيعها أو يُنوى استخدامها كأسلحة، بما في ذلك الأسلحة النارية أو الأجهزة والذخيرة\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: لاستخدام خدماتنا، يجب عليك تقديم اسمك القانوني الكامل والصحيح وعنوانك الحالي وبريدك الإلكتروني الصالح\nminimum_age:\n  value: '15'\n  text: لكي تبيع من خلال ويلت، يجب أن يكون عمرك 15 عاما فما فوق، أو على الأقل بلغت سن الرشد في البلد الذي ستستخدم\n    فيه موقعنا وخدماتنا.\n"
source_yaml_url: https://artifacts.apis.io/wuilt/eligibility/wuilt-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Wuilt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Website Builder
- No-Code
- E-Commerce
- Hosting
- Domains
- Software-as-a-Service
- GraphQL
- Egypt
- Small Business
---
