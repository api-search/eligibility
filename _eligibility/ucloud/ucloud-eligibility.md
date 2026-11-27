---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old, or above the age of majority for the legal jurisdiction to use the Services.
    type: individual
  - text: If you are an entity, organization, or company, you accept these terms on behalf of the individual and warrant that they have the authority to bind you to these terms
    type: business
  minimum_age:
    text: You must be at least 16 years old, or above the age of majority for the legal jurisdiction to use the Services.
    value: '16'
  restricted_uses:
  - summary: Illegal or harmful content
    text: you shall not use the Services to transmit any information or engage in any activities that is dishonest, defamatory, infringing, tortious, harmful, obscene
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you will complete the real-name authentication of your UCloud-Global account for the purpose of the security of your account and transactions when required by UCloud-Global at any time
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: UCloud
provenance_date: '2026-11-10'
provider_name: UCloud
provider_slug: ucloud
slug: ucloud-eligibility
source_date: '2026-11-10'
source_filename: ucloud-eligibility.yml
source_heading: Eligibility
source_page: https://www.ucloud-global.com/en/docs/agreement/ServicesAgreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UCloud\naid: ucloud\nurl: https://www.ucloud-global.com/en/docs/agreement/ServicesAgreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old, or above the age of majority for the legal jurisdiction to use the Services.\n- type: business\n  text: If you are an entity, organization, or company, you accept these terms on behalf of the individual and warrant\n    that they have the authority to bind you to these terms\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: you shall not use the\
  \ Services to transmit any information or engage in any activities that is dishonest,\n    defamatory, infringing, tortious, harmful, obscene\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you will complete the real-name authentication of your UCloud-Global account for the purpose of the security\n    of your account and transactions when required by UCloud-Global at any time\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old, or above the age of majority for the legal jurisdiction to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/ucloud/eligibility/ucloud-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from UCloud's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Cloud Computing
- Infrastructure-as-a-Service
- GPU
- Kubernetes
- Object Storage
- CDN
- China
---
