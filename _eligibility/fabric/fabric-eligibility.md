---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under 18, you may use the Site only with permission of a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: No PHI submission
    text: Do not submit Protected Health Information (“PHI”) through this Site.
  - summary: Informational use only
    text: It is not intended to provide medical advice, diagnosis, or treatment, nor to serve as a patient portal.
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
name: Fabric
provenance_date: '2026-11-09'
provider_name: Fabric
provider_slug: fabric
slug: fabric-eligibility
source_date: '2026-11-09'
source_filename: fabric-eligibility.yml
source_heading: Eligibility
source_page: https://www.fabrichealth.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fabric\naid: fabric\nurl: https://www.fabrichealth.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No PHI submission\n  text: Do not submit Protected Health Information (“PHI”) through this Site.\n- summary: Informational use only\n  text: It is not intended to provide medical advice, diagnosis, or treatment, nor to serve as a patient portal.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18, you may use the Site only\
  \ with permission of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/fabric/eligibility/fabric-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fabric's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Virtual Care
- Digital Health
- Patient Engagement
- Care Navigation
- AI Triage
- EMR Integration
---
