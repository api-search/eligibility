---
api_specs:
- filename: anytax-country-api-api-openapi.yml
  format: yaml
  label: AnyTax Country API
  slug: anytax-country-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-country-api-api-openapi.yml
- filename: anytax-e-r-api-api-openapi.yml
  format: yaml
  label: AnyTax EÜR API
  slug: anytax-e-r-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-e-r-api-api-openapi.yml
- filename: anytax-elster-import-api-api-openapi.yml
  format: yaml
  label: AnyTax ELSTER Import API
  slug: anytax-elster-import-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-elster-import-api-api-openapi.yml
- filename: anytax-estimator-api-openapi.yml
  format: yaml
  label: AnyTax Estimator API
  slug: anytax-estimator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-estimator-api-openapi.yml
- filename: anytax-filing-api-api-openapi.yml
  format: yaml
  label: AnyTax Filing API
  slug: anytax-filing-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-filing-api-api-openapi.yml
- filename: anytax-filing-eligibility-check-api-openapi.yml
  format: yaml
  label: AnyTax Filing Eligibility Check API
  slug: anytax-filing-eligibility-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-filing-eligibility-check-api-openapi.yml
- filename: anytax-navigation-api-api-openapi.yml
  format: yaml
  label: AnyTax Navigation API
  slug: anytax-navigation-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-navigation-api-api-openapi.yml
- filename: anytax-partner-platform-api-openapi.yml
  format: yaml
  label: AnyTax Partner platform API
  slug: anytax-partner-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-partner-platform-api-openapi.yml
- filename: anytax-public-api-api-openapi.yml
  format: yaml
  label: AnyTax Public API
  slug: anytax-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-public-api-api-openapi.yml
- filename: anytax-question-api-api-openapi.yml
  format: yaml
  label: AnyTax Question API
  slug: anytax-question-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-question-api-api-openapi.yml
- filename: anytax-scenario-api-api-openapi.yml
  format: yaml
  label: AnyTax Scenario API
  slug: anytax-scenario-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-scenario-api-api-openapi.yml
- filename: anytax-tax-saving-tip-api-api-openapi.yml
  format: yaml
  label: AnyTax Tax Saving Tip API
  slug: anytax-tax-saving-tip-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-tax-saving-tip-api-api-openapi.yml
- filename: anytax-user-api-api-openapi.yml
  format: yaml
  label: AnyTax User API
  slug: anytax-user-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-user-api-api-openapi.yml
- filename: anytax-wage-tax-api-api-openapi.yml
  format: yaml
  label: AnyTax Wage Tax API
  slug: anytax-wage-tax-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-wage-tax-api-api-openapi.yml
- filename: anytax-answer-api-api-openapi.yml
  format: yaml
  label: AnyTax Answer API
  slug: anytax-answer-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-answer-api-api-openapi.yml
- filename: anytax-auth-api-api-openapi.yml
  format: yaml
  label: AnyTax Auth API
  slug: anytax-auth-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anytax/openapi/anytax-auth-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: AnyTax gewährt dem Nutzer ein einfaches, nicht übertragbares, nicht unterlizenzierbares und widerrufbares Recht, die Dienste für die Dauer des Nutzungsverhältnisses für persönliche Zwecke zu nutzen.
    type: individual
  - text: Die folgende Freistellungsbestimmung gilt ausschließlich gegenüber Nutzern, die Unternehmer im Sinne von § 14 BGB sind.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No individual tax advice
    text: 'Die Dienste umfassen insbesondere nicht: (i) individuelle Steuerberatung oder Empfehlungen zur Steuerplanung;'
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
name: AnyTax
provenance_date: '2026-11-09'
provider_name: AnyTax
provider_slug: anytax
slug: anytax-eligibility
source_date: '2026-11-09'
source_filename: anytax-eligibility.yml
source_heading: Eligibility
source_page: https://www.anytax.io/legal-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnyTax\naid: anytax\nurl: https://www.anytax.io/legal-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: AnyTax gewährt dem Nutzer ein einfaches, nicht übertragbares, nicht unterlizenzierbares und widerrufbares\n    Recht, die Dienste für die Dauer des Nutzungsverhältnisses für persönliche Zwecke zu nutzen.\n- type: business\n  text: Die folgende Freistellungsbestimmung gilt ausschließlich gegenüber Nutzern, die Unternehmer im Sinne von\n    § 14 BGB sind.\nrestricted_uses:\n- summary: No individual tax advice\n  text: 'Die Dienste\
  \ umfassen insbesondere nicht: (i) individuelle Steuerberatung oder Empfehlungen zur Steuerplanung;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anytax/eligibility/anytax-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from AnyTax's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Tax
- Integration
- Banking
- Tax Planning
- White Label
- Compliance
---
