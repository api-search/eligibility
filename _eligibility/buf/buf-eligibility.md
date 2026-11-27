---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company Properties are controlled and offered by Company from its facilities in the United States of America. Company makes no representations that Company Properties are appropriate or available for use in other locations.
  minimum_age:
    text: you are of legal age to form a binding contract with COMPANY
    value: null
  restricted_uses:
  - summary: Violations of laws or misleading accounts
    text: You agree not to create an Account using a false identity or information, or on behalf of someone other than yourself.
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
name: Buf
provenance_date: '2026-11-09'
provider_name: Buf
provider_slug: buf
slug: buf-eligibility
source_date: '2026-11-09'
source_filename: buf-eligibility.yml
source_heading: Eligibility
source_page: https://buf.build/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buf\naid: buf\nurl: https://buf.build/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Company Properties are controlled and offered by Company from its facilities in the United States of America.\n    Company makes no representations that Company Properties are appropriate or available for use in other locations.\nentity_types: []\nrestricted_uses:\n- summary: Violations of laws or misleading accounts\n  text: You agree not to create an Account using a false identity or information, or on behalf of someone other\n    than yourself.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age to form a binding contract with COMPANY\n"
source_yaml_url: https://artifacts.apis.io/buf/eligibility/buf-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Buf's own page on 2026-11-09.
synthetic: false
tags:
- Code Generation
- gRPC
- Kafka
- Open Source
- Protocol Buffers
- Schema Registry
- SDK
- Streaming
---
