---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Website medical information is not medical advice
    text: 这类信息只作为知识提供，不应被视为诊疗指导或建议，不能取代向医生或其他医疗专业人士进行咨询
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
name: Berry Genomics
provenance_date: '2026-11-09'
provider_name: Berry Genomics
provider_slug: berrygenomics
slug: berrygenomics-eligibility
source_date: '2026-11-09'
source_filename: berrygenomics-eligibility.yml
source_heading: Eligibility
source_page: https://www.berrygenomics.com/cmscontent/327.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Berry Genomics\naid: berrygenomics\nurl: https://www.berrygenomics.com/cmscontent/327.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Website medical information is not medical advice\n  text: 这类信息只作为知识提供，不应被视为诊疗指导或建议，不能取代向医生或其他医疗专业人士进行咨询\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/berrygenomics/eligibility/berrygenomics-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Berry Genomics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Genomics
- Genetic Testing
- Healthcare
- Biotechnology
- Diagnostics
- Life Sciences
---
