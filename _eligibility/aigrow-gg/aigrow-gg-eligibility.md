---
api_specs:
- filename: aigrow-gg-openapi-generated.yml
  format: yaml
  label: AIGROW API
  slug: aigrow-gg-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aigrow-gg/openapi/_ae-authored/aigrow-gg-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use, export or re-export the Services in breach of US sanctions or export control laws, or of those of other countries that apply. You confirm that you are not located in, organised under the laws of, or ordinarily resident in a country or region subject to comprehensive US sanctions
  entity_types:
  - text: AIGROW is built and sold for businesses and professionals.
    type: business
  - text: Consumers may also buy from us.
    type: individual
  minimum_age:
    text: you are at least 18 years old, or the age of majority where you live if that is higher
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties and countries
    text: You confirm that you are not located in, organised under the laws of, or ordinarily resident in a country or region subject to comprehensive US sanctions
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may refuse to open an account or to accept an order for a legitimate reason, for example suspected fraud or abuse, an earlier breach of the Agreement, sanctions, or a request outside what we offer.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AIGROW
provenance_date: '2026-11-09'
provider_name: AIGROW
provider_slug: aigrow-gg
slug: aigrow-gg-eligibility
source_date: '2026-11-09'
source_filename: aigrow-gg-eligibility.yml
source_heading: Eligibility
source_page: https://aigrow.gg/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIGROW\naid: aigrow-gg\nurl: https://aigrow.gg/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use, export or re-export the Services in breach of US sanctions or export control laws, or of\n    those of other countries that apply. You confirm that you are not located in, organised under the laws of, or\n    ordinarily resident in a country or region subject to comprehensive US sanctions\nentity_types:\n- type: business\n  text: AIGROW is built and sold for businesses and professionals.\n- type: individual\n  text: Consumers may also buy from us.\nrestricted_uses:\n\
  - summary: Sanctioned parties and countries\n  text: You confirm that you are not located in, organised under the laws of, or ordinarily resident in a country\n    or region subject to comprehensive US sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may refuse to open an account or to accept an order for a legitimate reason, for example suspected fraud\n    or abuse, an earlier breach of the Agreement, sanctions, or a request outside what we offer.\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old, or the age of majority where you live if that is higher\n"
source_yaml_url: https://artifacts.apis.io/aigrow-gg/eligibility/aigrow-gg-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from AIGROW's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- SEO
- Automation
- Growth
- Company
---
