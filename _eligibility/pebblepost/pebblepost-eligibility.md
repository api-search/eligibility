---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Company makes no claims that the Site and the Site Content are appropriate for access or use outside of the United States of America.
  entity_types:
  - text: The Site is available to users who are at least 18-years-old
    type: individual
  - text: use the Site solely for your internal business purposes in accordance with these Terms.
    type: business
  minimum_age:
    text: The Site is available to users who are at least 18-years-old
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: You may not use the Site for any purpose that is unlawful or prohibited by this Agreement
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: who have properly registered by completing and submitting the Site’s registration form
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PebblePost
provenance_date: '2026-11-10'
provider_name: PebblePost
provider_slug: pebblepost
slug: pebblepost-eligibility
source_date: '2026-11-10'
source_filename: pebblepost-eligibility.yml
source_heading: Eligibility
source_page: http://www.verastance.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PebblePost\naid: pebblepost\nurl: http://www.verastance.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Company makes no claims that the Site and the Site Content are appropriate for access or use outside\n    of the United States of America.\nentity_types:\n- type: individual\n  text: The Site is available to users who are at least 18-years-old\n- type: business\n  text: use the Site solely for your internal business purposes in accordance with these Terms.\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: You may not use the Site for any purpose\
  \ that is unlawful or prohibited by this Agreement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: who have properly registered by completing and submitting the Site’s registration form\nminimum_age:\n  value: '18'\n  text: The Site is available to users who are at least 18-years-old\n"
source_yaml_url: https://artifacts.apis.io/pebblepost/eligibility/pebblepost-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from PebblePost's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Advertising
- Direct Mail
- Connected TV
- Retail
- Commerce
- Identity
- Analytics
---
