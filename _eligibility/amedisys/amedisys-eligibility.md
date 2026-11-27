---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our Online Services are intended for a United States ("U.S.") audience.
  entity_types:
  - text: You represent and warrant that you are at least 13 years of age, and that, if you are between 13 and the age of majority in your state and otherwise not emancipated, a parent and/or guardian agrees to these Terms on your behalf
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Export controls and sanctioned parties
    text: may not be exported, re-exported or made available in any manner (a) into any U.S. embargoed countries or (b) to anyone on the U.S. Treasury Department's list of Specially Designated Nationals
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
name: Amedisys
provenance_date: '2026-11-09'
provider_name: Amedisys
provider_slug: amedisys
slug: amedisys-eligibility
source_date: '2026-11-09'
source_filename: amedisys-eligibility.yml
source_heading: Eligibility
source_page: https://www.amedisys.com/terms-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amedisys\naid: amedisys\nurl: https://www.amedisys.com/terms-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our Online Services are intended for a United States (\"U.S.\") audience.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 13 years of age, and that, if you are between 13 and the\n    age of majority in your state and otherwise not emancipated, a parent and/or guardian agrees to these Terms\n    on your behalf\nrestricted_uses:\n- summary: Export controls and sanctioned parties\n  text: may not be exported, re-exported\
  \ or made available in any manner (a) into any U.S. embargoed countries or\n    (b) to anyone on the U.S. Treasury Department's list of Specially Designated Nationals\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You represent and warrant that you are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/amedisys/eligibility/amedisys-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Amedisys's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Home Care
- Hospice
- Palliative Care
- Health Systems
- Care Delivery
- Post-Acute Care
- Hospital at Home
---
