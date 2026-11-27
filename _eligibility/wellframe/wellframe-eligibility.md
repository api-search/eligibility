---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Content and Services are based in the United States and provided for access and use only by persons located in the United States.
  entity_types:
  - text: You (or your caregiver if you elect him or her into receiving the Services)
    type: individual
  minimum_age:
    text: children under the age of 13 are prohibited from using our Software. A parent, guardian, or personal representative may use the Software on behalf of a child under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Not for life-critical situations
    text: THE SOFTWARE IS NOT INTENDED FOR USE IN ANY SITUATION IN WHICH THE FAILURE OF THE SOFTWARE COULD LEAD TO DEATH OR BODILY INJURY OF ANY TYPE.
  - summary: No medical advice reliance
    text: THE SERVICES ARE NOT A SUBSTITUTE FOR AND IS NOT INTENDED TO PROVIDE PROFESSIONAL MEDICAL ADVICE, DIAGNOSIS, OR TREATMENT.
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
name: Wellframe
provenance_date: '2026-11-10'
provider_name: Wellframe
provider_slug: wellframe
slug: wellframe-eligibility
source_date: '2026-11-10'
source_filename: wellframe-eligibility.yml
source_heading: Eligibility
source_page: https://www.wellframe.com/eula/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wellframe\naid: wellframe\nurl: https://www.wellframe.com/eula/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Content and Services are based in the United States and provided for access and use only by persons\n    located in the United States.\nentity_types:\n- type: individual\n  text: You (or your caregiver if you elect him or her into receiving the Services)\nrestricted_uses:\n- summary: Not for life-critical situations\n  text: THE SOFTWARE IS NOT INTENDED FOR USE IN ANY SITUATION IN WHICH THE FAILURE OF THE SOFTWARE COULD LEAD TO\n    DEATH OR BODILY INJURY OF ANY\
  \ TYPE.\n- summary: No medical advice reliance\n  text: THE SERVICES ARE NOT A SUBSTITUTE FOR AND IS NOT INTENDED TO PROVIDE PROFESSIONAL MEDICAL ADVICE, DIAGNOSIS,\n    OR TREATMENT.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: children under the age of 13 are prohibited from using our Software. A parent, guardian, or personal representative\n    may use the Software on behalf of a child under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/wellframe/eligibility/wellframe-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Wellframe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Care Management
- Member Engagement
- Health Plans
- Payers
---
