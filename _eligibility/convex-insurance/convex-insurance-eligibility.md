---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: There are no restrictions for Users in terms of being Consumers or Business Users;
    type: individual
  - text: There are no restrictions for Users in terms of being Consumers or Business Users;
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use within intended scope and applicable law
    text: This Website and the Service may only be used within the scope of what they are provided for, under these Terms and applicable law.
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
name: Convex
provenance_date: '2026-11-09'
provider_name: Convex
provider_slug: convex-insurance
slug: convex-insurance-eligibility
source_date: '2026-11-09'
source_filename: convex-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://convexin.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Convex\naid: convex-insurance\nurl: https://convexin.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: There are no restrictions for Users in terms of being Consumers or Business Users;\n- type: business\n  text: There are no restrictions for Users in terms of being Consumers or Business Users;\nrestricted_uses:\n- summary: Use within intended scope and applicable law\n  text: This Website and the Service may only be used within the scope of what they are provided for, under these\n    Terms and applicable law.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/convex-insurance/eligibility/convex-insurance-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Convex's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- United Kingdom
- Property and Casualty
- Specialty Insurance
- Reinsurance
- Underwriting
- Claims
- London Market
- Carrier
- Digital Underwriting
---
