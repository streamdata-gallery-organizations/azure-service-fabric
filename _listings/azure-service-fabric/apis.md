---
name: Azure Service Fabric
x-slug: azure-service-fabric
description: Service Fabric is a microservices platform used to build scalable, reliable,
  and easily managed applications for the cloud. Addressing the significant challenges
  in developing and managing cloud applications, Service Fabric allows developers
  and administrators to avoid solving complex infrastructure problems and focus instead
  on implementing mission-critical, demanding workloads.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
x-kinRank: "10"
x-alexaRank: ""
tags: Azure Service Fabric
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Service Fabric API Clusters Update
  x-api-slug: azure-service-fabric-api
  description: Update cluster configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
  humanURL: https://azure.microsoft.com/en-us/services/service-fabric/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceFabric/clusters/{clusterName}
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicefabricclustersclustername-patch-openapi.md
- name: Azure Service Fabric API Clusters Get
  x-api-slug: azure-service-fabric-api
  description: Get cluster resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
  humanURL: https://azure.microsoft.com/en-us/services/service-fabric/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceFabric/clusters/{clusterName}
  tags: Clusters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicefabricclustersclustername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicefabricclustersclustername-get-openapi.md
- name: Azure Service Fabric API Clusters Create
  x-api-slug: azure-service-fabric-api
  description: Create cluster resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
  humanURL: https://azure.microsoft.com/en-us/services/service-fabric/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceFabric/clusters/{clusterName}
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicefabricclustersclustername-put-openapi.md
- name: Azure Service Fabric API Clusters Delete
  x-api-slug: azure-service-fabric-api
  description: Delete cluster resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
  humanURL: https://azure.microsoft.com/en-us/services/service-fabric/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceFabric/clusters/{clusterName}
  tags: Clusters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicefabricclustersclustername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicefabricclustersclustername-delete-openapi.md
- name: Azure Service Fabric API Clusters List By Resource Group
  x-api-slug: azure-service-fabric-api
  description: List cluster resource by resource group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
  humanURL: https://azure.microsoft.com/en-us/services/service-fabric/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/Microsoft.ServiceFabric/clusters
  tags: Clusters Resource Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicefabricclusters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicefabricclusters-get-openapi.md
- name: Azure Service Fabric API Clusters List
  x-api-slug: azure-service-fabric-api
  description: List cluster resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
  humanURL: https://azure.microsoft.com/en-us/services/service-fabric/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.ServiceFabric/clusters
  tags: Clusters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/subscriptionssubscriptionidprovidersmicrosoftservicefabricclusters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/subscriptionssubscriptionidprovidersmicrosoftservicefabricclusters-get-openapi.md
- name: Azure Service Fabric API Cluster Versions List
  x-api-slug: azure-service-fabric-api
  description: List cluster code versions by location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
  humanURL: https://azure.microsoft.com/en-us/services/service-fabric/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.ServiceFabric/locations/{location}/environments/{environment}/clusterVersions
  tags: Cluster Versions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/subscriptionssubscriptionidprovidersmicrosoftservicefabriclocationslocationenvironmentsenvironmentclusterversions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/subscriptionssubscriptionidprovidersmicrosoftservicefabriclocationslocationenvironmentsenvironmentclusterversions-get-openapi.md
- name: Azure Service Fabric API Operations List
  x-api-slug: azure-service-fabric-api
  description: Lists all of the available ServiceFabric REST API operations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
  humanURL: https://azure.microsoft.com/en-us/services/service-fabric/
  baseURL: ://management.azure.com////providers/Microsoft.ServiceFabric/operations
  tags: Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/providersmicrosoftservicefabricoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/providersmicrosoftservicefabricoperations-get-openapi.md
- name: Azure Service Fabric API
  x-api-slug: azure-service-fabric-api
  description: Service Fabric is a microservices platform used to build scalable,
    reliable, and easily managed applications for the cloud. Addressing the significant
    challenges in developing and managing cloud applications, Service Fabric allows
    developers and administrators to avoid solving complex infrastructure problems
    and focus instead on implementing mission-critical, demanding workloads.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-fabric-02.png
  humanURL: https://azure.microsoft.com/en-us/services/service-fabric/
  baseURL: ://management.azure.com//
  tags: Azure Service Fabric
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-fabric/master/_listings/azure-service-fabric/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/service-fabric/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/service-fabric/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/service-fabric/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/service-fabric/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---