---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you use the Service on behalf of a company or other entity, you represent that you have authority to bind that entity, and both you and the entity accept these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Employment, credit, insurance, housing decisions
    text: its outputs must not be used to make employment, credit, insurance, housing, or similar eligibility decisions about a person
  - summary: Not a background-check service
    text: 'Gigi is not: a recruitment or staffing service, a background-check or vetting service'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Service is currently invite-only. Joining the waitlist does not create an obligation for us to grant access
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Gigi
provenance_date: '2026-11-09'
provider_name: Gigi
provider_slug: gigi
slug: gigi-eligibility
source_date: '2026-11-09'
source_filename: gigi-eligibility.yml
source_heading: Eligibility
source_page: https://gigi.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gigi\naid: gigi\nurl: https://gigi.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you use the Service on behalf of a company or other entity, you represent that you have authority to\n    bind that entity, and both you and the entity accept these Terms.\nrestricted_uses:\n- summary: Employment, credit, insurance, housing decisions\n  text: its outputs must not be used to make employment, credit, insurance, housing, or similar eligibility decisions\n\
  \    about a person\n- summary: Not a background-check service\n  text: 'Gigi is not: a recruitment or staffing service, a background-check or vetting service'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Service is currently invite-only. Joining the waitlist does not create an obligation for us to grant\n    access\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/gigi/eligibility/gigi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Gigi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Networking
- Agents
- Privacy
---
