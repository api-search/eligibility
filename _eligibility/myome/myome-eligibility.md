---
api_specs:
- filename: myome-institutional-interface-api-openapi.yml
  format: yaml
  label: MyOme Institutional Interface API
  slug: myome-institutional-interface-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/myome/openapi/myome-institutional-interface-api-openapi.yml
- filename: myome-requisitions-and-orders-api-openapi.yml
  format: yaml
  label: MyOme Requisitions and Orders API
  slug: myome-requisitions-and-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/myome/openapi/myome-requisitions-and-orders-api-openapi.yml
- filename: myome-resources-api-openapi.yml
  format: yaml
  label: MyOme Resources API
  slug: myome-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/myome/openapi/myome-resources-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If accessing, browsing or using our services or any of the content available on our services on behalf of an entity, you have full authority to bind your entity to all of these terms and conditions.
    type: business
  - text: Qualified healthcare providers are subject to additional terms applicable their use of the Clinical Portals.
    type: individual
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Not medical advice; not for emergencies
    text: IF YOU ARE HAVING A MEDICAL EMERGENCY, CONTACT 911, AND DO NOT USE OUR SERVICES.
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
name: MyOme
provenance_date: '2026-11-10'
provider_name: MyOme
provider_slug: myome
slug: myome-eligibility
source_date: '2026-11-10'
source_filename: myome-eligibility.yml
source_heading: Eligibility
source_page: https://myome.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MyOme\naid: myome\nurl: https://myome.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If accessing, browsing or using our services or any of the content available on our services on behalf of\n    an entity, you have full authority to bind your entity to all of these terms and conditions.\n- type: individual\n  text: Qualified healthcare providers are subject to additional terms applicable their use of the Clinical Portals.\nrestricted_uses:\n- summary: Not medical advice; not for emergencies\n  text: IF YOU\
  \ ARE HAVING A MEDICAL EMERGENCY, CONTACT 911, AND DO NOT USE OUR SERVICES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/myome/eligibility/myome-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from MyOme's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Genomics
- Healthcare
- Clinical Laboratory
- Whole Genome Sequencing
- Precision Medicine
- Bioinformatics
- Polygenic Risk Scores
- Pharmacogenomics
- Rare Disease
- Diagnostics
- Life Sciences
---
