---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents and warrants that it is not located in (or a national of) a country that either is subject to a U.S. government embargo or has been designated by the U.S. government as a "state sponsor of terrorism".
  entity_types:
  - text: If you are using any RelationalAI Offerings as an employee, contractor, or agent of a corporation, partnership or similar entity, then you must be authorized to sign for and bind such entity
    type: business
  - text: To the extent Customer is an agency of or otherwise represents the United States federal government
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: HIPAA data
    text: Customer agrees not to process any HIPAA Data in the Service unless Customer has entered into a BAA with RelationalAI.
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
name: RelationalAI
provenance_date: '2026-11-10'
provider_name: RelationalAI
provider_slug: relationalai
slug: relationalai-eligibility
source_date: '2026-11-10'
source_filename: relationalai-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.prod.website-files.com/68c66131e7dc76329c719913/68d6bfd57445ffd406a54fec_relationalai-tos.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RelationalAI\naid: relationalai\nurl: https://cdn.prod.website-files.com/68c66131e7dc76329c719913/68d6bfd57445ffd406a54fec_relationalai-tos.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents and warrants that it is not located in (or a national of) a country that either is subject\n    to a U.S. government embargo or has been designated by the U.S. government as a \"state sponsor of terrorism\".\nentity_types:\n- type: business\n  text: If you are using any RelationalAI Offerings as an employee, contractor, or agent of a corporation, partnership\n    or similar\
  \ entity, then you must be authorized to sign for and bind such entity\n- type: government\n  text: To the extent Customer is an agency of or otherwise represents the United States federal government\nrestricted_uses:\n- summary: HIPAA data\n  text: Customer agrees not to process any HIPAA Data in the Service unless Customer has entered into a BAA with\n    RelationalAI.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/relationalai/eligibility/relationalai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from RelationalAI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Decision Intelligence
- Knowledge Graph
- Semantic Layer
- Snowflake
- Graph Analytics
- Machine Learning
- Optimization
- Reasoning
- Artificial Intelligence
---
