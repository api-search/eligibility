---
api_specs:
- filename: pypi-downloads-api-openapi.yml
  format: yaml
  label: PyPI Downloads API
  slug: pypi-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pypi/openapi/pypi-downloads-api-openapi.yml
- filename: pypi-projects-api-openapi.yml
  format: yaml
  label: PyPI Projects API
  slug: pypi-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pypi/openapi/pypi-projects-api-openapi.yml
- filename: pypi-provenance-api-openapi.yml
  format: yaml
  label: PyPI Provenance API
  slug: pypi-provenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pypi/openapi/pypi-provenance-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export controls and embargoed users
    text: I represent and warrant that I have complied with all government regulations concerning the transfer or export of any Content I upload to PyPI.
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
name: PyPI
provenance_date: '2026-11-10'
provider_name: PyPI
provider_slug: pypi
slug: pypi-eligibility
source_date: '2026-11-10'
source_filename: pypi-eligibility.yml
source_heading: Eligibility
source_page: https://policies.python.org/pypi.org/Terms-of-Use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PyPI\naid: pypi\nurl: https://policies.python.org/pypi.org/Terms-of-Use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export controls and embargoed users\n  text: I represent and warrant that I have complied with all government regulations concerning the transfer or\n    export of any Content I upload to PyPI.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pypi/eligibility/pypi-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from PyPI's own page on 2026-11-10.
synthetic: false
tags:
- Developer Tools
- Open Source
- Package Management
- Packages
- Python
---
