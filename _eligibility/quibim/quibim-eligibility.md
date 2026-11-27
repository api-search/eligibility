---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users who wish to acquire Quibim’s must be over the age of 18.
    type: individual
  minimum_age:
    text: Use of the Platform and the acquisition of the Studies is restricted to Users over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Diagnostic aid only, not replacement for medical professional
    text: The Studies are tools to assist with the diagnosis, which offer new elements of analysis to the User, but do not in any case replace the analysis and diagnosis prepared by a medical professional
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To acquire the services of Quibim, the User must be registered on the Platform
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: QUIBIM
provenance_date: '2026-11-10'
provider_name: QUIBIM
provider_slug: quibim
slug: quibim-eligibility
source_date: '2026-11-10'
source_filename: quibim-eligibility.yml
source_heading: Eligibility
source_page: https://quibim.ai/legal-notice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: QUIBIM\naid: quibim\nurl: https://quibim.ai/legal-notice/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users who wish to acquire Quibim’s must be over the age of 18.\nrestricted_uses:\n- summary: Diagnostic aid only, not replacement for medical professional\n  text: The Studies are tools to assist with the diagnosis, which offer new elements of analysis to the User, but\n    do not in any case replace the analysis and diagnosis prepared by a medical professional\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: To acquire the services of Quibim, the User must be registered on the Platform\nminimum_age:\n  value: '18'\n  text: Use of the Platform and the acquisition of the Studies is restricted to Users over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/quibim/eligibility/quibim-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from QUIBIM's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medical Imaging
- Artificial Intelligence
- Radiology
- Imaging Biomarkers
- Radiomics
- Life Sciences
- Drug Development
---
