---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old, or the age of digital consent where you live if that is higher.
    value: '16'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: presents medical, legal or financial claims as professional advice without the qualifications and disclosures the law requires where it is published
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
name: Automated Video App
provenance_date: '2026-11-09'
provider_name: Automated Video App
provider_slug: automatedvideoapp-com
slug: automatedvideoapp-com-eligibility
source_date: '2026-11-09'
source_filename: automatedvideoapp-com-eligibility.yml
source_heading: Eligibility
source_page: https://automatedvideoapp.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Automated Video App\naid: automatedvideoapp-com\nurl: https://automatedvideoapp.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: presents medical, legal or financial claims as professional advice without the qualifications and disclosures\n    the law requires where it is published\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old, or the age of digital consent where you live\
  \ if that is higher.\n"
source_yaml_url: https://artifacts.apis.io/automatedvideoapp-com/eligibility/automatedvideoapp-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Automated Video App's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Artificial Intelligence
- Automation
- Media
---
