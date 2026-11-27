---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: neither you nor any User is located in, organized under the laws of, or ordinarily resident in any country or region that is subject to U.S. Government sanctions or embargoes, or that has been designated by the U.S. Government as a Specially Designated National
  entity_types:
  - text: the Services are intended exclusively for commercial and business purposes
    type: business
  - text: you may use the Services for personal, family, or household purposes
    type: individual
  minimum_age:
    text: all Users are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Restricted business categories
    text: your business is not engaged in a restricted category (see our Acceptable Use Policy )
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: we may ask you for your name, address, date of birth, and other information that will allow us to identify you. We may also ask for your driver's license or other identifying documents, such as business-related documents.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Liquid
provenance_date: '2026-11-09'
provider_name: Liquid
provider_slug: goliquid-io
slug: goliquid-io-eligibility
source_date: '2026-11-09'
source_filename: goliquid-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.liquidtrust.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Liquid\naid: goliquid-io\nurl: https://www.liquidtrust.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: neither you nor any User is located in, organized under the laws of, or ordinarily resident in any country\n    or region that is subject to U.S. Government sanctions or embargoes, or that has been designated by the U.S.\n    Government as a Specially Designated National\nentity_types:\n- type: business\n  text: the Services are intended exclusively for commercial and business purposes\n- type: individual\n  text: you may use the Services for\
  \ personal, family, or household purposes\nrestricted_uses:\n- summary: Restricted business categories\n  text: your business is not engaged in a restricted category (see our Acceptable Use Policy )\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: we may ask you for your name, address, date of birth, and other information that will allow us to identify\n    you. We may also ask for your driver's license or other identifying documents, such as business-related documents.\nminimum_age:\n  value: '18'\n  text: all Users are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/goliquid-io/eligibility/goliquid-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Liquid's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Escrow
- Marketplace
- Platform
- Compliance
- Global Payments
---
