---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - GB
    text: This Site is operated by SellersFunding from its offices in the United States. if your business is located outside of the United States or the United Kingdom, plea se confirm with SellersFunding that the product of service you wish to use is available in your location.
  entity_types:
  - text: Our customers are businesses, including small businesses. We do not provide financing or cash advances to natural persons or business that are natural persons, only businesses organized as legal entities.
    type: business
  minimum_age:
    text: you are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Use only for business purposes
    text: You acknowledge and agree to create an account and register with our Site strictly for business purposes.
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
name: Sellersfi
provenance_date: '2026-11-10'
provider_name: Sellersfi
provider_slug: sellersfi
slug: sellersfi-eligibility
source_date: '2026-11-10'
source_filename: sellersfi-eligibility.yml
source_heading: Eligibility
source_page: https://sellersfi.com/terms/terms-of-use.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sellersfi\naid: sellersfi\nurl: https://sellersfi.com/terms/terms-of-use.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - GB\n  excluded: []\n  text: This Site is operated by SellersFunding from its offices in the United States. if your business is located\n    outside of the United States or the United Kingdom, plea se confirm with SellersFunding that the product of\n    service you wish to use is available in your location.\nentity_types:\n- type: business\n  text: Our customers are businesses, including small businesses. We do not provide financing or cash advances to\n\
  \    natural persons or business that are natural persons, only businesses organized as legal entities.\nrestricted_uses:\n- summary: Use only for business purposes\n  text: You acknowledge and agree to create an account and register with our Site strictly for business purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/sellersfi/eligibility/sellersfi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Sellersfi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Financial Services
- Lending
- Working Capital
- Inventory Financing
- E-Commerce
- Embedded Finance
---
