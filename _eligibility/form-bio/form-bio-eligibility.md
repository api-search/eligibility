---
api_specs:
- filename: form-bio-openapi-generated.yml
  format: yaml
  label: Form Bio API
  slug: form-bio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/form-bio/openapi/_ae-authored/form-bio-openapi-generated.yml
- filename: form-bio-form-bio-api-api-openapi.yml
  format: yaml
  label: Form Bio Form Bio API
  slug: form-bio-form-bio-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/form-bio/openapi/form-bio-form-bio-api-api-openapi.yml
- filename: form-bio-public-api-openapi.yml
  format: yaml
  label: Form Bio Public API
  slug: form-bio-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/form-bio/openapi/form-bio-public-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You represent and warrant that you are: (i) over 18 years of age or the age of majority in your jurisdiction, whichever is greater, and of legal age to form a binding contract'
    type: individual
  minimum_age:
    text: over 18 years of age or the age of majority in your jurisdiction, whichever is greater
    value: '18'
  restricted_uses:
  - summary: Competing product development
    text: access the Site for the purpose of developing, marketing, selling or distributing any product or service that competes with or includes features substantially similar to the Site
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must register for user accounts within the Platform and pay applicable fees for access to and use of the Platform.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Form Bio
provenance_date: '2026-11-09'
provider_name: Form Bio
provider_slug: form-bio
slug: form-bio-eligibility
source_date: '2026-11-09'
source_filename: form-bio-eligibility.yml
source_heading: Eligibility
source_page: https://www.formbio.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Form Bio\naid: form-bio\nurl: https://www.formbio.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'You represent and warrant that you are: (i) over 18 years of age or the age of majority in your jurisdiction,\n    whichever is greater, and of legal age to form a binding contract'\nrestricted_uses:\n- summary: Competing product development\n  text: access the Site for the purpose of developing, marketing, selling or distributing any product or service\n    that competes with or includes features substantially similar\
  \ to the Site\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must register for user accounts within the Platform and pay applicable fees for access to and use of\n    the Platform.\nminimum_age:\n  value: '18'\n  text: over 18 years of age or the age of majority in your jurisdiction, whichever is greater\n"
source_yaml_url: https://artifacts.apis.io/form-bio/eligibility/form-bio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Form Bio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Artificial Intelligence
- Genetic Medicine
- Genome Engineering
---
