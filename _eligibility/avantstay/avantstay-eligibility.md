---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are controlled and offered by us from our offices in the United States of America. We make no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: To use Our Site or book a Property using Our Site, you must be 25 years or older.
    type: individual
  - text: If you are an organization (i.e.- company), the individual accepting this Agreement on your behalf represents and warrants that he or she has the authority to bind you to this Agreement
    type: business
  minimum_age:
    text: you must be 25 years or older
    value: '25'
  restricted_uses:
  - summary: Commercial use of Property
    text: 'Unless express written consent is given by AvantStay, Guest may not use the Property for: (i) any commercial purpose, including photography and filming'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: the Primary Guest identified in Part I must successfully complete an identity verification check through Persona (Persona Identities Inc.) before check-in
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AvantStay
provenance_date: '2026-11-09'
provider_name: AvantStay
provider_slug: avantstay
slug: avantstay-eligibility
source_date: '2026-11-09'
source_filename: avantstay-eligibility.yml
source_heading: Eligibility
source_page: https://avantstay.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AvantStay\naid: avantstay\nurl: https://avantstay.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are controlled and offered by us from our offices in the United States of America. We make\n    no representations that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: To use Our Site or book a Property using Our Site, you must be 25 years or older.\n- type: business\n  text: If you are an organization (i.e.- company), the individual accepting this Agreement\
  \ on your behalf represents\n    and warrants that he or she has the authority to bind you to this Agreement\nrestricted_uses:\n- summary: Commercial use of Property\n  text: 'Unless express written consent is given by AvantStay, Guest may not use the Property for: (i) any commercial\n    purpose, including photography and filming'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: the Primary Guest identified in Part I must successfully complete an identity verification check through\n    Persona (Persona Identities Inc.) before check-in\nminimum_age:\n  value: '25'\n  text: you must be 25 years or older\n"
source_yaml_url: https://artifacts.apis.io/avantstay/eligibility/avantstay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from AvantStay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Vacation Rentals
- Short-Term Rental
- Hospitality
- Property Management
- Travel
- Real Estate
---
