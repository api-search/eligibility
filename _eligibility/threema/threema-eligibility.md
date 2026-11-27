---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Availability may be restricted in certain regions.
  entity_types:
  - text: Individuals who use the service (" Users ") receive the authorisation to use the service
    type: individual
  - text: The administrator of User Authorisations (hereinafter the " Administrator ") is defined as companies, organisations or natural persons who acquire multiple User Authorisations from THREEMA
    type: business
  minimum_age:
    text: Persons who lack full legal authority to bind a User to these Terms of Use are requested not to click on "Accept" and not to use the service until the User has consented to the Terms of Use.
    value: null
  restricted_uses:
  - summary: Emergency calls
    text: Emergency calls cannot be made via our service. Public telephone networks must be used instead.
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
name: Threema
provenance_date: '2026-11-10'
provider_name: Threema
provider_slug: threema
slug: threema-eligibility
source_date: '2026-11-10'
source_filename: threema-eligibility.yml
source_heading: Eligibility
source_page: https://threema.com/en/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Threema\naid: threema\nurl: https://threema.com/en/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Availability may be restricted in certain regions.\nentity_types:\n- type: individual\n  text: Individuals who use the service (\" Users \") receive the authorisation to use the service\n- type: business\n  text: The administrator of User Authorisations (hereinafter the \" Administrator \") is defined as companies, organisations\n    or natural persons who acquire multiple User Authorisations from THREEMA\nrestricted_uses:\n- summary: Emergency calls\n  text: Emergency calls cannot\
  \ be made via our service. Public telephone networks must be used instead.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Persons who lack full legal authority to bind a User to these Terms of Use are requested not to click on\n    \"Accept\" and not to use the service until the User has consented to the Terms of Use.\n"
source_yaml_url: https://artifacts.apis.io/threema/eligibility/threema-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Threema's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Messaging
- Security
- Privacy
- GDPR
---
