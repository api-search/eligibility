---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the Client is a natural person, the Client confirms that he/she is at least 18 years of age.
    type: individual
  - text: If the Client is accessing the Service on behalf of a legal entity, the person entering the Agreement on the behalf of the Client confirms that he/she has the legal authority to bind that entity.
    type: business
  minimum_age:
    text: If the Client is a natural person, the Client confirms that he/she is at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No business use of apartments
    text: using the Apartment(s) for business purposes or registering the address of the Apartment for business, is not permitted, unless otherwise confirmed by NAHVL in written form in advance;
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: NAHVL will ask and collect necessary information (including personal information) to verify your identity, contact details, preferences and other relevant information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bobw
provenance_date: '2026-11-09'
provider_name: Bobw
provider_slug: bobw
slug: bobw-eligibility
source_date: '2026-11-09'
source_filename: bobw-eligibility.yml
source_heading: Eligibility
source_page: https://bobw.co/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bobw\naid: bobw\nurl: https://bobw.co/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If the Client is a natural person, the Client confirms that he/she is at least 18 years of age.\n- type: business\n  text: If the Client is accessing the Service on behalf of a legal entity, the person entering the Agreement on\n    the behalf of the Client confirms that he/she has the legal authority to bind that entity.\nrestricted_uses:\n- summary: No business use of apartments\n  text: using the Apartment(s) for business purposes\
  \ or registering the address of the Apartment for business, is\n    not permitted, unless otherwise confirmed by NAHVL in written form in advance;\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: NAHVL will ask and collect necessary information (including personal information) to verify your identity,\n    contact details, preferences and other relevant information\nminimum_age:\n  value: '18'\n  text: If the Client is a natural person, the Client confirms that he/she is at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/bobw/eligibility/bobw-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Bobw's own page on 2026-11-09.
synthetic: false
tags:
- Hospitality
- Accommodation
- Sustainability
- Europe
- Short-Stay
---
