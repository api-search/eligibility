---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a territory that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist supporting" country
  entity_types:
  - text: You must be at least 18 years of age to use the Service.
    type: individual
  - text: If you are using the Service on behalf of an entity, organization, or company, you represent and warrant that you have the authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: No emergency calls
    text: the Service is not intended to support or carry emergency calls to any emergency services such as public safety answering points
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access most features of the Service, you must register for an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: UJET
provenance_date: '2026-11-10'
provider_name: UJET
provider_slug: ujet
slug: ujet-eligibility
source_date: '2026-11-10'
source_filename: ujet-eligibility.yml
source_heading: Eligibility
source_page: https://ujet.cx/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UJET\naid: ujet\nurl: https://ujet.cx/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a territory that is subject to a U.S. Government embargo, or that has been designated\n    by the U.S. Government as a \"terrorist supporting\" country\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Service.\n- type: business\n  text: If you are using the Service on behalf of an entity, organization, or company, you represent and warrant\n    that you have the authority to bind that organization to these Terms\n\
  restricted_uses:\n- summary: No emergency calls\n  text: the Service is not intended to support or carry emergency calls to any emergency services such as public\n    safety answering points\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access most features of the Service, you must register for an account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/ujet/eligibility/ujet-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from UJET's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Contact Center
- CCaaS
- Customer Experience
- Artificial Intelligence
- Voice
- Messaging
- Support
---
