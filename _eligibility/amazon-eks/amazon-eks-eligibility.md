---
api_specs:
- filename: amazon-eks-clusters-api-openapi.yml
  format: yaml
  label: Amazon EKS Clusters API
  slug: amazon-eks-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-clusters-api-openapi.yml
- filename: amazon-eks-fargate-profiles-api-openapi.yml
  format: yaml
  label: Amazon EKS Fargate Profiles API
  slug: amazon-eks-fargate-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-fargate-profiles-api-openapi.yml
- filename: amazon-eks-node-groups-api-openapi.yml
  format: yaml
  label: Amazon EKS Node Groups API
  slug: amazon-eks-node-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-node-groups-api-openapi.yml
- filename: amazon-eks-add-ons-api-openapi.yml
  format: yaml
  label: Amazon EKS Add Ons API
  slug: amazon-eks-add-ons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-add-ons-api-openapi.yml
- filename: amazon-eks-access-entries-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Access Entries API
  slug: amazon-eks-access-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-access-entries-api-openapi.yml
- filename: amazon-eks-access-policies-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Access Policies API
  slug: amazon-eks-access-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-access-policies-api-openapi.yml
- filename: amazon-eks-capabilities-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Capabilities API
  slug: amazon-eks-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-capabilities-api-openapi.yml
- filename: amazon-eks-certificate-authorities-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Certificate Authorities API
  slug: amazon-eks-certificate-authorities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-certificate-authorities-api-openapi.yml
- filename: amazon-eks-eks-anywhere-subscriptions-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Eks Anywhere Subscriptions API
  slug: amazon-eks-eks-anywhere-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-eks-anywhere-subscriptions-api-openapi.yml
- filename: amazon-eks-identity-provider-configs-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Identity Provider Configs API
  slug: amazon-eks-identity-provider-configs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-identity-provider-configs-api-openapi.yml
- filename: amazon-eks-operations-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Operations API
  slug: amazon-eks-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-operations-api-openapi.yml
- filename: amazon-eks-pod-identity-associations-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Pod Identity Associations API
  slug: amazon-eks-pod-identity-associations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-pod-identity-associations-api-openapi.yml
- filename: amazon-eks-tags-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Tags API
  slug: amazon-eks-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-tags-api-openapi.yml
- filename: amazon-eks-updates-api-openapi.yml
  format: yaml
  label: Amazon EKS Eks Updates API
  slug: amazon-eks-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-eks/openapi/amazon-eks-updates-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No High Risk Use of Microsoft Software
    text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other modes of human mass transportation, nuclear or chemical facilities, life support systems, implantable medical equipment, motor vehicles, weaponry systems, or any similar scenario
  - summary: Spend limits not for hazardous or regulated uses
    text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of any hazardous environments or critical systems, any regulated content (such as protected health information), government data, or any content of government entities.
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
name: Amazon EKS
provenance_date: '2026-11-09'
provider_name: Amazon EKS
provider_slug: amazon-eks
slug: amazon-eks-eligibility
source_date: '2026-11-09'
source_filename: amazon-eks-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon EKS\naid: amazon-eks\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No High Risk Use of Microsoft Software\n  text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other\n    modes of human mass transportation, nuclear or chemical facilities, life support systems, implantable medical\n    equipment, motor vehicles, weaponry systems, or any similar scenario\n- summary: Spend limits not for hazardous or regulated\
  \ uses\n  text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of\n    any hazardous environments or critical systems, any regulated content (such as protected health information),\n    government data, or any content of government entities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-eks/eligibility/amazon-eks-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Amazon EKS's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Container Orchestration
- Containers
- EKS
- Kubernetes
---
