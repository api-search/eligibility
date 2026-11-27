---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per individual. Account sharing is not permitted.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service. If you are between 13 and 18, you must have the consent of a parent or legal guardian.
    value: '13'
  restricted_uses:
  - summary: Unlawful or infringing content
    text: Upload content that is illegal, harmful, or infringes on third-party rights.
  - summary: Impersonation
    text: Impersonate another person or entity, or misrepresent your affiliation.
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
name: Adviserry
provenance_date: '2026-11-09'
provider_name: Adviserry
provider_slug: adviserry-com
slug: adviserry-com-eligibility
source_date: '2026-11-09'
source_filename: adviserry-com-eligibility.yml
source_heading: Eligibility
source_page: https://adviserry.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adviserry\naid: adviserry-com\nurl: https://adviserry.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account per individual. Account sharing is not permitted.\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: Upload content that is illegal, harmful, or infringes on third-party rights.\n- summary: Impersonation\n  text: Impersonate another person or entity, or misrepresent your affiliation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n\
  \  text: You must be at least 13 years old to use the Service. If you are between 13 and 18, you must have the consent\n    of a parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/adviserry-com/eligibility/adviserry-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Adviserry's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Advisory
- Newsletters
- Knowledge Base
- Productivity
- Automation
---
