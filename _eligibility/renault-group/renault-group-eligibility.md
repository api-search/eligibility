---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “User” means an adult natural person browsing the Website for their own needs, in a strictly personal or commercial context, without any direct or indirect profit-making purpose
    type: individual
  minimum_age:
    text: “User” means an adult natural person browsing the Website
    value: adult
  restricted_uses:
  - summary: Unlawful or harmful content
    text: not use the Website to display, download or transmit any unlawful, harmful or otherwise inappropriate content.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to certain Elements of the Website requires the User to create an account in accordance with the terms and procedures provided at the time the account is created.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Renault Group
provenance_date: '2026-11-10'
provider_name: Renault Group
provider_slug: renault-group
slug: renault-group-eligibility
source_date: '2026-11-10'
source_filename: renault-group-eligibility.yml
source_heading: Eligibility
source_page: https://developer.renaultgroup.com/en/footer/legal-information
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Renault Group\naid: renault-group\nurl: https://developer.renaultgroup.com/en/footer/legal-information\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “User” means an adult natural person browsing the Website for their own needs, in a strictly personal or\n    commercial context, without any direct or indirect profit-making purpose\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: not use the Website to display, download or transmit any unlawful, harmful or otherwise inappropriate content.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: Access to certain Elements of the Website requires the User to create an account in accordance with the\n    terms and procedures provided at the time the account is created.\nminimum_age:\n  value: adult\n  text: “User” means an adult natural person browsing the Website\n"
source_yaml_url: https://artifacts.apis.io/renault-group/eligibility/renault-group-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Renault Group's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automotive
- Android Automotive
- In-Vehicle Apps
- SDK
- Software Defined Vehicle
- Vehicle Signals
---
