---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you” also includes a company or other entity/organization on whose behalf you are accepting these Terms, to the extent applicable.
    type: business
  minimum_age:
    text: in any case, at least 16 years of age.
    value: '16'
  restricted_uses:
  - summary: Sanctioned persons or restricted jurisdictions
    text: You may not use the Services and may not accept these Terms if you are a person barred from using the Services whether under the laws of the country in which you are resident or from which you access the Services, or due to sanctions imposed on you.
  - summary: Military or export-controlled uses
    text: Customer Data does not support the design or development of a military or intelligence item and is not subject to any export controls under any applicable law
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
name: Certora
provenance_date: '2026-11-09'
provider_name: Certora
provider_slug: certora
slug: certora-eligibility
source_date: '2026-11-09'
source_filename: certora-eligibility.yml
source_heading: Eligibility
source_page: https://www.certora.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Certora\naid: certora\nurl: https://www.certora.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you” also includes a company or other entity/organization on whose behalf you are accepting these Terms,\n    to the extent applicable.\nrestricted_uses:\n- summary: Sanctioned persons or restricted jurisdictions\n  text: You may not use the Services and may not accept these Terms if you are a person barred from using the Services\n    whether under the laws of the country in which you are resident or from which you access the Services,\
  \ or due\n    to sanctions imposed on you.\n- summary: Military or export-controlled uses\n  text: Customer Data does not support the design or development of a military or intelligence item and is not subject\n    to any export controls under any applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: in any case, at least 16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/certora/eligibility/certora-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Certora's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Formal Verification
- Smart Contracts
- Blockchain
- Developer Tools
- CLI
- Web3
---
