---
api_specs:
- filename: cosmonic-cosmonic-api-api-openapi.yml
  format: yaml
  label: Cosmonic Cosmonic API
  slug: cosmonic-cosmonic-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmonic/openapi/cosmonic-cosmonic-api-api-openapi.yml
- filename: cosmonic-cosmonic-labs-api-openapi.yml
  format: yaml
  label: Cosmonic Cosmonic Labs API
  slug: cosmonic-cosmonic-labs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmonic/openapi/cosmonic-cosmonic-labs-api-openapi.yml
- filename: cosmonic-detect-api-openapi.yml
  format: yaml
  label: Cosmonic Detect API
  slug: cosmonic-detect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmonic/openapi/cosmonic-detect-api-openapi.yml
- filename: cosmonic-error-api-openapi.yml
  format: yaml
  label: Cosmonic Error API
  slug: cosmonic-error-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmonic/openapi/cosmonic-error-api-openapi.yml
- filename: cosmonic-form-api-openapi.yml
  format: yaml
  label: Cosmonic Form API
  slug: cosmonic-form-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmonic/openapi/cosmonic-form-api-openapi.yml
- filename: cosmonic-headers-api-openapi.yml
  format: yaml
  label: Cosmonic Headers API
  slug: cosmonic-headers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmonic/openapi/cosmonic-headers-api-openapi.yml
- filename: cosmonic-myfile-api-openapi.yml
  format: yaml
  label: Cosmonic Myfile API
  slug: cosmonic-myfile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmonic/openapi/cosmonic-myfile-api-openapi.yml
- filename: cosmonic-pkiops-api-openapi.yml
  format: yaml
  label: Cosmonic Pkiops API
  slug: cosmonic-pkiops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmonic/openapi/cosmonic-pkiops-api-openapi.yml
- filename: cosmonic-post-api-openapi.yml
  format: yaml
  label: Cosmonic Post API
  slug: cosmonic-post-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmonic/openapi/cosmonic-post-api-openapi.yml
- filename: cosmonic-workloads-api-openapi.yml
  format: yaml
  label: Cosmonic Workloads API
  slug: cosmonic-workloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmonic/openapi/cosmonic-workloads-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) You are not located in a country that is subject to the United States government embargo
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service, as applicable.
    type: individual
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
    value: '18'
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
name: Cosmonic
provenance_date: '2026-11-09'
provider_name: Cosmonic
provider_slug: cosmonic
slug: cosmonic-eligibility
source_date: '2026-11-09'
source_filename: cosmonic-eligibility.yml
source_heading: Eligibility
source_page: https://cosmonic.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cosmonic\naid: cosmonic\nurl: https://cosmonic.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) You are not located in a country that is subject to the United States\n    government embargo\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service, as applicable.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cosmonic/eligibility/cosmonic-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Cosmonic's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Sandbox
- Cloud
- Platform
- Wasm
---
