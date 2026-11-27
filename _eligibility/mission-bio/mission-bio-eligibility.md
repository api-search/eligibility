---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you contract on behalf of another person or entity, You warrant that You have the authority to bind that person or entity
    type: business
  minimum_age:
    text: You must be at least 18-years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: No PHI upload
    text: uploading, storing, or transferring any PHI using the Services without executing any necessary agreements is strictly prohibited under this Agreement.
  - summary: Research Use Only instruments
    text: Mission Bio is engaged in the manufacture and supply of certain Instruments manufactured, labeled and marketed for Research Use Only (“RUO”)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide your name, country, company/institution, a valid email address, and password to create one or more user accounts
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mission Bio
provenance_date: '2026-11-10'
provider_name: Mission Bio
provider_slug: mission-bio
slug: mission-bio-eligibility
source_date: '2026-11-10'
source_filename: mission-bio-eligibility.yml
source_heading: Eligibility
source_page: https://www.missionbio.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mission Bio\naid: mission-bio\nurl: https://www.missionbio.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you contract on behalf of another person or entity, You warrant that You have the authority to bind that\n    person or entity\nrestricted_uses:\n- summary: No PHI upload\n  text: uploading, storing, or transferring any PHI using the Services without executing any necessary agreements\n    is strictly prohibited under this Agreement.\n- summary: Research Use Only instruments\n  text: Mission Bio is engaged\
  \ in the manufacture and supply of certain Instruments manufactured, labeled and marketed\n    for Research Use Only (“RUO”)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide your name, country, company/institution, a valid email address, and password to create\n    one or more user accounts\nminimum_age:\n  value: '18'\n  text: You must be at least 18-years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/mission-bio/eligibility/mission-bio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Mission Bio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Genomics
- Single Cell
- Multiomics
- Bioinformatics
- Oncology
- Precision Medicine
- Python Libraries
- Scientific Computing
---
