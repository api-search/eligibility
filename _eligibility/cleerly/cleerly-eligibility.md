---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Cleerly Software and/or Services for your internal business purposes only
    type: business
  - text: intended to be used by trained medical professionals as an interactive tool for viewing and analyzing cardiac computed tomography
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No off-label use endorsed
    text: Cleerly does not endorse off-label use of our products.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access Cleerly Software and/or Services, you may be asked to provide certain registration details or other information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cleerly
provenance_date: '2026-11-09'
provider_name: Cleerly
provider_slug: cleerly
slug: cleerly-eligibility
source_date: '2026-11-09'
source_filename: cleerly-eligibility.yml
source_heading: Eligibility
source_page: https://cleerly.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cleerly\naid: cleerly\nurl: https://cleerly.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You may use the Cleerly Software and/or Services for your internal business purposes only\n- type: other\n  text: intended to be used by trained medical professionals as an interactive tool for viewing and analyzing cardiac\n    computed tomography\nrestricted_uses:\n- summary: No off-label use endorsed\n  text: Cleerly does not endorse off-label use of our products.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: To access Cleerly Software and/or Services, you may be asked to provide certain registration details or\n    other information.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cleerly/eligibility/cleerly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Cleerly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health
- Cardiology
- Heart Disease
- Medical Imaging
- Artificial Intelligence
- Diagnostics
- Clinical Software
- Digital Health
---
