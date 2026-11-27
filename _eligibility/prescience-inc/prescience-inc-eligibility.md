---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Employers and plan sponsors use Prescience to evaluate, sponsor, administer, fund, and monitor health-benefit programs for eligible employees and dependents.
    type: business
  - text: Members and patients use Prescience to understand benefits, navigate care, connect records, manage permissions, request support, and access services available through their plan.
    type: individual
  - text: Providers and provider organizations use Prescience to participate in network, direct-contract, scheduling, payment, claim, or administrative workflows.
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No employment decisions from health data
    text: Employers may not attempt to identify a member from aggregate reporting or use Prescience to make employment decisions based on individual health information.
  - summary: No marketing use of PHI
    text: Use PHI or personal information for marketing, employment, or non-plan purposes unless expressly permitted by law and written agreements;
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
name: Prescience
provenance_date: '2026-11-10'
provider_name: Prescience
provider_slug: prescience-inc
slug: prescience-inc-eligibility
source_date: '2026-11-10'
source_filename: prescience-inc-eligibility.yml
source_heading: Eligibility
source_page: https://www.getprescience.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prescience\naid: prescience-inc\nurl: https://www.getprescience.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Employers and plan sponsors use Prescience to evaluate, sponsor, administer, fund, and monitor health-benefit\n    programs for eligible employees and dependents.\n- type: individual\n  text: Members and patients use Prescience to understand benefits, navigate care, connect records, manage permissions,\n    request support, and access services available through their plan.\n- type: other\n  text: Providers and provider\
  \ organizations use Prescience to participate in network, direct-contract, scheduling,\n    payment, claim, or administrative workflows.\nrestricted_uses:\n- summary: No employment decisions from health data\n  text: Employers may not attempt to identify a member from aggregate reporting or use Prescience to make employment\n    decisions based on individual health information.\n- summary: No marketing use of PHI\n  text: Use PHI or personal information for marketing, employment, or non-plan purposes unless expressly permitted\n    by law and written agreements;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prescience-inc/eligibility/prescience-inc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Prescience's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health Insurance
- Employee Benefits
- Insurance
- Artificial Intelligence
- Machine Learning
- Startups
- Y Combinator
---
