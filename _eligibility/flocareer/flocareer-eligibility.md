---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: apply to individuals who participate in assessments, and interviews
    type: individual
  - text: when you or your organization (“Customer”) access the FloCareer Platform to recruit, evaluate, or otherwise engage with Candidates and FloExperts
    type: business
  - text: FloExperts (Interviewers) — rules for freelance interviewers conducting interviews via FloCareer.
    type: other
  minimum_age:
    text: You must be at least 18 years of age to use the Platform.
    value: '18'
  restricted_uses:
  - summary: Unlawful or infringing use
    text: Use the Platform in any way that is unlawful or infringes third-party rights.
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
name: FloCareer
provenance_date: '2026-11-09'
provider_name: FloCareer
provider_slug: flocareer
slug: flocareer-eligibility
source_date: '2026-11-09'
source_filename: flocareer-eligibility.yml
source_heading: Eligibility
source_page: https://flocareer.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FloCareer\naid: flocareer\nurl: https://flocareer.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: apply to individuals who participate in assessments, and interviews\n- type: business\n  text: when you or your organization (“Customer”) access the FloCareer Platform to recruit, evaluate, or otherwise\n    engage with Candidates and FloExperts\n- type: other\n  text: FloExperts (Interviewers) — rules for freelance interviewers conducting interviews via FloCareer.\nrestricted_uses:\n- summary: Unlawful or infringing use\n\
  \  text: Use the Platform in any way that is unlawful or infringes third-party rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/flocareer/eligibility/flocareer-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from FloCareer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Interview
- Hiring
- Platform
---
