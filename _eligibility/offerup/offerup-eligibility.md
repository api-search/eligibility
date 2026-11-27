---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you may only register for an OfferUp account if you are legally permitted to, and do, live in the United States or one of its territories.
  entity_types:
  - text: You must be at least 16 years of age to use our Services.
    type: individual
  - text: OfferUp Jobs postings are only available for employment at businesses, not by individuals at this time, and only for positions based within the United States.
    type: business
  minimum_age:
    text: You must be at least 16 years of age to use our Services.
    value: '16'
  restricted_uses:
  - summary: Services postings limited to qualified providers
    text: Individuals who do not meet the criteria for a service provider are not permitted to post service listings at this time.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: To receive the TruYou badge, users must provide certain personal identification documents (e.g., a driver's license).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OfferUp
provenance_date: '2026-11-10'
provider_name: OfferUp
provider_slug: offerup
slug: offerup-eligibility
source_date: '2026-11-10'
source_filename: offerup-eligibility.yml
source_heading: Eligibility
source_page: https://offerup.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OfferUp\naid: offerup\nurl: https://offerup.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you may only register for an OfferUp account if you are legally permitted to, and do, live in the United\n    States or one of its territories.\nentity_types:\n- type: individual\n  text: You must be at least 16 years of age to use our Services.\n- type: business\n  text: OfferUp Jobs postings are only available for employment at businesses, not by individuals at this time,\n    and only for positions based within the United States.\nrestricted_uses:\n- summary: Services postings\
  \ limited to qualified providers\n  text: Individuals who do not meet the criteria for a service provider are not permitted to post service listings\n    at this time.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: To receive the TruYou badge, users must provide certain personal identification documents (e.g., a driver's\n    license).\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/offerup/eligibility/offerup-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from OfferUp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Recommerce
- Classifieds
- E-Commerce
- Consumer
- Local Commerce
---
