---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Clinic means a medical practice, healthcare practice, Practitioner or other organised or incorporated body that provides healthcare services and has entered into a Software User Agreement or other signed written agreement with Us
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No critical or emergency care reliance
    text: not use or rely upon the Platform in relation to, any critical, emergency or acute care medical circumstances
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Any person who registers an Account in the Platform warrants that they are an authorised representative of the Clinic, with the requisite authority to bind the Clinic to these Terms.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HotDoc
provenance_date: '2026-11-09'
provider_name: HotDoc
provider_slug: hotdoc
slug: hotdoc-eligibility
source_date: '2026-11-09'
source_filename: hotdoc-eligibility.yml
source_heading: Eligibility
source_page: https://practices.hotdoc.com.au/terms-of-services-clinics/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HotDoc\naid: hotdoc\nurl: https://practices.hotdoc.com.au/terms-of-services-clinics/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Clinic means a medical practice, healthcare practice, Practitioner or other organised or incorporated body\n    that provides healthcare services and has entered into a Software User Agreement or other signed written agreement\n    with Us\nrestricted_uses:\n- summary: No critical or emergency care reliance\n  text: not use or rely upon the Platform in relation to, any critical, emergency or acute care\
  \ medical circumstances\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Any person who registers an Account in the Platform warrants that they are an authorised representative\n    of the Clinic, with the requisite authority to bind the Clinic to these Terms.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hotdoc/eligibility/hotdoc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from HotDoc's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Australia
- Patient Engagement
- Online Booking
- Appointment Scheduling
- Telehealth
- Practice Management
- Primary Care
- Digital Health
- e-Prescribing
- Scheduling
---
