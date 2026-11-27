---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the service if the law forbids us to provide it to you, including if you are in a country, or on a list of persons, under trade sanctions that apply to us.
  entity_types:
  - text: If you use the service for a company or another organisation, you accept these terms for it and confirm you are allowed to.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age at which you can enter a binding contract where you live if that is higher.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Give accurate information, keep it up to date, and use an email address you can read
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: curlshot-com
provenance_date: '2026-11-09'
provider_name: curlshot-com
provider_slug: curlshot-com
slug: curlshot-com-eligibility
source_date: '2026-11-09'
source_filename: curlshot-com-eligibility.yml
source_heading: Eligibility
source_page: https://curlshot.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: curlshot-com\naid: curlshot-com\nurl: https://curlshot.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the service if the law forbids us to provide it to you, including if you are in a country,\n    or on a list of persons, under trade sanctions that apply to us.\nentity_types:\n- type: business\n  text: If you use the service for a company or another organisation, you accept these terms for it and confirm\n    you are allowed to.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Give accurate information,\
  \ keep it up to date, and use an email address you can read\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age at which you can enter a binding contract where you live if\n    that is higher.\n"
source_yaml_url: https://artifacts.apis.io/curlshot-com/eligibility/curlshot-com-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from curlshot-com's own page on 2026-11-09.
synthetic: false
tags:
- Screenshots
- Web
- Automation
- Developer Tools
---
