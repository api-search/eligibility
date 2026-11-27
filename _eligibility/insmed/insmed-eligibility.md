---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Site and its content are for general informational purposes and intended strictly for access and use by United States residents who are 18 years of age or older.
  entity_types:
  - text: intended strictly for access and use by United States residents who are 18 years of age or older
    type: individual
  - text: If You are a licensed health care provider (such as a physician, health care facility, or pharmacy), a health insurance provider, or a representative of a licensed health care provider or health insurance provider, You may use the materials in connection with your professional duties
    type: other
  minimum_age:
    text: intended strictly for access and use by United States residents who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: No medical advice or reliance for health decisions
    text: The information provided on this Site should not be relied upon as the basis of any health-care decision.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You are not obligated to register with us in order to access this Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Insmed
provenance_date: '2026-11-09'
provider_name: Insmed
provider_slug: insmed
slug: insmed-eligibility
source_date: '2026-11-09'
source_filename: insmed-eligibility.yml
source_heading: Eligibility
source_page: https://insmed.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Insmed\naid: insmed\nurl: https://insmed.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Site and its content are for general informational purposes and intended strictly for access and use\n    by United States residents who are 18 years of age or older.\nentity_types:\n- type: individual\n  text: intended strictly for access and use by United States residents who are 18 years of age or older\n- type: other\n  text: If You are a licensed health care provider (such as a physician, health care facility, or pharmacy), a health\n    insurance provider, or\
  \ a representative of a licensed health care provider or health insurance provider, You\n    may use the materials in connection with your professional duties\nrestricted_uses:\n- summary: No medical advice or reliance for health decisions\n  text: The information provided on this Site should not be relied upon as the basis of any health-care decision.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You are not obligated to register with us in order to access this Site.\nminimum_age:\n  value: '18'\n  text: intended strictly for access and use by United States residents who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/insmed/eligibility/insmed-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Insmed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Biopharmaceutical
- Pharmaceuticals
- Healthcare
- Rare Disease
- Clinical Trials
- Life Sciences
---
