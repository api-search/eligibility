---
api_specs:
- filename: gcp-cloud-storage-anywherecaches-api-openapi.yml
  format: yaml
  label: Google Cloud Storage Anywhere Caches API
  slug: gcp-cloud-storage-anywherecaches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gcp-cloud-storage/openapi/gcp-cloud-storage-anywherecaches-api-openapi.yml
- filename: gcp-cloud-storage-bucketaccesscontrols-api-openapi.yml
  format: yaml
  label: Google Cloud Storage Bucket Access Controls API
  slug: gcp-cloud-storage-bucketaccesscontrols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gcp-cloud-storage/openapi/gcp-cloud-storage-bucketaccesscontrols-api-openapi.yml
- filename: gcp-cloud-storage-buckets-api-openapi.yml
  format: yaml
  label: Google Cloud Storage Buckets API
  slug: gcp-cloud-storage-buckets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gcp-cloud-storage/openapi/gcp-cloud-storage-buckets-api-openapi.yml
- filename: gcp-cloud-storage-defaultobjectaccesscontrols-api-openapi.yml
  format: yaml
  label: Google Cloud Storage Default Object Access Controls API
  slug: gcp-cloud-storage-defaultobjectaccesscontrols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gcp-cloud-storage/openapi/gcp-cloud-storage-defaultobjectaccesscontrols-api-openapi.yml
- filename: gcp-cloud-storage-folders-api-openapi.yml
  format: yaml
  label: Google Cloud Storage Folders API
  slug: gcp-cloud-storage-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gcp-cloud-storage/openapi/gcp-cloud-storage-folders-api-openapi.yml
- filename: gcp-cloud-storage-managedfolders-api-openapi.yml
  format: yaml
  label: Google Cloud Storage Managed Folders API
  slug: gcp-cloud-storage-managedfolders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gcp-cloud-storage/openapi/gcp-cloud-storage-managedfolders-api-openapi.yml
- filename: gcp-cloud-storage-notifications-api-openapi.yml
  format: yaml
  label: Google Cloud Storage Notifications API
  slug: gcp-cloud-storage-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gcp-cloud-storage/openapi/gcp-cloud-storage-notifications-api-openapi.yml
- filename: gcp-cloud-storage-objectaccesscontrols-api-openapi.yml
  format: yaml
  label: Google Cloud Storage Object Access Controls API
  slug: gcp-cloud-storage-objectaccesscontrols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gcp-cloud-storage/openapi/gcp-cloud-storage-objectaccesscontrols-api-openapi.yml
- filename: gcp-cloud-storage-objects-api-openapi.yml
  format: yaml
  label: Google Cloud Storage Objects API
  slug: gcp-cloud-storage-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gcp-cloud-storage/openapi/gcp-cloud-storage-objects-api-openapi.yml
- filename: gcp-cloud-storage-operations-api-openapi.yml
  format: yaml
  label: Google Cloud Storage Operations API
  slug: gcp-cloud-storage-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gcp-cloud-storage/openapi/gcp-cloud-storage-operations-api-openapi.yml
- filename: gcp-cloud-storage-projects-api-openapi.yml
  format: yaml
  label: Google Cloud Storage Projects API
  slug: gcp-cloud-storage-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gcp-cloud-storage/openapi/gcp-cloud-storage-projects-api-openapi.yml
- filename: gcp-cloud-storage-rapidcaches-api-openapi.yml
  format: yaml
  label: Google Cloud Storage Rapid Caches API
  slug: gcp-cloud-storage-rapidcaches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gcp-cloud-storage/openapi/gcp-cloud-storage-rapidcaches-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - source: https://policies.google.com/terms
    text: If you’re a business user or organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High Risk Activities
    text: access or use the Services or any AI Agent (i) for High Risk Activities;
  - summary: HIPAA health information
    text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except as permitted by an executed HIPAA BAA.
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
name: Google Cloud Storage
provenance_date: '2026-11-09'
provider_name: Google Cloud Storage
provider_slug: gcp-cloud-storage
slug: gcp-cloud-storage-eligibility
source_date: '2026-11-09'
source_filename: gcp-cloud-storage-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud Storage\naid: gcp-cloud-storage\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\n  sources:\n  - https://cloud.google.com/terms\n  - https://policies.google.com/terms\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you’re a business user or organization\n  source: https://policies.google.com/terms\nrestricted_uses:\n- summary: High Risk Activities\n  text: access or use the Services or any AI Agent (i) for High Risk Activities;\n- summary: HIPAA health information\n  text: (ix) to transmit, store, or process health\
  \ information subject to United States HIPAA regulations except\n    as permitted by an executed HIPAA BAA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gcp-cloud-storage/eligibility/gcp-cloud-storage-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Google Cloud Storage's own page on 2026-11-09.
synthetic: false
tags:
- Archival
- Backup
- Blob Storage
- Cloud Storage
- Data
- File Storage
- Google Cloud
- Object Storage
- Storage
---
