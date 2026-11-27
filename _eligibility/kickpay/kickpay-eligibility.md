---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users declare themselves to be adult according to their applicable legislation.
    type: individual
  - text: businesses can sell their account receivables to investors
    type: business
  minimum_age:
    text: Under no circumstance may persons under the age of 13 use Kickpay.
    value: '13'
  restricted_uses:
  - summary: Unlawful or abusive content
    text: disseminate or publish content that is unlawful, obscene, illegitimate, defamatory or inappropriate
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Users must register in a truthful and complete manner by providing all the required data in the relevant registration form.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kickpay
provenance_date: '2026-11-09'
provider_name: Kickpay
provider_slug: kickpay
slug: kickpay-eligibility
source_date: '2026-11-09'
source_filename: kickpay-eligibility.yml
source_heading: Eligibility
source_page: https://www.iubenda.com/terms-and-conditions/821696
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kickpay\naid: kickpay\nurl: https://www.iubenda.com/terms-and-conditions/821696\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users declare themselves to be adult according to their applicable legislation.\n- type: business\n  text: businesses can sell their account receivables to investors\nrestricted_uses:\n- summary: Unlawful or abusive content\n  text: disseminate or publish content that is unlawful, obscene, illegitimate, defamatory or inappropriate\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ Users must register in a truthful and complete manner by providing all the required data in the relevant\n    registration form.\nminimum_age:\n  value: '13'\n  text: Under no circumstance may persons under the age of 13 use Kickpay.\n"
source_yaml_url: https://artifacts.apis.io/kickpay/eligibility/kickpay-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Kickpay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Lending
- Inventory Financing
- E-Commerce
- Supply Chain Finance
- Working Capital
---
