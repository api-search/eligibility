---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - SA
    text: خدمات ديلي ميلز متاحة داخل عدة مدن في المملكة العربية السعودية تشمل الرياض، جدة، المنطقة الشرقية (الدمام والخبر والظهران).
  entity_types:
  - text: عند استخدام ديلي ميلز، فإن العميل يتعهد بصحة كافة البيانات الشخصية المقدمة
    type: individual
  - text: بعض العروض لا تشمل العملاء التابعين لباقات البيزنس.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: commercial or advertising use
    text: يلتزم بعدم استخدام خدمات ديلي ميلز لأي أغراض تجارية أو إعلانية دون الحصول على موافقة مكتوبة من القائمين على التطبيق.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: يجب ملئ استمارة التسجيل بشكل صحيح وتثبيت الاسم والعنوان ورقم الهاتف والبريد الإلكتروني.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DailyMealz
provenance_date: '2026-11-09'
provider_name: DailyMealz
provider_slug: dailymealz
slug: dailymealz-eligibility
source_date: '2026-11-09'
source_filename: dailymealz-eligibility.yml
source_heading: Eligibility
source_page: https://dailymealz.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DailyMealz\naid: dailymealz\nurl: https://dailymealz.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SA\n  excluded: []\n  text: خدمات ديلي ميلز متاحة داخل عدة مدن في المملكة العربية السعودية تشمل الرياض، جدة، المنطقة الشرقية (الدمام\n    والخبر والظهران).\nentity_types:\n- type: individual\n  text: عند استخدام ديلي ميلز، فإن العميل يتعهد بصحة كافة البيانات الشخصية المقدمة\n- type: business\n  text: بعض العروض لا تشمل العملاء التابعين لباقات البيزنس.\nrestricted_uses:\n- summary: commercial or advertising use\n  text: يلتزم بعدم استخدام خدمات ديلي ميلز لأي أغراض تجارية أو إعلانية\
  \ دون الحصول على موافقة مكتوبة من القائمين\n    على التطبيق.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: يجب ملئ استمارة التسجيل بشكل صحيح وتثبيت الاسم والعنوان ورقم الهاتف والبريد الإلكتروني.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dailymealz/eligibility/dailymealz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from DailyMealz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food Delivery
- Meal Subscription
- Food and Beverage
- Saudi Arabia
- Subscription
- Food Tech
---
