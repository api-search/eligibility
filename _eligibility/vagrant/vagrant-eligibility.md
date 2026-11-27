---
api_specs:
- filename: vagrant-boxes-api-openapi.yml
  format: yaml
  label: Vagrant Boxes API
  slug: vagrant-boxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vagrant/openapi/vagrant-boxes-api-openapi.yml
- filename: vagrant-providers-api-openapi.yml
  format: yaml
  label: Vagrant Providers API
  slug: vagrant-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vagrant/openapi/vagrant-providers-api-openapi.yml
- filename: vagrant-registries-api-openapi.yml
  format: yaml
  label: Vagrant Registries API
  slug: vagrant-registries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vagrant/openapi/vagrant-registries-api-openapi.yml
- filename: vagrant-search-api-openapi.yml
  format: yaml
  label: Vagrant Search API
  slug: vagrant-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vagrant/openapi/vagrant-search-api-openapi.yml
- filename: vagrant-versions-api-openapi.yml
  format: yaml
  label: Vagrant Versions API
  slug: vagrant-versions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vagrant/openapi/vagrant-versions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We are making the Website available to you for your information and personal use only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal use
    text: 'You may not: use our Website for any illegal purpose;'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to set up an account in order to use some of the features of the Website.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vagrant
provenance_date: '2026-11-10'
provider_name: Vagrant
provider_slug: vagrant
slug: vagrant-eligibility
source_date: '2026-11-10'
source_filename: vagrant-eligibility.yml
source_heading: Eligibility
source_page: https://www.hashicorp.com/en/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vagrant\naid: vagrant\nurl: https://www.hashicorp.com/en/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: We are making the Website available to you for your information and personal use only.\nrestricted_uses:\n- summary: Illegal use\n  text: 'You may not: use our Website for any illegal purpose;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to set up an account in order to use some of the features of the Website.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vagrant/eligibility/vagrant-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Vagrant's own page on 2026-11-10.
synthetic: false
tags:
- DevOps
- Virtualization
- Developer Environments
- Box
- Cloud
- HashiCorp
- Infrastructure
---
