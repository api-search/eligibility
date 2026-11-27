---
api_specs:
- filename: cisco-directory-connector-groups-api-openapi.yml
  format: yaml
  label: Cisco Directory Connector Groups API
  slug: cisco-directory-connector-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cisco-directory-connector/openapi/cisco-directory-connector-groups-api-openapi.yml
- filename: cisco-directory-connector-organizations-api-openapi.yml
  format: yaml
  label: Cisco Directory Connector Organizations API
  slug: cisco-directory-connector-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cisco-directory-connector/openapi/cisco-directory-connector-organizations-api-openapi.yml
- filename: cisco-directory-connector-people-api-openapi.yml
  format: yaml
  label: Cisco Directory Connector People API
  slug: cisco-directory-connector-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cisco-directory-connector/openapi/cisco-directory-connector-people-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Because international information is provided on our Site, not all products or programs mentioned will be available in your country.
  entity_types:
  - text: User accounts, profiles, usernames, and passwords are associated with one individual only
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or criminal activity
    text: Engage in or promote any illegal or criminal activity such as child pornography, gambling, or piracy.
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
name: Cisco Directory Connector
provenance_date: '2026-11-09'
provider_name: Cisco Directory Connector
provider_slug: cisco-directory-connector
slug: cisco-directory-connector-eligibility
source_date: '2026-11-09'
source_filename: cisco-directory-connector-eligibility.yml
source_heading: Eligibility
source_page: https://www.cisco.com/c/en/us/about/legal/terms-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cisco Directory Connector\naid: cisco-directory-connector\nurl: https://www.cisco.com/c/en/us/about/legal/terms-conditions.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Because international information is provided on our Site, not all products or programs mentioned will be\n    available in your country.\nentity_types:\n- type: individual\n  text: User accounts, profiles, usernames, and passwords are associated with one individual only\nrestricted_uses:\n- summary: Illegal or criminal activity\n  text: Engage in or promote any illegal or criminal activity such as child pornography,\
  \ gambling, or piracy.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cisco-directory-connector/eligibility/cisco-directory-connector-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Cisco Directory Connector's own page on 2026-11-09.
synthetic: false
tags:
- Active Directory
- Directory
- Enterprise
- Identity and Access Management
- LDAP
- Provisioning
- SCIM
- Synchronization
---
