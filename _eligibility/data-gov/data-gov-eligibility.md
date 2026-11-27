---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users are NOT required to provide any information to search, retrieve, download, filter and otherwise use the data available on Data.gov.
    type: individual
  - text: For certain Data.gov users who need access to administrative privileges in order to carry out Data.gov functions in their roles as official representatives of federal, state, local or tribal governments or certain non-governmental organizations, Data.gov collects additional information
    type: government
  minimum_age:
    text: Personal information from children under 13 is not knowingly collected, nor are children under 13 knowingly contacted by Data.gov.
    value: null
  restricted_uses:
  - summary: Non-public or protected information
    text: All datasets accessed through Data.gov are confined to public information and must not contain National Security information as defined by statute and/or Executive Order, or other information/data that is protected by other statute, practice, or legal precedent.
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
name: Data.gov
provenance_date: '2026-11-09'
provider_name: Data.gov
provider_slug: data-gov
slug: data-gov-eligibility
source_date: '2026-11-09'
source_filename: data-gov-eligibility.yml
source_heading: Eligibility
source_page: https://data.gov/privacy-policy/#data-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Data.gov\naid: data-gov\nurl: https://data.gov/privacy-policy/#data-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users are NOT required to provide any information to search, retrieve, download, filter and otherwise use\n    the data available on Data.gov.\n- type: government\n  text: For certain Data.gov users who need access to administrative privileges in order to carry out Data.gov functions\n    in their roles as official representatives of federal, state, local or tribal governments or certain non-governmental\n    organizations,\
  \ Data.gov collects additional information\nrestricted_uses:\n- summary: Non-public or protected information\n  text: All datasets accessed through Data.gov are confined to public information and must not contain National\n    Security information as defined by statute and/or Executive Order, or other information/data that is protected\n    by other statute, practice, or legal precedent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Personal information from children under 13 is not knowingly collected, nor are children under 13 knowingly\n    contacted by Data.gov.\n"
source_yaml_url: https://artifacts.apis.io/data-gov/eligibility/data-gov-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Data.gov's own page on 2026-11-09.
synthetic: false
tags:
- Government
- Open Data
- Catalog
- CKAN
- Datasets
- Federal
- GSA
- Open Government
- Data Catalog
- Government Data
---
