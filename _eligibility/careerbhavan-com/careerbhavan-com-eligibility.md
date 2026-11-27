---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: Explore and compare colleges, universities, and courses across India.
  entity_types:
  - text: If you are using our services on behalf of an institution, you represent that you have the authority to bind that institution to these Terms.
    type: other
  minimum_age:
    text: you confirm that you are at least 16 years old and have the legal capacity to enter into these Terms.
    value: '16'
  restricted_uses:
  - summary: Unlawful purposes
    text: Use the platform for any unlawful purpose or in violation of any applicable laws.
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
name: Career Bhavan
provenance_date: '2026-11-09'
provider_name: Career Bhavan
provider_slug: careerbhavan-com
slug: careerbhavan-com-eligibility
source_date: '2026-11-09'
source_filename: careerbhavan-com-eligibility.yml
source_heading: Eligibility
source_page: https://careerbhavan.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Career Bhavan\naid: careerbhavan-com\nurl: https://careerbhavan.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: Explore and compare colleges, universities, and courses across India.\nentity_types:\n- type: other\n  text: If you are using our services on behalf of an institution, you represent that you have the authority to\n    bind that institution to these Terms.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use the platform for any unlawful purpose or in violation of any applicable laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '16'\n  text: you confirm that you are at least 16 years old and have the legal capacity to enter into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/careerbhavan-com/eligibility/careerbhavan-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Career Bhavan's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Admissions
- Consulting
- India
- Careers
---
