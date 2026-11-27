---
api_specs:
- filename: docugami-openapi-generated.yml
  format: yaml
  label: Docugami API
  slug: docugami-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docugami/openapi/_ae-authored/docugami-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with Docugami
    type: individual
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Prohibited content and conduct
    text: 'Post, upload, publish, submit or transmit any Content that: (i) infringes, misappropriates or violates a third party’s patent, copyright, trademark, trade secret, moral rights or other intellectual property rights'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to provide additional information to verify your identity before completing your Transaction
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Docugami
provenance_date: '2026-11-09'
provider_name: Docugami
provider_slug: docugami
slug: docugami-eligibility
source_date: '2026-11-09'
source_filename: docugami-eligibility.yml
source_heading: Eligibility
source_page: https://www.docugami.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Docugami\naid: docugami\nurl: https://www.docugami.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with\n    Docugami\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that company or other legal entity to\n    these Terms.\nrestricted_uses:\n- summary: Prohibited content\
  \ and conduct\n  text: 'Post, upload, publish, submit or transmit any Content that: (i) infringes, misappropriates or violates\n    a third party’s patent, copyright, trademark, trade secret, moral rights or other intellectual property rights'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to provide additional information to verify your identity before completing your Transaction\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/docugami/eligibility/docugami-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Docugami's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Document Automation
- Enterprise
- Contract Management
---
