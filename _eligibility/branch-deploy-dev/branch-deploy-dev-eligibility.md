---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: BranchDeploy is intended for use by businesses in the course of their trade or profession.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Other organisations' subscriptions
    text: Use a single Pro subscription in Azure DevOps organisations other than the one its workspace is linked to.
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
name: BranchDeploy
provenance_date: '2026-11-09'
provider_name: BranchDeploy
provider_slug: branch-deploy-dev
slug: branch-deploy-dev-eligibility
source_date: '2026-11-09'
source_filename: branch-deploy-dev-eligibility.yml
source_heading: Eligibility
source_page: https://branch-deploy.dev/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BranchDeploy\naid: branch-deploy-dev\nurl: https://branch-deploy.dev/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: BranchDeploy is intended for use by businesses in the course of their trade or profession.\nrestricted_uses:\n- summary: Other organisations' subscriptions\n  text: Use a single Pro subscription in Azure DevOps organisations other than the one its workspace is linked to.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/branch-deploy-dev/eligibility/branch-deploy-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from BranchDeploy's own page on 2026-11-09.
synthetic: false
tags:
- Software-as-a-Service
- Microsoft Azure
- DevOps
- Deployment
- Automation
---
