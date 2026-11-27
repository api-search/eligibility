---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Paid Services (defined below) can only be accessed and used by Customers of at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful, spam or interfering use
    text: use the Services in a way that infringes upon the rights of others or restricts or inhibits anyone’s use or enjoyment of Services, or (vii) or attempt to interfere with the proper working of Services
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
name: Lemni
provenance_date: '2026-11-09'
provider_name: Lemni
provider_slug: lemni
slug: lemni-eligibility
source_date: '2026-11-09'
source_filename: lemni-eligibility.yml
source_heading: Eligibility
source_page: https://www.lemni.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lemni\naid: lemni\nurl: https://www.lemni.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, spam or interfering use\n  text: use the Services in a way that infringes upon the rights of others or restricts or inhibits anyone’s use\n    or enjoyment of Services, or (vii) or attempt to interfere with the proper working of Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Paid Services (defined below) can only be accessed and used by\
  \ Customers of at least eighteen (18) years\n    old.\n"
source_yaml_url: https://artifacts.apis.io/lemni/eligibility/lemni-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Lemni's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Customer Engagement
- Software-as-a-Service
- Automation
- Platform
---
