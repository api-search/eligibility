---
api_specs:
- filename: anon-li-openapi-generated.yml
  format: yaml
  label: anon.li API
  slug: anon-li-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anon-li/openapi/_ae-authored/anon-li-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years of age to use the Service.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 13 years of age to use the Service.
    value: '13'
  restricted_uses:
  - summary: Illegal content
    text: Uploading or sharing illegal content, including but not limited to child sexual abuse material (CSAM), non-consensual intimate imagery, or terrorist content
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
name: anon.li
provenance_date: '2026-11-09'
provider_name: anon.li
provider_slug: anon-li
slug: anon-li-eligibility
source_date: '2026-11-09'
source_filename: anon-li-eligibility.yml
source_heading: Eligibility
source_page: https://anon.li/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: anon.li\naid: anon-li\nurl: https://anon.li/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age to use the Service.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\nrestricted_uses:\n- summary: Illegal content\n  text: Uploading or sharing illegal content, including but not limited to child sexual abuse material (CSAM), non-consensual\n    intimate imagery, or terrorist\
  \ content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/anon-li/eligibility/anon-li-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from anon.li's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Privacy
- Email
- Encryption
- File Sharing
- Forms
---
