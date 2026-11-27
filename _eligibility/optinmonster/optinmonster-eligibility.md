---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services and may not accept this Agreement if ... (b) you are a person barred from receiving the Services under the laws of the United States or other countries including the country in which you are a resident or from which you use the Services.
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to these terms and conditions
    type: business
  minimum_age:
    text: in order to enter into this Agreement, you must be 18 years old or have otherwise reached the legal age of majority in your jurisdiction of residence or possess legal parental or guardian consent
    value: '18'
  restricted_uses:
  - summary: Children 13 and under
    text: This Site and the Services are not designed for or directed at children 13 years of age or younger.
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
name: OptinMonster
provenance_date: '2026-11-10'
provider_name: OptinMonster
provider_slug: optinmonster
slug: optinmonster-eligibility
source_date: '2026-11-10'
source_filename: optinmonster-eligibility.yml
source_heading: Eligibility
source_page: https://optinmonster.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OptinMonster\naid: optinmonster\nurl: https://optinmonster.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services and may not accept this Agreement if ... (b) you are a person barred from receiving\n    the Services under the laws of the United States or other countries including the country in which you are a\n    resident or from which you use the Services.\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity\
  \ to these terms and conditions\nrestricted_uses:\n- summary: Children 13 and under\n  text: This Site and the Services are not designed for or directed at children 13 years of age or younger.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: in order to enter into this Agreement, you must be 18 years old or have otherwise reached the legal age\n    of majority in your jurisdiction of residence or possess legal parental or guardian consent\n"
source_yaml_url: https://artifacts.apis.io/optinmonster/eligibility/optinmonster-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from OptinMonster's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Lead Generation
- Marketing
- Conversion Optimization
- Email Marketing
- Popups
- WordPress
- Webhook
- Software-as-a-Service
- Marketing Automation
---
