---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that You are not a citizen of, or otherwise located within, an embargoed nation, and that You are not otherwise prohibited under the Export Laws from receiving the Software.
  entity_types:
  - text: The Software is not intended for individuals and any individual licensing the Software on behalf of an institution shall have the authority to bind such institution to this Agreement.
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Clinical or diagnostic use outside labeling
    text: Under no circumstances shall the Software be Used for clinical or diagnostic purposes not in accordance with standard product labeling
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
name: AIRS Medical
provenance_date: '2026-11-09'
provider_name: AIRS Medical
provider_slug: airsmedical
slug: airsmedical-eligibility
source_date: '2026-11-09'
source_filename: airsmedical-eligibility.yml
source_heading: Eligibility
source_page: https://airsmed.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIRS Medical\naid: airsmedical\nurl: https://airsmed.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that You are not a citizen of, or otherwise located within, an embargoed nation,\n    and that You are not otherwise prohibited under the Export Laws from receiving the Software.\nentity_types:\n- type: other\n  text: The Software is not intended for individuals and any individual licensing the Software on behalf of an institution\n    shall have the authority to bind such institution to this Agreement.\nrestricted_uses:\n- summary:\
  \ Clinical or diagnostic use outside labeling\n  text: Under no circumstances shall the Software be Used for clinical or diagnostic purposes not in accordance\n    with standard product labeling\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/airsmedical/eligibility/airsmedical-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from AIRS Medical's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Imaging
- MRI
- Radiology
- Artificial Intelligence
- Medical Devices
- DICOM
---
