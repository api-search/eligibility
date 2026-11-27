---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: 'open only to legal residents of the forty-eight (48) contiguous United States and the District of Columbia (sweepstakes only). Service: Ollie makes no representations that the Service is appropriate or available for use in other locations.'
  entity_types:
  - text: Ollie sells pet food products (“Products”) to end-user customers like you for your personal, non-commercial use.
    type: individual
  - text: If you register on behalf of a business, you represent to Ollie that you have the authority to bind that business
    type: business
  minimum_age:
    text: The Service is only available to users who (1) are over the age of 18, (2) are emancipated minors, or (3) possess legal parental or guardian consent
    value: '18'
  restricted_uses:
  - summary: No resale
    text: You may not purchase Products or Subscriptions for resale purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Ollie reserves the right to refuse registration of an account, or cancel an account in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ollie
provenance_date: '2026-11-10'
provider_name: Ollie
provider_slug: ollie
slug: ollie-eligibility
source_date: '2026-11-10'
source_filename: ollie-eligibility.yml
source_heading: Eligibility
source_page: https://www.ollie.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ollie\naid: ollie\nurl: https://www.ollie.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: 'open only to legal residents of the forty-eight (48) contiguous United States and the District of Columbia\n    (sweepstakes only). Service: Ollie makes no representations that the Service is appropriate or available for\n    use in other locations.'\nentity_types:\n- type: individual\n  text: Ollie sells pet food products (“Products”) to end-user customers like you for your personal, non-commercial\n    use.\n- type: business\n  text: If you register on behalf\
  \ of a business, you represent to Ollie that you have the authority to bind that\n    business\nrestricted_uses:\n- summary: No resale\n  text: You may not purchase Products or Subscriptions for resale purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Ollie reserves the right to refuse registration of an account, or cancel an account in its sole discretion.\nminimum_age:\n  value: '18'\n  text: The Service is only available to users who (1) are over the age of 18, (2) are emancipated minors, or (3)\n    possess legal parental or guardian consent\n"
source_yaml_url: https://artifacts.apis.io/ollie/eligibility/ollie-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Ollie's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pets
- Pet Food
- Dog Food
- Direct to Consumer
- Subscription
- E-Commerce
- Consumer Health
---
