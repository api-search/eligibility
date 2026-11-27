---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the individual is accepting this MSA on behalf of a company or other legal entity, it represents and warrants that it has the full authority to bind the Licensee to this MSA.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned persons
    text: Licensee shall not use the Services in connection with, or for the benefit of, provide Authorized User credentials to, or otherwise permit access to the Services by, any country, government, organization, entity, or person that is restricted by the HM Treasury Sanctions List
  - summary: Deliverables limited to illicit activity investigation
    text: Deliverables may only be used by Licensee in connection with its investigation of illicit activities.
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
name: Chainalysis
provenance_date: '2026-11-09'
provider_name: Chainalysis
provider_slug: chainalysis
slug: chainalysis-eligibility
source_date: '2026-11-09'
source_filename: chainalysis-eligibility.yml
source_heading: Eligibility
source_page: https://www.chainalysis.com/msa1023/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chainalysis\naid: chainalysis\nurl: https://www.chainalysis.com/msa1023/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the individual is accepting this MSA on behalf of a company or other legal entity, it represents and\n    warrants that it has the full authority to bind the Licensee to this MSA.\nrestricted_uses:\n- summary: Sanctioned persons\n  text: Licensee shall not use the Services in connection with, or for the benefit of, provide Authorized User credentials\n    to, or otherwise permit access to the Services by, any country,\
  \ government, organization, entity, or person\n    that is restricted by the HM Treasury Sanctions List\n- summary: Deliverables limited to illicit activity investigation\n  text: Deliverables may only be used by Licensee in connection with its investigation of illicit activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chainalysis/eligibility/chainalysis-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Chainalysis's own page on 2026-11-09.
synthetic: false
tags:
- Compliance
- AML
- Transaction Monitoring
- Sanctions
- Investigations
- Blockchain Analytics
- Risk Management
- Cryptocurrency
---
