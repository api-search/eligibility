---
api_specs:
- filename: ethernovia-audit-user-trail-api-openapi.yml
  format: yaml
  label: Ethernovia Audit User Trail API
  slug: ethernovia-audit-user-trail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-audit-user-trail-api-openapi.yml
- filename: ethernovia-ec-document-api-openapi.yml
  format: yaml
  label: Ethernovia Ec Document API
  slug: ethernovia-ec-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-ec-document-api-openapi.yml
- filename: ethernovia-ec-document-type-api-openapi.yml
  format: yaml
  label: Ethernovia Ec Document Type API
  slug: ethernovia-ec-document-type-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-ec-document-type-api-openapi.yml
- filename: ethernovia-ec-excluded-domain-api-openapi.yml
  format: yaml
  label: Ethernovia Ec Excluded Domain API
  slug: ethernovia-ec-excluded-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-ec-excluded-domain-api-openapi.yml
- filename: ethernovia-ec-group-api-openapi.yml
  format: yaml
  label: Ethernovia Ec Group API
  slug: ethernovia-ec-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-ec-group-api-openapi.yml
- filename: ethernovia-ec-product-api-openapi.yml
  format: yaml
  label: Ethernovia Ec Product API
  slug: ethernovia-ec-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-ec-product-api-openapi.yml
- filename: ethernovia-ec-product-category-api-openapi.yml
  format: yaml
  label: Ethernovia Ec Product Category API
  slug: ethernovia-ec-product-category-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-ec-product-category-api-openapi.yml
- filename: ethernovia-ec-product-family-api-openapi.yml
  format: yaml
  label: Ethernovia Ec Product Family API
  slug: ethernovia-ec-product-family-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-ec-product-family-api-openapi.yml
- filename: ethernovia-ec-send-alert-email-api-openapi.yml
  format: yaml
  label: Ethernovia Ec Send Alert Email API
  slug: ethernovia-ec-send-alert-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-ec-send-alert-email-api-openapi.yml
- filename: ethernovia-ec-software-package-api-openapi.yml
  format: yaml
  label: Ethernovia Ec Software Package API
  slug: ethernovia-ec-software-package-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-ec-software-package-api-openapi.yml
- filename: ethernovia-ec-status-api-openapi.yml
  format: yaml
  label: Ethernovia Ec Status API
  slug: ethernovia-ec-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-ec-status-api-openapi.yml
- filename: ethernovia-my-download-api-openapi.yml
  format: yaml
  label: Ethernovia My Download API
  slug: ethernovia-my-download-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-my-download-api-openapi.yml
- filename: ethernovia-upload-file-api-openapi.yml
  format: yaml
  label: Ethernovia Upload - File API
  slug: ethernovia-upload-file-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-upload-file-api-openapi.yml
- filename: ethernovia-users-permissions-auth-api-openapi.yml
  format: yaml
  label: Ethernovia Users-Permissions - Auth API
  slug: ethernovia-users-permissions-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-users-permissions-auth-api-openapi.yml
- filename: ethernovia-users-permissions-users-roles-api-openapi.yml
  format: yaml
  label: Ethernovia Users-Permissions - Users & Roles API
  slug: ethernovia-users-permissions-users-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ethernovia/openapi/ethernovia-users-permissions-users-roles-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Section 3.2(n) bars use by persons barred from such use under the laws of the United States or of any other jurisdiction. Section 11.3 prohibits use or export to U.S. sanctioned or embargoed countries.
  minimum_age:
    text: You must be at least 18 years old or the applicable age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Competitors excluded
    text: You must not be a competitor of Ethernovia or otherwise access or use the Services (or any part thereof) for the purpose of developing competitive products or services
  - summary: Previously removed users excluded
    text: You must not have been previously removed, terminated, or suspended from accessing or using the Services
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: To access and/or use the Customer Portal, you must have a mutually executed NDA in place with Ethernovia.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ethernovia
provenance_date: '2026-11-09'
provider_name: Ethernovia
provider_slug: ethernovia
slug: ethernovia-eligibility
source_date: '2026-11-09'
source_filename: ethernovia-eligibility.yml
source_heading: Eligibility
source_page: https://www.ethernovia.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ethernovia\naid: ethernovia\nurl: https://www.ethernovia.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Section 3.2(n) bars use by persons barred from such use under the laws of the United States or of any other\n    jurisdiction. Section 11.3 prohibits use or export to U.S. sanctioned or embargoed countries.\nentity_types: []\nrestricted_uses:\n- summary: Competitors excluded\n  text: You must not be a competitor of Ethernovia or otherwise access or use the Services (or any part thereof)\n    for the purpose of developing competitive products or services\n- summary:\
  \ Previously removed users excluded\n  text: You must not have been previously removed, terminated, or suspended from accessing or using the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: To access and/or use the Customer Portal, you must have a mutually executed NDA in place with Ethernovia.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or the applicable age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/ethernovia/eligibility/ethernovia-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Ethernovia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Semiconductors
- Automotive
- Ethernet
- Networking
- Hardware
- Robotics
- Artificial Intelligence
- Autonomous Vehicles
- Physical AI
---
