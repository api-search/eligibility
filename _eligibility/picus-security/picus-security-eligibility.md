---
api_specs:
- filename: picus-security-activity-logs-api-openapi.yml
  format: yaml
  label: Picus Security Activity Logs API
  slug: picus-security-activity-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/picus-security/openapi/picus-security-activity-logs-api-openapi.yml
- filename: picus-security-agents-api-openapi.yml
  format: yaml
  label: Picus Security Agents API
  slug: picus-security-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/picus-security/openapi/picus-security-agents-api-openapi.yml
- filename: picus-security-authentication-api-openapi.yml
  format: yaml
  label: Picus Security Authentication API
  slug: picus-security-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/picus-security/openapi/picus-security-authentication-api-openapi.yml
- filename: picus-security-instances-api-openapi.yml
  format: yaml
  label: Picus Security Instances API
  slug: picus-security-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/picus-security/openapi/picus-security-instances-api-openapi.yml
- filename: picus-security-integrations-api-openapi.yml
  format: yaml
  label: Picus Security Integrations API
  slug: picus-security-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/picus-security/openapi/picus-security-integrations-api-openapi.yml
- filename: picus-security-mitigation-api-openapi.yml
  format: yaml
  label: Picus Security Mitigation API
  slug: picus-security-mitigation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/picus-security/openapi/picus-security-mitigation-api-openapi.yml
- filename: picus-security-simulation-latest-result-api-openapi.yml
  format: yaml
  label: Picus Security Simulation Latest Result API
  slug: picus-security-simulation-latest-result-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/picus-security/openapi/picus-security-simulation-latest-result-api-openapi.yml
- filename: picus-security-simulation-result-api-openapi.yml
  format: yaml
  label: Picus Security Simulation Result API
  slug: picus-security-simulation-result-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/picus-security/openapi/picus-security-simulation-result-api-openapi.yml
- filename: picus-security-simulation-result-reports-api-openapi.yml
  format: yaml
  label: Picus Security Simulation Result Reports API
  slug: picus-security-simulation-result-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/picus-security/openapi/picus-security-simulation-result-reports-api-openapi.yml
- filename: picus-security-simulations-api-openapi.yml
  format: yaml
  label: Picus Security Simulations API
  slug: picus-security-simulations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/picus-security/openapi/picus-security-simulations-api-openapi.yml
- filename: picus-security-summary-api-openapi.yml
  format: yaml
  label: Picus Security Summary API
  slug: picus-security-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/picus-security/openapi/picus-security-summary-api-openapi.yml
- filename: picus-security-templates-api-openapi.yml
  format: yaml
  label: Picus Security Templates API
  slug: picus-security-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/picus-security/openapi/picus-security-templates-api-openapi.yml
- filename: picus-security-threats-api-openapi.yml
  format: yaml
  label: Picus Security Threats API
  slug: picus-security-threats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/picus-security/openapi/picus-security-threats-api-openapi.yml
- filename: picus-security-users-api-openapi.yml
  format: yaml
  label: Picus Security Users API
  slug: picus-security-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/picus-security/openapi/picus-security-users-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: You means the individual accessing or using the Service
    type: individual
  - text: or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Industry-specific regulated uses
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  - summary: GLBA
    text: You may not use the Site in a way that would violate the Gramm- Leach-Bliley Act (GLBA).
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
name: Picus Security
provenance_date: '2026-11-10'
provider_name: Picus Security
provider_slug: picus-security
slug: picus-security-eligibility
source_date: '2026-11-10'
source_filename: picus-security-eligibility.yml
source_heading: Eligibility
source_page: https://www.picussecurity.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Picus Security\naid: picus-security\nurl: https://www.picussecurity.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service\n- type: business\n  text: or the company, or other legal entity on behalf of which such individual is accessing or using the Service\nrestricted_uses:\n\
  - summary: Industry-specific regulated uses\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\n- summary: GLBA\n  text: You may not use the Site in a way that would violate the Gramm- Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/picus-security/eligibility/picus-security-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Picus Security's own page on 2026-11-10.
synthetic: false
tags:
- Cybersecurity
- Security Validation
- Breach and Attack Simulation
- Adversarial Exposure Validation
- Continuous Threat Exposure Management
- Penetration Testing
- Threat Intelligence
- mitre-attack
- Detection Engineering
- Security Operations
---
