---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Be located within the Boston Metro service area.
  entity_types:
  - text: You agree, on behalf of yourself and the institution/company or other legal entity that you represent, to be legally bound by these Terms when you access or use the Site.
    type: business
  minimum_age:
    text: BY ACCESSING OR USING THE SITE, YOU ACKNOWLEDGE THAT YOU ARE AT LEAST THE AGE OF MAJORITY IN YOUR JURISDICTION AND ACCEPT THE TERMS SET FORTH HEREIN.
    value: age of majority
  restricted_uses:
  - summary: Violating applicable law
    text: In any way that violates any applicable federal, state, local or international law or regulation;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require you to provide information that may be used to confirm your identity and help ensure the security of your account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Reservoir
provenance_date: '2026-11-10'
provider_name: Reservoir
provider_slug: reservoirhome-com
slug: reservoirhome-com-eligibility
source_date: '2026-11-10'
source_filename: reservoirhome-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.reservoirhome.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reservoir\naid: reservoirhome-com\nurl: https://www.reservoirhome.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Be located within the Boston Metro service area.\nentity_types:\n- type: business\n  text: You agree, on behalf of yourself and the institution/company or other legal entity that you represent, to\n    be legally bound by these Terms when you access or use the Site.\nrestricted_uses:\n- summary: Violating applicable law\n  text: In any way that violates any applicable federal, state, local or international law or regulation;\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: We may require you to provide information that may be used to confirm your identity and help ensure the\n    security of your account.\nminimum_age:\n  value: age of majority\n  text: BY ACCESSING OR USING THE SITE, YOU ACKNOWLEDGE THAT YOU ARE AT LEAST THE AGE OF MAJORITY IN YOUR JURISDICTION\n    AND ACCEPT THE TERMS SET FORTH HEREIN.\n"
source_yaml_url: https://artifacts.apis.io/reservoirhome-com/eligibility/reservoirhome-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Reservoir's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Homes
- Electrification
- Clean Energy
- Water
---
