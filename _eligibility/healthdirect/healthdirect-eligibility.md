---
api_specs:
- filename: nhsd-developers-portal.postman_collection.json
  format: json
  label: NHSD FHIR API
  slug: nhsd-fhir-api
  spec_type: Postman
  url: https://artifacts.apis.io/healthdirect/collections/nhsd-developers-portal.postman_collection.json
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: The Online Services are designed only for people who are located within Australia
  entity_types:
  - text: are not intended to be used for commercial purposes such as for promoting, advertising, or generating revenue, directly or indirectly including through sponsorship, referrals, media publications, paid links, or the promotion of private services or businesses.
    type: business
  minimum_age:
    text: You must be aged 14 years or over to create a User Account.
    value: '14'
  restricted_uses:
  - summary: Commercial purposes
    text: are not intended to be used for commercial purposes such as for promoting, advertising, or generating revenue
  - summary: Widget use limited to own site
    text: You are not permitted to use a Healthdirect Widget for any other purpose or to give Healthdirect Widgets to other people to place on their or other third-party sites
  - summary: Not for emergencies
    text: The Online Services are not intended for use in emergency situations.
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
name: Healthdirect Australia
provenance_date: '2026-11-09'
provider_name: Healthdirect Australia
provider_slug: healthdirect
slug: healthdirect-eligibility
source_date: '2026-11-09'
source_filename: healthdirect-eligibility.yml
source_heading: Eligibility
source_page: https://about.healthdirect.gov.au/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Healthdirect Australia\naid: healthdirect\nurl: https://about.healthdirect.gov.au/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: The Online Services are designed only for people who are located within Australia\nentity_types:\n- type: business\n  text: are not intended to be used for commercial purposes such as for promoting, advertising, or generating revenue,\n    directly or indirectly including through sponsorship, referrals, media publications, paid links, or the promotion\n    of private services or businesses.\nrestricted_uses:\n- summary: Commercial purposes\n\
  \  text: are not intended to be used for commercial purposes such as for promoting, advertising, or generating revenue\n- summary: Widget use limited to own site\n  text: You are not permitted to use a Healthdirect Widget for any other purpose or to give Healthdirect Widgets\n    to other people to place on their or other third-party sites\n- summary: Not for emergencies\n  text: The Online Services are not intended for use in emergency situations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '14'\n  text: You must be aged 14 years or over to create a User Account.\n"
source_yaml_url: https://artifacts.apis.io/healthdirect/eligibility/healthdirect-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Healthdirect Australia's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Australia
- FHIR
- HL7
- Interoperability
- Provider Directory
- National Health System
- Health Services Directory
- Telehealth
- Digital Health
- Appointments
---
