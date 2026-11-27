---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Use of the Site is prohibited for anyone under the age of 13. If you are between 13 and 18 years of age, you must secure authorization from your parents or legal guardian before using the Site.
    value: '13'
  restricted_uses:
  - summary: Users under 13 prohibited
    text: Use of the Site is prohibited for anyone under the age of 13.
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
name: APA
provenance_date: '2026-11-09'
provider_name: APA
provider_slug: apa
slug: apa-eligibility
source_date: '2026-11-09'
source_filename: apa-eligibility.yml
source_heading: Eligibility
source_page: https://apacorp.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: APA\naid: apa\nurl: https://apacorp.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Users under 13 prohibited\n  text: Use of the Site is prohibited for anyone under the age of 13.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Use of the Site is prohibited for anyone under the age of 13. If you are between 13 and 18 years of age,\n    you must secure authorization from your parents or legal guardian before using the Site.\n"
source_yaml_url: https://artifacts.apis.io/apa/eligibility/apa-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from APA's own page on 2026-11-09.
synthetic: false
tags:
- Oil and Gas
- Energy
- Exploration
- Production
- WordPress
- REST
- Newsroom
- Investor Relations
- Energy Production
---
