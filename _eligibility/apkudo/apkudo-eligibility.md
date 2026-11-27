---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - source: https://www.apkudo.com/legal/acceptable-use-policy
    text: 'You will use the Apkudo Service for your internal business purposes and will not:'
    type: business
  minimum_age:
    text: You must be 18 years of age (or 20 years of age, if you are subject to the laws of Japan) or older to use the Subscription Service.
    value: '18'
  restricted_uses:
  - summary: No storage of Sensitive Data
    text: YOU ACKNOWLEDGE THAT THE SUBSCRIPTION SERVICE HAS NOT BEEN DESIGNED TO STORE SENSITIVE DATA AND ACCORDINGLY YOU AGREE NOT TO USE THE SUBSCRIPTION SERVICE TO STORE SENSITIVE DATA.
  - summary: Not for HIPAA/FISMA-regulated communications
    text: The Subscription Service is not designed to comply with industry-specific regulations such as the Health Insurance Portability and Accountability Act (HIPAA) or the Federal Information Security Management Act (FISMA), so you may not use the Subscription Service where your communications would be subject to such laws.
  - source: https://www.apkudo.com/legal/acceptable-use-policy
    summary: Hate speech and discrimination
    text: Organizations or individuals who promote, encourage, or facilitate hate speech, violence, discrimination, either through their own content or through distribution of user generated content, are prohibited from using the Apkudo Service
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
name: Apkudo
provenance_date: '2026-11-09'
provider_name: Apkudo
provider_slug: apkudo
slug: apkudo-eligibility
source_date: '2026-11-09'
source_filename: apkudo-eligibility.yml
source_heading: Eligibility
source_page: https://www.apkudo.com/legal/customer-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apkudo\naid: apkudo\nurl: https://www.apkudo.com/legal/customer-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\n  sources:\n  - https://www.apkudo.com/legal/acceptable-use-policy\n  - https://www.apkudo.com/legal/customer-terms-of-service\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'You will use the Apkudo Service for your internal business purposes and will not:'\n  source: https://www.apkudo.com/legal/acceptable-use-policy\nrestricted_uses:\n- summary: No storage of Sensitive Data\n  text: YOU ACKNOWLEDGE THAT THE SUBSCRIPTION SERVICE HAS\
  \ NOT BEEN DESIGNED TO STORE SENSITIVE DATA AND ACCORDINGLY\n    YOU AGREE NOT TO USE THE SUBSCRIPTION SERVICE TO STORE SENSITIVE DATA.\n- summary: Not for HIPAA/FISMA-regulated communications\n  text: The Subscription Service is not designed to comply with industry-specific regulations such as the Health\n    Insurance Portability and Accountability Act (HIPAA) or the Federal Information Security Management Act (FISMA),\n    so you may not use the Subscription Service where your communications would be subject to such laws.\n- summary: Hate speech and discrimination\n  text: Organizations or individuals who promote, encourage, or facilitate hate speech, violence, discrimination,\n    either through their own content or through distribution of user generated content, are prohibited from using\n    the Apkudo Service\n  source: https://www.apkudo.com/legal/acceptable-use-policy\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You must be 18 years of age (or 20 years of age, if you are subject to the laws of Japan) or older to use\n    the Subscription Service.\n"
source_yaml_url: https://artifacts.apis.io/apkudo/eligibility/apkudo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Apkudo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Connected Devices
- Mobile Devices
- Circular Economy
- Sustainability
- Supply Chain
- Robotics
- Device Diagnostics
- Trade-In
- IT Asset Disposition
- Telecommunications
---
