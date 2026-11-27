---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: The Marketplace is currently available to Canadian Users only.
  entity_types:
  - text: By downloading, accessing, or using the Marketplace, you represent and warrant that (i) you are in Canada; (ii) you are the legal age of majority in your province or territory of residence
    type: individual
  minimum_age:
    text: you are the legal age of majority in your province or territory of residence
    value: age of majority
  restricted_uses:
  - summary: No export-controlled or unlawful data storage
    text: (d) use the Marketplace or any App to store or transfer any restricted or unlawful data, including, without limitation, any Marketplace data that is controlled for export under export control laws and re-export control laws and regulations
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
name: WELL Health Technologies
provenance_date: '2026-11-10'
provider_name: WELL Health Technologies
provider_slug: well-health
slug: well-health-eligibility
source_date: '2026-11-10'
source_filename: well-health-eligibility.yml
source_heading: Eligibility
source_page: https://apps.health/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WELL Health Technologies\naid: well-health\nurl: https://apps.health/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: The Marketplace is currently available to Canadian Users only.\nentity_types:\n- type: individual\n  text: By downloading, accessing, or using the Marketplace, you represent and warrant that (i) you are in Canada;\n    (ii) you are the legal age of majority in your province or territory of residence\nrestricted_uses:\n- summary: No export-controlled or unlawful data storage\n  text: (d) use the Marketplace or any App to store or transfer any restricted\
  \ or unlawful data, including, without\n    limitation, any Marketplace data that is controlled for export under export control laws and re-export control\n    laws and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you are the legal age of majority in your province or territory of residence\n"
source_yaml_url: https://artifacts.apis.io/well-health/eligibility/well-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from WELL Health Technologies's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Canada
- Electronic Health Records
- FHIR
- HL7
- Interoperability
- Digital Health
- Telehealth
- ePharma
- Clinics
---
