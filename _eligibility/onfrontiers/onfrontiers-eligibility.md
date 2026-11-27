---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer- a business or organization that contracts with OnFrontiers under these Terms of Service.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No Controlled Unclassified Information submissions
    text: The Customer will not submit, and will not permit any Authorized User, Client, or Guest to submit, to the Platform or to any Expert any information designated as Controlled Unclassified Information under 32 C.F.R. Part 2002
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: OnFrontiers operates an expert vetting program under which it reviews an Expert’s application, verifies information the Expert provides, conducts background screening
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OnFrontiers
provenance_date: '2026-11-10'
provider_name: OnFrontiers
provider_slug: onfrontiers
slug: onfrontiers-eligibility
source_date: '2026-11-10'
source_filename: onfrontiers-eligibility.yml
source_heading: Eligibility
source_page: https://www.onfrontiers.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OnFrontiers\naid: onfrontiers\nurl: https://www.onfrontiers.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer- a business or organization that contracts with OnFrontiers under these Terms of Service.\nrestricted_uses:\n- summary: No Controlled Unclassified Information submissions\n  text: The Customer will not submit, and will not permit any Authorized User, Client, or Guest to submit, to the\n    Platform or to any Expert any information designated as Controlled Unclassified Information\
  \ under 32 C.F.R.\n    Part 2002\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: OnFrontiers operates an expert vetting program under which it reviews an Expert’s application, verifies\n    information the Expert provides, conducts background screening\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/onfrontiers/eligibility/onfrontiers-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from OnFrontiers's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Expert Network
- Federal Contracting
- GovCon
- Government
- Consulting
- Marketplace
- Knowledge
---
