---
api_specs:
- filename: finetunedb-openapi-generated.yml
  format: yaml
  label: FinetuneDB API
  slug: finetunedb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finetunedb/openapi/_ae-authored/finetunedb-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: individual
  - text: organizations can create and refine datasets, fine-tune both open-source and proprietary models
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Regulated data (HIPAA, FISMA, GLBA)
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
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
name: FinetuneDB
provenance_date: '2026-11-09'
provider_name: FinetuneDB
provider_slug: finetunedb
slug: finetunedb-eligibility
source_date: '2026-11-09'
source_filename: finetunedb-eligibility.yml
source_heading: Eligibility
source_page: https://finetunedb.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FinetuneDB\naid: finetunedb\nurl: https://finetunedb.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\n- type: business\n  text: organizations can create and refine datasets,\
  \ fine-tune both open-source and proprietary models\nrestricted_uses:\n- summary: Regulated data (HIPAA, FISMA, GLBA)\n  text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/finetunedb/eligibility/finetunedb-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from FinetuneDB's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Platform
- Fine-Tuning
---
