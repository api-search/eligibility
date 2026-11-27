---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: This website and our communications are created for access in the UK. Any users that are in a jurisdiction where the site's publication or availability is prohibited must not access the website.
  entity_types:
  - text: You must be at least 18 years of age to register with us upon the date of registration.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to register with us upon the date of registration.
    value: '18'
  restricted_uses:
  - summary: Services for own use only
    text: The services are offered for your use, and not for the use or benefit of a third party.
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
name: Smol
provenance_date: '2026-11-10'
provider_name: Smol
provider_slug: smol
slug: smol-eligibility
source_date: '2026-11-10'
source_filename: smol-eligibility.yml
source_heading: Eligibility
source_page: https://smol.com/uk/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Smol\naid: smol\nurl: https://smol.com/uk/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: This website and our communications are created for access in the UK. Any users that are in a jurisdiction\n    where the site's publication or availability is prohibited must not access the website.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to register with us upon the date of registration.\nrestricted_uses:\n- summary: Services for own use only\n  text: The services are offered for your use, and not for the use or benefit of a third\
  \ party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to register with us upon the date of registration.\n"
source_yaml_url: https://artifacts.apis.io/smol/eligibility/smol-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Smol's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Cleaning Products
- Subscription
- E-Commerce
- Direct to Consumer
- Sustainability
- B Corp
- Household Products
---
