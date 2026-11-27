---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: the Helix Platform may not be used, transferred or otherwise exported or re-exported to countries as to which the United States, maintains an embargo
  entity_types:
  - text: “Personal Use” is the use by an individual developer for personal use to develop free or paid applications
    type: individual
  - text: a “Small Business Environment” is a commercial undertaking with fewer than 250 employees and less than US $10,000,000 (or equivalent local currency) in annual revenue
    type: business
  - text: with the exception of Educational Use, Government Entities are prohibited from using the Helix Platform at the level of the Personal Offering
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Safety-critical or mission-critical deployments
    text: the Helix Platform should not be used as the basis to deploy systems that must be hardened or highly secure, or involve mission-critical business operations
  - summary: Export-restricted use
    text: may not be used, transferred or otherwise exported or re-exported to countries as to which the United States, maintains an embargo
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
name: HelixML
provenance_date: '2026-11-09'
provider_name: HelixML
provider_slug: helix-ml
slug: helix-ml-eligibility
source_date: '2026-11-09'
source_filename: helix-ml-eligibility.yml
source_heading: Eligibility
source_page: https://helix.ml/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HelixML\naid: helix-ml\nurl: https://helix.ml/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: the Helix Platform may not be used, transferred or otherwise exported or re-exported to countries as to\n    which the United States, maintains an embargo\nentity_types:\n- type: individual\n  text: “Personal Use” is the use by an individual developer for personal use to develop free or paid applications\n- type: business\n  text: a “Small Business Environment” is a commercial undertaking with fewer than 250 employees and less than US\n    $10,000,000 (or equivalent local\
  \ currency) in annual revenue\n- type: government\n  text: with the exception of Educational Use, Government Entities are prohibited from using the Helix Platform\n    at the level of the Personal Offering\nrestricted_uses:\n- summary: Safety-critical or mission-critical deployments\n  text: the Helix Platform should not be used as the basis to deploy systems that must be hardened or highly secure,\n    or involve mission-critical business operations\n- summary: Export-restricted use\n  text: may not be used, transferred or otherwise exported or re-exported to countries as to which the United States,\n    maintains an embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/helix-ml/eligibility/helix-ml-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 6 quoted statements, read from HelixML's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agent Virtualization
- Security
- Cloud
---
