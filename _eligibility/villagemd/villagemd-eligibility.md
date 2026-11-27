---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Digital Service for use only by persons located in the United States of America.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You may only use the Digital Service for lawful purposes and in accordance with these Terms of Use.
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
name: VillageMD
provenance_date: '2026-11-10'
provider_name: VillageMD
provider_slug: villagemd
slug: villagemd-eligibility
source_date: '2026-11-10'
source_filename: villagemd-eligibility.yml
source_heading: Eligibility
source_page: https://www.villagemedical.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VillageMD\naid: villagemd\nurl: https://www.villagemedical.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Digital Service for use only by persons located in the United States of America.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You may only use the Digital Service for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/villagemd/eligibility/villagemd-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from VillageMD's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Primary Care
- Value-Based Care
- Medical Practices
- Urgent Care
- Telehealth
- Patient Care
- Clinics
---
