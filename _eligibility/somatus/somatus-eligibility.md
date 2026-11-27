---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing to our Terms on behalf of a company or other legal entity (“ Your Organization “), then (i) you represent and warrant that you have authority to act on behalf of, and to bind, Your Organization
    type: business
  minimum_age:
    text: Our Platform may not be used by anyone who is under 18 years old or not of legal age in your state of residence.
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive use
    text: not to use the Platform in any unlawful manner, for any unlawful or criminal purpose, or in any manner inconsistent with these Terms
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
name: Somatus
provenance_date: '2026-11-10'
provider_name: Somatus
provider_slug: somatus
slug: somatus-eligibility
source_date: '2026-11-10'
source_filename: somatus-eligibility.yml
source_heading: Eligibility
source_page: https://somatus.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Somatus\naid: somatus\nurl: https://somatus.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing to our Terms on behalf of a company or other legal entity (“ Your Organization “), then\n    (i) you represent and warrant that you have authority to act on behalf of, and to bind, Your Organization\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: not to use the Platform in any unlawful manner, for any unlawful or criminal purpose, or in any manner inconsistent\n    with these Terms\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Platform may not be used by anyone who is under 18 years old or not of legal age in your state of residence.\n"
source_yaml_url: https://artifacts.apis.io/somatus/eligibility/somatus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Somatus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Kidney Care
- Value-Based Care
- Chronic Care Management
- Population Health
- Health Plans
- Nephrology
- Care Management
- Predictive Analytics
---
