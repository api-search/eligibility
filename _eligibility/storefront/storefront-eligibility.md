---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use our sites if you are not able to form legally binding contracts, are under the age of 18, or are temporarily or indefinitely suspended from using our sites;
    type: individual
  minimum_age:
    text: are under the age of 18
    value: '18'
  restricted_uses:
  - summary: Illegal or immoral purposes
    text: Use our website and/or the commercial offering in our website for any illegal or immoral purposes, including but not limited to pornography, drug use, gambling or prostitution
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Storefront may suspend or terminate your access to the Services and your account if Storefront has reason to believe that you are not authorized to act on behalf of a company or organization
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Storefront
provenance_date: '2026-11-10'
provider_name: Storefront
provider_slug: storefront
slug: storefront-eligibility
source_date: '2026-11-10'
source_filename: storefront-eligibility.yml
source_heading: Eligibility
source_page: https://www.thestorefront.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Storefront\naid: storefront\nurl: https://www.thestorefront.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use our sites if you are not able to form legally binding contracts, are under the age of 18, or are temporarily\n    or indefinitely suspended from using our sites;\nrestricted_uses:\n- summary: Illegal or immoral purposes\n  text: Use our website and/or the commercial offering in our website for any illegal or immoral purposes, including\n    but not limited to pornography, drug use,\
  \ gambling or prostitution\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Storefront may suspend or terminate your access to the Services and your account if Storefront has reason\n    to believe that you are not authorized to act on behalf of a company or organization\nminimum_age:\n  value: '18'\n  text: are under the age of 18\n"
source_yaml_url: https://artifacts.apis.io/storefront/eligibility/storefront-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Storefront's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Retail
- Pop-Up Retail
- Real Estate
- Event
- Commercial Space Rental
- E-Commerce
---
