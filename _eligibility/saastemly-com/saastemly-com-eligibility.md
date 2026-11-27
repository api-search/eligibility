---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing or using our services, you confirm that you are at least 18 years old and have the legal capacity to enter into these Terms.
    type: individual
  - text: If you are using our services on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: you confirm that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: Use the services for any unlawful purpose
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
name: saastemly-com
provenance_date: '2026-11-10'
provider_name: saastemly-com
provider_slug: saastemly-com
slug: saastemly-com-eligibility
source_date: '2026-11-10'
source_filename: saastemly-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.saastemly.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: saastemly-com\naid: saastemly-com\nurl: https://www.saastemly.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By accessing or using our services, you confirm that you are at least 18 years old and have the legal capacity\n    to enter into these Terms.\n- type: business\n  text: If you are using our services on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use the services for any unlawful purpose\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you confirm that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/saastemly-com/eligibility/saastemly-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from saastemly-com's own page on 2026-11-10.
synthetic: false
tags:
- Software Development
- Custom Software
- Web Applications
- Mobile App
- Artificial Intelligence
---
