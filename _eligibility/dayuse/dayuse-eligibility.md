---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: DAYUSE provides an online platform available on the website dayuse.com and the DAYUSE mobile app for daytime hotel bookings in 25 countries.
  entity_types:
  - text: The services offered on the DAYUSE Platform may only be used by persons of legal age.
    type: individual
  minimum_age:
    text: The Customer must confirm that they are of the legal age depending on local laws or over the age of 18 for the purposes of making a Booking.
    value: '18'
  restricted_uses:
  - summary: Promo codes limited to US hotels
    text: Promotional codes can only be used to book an offer in hotel located in the US.
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
name: Dayuse
provenance_date: '2026-11-09'
provider_name: Dayuse
provider_slug: dayuse
slug: dayuse-eligibility
source_date: '2026-11-09'
source_filename: dayuse-eligibility.yml
source_heading: Eligibility
source_page: https://www.dayuse.com/pages/dayuse/terms-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dayuse\naid: dayuse\nurl: https://www.dayuse.com/pages/dayuse/terms-privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: DAYUSE provides an online platform available on the website dayuse.com and the DAYUSE mobile app for daytime\n    hotel bookings in 25 countries.\nentity_types:\n- type: individual\n  text: The services offered on the DAYUSE Platform may only be used by persons of legal age.\nrestricted_uses:\n- summary: Promo codes limited to US hotels\n  text: Promotional codes can only be used to book an offer in hotel located in the US.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Customer must confirm that they are of the legal age depending on local laws or over the age of 18 for\n    the purposes of making a Booking.\n"
source_yaml_url: https://artifacts.apis.io/dayuse/eligibility/dayuse-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Dayuse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Travel
- Hospitality
- Hotels
- Booking
- Reservations
- Day Use
- Microstay
- Consumer
---
