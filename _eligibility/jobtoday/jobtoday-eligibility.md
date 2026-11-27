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
  - summary: Unlawful or objectionable content
    text: Users must not post User Content or information that is unlawful, fraudulent, discriminatory, threatening, abusive, libelous, defamatory, obscene or otherwise objectionable
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
name: JobToday
provenance_date: '2026-11-09'
provider_name: JobToday
provider_slug: jobtoday
slug: jobtoday-eligibility
source_date: '2026-11-09'
source_filename: jobtoday-eligibility.yml
source_heading: Eligibility
source_page: https://jobtoday.com/us/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JobToday\naid: jobtoday\nurl: https://jobtoday.com/us/legal/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or objectionable content\n  text: Users must not post User Content or information that is unlawful, fraudulent, discriminatory, threatening,\n    abusive, libelous, defamatory, obscene or otherwise objectionable\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jobtoday/eligibility/jobtoday-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from JobToday's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Job
- Recruiting
- Hiring
- Marketplace
- Employment
- Staffing
- Mobile
---
