---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Anyone who accesses or uses the Website or Services, either as an individual or on behalf of a business entity.
    type: individual
  - text: If you represent a company or organization, you confirm that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to access our Services.
    value: '18'
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
name: Celebal Technologies
provenance_date: '2026-11-09'
provider_name: Celebal Technologies
provider_slug: celebaltech
slug: celebaltech-eligibility
source_date: '2026-11-09'
source_filename: celebaltech-eligibility.yml
source_heading: Eligibility
source_page: https://celebaltech.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Celebal Technologies\naid: celebaltech\nurl: https://celebaltech.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Anyone who accesses or uses the Website or Services, either as an individual or on behalf of a business\n    entity.\n- type: business\n  text: If you represent a company or organization, you confirm that you have the authority to bind that entity\n    to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You must be at least 18 years of age to access our Services.\n"
source_yaml_url: https://artifacts.apis.io/celebaltech/eligibility/celebaltech-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Celebal Technologies's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consulting
- Artificial Intelligence
- Data Engineering
- Machine Learning
- Cloud
- Generative AI
- Databricks
- Microsoft Azure
- Data Science
- Data
---
