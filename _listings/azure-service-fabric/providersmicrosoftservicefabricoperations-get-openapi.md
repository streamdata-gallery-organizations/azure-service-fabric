---
swagger: "2.0"
x-collection-name: Azure Service Fabric
x-complete: 0
info:
  title: Azure Service Fabric API Operations List
  version: 1.0.0
  description: Lists all of the available ServiceFabric REST API operations.
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceFabric/clusters/{clusterName}:
    patch:
      summary: Clusters Update
      description: Update cluster configuration
      operationId: Clusters_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicefabricclustersclustername-patch
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters which contains the property value and property
          name which used to update the cluster configuration
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Clusters
    get:
      summary: Clusters Get
      description: Get cluster resource
      operationId: Clusters_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicefabricclustersclustername-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Clusters
    put:
      summary: Clusters Create
      description: Create cluster resource
      operationId: Clusters_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicefabricclustersclustername-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Put Request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Clusters
    delete:
      summary: Clusters Delete
      description: Delete cluster resource
      operationId: Clusters_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicefabricclustersclustername-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/Microsoft.ServiceFabric/clusters:
    get:
      summary: Clusters List By Resource Group
      description: List cluster resource by resource group
      operationId: Clusters_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicefabricclusters-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Clusters Resource Group
  /subscriptions/{subscriptionId}/providers/Microsoft.ServiceFabric/clusters:
    get:
      summary: Clusters List
      description: List cluster resource
      operationId: Clusters_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftservicefabricclusters-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Clusters
  ? /subscriptions/{subscriptionId}/providers/Microsoft.ServiceFabric/locations/{location}/environments/{environment}/clusterVersions
  : get:
      summary: Cluster Versions List
      description: List cluster code versions by location
      operationId: ClusterVersions_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftservicefabriclocationslocationenvironmentsenvironmentclusterversions-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Cluster Versions
  /providers/Microsoft.ServiceFabric/operations:
    get:
      summary: Operations List
      description: Lists all of the available ServiceFabric REST API operations.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoftservicefabricoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---