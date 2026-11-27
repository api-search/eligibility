---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: In order to use the services, minors must always obtain prior consent from their parents, guardians or legal representatives
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In general, the provision of the Services does not require prior subscription or registration of Users. However, COUNCILBOX TECHNOLOGY, S.L. conditions the use of some of the services to the prior completion of the corresponding User registration.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Councilbox
provenance_date: '2026-11-09'
provider_name: Councilbox
provider_slug: councilbox
slug: councilbox-eligibility
source_date: '2026-11-09'
source_filename: councilbox-eligibility.yml
source_heading: Eligibility
source_page: https://www.councilbox.com/en/legal-notice-2/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Councilbox\naid: councilbox\nurl: https://www.councilbox.com/en/legal-notice-2/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In general, the provision of the Services does not require prior subscription or registration of Users.\n    However, COUNCILBOX TECHNOLOGY, S.L. conditions the use of some of the services to the prior completion of the\n    corresponding User registration.\nminimum_age:\n  value: null\n  text: In order to use the services, minors must\
  \ always obtain prior consent from their parents, guardians or legal\n    representatives\n"
source_yaml_url: https://artifacts.apis.io/councilbox/eligibility/councilbox-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from Councilbox's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Civic Tech
- API Platform
- Community Engagement
- Cloud Services
---
