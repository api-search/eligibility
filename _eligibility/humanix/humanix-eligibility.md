---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you and the legal entity on whose behalf you access the Site
    type: business
  minimum_age:
    text: You must be 13 years or older to submit data through the Site.
    value: '13'
  restricted_uses:
  - summary: No unapproved advertising or solicitation
    text: You shall not publish any advertising or solicitation for goods or services through the Site without the express approval of Humanix.
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
name: Humanix
provenance_date: '2026-11-09'
provider_name: Humanix
provider_slug: humanix
slug: humanix-eligibility
source_date: '2026-11-09'
source_filename: humanix-eligibility.yml
source_heading: Eligibility
source_page: https://www.humanix.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Humanix\naid: humanix\nurl: https://www.humanix.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you and the legal entity on whose behalf you access the Site\nrestricted_uses:\n- summary: No unapproved advertising or solicitation\n  text: You shall not publish any advertising or solicitation for goods or services through the Site without the\n    express approval of Humanix.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years or older to\
  \ submit data through the Site.\n"
source_yaml_url: https://artifacts.apis.io/humanix/eligibility/humanix-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Humanix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Artificial Intelligence
- User Behavior Analytics
- Social-Engineering
---
