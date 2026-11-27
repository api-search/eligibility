---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Heartflow Analysis ... is commercially available in the United States. Specific functionalities are also available in European Union, UK, Japan, Canada, and other select regions.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Accessing certain areas of the Web Site and using certain functions or features of the Web Site may require you to register and provide personal information such as name, physical address, email address and phone number.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HeartFlow
provenance_date: '2026-11-09'
provider_name: HeartFlow
provider_slug: heartflow
slug: heartflow-eligibility
source_date: '2026-11-09'
source_filename: heartflow-eligibility.yml
source_heading: Eligibility
source_page: https://www.heartflow.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HeartFlow\naid: heartflow\nurl: https://www.heartflow.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Heartflow Analysis ... is commercially available in the United States. Specific functionalities are\n    also available in European Union, UK, Japan, Canada, and other select regions.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Accessing certain areas of the Web Site and using certain functions or features of the Web Site may require\n    you to register and provide personal information\
  \ such as name, physical address, email address and phone number.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/heartflow/eligibility/heartflow-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from HeartFlow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Imaging
- Artificial Intelligence
- Cardiology
- Diagnostics
- Medical Devices
- Radiology
- Clinical Decision Support
- Machine Learning
---
