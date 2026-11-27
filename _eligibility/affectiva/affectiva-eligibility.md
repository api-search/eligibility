---
api_specs:
- filename: affectiva-annotations-api-openapi.yml
  format: yaml
  label: Affectiva Annotations API
  slug: affectiva-annotations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affectiva/openapi/affectiva-annotations-api-openapi.yml
- filename: affectiva-data-collection-projects-api-openapi.yml
  format: yaml
  label: Affectiva data collection projects API
  slug: affectiva-data-collection-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affectiva/openapi/affectiva-data-collection-projects-api-openapi.yml
- filename: affectiva-entries-api-openapi.yml
  format: yaml
  label: Affectiva Entries API
  slug: affectiva-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affectiva/openapi/affectiva-entries-api-openapi.yml
- filename: affectiva-event-configs-api-openapi.yml
  format: yaml
  label: Affectiva event configs API
  slug: affectiva-event-configs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affectiva/openapi/affectiva-event-configs-api-openapi.yml
- filename: affectiva-event-instances-api-openapi.yml
  format: yaml
  label: Affectiva event instances API
  slug: affectiva-event-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affectiva/openapi/affectiva-event-instances-api-openapi.yml
- filename: affectiva-frame-sampling-jobs-api-openapi.yml
  format: yaml
  label: Affectiva frame sampling jobs API
  slug: affectiva-frame-sampling-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affectiva/openapi/affectiva-frame-sampling-jobs-api-openapi.yml
- filename: affectiva-jobs-api-openapi.yml
  format: yaml
  label: Affectiva Jobs API
  slug: affectiva-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affectiva/openapi/affectiva-jobs-api-openapi.yml
- filename: affectiva-labeling-job-annotations-api-openapi.yml
  format: yaml
  label: Affectiva Labeling Job Annotations API
  slug: affectiva-labeling-job-annotations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affectiva/openapi/affectiva-labeling-job-annotations-api-openapi.yml
- filename: affectiva-labeling-jobs-api-openapi.yml
  format: yaml
  label: Affectiva Labeling Jobs API
  slug: affectiva-labeling-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affectiva/openapi/affectiva-labeling-jobs-api-openapi.yml
- filename: affectiva-labeling-tasks-api-openapi.yml
  format: yaml
  label: Affectiva Labeling Tasks API
  slug: affectiva-labeling-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affectiva/openapi/affectiva-labeling-tasks-api-openapi.yml
- filename: affectiva-representation-storages-api-openapi.yml
  format: yaml
  label: Affectiva representation storages API
  slug: affectiva-representation-storages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affectiva/openapi/affectiva-representation-storages-api-openapi.yml
- filename: affectiva-representations-api-openapi.yml
  format: yaml
  label: Affectiva Representations API
  slug: affectiva-representations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affectiva/openapi/affectiva-representations-api-openapi.yml
- filename: affectiva-video-frames-api-openapi.yml
  format: yaml
  label: Affectiva Video Frames API
  slug: affectiva-video-frames-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affectiva/openapi/affectiva-video-frames-api-openapi.yml
- filename: affectiva-video-segments-api-openapi.yml
  format: yaml
  label: Affectiva Video Segments API
  slug: affectiva-video-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affectiva/openapi/affectiva-video-segments-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The individual who is using the Products, or who is registered with Affectiva, or has provided Affectiva with their credit card or alternative payment mechanism for the Products.
    type: individual
  minimum_age:
    text: If you are a parent or legal guardian entering into this Agreement for use of the Products by your child, you agree that your child is at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Not for medical diagnosis
    text: our Products are not intended to be used in the diagnosis of disease or to treat, cure or prevent any disease.
  - summary: Not for hazardous environments
    text: the Products are not designed or licensed for use in hazardous environments requiring fail-safe controls, including without limitation operation of nuclear facilities, aircraft navigation/communication systems, air traffic control, and life support or weapons systems.
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
name: Affectiva
provenance_date: '2026-11-09'
provider_name: Affectiva
provider_slug: affectiva
slug: affectiva-eligibility
source_date: '2026-11-09'
source_filename: affectiva-eligibility.yml
source_heading: Eligibility
source_page: https://www.affectiva.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Affectiva\naid: affectiva\nurl: https://www.affectiva.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The individual who is using the Products, or who is registered with Affectiva, or has provided Affectiva\n    with their credit card or alternative payment mechanism for the Products.\nrestricted_uses:\n- summary: Not for medical diagnosis\n  text: our Products are not intended to be used in the diagnosis of disease or to treat, cure or prevent any disease.\n- summary: Not for hazardous environments\n  text: the\
  \ Products are not designed or licensed for use in hazardous environments requiring fail-safe controls,\n    including without limitation operation of nuclear facilities, aircraft navigation/communication systems, air\n    traffic control, and life support or weapons systems.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are a parent or legal guardian entering into this Agreement for use of the Products by your child,\n    you agree that your child is at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/affectiva/eligibility/affectiva-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Affectiva's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Emotion AI
- Artificial Intelligence
- Machine Learning
- Computer Vision
- Facial Coding
- Facial Expression Analysis
- Media Analytics
- Market Research
- Automotive
- Driver Monitoring
- Video Analysis
---
