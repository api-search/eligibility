---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: We may restrict or prohibit use of the Services from certain U.S. states or foreign jurisdictions including, without limitation, Cuba, Iran, North Korea, Syria, or any other territory that is subject to a U.S. government embargo
  entity_types:
  - text: If you are registering to use the Services on behalf of a legal entity, you represent and warrant that (i) such legal entity is duly organized and validly existing
    type: business
  minimum_age:
    text: (a) are over the age of eighteen and of legal age to form a binding contract
    value: '18'
  restricted_uses:
  - summary: Illegal activities and fraud
    text: Use our Services to pay for, support, or otherwise engage in any illegal gambling activities; fraud; money-laundering; terrorist activities; or other illegal activities;
  - summary: Purchase to external address
    text: Use our Services to purchase and send bitcoin to an address not controlled (or owned) by yourself;
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Registered members from all regions and jurisdictions are required to verify their identities, prior to being authorized to perform any transaction involving fiat currency.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LibertyX
provenance_date: '2026-11-09'
provider_name: LibertyX
provider_slug: libertyx
slug: libertyx-eligibility
source_date: '2026-11-09'
source_filename: libertyx-eligibility.yml
source_heading: Eligibility
source_page: https://libertyx.com/docs/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LibertyX\naid: libertyx\nurl: https://libertyx.com/docs/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: We may restrict or prohibit use of the Services from certain U.S. states or foreign jurisdictions including,\n    without limitation, Cuba, Iran, North Korea, Syria, or any other territory that is subject to a U.S. government\n    embargo\nentity_types:\n- type: business\n  text: If you are registering to use the Services on behalf of a legal entity, you represent and warrant that (i)\n    such legal entity is duly organized and validly existing\n\
  restricted_uses:\n- summary: Illegal activities and fraud\n  text: Use our Services to pay for, support, or otherwise engage in any illegal gambling activities; fraud; money-laundering;\n    terrorist activities; or other illegal activities;\n- summary: Purchase to external address\n  text: Use our Services to purchase and send bitcoin to an address not controlled (or owned) by yourself;\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Registered members from all regions and jurisdictions are required to verify their identities, prior to\n    being authorized to perform any transaction involving fiat currency.\nminimum_age:\n  value: '18'\n  text: (a) are over the age of eighteen and of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/libertyx/eligibility/libertyx-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from LibertyX's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
