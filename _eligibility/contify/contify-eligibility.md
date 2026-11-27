---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: where the User is a body corporate or business partnership, to its duly authorized employees or its Secondary Users
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: The User shall not access the website in a way that will not confirm to applicable laws and regulations.
  - summary: No prejudicial use of data
    text: Data accessed from the website shall not be used in any manner likely to be directly prejudicial to the reputation and good standing of Athena or publishers.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Website requires registration as a User by creating an Account in order to access information or data on the Website.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Contify
provenance_date: '2026-11-09'
provider_name: Contify
provider_slug: contify
slug: contify-eligibility
source_date: '2026-11-09'
source_filename: contify-eligibility.yml
source_heading: Eligibility
source_page: https://www.contify.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Contify\naid: contify\nurl: https://www.contify.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: where the User is a body corporate or business partnership, to its duly authorized employees or its Secondary\n    Users\nrestricted_uses:\n- summary: Lawful use only\n  text: The User shall not access the website in a way that will not confirm to applicable laws and regulations.\n- summary: No prejudicial use of data\n  text: Data accessed from the website shall not be used in any manner likely to be directly prejudicial\
  \ to the\n    reputation and good standing of Athena or publishers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Website requires registration as a User by creating an Account in order to access information or data\n    on the Website.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/contify/eligibility/contify-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Contify's own page on 2026-11-09.
synthetic: false
tags:
- Competitive Intelligence
- Market Intelligence
- Business News
- News
- Artificial Intelligence
- Data
- Strategies
---
