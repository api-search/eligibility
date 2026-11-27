---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Zenith operates the Service for customers worldwide, including in the United States and Europe.
  entity_types:
  - text: You may use the Service only if you are at least 13 years old, or older where your jurisdiction sets a higher minimum age
    type: individual
  - text: If you use the Service on behalf of a business, organisation, or other legal entity, you represent and warrant that you are authorised to bind that entity to these Terms
    type: business
  minimum_age:
    text: You may use the Service only if you are at least 13 years old, or older where your jurisdiction sets a higher minimum age
    value: '13'
  restricted_uses:
  - summary: Sanctioned countries and parties
    text: You represent that you are not located in, and will not use the Service in or for the benefit of, any country or party subject to applicable embargoes or sanctions
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use most features you must create an account. You agree to provide accurate, current, and complete information and to keep it up to date.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zenith Hosting
provenance_date: '2026-11-10'
provider_name: Zenith Hosting
provider_slug: zenith-hosting
slug: zenith-hosting-eligibility
source_date: '2026-11-10'
source_filename: zenith-hosting-eligibility.yml
source_heading: Eligibility
source_page: https://zenith.hosting/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zenith Hosting\naid: zenith-hosting\nurl: https://zenith.hosting/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Zenith operates the Service for customers worldwide, including in the United States and Europe.\nentity_types:\n- type: individual\n  text: You may use the Service only if you are at least 13 years old, or older where your jurisdiction sets a higher\n    minimum age\n- type: business\n  text: If you use the Service on behalf of a business, organisation, or other legal entity, you represent and warrant\n    that you are authorised to bind that entity to these\
  \ Terms\nrestricted_uses:\n- summary: Sanctioned countries and parties\n  text: You represent that you are not located in, and will not use the Service in or for the benefit of, any country\n    or party subject to applicable embargoes or sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use most features you must create an account. You agree to provide accurate, current, and complete information\n    and to keep it up to date.\nminimum_age:\n  value: '13'\n  text: You may use the Service only if you are at least 13 years old, or older where your jurisdiction sets a higher\n    minimum age\n"
source_yaml_url: https://artifacts.apis.io/zenith-hosting/eligibility/zenith-hosting-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Zenith Hosting's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hosting
- Cloud
- Software-as-a-Service
- Application
---
