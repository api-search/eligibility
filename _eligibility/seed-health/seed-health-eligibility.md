---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may only access and use the Site in compliance with all applicable laws... use or access the Site from a jurisdiction where such use or access is not authorized
  entity_types:
  - text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO USE OR ACCESS THE SITE, TO USE OUR SERVICES, AND TO PURCHASE OR SUBSCRIBE TO OUR PRODUCTS.
    type: individual
  minimum_age:
    text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO USE OR ACCESS THE SITE
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Users are the sole creators of their accounts and Seed Health may not independently verify the information provided.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Seed Health
provenance_date: '2026-11-10'
provider_name: Seed Health
provider_slug: seed-health
slug: seed-health-eligibility
source_date: '2026-11-10'
source_filename: seed-health-eligibility.yml
source_heading: Eligibility
source_page: https://seed.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Seed Health\naid: seed-health\nurl: https://seed.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may only access and use the Site in compliance with all applicable laws... use or access the Site from\n    a jurisdiction where such use or access is not authorized\nentity_types:\n- type: individual\n  text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO USE OR ACCESS THE SITE, TO USE OUR SERVICES, AND TO PURCHASE OR\n    SUBSCRIBE TO OUR PRODUCTS.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Users are the sole creators\
  \ of their accounts and Seed Health may not independently verify the information\n    provided.\nminimum_age:\n  value: '18'\n  text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO USE OR ACCESS THE SITE\n"
source_yaml_url: https://artifacts.apis.io/seed-health/eligibility/seed-health-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Seed Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Consumer Products
- Life Sciences
- Microbiome
- Probiotics
- Nutrition
- Subscription Commerce
- Direct to Consumer
- Biotechnology
---
