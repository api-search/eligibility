---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Althea US ships from Korea to over 200 countries in the world
  entity_types:
  - text: Each member is entitled to one Althea account.
    type: individual
  minimum_age:
    text: If you are under 18, you may use Althea only with involvement of a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: No resale or commercial use
    text: This license does not include any resale or commercial use of this site or its contents
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Account verification is done through verification of the member's mobile phone number.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Althea
provenance_date: '2026-11-09'
provider_name: Althea
provider_slug: althea
slug: althea-eligibility
source_date: '2026-11-09'
source_filename: althea-eligibility.yml
source_heading: Eligibility
source_page: https://us.althea.kr/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Althea\naid: althea\nurl: https://us.althea.kr/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Althea US ships from Korea to over 200 countries in the world\nentity_types:\n- type: individual\n  text: Each member is entitled to one Althea account.\nrestricted_uses:\n- summary: No resale or commercial use\n  text: This license does not include any resale or commercial use of this site or its contents\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Account verification is done through verification of the member's mobile phone number.\n\
  minimum_age:\n  value: '18'\n  text: If you are under 18, you may use Althea only with involvement of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/althea/eligibility/althea-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Althea's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Beauty
- Cosmetics
- K-Beauty
- Skincare
- Agentic Commerce
- Shopify
---
