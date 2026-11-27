---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you access the Sites on behalf of a legal entity, to that entity.
    type: business
  minimum_age:
    text: BY ACCESSING OR USING ANY OF THE SITES, YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Third-party apps and competition
    text: Develop any third-party applications that interact with the Sites or Content without our prior written consent.
  - summary: Competitive use
    text: Use or apply the Sites in any manner directly or indirectly competitive with any business of Databricks.
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
name: Databricks Asset Bundles
provenance_date: '2026-11-09'
provider_name: Databricks Asset Bundles
provider_slug: databricks-asset-bundles
slug: databricks-asset-bundles-eligibility
source_date: '2026-11-09'
source_filename: databricks-asset-bundles-eligibility.yml
source_heading: Eligibility
source_page: https://www.databricks.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Databricks Asset Bundles\naid: databricks-asset-bundles\nurl: https://www.databricks.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you access the Sites on behalf of a legal entity, to that entity.\nrestricted_uses:\n- summary: Third-party apps and competition\n  text: Develop any third-party applications that interact with the Sites or Content without our prior written consent.\n- summary: Competitive use\n  text: Use or apply the Sites in any manner directly or indirectly competitive with any business of\
  \ Databricks.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: BY ACCESSING OR USING ANY OF THE SITES, YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/databricks-asset-bundles/eligibility/databricks-asset-bundles-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Databricks Asset Bundles's own page on 2026-11-09.
synthetic: false
tags:
- CI/CD
- Data Engineering
- Databricks
- Deployment
- Infrastructure as Code
- Job
- Machine Learning
- MLOps
- Pipelines
- Workflows
---
