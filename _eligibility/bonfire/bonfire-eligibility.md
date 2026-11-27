---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to a Site and/or the content thereon may not be legal in certain countries outside the United States of America.
  entity_types:
  - text: Bonfire Marketplace provides a platform which allows Charitable Organizations, creators, artists, non-profits, businesses, or individuals who agree to these Terms of Use
    type: business
  - text: Bonfire Marketplace provides a platform which allows Charitable Organizations, creators, artists, non-profits, businesses, or individuals who agree to these Terms of Use
    type: nonprofit
  minimum_age:
    text: You must be at least eighteen (18) years old to register for or create a Bonfire Marketplace or Bonfire Pro account or to access or use any of Bonfire’s Services.
    value: eighteen (18) years
  restricted_uses:
  - summary: No shipping of political seller shirts outside US
    text: Bonfire will not ship to any user with a shipping or billing address outside of the United States if the user purchases a shirt from a Political Campaign Seller.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require that you provide a Form W-9 to us prior to releasing funds.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bonfire
provenance_date: '2026-11-09'
provider_name: Bonfire
provider_slug: bonfire
slug: bonfire-eligibility
source_date: '2026-11-09'
source_filename: bonfire-eligibility.yml
source_heading: Eligibility
source_page: https://www.bonfire.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bonfire\naid: bonfire\nurl: https://www.bonfire.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Access to a Site and/or the content thereon may not be legal in certain countries outside the United States\n    of America.\nentity_types:\n- type: business\n  text: Bonfire Marketplace provides a platform which allows Charitable Organizations, creators, artists, non-profits,\n    businesses, or individuals who agree to these Terms of Use\n- type: nonprofit\n  text: Bonfire Marketplace provides a platform which allows Charitable Organizations,\
  \ creators, artists, non-profits,\n    businesses, or individuals who agree to these Terms of Use\nrestricted_uses:\n- summary: No shipping of political seller shirts outside US\n  text: Bonfire will not ship to any user with a shipping or billing address outside of the United States if the\n    user purchases a shirt from a Political Campaign Seller.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require that you provide a Form W-9 to us prior to releasing funds.\nminimum_age:\n  value: eighteen (18) years\n  text: You must be at least eighteen (18) years old to register for or create a Bonfire Marketplace or Bonfire\n    Pro account or to access or use any of Bonfire’s Services.\n"
source_yaml_url: https://artifacts.apis.io/bonfire/eligibility/bonfire-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Bonfire's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Merchandising
- Fundraising
- Custom Design
---
