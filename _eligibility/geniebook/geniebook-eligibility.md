---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The App is available to all territories as specified on the App Store.
  minimum_age:
    text: If you are a minor, under the age of 18 years and over the age of 13 years, you may use the Apps under the supervision of a parent or legal guardian who agrees to be bound by these Terms.
    value: '13'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: Use the Website or any material or Content for any purpose that is unlawful or prohibited by these Terms
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To create an account, you need to enter Your phone number for verification purposes and a password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Geniebook
provenance_date: '2026-11-09'
provider_name: Geniebook
provider_slug: geniebook
slug: geniebook-eligibility
source_date: '2026-11-09'
source_filename: geniebook-eligibility.yml
source_heading: Eligibility
source_page: https://app.geniebook.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Geniebook\naid: geniebook\nurl: https://app.geniebook.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The App is available to all territories as specified on the App Store.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: Use the Website or any material or Content for any purpose that is unlawful or prohibited by these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To create an account, you need to enter Your phone number for verification purposes and a password.\nminimum_age:\n  value: '13'\n  text:\
  \ If you are a minor, under the age of 18 years and over the age of 13 years, you may use the Apps under the\n    supervision of a parent or legal guardian who agrees to be bound by these Terms.\n"
source_yaml_url: https://artifacts.apis.io/geniebook/eligibility/geniebook-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Geniebook's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- E-Learning
- Artificial Intelligence
- Tutoring
- Singapore
- Consumer
---
