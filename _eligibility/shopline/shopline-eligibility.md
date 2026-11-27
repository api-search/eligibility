---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the Developer is a company, organization, or legal entity, it has been duly established or organized and is valid and in good standing under the laws of its jurisdiction.
    type: business
  - text: If the Developer is an individual, the Developer must be at least 18 years old or have reached the legal age of majority in the Developer's place of residence
    type: individual
  minimum_age:
    text: the Developer must be at least 18 years old or have reached the legal age of majority in the Developer's place of residence
    value: '18'
  restricted_uses:
  - summary: Illegal, infringing or harmful content
    text: Not to use SHOPLINE's resources and services to upload, download, store, or publish any illegal, infringing, obscene, pornographic, immoral, fraudulent, defamatory
  - summary: Advertising within applications
    text: The Application shall not contain or be embedded with any form of advertisement, including but not limited to pop-up advertisements, banner advertisements, or any other form of advertising.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: After a Developer has successfully registered a Developer account, SHOPLINE will verify the identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SHOPLINE
provenance_date: '2026-11-10'
provider_name: SHOPLINE
provider_slug: shopline
slug: shopline-eligibility
source_date: '2026-11-10'
source_filename: shopline-eligibility.yml
source_heading: Eligibility
source_page: https://developer.shopline.com/docs/apps/get-started/shopline-developer-services-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SHOPLINE\naid: shopline\nurl: https://developer.shopline.com/docs/apps/get-started/shopline-developer-services-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the Developer is a company, organization, or legal entity, it has been duly established or organized\n    and is valid and in good standing under the laws of its jurisdiction.\n- type: individual\n  text: If the Developer is an individual, the Developer must be at least 18 years old or have reached the legal\n    age of majority in the Developer's\
  \ place of residence\nrestricted_uses:\n- summary: Illegal, infringing or harmful content\n  text: Not to use SHOPLINE's resources and services to upload, download, store, or publish any illegal, infringing,\n    obscene, pornographic, immoral, fraudulent, defamatory\n- summary: Advertising within applications\n  text: The Application shall not contain or be embedded with any form of advertisement, including but not limited\n    to pop-up advertisements, banner advertisements, or any other form of advertising.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: After a Developer has successfully registered a Developer account, SHOPLINE will verify the identity.\nminimum_age:\n  value: '18'\n  text: the Developer must be at least 18 years old or have reached the legal age of majority in the Developer's\n    place of residence\n"
source_yaml_url: https://artifacts.apis.io/shopline/eligibility/shopline-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from SHOPLINE's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Commerce
- Retail
- Point-of-Sale
- Storefront
- Payments
- Webhook
- GraphQL
- Developer Platform
- Application
---
