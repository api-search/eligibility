---
api_specs:
- filename: upsie-authorization-api-openapi.yml
  format: yaml
  label: Upsie Authorization API
  slug: upsie-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upsie/openapi/upsie-authorization-api-openapi.yml
- filename: upsie-repair-assignments-repairassignments-api-openapi.yml
  format: yaml
  label: Upsie Repair Assignments (/repairassignments) API
  slug: upsie-repair-assignments-repairassignments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upsie/openapi/upsie-repair-assignments-repairassignments-api-openapi.yml
- filename: upsie-repair-categories-api-openapi.yml
  format: yaml
  label: Upsie Repair Categories API
  slug: upsie-repair-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upsie/openapi/upsie-repair-categories-api-openapi.yml
- filename: upsie-repair-item-templates-api-openapi.yml
  format: yaml
  label: Upsie Repair Item Templates API
  slug: upsie-repair-item-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upsie/openapi/upsie-repair-item-templates-api-openapi.yml
- filename: upsie-repair-items-repairitems-api-openapi.yml
  format: yaml
  label: Upsie Repair Items (/repairitems) API
  slug: upsie-repair-items-repairitems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upsie/openapi/upsie-repair-items-repairitems-api-openapi.yml
- filename: upsie-repair-notes-api-openapi.yml
  format: yaml
  label: Upsie Repair Notes API
  slug: upsie-repair-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upsie/openapi/upsie-repair-notes-api-openapi.yml
- filename: upsie-repairs-repairs-api-openapi.yml
  format: yaml
  label: Upsie Repairs (/repairs) API
  slug: upsie-repairs-repairs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upsie/openapi/upsie-repairs-repairs-api-openapi.yml
- filename: upsie-webhooks-api-openapi.yml
  format: yaml
  label: Upsie Webhooks API
  slug: upsie-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upsie/openapi/upsie-webhooks-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have the permission of, and be directly supervised by, their parent or guardian to use the Site.
    type: individual
  - text: These Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have the permission of, and be directly supervised by, their parent or guardian to use the Site.
    value: '18'
  restricted_uses:
  - summary: Regulated data uses
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Upsie
provenance_date: '2026-11-10'
provider_name: Upsie
provider_slug: upsie
slug: upsie-eligibility
source_date: '2026-11-10'
source_filename: upsie-eligibility.yml
source_heading: Eligibility
source_page: https://app.termly.io/policy-viewer/policy.html?policyUUID=e4aa24cb-f6f6-4ebd-95bc-5e963adcacb1
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Upsie\naid: upsie\nurl: https://app.termly.io/policy-viewer/policy.html?policyUUID=e4aa24cb-f6f6-4ebd-95bc-5e963adcacb1\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have\n    the permission of, and be directly supervised by, their\
  \ parent or guardian to use the Site.\n- type: business\n  text: These Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: Regulated data uses\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with the Site.\nminimum_age:\n  value: '18'\n  text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have\n    the permission of, and be directly supervised by, their parent or guardian to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/upsie/eligibility/upsie-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Upsie's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Warranties
- Protection-Plans
- Consumer Electronics
- Repairs
- Insurance
---
