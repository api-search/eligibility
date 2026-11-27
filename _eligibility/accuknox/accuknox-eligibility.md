---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of a company or another legal entity, you represent that you have the authority to bind such entity and its affiliates to these Terms
    type: business
  minimum_age:
    text: The Service is not directed at children. If you are a child, please do not use or attempt to register to use the Service.
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
name: AccuKnox
provenance_date: '2026-11-09'
provider_name: AccuKnox
provider_slug: accuknox
slug: accuknox-eligibility
source_date: '2026-11-09'
source_filename: accuknox-eligibility.yml
source_heading: Eligibility
source_page: https://accuknox.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AccuKnox\naid: accuknox\nurl: https://accuknox.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a company or another legal entity, you represent that\n    you have the authority to bind such entity and its affiliates to these Terms\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is not directed at children. If you are a child, please do not use or attempt to register\
  \ to\n    use the Service.\n"
source_yaml_url: https://artifacts.apis.io/accuknox/eligibility/accuknox-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from AccuKnox's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cloud Security
- Cloud Native Application Protection Platform
- Kubernetes Security
- Runtime Security
- Zero Trust
- DevSecOps
- Compliance
- AI Security
- Vulnerability Management
- Container Security
---
