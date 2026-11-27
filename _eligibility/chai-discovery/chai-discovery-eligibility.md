---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
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
name: Chai Discovery
provenance_date: '2026-11-09'
provider_name: Chai Discovery
provider_slug: chai-discovery
slug: chai-discovery-eligibility
source_date: '2026-11-09'
source_filename: chai-discovery-eligibility.yml
source_heading: Eligibility
source_page: https://www.chaidiscovery.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chai Discovery\naid: chai-discovery\nurl: https://www.chaidiscovery.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that entity to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chai-discovery/eligibility/chai-discovery-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Chai Discovery's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Biology
- Structural Biology
- Protein Structure Prediction
- Antibody Design
- Drug Discovery
- Machine Learning
- Bioinformatics
- Artificial Intelligence
---
