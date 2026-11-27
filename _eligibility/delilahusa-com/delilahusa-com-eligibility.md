---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: By using the Platform, you represent and warrant that you are at least 13 years old and are located in, or a resident of, the United States of America.
  entity_types:
  - text: You must be at least thirteen (13) years of age to use the Platform.
    type: individual
  - text: If you are accepting these Terms on behalf of a company, organization, or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be at least thirteen (13) years of age to use the Platform.
    value: '13'
  restricted_uses:
  - summary: Competitive use restriction
    text: You agree that during the period of your use of the Platform and for a period of two (2) years following the termination of your account, you will not use any knowledge, information, or insights gained from the Platform to directly or indirectly develop, design, build, market, operate, or contribute to any product or service that competes with or is substantially similar to any aspect of the Platform.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Delilah reserves the right to refuse service, terminate accounts, or restrict access to the Platform at our sole discretion if we believe any eligibility requirement is not met.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Delilah
provenance_date: '2026-11-09'
provider_name: Delilah
provider_slug: delilahusa-com
slug: delilahusa-com-eligibility
source_date: '2026-11-09'
source_filename: delilahusa-com-eligibility.yml
source_heading: Eligibility
source_page: https://delilahusa.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Delilah\naid: delilahusa-com\nurl: https://delilahusa.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: By using the Platform, you represent and warrant that you are at least 13 years old and are located in,\n    or a resident of, the United States of America.\nentity_types:\n- type: individual\n  text: You must be at least thirteen (13) years of age to use the Platform.\n- type: business\n  text: If you are accepting these Terms on behalf of a company, organization, or other legal entity, you represent\n    and warrant that you have the authority to bind that entity\
  \ to these Terms\nrestricted_uses:\n- summary: Competitive use restriction\n  text: You agree that during the period of your use of the Platform and for a period of two (2) years following\n    the termination of your account, you will not use any knowledge, information, or insights gained from the Platform\n    to directly or indirectly develop, design, build, market, operate, or contribute to any product or service that\n    competes with or is substantially similar to any aspect of the Platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Delilah reserves the right to refuse service, terminate accounts, or restrict access to the Platform at\n    our sole discretion if we believe any eligibility requirement is not met.\nminimum_age:\n  value: '13'\n  text: You must be at least thirteen (13) years of age to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/delilahusa-com/eligibility/delilahusa-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Delilah's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legislation
- Government
- Civic Technology
- Artificial Intelligence
- Policy
- MCP
- Public Data
---
