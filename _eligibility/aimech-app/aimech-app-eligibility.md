---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old and legally able to enter into these Terms. If you are under the age of majority where you live, a parent or legal guardian must approve your use.
    type: individual
  minimum_age:
    text: You must be at least 13 years old and legally able to enter into these Terms.
    value: '13'
  restricted_uses:
  - summary: Not a substitute for professional inspection
    text: use output as a substitute for required professional inspection, regulatory compliance, or safety procedures.
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
name: AIMECH.APP
provenance_date: '2026-11-09'
provider_name: AIMECH.APP
provider_slug: aimech-app
slug: aimech-app-eligibility
source_date: '2026-11-09'
source_filename: aimech-app-eligibility.yml
source_heading: Eligibility
source_page: https://aimech.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIMECH.APP\naid: aimech-app\nurl: https://aimech.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old and legally able to enter into these Terms. If you are under the age of\n    majority where you live, a parent or legal guardian must approve your use.\nrestricted_uses:\n- summary: Not a substitute for professional inspection\n  text: use output as a substitute for required professional inspection, regulatory compliance, or safety procedures.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old and legally able to enter into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/aimech-app/eligibility/aimech-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AIMECH.APP's own page on 2026-11-09.
synthetic: false
tags:
- Car Diagnostics
- Vehicle Maintenance
- Digital Garage
- Repair Cost Estimates
---
