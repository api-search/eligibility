---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The contracting party will be the Peerspace entity in the jurisdiction where the Space that you are booking is located.
  entity_types:
  - text: You must be at least the legal age of majority in your jurisdiction of residence, and able to enter into legally binding contracts in order to access and use the Platform
    type: individual
  - text: If you are registering on behalf of a legal entity, you represent and warrant that you have the authority to legally bind that entity
    type: business
  minimum_age:
    text: You must be at least the legal age of majority in your jurisdiction of residence
    value: null
  restricted_uses:
  - summary: Embargoed countries
    text: Directly or indirectly conduct, promote, or facilitate business in countries and/or with nationals or members of governments that are subject to embargoes or trade sanctions
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may, but have no obligation to, take efforts to verify the identity of users and/or screen them against public and private databases
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Peerspace
provenance_date: '2026-11-10'
provider_name: Peerspace
provider_slug: peerspace
slug: peerspace-eligibility
source_date: '2026-11-10'
source_filename: peerspace-eligibility.yml
source_heading: Eligibility
source_page: https://www.peerspace.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Peerspace\naid: peerspace\nurl: https://www.peerspace.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The contracting party will be the Peerspace entity in the jurisdiction where the Space that you are booking\n    is located.\nentity_types:\n- type: individual\n  text: You must be at least the legal age of majority in your jurisdiction of residence, and able to enter into\n    legally binding contracts in order to access and use the Platform\n- type: business\n  text: If you are registering on behalf of a legal entity, you represent and warrant\
  \ that you have the authority\n    to legally bind that entity\nrestricted_uses:\n- summary: Embargoed countries\n  text: Directly or indirectly conduct, promote, or facilitate business in countries and/or with nationals or members\n    of governments that are subject to embargoes or trade sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we may, but have no obligation to, take efforts to verify the identity of users and/or screen them against\n    public and private databases\nminimum_age:\n  value: null\n  text: You must be at least the legal age of majority in your jurisdiction of residence\n"
source_yaml_url: https://artifacts.apis.io/peerspace/eligibility/peerspace-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Peerspace's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Marketplace
- Venues
- Event Spaces
- Booking
- Travel
- Real Estate
---
