---
api_specs:
- filename: virtru-authorization-authorizationservice-api-openapi.yml
  format: yaml
  label: Virtru authorization.AuthorizationService API
  slug: virtru-authorization-authorizationservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtru/openapi/virtru-authorization-authorizationservice-api-openapi.yml
- filename: virtru-authorization-v2-authorizationservice-api-openapi.yml
  format: yaml
  label: Virtru authorization.v2.AuthorizationService API
  slug: virtru-authorization-v2-authorizationservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtru/openapi/virtru-authorization-v2-authorizationservice-api-openapi.yml
- filename: virtru-entityresolution-v2-entityresolutionservice-api-openapi.yml
  format: yaml
  label: Virtru Entityresolution.v2.Entity Resolution Service API
  slug: virtru-entityresolution-v2-entityresolutionservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtru/openapi/virtru-entityresolution-v2-entityresolutionservice-api-openapi.yml
- filename: virtru-kas-accessservice-api-openapi.yml
  format: yaml
  label: Virtru Kas.Access Service API
  slug: virtru-kas-accessservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtru/openapi/virtru-kas-accessservice-api-openapi.yml
- filename: virtru-policy-actions-actionservice-api-openapi.yml
  format: yaml
  label: Virtru Policy.actions.Action Service API
  slug: virtru-policy-actions-actionservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtru/openapi/virtru-policy-actions-actionservice-api-openapi.yml
- filename: virtru-policy-attributes-attributesservice-api-openapi.yml
  format: yaml
  label: Virtru Policy.attributes.Attributes Service API
  slug: virtru-policy-attributes-attributesservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtru/openapi/virtru-policy-attributes-attributesservice-api-openapi.yml
- filename: virtru-policy-kasregistry-keyaccessserverregistryservice-api-openapi.yml
  format: yaml
  label: Virtru Policy.kasregistry.Key Access Server Registry Service API
  slug: virtru-policy-kasregistry-keyaccessserverregistryservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtru/openapi/virtru-policy-kasregistry-keyaccessserverregistryservice-api-openapi.yml
- filename: virtru-policy-keymanagement-keymanagementservice-api-openapi.yml
  format: yaml
  label: Virtru Policy.keymanagement.Key Management Service API
  slug: virtru-policy-keymanagement-keymanagementservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtru/openapi/virtru-policy-keymanagement-keymanagementservice-api-openapi.yml
- filename: virtru-policy-namespaces-namespaceservice-api-openapi.yml
  format: yaml
  label: Virtru Policy.namespaces.Namespace Service API
  slug: virtru-policy-namespaces-namespaceservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtru/openapi/virtru-policy-namespaces-namespaceservice-api-openapi.yml
- filename: virtru-policy-obligations-service-api-openapi.yml
  format: yaml
  label: Virtru Policy.obligations.Service API
  slug: virtru-policy-obligations-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtru/openapi/virtru-policy-obligations-service-api-openapi.yml
- filename: virtru-policy-registeredresources-registeredresourcesservice-api-openapi.yml
  format: yaml
  label: Virtru Policy.registeredresources.Registered Resources Service API
  slug: virtru-policy-registeredresources-registeredresourcesservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtru/openapi/virtru-policy-registeredresources-registeredresourcesservice-api-openapi.yml
- filename: virtru-policy-resourcemapping-resourcemappingservice-api-openapi.yml
  format: yaml
  label: Virtru Policy.resourcemapping.Resource Mapping Service API
  slug: virtru-policy-resourcemapping-resourcemappingservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtru/openapi/virtru-policy-resourcemapping-resourcemappingservice-api-openapi.yml
- filename: virtru-policy-subjectmapping-subjectmappingservice-api-openapi.yml
  format: yaml
  label: Virtru Policy.subjectmapping.Subject Mapping Service API
  slug: virtru-policy-subjectmapping-subjectmappingservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtru/openapi/virtru-policy-subjectmapping-subjectmappingservice-api-openapi.yml
- filename: virtru-wellknownconfiguration-wellknownservice-api-openapi.yml
  format: yaml
  label: Virtru Wellknownconfiguration.Well Known Service API
  slug: virtru-wellknownconfiguration-wellknownservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtru/openapi/virtru-wellknownconfiguration-wellknownservice-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If Customer is an agency or instrumentality of the United States Government, the Materials are “commercial computer software”
    type: government
  - text: solely in connection with your personal, non-business, non-commercial e-mail account(s) and solely for personal, non-business, non-commercial purpose
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Life-critical identity verification
    text: use the Materials or Virtru Services for any purpose where an accurate verification of identity has critical or life-threatening consequences
  - summary: Export restrictions
    text: Customer represents and warrants that it is not listed on any U.S. government list of prohibited or restricted parties
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
name: Virtru
provenance_date: '2026-11-10'
provider_name: Virtru
provider_slug: virtru
slug: virtru-eligibility
source_date: '2026-11-10'
source_filename: virtru-eligibility.yml
source_heading: Eligibility
source_page: https://www.virtru.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Virtru\naid: virtru\nurl: https://www.virtru.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: If Customer is an agency or instrumentality of the United States Government, the Materials are “commercial\n    computer software”\n- type: individual\n  text: solely in connection with your personal, non-business, non-commercial e-mail account(s) and solely for personal,\n    non-business, non-commercial purpose\nrestricted_uses:\n- summary: Life-critical identity verification\n  text: use the Materials\
  \ or Virtru Services for any purpose where an accurate verification of identity has critical\n    or life-threatening consequences\n- summary: Export restrictions\n  text: Customer represents and warrants that it is not listed on any U.S. government list of prohibited or restricted\n    parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/virtru/eligibility/virtru-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Virtru's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cybersecurity
- Data Security
- Encryption
- Access Control
- Zero Trust
- Privacy
- OpenTDF
- Key Management
---
