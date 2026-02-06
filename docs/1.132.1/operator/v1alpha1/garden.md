---
permalink: /1.132.1/operator/v1alpha1/garden/
---

# operator.v1alpha1.garden

"Garden describes a list of gardens."

## Index

* [`fn new(name)`](#fn-new)
* [`obj metadata`](#obj-metadata)
  * [`fn withAnnotations(annotations)`](#fn-metadatawithannotations)
  * [`fn withAnnotationsMixin(annotations)`](#fn-metadatawithannotationsmixin)
  * [`fn withClusterName(clusterName)`](#fn-metadatawithclustername)
  * [`fn withCreationTimestamp(creationTimestamp)`](#fn-metadatawithcreationtimestamp)
  * [`fn withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)`](#fn-metadatawithdeletiongraceperiodseconds)
  * [`fn withDeletionTimestamp(deletionTimestamp)`](#fn-metadatawithdeletiontimestamp)
  * [`fn withFinalizers(finalizers)`](#fn-metadatawithfinalizers)
  * [`fn withFinalizersMixin(finalizers)`](#fn-metadatawithfinalizersmixin)
  * [`fn withGenerateName(generateName)`](#fn-metadatawithgeneratename)
  * [`fn withGeneration(generation)`](#fn-metadatawithgeneration)
  * [`fn withLabels(labels)`](#fn-metadatawithlabels)
  * [`fn withLabelsMixin(labels)`](#fn-metadatawithlabelsmixin)
  * [`fn withName(name)`](#fn-metadatawithname)
  * [`fn withNamespace(namespace)`](#fn-metadatawithnamespace)
  * [`fn withOwnerReferences(ownerReferences)`](#fn-metadatawithownerreferences)
  * [`fn withOwnerReferencesMixin(ownerReferences)`](#fn-metadatawithownerreferencesmixin)
  * [`fn withResourceVersion(resourceVersion)`](#fn-metadatawithresourceversion)
  * [`fn withSelfLink(selfLink)`](#fn-metadatawithselflink)
  * [`fn withUid(uid)`](#fn-metadatawithuid)
* [`obj spec`](#obj-spec)
  * [`fn withExtensions(extensions)`](#fn-specwithextensions)
  * [`fn withExtensionsMixin(extensions)`](#fn-specwithextensionsmixin)
  * [`obj spec.dns`](#obj-specdns)
    * [`fn withProviders(providers)`](#fn-specdnswithproviders)
    * [`fn withProvidersMixin(providers)`](#fn-specdnswithprovidersmixin)
    * [`obj spec.dns.providers`](#obj-specdnsproviders)
      * [`fn withName(name)`](#fn-specdnsproviderswithname)
      * [`fn withProviderConfig(providerConfig)`](#fn-specdnsproviderswithproviderconfig)
      * [`fn withProviderConfigMixin(providerConfig)`](#fn-specdnsproviderswithproviderconfigmixin)
      * [`fn withType(type)`](#fn-specdnsproviderswithtype)
      * [`obj spec.dns.providers.secretRef`](#obj-specdnsproviderssecretref)
        * [`fn withName(name)`](#fn-specdnsproviderssecretrefwithname)
  * [`obj spec.extensions`](#obj-specextensions)
    * [`fn withProviderConfig(providerConfig)`](#fn-specextensionswithproviderconfig)
    * [`fn withProviderConfigMixin(providerConfig)`](#fn-specextensionswithproviderconfigmixin)
    * [`fn withType(type)`](#fn-specextensionswithtype)
  * [`obj spec.runtimeCluster`](#obj-specruntimecluster)
    * [`obj spec.runtimeCluster.ingress`](#obj-specruntimeclusteringress)
      * [`fn withDomains(domains)`](#fn-specruntimeclusteringresswithdomains)
      * [`fn withDomainsMixin(domains)`](#fn-specruntimeclusteringresswithdomainsmixin)
      * [`obj spec.runtimeCluster.ingress.controller`](#obj-specruntimeclusteringresscontroller)
        * [`fn withKind(kind)`](#fn-specruntimeclusteringresscontrollerwithkind)
        * [`fn withProviderConfig(providerConfig)`](#fn-specruntimeclusteringresscontrollerwithproviderconfig)
        * [`fn withProviderConfigMixin(providerConfig)`](#fn-specruntimeclusteringresscontrollerwithproviderconfigmixin)
      * [`obj spec.runtimeCluster.ingress.domains`](#obj-specruntimeclusteringressdomains)
        * [`fn withName(name)`](#fn-specruntimeclusteringressdomainswithname)
        * [`fn withProvider(provider)`](#fn-specruntimeclusteringressdomainswithprovider)
    * [`obj spec.runtimeCluster.networking`](#obj-specruntimeclusternetworking)
      * [`fn withBlockCIDRs(blockCIDRs)`](#fn-specruntimeclusternetworkingwithblockcidrs)
      * [`fn withBlockCIDRsMixin(blockCIDRs)`](#fn-specruntimeclusternetworkingwithblockcidrsmixin)
      * [`fn withIpFamilies(ipFamilies)`](#fn-specruntimeclusternetworkingwithipfamilies)
      * [`fn withIpFamiliesMixin(ipFamilies)`](#fn-specruntimeclusternetworkingwithipfamiliesmixin)
      * [`fn withNodes(nodes)`](#fn-specruntimeclusternetworkingwithnodes)
      * [`fn withNodesMixin(nodes)`](#fn-specruntimeclusternetworkingwithnodesmixin)
      * [`fn withPods(pods)`](#fn-specruntimeclusternetworkingwithpods)
      * [`fn withPodsMixin(pods)`](#fn-specruntimeclusternetworkingwithpodsmixin)
      * [`fn withServices(services)`](#fn-specruntimeclusternetworkingwithservices)
      * [`fn withServicesMixin(services)`](#fn-specruntimeclusternetworkingwithservicesmixin)
    * [`obj spec.runtimeCluster.provider`](#obj-specruntimeclusterprovider)
      * [`fn withRegion(region)`](#fn-specruntimeclusterproviderwithregion)
      * [`fn withZones(zones)`](#fn-specruntimeclusterproviderwithzones)
      * [`fn withZonesMixin(zones)`](#fn-specruntimeclusterproviderwithzonesmixin)
    * [`obj spec.runtimeCluster.settings`](#obj-specruntimeclustersettings)
      * [`obj spec.runtimeCluster.settings.loadBalancerServices`](#obj-specruntimeclustersettingsloadbalancerservices)
        * [`fn withAnnotations(annotations)`](#fn-specruntimeclustersettingsloadbalancerserviceswithannotations)
        * [`fn withAnnotationsMixin(annotations)`](#fn-specruntimeclustersettingsloadbalancerserviceswithannotationsmixin)
      * [`obj spec.runtimeCluster.settings.topologyAwareRouting`](#obj-specruntimeclustersettingstopologyawarerouting)
        * [`fn withEnabled(enabled)`](#fn-specruntimeclustersettingstopologyawareroutingwithenabled)
      * [`obj spec.runtimeCluster.settings.verticalPodAutoscaler`](#obj-specruntimeclustersettingsverticalpodautoscaler)
        * [`fn withEnabled(enabled)`](#fn-specruntimeclustersettingsverticalpodautoscalerwithenabled)
        * [`fn withFeatureGates(featureGates)`](#fn-specruntimeclustersettingsverticalpodautoscalerwithfeaturegates)
        * [`fn withFeatureGatesMixin(featureGates)`](#fn-specruntimeclustersettingsverticalpodautoscalerwithfeaturegatesmixin)
        * [`fn withMaxAllowed(maxAllowed)`](#fn-specruntimeclustersettingsverticalpodautoscalerwithmaxallowed)
        * [`fn withMaxAllowedMixin(maxAllowed)`](#fn-specruntimeclustersettingsverticalpodautoscalerwithmaxallowedmixin)
    * [`obj spec.runtimeCluster.volume`](#obj-specruntimeclustervolume)
      * [`fn withMinimumSize(minimumSize)`](#fn-specruntimeclustervolumewithminimumsize)
  * [`obj spec.virtualCluster`](#obj-specvirtualcluster)
    * [`obj spec.virtualCluster.controlPlane`](#obj-specvirtualclustercontrolplane)
      * [`fn withHighAvailability(highAvailability)`](#fn-specvirtualclustercontrolplanewithhighavailability)
      * [`fn withHighAvailabilityMixin(highAvailability)`](#fn-specvirtualclustercontrolplanewithhighavailabilitymixin)
    * [`obj spec.virtualCluster.dns`](#obj-specvirtualclusterdns)
      * [`fn withDomains(domains)`](#fn-specvirtualclusterdnswithdomains)
      * [`fn withDomainsMixin(domains)`](#fn-specvirtualclusterdnswithdomainsmixin)
      * [`obj spec.virtualCluster.dns.domains`](#obj-specvirtualclusterdnsdomains)
        * [`fn withName(name)`](#fn-specvirtualclusterdnsdomainswithname)
        * [`fn withProvider(provider)`](#fn-specvirtualclusterdnsdomainswithprovider)
    * [`obj spec.virtualCluster.etcd`](#obj-specvirtualclusteretcd)
      * [`obj spec.virtualCluster.etcd.events`](#obj-specvirtualclusteretcdevents)
        * [`obj spec.virtualCluster.etcd.events.autoscaling`](#obj-specvirtualclusteretcdeventsautoscaling)
          * [`fn withMinAllowed(minAllowed)`](#fn-specvirtualclusteretcdeventsautoscalingwithminallowed)
          * [`fn withMinAllowedMixin(minAllowed)`](#fn-specvirtualclusteretcdeventsautoscalingwithminallowedmixin)
        * [`obj spec.virtualCluster.etcd.events.storage`](#obj-specvirtualclusteretcdeventsstorage)
          * [`fn withCapacity(capacity)`](#fn-specvirtualclusteretcdeventsstoragewithcapacity)
          * [`fn withClassName(className)`](#fn-specvirtualclusteretcdeventsstoragewithclassname)
      * [`obj spec.virtualCluster.etcd.main`](#obj-specvirtualclusteretcdmain)
        * [`obj spec.virtualCluster.etcd.main.autoscaling`](#obj-specvirtualclusteretcdmainautoscaling)
          * [`fn withMinAllowed(minAllowed)`](#fn-specvirtualclusteretcdmainautoscalingwithminallowed)
          * [`fn withMinAllowedMixin(minAllowed)`](#fn-specvirtualclusteretcdmainautoscalingwithminallowedmixin)
        * [`obj spec.virtualCluster.etcd.main.backup`](#obj-specvirtualclusteretcdmainbackup)
          * [`fn withBucketName(bucketName)`](#fn-specvirtualclusteretcdmainbackupwithbucketname)
          * [`fn withProvider(provider)`](#fn-specvirtualclusteretcdmainbackupwithprovider)
          * [`fn withProviderConfig(providerConfig)`](#fn-specvirtualclusteretcdmainbackupwithproviderconfig)
          * [`fn withProviderConfigMixin(providerConfig)`](#fn-specvirtualclusteretcdmainbackupwithproviderconfigmixin)
          * [`fn withRegion(region)`](#fn-specvirtualclusteretcdmainbackupwithregion)
          * [`obj spec.virtualCluster.etcd.main.backup.secretRef`](#obj-specvirtualclusteretcdmainbackupsecretref)
            * [`fn withName(name)`](#fn-specvirtualclusteretcdmainbackupsecretrefwithname)
        * [`obj spec.virtualCluster.etcd.main.storage`](#obj-specvirtualclusteretcdmainstorage)
          * [`fn withCapacity(capacity)`](#fn-specvirtualclusteretcdmainstoragewithcapacity)
          * [`fn withClassName(className)`](#fn-specvirtualclusteretcdmainstoragewithclassname)
    * [`obj spec.virtualCluster.gardener`](#obj-specvirtualclustergardener)
      * [`fn withClusterIdentity(clusterIdentity)`](#fn-specvirtualclustergardenerwithclusteridentity)
      * [`fn withGardenerDiscoveryServer(gardenerDiscoveryServer)`](#fn-specvirtualclustergardenerwithgardenerdiscoveryserver)
      * [`fn withGardenerDiscoveryServerMixin(gardenerDiscoveryServer)`](#fn-specvirtualclustergardenerwithgardenerdiscoveryservermixin)
      * [`obj spec.virtualCluster.gardener.gardenerAPIServer`](#obj-specvirtualclustergardenergardenerapiserver)
        * [`fn withAdmissionPlugins(admissionPlugins)`](#fn-specvirtualclustergardenergardenerapiserverwithadmissionplugins)
        * [`fn withAdmissionPluginsMixin(admissionPlugins)`](#fn-specvirtualclustergardenergardenerapiserverwithadmissionpluginsmixin)
        * [`fn withFeatureGates(featureGates)`](#fn-specvirtualclustergardenergardenerapiserverwithfeaturegates)
        * [`fn withFeatureGatesMixin(featureGates)`](#fn-specvirtualclustergardenergardenerapiserverwithfeaturegatesmixin)
        * [`fn withGoAwayChance(goAwayChance)`](#fn-specvirtualclustergardenergardenerapiserverwithgoawaychance)
        * [`fn withShootAdminKubeconfigMaxExpiration(shootAdminKubeconfigMaxExpiration)`](#fn-specvirtualclustergardenergardenerapiserverwithshootadminkubeconfigmaxexpiration)
        * [`obj spec.virtualCluster.gardener.gardenerAPIServer.admissionPlugins`](#obj-specvirtualclustergardenergardenerapiserveradmissionplugins)
          * [`fn withConfig(config)`](#fn-specvirtualclustergardenergardenerapiserveradmissionpluginswithconfig)
          * [`fn withConfigMixin(config)`](#fn-specvirtualclustergardenergardenerapiserveradmissionpluginswithconfigmixin)
          * [`fn withDisabled(disabled)`](#fn-specvirtualclustergardenergardenerapiserveradmissionpluginswithdisabled)
          * [`fn withKubeconfigSecretName(kubeconfigSecretName)`](#fn-specvirtualclustergardenergardenerapiserveradmissionpluginswithkubeconfigsecretname)
          * [`fn withName(name)`](#fn-specvirtualclustergardenergardenerapiserveradmissionpluginswithname)
        * [`obj spec.virtualCluster.gardener.gardenerAPIServer.auditConfig`](#obj-specvirtualclustergardenergardenerapiserverauditconfig)
          * [`obj spec.virtualCluster.gardener.gardenerAPIServer.auditConfig.auditPolicy`](#obj-specvirtualclustergardenergardenerapiserverauditconfigauditpolicy)
            * [`obj spec.virtualCluster.gardener.gardenerAPIServer.auditConfig.auditPolicy.configMapRef`](#obj-specvirtualclustergardenergardenerapiserverauditconfigauditpolicyconfigmapref)
              * [`fn withApiVersion(apiVersion)`](#fn-specvirtualclustergardenergardenerapiserverauditconfigauditpolicyconfigmaprefwithapiversion)
              * [`fn withFieldPath(fieldPath)`](#fn-specvirtualclustergardenergardenerapiserverauditconfigauditpolicyconfigmaprefwithfieldpath)
              * [`fn withKind(kind)`](#fn-specvirtualclustergardenergardenerapiserverauditconfigauditpolicyconfigmaprefwithkind)
              * [`fn withName(name)`](#fn-specvirtualclustergardenergardenerapiserverauditconfigauditpolicyconfigmaprefwithname)
              * [`fn withNamespace(namespace)`](#fn-specvirtualclustergardenergardenerapiserverauditconfigauditpolicyconfigmaprefwithnamespace)
              * [`fn withResourceVersion(resourceVersion)`](#fn-specvirtualclustergardenergardenerapiserverauditconfigauditpolicyconfigmaprefwithresourceversion)
              * [`fn withUid(uid)`](#fn-specvirtualclustergardenergardenerapiserverauditconfigauditpolicyconfigmaprefwithuid)
        * [`obj spec.virtualCluster.gardener.gardenerAPIServer.auditWebhook`](#obj-specvirtualclustergardenergardenerapiserverauditwebhook)
          * [`fn withBatchMaxSize(batchMaxSize)`](#fn-specvirtualclustergardenergardenerapiserverauditwebhookwithbatchmaxsize)
          * [`fn withKubeconfigSecretName(kubeconfigSecretName)`](#fn-specvirtualclustergardenergardenerapiserverauditwebhookwithkubeconfigsecretname)
          * [`fn withVersion(version)`](#fn-specvirtualclustergardenergardenerapiserverauditwebhookwithversion)
        * [`obj spec.virtualCluster.gardener.gardenerAPIServer.encryptionConfig`](#obj-specvirtualclustergardenergardenerapiserverencryptionconfig)
          * [`fn withResources(resources)`](#fn-specvirtualclustergardenergardenerapiserverencryptionconfigwithresources)
          * [`fn withResourcesMixin(resources)`](#fn-specvirtualclustergardenergardenerapiserverencryptionconfigwithresourcesmixin)
        * [`obj spec.virtualCluster.gardener.gardenerAPIServer.logging`](#obj-specvirtualclustergardenergardenerapiserverlogging)
          * [`fn withHttpAccessVerbosity(httpAccessVerbosity)`](#fn-specvirtualclustergardenergardenerapiserverloggingwithhttpaccessverbosity)
          * [`fn withVerbosity(verbosity)`](#fn-specvirtualclustergardenergardenerapiserverloggingwithverbosity)
        * [`obj spec.virtualCluster.gardener.gardenerAPIServer.requests`](#obj-specvirtualclustergardenergardenerapiserverrequests)
          * [`fn withMaxMutatingInflight(maxMutatingInflight)`](#fn-specvirtualclustergardenergardenerapiserverrequestswithmaxmutatinginflight)
          * [`fn withMaxNonMutatingInflight(maxNonMutatingInflight)`](#fn-specvirtualclustergardenergardenerapiserverrequestswithmaxnonmutatinginflight)
        * [`obj spec.virtualCluster.gardener.gardenerAPIServer.watchCacheSizes`](#obj-specvirtualclustergardenergardenerapiserverwatchcachesizes)
          * [`fn withDefault(default)`](#fn-specvirtualclustergardenergardenerapiserverwatchcachesizeswithdefault)
          * [`fn withResources(resources)`](#fn-specvirtualclustergardenergardenerapiserverwatchcachesizeswithresources)
          * [`fn withResourcesMixin(resources)`](#fn-specvirtualclustergardenergardenerapiserverwatchcachesizeswithresourcesmixin)
          * [`obj spec.virtualCluster.gardener.gardenerAPIServer.watchCacheSizes.resources`](#obj-specvirtualclustergardenergardenerapiserverwatchcachesizesresources)
            * [`fn withApiGroup(apiGroup)`](#fn-specvirtualclustergardenergardenerapiserverwatchcachesizesresourceswithapigroup)
            * [`fn withResource(resource)`](#fn-specvirtualclustergardenergardenerapiserverwatchcachesizesresourceswithresource)
            * [`fn withSize(size)`](#fn-specvirtualclustergardenergardenerapiserverwatchcachesizesresourceswithsize)
      * [`obj spec.virtualCluster.gardener.gardenerAdmissionController`](#obj-specvirtualclustergardenergardeneradmissioncontroller)
        * [`fn withLogLevel(logLevel)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerwithloglevel)
        * [`obj spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration`](#obj-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfiguration)
          * [`fn withLimits(limits)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationwithlimits)
          * [`fn withLimitsMixin(limits)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationwithlimitsmixin)
          * [`fn withOperationMode(operationMode)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationwithoperationmode)
          * [`fn withUnrestrictedSubjects(unrestrictedSubjects)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationwithunrestrictedsubjects)
          * [`fn withUnrestrictedSubjectsMixin(unrestrictedSubjects)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationwithunrestrictedsubjectsmixin)
          * [`obj spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.limits`](#obj-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationlimits)
            * [`fn withApiGroups(apiGroups)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationlimitswithapigroups)
            * [`fn withApiGroupsMixin(apiGroups)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationlimitswithapigroupsmixin)
            * [`fn withApiVersions(apiVersions)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationlimitswithapiversions)
            * [`fn withApiVersionsMixin(apiVersions)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationlimitswithapiversionsmixin)
            * [`fn withCount(count)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationlimitswithcount)
            * [`fn withResources(resources)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationlimitswithresources)
            * [`fn withResourcesMixin(resources)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationlimitswithresourcesmixin)
            * [`fn withSize(size)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationlimitswithsize)
          * [`obj spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.unrestrictedSubjects`](#obj-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationunrestrictedsubjects)
            * [`fn withApiGroup(apiGroup)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationunrestrictedsubjectswithapigroup)
            * [`fn withKind(kind)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationunrestrictedsubjectswithkind)
            * [`fn withName(name)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationunrestrictedsubjectswithname)
            * [`fn withNamespace(namespace)`](#fn-specvirtualclustergardenergardeneradmissioncontrollerresourceadmissionconfigurationunrestrictedsubjectswithnamespace)
      * [`obj spec.virtualCluster.gardener.gardenerControllerManager`](#obj-specvirtualclustergardenergardenercontrollermanager)
        * [`fn withDefaultProjectQuotas(defaultProjectQuotas)`](#fn-specvirtualclustergardenergardenercontrollermanagerwithdefaultprojectquotas)
        * [`fn withDefaultProjectQuotasMixin(defaultProjectQuotas)`](#fn-specvirtualclustergardenergardenercontrollermanagerwithdefaultprojectquotasmixin)
        * [`fn withFeatureGates(featureGates)`](#fn-specvirtualclustergardenergardenercontrollermanagerwithfeaturegates)
        * [`fn withFeatureGatesMixin(featureGates)`](#fn-specvirtualclustergardenergardenercontrollermanagerwithfeaturegatesmixin)
        * [`fn withLogLevel(logLevel)`](#fn-specvirtualclustergardenergardenercontrollermanagerwithloglevel)
        * [`obj spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas`](#obj-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotas)
          * [`obj spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config`](#obj-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfig)
            * [`fn withApiVersion(apiVersion)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigwithapiversion)
            * [`fn withKind(kind)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigwithkind)
            * [`fn withMetadata(metadata)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigwithmetadata)
            * [`fn withMetadataMixin(metadata)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigwithmetadatamixin)
            * [`obj spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec`](#obj-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigspec)
              * [`fn withHard(hard)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigspecwithhard)
              * [`fn withHardMixin(hard)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigspecwithhardmixin)
              * [`fn withScopes(scopes)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigspecwithscopes)
              * [`fn withScopesMixin(scopes)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigspecwithscopesmixin)
              * [`obj spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec.scopeSelector`](#obj-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigspecscopeselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigspecscopeselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigspecscopeselectorwithmatchexpressionsmixin)
                * [`obj spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec.scopeSelector.matchExpressions`](#obj-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigspecscopeselectormatchexpressions)
                  * [`fn withOperator(operator)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigspecscopeselectormatchexpressionswithoperator)
                  * [`fn withScopeName(scopeName)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigspecscopeselectormatchexpressionswithscopename)
                  * [`fn withValues(values)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigspecscopeselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasconfigspecscopeselectormatchexpressionswithvaluesmixin)
          * [`obj spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.projectSelector`](#obj-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasprojectselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasprojectselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasprojectselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasprojectselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasprojectselectorwithmatchlabelsmixin)
            * [`obj spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.projectSelector.matchExpressions`](#obj-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasprojectselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasprojectselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasprojectselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasprojectselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specvirtualclustergardenergardenercontrollermanagerdefaultprojectquotasprojectselectormatchexpressionswithvaluesmixin)
      * [`obj spec.virtualCluster.gardener.gardenerDashboard`](#obj-specvirtualclustergardenergardenerdashboard)
        * [`fn withEnableTokenLogin(enableTokenLogin)`](#fn-specvirtualclustergardenergardenerdashboardwithenabletokenlogin)
        * [`fn withLogLevel(logLevel)`](#fn-specvirtualclustergardenergardenerdashboardwithloglevel)
        * [`obj spec.virtualCluster.gardener.gardenerDashboard.assetsConfigMapRef`](#obj-specvirtualclustergardenergardenerdashboardassetsconfigmapref)
          * [`fn withName(name)`](#fn-specvirtualclustergardenergardenerdashboardassetsconfigmaprefwithname)
        * [`obj spec.virtualCluster.gardener.gardenerDashboard.frontendConfigMapRef`](#obj-specvirtualclustergardenergardenerdashboardfrontendconfigmapref)
          * [`fn withName(name)`](#fn-specvirtualclustergardenergardenerdashboardfrontendconfigmaprefwithname)
        * [`obj spec.virtualCluster.gardener.gardenerDashboard.gitHub`](#obj-specvirtualclustergardenergardenerdashboardgithub)
          * [`fn withApiURL(apiURL)`](#fn-specvirtualclustergardenergardenerdashboardgithubwithapiurl)
          * [`fn withOrganisation(organisation)`](#fn-specvirtualclustergardenergardenerdashboardgithubwithorganisation)
          * [`fn withPollInterval(pollInterval)`](#fn-specvirtualclustergardenergardenerdashboardgithubwithpollinterval)
          * [`fn withRepository(repository)`](#fn-specvirtualclustergardenergardenerdashboardgithubwithrepository)
          * [`obj spec.virtualCluster.gardener.gardenerDashboard.gitHub.secretRef`](#obj-specvirtualclustergardenergardenerdashboardgithubsecretref)
            * [`fn withName(name)`](#fn-specvirtualclustergardenergardenerdashboardgithubsecretrefwithname)
        * [`obj spec.virtualCluster.gardener.gardenerDashboard.ingress`](#obj-specvirtualclustergardenergardenerdashboardingress)
          * [`fn withEnabled(enabled)`](#fn-specvirtualclustergardenergardenerdashboardingresswithenabled)
        * [`obj spec.virtualCluster.gardener.gardenerDashboard.oidcConfig`](#obj-specvirtualclustergardenergardenerdashboardoidcconfig)
          * [`fn withAdditionalScopes(additionalScopes)`](#fn-specvirtualclustergardenergardenerdashboardoidcconfigwithadditionalscopes)
          * [`fn withAdditionalScopesMixin(additionalScopes)`](#fn-specvirtualclustergardenergardenerdashboardoidcconfigwithadditionalscopesmixin)
          * [`fn withClientIDPublic(clientIDPublic)`](#fn-specvirtualclustergardenergardenerdashboardoidcconfigwithclientidpublic)
          * [`fn withIssuerURL(issuerURL)`](#fn-specvirtualclustergardenergardenerdashboardoidcconfigwithissuerurl)
          * [`fn withSessionLifetime(sessionLifetime)`](#fn-specvirtualclustergardenergardenerdashboardoidcconfigwithsessionlifetime)
          * [`obj spec.virtualCluster.gardener.gardenerDashboard.oidcConfig.certificateAuthoritySecretRef`](#obj-specvirtualclustergardenergardenerdashboardoidcconfigcertificateauthoritysecretref)
            * [`fn withName(name)`](#fn-specvirtualclustergardenergardenerdashboardoidcconfigcertificateauthoritysecretrefwithname)
          * [`obj spec.virtualCluster.gardener.gardenerDashboard.oidcConfig.secretRef`](#obj-specvirtualclustergardenergardenerdashboardoidcconfigsecretref)
            * [`fn withName(name)`](#fn-specvirtualclustergardenergardenerdashboardoidcconfigsecretrefwithname)
        * [`obj spec.virtualCluster.gardener.gardenerDashboard.terminal`](#obj-specvirtualclustergardenergardenerdashboardterminal)
          * [`fn withAllowedHosts(allowedHosts)`](#fn-specvirtualclustergardenergardenerdashboardterminalwithallowedhosts)
          * [`fn withAllowedHostsMixin(allowedHosts)`](#fn-specvirtualclustergardenergardenerdashboardterminalwithallowedhostsmixin)
          * [`obj spec.virtualCluster.gardener.gardenerDashboard.terminal.container`](#obj-specvirtualclustergardenergardenerdashboardterminalcontainer)
            * [`fn withDescription(description)`](#fn-specvirtualclustergardenergardenerdashboardterminalcontainerwithdescription)
            * [`fn withImage(image)`](#fn-specvirtualclustergardenergardenerdashboardterminalcontainerwithimage)
      * [`obj spec.virtualCluster.gardener.gardenerScheduler`](#obj-specvirtualclustergardenergardenerscheduler)
        * [`fn withFeatureGates(featureGates)`](#fn-specvirtualclustergardenergardenerschedulerwithfeaturegates)
        * [`fn withFeatureGatesMixin(featureGates)`](#fn-specvirtualclustergardenergardenerschedulerwithfeaturegatesmixin)
        * [`fn withLogLevel(logLevel)`](#fn-specvirtualclustergardenergardenerschedulerwithloglevel)
    * [`obj spec.virtualCluster.kubernetes`](#obj-specvirtualclusterkubernetes)
      * [`fn withVersion(version)`](#fn-specvirtualclusterkuberneteswithversion)
      * [`obj spec.virtualCluster.kubernetes.kubeAPIServer`](#obj-specvirtualclusterkuberneteskubeapiserver)
        * [`fn withAdmissionPlugins(admissionPlugins)`](#fn-specvirtualclusterkuberneteskubeapiserverwithadmissionplugins)
        * [`fn withAdmissionPluginsMixin(admissionPlugins)`](#fn-specvirtualclusterkuberneteskubeapiserverwithadmissionpluginsmixin)
        * [`fn withApiAudiences(apiAudiences)`](#fn-specvirtualclusterkuberneteskubeapiserverwithapiaudiences)
        * [`fn withApiAudiencesMixin(apiAudiences)`](#fn-specvirtualclusterkuberneteskubeapiserverwithapiaudiencesmixin)
        * [`fn withDefaultNotReadyTolerationSeconds(defaultNotReadyTolerationSeconds)`](#fn-specvirtualclusterkuberneteskubeapiserverwithdefaultnotreadytolerationseconds)
        * [`fn withDefaultUnreachableTolerationSeconds(defaultUnreachableTolerationSeconds)`](#fn-specvirtualclusterkuberneteskubeapiserverwithdefaultunreachabletolerationseconds)
        * [`fn withEnableAnonymousAuthentication(enableAnonymousAuthentication)`](#fn-specvirtualclusterkuberneteskubeapiserverwithenableanonymousauthentication)
        * [`fn withEventTTL(eventTTL)`](#fn-specvirtualclusterkuberneteskubeapiserverwitheventttl)
        * [`fn withFeatureGates(featureGates)`](#fn-specvirtualclusterkuberneteskubeapiserverwithfeaturegates)
        * [`fn withFeatureGatesMixin(featureGates)`](#fn-specvirtualclusterkuberneteskubeapiserverwithfeaturegatesmixin)
        * [`fn withResourcesToStoreInETCDEvents(resourcesToStoreInETCDEvents)`](#fn-specvirtualclusterkuberneteskubeapiserverwithresourcestostoreinetcdevents)
        * [`fn withResourcesToStoreInETCDEventsMixin(resourcesToStoreInETCDEvents)`](#fn-specvirtualclusterkuberneteskubeapiserverwithresourcestostoreinetcdeventsmixin)
        * [`fn withRuntimeConfig(runtimeConfig)`](#fn-specvirtualclusterkuberneteskubeapiserverwithruntimeconfig)
        * [`fn withRuntimeConfigMixin(runtimeConfig)`](#fn-specvirtualclusterkuberneteskubeapiserverwithruntimeconfigmixin)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.admissionPlugins`](#obj-specvirtualclusterkuberneteskubeapiserveradmissionplugins)
          * [`fn withConfig(config)`](#fn-specvirtualclusterkuberneteskubeapiserveradmissionpluginswithconfig)
          * [`fn withConfigMixin(config)`](#fn-specvirtualclusterkuberneteskubeapiserveradmissionpluginswithconfigmixin)
          * [`fn withDisabled(disabled)`](#fn-specvirtualclusterkuberneteskubeapiserveradmissionpluginswithdisabled)
          * [`fn withKubeconfigSecretName(kubeconfigSecretName)`](#fn-specvirtualclusterkuberneteskubeapiserveradmissionpluginswithkubeconfigsecretname)
          * [`fn withName(name)`](#fn-specvirtualclusterkuberneteskubeapiserveradmissionpluginswithname)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.auditConfig`](#obj-specvirtualclusterkuberneteskubeapiserverauditconfig)
          * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.auditConfig.auditPolicy`](#obj-specvirtualclusterkuberneteskubeapiserverauditconfigauditpolicy)
            * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.auditConfig.auditPolicy.configMapRef`](#obj-specvirtualclusterkuberneteskubeapiserverauditconfigauditpolicyconfigmapref)
              * [`fn withApiVersion(apiVersion)`](#fn-specvirtualclusterkuberneteskubeapiserverauditconfigauditpolicyconfigmaprefwithapiversion)
              * [`fn withFieldPath(fieldPath)`](#fn-specvirtualclusterkuberneteskubeapiserverauditconfigauditpolicyconfigmaprefwithfieldpath)
              * [`fn withKind(kind)`](#fn-specvirtualclusterkuberneteskubeapiserverauditconfigauditpolicyconfigmaprefwithkind)
              * [`fn withName(name)`](#fn-specvirtualclusterkuberneteskubeapiserverauditconfigauditpolicyconfigmaprefwithname)
              * [`fn withNamespace(namespace)`](#fn-specvirtualclusterkuberneteskubeapiserverauditconfigauditpolicyconfigmaprefwithnamespace)
              * [`fn withResourceVersion(resourceVersion)`](#fn-specvirtualclusterkuberneteskubeapiserverauditconfigauditpolicyconfigmaprefwithresourceversion)
              * [`fn withUid(uid)`](#fn-specvirtualclusterkuberneteskubeapiserverauditconfigauditpolicyconfigmaprefwithuid)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.auditWebhook`](#obj-specvirtualclusterkuberneteskubeapiserverauditwebhook)
          * [`fn withBatchMaxSize(batchMaxSize)`](#fn-specvirtualclusterkuberneteskubeapiserverauditwebhookwithbatchmaxsize)
          * [`fn withKubeconfigSecretName(kubeconfigSecretName)`](#fn-specvirtualclusterkuberneteskubeapiserverauditwebhookwithkubeconfigsecretname)
          * [`fn withVersion(version)`](#fn-specvirtualclusterkuberneteskubeapiserverauditwebhookwithversion)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.authentication`](#obj-specvirtualclusterkuberneteskubeapiserverauthentication)
          * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.authentication.webhook`](#obj-specvirtualclusterkuberneteskubeapiserverauthenticationwebhook)
            * [`fn withCacheTTL(cacheTTL)`](#fn-specvirtualclusterkuberneteskubeapiserverauthenticationwebhookwithcachettl)
            * [`fn withKubeconfigSecretName(kubeconfigSecretName)`](#fn-specvirtualclusterkuberneteskubeapiserverauthenticationwebhookwithkubeconfigsecretname)
            * [`fn withVersion(version)`](#fn-specvirtualclusterkuberneteskubeapiserverauthenticationwebhookwithversion)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.autoscaling`](#obj-specvirtualclusterkuberneteskubeapiserverautoscaling)
          * [`fn withMinAllowed(minAllowed)`](#fn-specvirtualclusterkuberneteskubeapiserverautoscalingwithminallowed)
          * [`fn withMinAllowedMixin(minAllowed)`](#fn-specvirtualclusterkuberneteskubeapiserverautoscalingwithminallowedmixin)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.encryptionConfig`](#obj-specvirtualclusterkuberneteskubeapiserverencryptionconfig)
          * [`fn withResources(resources)`](#fn-specvirtualclusterkuberneteskubeapiserverencryptionconfigwithresources)
          * [`fn withResourcesMixin(resources)`](#fn-specvirtualclusterkuberneteskubeapiserverencryptionconfigwithresourcesmixin)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.logging`](#obj-specvirtualclusterkuberneteskubeapiserverlogging)
          * [`fn withHttpAccessVerbosity(httpAccessVerbosity)`](#fn-specvirtualclusterkuberneteskubeapiserverloggingwithhttpaccessverbosity)
          * [`fn withVerbosity(verbosity)`](#fn-specvirtualclusterkuberneteskubeapiserverloggingwithverbosity)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig`](#obj-specvirtualclusterkuberneteskubeapiserveroidcconfig)
          * [`fn withCaBundle(caBundle)`](#fn-specvirtualclusterkuberneteskubeapiserveroidcconfigwithcabundle)
          * [`fn withClientID(clientID)`](#fn-specvirtualclusterkuberneteskubeapiserveroidcconfigwithclientid)
          * [`fn withGroupsClaim(groupsClaim)`](#fn-specvirtualclusterkuberneteskubeapiserveroidcconfigwithgroupsclaim)
          * [`fn withGroupsPrefix(groupsPrefix)`](#fn-specvirtualclusterkuberneteskubeapiserveroidcconfigwithgroupsprefix)
          * [`fn withIssuerURL(issuerURL)`](#fn-specvirtualclusterkuberneteskubeapiserveroidcconfigwithissuerurl)
          * [`fn withRequiredClaims(requiredClaims)`](#fn-specvirtualclusterkuberneteskubeapiserveroidcconfigwithrequiredclaims)
          * [`fn withRequiredClaimsMixin(requiredClaims)`](#fn-specvirtualclusterkuberneteskubeapiserveroidcconfigwithrequiredclaimsmixin)
          * [`fn withSigningAlgs(signingAlgs)`](#fn-specvirtualclusterkuberneteskubeapiserveroidcconfigwithsigningalgs)
          * [`fn withSigningAlgsMixin(signingAlgs)`](#fn-specvirtualclusterkuberneteskubeapiserveroidcconfigwithsigningalgsmixin)
          * [`fn withUsernameClaim(usernameClaim)`](#fn-specvirtualclusterkuberneteskubeapiserveroidcconfigwithusernameclaim)
          * [`fn withUsernamePrefix(usernamePrefix)`](#fn-specvirtualclusterkuberneteskubeapiserveroidcconfigwithusernameprefix)
          * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.clientAuthentication`](#obj-specvirtualclusterkuberneteskubeapiserveroidcconfigclientauthentication)
            * [`fn withExtraConfig(extraConfig)`](#fn-specvirtualclusterkuberneteskubeapiserveroidcconfigclientauthenticationwithextraconfig)
            * [`fn withExtraConfigMixin(extraConfig)`](#fn-specvirtualclusterkuberneteskubeapiserveroidcconfigclientauthenticationwithextraconfigmixin)
            * [`fn withSecret(secret)`](#fn-specvirtualclusterkuberneteskubeapiserveroidcconfigclientauthenticationwithsecret)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.requests`](#obj-specvirtualclusterkuberneteskubeapiserverrequests)
          * [`fn withMaxMutatingInflight(maxMutatingInflight)`](#fn-specvirtualclusterkuberneteskubeapiserverrequestswithmaxmutatinginflight)
          * [`fn withMaxNonMutatingInflight(maxNonMutatingInflight)`](#fn-specvirtualclusterkuberneteskubeapiserverrequestswithmaxnonmutatinginflight)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.resourcesToStoreInETCDEvents`](#obj-specvirtualclusterkuberneteskubeapiserverresourcestostoreinetcdevents)
          * [`fn withGroup(group)`](#fn-specvirtualclusterkuberneteskubeapiserverresourcestostoreinetcdeventswithgroup)
          * [`fn withResource(resource)`](#fn-specvirtualclusterkuberneteskubeapiserverresourcestostoreinetcdeventswithresource)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.serviceAccountConfig`](#obj-specvirtualclusterkuberneteskubeapiserverserviceaccountconfig)
          * [`fn withAcceptedIssuers(acceptedIssuers)`](#fn-specvirtualclusterkuberneteskubeapiserverserviceaccountconfigwithacceptedissuers)
          * [`fn withAcceptedIssuersMixin(acceptedIssuers)`](#fn-specvirtualclusterkuberneteskubeapiserverserviceaccountconfigwithacceptedissuersmixin)
          * [`fn withExtendTokenExpiration(extendTokenExpiration)`](#fn-specvirtualclusterkuberneteskubeapiserverserviceaccountconfigwithextendtokenexpiration)
          * [`fn withIssuer(issuer)`](#fn-specvirtualclusterkuberneteskubeapiserverserviceaccountconfigwithissuer)
          * [`fn withMaxTokenExpiration(maxTokenExpiration)`](#fn-specvirtualclusterkuberneteskubeapiserverserviceaccountconfigwithmaxtokenexpiration)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.sni`](#obj-specvirtualclusterkuberneteskubeapiserversni)
          * [`fn withDomainPatterns(domainPatterns)`](#fn-specvirtualclusterkuberneteskubeapiserversniwithdomainpatterns)
          * [`fn withDomainPatternsMixin(domainPatterns)`](#fn-specvirtualclusterkuberneteskubeapiserversniwithdomainpatternsmixin)
          * [`fn withSecretName(secretName)`](#fn-specvirtualclusterkuberneteskubeapiserversniwithsecretname)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.structuredAuthentication`](#obj-specvirtualclusterkuberneteskubeapiserverstructuredauthentication)
          * [`fn withConfigMapName(configMapName)`](#fn-specvirtualclusterkuberneteskubeapiserverstructuredauthenticationwithconfigmapname)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.structuredAuthorization`](#obj-specvirtualclusterkuberneteskubeapiserverstructuredauthorization)
          * [`fn withConfigMapName(configMapName)`](#fn-specvirtualclusterkuberneteskubeapiserverstructuredauthorizationwithconfigmapname)
          * [`fn withKubeconfigs(kubeconfigs)`](#fn-specvirtualclusterkuberneteskubeapiserverstructuredauthorizationwithkubeconfigs)
          * [`fn withKubeconfigsMixin(kubeconfigs)`](#fn-specvirtualclusterkuberneteskubeapiserverstructuredauthorizationwithkubeconfigsmixin)
          * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.structuredAuthorization.kubeconfigs`](#obj-specvirtualclusterkuberneteskubeapiserverstructuredauthorizationkubeconfigs)
            * [`fn withAuthorizerName(authorizerName)`](#fn-specvirtualclusterkuberneteskubeapiserverstructuredauthorizationkubeconfigswithauthorizername)
            * [`fn withSecretName(secretName)`](#fn-specvirtualclusterkuberneteskubeapiserverstructuredauthorizationkubeconfigswithsecretname)
        * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.watchCacheSizes`](#obj-specvirtualclusterkuberneteskubeapiserverwatchcachesizes)
          * [`fn withDefault(default)`](#fn-specvirtualclusterkuberneteskubeapiserverwatchcachesizeswithdefault)
          * [`fn withResources(resources)`](#fn-specvirtualclusterkuberneteskubeapiserverwatchcachesizeswithresources)
          * [`fn withResourcesMixin(resources)`](#fn-specvirtualclusterkuberneteskubeapiserverwatchcachesizeswithresourcesmixin)
          * [`obj spec.virtualCluster.kubernetes.kubeAPIServer.watchCacheSizes.resources`](#obj-specvirtualclusterkuberneteskubeapiserverwatchcachesizesresources)
            * [`fn withApiGroup(apiGroup)`](#fn-specvirtualclusterkuberneteskubeapiserverwatchcachesizesresourceswithapigroup)
            * [`fn withResource(resource)`](#fn-specvirtualclusterkuberneteskubeapiserverwatchcachesizesresourceswithresource)
            * [`fn withSize(size)`](#fn-specvirtualclusterkuberneteskubeapiserverwatchcachesizesresourceswithsize)
      * [`obj spec.virtualCluster.kubernetes.kubeControllerManager`](#obj-specvirtualclusterkuberneteskubecontrollermanager)
        * [`fn withCertificateSigningDuration(certificateSigningDuration)`](#fn-specvirtualclusterkuberneteskubecontrollermanagerwithcertificatesigningduration)
        * [`fn withFeatureGates(featureGates)`](#fn-specvirtualclusterkuberneteskubecontrollermanagerwithfeaturegates)
        * [`fn withFeatureGatesMixin(featureGates)`](#fn-specvirtualclusterkuberneteskubecontrollermanagerwithfeaturegatesmixin)
        * [`fn withNodeCIDRMaskSize(nodeCIDRMaskSize)`](#fn-specvirtualclusterkuberneteskubecontrollermanagerwithnodecidrmasksize)
        * [`fn withNodeMonitorGracePeriod(nodeMonitorGracePeriod)`](#fn-specvirtualclusterkuberneteskubecontrollermanagerwithnodemonitorgraceperiod)
        * [`fn withPodEvictionTimeout(podEvictionTimeout)`](#fn-specvirtualclusterkuberneteskubecontrollermanagerwithpodevictiontimeout)
        * [`obj spec.virtualCluster.kubernetes.kubeControllerManager.horizontalPodAutoscaler`](#obj-specvirtualclusterkuberneteskubecontrollermanagerhorizontalpodautoscaler)
          * [`fn withCpuInitializationPeriod(cpuInitializationPeriod)`](#fn-specvirtualclusterkuberneteskubecontrollermanagerhorizontalpodautoscalerwithcpuinitializationperiod)
          * [`fn withDownscaleStabilization(downscaleStabilization)`](#fn-specvirtualclusterkuberneteskubecontrollermanagerhorizontalpodautoscalerwithdownscalestabilization)
          * [`fn withInitialReadinessDelay(initialReadinessDelay)`](#fn-specvirtualclusterkuberneteskubecontrollermanagerhorizontalpodautoscalerwithinitialreadinessdelay)
          * [`fn withSyncPeriod(syncPeriod)`](#fn-specvirtualclusterkuberneteskubecontrollermanagerhorizontalpodautoscalerwithsyncperiod)
          * [`fn withTolerance(tolerance)`](#fn-specvirtualclusterkuberneteskubecontrollermanagerhorizontalpodautoscalerwithtolerance)
    * [`obj spec.virtualCluster.maintenance`](#obj-specvirtualclustermaintenance)
      * [`obj spec.virtualCluster.maintenance.timeWindow`](#obj-specvirtualclustermaintenancetimewindow)
        * [`fn withBegin(begin)`](#fn-specvirtualclustermaintenancetimewindowwithbegin)
        * [`fn withEnd(end)`](#fn-specvirtualclustermaintenancetimewindowwithend)
    * [`obj spec.virtualCluster.networking`](#obj-specvirtualclusternetworking)
      * [`fn withServices(services)`](#fn-specvirtualclusternetworkingwithservices)
      * [`fn withServicesMixin(services)`](#fn-specvirtualclusternetworkingwithservicesmixin)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of Garden

## obj metadata

"ObjectMeta is metadata that all persisted resources must have, which includes all objects users must create."

### fn metadata.withAnnotations

```ts
withAnnotations(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

### fn metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

**Note:** This function appends passed data to existing values

### fn metadata.withClusterName

```ts
withClusterName(clusterName)
```

"The name of the cluster which the object belongs to. This is used to distinguish resources with same name and namespace in different clusters. This field is not set anywhere right now and apiserver is going to ignore it if set in create or update request."

### fn metadata.withCreationTimestamp

```ts
withCreationTimestamp(creationTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withDeletionGracePeriodSeconds

```ts
withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)
```

"Number of seconds allowed for this object to gracefully terminate before it will be removed from the system. Only set when deletionTimestamp is also set. May only be shortened. Read-only."

### fn metadata.withDeletionTimestamp

```ts
withDeletionTimestamp(deletionTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withFinalizers

```ts
withFinalizers(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

### fn metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

**Note:** This function appends passed data to existing values

### fn metadata.withGenerateName

```ts
withGenerateName(generateName)
```

"GenerateName is an optional prefix, used by the server, to generate a unique name ONLY IF the Name field has not been provided. If this field is used, the name returned to the client will be different than the name passed. This value will also be combined with a unique suffix. The provided value has the same validation rules as the Name field, and may be truncated by the length of the suffix required to make the value unique on the server.\n\nIf this field is specified and the generated name exists, the server will NOT return a 409 - instead, it will either return 201 Created or 500 with Reason ServerTimeout indicating a unique name could not be found in the time allotted, and the client should retry (optionally after the time indicated in the Retry-After header).\n\nApplied only if Name is not specified. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#idempotency"

### fn metadata.withGeneration

```ts
withGeneration(generation)
```

"A sequence number representing a specific generation of the desired state. Populated by the system. Read-only."

### fn metadata.withLabels

```ts
withLabels(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

### fn metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

**Note:** This function appends passed data to existing values

### fn metadata.withName

```ts
withName(name)
```

"Name must be unique within a namespace. Is required when creating resources, although some resources may allow a client to request the generation of an appropriate name automatically. Name is primarily intended for creation idempotence and configuration definition. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/identifiers#names"

### fn metadata.withNamespace

```ts
withNamespace(namespace)
```

"Namespace defines the space within which each name must be unique. An empty namespace is equivalent to the \"default\" namespace, but \"default\" is the canonical representation. Not all objects are required to be scoped to a namespace - the value of this field for those objects will be empty.\n\nMust be a DNS_LABEL. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/namespaces"

### fn metadata.withOwnerReferences

```ts
withOwnerReferences(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

### fn metadata.withOwnerReferencesMixin

```ts
withOwnerReferencesMixin(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

**Note:** This function appends passed data to existing values

### fn metadata.withResourceVersion

```ts
withResourceVersion(resourceVersion)
```

"An opaque value that represents the internal version of this object that can be used by clients to determine when objects have changed. May be used for optimistic concurrency, change detection, and the watch operation on a resource or set of resources. Clients must treat these values as opaque and passed unmodified back to the server. They may only be valid for a particular resource or set of resources.\n\nPopulated by the system. Read-only. Value must be treated as opaque by clients and . More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#concurrency-control-and-consistency"

### fn metadata.withSelfLink

```ts
withSelfLink(selfLink)
```

"SelfLink is a URL representing this object. Populated by the system. Read-only.\n\nDEPRECATED Kubernetes will stop propagating this field in 1.20 release and the field is planned to be removed in 1.21 release."

### fn metadata.withUid

```ts
withUid(uid)
```

"UID is the unique in time and space value for this object. It is typically generated by the server on successful creation of a resource and is not allowed to change on PUT operations.\n\nPopulated by the system. Read-only. More info: http://kubernetes.io/docs/user-guide/identifiers#uids"

## obj spec

"Spec contains the specification of this garden."

### fn spec.withExtensions

```ts
withExtensions(extensions)
```

"Extensions contain type and provider information for Garden extensions."

### fn spec.withExtensionsMixin

```ts
withExtensionsMixin(extensions)
```

"Extensions contain type and provider information for Garden extensions."

**Note:** This function appends passed data to existing values

## obj spec.dns

"DNS contains specifications of DNS providers."

### fn spec.dns.withProviders

```ts
withProviders(providers)
```

"Providers is a list of DNS providers."

### fn spec.dns.withProvidersMixin

```ts
withProvidersMixin(providers)
```

"Providers is a list of DNS providers."

**Note:** This function appends passed data to existing values

## obj spec.dns.providers

"Providers is a list of DNS providers."

### fn spec.dns.providers.withName

```ts
withName(name)
```

"Name is the name of the DNS provider."

### fn spec.dns.providers.withProviderConfig

```ts
withProviderConfig(providerConfig)
```

"Config is the provider-specific configuration passed to DNSRecord resources."

### fn spec.dns.providers.withProviderConfigMixin

```ts
withProviderConfigMixin(providerConfig)
```

"Config is the provider-specific configuration passed to DNSRecord resources."

**Note:** This function appends passed data to existing values

### fn spec.dns.providers.withType

```ts
withType(type)
```

"Type is the type of the DNS provider."

## obj spec.dns.providers.secretRef

"SecretRef is a reference to a Secret object containing the DNS provider credentials."

### fn spec.dns.providers.secretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.extensions

"Extensions contain type and provider information for Garden extensions."

### fn spec.extensions.withProviderConfig

```ts
withProviderConfig(providerConfig)
```

"ProviderConfig is the configuration passed to extension resource."

### fn spec.extensions.withProviderConfigMixin

```ts
withProviderConfigMixin(providerConfig)
```

"ProviderConfig is the configuration passed to extension resource."

**Note:** This function appends passed data to existing values

### fn spec.extensions.withType

```ts
withType(type)
```

"Type is the type of the extension resource."

## obj spec.runtimeCluster

"RuntimeCluster contains configuration for the runtime cluster."

## obj spec.runtimeCluster.ingress

"Ingress configures Ingress specific settings for the Garden cluster."

### fn spec.runtimeCluster.ingress.withDomains

```ts
withDomains(domains)
```

"Domains specify the ingress domains of the cluster pointing to the ingress controller endpoint. They will be used\nto construct ingress URLs for system applications running in runtime cluster."

### fn spec.runtimeCluster.ingress.withDomainsMixin

```ts
withDomainsMixin(domains)
```

"Domains specify the ingress domains of the cluster pointing to the ingress controller endpoint. They will be used\nto construct ingress URLs for system applications running in runtime cluster."

**Note:** This function appends passed data to existing values

## obj spec.runtimeCluster.ingress.controller

"Controller configures a Gardener managed Ingress Controller listening on the ingressDomain."

### fn spec.runtimeCluster.ingress.controller.withKind

```ts
withKind(kind)
```

"Kind defines which kind of IngressController to use. At the moment only `nginx` is supported"

### fn spec.runtimeCluster.ingress.controller.withProviderConfig

```ts
withProviderConfig(providerConfig)
```

"ProviderConfig specifies infrastructure specific configuration for the ingressController"

### fn spec.runtimeCluster.ingress.controller.withProviderConfigMixin

```ts
withProviderConfigMixin(providerConfig)
```

"ProviderConfig specifies infrastructure specific configuration for the ingressController"

**Note:** This function appends passed data to existing values

## obj spec.runtimeCluster.ingress.domains

"Domains specify the ingress domains of the cluster pointing to the ingress controller endpoint. They will be used\nto construct ingress URLs for system applications running in runtime cluster."

### fn spec.runtimeCluster.ingress.domains.withName

```ts
withName(name)
```

"Name is the domain name."

### fn spec.runtimeCluster.ingress.domains.withProvider

```ts
withProvider(provider)
```

"Provider is the name of the DNS provider as declared in the '.spec.dns.providers' section.\nIt is only optional, if the `.spec.dns` section is not provided at all."

## obj spec.runtimeCluster.networking

"Networking defines the networking configuration of the runtime cluster."

### fn spec.runtimeCluster.networking.withBlockCIDRs

```ts
withBlockCIDRs(blockCIDRs)
```

"BlockCIDRs is a list of network addresses that should be blocked."

### fn spec.runtimeCluster.networking.withBlockCIDRsMixin

```ts
withBlockCIDRsMixin(blockCIDRs)
```

"BlockCIDRs is a list of network addresses that should be blocked."

**Note:** This function appends passed data to existing values

### fn spec.runtimeCluster.networking.withIpFamilies

```ts
withIpFamilies(ipFamilies)
```

"IPFamilies specifies the IP protocol versions to use for the runtime cluster's networking. This field is\nimmutable.\nDefaults to [\"IPv4\"]."

### fn spec.runtimeCluster.networking.withIpFamiliesMixin

```ts
withIpFamiliesMixin(ipFamilies)
```

"IPFamilies specifies the IP protocol versions to use for the runtime cluster's networking. This field is\nimmutable.\nDefaults to [\"IPv4\"]."

**Note:** This function appends passed data to existing values

### fn spec.runtimeCluster.networking.withNodes

```ts
withNodes(nodes)
```

"Nodes are the CIDRs of the node network. Elements can be appended to this list, but not removed."

### fn spec.runtimeCluster.networking.withNodesMixin

```ts
withNodesMixin(nodes)
```

"Nodes are the CIDRs of the node network. Elements can be appended to this list, but not removed."

**Note:** This function appends passed data to existing values

### fn spec.runtimeCluster.networking.withPods

```ts
withPods(pods)
```

"Pods are the CIDRs of the pod network. Elements can be appended to this list, but not removed."

### fn spec.runtimeCluster.networking.withPodsMixin

```ts
withPodsMixin(pods)
```

"Pods are the CIDRs of the pod network. Elements can be appended to this list, but not removed."

**Note:** This function appends passed data to existing values

### fn spec.runtimeCluster.networking.withServices

```ts
withServices(services)
```

"Services are the CIDRs of the service network. Elements can be appended to this list, but not removed."

### fn spec.runtimeCluster.networking.withServicesMixin

```ts
withServicesMixin(services)
```

"Services are the CIDRs of the service network. Elements can be appended to this list, but not removed."

**Note:** This function appends passed data to existing values

## obj spec.runtimeCluster.provider

"Provider defines the provider-specific information for this cluster."

### fn spec.runtimeCluster.provider.withRegion

```ts
withRegion(region)
```

"Region is the region the cluster is deployed to."

### fn spec.runtimeCluster.provider.withZones

```ts
withZones(zones)
```

"Zones is the list of availability zones the cluster is deployed to."

### fn spec.runtimeCluster.provider.withZonesMixin

```ts
withZonesMixin(zones)
```

"Zones is the list of availability zones the cluster is deployed to."

**Note:** This function appends passed data to existing values

## obj spec.runtimeCluster.settings

"Settings contains certain settings for this cluster."

## obj spec.runtimeCluster.settings.loadBalancerServices

"LoadBalancerServices controls certain settings for services of type load balancer that are created in the runtime\ncluster."

### fn spec.runtimeCluster.settings.loadBalancerServices.withAnnotations

```ts
withAnnotations(annotations)
```

"Annotations is a map of annotations that will be injected/merged into every load balancer service object."

### fn spec.runtimeCluster.settings.loadBalancerServices.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Annotations is a map of annotations that will be injected/merged into every load balancer service object."

**Note:** This function appends passed data to existing values

## obj spec.runtimeCluster.settings.topologyAwareRouting

"TopologyAwareRouting controls certain settings for topology-aware traffic routing in the cluster.\nSee https://github.com/gardener/gardener/blob/master/docs/operations/topology_aware_routing.md."

### fn spec.runtimeCluster.settings.topologyAwareRouting.withEnabled

```ts
withEnabled(enabled)
```

"Enabled controls whether certain Services deployed in the cluster should be topology-aware.\nThese Services are virtual-garden-etcd-main-client, virtual-garden-etcd-events-client and virtual-garden-kube-apiserver.\nAdditionally, other components that are deployed to the runtime cluster via other means can read this field and\naccording to its value enable/disable topology-aware routing for their Services."

## obj spec.runtimeCluster.settings.verticalPodAutoscaler

"VerticalPodAutoscaler controls certain settings for the vertical pod autoscaler components deployed in the\ncluster."

### fn spec.runtimeCluster.settings.verticalPodAutoscaler.withEnabled

```ts
withEnabled(enabled)
```

"Enabled controls whether the VPA components shall be deployed into this cluster. It is true by default because\nthe operator (and Gardener) heavily rely on a VPA being deployed. You should only disable this if your runtime\ncluster already has another, manually/custom managed VPA deployment. If this is not the case, but you still\ndisable it, then reconciliation will fail."

### fn spec.runtimeCluster.settings.verticalPodAutoscaler.withFeatureGates

```ts
withFeatureGates(featureGates)
```

"FeatureGates contains information about enabled feature gates."

### fn spec.runtimeCluster.settings.verticalPodAutoscaler.withFeatureGatesMixin

```ts
withFeatureGatesMixin(featureGates)
```

"FeatureGates contains information about enabled feature gates."

**Note:** This function appends passed data to existing values

### fn spec.runtimeCluster.settings.verticalPodAutoscaler.withMaxAllowed

```ts
withMaxAllowed(maxAllowed)
```

"MaxAllowed specifies the global maximum allowed (maximum amount of resources) that vpa-recommender can recommend for a container.\nThe VerticalPodAutoscaler-level maximum allowed takes precedence over the global maximum allowed.\nFor more information, see https://github.com/kubernetes/autoscaler/blob/master/vertical-pod-autoscaler/docs/examples.md#specifying-global-maximum-allowed-resources-to-prevent-pods-from-being-unschedulable.\n\nDefaults to nil (no maximum)."

### fn spec.runtimeCluster.settings.verticalPodAutoscaler.withMaxAllowedMixin

```ts
withMaxAllowedMixin(maxAllowed)
```

"MaxAllowed specifies the global maximum allowed (maximum amount of resources) that vpa-recommender can recommend for a container.\nThe VerticalPodAutoscaler-level maximum allowed takes precedence over the global maximum allowed.\nFor more information, see https://github.com/kubernetes/autoscaler/blob/master/vertical-pod-autoscaler/docs/examples.md#specifying-global-maximum-allowed-resources-to-prevent-pods-from-being-unschedulable.\n\nDefaults to nil (no maximum)."

**Note:** This function appends passed data to existing values

## obj spec.runtimeCluster.volume

"Volume contains settings for persistent volumes created in the runtime cluster."

### fn spec.runtimeCluster.volume.withMinimumSize

```ts
withMinimumSize(minimumSize)
```

"MinimumSize defines the minimum size that should be used for PVCs in the runtime cluster."

## obj spec.virtualCluster

"VirtualCluster contains configuration for the virtual cluster."

## obj spec.virtualCluster.controlPlane

"ControlPlane holds information about the general settings for the control plane of the virtual cluster."

### fn spec.virtualCluster.controlPlane.withHighAvailability

```ts
withHighAvailability(highAvailability)
```

"HighAvailability holds the configuration settings for high availability settings."

### fn spec.virtualCluster.controlPlane.withHighAvailabilityMixin

```ts
withHighAvailabilityMixin(highAvailability)
```

"HighAvailability holds the configuration settings for high availability settings."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.dns

"DNS holds information about DNS settings."

### fn spec.virtualCluster.dns.withDomains

```ts
withDomains(domains)
```

"Domains are the external domains of the virtual garden cluster.\nThe first given domain in this list is immutable."

### fn spec.virtualCluster.dns.withDomainsMixin

```ts
withDomainsMixin(domains)
```

"Domains are the external domains of the virtual garden cluster.\nThe first given domain in this list is immutable."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.dns.domains

"Domains are the external domains of the virtual garden cluster.\nThe first given domain in this list is immutable."

### fn spec.virtualCluster.dns.domains.withName

```ts
withName(name)
```

"Name is the domain name."

### fn spec.virtualCluster.dns.domains.withProvider

```ts
withProvider(provider)
```

"Provider is the name of the DNS provider as declared in the '.spec.dns.providers' section.\nIt is only optional, if the `.spec.dns` section is not provided at all."

## obj spec.virtualCluster.etcd

"ETCD contains configuration for the etcds of the virtual garden cluster."

## obj spec.virtualCluster.etcd.events

"Events contains configuration for the events etcd."

## obj spec.virtualCluster.etcd.events.autoscaling

"Autoscaling contains auto-scaling configuration options for etcd."

### fn spec.virtualCluster.etcd.events.autoscaling.withMinAllowed

```ts
withMinAllowed(minAllowed)
```

"MinAllowed configures the minimum allowed resource requests for vertical pod autoscaling..\nConfiguration of minAllowed resources is an advanced feature that can help clusters to overcome scale-up delays.\nDefault values are not applied to this field."

### fn spec.virtualCluster.etcd.events.autoscaling.withMinAllowedMixin

```ts
withMinAllowedMixin(minAllowed)
```

"MinAllowed configures the minimum allowed resource requests for vertical pod autoscaling..\nConfiguration of minAllowed resources is an advanced feature that can help clusters to overcome scale-up delays.\nDefault values are not applied to this field."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.etcd.events.storage

"Storage contains storage configuration."

### fn spec.virtualCluster.etcd.events.storage.withCapacity

```ts
withCapacity(capacity)
```

"Capacity is the storage capacity for the volumes."

### fn spec.virtualCluster.etcd.events.storage.withClassName

```ts
withClassName(className)
```

"ClassName is the name of a storage class."

## obj spec.virtualCluster.etcd.main

"Main contains configuration for the main etcd."

## obj spec.virtualCluster.etcd.main.autoscaling

"Autoscaling contains auto-scaling configuration options for etcd."

### fn spec.virtualCluster.etcd.main.autoscaling.withMinAllowed

```ts
withMinAllowed(minAllowed)
```

"MinAllowed configures the minimum allowed resource requests for vertical pod autoscaling..\nConfiguration of minAllowed resources is an advanced feature that can help clusters to overcome scale-up delays.\nDefault values are not applied to this field."

### fn spec.virtualCluster.etcd.main.autoscaling.withMinAllowedMixin

```ts
withMinAllowedMixin(minAllowed)
```

"MinAllowed configures the minimum allowed resource requests for vertical pod autoscaling..\nConfiguration of minAllowed resources is an advanced feature that can help clusters to overcome scale-up delays.\nDefault values are not applied to this field."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.etcd.main.backup

"Backup contains the object store configuration for backups for the virtual garden etcd."

### fn spec.virtualCluster.etcd.main.backup.withBucketName

```ts
withBucketName(bucketName)
```

"BucketName is the name of the backup bucket. If not provided, gardener-operator attempts to manage a new bucket.\nIn this case, the cloud provider credentials provided in the SecretRef must have enough privileges for creating\nand deleting buckets."

### fn spec.virtualCluster.etcd.main.backup.withProvider

```ts
withProvider(provider)
```

"Provider is a provider name. This field is immutable."

### fn spec.virtualCluster.etcd.main.backup.withProviderConfig

```ts
withProviderConfig(providerConfig)
```

"ProviderConfig is the provider-specific configuration passed to BackupBucket resource."

### fn spec.virtualCluster.etcd.main.backup.withProviderConfigMixin

```ts
withProviderConfigMixin(providerConfig)
```

"ProviderConfig is the provider-specific configuration passed to BackupBucket resource."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.etcd.main.backup.withRegion

```ts
withRegion(region)
```

"Region is a region name. If undefined, the provider region is used. This field is immutable."

## obj spec.virtualCluster.etcd.main.backup.secretRef

"SecretRef is a reference to a Secret object containing the cloud provider credentials for the object store where\nbackups should be stored. It should have enough privileges to manipulate the objects as well as buckets."

### fn spec.virtualCluster.etcd.main.backup.secretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.virtualCluster.etcd.main.storage

"Storage contains storage configuration."

### fn spec.virtualCluster.etcd.main.storage.withCapacity

```ts
withCapacity(capacity)
```

"Capacity is the storage capacity for the volumes."

### fn spec.virtualCluster.etcd.main.storage.withClassName

```ts
withClassName(className)
```

"ClassName is the name of a storage class."

## obj spec.virtualCluster.gardener

"Gardener contains the configuration options for the Gardener control plane components."

### fn spec.virtualCluster.gardener.withClusterIdentity

```ts
withClusterIdentity(clusterIdentity)
```

"ClusterIdentity is the identity of the garden cluster. This field is immutable."

### fn spec.virtualCluster.gardener.withGardenerDiscoveryServer

```ts
withGardenerDiscoveryServer(gardenerDiscoveryServer)
```

"DiscoveryServer contains configuration settings for the gardener-discovery-server."

### fn spec.virtualCluster.gardener.withGardenerDiscoveryServerMixin

```ts
withGardenerDiscoveryServerMixin(gardenerDiscoveryServer)
```

"DiscoveryServer contains configuration settings for the gardener-discovery-server."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.gardener.gardenerAPIServer

"APIServer contains configuration settings for the gardener-apiserver."

### fn spec.virtualCluster.gardener.gardenerAPIServer.withAdmissionPlugins

```ts
withAdmissionPlugins(admissionPlugins)
```

"AdmissionPlugins contains the list of user-defined admission plugins (additional to those managed by Gardener),\nand, if desired, the corresponding configuration."

### fn spec.virtualCluster.gardener.gardenerAPIServer.withAdmissionPluginsMixin

```ts
withAdmissionPluginsMixin(admissionPlugins)
```

"AdmissionPlugins contains the list of user-defined admission plugins (additional to those managed by Gardener),\nand, if desired, the corresponding configuration."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.gardener.gardenerAPIServer.withFeatureGates

```ts
withFeatureGates(featureGates)
```

"FeatureGates contains information about enabled feature gates."

### fn spec.virtualCluster.gardener.gardenerAPIServer.withFeatureGatesMixin

```ts
withFeatureGatesMixin(featureGates)
```

"FeatureGates contains information about enabled feature gates."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.gardener.gardenerAPIServer.withGoAwayChance

```ts
withGoAwayChance(goAwayChance)
```

"GoAwayChance can be used to prevent HTTP/2 clients from getting stuck on a single apiserver, randomly close a\nconnection (GOAWAY). The client's other in-flight requests won't be affected, and the client will reconnect,\nlikely landing on a different apiserver after going through the load balancer again. This field sets the fraction\nof requests that will be sent a GOAWAY. Min is 0 (off), Max is 0.02 (1/50 requests); 0.001 (1/1000) is a\nrecommended starting point."

### fn spec.virtualCluster.gardener.gardenerAPIServer.withShootAdminKubeconfigMaxExpiration

```ts
withShootAdminKubeconfigMaxExpiration(shootAdminKubeconfigMaxExpiration)
```

"ShootAdminKubeconfigMaxExpiration is the maximum validity duration of a credential requested to a Shoot by an AdminKubeconfigRequest.\nIf an otherwise valid AdminKubeconfigRequest with a validity duration larger than this value is requested,\na credential will be issued with a validity duration of this value."

## obj spec.virtualCluster.gardener.gardenerAPIServer.admissionPlugins

"AdmissionPlugins contains the list of user-defined admission plugins (additional to those managed by Gardener),\nand, if desired, the corresponding configuration."

### fn spec.virtualCluster.gardener.gardenerAPIServer.admissionPlugins.withConfig

```ts
withConfig(config)
```

"Config is the configuration of the plugin."

### fn spec.virtualCluster.gardener.gardenerAPIServer.admissionPlugins.withConfigMixin

```ts
withConfigMixin(config)
```

"Config is the configuration of the plugin."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.gardener.gardenerAPIServer.admissionPlugins.withDisabled

```ts
withDisabled(disabled)
```

"Disabled specifies whether this plugin should be disabled."

### fn spec.virtualCluster.gardener.gardenerAPIServer.admissionPlugins.withKubeconfigSecretName

```ts
withKubeconfigSecretName(kubeconfigSecretName)
```

"KubeconfigSecretName specifies the name of a secret containing the kubeconfig for this admission plugin."

### fn spec.virtualCluster.gardener.gardenerAPIServer.admissionPlugins.withName

```ts
withName(name)
```

"Name is the name of the plugin."

## obj spec.virtualCluster.gardener.gardenerAPIServer.auditConfig

"AuditConfig contains configuration settings for the audit of the kube-apiserver."

## obj spec.virtualCluster.gardener.gardenerAPIServer.auditConfig.auditPolicy

"AuditPolicy contains configuration settings for audit policy of the kube-apiserver."

## obj spec.virtualCluster.gardener.gardenerAPIServer.auditConfig.auditPolicy.configMapRef

"ConfigMapRef is a reference to a ConfigMap object in the same namespace,\nwhich contains the audit policy for the kube-apiserver."

### fn spec.virtualCluster.gardener.gardenerAPIServer.auditConfig.auditPolicy.configMapRef.withApiVersion

```ts
withApiVersion(apiVersion)
```

"API version of the referent."

### fn spec.virtualCluster.gardener.gardenerAPIServer.auditConfig.auditPolicy.configMapRef.withFieldPath

```ts
withFieldPath(fieldPath)
```

"If referring to a piece of an object instead of an entire object, this string\nshould contain a valid JSON/Go field access statement, such as desiredState.manifest.containers[2].\nFor example, if the object reference is to a container within a pod, this would take on a value like:\n\"spec.containers{name}\" (where \"name\" refers to the name of the container that triggered\nthe event) or if no container name is specified \"spec.containers[2]\" (container with\nindex 2 in this pod). This syntax is chosen only to have some well-defined way of\nreferencing a part of an object."

### fn spec.virtualCluster.gardener.gardenerAPIServer.auditConfig.auditPolicy.configMapRef.withKind

```ts
withKind(kind)
```

"Kind of the referent.\nMore info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#types-kinds"

### fn spec.virtualCluster.gardener.gardenerAPIServer.auditConfig.auditPolicy.configMapRef.withName

```ts
withName(name)
```

"Name of the referent.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.virtualCluster.gardener.gardenerAPIServer.auditConfig.auditPolicy.configMapRef.withNamespace

```ts
withNamespace(namespace)
```

"Namespace of the referent.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/"

### fn spec.virtualCluster.gardener.gardenerAPIServer.auditConfig.auditPolicy.configMapRef.withResourceVersion

```ts
withResourceVersion(resourceVersion)
```

"Specific resourceVersion to which this reference is made, if any.\nMore info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#concurrency-control-and-consistency"

### fn spec.virtualCluster.gardener.gardenerAPIServer.auditConfig.auditPolicy.configMapRef.withUid

```ts
withUid(uid)
```

"UID of the referent.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#uids"

## obj spec.virtualCluster.gardener.gardenerAPIServer.auditWebhook

"AuditWebhook contains settings related to an audit webhook configuration."

### fn spec.virtualCluster.gardener.gardenerAPIServer.auditWebhook.withBatchMaxSize

```ts
withBatchMaxSize(batchMaxSize)
```

"BatchMaxSize is the maximum size of a batch."

### fn spec.virtualCluster.gardener.gardenerAPIServer.auditWebhook.withKubeconfigSecretName

```ts
withKubeconfigSecretName(kubeconfigSecretName)
```

"KubeconfigSecretName specifies the name of a secret containing the kubeconfig for this webhook."

### fn spec.virtualCluster.gardener.gardenerAPIServer.auditWebhook.withVersion

```ts
withVersion(version)
```

"Version is the API version to send and expect from the webhook."

## obj spec.virtualCluster.gardener.gardenerAPIServer.encryptionConfig

"EncryptionConfig contains customizable encryption configuration of the Gardener API server."

### fn spec.virtualCluster.gardener.gardenerAPIServer.encryptionConfig.withResources

```ts
withResources(resources)
```

"Resources contains the list of resources that shall be encrypted in addition to secrets.\nEach item is a Kubernetes resource name in plural (resource or resource.group) that should be encrypted.\nWildcards are not supported for now.\nSee https://github.com/gardener/gardener/blob/master/docs/usage/security/etcd_encryption_config.md for more details."

### fn spec.virtualCluster.gardener.gardenerAPIServer.encryptionConfig.withResourcesMixin

```ts
withResourcesMixin(resources)
```

"Resources contains the list of resources that shall be encrypted in addition to secrets.\nEach item is a Kubernetes resource name in plural (resource or resource.group) that should be encrypted.\nWildcards are not supported for now.\nSee https://github.com/gardener/gardener/blob/master/docs/usage/security/etcd_encryption_config.md for more details."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.gardener.gardenerAPIServer.logging

"Logging contains configuration for the log level and HTTP access logs."

### fn spec.virtualCluster.gardener.gardenerAPIServer.logging.withHttpAccessVerbosity

```ts
withHttpAccessVerbosity(httpAccessVerbosity)
```

"HTTPAccessVerbosity is the kube-apiserver access logs level"

### fn spec.virtualCluster.gardener.gardenerAPIServer.logging.withVerbosity

```ts
withVerbosity(verbosity)
```

"Verbosity is the kube-apiserver log verbosity level\nDefaults to 2."

## obj spec.virtualCluster.gardener.gardenerAPIServer.requests

"Requests contains configuration for request-specific settings for the kube-apiserver."

### fn spec.virtualCluster.gardener.gardenerAPIServer.requests.withMaxMutatingInflight

```ts
withMaxMutatingInflight(maxMutatingInflight)
```

"MaxMutatingInflight is the maximum number of mutating requests in flight at a given time. When the server\nexceeds this, it rejects requests."

### fn spec.virtualCluster.gardener.gardenerAPIServer.requests.withMaxNonMutatingInflight

```ts
withMaxNonMutatingInflight(maxNonMutatingInflight)
```

"MaxNonMutatingInflight is the maximum number of non-mutating requests in flight at a given time. When the server\nexceeds this, it rejects requests."

## obj spec.virtualCluster.gardener.gardenerAPIServer.watchCacheSizes

"WatchCacheSizes contains configuration of the API server's watch cache sizes.\nConfiguring these flags might be useful for large-scale Garden clusters with a lot of parallel update requests\nand a lot of watching controllers (e.g. large ManagedSeed clusters). When the API server's watch cache's\ncapacity is too small to cope with the amount of update requests and watchers for a particular resource, it\nmight happen that controller watches are permanently stopped with `too old resource version` errors.\nStarting from kubernetes v1.19, the API server's watch cache size is adapted dynamically and setting the watch\ncache size flags will have no effect, except when setting it to 0 (which disables the watch cache)."

### fn spec.virtualCluster.gardener.gardenerAPIServer.watchCacheSizes.withDefault

```ts
withDefault(default)
```

"Default configures the default watch cache size of the kube-apiserver\n(flag `--default-watch-cache-size`, defaults to 100).\nSee: https://kubernetes.io/docs/reference/command-line-tools-reference/kube-apiserver/"

### fn spec.virtualCluster.gardener.gardenerAPIServer.watchCacheSizes.withResources

```ts
withResources(resources)
```

"Resources configures the watch cache size of the kube-apiserver per resource\n(flag `--watch-cache-sizes`).\nSee: https://kubernetes.io/docs/reference/command-line-tools-reference/kube-apiserver/"

### fn spec.virtualCluster.gardener.gardenerAPIServer.watchCacheSizes.withResourcesMixin

```ts
withResourcesMixin(resources)
```

"Resources configures the watch cache size of the kube-apiserver per resource\n(flag `--watch-cache-sizes`).\nSee: https://kubernetes.io/docs/reference/command-line-tools-reference/kube-apiserver/"

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.gardener.gardenerAPIServer.watchCacheSizes.resources

"Resources configures the watch cache size of the kube-apiserver per resource\n(flag `--watch-cache-sizes`).\nSee: https://kubernetes.io/docs/reference/command-line-tools-reference/kube-apiserver/"

### fn spec.virtualCluster.gardener.gardenerAPIServer.watchCacheSizes.resources.withApiGroup

```ts
withApiGroup(apiGroup)
```

"APIGroup is the API group of the resource for which the watch cache size should be configured.\nAn unset value is used to specify the legacy core API (e.g. for `secrets`)."

### fn spec.virtualCluster.gardener.gardenerAPIServer.watchCacheSizes.resources.withResource

```ts
withResource(resource)
```

"Resource is the name of the resource for which the watch cache size should be configured\n(in lowercase plural form, e.g. `secrets`)."

### fn spec.virtualCluster.gardener.gardenerAPIServer.watchCacheSizes.resources.withSize

```ts
withSize(size)
```

"CacheSize specifies the watch cache size that should be configured for the specified resource."

## obj spec.virtualCluster.gardener.gardenerAdmissionController

"AdmissionController contains configuration settings for the gardener-admission-controller."

### fn spec.virtualCluster.gardener.gardenerAdmissionController.withLogLevel

```ts
withLogLevel(logLevel)
```

"LogLevel is the configured log level for the gardener-admission-controller. Must be one of [info,debug,error].\nDefaults to info."

## obj spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration

"ResourceAdmissionConfiguration is the configuration for resource size restrictions for arbitrary Group-Version-Kinds."

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.withLimits

```ts
withLimits(limits)
```

"Limits contains configuration for resources which are subjected to size limitations."

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.withLimitsMixin

```ts
withLimitsMixin(limits)
```

"Limits contains configuration for resources which are subjected to size limitations."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.withOperationMode

```ts
withOperationMode(operationMode)
```

"OperationMode specifies the mode the webhooks operates in. Allowed values are \"block\" and \"log\". Defaults to \"block\"."

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.withUnrestrictedSubjects

```ts
withUnrestrictedSubjects(unrestrictedSubjects)
```

"UnrestrictedSubjects contains references to users, groups, or service accounts which aren't subjected to any resource size limit."

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.withUnrestrictedSubjectsMixin

```ts
withUnrestrictedSubjectsMixin(unrestrictedSubjects)
```

"UnrestrictedSubjects contains references to users, groups, or service accounts which aren't subjected to any resource size limit."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.limits

"Limits contains configuration for resources which are subjected to size limitations."

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.limits.withApiGroups

```ts
withApiGroups(apiGroups)
```

"APIGroups is the name of the APIGroup that contains the limited resource. WildcardAll represents all groups."

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.limits.withApiGroupsMixin

```ts
withApiGroupsMixin(apiGroups)
```

"APIGroups is the name of the APIGroup that contains the limited resource. WildcardAll represents all groups."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.limits.withApiVersions

```ts
withApiVersions(apiVersions)
```

"APIVersions is the version of the resource. WildcardAll represents all versions."

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.limits.withApiVersionsMixin

```ts
withApiVersionsMixin(apiVersions)
```

"APIVersions is the version of the resource. WildcardAll represents all versions."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.limits.withCount

```ts
withCount(count)
```

"Count specifies the maximum number of resources of the given kind. Only cluster-scoped resources are considered."

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.limits.withResources

```ts
withResources(resources)
```

"Resources is the name of the resource this rule applies to. WildcardAll represents all resources."

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.limits.withResourcesMixin

```ts
withResourcesMixin(resources)
```

"Resources is the name of the resource this rule applies to. WildcardAll represents all resources."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.limits.withSize

```ts
withSize(size)
```

"Size specifies the imposed limit."

## obj spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.unrestrictedSubjects

"UnrestrictedSubjects contains references to users, groups, or service accounts which aren't subjected to any resource size limit."

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.unrestrictedSubjects.withApiGroup

```ts
withApiGroup(apiGroup)
```

"APIGroup holds the API group of the referenced subject.\nDefaults to \"\" for ServiceAccount subjects.\nDefaults to \"rbac.authorization.k8s.io\" for User and Group subjects."

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.unrestrictedSubjects.withKind

```ts
withKind(kind)
```

"Kind of object being referenced. Values defined by this API group are \"User\", \"Group\", and \"ServiceAccount\".\nIf the Authorizer does not recognized the kind value, the Authorizer should report an error."

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.unrestrictedSubjects.withName

```ts
withName(name)
```

"Name of the object being referenced."

### fn spec.virtualCluster.gardener.gardenerAdmissionController.resourceAdmissionConfiguration.unrestrictedSubjects.withNamespace

```ts
withNamespace(namespace)
```

"Namespace of the referenced object.  If the object kind is non-namespace, such as \"User\" or \"Group\", and this value is not empty\nthe Authorizer should report an error."

## obj spec.virtualCluster.gardener.gardenerControllerManager

"ControllerManager contains configuration settings for the gardener-controller-manager."

### fn spec.virtualCluster.gardener.gardenerControllerManager.withDefaultProjectQuotas

```ts
withDefaultProjectQuotas(defaultProjectQuotas)
```

"DefaultProjectQuotas is the default configuration matching projects are set up with if a quota is not already\nspecified."

### fn spec.virtualCluster.gardener.gardenerControllerManager.withDefaultProjectQuotasMixin

```ts
withDefaultProjectQuotasMixin(defaultProjectQuotas)
```

"DefaultProjectQuotas is the default configuration matching projects are set up with if a quota is not already\nspecified."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.gardener.gardenerControllerManager.withFeatureGates

```ts
withFeatureGates(featureGates)
```

"FeatureGates contains information about enabled feature gates."

### fn spec.virtualCluster.gardener.gardenerControllerManager.withFeatureGatesMixin

```ts
withFeatureGatesMixin(featureGates)
```

"FeatureGates contains information about enabled feature gates."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.gardener.gardenerControllerManager.withLogLevel

```ts
withLogLevel(logLevel)
```

"LogLevel is the configured log level for the gardener-controller-manager. Must be one of [info,debug,error].\nDefaults to info."

## obj spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas

"DefaultProjectQuotas is the default configuration matching projects are set up with if a quota is not already\nspecified."

## obj spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config

"Config is the corev1.ResourceQuota specification used for the project set-up."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.withApiVersion

```ts
withApiVersion(apiVersion)
```

"APIVersion defines the versioned schema of this representation of an object.\nServers should convert recognized schemas to the latest internal value, and\nmay reject unrecognized values.\nMore info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#resources"

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.withKind

```ts
withKind(kind)
```

"Kind is a string value representing the REST resource this object represents.\nServers may infer this from the endpoint the client submits requests to.\nCannot be updated.\nIn CamelCase.\nMore info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#types-kinds"

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.withMetadata

```ts
withMetadata(metadata)
```

"Standard object's metadata.\nMore info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#metadata"

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.withMetadataMixin

```ts
withMetadataMixin(metadata)
```

"Standard object's metadata.\nMore info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#metadata"

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec

"Spec defines the desired quota.\nhttps://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#spec-and-status"

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec.withHard

```ts
withHard(hard)
```

"hard is the set of desired hard limits for each named resource.\nMore info: https://kubernetes.io/docs/concepts/policy/resource-quotas/"

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec.withHardMixin

```ts
withHardMixin(hard)
```

"hard is the set of desired hard limits for each named resource.\nMore info: https://kubernetes.io/docs/concepts/policy/resource-quotas/"

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec.withScopes

```ts
withScopes(scopes)
```

"A collection of filters that must match each object tracked by a quota.\nIf not specified, the quota matches all objects."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec.withScopesMixin

```ts
withScopesMixin(scopes)
```

"A collection of filters that must match each object tracked by a quota.\nIf not specified, the quota matches all objects."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec.scopeSelector

"scopeSelector is also a collection of filters like scopes that must match each object tracked by a quota\nbut expressed using ScopeSelectorOperator in combination with possible values.\nFor a resource to match, both scopes AND scopeSelector (if specified in spec), must be matched."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec.scopeSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"A list of scope selector requirements by scope of the resources."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec.scopeSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"A list of scope selector requirements by scope of the resources."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec.scopeSelector.matchExpressions

"A list of scope selector requirements by scope of the resources."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec.scopeSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"Represents a scope's relationship to a set of values.\nValid operators are In, NotIn, Exists, DoesNotExist."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec.scopeSelector.matchExpressions.withScopeName

```ts
withScopeName(scopeName)
```

"The name of the scope that the selector applies to."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec.scopeSelector.matchExpressions.withValues

```ts
withValues(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty.\nThis array is replaced during a strategic merge patch."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.config.spec.scopeSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty.\nThis array is replaced during a strategic merge patch."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.projectSelector

"ProjectSelector is an optional setting to select the projects considered for quotas.\nDefaults to empty LabelSelector, which matches all projects."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.projectSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.projectSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.projectSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.projectSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.projectSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.projectSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.projectSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.projectSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.virtualCluster.gardener.gardenerControllerManager.defaultProjectQuotas.projectSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.gardener.gardenerDashboard

"Dashboard contains configuration settings for the gardener-dashboard."

### fn spec.virtualCluster.gardener.gardenerDashboard.withEnableTokenLogin

```ts
withEnableTokenLogin(enableTokenLogin)
```

"EnableTokenLogin specifies whether it is possible to log into the dashboard with a JWT token. If disabled, OIDC\nmust be configured."

### fn spec.virtualCluster.gardener.gardenerDashboard.withLogLevel

```ts
withLogLevel(logLevel)
```

"LogLevel is the configured log level. Must be one of [trace,debug,info,warn,error].\nDefaults to info."

## obj spec.virtualCluster.gardener.gardenerDashboard.assetsConfigMapRef

"AssetsConfigMapRef is the reference to a ConfigMap in the garden namespace containing the assets (logos/icons)."

### fn spec.virtualCluster.gardener.gardenerDashboard.assetsConfigMapRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.virtualCluster.gardener.gardenerDashboard.frontendConfigMapRef

"FrontendConfigMapRef is the reference to a ConfigMap in the garden namespace containing the frontend\nconfiguration."

### fn spec.virtualCluster.gardener.gardenerDashboard.frontendConfigMapRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.virtualCluster.gardener.gardenerDashboard.gitHub

"GitHub contains configuration for the GitHub ticketing feature."

### fn spec.virtualCluster.gardener.gardenerDashboard.gitHub.withApiURL

```ts
withApiURL(apiURL)
```

"APIURL is the URL to the GitHub API."

### fn spec.virtualCluster.gardener.gardenerDashboard.gitHub.withOrganisation

```ts
withOrganisation(organisation)
```

"Organisation is the name of the GitHub organisation."

### fn spec.virtualCluster.gardener.gardenerDashboard.gitHub.withPollInterval

```ts
withPollInterval(pollInterval)
```

"PollInterval is the interval of how often the GitHub API is polled for issue updates. This field is used as a\nfallback mechanism to ensure state synchronization, even when there is a GitHub webhook configuration. If a\nwebhook event is missed or not successfully delivered, the polling will help catch up on any missed updates.\nIf this field is not provided and there is no 'webhookSecret' key in the referenced secret, it will be\nimplicitly defaulted to `15m`."

### fn spec.virtualCluster.gardener.gardenerDashboard.gitHub.withRepository

```ts
withRepository(repository)
```

"Repository is the name of the GitHub repository."

## obj spec.virtualCluster.gardener.gardenerDashboard.gitHub.secretRef

"SecretRef is the reference to a secret in the garden namespace containing the GitHub credentials."

### fn spec.virtualCluster.gardener.gardenerDashboard.gitHub.secretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.virtualCluster.gardener.gardenerDashboard.ingress

"Ingress contains configuration for the ingress settings."

### fn spec.virtualCluster.gardener.gardenerDashboard.ingress.withEnabled

```ts
withEnabled(enabled)
```

"Enabled controls whether the Dashboard Ingress resource will be deployed to the cluster."

## obj spec.virtualCluster.gardener.gardenerDashboard.oidcConfig

"OIDCConfig contains configuration for the OIDC provider. This field must be provided when EnableTokenLogin is false."

### fn spec.virtualCluster.gardener.gardenerDashboard.oidcConfig.withAdditionalScopes

```ts
withAdditionalScopes(additionalScopes)
```

"AdditionalScopes is the list of additional OIDC scopes."

### fn spec.virtualCluster.gardener.gardenerDashboard.oidcConfig.withAdditionalScopesMixin

```ts
withAdditionalScopesMixin(additionalScopes)
```

"AdditionalScopes is the list of additional OIDC scopes."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.gardener.gardenerDashboard.oidcConfig.withClientIDPublic

```ts
withClientIDPublic(clientIDPublic)
```

"ClientIDPublic is the public client ID.\nFalls back to the API server's OIDC client ID configuration if not set here."

### fn spec.virtualCluster.gardener.gardenerDashboard.oidcConfig.withIssuerURL

```ts
withIssuerURL(issuerURL)
```

"The URL of the OpenID issuer, only HTTPS scheme will be accepted. Used to verify the OIDC JSON Web Token (JWT).\nFalls back to the API server's OIDC issuer URL configuration if not set here."

### fn spec.virtualCluster.gardener.gardenerDashboard.oidcConfig.withSessionLifetime

```ts
withSessionLifetime(sessionLifetime)
```

"SessionLifetime is the maximum duration of a session."

## obj spec.virtualCluster.gardener.gardenerDashboard.oidcConfig.certificateAuthoritySecretRef

"CertificateAuthoritySecretRef is the reference to a secret in the garden namespace containing a custom CA certificate under the \"ca.crt\" key"

### fn spec.virtualCluster.gardener.gardenerDashboard.oidcConfig.certificateAuthoritySecretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.virtualCluster.gardener.gardenerDashboard.oidcConfig.secretRef

"SecretRef is the reference to a secret in the garden namespace containing the OIDC client ID and secret for the dashboard."

### fn spec.virtualCluster.gardener.gardenerDashboard.oidcConfig.secretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.virtualCluster.gardener.gardenerDashboard.terminal

"Terminal contains configuration for the terminal settings."

### fn spec.virtualCluster.gardener.gardenerDashboard.terminal.withAllowedHosts

```ts
withAllowedHosts(allowedHosts)
```

"AllowedHosts should consist of permitted hostnames (without the scheme) for terminal connections.\nIt is important to consider that the usage of wildcards follows the rules defined by the content security policy.\n'*.seed.local.gardener.cloud', or '*.other-seeds.local.gardener.cloud'. For more information, see\nhttps://github.com/gardener/dashboard/blob/master/docs/operations/webterminals.md#allowlist-for-hosts."

### fn spec.virtualCluster.gardener.gardenerDashboard.terminal.withAllowedHostsMixin

```ts
withAllowedHostsMixin(allowedHosts)
```

"AllowedHosts should consist of permitted hostnames (without the scheme) for terminal connections.\nIt is important to consider that the usage of wildcards follows the rules defined by the content security policy.\n'*.seed.local.gardener.cloud', or '*.other-seeds.local.gardener.cloud'. For more information, see\nhttps://github.com/gardener/dashboard/blob/master/docs/operations/webterminals.md#allowlist-for-hosts."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.gardener.gardenerDashboard.terminal.container

"Container contains configuration for the dashboard terminal container."

### fn spec.virtualCluster.gardener.gardenerDashboard.terminal.container.withDescription

```ts
withDescription(description)
```

"Description is a description for the dashboard terminal container with hints for the user."

### fn spec.virtualCluster.gardener.gardenerDashboard.terminal.container.withImage

```ts
withImage(image)
```

"Image is the container image for the dashboard terminal container."

## obj spec.virtualCluster.gardener.gardenerScheduler

"Scheduler contains configuration settings for the gardener-scheduler."

### fn spec.virtualCluster.gardener.gardenerScheduler.withFeatureGates

```ts
withFeatureGates(featureGates)
```

"FeatureGates contains information about enabled feature gates."

### fn spec.virtualCluster.gardener.gardenerScheduler.withFeatureGatesMixin

```ts
withFeatureGatesMixin(featureGates)
```

"FeatureGates contains information about enabled feature gates."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.gardener.gardenerScheduler.withLogLevel

```ts
withLogLevel(logLevel)
```

"LogLevel is the configured log level for the gardener-scheduler. Must be one of [info,debug,error].\nDefaults to info."

## obj spec.virtualCluster.kubernetes

"Kubernetes contains the version and configuration options for the Kubernetes components of the virtual garden\ncluster."

### fn spec.virtualCluster.kubernetes.withVersion

```ts
withVersion(version)
```

"Version is the semantic Kubernetes version to use for the virtual garden cluster."

## obj spec.virtualCluster.kubernetes.kubeAPIServer

"KubeAPIServer contains configuration settings for the kube-apiserver."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.withAdmissionPlugins

```ts
withAdmissionPlugins(admissionPlugins)
```

"AdmissionPlugins contains the list of user-defined admission plugins (additional to those managed by Gardener), and, if desired, the corresponding\nconfiguration."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.withAdmissionPluginsMixin

```ts
withAdmissionPluginsMixin(admissionPlugins)
```

"AdmissionPlugins contains the list of user-defined admission plugins (additional to those managed by Gardener), and, if desired, the corresponding\nconfiguration."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.kubernetes.kubeAPIServer.withApiAudiences

```ts
withApiAudiences(apiAudiences)
```

"APIAudiences are the identifiers of the API. The service account token authenticator will\nvalidate that tokens used against the API are bound to at least one of these audiences.\nDefaults to [\"kubernetes\"]."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.withApiAudiencesMixin

```ts
withApiAudiencesMixin(apiAudiences)
```

"APIAudiences are the identifiers of the API. The service account token authenticator will\nvalidate that tokens used against the API are bound to at least one of these audiences.\nDefaults to [\"kubernetes\"]."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.kubernetes.kubeAPIServer.withDefaultNotReadyTolerationSeconds

```ts
withDefaultNotReadyTolerationSeconds(defaultNotReadyTolerationSeconds)
```

"DefaultNotReadyTolerationSeconds indicates the tolerationSeconds of the toleration for notReady:NoExecute\nthat is added by default to every pod that does not already have such a toleration (flag `--default-not-ready-toleration-seconds`).\nThe field has effect only when the `DefaultTolerationSeconds` admission plugin is enabled.\nDefaults to 300."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.withDefaultUnreachableTolerationSeconds

```ts
withDefaultUnreachableTolerationSeconds(defaultUnreachableTolerationSeconds)
```

"DefaultUnreachableTolerationSeconds indicates the tolerationSeconds of the toleration for unreachable:NoExecute\nthat is added by default to every pod that does not already have such a toleration (flag `--default-unreachable-toleration-seconds`).\nThe field has effect only when the `DefaultTolerationSeconds` admission plugin is enabled.\nDefaults to 300."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.withEnableAnonymousAuthentication

```ts
withEnableAnonymousAuthentication(enableAnonymousAuthentication)
```

"EnableAnonymousAuthentication defines whether anonymous requests to the secure port\nof the API server should be allowed (flag `--anonymous-auth`).\nSee: https://kubernetes.io/docs/reference/command-line-tools-reference/kube-apiserver/\n\nDeprecated: This field is deprecated and will be removed in a future release.\nPlease use anonymous authentication configuration instead.\nFor more information see: https://kubernetes.io/docs/reference/access-authn-authz/authentication/#anonymous-authenticator-configuration"

### fn spec.virtualCluster.kubernetes.kubeAPIServer.withEventTTL

```ts
withEventTTL(eventTTL)
```

"EventTTL controls the amount of time to retain events.\nDefaults to 1h."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.withFeatureGates

```ts
withFeatureGates(featureGates)
```

"FeatureGates contains information about enabled feature gates."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.withFeatureGatesMixin

```ts
withFeatureGatesMixin(featureGates)
```

"FeatureGates contains information about enabled feature gates."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.kubernetes.kubeAPIServer.withResourcesToStoreInETCDEvents

```ts
withResourcesToStoreInETCDEvents(resourcesToStoreInETCDEvents)
```

"ResourcesToStoreInETCDEvents contains a list of resources which should be stored in etcd-events instead of\netcd-main. The 'events' resource is always stored in etcd-events. Note that adding or removing resources from\nthis list will not migrate them automatically from the etcd-main to etcd-events or vice versa."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.withResourcesToStoreInETCDEventsMixin

```ts
withResourcesToStoreInETCDEventsMixin(resourcesToStoreInETCDEvents)
```

"ResourcesToStoreInETCDEvents contains a list of resources which should be stored in etcd-events instead of\netcd-main. The 'events' resource is always stored in etcd-events. Note that adding or removing resources from\nthis list will not migrate them automatically from the etcd-main to etcd-events or vice versa."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.kubernetes.kubeAPIServer.withRuntimeConfig

```ts
withRuntimeConfig(runtimeConfig)
```

"RuntimeConfig contains information about enabled or disabled APIs."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.withRuntimeConfigMixin

```ts
withRuntimeConfigMixin(runtimeConfig)
```

"RuntimeConfig contains information about enabled or disabled APIs."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.kubernetes.kubeAPIServer.admissionPlugins

"AdmissionPlugins contains the list of user-defined admission plugins (additional to those managed by Gardener), and, if desired, the corresponding\nconfiguration."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.admissionPlugins.withConfig

```ts
withConfig(config)
```

"Config is the configuration of the plugin."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.admissionPlugins.withConfigMixin

```ts
withConfigMixin(config)
```

"Config is the configuration of the plugin."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.kubernetes.kubeAPIServer.admissionPlugins.withDisabled

```ts
withDisabled(disabled)
```

"Disabled specifies whether this plugin should be disabled."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.admissionPlugins.withKubeconfigSecretName

```ts
withKubeconfigSecretName(kubeconfigSecretName)
```

"KubeconfigSecretName specifies the name of a secret containing the kubeconfig for this admission plugin."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.admissionPlugins.withName

```ts
withName(name)
```

"Name is the name of the plugin."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.auditConfig

"AuditConfig contains configuration settings for the audit of the kube-apiserver."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.auditConfig.auditPolicy

"AuditPolicy contains configuration settings for audit policy of the kube-apiserver."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.auditConfig.auditPolicy.configMapRef

"ConfigMapRef is a reference to a ConfigMap object in the same namespace,\nwhich contains the audit policy for the kube-apiserver."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.auditConfig.auditPolicy.configMapRef.withApiVersion

```ts
withApiVersion(apiVersion)
```

"API version of the referent."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.auditConfig.auditPolicy.configMapRef.withFieldPath

```ts
withFieldPath(fieldPath)
```

"If referring to a piece of an object instead of an entire object, this string\nshould contain a valid JSON/Go field access statement, such as desiredState.manifest.containers[2].\nFor example, if the object reference is to a container within a pod, this would take on a value like:\n\"spec.containers{name}\" (where \"name\" refers to the name of the container that triggered\nthe event) or if no container name is specified \"spec.containers[2]\" (container with\nindex 2 in this pod). This syntax is chosen only to have some well-defined way of\nreferencing a part of an object."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.auditConfig.auditPolicy.configMapRef.withKind

```ts
withKind(kind)
```

"Kind of the referent.\nMore info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#types-kinds"

### fn spec.virtualCluster.kubernetes.kubeAPIServer.auditConfig.auditPolicy.configMapRef.withName

```ts
withName(name)
```

"Name of the referent.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.virtualCluster.kubernetes.kubeAPIServer.auditConfig.auditPolicy.configMapRef.withNamespace

```ts
withNamespace(namespace)
```

"Namespace of the referent.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/"

### fn spec.virtualCluster.kubernetes.kubeAPIServer.auditConfig.auditPolicy.configMapRef.withResourceVersion

```ts
withResourceVersion(resourceVersion)
```

"Specific resourceVersion to which this reference is made, if any.\nMore info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#concurrency-control-and-consistency"

### fn spec.virtualCluster.kubernetes.kubeAPIServer.auditConfig.auditPolicy.configMapRef.withUid

```ts
withUid(uid)
```

"UID of the referent.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#uids"

## obj spec.virtualCluster.kubernetes.kubeAPIServer.auditWebhook

"AuditWebhook contains settings related to an audit webhook configuration."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.auditWebhook.withBatchMaxSize

```ts
withBatchMaxSize(batchMaxSize)
```

"BatchMaxSize is the maximum size of a batch."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.auditWebhook.withKubeconfigSecretName

```ts
withKubeconfigSecretName(kubeconfigSecretName)
```

"KubeconfigSecretName specifies the name of a secret containing the kubeconfig for this webhook."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.auditWebhook.withVersion

```ts
withVersion(version)
```

"Version is the API version to send and expect from the webhook."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.authentication

"Authentication contains settings related to authentication."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.authentication.webhook

"Webhook contains settings related to an authentication webhook configuration."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.authentication.webhook.withCacheTTL

```ts
withCacheTTL(cacheTTL)
```

"CacheTTL is the duration to cache responses from the webhook authenticator."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.authentication.webhook.withKubeconfigSecretName

```ts
withKubeconfigSecretName(kubeconfigSecretName)
```

"KubeconfigSecretName specifies the name of a secret containing the kubeconfig for this webhook."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.authentication.webhook.withVersion

```ts
withVersion(version)
```

"Version is the API version to send and expect from the webhook."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.autoscaling

"Autoscaling contains auto-scaling configuration options for the kube-apiserver."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.autoscaling.withMinAllowed

```ts
withMinAllowed(minAllowed)
```

"MinAllowed configures the minimum allowed resource requests for vertical pod autoscaling..\nConfiguration of minAllowed resources is an advanced feature that can help clusters to overcome scale-up delays.\nDefault values are not applied to this field."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.autoscaling.withMinAllowedMixin

```ts
withMinAllowedMixin(minAllowed)
```

"MinAllowed configures the minimum allowed resource requests for vertical pod autoscaling..\nConfiguration of minAllowed resources is an advanced feature that can help clusters to overcome scale-up delays.\nDefault values are not applied to this field."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.kubernetes.kubeAPIServer.encryptionConfig

"EncryptionConfig contains customizable encryption configuration of the Kube API server."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.encryptionConfig.withResources

```ts
withResources(resources)
```

"Resources contains the list of resources that shall be encrypted in addition to secrets.\nEach item is a Kubernetes resource name in plural (resource or resource.group) that should be encrypted.\nWildcards are not supported for now.\nSee https://github.com/gardener/gardener/blob/master/docs/usage/security/etcd_encryption_config.md for more details."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.encryptionConfig.withResourcesMixin

```ts
withResourcesMixin(resources)
```

"Resources contains the list of resources that shall be encrypted in addition to secrets.\nEach item is a Kubernetes resource name in plural (resource or resource.group) that should be encrypted.\nWildcards are not supported for now.\nSee https://github.com/gardener/gardener/blob/master/docs/usage/security/etcd_encryption_config.md for more details."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.kubernetes.kubeAPIServer.logging

"Logging contains configuration for the log level and HTTP access logs."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.logging.withHttpAccessVerbosity

```ts
withHttpAccessVerbosity(httpAccessVerbosity)
```

"HTTPAccessVerbosity is the kube-apiserver access logs level"

### fn spec.virtualCluster.kubernetes.kubeAPIServer.logging.withVerbosity

```ts
withVerbosity(verbosity)
```

"Verbosity is the kube-apiserver log verbosity level\nDefaults to 2."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig

"OIDCConfig contains configuration settings for the OIDC provider.\n\nDeprecated: This field is deprecated and will be forbidden starting from Kubernetes 1.32.\nPlease configure and use structured authentication instead of oidc flags.\nFor more information check https://github.com/gardener/gardener/issues/9858"

### fn spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.withCaBundle

```ts
withCaBundle(caBundle)
```

"If set, the OpenID server's certificate will be verified by one of the authorities in the oidc-ca-file, otherwise the host's root CA set will be used."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.withClientID

```ts
withClientID(clientID)
```

"The client ID for the OpenID Connect client, must be set."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.withGroupsClaim

```ts
withGroupsClaim(groupsClaim)
```

"If provided, the name of a custom OpenID Connect claim for specifying user groups. The claim value is expected to be a string or array of strings. This flag is experimental, please see the authentication documentation for further details."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.withGroupsPrefix

```ts
withGroupsPrefix(groupsPrefix)
```

"If provided, all groups will be prefixed with this value to prevent conflicts with other authentication strategies."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.withIssuerURL

```ts
withIssuerURL(issuerURL)
```

"The URL of the OpenID issuer, only HTTPS scheme will be accepted. Used to verify the OIDC JSON Web Token (JWT)."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.withRequiredClaims

```ts
withRequiredClaims(requiredClaims)
```

"key=value pairs that describes a required claim in the ID Token. If set, the claim is verified to be present in the ID Token with a matching value."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.withRequiredClaimsMixin

```ts
withRequiredClaimsMixin(requiredClaims)
```

"key=value pairs that describes a required claim in the ID Token. If set, the claim is verified to be present in the ID Token with a matching value."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.withSigningAlgs

```ts
withSigningAlgs(signingAlgs)
```

"List of allowed JOSE asymmetric signing algorithms. JWTs with a 'alg' header value not in this list will be rejected. Values are defined by RFC 7518 https://tools.ietf.org/html/rfc7518#section-3.1"

### fn spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.withSigningAlgsMixin

```ts
withSigningAlgsMixin(signingAlgs)
```

"List of allowed JOSE asymmetric signing algorithms. JWTs with a 'alg' header value not in this list will be rejected. Values are defined by RFC 7518 https://tools.ietf.org/html/rfc7518#section-3.1"

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.withUsernameClaim

```ts
withUsernameClaim(usernameClaim)
```

"The OpenID claim to use as the user name. Note that claims other than the default ('sub') is not guaranteed to be unique and immutable. This flag is experimental, please see the authentication documentation for further details. (default \"sub\")"

### fn spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.withUsernamePrefix

```ts
withUsernamePrefix(usernamePrefix)
```

"If provided, all usernames will be prefixed with this value. If not provided, username claims other than 'email' are prefixed by the issuer URL to avoid clashes. To skip any prefixing, provide the value '-'."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.clientAuthentication

"ClientAuthentication can optionally contain client configuration used for kubeconfig generation.\n\nDeprecated: This field has no implemented use and will be forbidden starting from Kubernetes 1.31.\nIt's use was planned for generating OIDC kubeconfig https://github.com/gardener/gardener/issues/1433"

### fn spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.clientAuthentication.withExtraConfig

```ts
withExtraConfig(extraConfig)
```

"Extra configuration added to kubeconfig's auth-provider.\nMust not be any of idp-issuer-url, client-id, client-secret, idp-certificate-authority, idp-certificate-authority-data, id-token or refresh-token"

### fn spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.clientAuthentication.withExtraConfigMixin

```ts
withExtraConfigMixin(extraConfig)
```

"Extra configuration added to kubeconfig's auth-provider.\nMust not be any of idp-issuer-url, client-id, client-secret, idp-certificate-authority, idp-certificate-authority-data, id-token or refresh-token"

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.kubernetes.kubeAPIServer.oidcConfig.clientAuthentication.withSecret

```ts
withSecret(secret)
```

"The client Secret for the OpenID Connect client."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.requests

"Requests contains configuration for request-specific settings for the kube-apiserver."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.requests.withMaxMutatingInflight

```ts
withMaxMutatingInflight(maxMutatingInflight)
```

"MaxMutatingInflight is the maximum number of mutating requests in flight at a given time. When the server\nexceeds this, it rejects requests."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.requests.withMaxNonMutatingInflight

```ts
withMaxNonMutatingInflight(maxNonMutatingInflight)
```

"MaxNonMutatingInflight is the maximum number of non-mutating requests in flight at a given time. When the server\nexceeds this, it rejects requests."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.resourcesToStoreInETCDEvents

"ResourcesToStoreInETCDEvents contains a list of resources which should be stored in etcd-events instead of\netcd-main. The 'events' resource is always stored in etcd-events. Note that adding or removing resources from\nthis list will not migrate them automatically from the etcd-main to etcd-events or vice versa."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.resourcesToStoreInETCDEvents.withGroup

```ts
withGroup(group)
```

"Group is the API group name."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.resourcesToStoreInETCDEvents.withResource

```ts
withResource(resource)
```

"Resource is the resource name."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.serviceAccountConfig

"ServiceAccountConfig contains configuration settings for the service account handling\nof the kube-apiserver."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.serviceAccountConfig.withAcceptedIssuers

```ts
withAcceptedIssuers(acceptedIssuers)
```

"AcceptedIssuers is an additional set of issuers that are used to determine which service account tokens are accepted.\nThese values are not used to generate new service account tokens. Only useful when service account tokens are also\nissued by another external system or a change of the current issuer that is used for generating tokens is being performed."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.serviceAccountConfig.withAcceptedIssuersMixin

```ts
withAcceptedIssuersMixin(acceptedIssuers)
```

"AcceptedIssuers is an additional set of issuers that are used to determine which service account tokens are accepted.\nThese values are not used to generate new service account tokens. Only useful when service account tokens are also\nissued by another external system or a change of the current issuer that is used for generating tokens is being performed."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.kubernetes.kubeAPIServer.serviceAccountConfig.withExtendTokenExpiration

```ts
withExtendTokenExpiration(extendTokenExpiration)
```

"ExtendTokenExpiration turns on projected service account expiration extension during token generation, which\nhelps safe transition from legacy token to bound service account token feature. If this flag is enabled,\nadmission injected tokens would be extended up to 1 year to prevent unexpected failure during transition,\nignoring value of service-account-max-token-expiration."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.serviceAccountConfig.withIssuer

```ts
withIssuer(issuer)
```

"Issuer is the identifier of the service account token issuer. The issuer will assert this\nidentifier in \"iss\" claim of issued tokens. This value is used to generate new service account tokens.\nThis value is a string or URI. Defaults to URI of the API server."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.serviceAccountConfig.withMaxTokenExpiration

```ts
withMaxTokenExpiration(maxTokenExpiration)
```

"MaxTokenExpiration is the maximum validity duration of a token created by the service account token issuer. If an\notherwise valid TokenRequest with a validity duration larger than this value is requested, a token will be issued\nwith a validity duration of this value.\nThis field must be within [30d,90d]."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.sni

"SNI contains configuration options for the TLS SNI settings."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.sni.withDomainPatterns

```ts
withDomainPatterns(domainPatterns)
```

"DomainPatterns is a list of fully qualified domain names, possibly with prefixed wildcard segments. The domain\npatterns also allow IP addresses, but IPs should only be used if the apiserver has visibility to the IP address\nrequested by a client. If no domain patterns are provided, the names of the certificate are extracted.\nNon-wildcard matches trump over wildcard matches, explicit domain patterns trump over extracted names."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.sni.withDomainPatternsMixin

```ts
withDomainPatternsMixin(domainPatterns)
```

"DomainPatterns is a list of fully qualified domain names, possibly with prefixed wildcard segments. The domain\npatterns also allow IP addresses, but IPs should only be used if the apiserver has visibility to the IP address\nrequested by a client. If no domain patterns are provided, the names of the certificate are extracted.\nNon-wildcard matches trump over wildcard matches, explicit domain patterns trump over extracted names."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.kubernetes.kubeAPIServer.sni.withSecretName

```ts
withSecretName(secretName)
```

"SecretName is the name of a secret containing the TLS certificate and private key.\nIf not configured, Gardener falls back to a secret labelled with 'gardener.cloud/role=garden-cert'."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.structuredAuthentication

"StructuredAuthentication contains configuration settings for structured authentication for the kube-apiserver.\nThis field is only available for Kubernetes v1.30 or later."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.structuredAuthentication.withConfigMapName

```ts
withConfigMapName(configMapName)
```

"ConfigMapName is the name of the ConfigMap in the project namespace which contains AuthenticationConfiguration\nfor the kube-apiserver."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.structuredAuthorization

"StructuredAuthorization contains configuration settings for structured authorization for the kube-apiserver.\nThis field is only available for Kubernetes v1.30 or later."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.structuredAuthorization.withConfigMapName

```ts
withConfigMapName(configMapName)
```

"ConfigMapName is the name of the ConfigMap in the project namespace which contains AuthorizationConfiguration for\nthe kube-apiserver."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.structuredAuthorization.withKubeconfigs

```ts
withKubeconfigs(kubeconfigs)
```

"Kubeconfigs is a list of references for kubeconfigs for the authorization webhooks."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.structuredAuthorization.withKubeconfigsMixin

```ts
withKubeconfigsMixin(kubeconfigs)
```

"Kubeconfigs is a list of references for kubeconfigs for the authorization webhooks."

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.kubernetes.kubeAPIServer.structuredAuthorization.kubeconfigs

"Kubeconfigs is a list of references for kubeconfigs for the authorization webhooks."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.structuredAuthorization.kubeconfigs.withAuthorizerName

```ts
withAuthorizerName(authorizerName)
```

"AuthorizerName is the name of a webhook authorizer."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.structuredAuthorization.kubeconfigs.withSecretName

```ts
withSecretName(secretName)
```

"SecretName is the name of a secret containing the kubeconfig."

## obj spec.virtualCluster.kubernetes.kubeAPIServer.watchCacheSizes

"WatchCacheSizes contains configuration of the API server's watch cache sizes.\nConfiguring these flags might be useful for large-scale Shoot clusters with a lot of parallel update requests\nand a lot of watching controllers (e.g. large ManagedSeed clusters). When the API server's watch cache's\ncapacity is too small to cope with the amount of update requests and watchers for a particular resource, it\nmight happen that controller watches are permanently stopped with `too old resource version` errors.\nStarting from kubernetes v1.19, the API server's watch cache size is adapted dynamically and setting the watch\ncache size flags will have no effect, except when setting it to 0 (which disables the watch cache)."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.watchCacheSizes.withDefault

```ts
withDefault(default)
```

"Default configures the default watch cache size of the kube-apiserver\n(flag `--default-watch-cache-size`, defaults to 100).\nSee: https://kubernetes.io/docs/reference/command-line-tools-reference/kube-apiserver/"

### fn spec.virtualCluster.kubernetes.kubeAPIServer.watchCacheSizes.withResources

```ts
withResources(resources)
```

"Resources configures the watch cache size of the kube-apiserver per resource\n(flag `--watch-cache-sizes`).\nSee: https://kubernetes.io/docs/reference/command-line-tools-reference/kube-apiserver/"

### fn spec.virtualCluster.kubernetes.kubeAPIServer.watchCacheSizes.withResourcesMixin

```ts
withResourcesMixin(resources)
```

"Resources configures the watch cache size of the kube-apiserver per resource\n(flag `--watch-cache-sizes`).\nSee: https://kubernetes.io/docs/reference/command-line-tools-reference/kube-apiserver/"

**Note:** This function appends passed data to existing values

## obj spec.virtualCluster.kubernetes.kubeAPIServer.watchCacheSizes.resources

"Resources configures the watch cache size of the kube-apiserver per resource\n(flag `--watch-cache-sizes`).\nSee: https://kubernetes.io/docs/reference/command-line-tools-reference/kube-apiserver/"

### fn spec.virtualCluster.kubernetes.kubeAPIServer.watchCacheSizes.resources.withApiGroup

```ts
withApiGroup(apiGroup)
```

"APIGroup is the API group of the resource for which the watch cache size should be configured.\nAn unset value is used to specify the legacy core API (e.g. for `secrets`)."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.watchCacheSizes.resources.withResource

```ts
withResource(resource)
```

"Resource is the name of the resource for which the watch cache size should be configured\n(in lowercase plural form, e.g. `secrets`)."

### fn spec.virtualCluster.kubernetes.kubeAPIServer.watchCacheSizes.resources.withSize

```ts
withSize(size)
```

"CacheSize specifies the watch cache size that should be configured for the specified resource."

## obj spec.virtualCluster.kubernetes.kubeControllerManager

"KubeControllerManager contains configuration settings for the kube-controller-manager."

### fn spec.virtualCluster.kubernetes.kubeControllerManager.withCertificateSigningDuration

```ts
withCertificateSigningDuration(certificateSigningDuration)
```

"CertificateSigningDuration is the maximum length of duration signed certificates will be given. Individual CSRs\nmay request shorter certs by setting `spec.expirationSeconds`."

### fn spec.virtualCluster.kubernetes.kubeControllerManager.withFeatureGates

```ts
withFeatureGates(featureGates)
```

"FeatureGates contains information about enabled feature gates."

### fn spec.virtualCluster.kubernetes.kubeControllerManager.withFeatureGatesMixin

```ts
withFeatureGatesMixin(featureGates)
```

"FeatureGates contains information about enabled feature gates."

**Note:** This function appends passed data to existing values

### fn spec.virtualCluster.kubernetes.kubeControllerManager.withNodeCIDRMaskSize

```ts
withNodeCIDRMaskSize(nodeCIDRMaskSize)
```

"NodeCIDRMaskSize defines the mask size for node cidr in cluster (default is 24). This field is immutable."

### fn spec.virtualCluster.kubernetes.kubeControllerManager.withNodeMonitorGracePeriod

```ts
withNodeMonitorGracePeriod(nodeMonitorGracePeriod)
```

"NodeMonitorGracePeriod defines the grace period before an unresponsive node is marked unhealthy."

### fn spec.virtualCluster.kubernetes.kubeControllerManager.withPodEvictionTimeout

```ts
withPodEvictionTimeout(podEvictionTimeout)
```

"PodEvictionTimeout defines the grace period for deleting pods on failed nodes. Defaults to 2m.\n\nDeprecated: The corresponding kube-controller-manager flag `--pod-eviction-timeout` is deprecated\nin favor of the kube-apiserver flags `--default-not-ready-toleration-seconds` and `--default-unreachable-toleration-seconds`.\nThe `--pod-eviction-timeout` flag does not have effect when the taint based eviction is enabled. The taint\nbased eviction is beta (enabled by default) since Kubernetes 1.13 and GA since Kubernetes 1.18. Hence,\ninstead of setting this field, set the `spec.kubernetes.kubeAPIServer.defaultNotReadyTolerationSeconds` and\n`spec.kubernetes.kubeAPIServer.defaultUnreachableTolerationSeconds`. Setting this field is forbidden starting\nfrom Kubernetes 1.33."

## obj spec.virtualCluster.kubernetes.kubeControllerManager.horizontalPodAutoscaler

"HorizontalPodAutoscalerConfig contains horizontal pod autoscaler configuration settings for the kube-controller-manager."

### fn spec.virtualCluster.kubernetes.kubeControllerManager.horizontalPodAutoscaler.withCpuInitializationPeriod

```ts
withCpuInitializationPeriod(cpuInitializationPeriod)
```

"The period after which a ready pod transition is considered to be the first."

### fn spec.virtualCluster.kubernetes.kubeControllerManager.horizontalPodAutoscaler.withDownscaleStabilization

```ts
withDownscaleStabilization(downscaleStabilization)
```

"The configurable window at which the controller will choose the highest recommendation for autoscaling."

### fn spec.virtualCluster.kubernetes.kubeControllerManager.horizontalPodAutoscaler.withInitialReadinessDelay

```ts
withInitialReadinessDelay(initialReadinessDelay)
```

"The configurable period at which the horizontal pod autoscaler considers a Pod “not yet ready” given that it’s unready and it has  transitioned to unready during that time."

### fn spec.virtualCluster.kubernetes.kubeControllerManager.horizontalPodAutoscaler.withSyncPeriod

```ts
withSyncPeriod(syncPeriod)
```

"The period for syncing the number of pods in horizontal pod autoscaler."

### fn spec.virtualCluster.kubernetes.kubeControllerManager.horizontalPodAutoscaler.withTolerance

```ts
withTolerance(tolerance)
```

"The minimum change (from 1.0) in the desired-to-actual metrics ratio for the horizontal pod autoscaler to consider scaling."

## obj spec.virtualCluster.maintenance

"Maintenance contains information about the time window for maintenance operations."

## obj spec.virtualCluster.maintenance.timeWindow

"TimeWindow contains information about the time window for maintenance operations."

### fn spec.virtualCluster.maintenance.timeWindow.withBegin

```ts
withBegin(begin)
```

"Begin is the beginning of the time window in the format HHMMSS+ZONE, e.g. \"220000+0100\".\nIf not present, a random value will be computed."

### fn spec.virtualCluster.maintenance.timeWindow.withEnd

```ts
withEnd(end)
```

"End is the end of the time window in the format HHMMSS+ZONE, e.g. \"220000+0100\".\nIf not present, the value will be computed based on the \"Begin\" value."

## obj spec.virtualCluster.networking

"Networking contains information about cluster networking such as CIDRs, etc."

### fn spec.virtualCluster.networking.withServices

```ts
withServices(services)
```

"Services are the CIDRs of the service network. Elements can be appended to this list, but not removed."

### fn spec.virtualCluster.networking.withServicesMixin

```ts
withServicesMixin(services)
```

"Services are the CIDRs of the service network. Elements can be appended to this list, but not removed."

**Note:** This function appends passed data to existing values