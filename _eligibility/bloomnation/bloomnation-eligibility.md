---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Some products may have restricted delivery within the United States.
  entity_types:
  - text: BloomNation is available only to, and may only be used by, individuals who are 18 years of age and older
    type: individual
  - text: If you are registering as a business entity, you personally guarantee that you have the authority to bind the entity you are acting on behalf of to this Agreement.
    type: business
  minimum_age:
    text: BloomNation is available only to, and may only be used by, individuals who are 18 years of age and older
    value: '18'
  restricted_uses:
  - summary: No illegal, counterfeit or stolen items
    text: (ii) Be fraudulent or involve the sale of illegal, counterfeit or stolen items.
  - summary: No stock or wire-service photos in listings
    text: Florist may not utilize wire-service or stock photos in its listings.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: BloomNation does not conduct background checks regarding any users of the Site and our verification process for Florists is limited.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BloomNation
provenance_date: '2026-11-09'
provider_name: BloomNation
provider_slug: bloomnation
slug: bloomnation-eligibility
source_date: '2026-11-09'
source_filename: bloomnation-eligibility.yml
source_heading: Eligibility
source_page: https://www.bloomnation.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BloomNation\naid: bloomnation\nurl: https://www.bloomnation.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Some products may have restricted delivery within the United States.\nentity_types:\n- type: individual\n  text: BloomNation is available only to, and may only be used by, individuals who are 18 years of age and older\n- type: business\n  text: If you are registering as a business entity, you personally guarantee that you have the authority to bind\n    the entity you are acting on behalf of to this Agreement.\nrestricted_uses:\n- summary:\
  \ No illegal, counterfeit or stolen items\n  text: (ii) Be fraudulent or involve the sale of illegal, counterfeit or stolen items.\n- summary: No stock or wire-service photos in listings\n  text: Florist may not utilize wire-service or stock photos in its listings.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: BloomNation does not conduct background checks regarding any users of the Site and our verification process\n    for Florists is limited.\nminimum_age:\n  value: '18'\n  text: BloomNation is available only to, and may only be used by, individuals who are 18 years of age and older\n"
source_yaml_url: https://artifacts.apis.io/bloomnation/eligibility/bloomnation-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from BloomNation's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Flowers
- Floral Delivery
- Marketplace
- E-Commerce
- Local Florists
- Same-Day Delivery
- Retail
- Payments
- Consumer
---
