---
api_specs:
- filename: conversion-audiences-api-openapi.yml
  format: yaml
  label: Conversion Audiences API
  slug: conversion-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-audiences-api-openapi.yml
- filename: conversion-campaigns-api-openapi.yml
  format: yaml
  label: Conversion Campaigns API
  slug: conversion-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-campaigns-api-openapi.yml
- filename: conversion-contacts-api-openapi.yml
  format: yaml
  label: Conversion Contacts API
  slug: conversion-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-contacts-api-openapi.yml
- filename: conversion-custom-objects-api-openapi.yml
  format: yaml
  label: Conversion Custom Objects API
  slug: conversion-custom-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-custom-objects-api-openapi.yml
- filename: conversion-events-api-openapi.yml
  format: yaml
  label: Conversion Events API
  slug: conversion-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-events-api-openapi.yml
- filename: conversion-exports-api-openapi.yml
  format: yaml
  label: Conversion Exports API
  slug: conversion-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-exports-api-openapi.yml
- filename: conversion-fields-api-openapi.yml
  format: yaml
  label: Conversion Fields API
  slug: conversion-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-fields-api-openapi.yml
- filename: conversion-forms-api-openapi.yml
  format: yaml
  label: Conversion Forms API
  slug: conversion-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-forms-api-openapi.yml
- filename: conversion-full-delete-api-openapi.yml
  format: yaml
  label: Conversion Full Delete API
  slug: conversion-full-delete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-full-delete-api-openapi.yml
- filename: conversion-workflows-api-openapi.yml
  format: yaml
  label: Conversion Workflows API
  slug: conversion-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-workflows-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You represent and warrant that you are at least eighteen years of age and have the legal capacity to enter into these Terms.
    value: '18'
  restricted_uses:
  - summary: Special category data and PHI
    text: Conversion does not intentionally collect or process special category data and prohibits customers from uploading such information unless expressly authorized in writing via a separate amendment to the DPA or MSA.
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
name: Conversion
provenance_date: '2026-11-09'
provider_name: Conversion
provider_slug: conversion
slug: conversion-eligibility
source_date: '2026-11-09'
source_filename: conversion-eligibility.yml
source_heading: Eligibility
source_page: https://conversion.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conversion\naid: conversion\nurl: https://conversion.ai/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of an organization, you represent and warrant that you have\n    the authority to bind that organization to these Terms\nrestricted_uses:\n- summary: Special category data and PHI\n  text: Conversion does not intentionally collect or process special category data and prohibits customers from\n    uploading such information unless expressly authorized in writing via a\
  \ separate amendment to the DPA or MSA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least eighteen years of age and have the legal capacity to enter\n    into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/conversion/eligibility/conversion-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Conversion's own page on 2026-11-09.
synthetic: false
tags:
- Marketing
- Automation
- Artificial Intelligence
- B2B
- Software-as-a-Service
- Platform
---
