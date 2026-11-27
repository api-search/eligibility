---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the Customer is a natural person, the Customer can be the same person as the User depending on the circumstances.
    type: individual
  - text: CENOS license is used for the Customer’s business.
    type: business
  - text: a person who is affiliated with a university or a research organization, or is a hobbyist
    type: nonprofit
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions and export bans
    text: You and Customer acknowledge and agree that in accordance with the applicable legislation you and Customer may be forbidden to use CENOS Software in relation with specific governments, individuals, entities and/or territories
  - summary: Unlawful use
    text: You and Customer have no right to use CENOS Software for any purposes forbidden by the applicable law.
  - summary: Sale of software or license key
    text: Carrying out a sale of CENOS Software or the license key giving access to CENOS Software without an explicit notarized written consent of authorized representatives of CENOS;
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Non-Commercial Users can use CENOS Application and CENOS Additional Product based on CENOS non-commercial license issued for a one-year period in return to submission of (a) a document that confirms the Non-Commercial User’s affiliation with the university or the research organization or hobbyist organization
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cenos
provenance_date: '2026-11-09'
provider_name: Cenos
provider_slug: cenos
slug: cenos-eligibility
source_date: '2026-11-09'
source_filename: cenos-eligibility.yml
source_heading: Eligibility
source_page: https://cenos-platform.com/about/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cenos\naid: cenos\nurl: https://cenos-platform.com/about/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If the Customer is a natural person, the Customer can be the same person as the User depending on the circumstances.\n- type: business\n  text: CENOS license is used for the Customer’s business.\n- type: nonprofit\n  text: a person who is affiliated with a university or a research organization, or is a hobbyist\nrestricted_uses:\n- summary: Sanctions and export bans\n  text: You and Customer\
  \ acknowledge and agree that in accordance with the applicable legislation you and Customer\n    may be forbidden to use CENOS Software in relation with specific governments, individuals, entities and/or territories\n- summary: Unlawful use\n  text: You and Customer have no right to use CENOS Software for any purposes forbidden by the applicable law.\n- summary: Sale of software or license key\n  text: Carrying out a sale of CENOS Software or the license key giving access to CENOS Software without an explicit\n    notarized written consent of authorized representatives of CENOS;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Non-Commercial Users can use CENOS Application and CENOS Additional Product based on CENOS non-commercial\n    license issued for a one-year period in return to submission of (a) a document that confirms the Non-Commercial\n    User’s affiliation with the university or the research organization or hobbyist organization\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cenos/eligibility/cenos-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 7 quoted statements, read from Cenos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Simulation
- Engineering
- Electromagnetics
- Induction Heating
- Radio Frequency
- Wireless Charging
- CAE
- FEM
---
