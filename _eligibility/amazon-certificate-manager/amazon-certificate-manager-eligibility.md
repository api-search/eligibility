---
api_specs:
- filename: amazon-certificate-manager-certificates-api-openapi.yml
  format: yaml
  label: Amazon Certificate Manager Certificates API
  slug: amazon-certificate-manager-certificates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-certificate-manager/openapi/amazon-certificate-manager-certificates-api-openapi.yml
- filename: amazon-certificate-manager-acme-account-api-openapi.yml
  format: yaml
  label: Amazon Certificate Manager Certificate Manager Acme Account API
  slug: amazon-certificate-manager-acme-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-certificate-manager/openapi/amazon-certificate-manager-acme-account-api-openapi.yml
- filename: amazon-certificate-manager-acme-domain-validation-api-openapi.yml
  format: yaml
  label: Amazon Certificate Manager Certificate Manager Acme Domain Validation API
  slug: amazon-certificate-manager-acme-domain-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-certificate-manager/openapi/amazon-certificate-manager-acme-domain-validation-api-openapi.yml
- filename: amazon-certificate-manager-acme-endpoint-api-openapi.yml
  format: yaml
  label: Amazon Certificate Manager Certificate Manager Acme Endpoint API
  slug: amazon-certificate-manager-acme-endpoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-certificate-manager/openapi/amazon-certificate-manager-acme-endpoint-api-openapi.yml
- filename: amazon-certificate-manager-acme-external-account-binding-api-openapi.yml
  format: yaml
  label: Amazon Certificate Manager Certificate Manager Acme External Account Binding API
  slug: amazon-certificate-manager-acme-external-account-binding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-certificate-manager/openapi/amazon-certificate-manager-acme-external-account-binding-api-openapi.yml
- filename: amazon-certificate-manager-operations-api-openapi.yml
  format: yaml
  label: Amazon Certificate Manager Certificate Manager Operations API
  slug: amazon-certificate-manager-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-certificate-manager/openapi/amazon-certificate-manager-operations-api-openapi.yml
- filename: amazon-certificate-manager-tag-api-openapi.yml
  format: yaml
  label: Amazon Certificate Manager Certificate Manager Tag API
  slug: amazon-certificate-manager-tag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-certificate-manager/openapi/amazon-certificate-manager-tag-api-openapi.yml
claim_count: 2
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
  - summary: High Risk Use of Microsoft Software
    text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other modes of human mass transportation, nuclear or chemical facilities, life support systems, implantable medical equipment, motor vehicles, weaponry systems, or any similar scenario
  - summary: Spend limits not for critical use
    text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of any hazardous environments or critical systems, any regulated content (such as protected health information), government data, or any content of government entities.
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
name: Amazon Certificate Manager
provenance_date: '2026-11-09'
provider_name: Amazon Certificate Manager
provider_slug: amazon-certificate-manager
slug: amazon-certificate-manager-eligibility
source_date: '2026-11-09'
source_filename: amazon-certificate-manager-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon Certificate Manager\naid: amazon-certificate-manager\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High Risk Use of Microsoft Software\n  text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other\n    modes of human mass transportation, nuclear or chemical facilities, life support systems, implantable medical\n    equipment, motor vehicles, weaponry systems, or any similar scenario\n- summary: Spend limits\
  \ not for critical use\n  text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of\n    any hazardous environments or critical systems, any regulated content (such as protected health information),\n    government data, or any content of government entities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-certificate-manager/eligibility/amazon-certificate-manager-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Amazon Certificate Manager's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Certificates
- Encryption
- Security
- SSL
- TLS
---
