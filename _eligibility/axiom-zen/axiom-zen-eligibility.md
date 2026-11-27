---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering for an account on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind such entity, its affiliates, and all users who access our Services through such account to these Terms
    type: business
  minimum_age:
    text: null
    value: null
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
name: ZenHub
provenance_date: '2026-11-09'
provider_name: ZenHub
provider_slug: axiom-zen
slug: axiom-zen-eligibility
source_date: '2026-11-09'
source_filename: axiom-zen-eligibility.yml
source_heading: Eligibility
source_page: https://www.zenhub.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZenHub\naid: axiom-zen\nurl: https://www.zenhub.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are registering for an account on behalf of a company or other legal entity, you represent and warrant\n    that you have the authority to bind such entity, its affiliates, and all users who access our Services through\n    such account to these Terms\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/axiom-zen/eligibility/axiom-zen-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from ZenHub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Project Management
- GitHub Integration
- AI Automation
- Enterprise
---
