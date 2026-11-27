---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Website is not intended for use by children, and those under the age of 13 should not proceed to use the Website.
    value: '13'
  restricted_uses:
  - summary: Export restrictions
    text: the Website and any portions or Content thereof may not be exported or re-exported (a) into any United States embargoed countries, or (b) to anyone on the U.S. Treasury Department’s list of Specially Designated Nationals
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
name: RefleXion Medical
provenance_date: '2026-11-10'
provider_name: RefleXion Medical
provider_slug: reflexion-medical
slug: reflexion-medical-eligibility
source_date: '2026-11-10'
source_filename: reflexion-medical-eligibility.yml
source_heading: Eligibility
source_page: https://reflexion.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RefleXion Medical\naid: reflexion-medical\nurl: https://reflexion.com/legal/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: the Website and any portions or Content thereof may not be exported or re-exported (a) into any United States\n    embargoed countries, or (b) to anyone on the U.S. Treasury Department’s list of Specially Designated Nationals\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Website is not intended\
  \ for use by children, and those under the age of 13 should not proceed to use\n    the Website.\n"
source_yaml_url: https://artifacts.apis.io/reflexion-medical/eligibility/reflexion-medical-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from RefleXion Medical's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medical Devices
- Oncology
- Radiation Oncology
- Radiotherapy
- Medical Imaging
- Cancer Care
---
