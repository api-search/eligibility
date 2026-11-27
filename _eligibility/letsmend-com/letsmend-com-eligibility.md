---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be at least eighteen (18) years of age and a resident of the United States of America to use the Properties.
  entity_types:
  - text: You agree that you will only use the Properties for your own personal use.
    type: individual
  minimum_age:
    text: You must be at least eighteen (18) years of age and a resident of the United States of America to use the Properties.
    value: '18'
  restricted_uses:
  - summary: Impersonation and multiple accounts
    text: Register for more than one Mend account or register a Mend account on behalf of an individual other than yourself;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We do not verify the accuracy of this information, nor do we confirm the identity of any users or third parties.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mend
provenance_date: '2026-11-09'
provider_name: Mend
provider_slug: letsmend-com
slug: letsmend-com-eligibility
source_date: '2026-11-09'
source_filename: letsmend-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.letsmend.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mend\naid: letsmend-com\nurl: https://www.letsmend.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be at least eighteen (18) years of age and a resident of the United States of America to use the\n    Properties.\nentity_types:\n- type: individual\n  text: You agree that you will only use the Properties for your own personal use.\nrestricted_uses:\n- summary: Impersonation and multiple accounts\n  text: Register for more than one Mend account or register a Mend account on behalf of an individual other than\n    yourself;\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: We do not verify the accuracy of this information, nor do we confirm the identity of any users or third\n    parties.\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age and a resident of the United States of America to use the\n    Properties.\n"
source_yaml_url: https://artifacts.apis.io/letsmend-com/eligibility/letsmend-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Mend's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Breakup
- Mental Health
- Community
---
