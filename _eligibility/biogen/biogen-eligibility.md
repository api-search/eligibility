---
api_specs:
- filename: biogen-keys-api-openapi.yml
  format: yaml
  label: Biogen Keys API
  slug: biogen-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biogen/openapi/biogen-keys-api-openapi.yml
- filename: biogen-services-api-openapi.yml
  format: yaml
  label: Biogen Services API
  slug: biogen-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biogen/openapi/biogen-services-api-openapi.yml
- filename: biogen-export-api-openapi.yml
  format: yaml
  label: Biogen Export API
  slug: biogen-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biogen/openapi/biogen-export-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Biogen makes no representation that the information in the website is appropriate or available for use in other locations, and access to the Biogen website from territories where the content of the Biogen website may be illegal is prohibited.
  entity_types:
  - text: By using this website, you represent that you are at least 18 years old and a U.S. resident.
    type: individual
  minimum_age:
    text: By using this website, you represent that you are at least 18 years old and a U.S. resident.
    value: '18'
  restricted_uses:
  - summary: Non-commercial informational use only
    text: Biogen invites you to view, use and download a single copy of this website for your informational, non-commercial use.
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
name: Biogen
provenance_date: '2026-11-09'
provider_name: Biogen
provider_slug: biogen
slug: biogen-eligibility
source_date: '2026-11-09'
source_filename: biogen-eligibility.yml
source_heading: Eligibility
source_page: https://www.biogen.com/terms-and-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Biogen\naid: biogen\nurl: https://www.biogen.com/terms-and-conditions.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Biogen makes no representation that the information in the website is appropriate or available for use in\n    other locations, and access to the Biogen website from territories where the content of the Biogen website may\n    be illegal is prohibited.\nentity_types:\n- type: individual\n  text: By using this website, you represent that you are at least 18 years old and a U.S. resident.\nrestricted_uses:\n- summary: Non-commercial informational use only\n  text:\
  \ Biogen invites you to view, use and download a single copy of this website for your informational, non-commercial\n    use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using this website, you represent that you are at least 18 years old and a U.S. resident.\n"
source_yaml_url: https://artifacts.apis.io/biogen/eligibility/biogen-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Biogen's own page on 2026-11-09.
synthetic: false
tags:
- Biotechnology
- Healthcare
- Life Sciences
- Pharmaceuticals
- Neurology
- Fortune 500
---
