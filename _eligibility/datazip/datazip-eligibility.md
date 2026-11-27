---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You affirm that You are either more than 18 years of age and are fully able and competent to enter into the terms
    type: individual
  - text: If You are entering into these Terms on behalf of an entity, organization, or company (a "Subscribing Organization"), You represent and warrant that You have the authority to bind such Subscribing Organization
    type: business
  minimum_age:
    text: You affirm that You are either more than 18 years of age
    value: '18'
  restricted_uses:
  - summary: Sensitive information
    text: You shall not use the Services for such purposes or under such circumstances or to process or store Sensitive Information.
  - summary: Competing use
    text: use or apply, directly or indirectly, the Services in any manner competitive with the business of Datazip
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
name: Datazip, Inc.
provenance_date: '2026-11-09'
provider_name: Datazip, Inc.
provider_slug: datazip
slug: datazip-eligibility
source_date: '2026-11-09'
source_filename: datazip-eligibility.yml
source_heading: Eligibility
source_page: https://olake.io/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Datazip, Inc.\naid: datazip\nurl: https://olake.io/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You affirm that You are either more than 18 years of age and are fully able and competent to enter into\n    the terms\n- type: business\n  text: If You are entering into these Terms on behalf of an entity, organization, or company (a \"Subscribing Organization\"),\n    You represent and warrant that You have the authority to bind such Subscribing Organization\nrestricted_uses:\n- summary: Sensitive information\n  text:\
  \ You shall not use the Services for such purposes or under such circumstances or to process or store Sensitive\n    Information.\n- summary: Competing use\n  text: use or apply, directly or indirectly, the Services in any manner competitive with the business of Datazip\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You affirm that You are either more than 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/datazip/eligibility/datazip-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Datazip, Inc.'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Engineering
- Open Source
- Apache Iceberg
- Data Platform
---
