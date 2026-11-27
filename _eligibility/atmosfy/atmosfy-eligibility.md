---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 18 or under the age of legal majority where you live, you may use the Site only with the permission of a parent or legal guardian who has reviewed these Terms and agreed to supervise your use.
    type: individual
  - text: Separate commercial creator programs and third-party commercial licensing require that you have reached the age of legal majority where you live and are at least 18, unless Company has separately established the legally required authorization for participation by a minor.
    type: individual
  minimum_age:
    text: You must be at least 13 years old, and meet any higher minimum age required where you live, to use the Site.
    value: '13'
  restricted_uses:
  - summary: Restricted material for commercial licensing
    text: Do not offer restricted material for commercial licensing.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may request reasonable evidence of age, identity, authority, or required guardian authorization before making content eligible for third-party commercial licensing.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Atmosfy
provenance_date: '2026-11-09'
provider_name: Atmosfy
provider_slug: atmosfy
slug: atmosfy-eligibility
source_date: '2026-11-09'
source_filename: atmosfy-eligibility.yml
source_heading: Eligibility
source_page: https://atmosfy.io/terms-of-service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atmosfy\naid: atmosfy\nurl: https://atmosfy.io/terms-of-service.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 18 or under the age of legal majority where you live, you may use the Site only with the\n    permission of a parent or legal guardian who has reviewed these Terms and agreed to supervise your use.\n- type: individual\n  text: Separate commercial creator programs and third-party commercial licensing require that you have reached\n    the age of legal majority where you live and are at least 18, unless\
  \ Company has separately established the\n    legally required authorization for participation by a minor.\nrestricted_uses:\n- summary: Restricted material for commercial licensing\n  text: Do not offer restricted material for commercial licensing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may request reasonable evidence of age, identity, authority, or required guardian authorization before\n    making content eligible for third-party commercial licensing.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old, and meet any higher minimum age required where you live, to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/atmosfy/eligibility/atmosfy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Atmosfy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Maps
- Location
- Social
- Discovery
- Local
- Restaurant
- User Generated Content
- AI Training Data
---
