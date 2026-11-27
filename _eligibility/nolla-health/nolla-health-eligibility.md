---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Platform is limited exclusively to users located in states within the United States where the Platform is available. Services are not available to users located outside the United States.
  minimum_age:
    text: you represent and warrant that you are at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: No automated access or scraping
    text: Except for ADA accessibility purposes, you may not use any scraper, crawler, spider, robot, or other automated means of any kind to access or copy data on the Platform
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
name: Nolla Health
provenance_date: '2026-11-10'
provider_name: Nolla Health
provider_slug: nolla-health
slug: nolla-health-eligibility
source_date: '2026-11-10'
source_filename: nolla-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.nollahealth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nolla Health\naid: nolla-health\nurl: https://www.nollahealth.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Platform is limited exclusively to users located in states within the United States\n    where the Platform is available. Services are not available to users located outside the United States.\nentity_types: []\nrestricted_uses:\n- summary: No automated access or scraping\n  text: Except for ADA accessibility purposes, you may not use any scraper, crawler, spider, robot, or other automated\n    means of any kind to access or copy data\
  \ on the Platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you represent and warrant that you are at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/nolla-health/eligibility/nolla-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Nolla Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Dermatology
- Digital Health
- Artificial Intelligence
- Consumer Health
---
