---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: 'Service is available only in the states shown as available on the Platform at the time of your visit, which are currently: Arizona (AZ), Colorado (CO), Connecticut (CT), Florida (FL), Iowa (IA), Maryland (MD), Montana (MT), New Mexico (NM), Utah (UT), Virginia (VA), and Washington (WA)'
  entity_types:
  - text: You must be the patient seeking treatment for yourself. You may not submit an intake form or request a prescription on behalf of another individual
    type: individual
  minimum_age:
    text: You must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No controlled substances
    text: Bidwell Health does not prescribe controlled substances of any schedule under any circumstances
  - summary: Not for emergency care
    text: Our services are NOT intended for emergency care.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Bidwell Health reserves the right to refuse service to any individual who does not meet the above eligibility criteria or for any other reason at our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bidwell Health
provenance_date: '2026-11-09'
provider_name: Bidwell Health
provider_slug: bidwellhealth-com
slug: bidwellhealth-com-eligibility
source_date: '2026-11-09'
source_filename: bidwellhealth-com-eligibility.yml
source_heading: Eligibility
source_page: https://bidwellhealth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bidwell Health\naid: bidwellhealth-com\nurl: https://bidwellhealth.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: 'Service is available only in the states shown as available on the Platform at the time of your visit, which\n    are currently: Arizona (AZ), Colorado (CO), Connecticut (CT), Florida (FL), Iowa (IA), Maryland (MD), Montana\n    (MT), New Mexico (NM), Utah (UT), Virginia (VA), and Washington (WA)'\nentity_types:\n- type: individual\n  text: You must be the patient seeking treatment for yourself. You may not submit an intake form or request a prescription\n\
  \    on behalf of another individual\nrestricted_uses:\n- summary: No controlled substances\n  text: Bidwell Health does not prescribe controlled substances of any schedule under any circumstances\n- summary: Not for emergency care\n  text: Our services are NOT intended for emergency care.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Bidwell Health reserves the right to refuse service to any individual who does not meet the above eligibility\n    criteria or for any other reason at our sole discretion.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/bidwellhealth-com/eligibility/bidwellhealth-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Bidwell Health's own page on 2026-11-09.
synthetic: false
tags:
- Telehealth
- Healthcare
- Online Visits
- Cash Pay
- US
---
