---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Standard terms are net 30 days from the date of invoice upon approval of a signed credit application.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Standard terms are net 30 days from the date of invoice upon approval of a signed credit application.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Grove Health
provenance_date: '2026-11-09'
provider_name: Grove Health
provider_slug: grove-health
slug: grove-health-eligibility
source_date: '2026-11-09'
source_filename: grove-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.grovemedical.com/?page=customer&file=customer/grmein/customerpages/Terms_Conditions.htm
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Grove Health\naid: grove-health\nurl: https://www.grovemedical.com/?page=customer&file=customer/grmein/customerpages/Terms_Conditions.htm\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Standard terms are net 30 days from the date of invoice upon approval of a signed credit application.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Standard terms are net 30 days from the date of invoice upon approval of a signed credit application.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/grove-health/eligibility/grove-health-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Grove Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Supplies
- Distribution
- E-Commerce
- Medical Equipment
- B2B
---
