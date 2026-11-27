---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use our Services and may not accept the Terms if you are barred from receiving the Services under the laws of the United States or other countries, including the country in which you are resident or from which you use the Services.
  entity_types:
  - text: If using our Services on behalf of an organization, (a) “you” and “your” will refer to that organization, (b) you agree to these Terms on behalf of that organization and you represent that you have the authority to do so
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions and restricted lists
    text: your end users do not use the Services in violation of any export restriction or embargo by the United States, and (b) you do not provide access to the Services to persons or entities on any restricted lists.
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
name: Medallion
provenance_date: '2026-11-10'
provider_name: Medallion
provider_slug: medallion
slug: medallion-eligibility
source_date: '2026-11-10'
source_filename: medallion-eligibility.yml
source_heading: Eligibility
source_page: https://www.medallion.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Medallion\naid: medallion\nurl: https://www.medallion.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use our Services and may not accept the Terms if you are barred from receiving the Services\n    under the laws of the United States or other countries, including the country in which you are resident or from\n    which you use the Services.\nentity_types:\n- type: business\n  text: If using our Services on behalf of an organization, (a) “you” and “your” will refer to that organization,\n    (b) you agree to these Terms on behalf of that organization and you\
  \ represent that you have the authority to\n    do so\nrestricted_uses:\n- summary: Export restrictions and restricted lists\n  text: your end users do not use the Services in violation of any export restriction or embargo by the United States,\n    and (b) you do not provide access to the Services to persons or entities on any restricted lists.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/medallion/eligibility/medallion-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Medallion's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Healthcare
- Credentialing
- Provider Data
- Licensing
- Payer Enrollment
- Compliance
---
