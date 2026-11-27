---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you agree to these Terms of Service on behalf of a business, you represent and warrant that you have the authority to bind that business to these Terms of Service
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or harmful use
    text: engaged in actions relating to or in the course of using the Site or Services that may be illegal or cause liability, harm, embarrassment, harassment, abuse or disruption
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
name: Shopventory
provenance_date: '2026-11-10'
provider_name: Shopventory
provider_slug: shopventory
slug: shopventory-eligibility
source_date: '2026-11-10'
source_filename: shopventory-eligibility.yml
source_heading: Eligibility
source_page: https://shopventory.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shopventory\naid: shopventory\nurl: https://shopventory.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you agree to these Terms of Service on behalf of a business, you represent and warrant that you have\n    the authority to bind that business to these Terms of Service\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: engaged in actions relating to or in the course of using the Site or Services that may be illegal or cause\n    liability, harm, embarrassment, harassment, abuse or disruption\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shopventory/eligibility/shopventory-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Shopventory's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Inventory
- Point-of-Sale
- Retail
- E-Commerce
- Reporting
- Small Business
- Techstars
---
