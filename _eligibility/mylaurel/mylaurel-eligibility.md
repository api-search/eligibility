---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: myLaurel's Sites are intended solely for residents of the United States. The Sites should not be used outside of the United States.
  entity_types:
  - text: No one under the age of 18 is allowed to use, access, or request services from our Sites.
    type: individual
  - text: if you use the Sites on behalf of an organization or entity, you have the legal authority to bind such organization or entity to these Terms
    type: business
  minimum_age:
    text: No one under the age of 18 is allowed to use, access, or request services from our Sites.
    value: '18'
  restricted_uses:
  - summary: Medical emergencies
    text: OUR SITES AND SERVICES ARE NOT INTENDED FOR USE IN MEDICAL EMERGENCIES OR OTHER URGENT SITUATIONS.
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
name: myLaurel
provenance_date: '2026-11-10'
provider_name: myLaurel
provider_slug: mylaurel
slug: mylaurel-eligibility
source_date: '2026-11-10'
source_filename: mylaurel-eligibility.yml
source_heading: Eligibility
source_page: https://www.mylaurelhealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: myLaurel\naid: mylaurel\nurl: https://www.mylaurelhealth.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: myLaurel's Sites are intended solely for residents of the United States. The Sites should not be used outside\n    of the United States.\nentity_types:\n- type: individual\n  text: No one under the age of 18 is allowed to use, access, or request services from our Sites.\n- type: business\n  text: if you use the Sites on behalf of an organization or entity, you have the legal authority to bind such organization\n    or entity to these Terms\nrestricted_uses:\n\
  - summary: Medical emergencies\n  text: OUR SITES AND SERVICES ARE NOT INTENDED FOR USE IN MEDICAL EMERGENCIES OR OTHER URGENT SITUATIONS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: No one under the age of 18 is allowed to use, access, or request services from our Sites.\n"
source_yaml_url: https://artifacts.apis.io/mylaurel/eligibility/mylaurel-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from myLaurel's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Healthcare
- Home Care
- Acute Care
- Transitional Care
- Digital Health
- Value-Based Care
---
