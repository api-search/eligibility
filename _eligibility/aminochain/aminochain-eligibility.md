---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may create and use an AminoChain account only if legally permitted to do so.
    type: individual
  - text: If you use the Services on behalf of an employer, research institution, healthcare organization, study sponsor, or other organization, you represent that you are authorized to do so.
    type: business
  minimum_age:
    text: Certain research programs may be approved to enroll minors or individuals who cannot independently provide legally effective consent.
    value: null
  restricted_uses:
  - summary: Professional access limited to assigned role
    text: Professional users may access only information authorized for their assigned role.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Professional users must be authorized by AminoChain and the applicable organization to access restricted professional or research functionality.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AminoChain
provenance_date: '2026-11-09'
provider_name: AminoChain
provider_slug: aminochain
slug: aminochain-eligibility
source_date: '2026-11-09'
source_filename: aminochain-eligibility.yml
source_heading: Eligibility
source_page: https://aminochain.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AminoChain\naid: aminochain\nurl: https://aminochain.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may create and use an AminoChain account only if legally permitted to do so.\n- type: business\n  text: If you use the Services on behalf of an employer, research institution, healthcare organization, study sponsor,\n    or other organization, you represent that you are authorized to do so.\nrestricted_uses:\n- summary: Professional access limited to assigned role\n  text: Professional users may access only information\
  \ authorized for their assigned role.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Professional users must be authorized by AminoChain and the applicable organization to access restricted\n    professional or research functionality.\nminimum_age:\n  value: null\n  text: Certain research programs may be approved to enroll minors or individuals who cannot independently provide\n    legally effective consent.\n"
source_yaml_url: https://artifacts.apis.io/aminochain/eligibility/aminochain-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from AminoChain's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Biomedical Research
- Biobanking
- Specimen Discovery
- Decentralized
- Healthcare
- Consent Management
---
