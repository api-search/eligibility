---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are intended for use in the United States only.
  entity_types:
  - text: The Services are not intended for or directed to children under 18 years old.
    type: individual
  minimum_age:
    text: The Services are not intended for or directed to children under 18 years old.
    value: '18'
  restricted_uses:
  - summary: Emergency use
    text: Dial 911 in the case of an emergency. Covera is not a health care provider and cannot provide assistance in the case of an emergency.
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
name: Covera Health
provenance_date: '2026-11-09'
provider_name: Covera Health
provider_slug: covera-health
slug: covera-health-eligibility
source_date: '2026-11-09'
source_filename: covera-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.coverahealth.com/termsconditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Covera Health\naid: covera-health\nurl: https://www.coverahealth.com/termsconditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are intended for use in the United States only.\nentity_types:\n- type: individual\n  text: The Services are not intended for or directed to children under 18 years old.\nrestricted_uses:\n- summary: Emergency use\n  text: Dial 911 in the case of an emergency. Covera is not a health care provider and cannot provide assistance\n    in the case of an emergency.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: The Services are not intended for or directed to children under 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/covera-health/eligibility/covera-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Covera Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Radiology
- Artificial Intelligence
- Clinical Intelligence
- Diagnostics
- Health Plans
- Quality Insights
---
