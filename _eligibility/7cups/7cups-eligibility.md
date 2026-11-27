---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using our Services on behalf of a business or organization, that business or organization accepts these Terms.
    type: business
  minimum_age:
    text: You affirm that you are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: No emergency use
    text: DO NOT USE OUR SERVICE FOR EMERGENCIES.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: While 7 Cups does verify the license, qualifications and credentials of Therapists providing services through 7 Cups, you acknowledge that we do not guarantee such verification
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 7 Cups
provenance_date: '2026-11-09'
provider_name: 7 Cups
provider_slug: 7cups
slug: 7cups-eligibility
source_date: '2026-11-09'
source_filename: 7cups-eligibility.yml
source_heading: Eligibility
source_page: https://www.7cups.com/Documents/TermsOfService/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 7 Cups\naid: 7cups\nurl: https://www.7cups.com/Documents/TermsOfService/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using our Services on behalf of a business or organization, that business or organization accepts\n    these Terms.\nrestricted_uses:\n- summary: No emergency use\n  text: DO NOT USE OUR SERVICE FOR EMERGENCIES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: While 7 Cups does verify the license, qualifications and credentials of Therapists providing services through\n    7 Cups,\
  \ you acknowledge that we do not guarantee such verification\nminimum_age:\n  value: '13'\n  text: You affirm that you are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/7cups/eligibility/7cups-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from 7 Cups's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mental Health
- Online Therapy
- Emotional Support
- Counseling
- Healthcare
- Wellness
- Community
---
