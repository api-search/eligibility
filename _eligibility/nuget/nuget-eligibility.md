---
api_specs:
- filename: nuget-package-publish-api-openapi.yml
  format: yaml
  label: NuGet Package Publish API
  slug: nuget-package-publish-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuget/openapi/nuget-package-publish-api-openapi.yml
- filename: nuget-registration-api-openapi.yml
  format: yaml
  label: NuGet Registration API
  slug: nuget-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuget/openapi/nuget-registration-api-openapi.yml
- filename: nuget-service-index-api-openapi.yml
  format: yaml
  label: NuGet Service Index API
  slug: nuget-service-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuget/openapi/nuget-service-index-api-openapi.yml
- filename: nuget-autocomplete-api-openapi.yml
  format: yaml
  label: Microsoft NuGet Autocomplete API
  slug: microsoft-nuget-autocomplete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuget/openapi/nuget-autocomplete-api-openapi.yml
- filename: nuget-flatcontainer-api-openapi.yml
  format: yaml
  label: Microsoft NuGet Flatcontainer API
  slug: microsoft-nuget-flatcontainer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuget/openapi/nuget-flatcontainer-api-openapi.yml
- filename: nuget-query-api-openapi.yml
  format: yaml
  label: Microsoft NuGet Query API
  slug: microsoft-nuget-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuget/openapi/nuget-query-api-openapi.yml
- filename: nuget-registration5-gz-semver2-api-openapi.yml
  format: yaml
  label: Microsoft NuGet Registration5 Gz Semver2 API
  slug: microsoft-nuget-registration5-gz-semver2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuget/openapi/nuget-registration5-gz-semver2-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual accepting these terms on behalf of an entity, you represent that you have the legal authority to enter into this Agreement on that entity's behalf.
    type: individual
  minimum_age:
    text: Don’t use the Sites if you are under the age of thirteen (13).
    value: '13'
  restricted_uses:
  - summary: Under-13 users
    text: Don’t use the Sites if you are under the age of thirteen (13).
  - summary: General purpose hosting
    text: Don’t use the Sites for “general purpose”-hosting.
  - summary: Spamming with personal information
    text: You may not use information (including another person’s personal information) from the Sites for spamming purposes
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
name: NuGet
provenance_date: '2026-11-10'
provider_name: NuGet
provider_slug: nuget
slug: nuget-eligibility
source_date: '2026-11-10'
source_filename: nuget-eligibility.yml
source_heading: Eligibility
source_page: https://www.nuget.org/policies/Terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NuGet\naid: nuget\nurl: https://www.nuget.org/policies/Terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual accepting these terms on behalf of an entity, you represent that you have the legal\n    authority to enter into this Agreement on that entity's behalf.\nrestricted_uses:\n- summary: Under-13 users\n  text: Don’t use the Sites if you are under the age of thirteen (13).\n- summary: General purpose hosting\n  text: Don’t use the Sites for “general purpose”-hosting.\n- summary: Spamming with personal information\n\
  \  text: You may not use information (including another person’s personal information) from the Sites for spamming\n    purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Don’t use the Sites if you are under the age of thirteen (13).\n"
source_yaml_url: https://artifacts.apis.io/nuget/eligibility/nuget-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from NuGet's own page on 2026-11-10.
synthetic: false
tags:
- Package Management
- .NET
- Packages
- Dependencies
- Software Distribution
- Registry
- Developer Tools
---
