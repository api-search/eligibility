---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If Buyer is placing an Order for the U.S. Government or in support of a contract with the U.S. Government, Buyer agrees that the Products purchased and licensed are “commercial items”
    type: government
  - text: a public university, college or other not-for-profit institution chartered under the laws of a U.S. state
    type: nonprofit
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Research use only; no clinical or diagnostic claims
    text: No claim, representation, or warranty is made or intended by PacBio that any Product or Service or its performance is suitable or has been validated for clinical or diagnostic use.
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
name: PacBio
provenance_date: '2026-11-10'
provider_name: PacBio
provider_slug: pacbio
slug: pacbio-eligibility
source_date: '2026-11-10'
source_filename: pacbio-eligibility.yml
source_heading: Eligibility
source_page: https://www.pacb.com/legal-and-trademarks/terms-and-conditions-of-sale/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PacBio\naid: pacbio\nurl: https://www.pacb.com/legal-and-trademarks/terms-and-conditions-of-sale/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: If Buyer is placing an Order for the U.S. Government or in support of a contract with the U.S. Government,\n    Buyer agrees that the Products purchased and licensed are “commercial items”\n- type: nonprofit\n  text: a public university, college or other not-for-profit institution chartered under the laws of a U.S. state\nrestricted_uses:\n- summary: Research use only;\
  \ no clinical or diagnostic claims\n  text: No claim, representation, or warranty is made or intended by PacBio that any Product or Service or its performance\n    is suitable or has been validated for clinical or diagnostic use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pacbio/eligibility/pacbio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from PacBio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sequencing
- Genomics
- Biotechnology
- Bioinformatics
---
