---
permalink: /1.3.0/k6/v1alpha1/privateLoadZone/
---

# k6.v1alpha1.privateLoadZone



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
  * [`fn withImage(image)`](#fn-specwithimage)
  * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-specwithimagepullsecrets)
  * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-specwithimagepullsecretsmixin)
  * [`fn withNodeSelector(nodeSelector)`](#fn-specwithnodeselector)
  * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-specwithnodeselectormixin)
  * [`fn withServiceAccountName(serviceAccountName)`](#fn-specwithserviceaccountname)
  * [`fn withToken(token)`](#fn-specwithtoken)
  * [`obj spec.config`](#obj-specconfig)
    * [`fn withSecrets(secrets)`](#fn-specconfigwithsecrets)
    * [`fn withSecretsMixin(secrets)`](#fn-specconfigwithsecretsmixin)
    * [`obj spec.config.secrets`](#obj-specconfigsecrets)
      * [`obj spec.config.secrets.configMapRef`](#obj-specconfigsecretsconfigmapref)
        * [`fn withName(name)`](#fn-specconfigsecretsconfigmaprefwithname)
        * [`fn withOptional(optional)`](#fn-specconfigsecretsconfigmaprefwithoptional)
      * [`obj spec.config.secrets.secretRef`](#obj-specconfigsecretssecretref)
        * [`fn withName(name)`](#fn-specconfigsecretssecretrefwithname)
        * [`fn withOptional(optional)`](#fn-specconfigsecretssecretrefwithoptional)
  * [`obj spec.imagePullSecrets`](#obj-specimagepullsecrets)
    * [`fn withName(name)`](#fn-specimagepullsecretswithname)
  * [`obj spec.podTemplate`](#obj-specpodtemplate)
    * [`fn withMetadata(metadata)`](#fn-specpodtemplatewithmetadata)
    * [`fn withMetadataMixin(metadata)`](#fn-specpodtemplatewithmetadatamixin)
    * [`obj spec.podTemplate.spec`](#obj-specpodtemplatespec)
      * [`fn withActiveDeadlineSeconds(activeDeadlineSeconds)`](#fn-specpodtemplatespecwithactivedeadlineseconds)
      * [`fn withAutomountServiceAccountToken(automountServiceAccountToken)`](#fn-specpodtemplatespecwithautomountserviceaccounttoken)
      * [`fn withContainers(containers)`](#fn-specpodtemplatespecwithcontainers)
      * [`fn withContainersMixin(containers)`](#fn-specpodtemplatespecwithcontainersmixin)
      * [`fn withDnsPolicy(dnsPolicy)`](#fn-specpodtemplatespecwithdnspolicy)
      * [`fn withEnableServiceLinks(enableServiceLinks)`](#fn-specpodtemplatespecwithenableservicelinks)
      * [`fn withEphemeralContainers(ephemeralContainers)`](#fn-specpodtemplatespecwithephemeralcontainers)
      * [`fn withEphemeralContainersMixin(ephemeralContainers)`](#fn-specpodtemplatespecwithephemeralcontainersmixin)
      * [`fn withHostAliases(hostAliases)`](#fn-specpodtemplatespecwithhostaliases)
      * [`fn withHostAliasesMixin(hostAliases)`](#fn-specpodtemplatespecwithhostaliasesmixin)
      * [`fn withHostIPC(hostIPC)`](#fn-specpodtemplatespecwithhostipc)
      * [`fn withHostNetwork(hostNetwork)`](#fn-specpodtemplatespecwithhostnetwork)
      * [`fn withHostPID(hostPID)`](#fn-specpodtemplatespecwithhostpid)
      * [`fn withHostUsers(hostUsers)`](#fn-specpodtemplatespecwithhostusers)
      * [`fn withHostname(hostname)`](#fn-specpodtemplatespecwithhostname)
      * [`fn withHostnameOverride(hostnameOverride)`](#fn-specpodtemplatespecwithhostnameoverride)
      * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-specpodtemplatespecwithimagepullsecrets)
      * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-specpodtemplatespecwithimagepullsecretsmixin)
      * [`fn withInitContainers(initContainers)`](#fn-specpodtemplatespecwithinitcontainers)
      * [`fn withInitContainersMixin(initContainers)`](#fn-specpodtemplatespecwithinitcontainersmixin)
      * [`fn withNodeName(nodeName)`](#fn-specpodtemplatespecwithnodename)
      * [`fn withNodeSelector(nodeSelector)`](#fn-specpodtemplatespecwithnodeselector)
      * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-specpodtemplatespecwithnodeselectormixin)
      * [`fn withOverhead(overhead)`](#fn-specpodtemplatespecwithoverhead)
      * [`fn withOverheadMixin(overhead)`](#fn-specpodtemplatespecwithoverheadmixin)
      * [`fn withPreemptionPolicy(preemptionPolicy)`](#fn-specpodtemplatespecwithpreemptionpolicy)
      * [`fn withPriority(priority)`](#fn-specpodtemplatespecwithpriority)
      * [`fn withPriorityClassName(priorityClassName)`](#fn-specpodtemplatespecwithpriorityclassname)
      * [`fn withReadinessGates(readinessGates)`](#fn-specpodtemplatespecwithreadinessgates)
      * [`fn withReadinessGatesMixin(readinessGates)`](#fn-specpodtemplatespecwithreadinessgatesmixin)
      * [`fn withResourceClaims(resourceClaims)`](#fn-specpodtemplatespecwithresourceclaims)
      * [`fn withResourceClaimsMixin(resourceClaims)`](#fn-specpodtemplatespecwithresourceclaimsmixin)
      * [`fn withRestartPolicy(restartPolicy)`](#fn-specpodtemplatespecwithrestartpolicy)
      * [`fn withRuntimeClassName(runtimeClassName)`](#fn-specpodtemplatespecwithruntimeclassname)
      * [`fn withSchedulerName(schedulerName)`](#fn-specpodtemplatespecwithschedulername)
      * [`fn withSchedulingGates(schedulingGates)`](#fn-specpodtemplatespecwithschedulinggates)
      * [`fn withSchedulingGatesMixin(schedulingGates)`](#fn-specpodtemplatespecwithschedulinggatesmixin)
      * [`fn withServiceAccount(serviceAccount)`](#fn-specpodtemplatespecwithserviceaccount)
      * [`fn withServiceAccountName(serviceAccountName)`](#fn-specpodtemplatespecwithserviceaccountname)
      * [`fn withSetHostnameAsFQDN(setHostnameAsFQDN)`](#fn-specpodtemplatespecwithsethostnameasfqdn)
      * [`fn withShareProcessNamespace(shareProcessNamespace)`](#fn-specpodtemplatespecwithshareprocessnamespace)
      * [`fn withSubdomain(subdomain)`](#fn-specpodtemplatespecwithsubdomain)
      * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodtemplatespecwithterminationgraceperiodseconds)
      * [`fn withTolerations(tolerations)`](#fn-specpodtemplatespecwithtolerations)
      * [`fn withTolerationsMixin(tolerations)`](#fn-specpodtemplatespecwithtolerationsmixin)
      * [`fn withTopologySpreadConstraints(topologySpreadConstraints)`](#fn-specpodtemplatespecwithtopologyspreadconstraints)
      * [`fn withTopologySpreadConstraintsMixin(topologySpreadConstraints)`](#fn-specpodtemplatespecwithtopologyspreadconstraintsmixin)
      * [`fn withVolumes(volumes)`](#fn-specpodtemplatespecwithvolumes)
      * [`fn withVolumesMixin(volumes)`](#fn-specpodtemplatespecwithvolumesmixin)
      * [`obj spec.podTemplate.spec.affinity`](#obj-specpodtemplatespecaffinity)
        * [`obj spec.podTemplate.spec.affinity.nodeAffinity`](#obj-specpodtemplatespecaffinitynodeaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodtemplatespecaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodtemplatespecaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
              * [`obj spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                * [`fn withKey(key)`](#fn-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
              * [`obj spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                * [`fn withKey(key)`](#fn-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                * [`fn withValues(values)`](#fn-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
          * [`obj spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
            * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
            * [`obj spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
              * [`obj spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                * [`fn withKey(key)`](#fn-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
              * [`obj spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                * [`fn withKey(key)`](#fn-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                * [`fn withValues(values)`](#fn-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
        * [`obj spec.podTemplate.spec.affinity.podAffinity`](#obj-specpodtemplatespecaffinitypodaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodtemplatespecaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodtemplatespecaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodtemplatespecaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodtemplatespecaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
              * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
              * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
              * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
              * [`fn withNamespaces(namespaces)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.podTemplate.spec.affinity.podAntiAffinity`](#obj-specpodtemplatespecaffinitypodantiaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodtemplatespecaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodtemplatespecaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodtemplatespecaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodtemplatespecaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
              * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
              * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
              * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
              * [`fn withNamespaces(namespaces)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.podTemplate.spec.containers`](#obj-specpodtemplatespeccontainers)
        * [`fn withArgs(args)`](#fn-specpodtemplatespeccontainerswithargs)
        * [`fn withArgsMixin(args)`](#fn-specpodtemplatespeccontainerswithargsmixin)
        * [`fn withCommand(command)`](#fn-specpodtemplatespeccontainerswithcommand)
        * [`fn withCommandMixin(command)`](#fn-specpodtemplatespeccontainerswithcommandmixin)
        * [`fn withEnv(env)`](#fn-specpodtemplatespeccontainerswithenv)
        * [`fn withEnvFrom(envFrom)`](#fn-specpodtemplatespeccontainerswithenvfrom)
        * [`fn withEnvFromMixin(envFrom)`](#fn-specpodtemplatespeccontainerswithenvfrommixin)
        * [`fn withEnvMixin(env)`](#fn-specpodtemplatespeccontainerswithenvmixin)
        * [`fn withImage(image)`](#fn-specpodtemplatespeccontainerswithimage)
        * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specpodtemplatespeccontainerswithimagepullpolicy)
        * [`fn withName(name)`](#fn-specpodtemplatespeccontainerswithname)
        * [`fn withPorts(ports)`](#fn-specpodtemplatespeccontainerswithports)
        * [`fn withPortsMixin(ports)`](#fn-specpodtemplatespeccontainerswithportsmixin)
        * [`fn withResizePolicy(resizePolicy)`](#fn-specpodtemplatespeccontainerswithresizepolicy)
        * [`fn withResizePolicyMixin(resizePolicy)`](#fn-specpodtemplatespeccontainerswithresizepolicymixin)
        * [`fn withRestartPolicy(restartPolicy)`](#fn-specpodtemplatespeccontainerswithrestartpolicy)
        * [`fn withRestartPolicyRules(restartPolicyRules)`](#fn-specpodtemplatespeccontainerswithrestartpolicyrules)
        * [`fn withRestartPolicyRulesMixin(restartPolicyRules)`](#fn-specpodtemplatespeccontainerswithrestartpolicyrulesmixin)
        * [`fn withStdin(stdin)`](#fn-specpodtemplatespeccontainerswithstdin)
        * [`fn withStdinOnce(stdinOnce)`](#fn-specpodtemplatespeccontainerswithstdinonce)
        * [`fn withTerminationMessagePath(terminationMessagePath)`](#fn-specpodtemplatespeccontainerswithterminationmessagepath)
        * [`fn withTerminationMessagePolicy(terminationMessagePolicy)`](#fn-specpodtemplatespeccontainerswithterminationmessagepolicy)
        * [`fn withTty(tty)`](#fn-specpodtemplatespeccontainerswithtty)
        * [`fn withVolumeDevices(volumeDevices)`](#fn-specpodtemplatespeccontainerswithvolumedevices)
        * [`fn withVolumeDevicesMixin(volumeDevices)`](#fn-specpodtemplatespeccontainerswithvolumedevicesmixin)
        * [`fn withVolumeMounts(volumeMounts)`](#fn-specpodtemplatespeccontainerswithvolumemounts)
        * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specpodtemplatespeccontainerswithvolumemountsmixin)
        * [`fn withWorkingDir(workingDir)`](#fn-specpodtemplatespeccontainerswithworkingdir)
        * [`obj spec.podTemplate.spec.containers.env`](#obj-specpodtemplatespeccontainersenv)
          * [`fn withName(name)`](#fn-specpodtemplatespeccontainersenvwithname)
          * [`fn withValue(value)`](#fn-specpodtemplatespeccontainersenvwithvalue)
          * [`obj spec.podTemplate.spec.containers.env.valueFrom`](#obj-specpodtemplatespeccontainersenvvaluefrom)
            * [`obj spec.podTemplate.spec.containers.env.valueFrom.configMapKeyRef`](#obj-specpodtemplatespeccontainersenvvaluefromconfigmapkeyref)
              * [`fn withKey(key)`](#fn-specpodtemplatespeccontainersenvvaluefromconfigmapkeyrefwithkey)
              * [`fn withName(name)`](#fn-specpodtemplatespeccontainersenvvaluefromconfigmapkeyrefwithname)
              * [`fn withOptional(optional)`](#fn-specpodtemplatespeccontainersenvvaluefromconfigmapkeyrefwithoptional)
            * [`obj spec.podTemplate.spec.containers.env.valueFrom.fieldRef`](#obj-specpodtemplatespeccontainersenvvaluefromfieldref)
              * [`fn withApiVersion(apiVersion)`](#fn-specpodtemplatespeccontainersenvvaluefromfieldrefwithapiversion)
              * [`fn withFieldPath(fieldPath)`](#fn-specpodtemplatespeccontainersenvvaluefromfieldrefwithfieldpath)
            * [`obj spec.podTemplate.spec.containers.env.valueFrom.fileKeyRef`](#obj-specpodtemplatespeccontainersenvvaluefromfilekeyref)
              * [`fn withKey(key)`](#fn-specpodtemplatespeccontainersenvvaluefromfilekeyrefwithkey)
              * [`fn withOptional(optional)`](#fn-specpodtemplatespeccontainersenvvaluefromfilekeyrefwithoptional)
              * [`fn withPath(path)`](#fn-specpodtemplatespeccontainersenvvaluefromfilekeyrefwithpath)
              * [`fn withVolumeName(volumeName)`](#fn-specpodtemplatespeccontainersenvvaluefromfilekeyrefwithvolumename)
            * [`obj spec.podTemplate.spec.containers.env.valueFrom.resourceFieldRef`](#obj-specpodtemplatespeccontainersenvvaluefromresourcefieldref)
              * [`fn withContainerName(containerName)`](#fn-specpodtemplatespeccontainersenvvaluefromresourcefieldrefwithcontainername)
              * [`fn withDivisor(divisor)`](#fn-specpodtemplatespeccontainersenvvaluefromresourcefieldrefwithdivisor)
              * [`fn withResource(resource)`](#fn-specpodtemplatespeccontainersenvvaluefromresourcefieldrefwithresource)
            * [`obj spec.podTemplate.spec.containers.env.valueFrom.secretKeyRef`](#obj-specpodtemplatespeccontainersenvvaluefromsecretkeyref)
              * [`fn withKey(key)`](#fn-specpodtemplatespeccontainersenvvaluefromsecretkeyrefwithkey)
              * [`fn withName(name)`](#fn-specpodtemplatespeccontainersenvvaluefromsecretkeyrefwithname)
              * [`fn withOptional(optional)`](#fn-specpodtemplatespeccontainersenvvaluefromsecretkeyrefwithoptional)
        * [`obj spec.podTemplate.spec.containers.envFrom`](#obj-specpodtemplatespeccontainersenvfrom)
          * [`fn withPrefix(prefix)`](#fn-specpodtemplatespeccontainersenvfromwithprefix)
          * [`obj spec.podTemplate.spec.containers.envFrom.configMapRef`](#obj-specpodtemplatespeccontainersenvfromconfigmapref)
            * [`fn withName(name)`](#fn-specpodtemplatespeccontainersenvfromconfigmaprefwithname)
            * [`fn withOptional(optional)`](#fn-specpodtemplatespeccontainersenvfromconfigmaprefwithoptional)
          * [`obj spec.podTemplate.spec.containers.envFrom.secretRef`](#obj-specpodtemplatespeccontainersenvfromsecretref)
            * [`fn withName(name)`](#fn-specpodtemplatespeccontainersenvfromsecretrefwithname)
            * [`fn withOptional(optional)`](#fn-specpodtemplatespeccontainersenvfromsecretrefwithoptional)
        * [`obj spec.podTemplate.spec.containers.lifecycle`](#obj-specpodtemplatespeccontainerslifecycle)
          * [`fn withStopSignal(stopSignal)`](#fn-specpodtemplatespeccontainerslifecyclewithstopsignal)
          * [`obj spec.podTemplate.spec.containers.lifecycle.postStart`](#obj-specpodtemplatespeccontainerslifecyclepoststart)
            * [`obj spec.podTemplate.spec.containers.lifecycle.postStart.exec`](#obj-specpodtemplatespeccontainerslifecyclepoststartexec)
              * [`fn withCommand(command)`](#fn-specpodtemplatespeccontainerslifecyclepoststartexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodtemplatespeccontainerslifecyclepoststartexecwithcommandmixin)
            * [`obj spec.podTemplate.spec.containers.lifecycle.postStart.httpGet`](#obj-specpodtemplatespeccontainerslifecyclepoststarthttpget)
              * [`fn withHost(host)`](#fn-specpodtemplatespeccontainerslifecyclepoststarthttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespeccontainerslifecyclepoststarthttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespeccontainerslifecyclepoststarthttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodtemplatespeccontainerslifecyclepoststarthttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodtemplatespeccontainerslifecyclepoststarthttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodtemplatespeccontainerslifecyclepoststarthttpgetwithscheme)
              * [`obj spec.podTemplate.spec.containers.lifecycle.postStart.httpGet.httpHeaders`](#obj-specpodtemplatespeccontainerslifecyclepoststarthttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodtemplatespeccontainerslifecyclepoststarthttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodtemplatespeccontainerslifecyclepoststarthttpgethttpheaderswithvalue)
            * [`obj spec.podTemplate.spec.containers.lifecycle.postStart.sleep`](#obj-specpodtemplatespeccontainerslifecyclepoststartsleep)
              * [`fn withSeconds(seconds)`](#fn-specpodtemplatespeccontainerslifecyclepoststartsleepwithseconds)
            * [`obj spec.podTemplate.spec.containers.lifecycle.postStart.tcpSocket`](#obj-specpodtemplatespeccontainerslifecyclepoststarttcpsocket)
              * [`fn withHost(host)`](#fn-specpodtemplatespeccontainerslifecyclepoststarttcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodtemplatespeccontainerslifecyclepoststarttcpsocketwithport)
          * [`obj spec.podTemplate.spec.containers.lifecycle.preStop`](#obj-specpodtemplatespeccontainerslifecycleprestop)
            * [`obj spec.podTemplate.spec.containers.lifecycle.preStop.exec`](#obj-specpodtemplatespeccontainerslifecycleprestopexec)
              * [`fn withCommand(command)`](#fn-specpodtemplatespeccontainerslifecycleprestopexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodtemplatespeccontainerslifecycleprestopexecwithcommandmixin)
            * [`obj spec.podTemplate.spec.containers.lifecycle.preStop.httpGet`](#obj-specpodtemplatespeccontainerslifecycleprestophttpget)
              * [`fn withHost(host)`](#fn-specpodtemplatespeccontainerslifecycleprestophttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespeccontainerslifecycleprestophttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespeccontainerslifecycleprestophttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodtemplatespeccontainerslifecycleprestophttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodtemplatespeccontainerslifecycleprestophttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodtemplatespeccontainerslifecycleprestophttpgetwithscheme)
              * [`obj spec.podTemplate.spec.containers.lifecycle.preStop.httpGet.httpHeaders`](#obj-specpodtemplatespeccontainerslifecycleprestophttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodtemplatespeccontainerslifecycleprestophttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodtemplatespeccontainerslifecycleprestophttpgethttpheaderswithvalue)
            * [`obj spec.podTemplate.spec.containers.lifecycle.preStop.sleep`](#obj-specpodtemplatespeccontainerslifecycleprestopsleep)
              * [`fn withSeconds(seconds)`](#fn-specpodtemplatespeccontainerslifecycleprestopsleepwithseconds)
            * [`obj spec.podTemplate.spec.containers.lifecycle.preStop.tcpSocket`](#obj-specpodtemplatespeccontainerslifecycleprestoptcpsocket)
              * [`fn withHost(host)`](#fn-specpodtemplatespeccontainerslifecycleprestoptcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodtemplatespeccontainerslifecycleprestoptcpsocketwithport)
        * [`obj spec.podTemplate.spec.containers.livenessProbe`](#obj-specpodtemplatespeccontainerslivenessprobe)
          * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodtemplatespeccontainerslivenessprobewithfailurethreshold)
          * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodtemplatespeccontainerslivenessprobewithinitialdelayseconds)
          * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodtemplatespeccontainerslivenessprobewithperiodseconds)
          * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodtemplatespeccontainerslivenessprobewithsuccessthreshold)
          * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodtemplatespeccontainerslivenessprobewithterminationgraceperiodseconds)
          * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodtemplatespeccontainerslivenessprobewithtimeoutseconds)
          * [`obj spec.podTemplate.spec.containers.livenessProbe.exec`](#obj-specpodtemplatespeccontainerslivenessprobeexec)
            * [`fn withCommand(command)`](#fn-specpodtemplatespeccontainerslivenessprobeexecwithcommand)
            * [`fn withCommandMixin(command)`](#fn-specpodtemplatespeccontainerslivenessprobeexecwithcommandmixin)
          * [`obj spec.podTemplate.spec.containers.livenessProbe.grpc`](#obj-specpodtemplatespeccontainerslivenessprobegrpc)
            * [`fn withPort(port)`](#fn-specpodtemplatespeccontainerslivenessprobegrpcwithport)
            * [`fn withService(service)`](#fn-specpodtemplatespeccontainerslivenessprobegrpcwithservice)
          * [`obj spec.podTemplate.spec.containers.livenessProbe.httpGet`](#obj-specpodtemplatespeccontainerslivenessprobehttpget)
            * [`fn withHost(host)`](#fn-specpodtemplatespeccontainerslivenessprobehttpgetwithhost)
            * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespeccontainerslivenessprobehttpgetwithhttpheaders)
            * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespeccontainerslivenessprobehttpgetwithhttpheadersmixin)
            * [`fn withPath(path)`](#fn-specpodtemplatespeccontainerslivenessprobehttpgetwithpath)
            * [`fn withPort(port)`](#fn-specpodtemplatespeccontainerslivenessprobehttpgetwithport)
            * [`fn withScheme(scheme)`](#fn-specpodtemplatespeccontainerslivenessprobehttpgetwithscheme)
            * [`obj spec.podTemplate.spec.containers.livenessProbe.httpGet.httpHeaders`](#obj-specpodtemplatespeccontainerslivenessprobehttpgethttpheaders)
              * [`fn withName(name)`](#fn-specpodtemplatespeccontainerslivenessprobehttpgethttpheaderswithname)
              * [`fn withValue(value)`](#fn-specpodtemplatespeccontainerslivenessprobehttpgethttpheaderswithvalue)
          * [`obj spec.podTemplate.spec.containers.livenessProbe.tcpSocket`](#obj-specpodtemplatespeccontainerslivenessprobetcpsocket)
            * [`fn withHost(host)`](#fn-specpodtemplatespeccontainerslivenessprobetcpsocketwithhost)
            * [`fn withPort(port)`](#fn-specpodtemplatespeccontainerslivenessprobetcpsocketwithport)
        * [`obj spec.podTemplate.spec.containers.ports`](#obj-specpodtemplatespeccontainersports)
          * [`fn withContainerPort(containerPort)`](#fn-specpodtemplatespeccontainersportswithcontainerport)
          * [`fn withHostIP(hostIP)`](#fn-specpodtemplatespeccontainersportswithhostip)
          * [`fn withHostPort(hostPort)`](#fn-specpodtemplatespeccontainersportswithhostport)
          * [`fn withName(name)`](#fn-specpodtemplatespeccontainersportswithname)
          * [`fn withProtocol(protocol)`](#fn-specpodtemplatespeccontainersportswithprotocol)
        * [`obj spec.podTemplate.spec.containers.readinessProbe`](#obj-specpodtemplatespeccontainersreadinessprobe)
          * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodtemplatespeccontainersreadinessprobewithfailurethreshold)
          * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodtemplatespeccontainersreadinessprobewithinitialdelayseconds)
          * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodtemplatespeccontainersreadinessprobewithperiodseconds)
          * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodtemplatespeccontainersreadinessprobewithsuccessthreshold)
          * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodtemplatespeccontainersreadinessprobewithterminationgraceperiodseconds)
          * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodtemplatespeccontainersreadinessprobewithtimeoutseconds)
          * [`obj spec.podTemplate.spec.containers.readinessProbe.exec`](#obj-specpodtemplatespeccontainersreadinessprobeexec)
            * [`fn withCommand(command)`](#fn-specpodtemplatespeccontainersreadinessprobeexecwithcommand)
            * [`fn withCommandMixin(command)`](#fn-specpodtemplatespeccontainersreadinessprobeexecwithcommandmixin)
          * [`obj spec.podTemplate.spec.containers.readinessProbe.grpc`](#obj-specpodtemplatespeccontainersreadinessprobegrpc)
            * [`fn withPort(port)`](#fn-specpodtemplatespeccontainersreadinessprobegrpcwithport)
            * [`fn withService(service)`](#fn-specpodtemplatespeccontainersreadinessprobegrpcwithservice)
          * [`obj spec.podTemplate.spec.containers.readinessProbe.httpGet`](#obj-specpodtemplatespeccontainersreadinessprobehttpget)
            * [`fn withHost(host)`](#fn-specpodtemplatespeccontainersreadinessprobehttpgetwithhost)
            * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespeccontainersreadinessprobehttpgetwithhttpheaders)
            * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespeccontainersreadinessprobehttpgetwithhttpheadersmixin)
            * [`fn withPath(path)`](#fn-specpodtemplatespeccontainersreadinessprobehttpgetwithpath)
            * [`fn withPort(port)`](#fn-specpodtemplatespeccontainersreadinessprobehttpgetwithport)
            * [`fn withScheme(scheme)`](#fn-specpodtemplatespeccontainersreadinessprobehttpgetwithscheme)
            * [`obj spec.podTemplate.spec.containers.readinessProbe.httpGet.httpHeaders`](#obj-specpodtemplatespeccontainersreadinessprobehttpgethttpheaders)
              * [`fn withName(name)`](#fn-specpodtemplatespeccontainersreadinessprobehttpgethttpheaderswithname)
              * [`fn withValue(value)`](#fn-specpodtemplatespeccontainersreadinessprobehttpgethttpheaderswithvalue)
          * [`obj spec.podTemplate.spec.containers.readinessProbe.tcpSocket`](#obj-specpodtemplatespeccontainersreadinessprobetcpsocket)
            * [`fn withHost(host)`](#fn-specpodtemplatespeccontainersreadinessprobetcpsocketwithhost)
            * [`fn withPort(port)`](#fn-specpodtemplatespeccontainersreadinessprobetcpsocketwithport)
        * [`obj spec.podTemplate.spec.containers.resizePolicy`](#obj-specpodtemplatespeccontainersresizepolicy)
          * [`fn withResourceName(resourceName)`](#fn-specpodtemplatespeccontainersresizepolicywithresourcename)
          * [`fn withRestartPolicy(restartPolicy)`](#fn-specpodtemplatespeccontainersresizepolicywithrestartpolicy)
        * [`obj spec.podTemplate.spec.containers.resources`](#obj-specpodtemplatespeccontainersresources)
          * [`fn withClaims(claims)`](#fn-specpodtemplatespeccontainersresourceswithclaims)
          * [`fn withClaimsMixin(claims)`](#fn-specpodtemplatespeccontainersresourceswithclaimsmixin)
          * [`fn withLimits(limits)`](#fn-specpodtemplatespeccontainersresourceswithlimits)
          * [`fn withLimitsMixin(limits)`](#fn-specpodtemplatespeccontainersresourceswithlimitsmixin)
          * [`fn withRequests(requests)`](#fn-specpodtemplatespeccontainersresourceswithrequests)
          * [`fn withRequestsMixin(requests)`](#fn-specpodtemplatespeccontainersresourceswithrequestsmixin)
          * [`obj spec.podTemplate.spec.containers.resources.claims`](#obj-specpodtemplatespeccontainersresourcesclaims)
            * [`fn withName(name)`](#fn-specpodtemplatespeccontainersresourcesclaimswithname)
            * [`fn withRequest(request)`](#fn-specpodtemplatespeccontainersresourcesclaimswithrequest)
        * [`obj spec.podTemplate.spec.containers.restartPolicyRules`](#obj-specpodtemplatespeccontainersrestartpolicyrules)
          * [`fn withAction(action)`](#fn-specpodtemplatespeccontainersrestartpolicyruleswithaction)
          * [`obj spec.podTemplate.spec.containers.restartPolicyRules.exitCodes`](#obj-specpodtemplatespeccontainersrestartpolicyrulesexitcodes)
            * [`fn withOperator(operator)`](#fn-specpodtemplatespeccontainersrestartpolicyrulesexitcodeswithoperator)
            * [`fn withValues(values)`](#fn-specpodtemplatespeccontainersrestartpolicyrulesexitcodeswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specpodtemplatespeccontainersrestartpolicyrulesexitcodeswithvaluesmixin)
        * [`obj spec.podTemplate.spec.containers.securityContext`](#obj-specpodtemplatespeccontainerssecuritycontext)
          * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specpodtemplatespeccontainerssecuritycontextwithallowprivilegeescalation)
          * [`fn withPrivileged(privileged)`](#fn-specpodtemplatespeccontainerssecuritycontextwithprivileged)
          * [`fn withProcMount(procMount)`](#fn-specpodtemplatespeccontainerssecuritycontextwithprocmount)
          * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specpodtemplatespeccontainerssecuritycontextwithreadonlyrootfilesystem)
          * [`fn withRunAsGroup(runAsGroup)`](#fn-specpodtemplatespeccontainerssecuritycontextwithrunasgroup)
          * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specpodtemplatespeccontainerssecuritycontextwithrunasnonroot)
          * [`fn withRunAsUser(runAsUser)`](#fn-specpodtemplatespeccontainerssecuritycontextwithrunasuser)
          * [`obj spec.podTemplate.spec.containers.securityContext.appArmorProfile`](#obj-specpodtemplatespeccontainerssecuritycontextapparmorprofile)
            * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodtemplatespeccontainerssecuritycontextapparmorprofilewithlocalhostprofile)
            * [`fn withType(type)`](#fn-specpodtemplatespeccontainerssecuritycontextapparmorprofilewithtype)
          * [`obj spec.podTemplate.spec.containers.securityContext.capabilities`](#obj-specpodtemplatespeccontainerssecuritycontextcapabilities)
            * [`fn withAdd(add)`](#fn-specpodtemplatespeccontainerssecuritycontextcapabilitieswithadd)
            * [`fn withAddMixin(add)`](#fn-specpodtemplatespeccontainerssecuritycontextcapabilitieswithaddmixin)
            * [`fn withDrop(drop)`](#fn-specpodtemplatespeccontainerssecuritycontextcapabilitieswithdrop)
            * [`fn withDropMixin(drop)`](#fn-specpodtemplatespeccontainerssecuritycontextcapabilitieswithdropmixin)
          * [`obj spec.podTemplate.spec.containers.securityContext.seLinuxOptions`](#obj-specpodtemplatespeccontainerssecuritycontextselinuxoptions)
            * [`fn withLevel(level)`](#fn-specpodtemplatespeccontainerssecuritycontextselinuxoptionswithlevel)
            * [`fn withRole(role)`](#fn-specpodtemplatespeccontainerssecuritycontextselinuxoptionswithrole)
            * [`fn withType(type)`](#fn-specpodtemplatespeccontainerssecuritycontextselinuxoptionswithtype)
            * [`fn withUser(user)`](#fn-specpodtemplatespeccontainerssecuritycontextselinuxoptionswithuser)
          * [`obj spec.podTemplate.spec.containers.securityContext.seccompProfile`](#obj-specpodtemplatespeccontainerssecuritycontextseccompprofile)
            * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodtemplatespeccontainerssecuritycontextseccompprofilewithlocalhostprofile)
            * [`fn withType(type)`](#fn-specpodtemplatespeccontainerssecuritycontextseccompprofilewithtype)
          * [`obj spec.podTemplate.spec.containers.securityContext.windowsOptions`](#obj-specpodtemplatespeccontainerssecuritycontextwindowsoptions)
            * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specpodtemplatespeccontainerssecuritycontextwindowsoptionswithgmsacredentialspec)
            * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specpodtemplatespeccontainerssecuritycontextwindowsoptionswithgmsacredentialspecname)
            * [`fn withHostProcess(hostProcess)`](#fn-specpodtemplatespeccontainerssecuritycontextwindowsoptionswithhostprocess)
            * [`fn withRunAsUserName(runAsUserName)`](#fn-specpodtemplatespeccontainerssecuritycontextwindowsoptionswithrunasusername)
        * [`obj spec.podTemplate.spec.containers.startupProbe`](#obj-specpodtemplatespeccontainersstartupprobe)
          * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodtemplatespeccontainersstartupprobewithfailurethreshold)
          * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodtemplatespeccontainersstartupprobewithinitialdelayseconds)
          * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodtemplatespeccontainersstartupprobewithperiodseconds)
          * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodtemplatespeccontainersstartupprobewithsuccessthreshold)
          * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodtemplatespeccontainersstartupprobewithterminationgraceperiodseconds)
          * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodtemplatespeccontainersstartupprobewithtimeoutseconds)
          * [`obj spec.podTemplate.spec.containers.startupProbe.exec`](#obj-specpodtemplatespeccontainersstartupprobeexec)
            * [`fn withCommand(command)`](#fn-specpodtemplatespeccontainersstartupprobeexecwithcommand)
            * [`fn withCommandMixin(command)`](#fn-specpodtemplatespeccontainersstartupprobeexecwithcommandmixin)
          * [`obj spec.podTemplate.spec.containers.startupProbe.grpc`](#obj-specpodtemplatespeccontainersstartupprobegrpc)
            * [`fn withPort(port)`](#fn-specpodtemplatespeccontainersstartupprobegrpcwithport)
            * [`fn withService(service)`](#fn-specpodtemplatespeccontainersstartupprobegrpcwithservice)
          * [`obj spec.podTemplate.spec.containers.startupProbe.httpGet`](#obj-specpodtemplatespeccontainersstartupprobehttpget)
            * [`fn withHost(host)`](#fn-specpodtemplatespeccontainersstartupprobehttpgetwithhost)
            * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespeccontainersstartupprobehttpgetwithhttpheaders)
            * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespeccontainersstartupprobehttpgetwithhttpheadersmixin)
            * [`fn withPath(path)`](#fn-specpodtemplatespeccontainersstartupprobehttpgetwithpath)
            * [`fn withPort(port)`](#fn-specpodtemplatespeccontainersstartupprobehttpgetwithport)
            * [`fn withScheme(scheme)`](#fn-specpodtemplatespeccontainersstartupprobehttpgetwithscheme)
            * [`obj spec.podTemplate.spec.containers.startupProbe.httpGet.httpHeaders`](#obj-specpodtemplatespeccontainersstartupprobehttpgethttpheaders)
              * [`fn withName(name)`](#fn-specpodtemplatespeccontainersstartupprobehttpgethttpheaderswithname)
              * [`fn withValue(value)`](#fn-specpodtemplatespeccontainersstartupprobehttpgethttpheaderswithvalue)
          * [`obj spec.podTemplate.spec.containers.startupProbe.tcpSocket`](#obj-specpodtemplatespeccontainersstartupprobetcpsocket)
            * [`fn withHost(host)`](#fn-specpodtemplatespeccontainersstartupprobetcpsocketwithhost)
            * [`fn withPort(port)`](#fn-specpodtemplatespeccontainersstartupprobetcpsocketwithport)
        * [`obj spec.podTemplate.spec.containers.volumeDevices`](#obj-specpodtemplatespeccontainersvolumedevices)
          * [`fn withDevicePath(devicePath)`](#fn-specpodtemplatespeccontainersvolumedeviceswithdevicepath)
          * [`fn withName(name)`](#fn-specpodtemplatespeccontainersvolumedeviceswithname)
        * [`obj spec.podTemplate.spec.containers.volumeMounts`](#obj-specpodtemplatespeccontainersvolumemounts)
          * [`fn withMountPath(mountPath)`](#fn-specpodtemplatespeccontainersvolumemountswithmountpath)
          * [`fn withMountPropagation(mountPropagation)`](#fn-specpodtemplatespeccontainersvolumemountswithmountpropagation)
          * [`fn withName(name)`](#fn-specpodtemplatespeccontainersvolumemountswithname)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespeccontainersvolumemountswithreadonly)
          * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specpodtemplatespeccontainersvolumemountswithrecursivereadonly)
          * [`fn withSubPath(subPath)`](#fn-specpodtemplatespeccontainersvolumemountswithsubpath)
          * [`fn withSubPathExpr(subPathExpr)`](#fn-specpodtemplatespeccontainersvolumemountswithsubpathexpr)
      * [`obj spec.podTemplate.spec.dnsConfig`](#obj-specpodtemplatespecdnsconfig)
        * [`fn withNameservers(nameservers)`](#fn-specpodtemplatespecdnsconfigwithnameservers)
        * [`fn withNameserversMixin(nameservers)`](#fn-specpodtemplatespecdnsconfigwithnameserversmixin)
        * [`fn withOptions(options)`](#fn-specpodtemplatespecdnsconfigwithoptions)
        * [`fn withOptionsMixin(options)`](#fn-specpodtemplatespecdnsconfigwithoptionsmixin)
        * [`fn withSearches(searches)`](#fn-specpodtemplatespecdnsconfigwithsearches)
        * [`fn withSearchesMixin(searches)`](#fn-specpodtemplatespecdnsconfigwithsearchesmixin)
        * [`obj spec.podTemplate.spec.dnsConfig.options`](#obj-specpodtemplatespecdnsconfigoptions)
          * [`fn withName(name)`](#fn-specpodtemplatespecdnsconfigoptionswithname)
          * [`fn withValue(value)`](#fn-specpodtemplatespecdnsconfigoptionswithvalue)
      * [`obj spec.podTemplate.spec.ephemeralContainers`](#obj-specpodtemplatespecephemeralcontainers)
        * [`fn withArgs(args)`](#fn-specpodtemplatespecephemeralcontainerswithargs)
        * [`fn withArgsMixin(args)`](#fn-specpodtemplatespecephemeralcontainerswithargsmixin)
        * [`fn withCommand(command)`](#fn-specpodtemplatespecephemeralcontainerswithcommand)
        * [`fn withCommandMixin(command)`](#fn-specpodtemplatespecephemeralcontainerswithcommandmixin)
        * [`fn withEnv(env)`](#fn-specpodtemplatespecephemeralcontainerswithenv)
        * [`fn withEnvFrom(envFrom)`](#fn-specpodtemplatespecephemeralcontainerswithenvfrom)
        * [`fn withEnvFromMixin(envFrom)`](#fn-specpodtemplatespecephemeralcontainerswithenvfrommixin)
        * [`fn withEnvMixin(env)`](#fn-specpodtemplatespecephemeralcontainerswithenvmixin)
        * [`fn withImage(image)`](#fn-specpodtemplatespecephemeralcontainerswithimage)
        * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specpodtemplatespecephemeralcontainerswithimagepullpolicy)
        * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainerswithname)
        * [`fn withPorts(ports)`](#fn-specpodtemplatespecephemeralcontainerswithports)
        * [`fn withPortsMixin(ports)`](#fn-specpodtemplatespecephemeralcontainerswithportsmixin)
        * [`fn withResizePolicy(resizePolicy)`](#fn-specpodtemplatespecephemeralcontainerswithresizepolicy)
        * [`fn withResizePolicyMixin(resizePolicy)`](#fn-specpodtemplatespecephemeralcontainerswithresizepolicymixin)
        * [`fn withRestartPolicy(restartPolicy)`](#fn-specpodtemplatespecephemeralcontainerswithrestartpolicy)
        * [`fn withRestartPolicyRules(restartPolicyRules)`](#fn-specpodtemplatespecephemeralcontainerswithrestartpolicyrules)
        * [`fn withRestartPolicyRulesMixin(restartPolicyRules)`](#fn-specpodtemplatespecephemeralcontainerswithrestartpolicyrulesmixin)
        * [`fn withStdin(stdin)`](#fn-specpodtemplatespecephemeralcontainerswithstdin)
        * [`fn withStdinOnce(stdinOnce)`](#fn-specpodtemplatespecephemeralcontainerswithstdinonce)
        * [`fn withTargetContainerName(targetContainerName)`](#fn-specpodtemplatespecephemeralcontainerswithtargetcontainername)
        * [`fn withTerminationMessagePath(terminationMessagePath)`](#fn-specpodtemplatespecephemeralcontainerswithterminationmessagepath)
        * [`fn withTerminationMessagePolicy(terminationMessagePolicy)`](#fn-specpodtemplatespecephemeralcontainerswithterminationmessagepolicy)
        * [`fn withTty(tty)`](#fn-specpodtemplatespecephemeralcontainerswithtty)
        * [`fn withVolumeDevices(volumeDevices)`](#fn-specpodtemplatespecephemeralcontainerswithvolumedevices)
        * [`fn withVolumeDevicesMixin(volumeDevices)`](#fn-specpodtemplatespecephemeralcontainerswithvolumedevicesmixin)
        * [`fn withVolumeMounts(volumeMounts)`](#fn-specpodtemplatespecephemeralcontainerswithvolumemounts)
        * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specpodtemplatespecephemeralcontainerswithvolumemountsmixin)
        * [`fn withWorkingDir(workingDir)`](#fn-specpodtemplatespecephemeralcontainerswithworkingdir)
        * [`obj spec.podTemplate.spec.ephemeralContainers.env`](#obj-specpodtemplatespecephemeralcontainersenv)
          * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainersenvwithname)
          * [`fn withValue(value)`](#fn-specpodtemplatespecephemeralcontainersenvwithvalue)
          * [`obj spec.podTemplate.spec.ephemeralContainers.env.valueFrom`](#obj-specpodtemplatespecephemeralcontainersenvvaluefrom)
            * [`obj spec.podTemplate.spec.ephemeralContainers.env.valueFrom.configMapKeyRef`](#obj-specpodtemplatespecephemeralcontainersenvvaluefromconfigmapkeyref)
              * [`fn withKey(key)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromconfigmapkeyrefwithkey)
              * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromconfigmapkeyrefwithname)
              * [`fn withOptional(optional)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromconfigmapkeyrefwithoptional)
            * [`obj spec.podTemplate.spec.ephemeralContainers.env.valueFrom.fieldRef`](#obj-specpodtemplatespecephemeralcontainersenvvaluefromfieldref)
              * [`fn withApiVersion(apiVersion)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromfieldrefwithapiversion)
              * [`fn withFieldPath(fieldPath)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromfieldrefwithfieldpath)
            * [`obj spec.podTemplate.spec.ephemeralContainers.env.valueFrom.fileKeyRef`](#obj-specpodtemplatespecephemeralcontainersenvvaluefromfilekeyref)
              * [`fn withKey(key)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromfilekeyrefwithkey)
              * [`fn withOptional(optional)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromfilekeyrefwithoptional)
              * [`fn withPath(path)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromfilekeyrefwithpath)
              * [`fn withVolumeName(volumeName)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromfilekeyrefwithvolumename)
            * [`obj spec.podTemplate.spec.ephemeralContainers.env.valueFrom.resourceFieldRef`](#obj-specpodtemplatespecephemeralcontainersenvvaluefromresourcefieldref)
              * [`fn withContainerName(containerName)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromresourcefieldrefwithcontainername)
              * [`fn withDivisor(divisor)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromresourcefieldrefwithdivisor)
              * [`fn withResource(resource)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromresourcefieldrefwithresource)
            * [`obj spec.podTemplate.spec.ephemeralContainers.env.valueFrom.secretKeyRef`](#obj-specpodtemplatespecephemeralcontainersenvvaluefromsecretkeyref)
              * [`fn withKey(key)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromsecretkeyrefwithkey)
              * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromsecretkeyrefwithname)
              * [`fn withOptional(optional)`](#fn-specpodtemplatespecephemeralcontainersenvvaluefromsecretkeyrefwithoptional)
        * [`obj spec.podTemplate.spec.ephemeralContainers.envFrom`](#obj-specpodtemplatespecephemeralcontainersenvfrom)
          * [`fn withPrefix(prefix)`](#fn-specpodtemplatespecephemeralcontainersenvfromwithprefix)
          * [`obj spec.podTemplate.spec.ephemeralContainers.envFrom.configMapRef`](#obj-specpodtemplatespecephemeralcontainersenvfromconfigmapref)
            * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainersenvfromconfigmaprefwithname)
            * [`fn withOptional(optional)`](#fn-specpodtemplatespecephemeralcontainersenvfromconfigmaprefwithoptional)
          * [`obj spec.podTemplate.spec.ephemeralContainers.envFrom.secretRef`](#obj-specpodtemplatespecephemeralcontainersenvfromsecretref)
            * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainersenvfromsecretrefwithname)
            * [`fn withOptional(optional)`](#fn-specpodtemplatespecephemeralcontainersenvfromsecretrefwithoptional)
        * [`obj spec.podTemplate.spec.ephemeralContainers.lifecycle`](#obj-specpodtemplatespecephemeralcontainerslifecycle)
          * [`fn withStopSignal(stopSignal)`](#fn-specpodtemplatespecephemeralcontainerslifecyclewithstopsignal)
          * [`obj spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart`](#obj-specpodtemplatespecephemeralcontainerslifecyclepoststart)
            * [`obj spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.exec`](#obj-specpodtemplatespecephemeralcontainerslifecyclepoststartexec)
              * [`fn withCommand(command)`](#fn-specpodtemplatespecephemeralcontainerslifecyclepoststartexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodtemplatespecephemeralcontainerslifecyclepoststartexecwithcommandmixin)
            * [`obj spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet`](#obj-specpodtemplatespecephemeralcontainerslifecyclepoststarthttpget)
              * [`fn withHost(host)`](#fn-specpodtemplatespecephemeralcontainerslifecyclepoststarthttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespecephemeralcontainerslifecyclepoststarthttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespecephemeralcontainerslifecyclepoststarthttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodtemplatespecephemeralcontainerslifecyclepoststarthttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodtemplatespecephemeralcontainerslifecyclepoststarthttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodtemplatespecephemeralcontainerslifecyclepoststarthttpgetwithscheme)
              * [`obj spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders`](#obj-specpodtemplatespecephemeralcontainerslifecyclepoststarthttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainerslifecyclepoststarthttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodtemplatespecephemeralcontainerslifecyclepoststarthttpgethttpheaderswithvalue)
            * [`obj spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.sleep`](#obj-specpodtemplatespecephemeralcontainerslifecyclepoststartsleep)
              * [`fn withSeconds(seconds)`](#fn-specpodtemplatespecephemeralcontainerslifecyclepoststartsleepwithseconds)
            * [`obj spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.tcpSocket`](#obj-specpodtemplatespecephemeralcontainerslifecyclepoststarttcpsocket)
              * [`fn withHost(host)`](#fn-specpodtemplatespecephemeralcontainerslifecyclepoststarttcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodtemplatespecephemeralcontainerslifecyclepoststarttcpsocketwithport)
          * [`obj spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop`](#obj-specpodtemplatespecephemeralcontainerslifecycleprestop)
            * [`obj spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.exec`](#obj-specpodtemplatespecephemeralcontainerslifecycleprestopexec)
              * [`fn withCommand(command)`](#fn-specpodtemplatespecephemeralcontainerslifecycleprestopexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodtemplatespecephemeralcontainerslifecycleprestopexecwithcommandmixin)
            * [`obj spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet`](#obj-specpodtemplatespecephemeralcontainerslifecycleprestophttpget)
              * [`fn withHost(host)`](#fn-specpodtemplatespecephemeralcontainerslifecycleprestophttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespecephemeralcontainerslifecycleprestophttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespecephemeralcontainerslifecycleprestophttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodtemplatespecephemeralcontainerslifecycleprestophttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodtemplatespecephemeralcontainerslifecycleprestophttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodtemplatespecephemeralcontainerslifecycleprestophttpgetwithscheme)
              * [`obj spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders`](#obj-specpodtemplatespecephemeralcontainerslifecycleprestophttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainerslifecycleprestophttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodtemplatespecephemeralcontainerslifecycleprestophttpgethttpheaderswithvalue)
            * [`obj spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.sleep`](#obj-specpodtemplatespecephemeralcontainerslifecycleprestopsleep)
              * [`fn withSeconds(seconds)`](#fn-specpodtemplatespecephemeralcontainerslifecycleprestopsleepwithseconds)
            * [`obj spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.tcpSocket`](#obj-specpodtemplatespecephemeralcontainerslifecycleprestoptcpsocket)
              * [`fn withHost(host)`](#fn-specpodtemplatespecephemeralcontainerslifecycleprestoptcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodtemplatespecephemeralcontainerslifecycleprestoptcpsocketwithport)
        * [`obj spec.podTemplate.spec.ephemeralContainers.livenessProbe`](#obj-specpodtemplatespecephemeralcontainerslivenessprobe)
          * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobewithfailurethreshold)
          * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobewithinitialdelayseconds)
          * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobewithperiodseconds)
          * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobewithsuccessthreshold)
          * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobewithterminationgraceperiodseconds)
          * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobewithtimeoutseconds)
          * [`obj spec.podTemplate.spec.ephemeralContainers.livenessProbe.exec`](#obj-specpodtemplatespecephemeralcontainerslivenessprobeexec)
            * [`fn withCommand(command)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobeexecwithcommand)
            * [`fn withCommandMixin(command)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobeexecwithcommandmixin)
          * [`obj spec.podTemplate.spec.ephemeralContainers.livenessProbe.grpc`](#obj-specpodtemplatespecephemeralcontainerslivenessprobegrpc)
            * [`fn withPort(port)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobegrpcwithport)
            * [`fn withService(service)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobegrpcwithservice)
          * [`obj spec.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet`](#obj-specpodtemplatespecephemeralcontainerslivenessprobehttpget)
            * [`fn withHost(host)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobehttpgetwithhost)
            * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobehttpgetwithhttpheaders)
            * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobehttpgetwithhttpheadersmixin)
            * [`fn withPath(path)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobehttpgetwithpath)
            * [`fn withPort(port)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobehttpgetwithport)
            * [`fn withScheme(scheme)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobehttpgetwithscheme)
            * [`obj spec.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders`](#obj-specpodtemplatespecephemeralcontainerslivenessprobehttpgethttpheaders)
              * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobehttpgethttpheaderswithname)
              * [`fn withValue(value)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobehttpgethttpheaderswithvalue)
          * [`obj spec.podTemplate.spec.ephemeralContainers.livenessProbe.tcpSocket`](#obj-specpodtemplatespecephemeralcontainerslivenessprobetcpsocket)
            * [`fn withHost(host)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobetcpsocketwithhost)
            * [`fn withPort(port)`](#fn-specpodtemplatespecephemeralcontainerslivenessprobetcpsocketwithport)
        * [`obj spec.podTemplate.spec.ephemeralContainers.ports`](#obj-specpodtemplatespecephemeralcontainersports)
          * [`fn withContainerPort(containerPort)`](#fn-specpodtemplatespecephemeralcontainersportswithcontainerport)
          * [`fn withHostIP(hostIP)`](#fn-specpodtemplatespecephemeralcontainersportswithhostip)
          * [`fn withHostPort(hostPort)`](#fn-specpodtemplatespecephemeralcontainersportswithhostport)
          * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainersportswithname)
          * [`fn withProtocol(protocol)`](#fn-specpodtemplatespecephemeralcontainersportswithprotocol)
        * [`obj spec.podTemplate.spec.ephemeralContainers.readinessProbe`](#obj-specpodtemplatespecephemeralcontainersreadinessprobe)
          * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobewithfailurethreshold)
          * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobewithinitialdelayseconds)
          * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobewithperiodseconds)
          * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobewithsuccessthreshold)
          * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobewithterminationgraceperiodseconds)
          * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobewithtimeoutseconds)
          * [`obj spec.podTemplate.spec.ephemeralContainers.readinessProbe.exec`](#obj-specpodtemplatespecephemeralcontainersreadinessprobeexec)
            * [`fn withCommand(command)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobeexecwithcommand)
            * [`fn withCommandMixin(command)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobeexecwithcommandmixin)
          * [`obj spec.podTemplate.spec.ephemeralContainers.readinessProbe.grpc`](#obj-specpodtemplatespecephemeralcontainersreadinessprobegrpc)
            * [`fn withPort(port)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobegrpcwithport)
            * [`fn withService(service)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobegrpcwithservice)
          * [`obj spec.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet`](#obj-specpodtemplatespecephemeralcontainersreadinessprobehttpget)
            * [`fn withHost(host)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobehttpgetwithhost)
            * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobehttpgetwithhttpheaders)
            * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobehttpgetwithhttpheadersmixin)
            * [`fn withPath(path)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobehttpgetwithpath)
            * [`fn withPort(port)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobehttpgetwithport)
            * [`fn withScheme(scheme)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobehttpgetwithscheme)
            * [`obj spec.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders`](#obj-specpodtemplatespecephemeralcontainersreadinessprobehttpgethttpheaders)
              * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobehttpgethttpheaderswithname)
              * [`fn withValue(value)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobehttpgethttpheaderswithvalue)
          * [`obj spec.podTemplate.spec.ephemeralContainers.readinessProbe.tcpSocket`](#obj-specpodtemplatespecephemeralcontainersreadinessprobetcpsocket)
            * [`fn withHost(host)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobetcpsocketwithhost)
            * [`fn withPort(port)`](#fn-specpodtemplatespecephemeralcontainersreadinessprobetcpsocketwithport)
        * [`obj spec.podTemplate.spec.ephemeralContainers.resizePolicy`](#obj-specpodtemplatespecephemeralcontainersresizepolicy)
          * [`fn withResourceName(resourceName)`](#fn-specpodtemplatespecephemeralcontainersresizepolicywithresourcename)
          * [`fn withRestartPolicy(restartPolicy)`](#fn-specpodtemplatespecephemeralcontainersresizepolicywithrestartpolicy)
        * [`obj spec.podTemplate.spec.ephemeralContainers.resources`](#obj-specpodtemplatespecephemeralcontainersresources)
          * [`fn withClaims(claims)`](#fn-specpodtemplatespecephemeralcontainersresourceswithclaims)
          * [`fn withClaimsMixin(claims)`](#fn-specpodtemplatespecephemeralcontainersresourceswithclaimsmixin)
          * [`fn withLimits(limits)`](#fn-specpodtemplatespecephemeralcontainersresourceswithlimits)
          * [`fn withLimitsMixin(limits)`](#fn-specpodtemplatespecephemeralcontainersresourceswithlimitsmixin)
          * [`fn withRequests(requests)`](#fn-specpodtemplatespecephemeralcontainersresourceswithrequests)
          * [`fn withRequestsMixin(requests)`](#fn-specpodtemplatespecephemeralcontainersresourceswithrequestsmixin)
          * [`obj spec.podTemplate.spec.ephemeralContainers.resources.claims`](#obj-specpodtemplatespecephemeralcontainersresourcesclaims)
            * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainersresourcesclaimswithname)
            * [`fn withRequest(request)`](#fn-specpodtemplatespecephemeralcontainersresourcesclaimswithrequest)
        * [`obj spec.podTemplate.spec.ephemeralContainers.restartPolicyRules`](#obj-specpodtemplatespecephemeralcontainersrestartpolicyrules)
          * [`fn withAction(action)`](#fn-specpodtemplatespecephemeralcontainersrestartpolicyruleswithaction)
          * [`obj spec.podTemplate.spec.ephemeralContainers.restartPolicyRules.exitCodes`](#obj-specpodtemplatespecephemeralcontainersrestartpolicyrulesexitcodes)
            * [`fn withOperator(operator)`](#fn-specpodtemplatespecephemeralcontainersrestartpolicyrulesexitcodeswithoperator)
            * [`fn withValues(values)`](#fn-specpodtemplatespecephemeralcontainersrestartpolicyrulesexitcodeswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecephemeralcontainersrestartpolicyrulesexitcodeswithvaluesmixin)
        * [`obj spec.podTemplate.spec.ephemeralContainers.securityContext`](#obj-specpodtemplatespecephemeralcontainerssecuritycontext)
          * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextwithallowprivilegeescalation)
          * [`fn withPrivileged(privileged)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextwithprivileged)
          * [`fn withProcMount(procMount)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextwithprocmount)
          * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextwithreadonlyrootfilesystem)
          * [`fn withRunAsGroup(runAsGroup)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextwithrunasgroup)
          * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextwithrunasnonroot)
          * [`fn withRunAsUser(runAsUser)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextwithrunasuser)
          * [`obj spec.podTemplate.spec.ephemeralContainers.securityContext.appArmorProfile`](#obj-specpodtemplatespecephemeralcontainerssecuritycontextapparmorprofile)
            * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextapparmorprofilewithlocalhostprofile)
            * [`fn withType(type)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextapparmorprofilewithtype)
          * [`obj spec.podTemplate.spec.ephemeralContainers.securityContext.capabilities`](#obj-specpodtemplatespecephemeralcontainerssecuritycontextcapabilities)
            * [`fn withAdd(add)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextcapabilitieswithadd)
            * [`fn withAddMixin(add)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextcapabilitieswithaddmixin)
            * [`fn withDrop(drop)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextcapabilitieswithdrop)
            * [`fn withDropMixin(drop)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextcapabilitieswithdropmixin)
          * [`obj spec.podTemplate.spec.ephemeralContainers.securityContext.seLinuxOptions`](#obj-specpodtemplatespecephemeralcontainerssecuritycontextselinuxoptions)
            * [`fn withLevel(level)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextselinuxoptionswithlevel)
            * [`fn withRole(role)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextselinuxoptionswithrole)
            * [`fn withType(type)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextselinuxoptionswithtype)
            * [`fn withUser(user)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextselinuxoptionswithuser)
          * [`obj spec.podTemplate.spec.ephemeralContainers.securityContext.seccompProfile`](#obj-specpodtemplatespecephemeralcontainerssecuritycontextseccompprofile)
            * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextseccompprofilewithlocalhostprofile)
            * [`fn withType(type)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextseccompprofilewithtype)
          * [`obj spec.podTemplate.spec.ephemeralContainers.securityContext.windowsOptions`](#obj-specpodtemplatespecephemeralcontainerssecuritycontextwindowsoptions)
            * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextwindowsoptionswithgmsacredentialspec)
            * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextwindowsoptionswithgmsacredentialspecname)
            * [`fn withHostProcess(hostProcess)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextwindowsoptionswithhostprocess)
            * [`fn withRunAsUserName(runAsUserName)`](#fn-specpodtemplatespecephemeralcontainerssecuritycontextwindowsoptionswithrunasusername)
        * [`obj spec.podTemplate.spec.ephemeralContainers.startupProbe`](#obj-specpodtemplatespecephemeralcontainersstartupprobe)
          * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodtemplatespecephemeralcontainersstartupprobewithfailurethreshold)
          * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodtemplatespecephemeralcontainersstartupprobewithinitialdelayseconds)
          * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodtemplatespecephemeralcontainersstartupprobewithperiodseconds)
          * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodtemplatespecephemeralcontainersstartupprobewithsuccessthreshold)
          * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodtemplatespecephemeralcontainersstartupprobewithterminationgraceperiodseconds)
          * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodtemplatespecephemeralcontainersstartupprobewithtimeoutseconds)
          * [`obj spec.podTemplate.spec.ephemeralContainers.startupProbe.exec`](#obj-specpodtemplatespecephemeralcontainersstartupprobeexec)
            * [`fn withCommand(command)`](#fn-specpodtemplatespecephemeralcontainersstartupprobeexecwithcommand)
            * [`fn withCommandMixin(command)`](#fn-specpodtemplatespecephemeralcontainersstartupprobeexecwithcommandmixin)
          * [`obj spec.podTemplate.spec.ephemeralContainers.startupProbe.grpc`](#obj-specpodtemplatespecephemeralcontainersstartupprobegrpc)
            * [`fn withPort(port)`](#fn-specpodtemplatespecephemeralcontainersstartupprobegrpcwithport)
            * [`fn withService(service)`](#fn-specpodtemplatespecephemeralcontainersstartupprobegrpcwithservice)
          * [`obj spec.podTemplate.spec.ephemeralContainers.startupProbe.httpGet`](#obj-specpodtemplatespecephemeralcontainersstartupprobehttpget)
            * [`fn withHost(host)`](#fn-specpodtemplatespecephemeralcontainersstartupprobehttpgetwithhost)
            * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespecephemeralcontainersstartupprobehttpgetwithhttpheaders)
            * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespecephemeralcontainersstartupprobehttpgetwithhttpheadersmixin)
            * [`fn withPath(path)`](#fn-specpodtemplatespecephemeralcontainersstartupprobehttpgetwithpath)
            * [`fn withPort(port)`](#fn-specpodtemplatespecephemeralcontainersstartupprobehttpgetwithport)
            * [`fn withScheme(scheme)`](#fn-specpodtemplatespecephemeralcontainersstartupprobehttpgetwithscheme)
            * [`obj spec.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders`](#obj-specpodtemplatespecephemeralcontainersstartupprobehttpgethttpheaders)
              * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainersstartupprobehttpgethttpheaderswithname)
              * [`fn withValue(value)`](#fn-specpodtemplatespecephemeralcontainersstartupprobehttpgethttpheaderswithvalue)
          * [`obj spec.podTemplate.spec.ephemeralContainers.startupProbe.tcpSocket`](#obj-specpodtemplatespecephemeralcontainersstartupprobetcpsocket)
            * [`fn withHost(host)`](#fn-specpodtemplatespecephemeralcontainersstartupprobetcpsocketwithhost)
            * [`fn withPort(port)`](#fn-specpodtemplatespecephemeralcontainersstartupprobetcpsocketwithport)
        * [`obj spec.podTemplate.spec.ephemeralContainers.volumeDevices`](#obj-specpodtemplatespecephemeralcontainersvolumedevices)
          * [`fn withDevicePath(devicePath)`](#fn-specpodtemplatespecephemeralcontainersvolumedeviceswithdevicepath)
          * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainersvolumedeviceswithname)
        * [`obj spec.podTemplate.spec.ephemeralContainers.volumeMounts`](#obj-specpodtemplatespecephemeralcontainersvolumemounts)
          * [`fn withMountPath(mountPath)`](#fn-specpodtemplatespecephemeralcontainersvolumemountswithmountpath)
          * [`fn withMountPropagation(mountPropagation)`](#fn-specpodtemplatespecephemeralcontainersvolumemountswithmountpropagation)
          * [`fn withName(name)`](#fn-specpodtemplatespecephemeralcontainersvolumemountswithname)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecephemeralcontainersvolumemountswithreadonly)
          * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specpodtemplatespecephemeralcontainersvolumemountswithrecursivereadonly)
          * [`fn withSubPath(subPath)`](#fn-specpodtemplatespecephemeralcontainersvolumemountswithsubpath)
          * [`fn withSubPathExpr(subPathExpr)`](#fn-specpodtemplatespecephemeralcontainersvolumemountswithsubpathexpr)
      * [`obj spec.podTemplate.spec.hostAliases`](#obj-specpodtemplatespechostaliases)
        * [`fn withHostnames(hostnames)`](#fn-specpodtemplatespechostaliaseswithhostnames)
        * [`fn withHostnamesMixin(hostnames)`](#fn-specpodtemplatespechostaliaseswithhostnamesmixin)
        * [`fn withIp(ip)`](#fn-specpodtemplatespechostaliaseswithip)
      * [`obj spec.podTemplate.spec.imagePullSecrets`](#obj-specpodtemplatespecimagepullsecrets)
        * [`fn withName(name)`](#fn-specpodtemplatespecimagepullsecretswithname)
      * [`obj spec.podTemplate.spec.initContainers`](#obj-specpodtemplatespecinitcontainers)
        * [`fn withArgs(args)`](#fn-specpodtemplatespecinitcontainerswithargs)
        * [`fn withArgsMixin(args)`](#fn-specpodtemplatespecinitcontainerswithargsmixin)
        * [`fn withCommand(command)`](#fn-specpodtemplatespecinitcontainerswithcommand)
        * [`fn withCommandMixin(command)`](#fn-specpodtemplatespecinitcontainerswithcommandmixin)
        * [`fn withEnv(env)`](#fn-specpodtemplatespecinitcontainerswithenv)
        * [`fn withEnvFrom(envFrom)`](#fn-specpodtemplatespecinitcontainerswithenvfrom)
        * [`fn withEnvFromMixin(envFrom)`](#fn-specpodtemplatespecinitcontainerswithenvfrommixin)
        * [`fn withEnvMixin(env)`](#fn-specpodtemplatespecinitcontainerswithenvmixin)
        * [`fn withImage(image)`](#fn-specpodtemplatespecinitcontainerswithimage)
        * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specpodtemplatespecinitcontainerswithimagepullpolicy)
        * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainerswithname)
        * [`fn withPorts(ports)`](#fn-specpodtemplatespecinitcontainerswithports)
        * [`fn withPortsMixin(ports)`](#fn-specpodtemplatespecinitcontainerswithportsmixin)
        * [`fn withResizePolicy(resizePolicy)`](#fn-specpodtemplatespecinitcontainerswithresizepolicy)
        * [`fn withResizePolicyMixin(resizePolicy)`](#fn-specpodtemplatespecinitcontainerswithresizepolicymixin)
        * [`fn withRestartPolicy(restartPolicy)`](#fn-specpodtemplatespecinitcontainerswithrestartpolicy)
        * [`fn withRestartPolicyRules(restartPolicyRules)`](#fn-specpodtemplatespecinitcontainerswithrestartpolicyrules)
        * [`fn withRestartPolicyRulesMixin(restartPolicyRules)`](#fn-specpodtemplatespecinitcontainerswithrestartpolicyrulesmixin)
        * [`fn withStdin(stdin)`](#fn-specpodtemplatespecinitcontainerswithstdin)
        * [`fn withStdinOnce(stdinOnce)`](#fn-specpodtemplatespecinitcontainerswithstdinonce)
        * [`fn withTerminationMessagePath(terminationMessagePath)`](#fn-specpodtemplatespecinitcontainerswithterminationmessagepath)
        * [`fn withTerminationMessagePolicy(terminationMessagePolicy)`](#fn-specpodtemplatespecinitcontainerswithterminationmessagepolicy)
        * [`fn withTty(tty)`](#fn-specpodtemplatespecinitcontainerswithtty)
        * [`fn withVolumeDevices(volumeDevices)`](#fn-specpodtemplatespecinitcontainerswithvolumedevices)
        * [`fn withVolumeDevicesMixin(volumeDevices)`](#fn-specpodtemplatespecinitcontainerswithvolumedevicesmixin)
        * [`fn withVolumeMounts(volumeMounts)`](#fn-specpodtemplatespecinitcontainerswithvolumemounts)
        * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specpodtemplatespecinitcontainerswithvolumemountsmixin)
        * [`fn withWorkingDir(workingDir)`](#fn-specpodtemplatespecinitcontainerswithworkingdir)
        * [`obj spec.podTemplate.spec.initContainers.env`](#obj-specpodtemplatespecinitcontainersenv)
          * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainersenvwithname)
          * [`fn withValue(value)`](#fn-specpodtemplatespecinitcontainersenvwithvalue)
          * [`obj spec.podTemplate.spec.initContainers.env.valueFrom`](#obj-specpodtemplatespecinitcontainersenvvaluefrom)
            * [`obj spec.podTemplate.spec.initContainers.env.valueFrom.configMapKeyRef`](#obj-specpodtemplatespecinitcontainersenvvaluefromconfigmapkeyref)
              * [`fn withKey(key)`](#fn-specpodtemplatespecinitcontainersenvvaluefromconfigmapkeyrefwithkey)
              * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainersenvvaluefromconfigmapkeyrefwithname)
              * [`fn withOptional(optional)`](#fn-specpodtemplatespecinitcontainersenvvaluefromconfigmapkeyrefwithoptional)
            * [`obj spec.podTemplate.spec.initContainers.env.valueFrom.fieldRef`](#obj-specpodtemplatespecinitcontainersenvvaluefromfieldref)
              * [`fn withApiVersion(apiVersion)`](#fn-specpodtemplatespecinitcontainersenvvaluefromfieldrefwithapiversion)
              * [`fn withFieldPath(fieldPath)`](#fn-specpodtemplatespecinitcontainersenvvaluefromfieldrefwithfieldpath)
            * [`obj spec.podTemplate.spec.initContainers.env.valueFrom.fileKeyRef`](#obj-specpodtemplatespecinitcontainersenvvaluefromfilekeyref)
              * [`fn withKey(key)`](#fn-specpodtemplatespecinitcontainersenvvaluefromfilekeyrefwithkey)
              * [`fn withOptional(optional)`](#fn-specpodtemplatespecinitcontainersenvvaluefromfilekeyrefwithoptional)
              * [`fn withPath(path)`](#fn-specpodtemplatespecinitcontainersenvvaluefromfilekeyrefwithpath)
              * [`fn withVolumeName(volumeName)`](#fn-specpodtemplatespecinitcontainersenvvaluefromfilekeyrefwithvolumename)
            * [`obj spec.podTemplate.spec.initContainers.env.valueFrom.resourceFieldRef`](#obj-specpodtemplatespecinitcontainersenvvaluefromresourcefieldref)
              * [`fn withContainerName(containerName)`](#fn-specpodtemplatespecinitcontainersenvvaluefromresourcefieldrefwithcontainername)
              * [`fn withDivisor(divisor)`](#fn-specpodtemplatespecinitcontainersenvvaluefromresourcefieldrefwithdivisor)
              * [`fn withResource(resource)`](#fn-specpodtemplatespecinitcontainersenvvaluefromresourcefieldrefwithresource)
            * [`obj spec.podTemplate.spec.initContainers.env.valueFrom.secretKeyRef`](#obj-specpodtemplatespecinitcontainersenvvaluefromsecretkeyref)
              * [`fn withKey(key)`](#fn-specpodtemplatespecinitcontainersenvvaluefromsecretkeyrefwithkey)
              * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainersenvvaluefromsecretkeyrefwithname)
              * [`fn withOptional(optional)`](#fn-specpodtemplatespecinitcontainersenvvaluefromsecretkeyrefwithoptional)
        * [`obj spec.podTemplate.spec.initContainers.envFrom`](#obj-specpodtemplatespecinitcontainersenvfrom)
          * [`fn withPrefix(prefix)`](#fn-specpodtemplatespecinitcontainersenvfromwithprefix)
          * [`obj spec.podTemplate.spec.initContainers.envFrom.configMapRef`](#obj-specpodtemplatespecinitcontainersenvfromconfigmapref)
            * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainersenvfromconfigmaprefwithname)
            * [`fn withOptional(optional)`](#fn-specpodtemplatespecinitcontainersenvfromconfigmaprefwithoptional)
          * [`obj spec.podTemplate.spec.initContainers.envFrom.secretRef`](#obj-specpodtemplatespecinitcontainersenvfromsecretref)
            * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainersenvfromsecretrefwithname)
            * [`fn withOptional(optional)`](#fn-specpodtemplatespecinitcontainersenvfromsecretrefwithoptional)
        * [`obj spec.podTemplate.spec.initContainers.lifecycle`](#obj-specpodtemplatespecinitcontainerslifecycle)
          * [`fn withStopSignal(stopSignal)`](#fn-specpodtemplatespecinitcontainerslifecyclewithstopsignal)
          * [`obj spec.podTemplate.spec.initContainers.lifecycle.postStart`](#obj-specpodtemplatespecinitcontainerslifecyclepoststart)
            * [`obj spec.podTemplate.spec.initContainers.lifecycle.postStart.exec`](#obj-specpodtemplatespecinitcontainerslifecyclepoststartexec)
              * [`fn withCommand(command)`](#fn-specpodtemplatespecinitcontainerslifecyclepoststartexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodtemplatespecinitcontainerslifecyclepoststartexecwithcommandmixin)
            * [`obj spec.podTemplate.spec.initContainers.lifecycle.postStart.httpGet`](#obj-specpodtemplatespecinitcontainerslifecyclepoststarthttpget)
              * [`fn withHost(host)`](#fn-specpodtemplatespecinitcontainerslifecyclepoststarthttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespecinitcontainerslifecyclepoststarthttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespecinitcontainerslifecyclepoststarthttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodtemplatespecinitcontainerslifecyclepoststarthttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodtemplatespecinitcontainerslifecyclepoststarthttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodtemplatespecinitcontainerslifecyclepoststarthttpgetwithscheme)
              * [`obj spec.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders`](#obj-specpodtemplatespecinitcontainerslifecyclepoststarthttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainerslifecyclepoststarthttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodtemplatespecinitcontainerslifecyclepoststarthttpgethttpheaderswithvalue)
            * [`obj spec.podTemplate.spec.initContainers.lifecycle.postStart.sleep`](#obj-specpodtemplatespecinitcontainerslifecyclepoststartsleep)
              * [`fn withSeconds(seconds)`](#fn-specpodtemplatespecinitcontainerslifecyclepoststartsleepwithseconds)
            * [`obj spec.podTemplate.spec.initContainers.lifecycle.postStart.tcpSocket`](#obj-specpodtemplatespecinitcontainerslifecyclepoststarttcpsocket)
              * [`fn withHost(host)`](#fn-specpodtemplatespecinitcontainerslifecyclepoststarttcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodtemplatespecinitcontainerslifecyclepoststarttcpsocketwithport)
          * [`obj spec.podTemplate.spec.initContainers.lifecycle.preStop`](#obj-specpodtemplatespecinitcontainerslifecycleprestop)
            * [`obj spec.podTemplate.spec.initContainers.lifecycle.preStop.exec`](#obj-specpodtemplatespecinitcontainerslifecycleprestopexec)
              * [`fn withCommand(command)`](#fn-specpodtemplatespecinitcontainerslifecycleprestopexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodtemplatespecinitcontainerslifecycleprestopexecwithcommandmixin)
            * [`obj spec.podTemplate.spec.initContainers.lifecycle.preStop.httpGet`](#obj-specpodtemplatespecinitcontainerslifecycleprestophttpget)
              * [`fn withHost(host)`](#fn-specpodtemplatespecinitcontainerslifecycleprestophttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespecinitcontainerslifecycleprestophttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespecinitcontainerslifecycleprestophttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodtemplatespecinitcontainerslifecycleprestophttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodtemplatespecinitcontainerslifecycleprestophttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodtemplatespecinitcontainerslifecycleprestophttpgetwithscheme)
              * [`obj spec.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders`](#obj-specpodtemplatespecinitcontainerslifecycleprestophttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainerslifecycleprestophttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodtemplatespecinitcontainerslifecycleprestophttpgethttpheaderswithvalue)
            * [`obj spec.podTemplate.spec.initContainers.lifecycle.preStop.sleep`](#obj-specpodtemplatespecinitcontainerslifecycleprestopsleep)
              * [`fn withSeconds(seconds)`](#fn-specpodtemplatespecinitcontainerslifecycleprestopsleepwithseconds)
            * [`obj spec.podTemplate.spec.initContainers.lifecycle.preStop.tcpSocket`](#obj-specpodtemplatespecinitcontainerslifecycleprestoptcpsocket)
              * [`fn withHost(host)`](#fn-specpodtemplatespecinitcontainerslifecycleprestoptcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodtemplatespecinitcontainerslifecycleprestoptcpsocketwithport)
        * [`obj spec.podTemplate.spec.initContainers.livenessProbe`](#obj-specpodtemplatespecinitcontainerslivenessprobe)
          * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodtemplatespecinitcontainerslivenessprobewithfailurethreshold)
          * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodtemplatespecinitcontainerslivenessprobewithinitialdelayseconds)
          * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodtemplatespecinitcontainerslivenessprobewithperiodseconds)
          * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodtemplatespecinitcontainerslivenessprobewithsuccessthreshold)
          * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodtemplatespecinitcontainerslivenessprobewithterminationgraceperiodseconds)
          * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodtemplatespecinitcontainerslivenessprobewithtimeoutseconds)
          * [`obj spec.podTemplate.spec.initContainers.livenessProbe.exec`](#obj-specpodtemplatespecinitcontainerslivenessprobeexec)
            * [`fn withCommand(command)`](#fn-specpodtemplatespecinitcontainerslivenessprobeexecwithcommand)
            * [`fn withCommandMixin(command)`](#fn-specpodtemplatespecinitcontainerslivenessprobeexecwithcommandmixin)
          * [`obj spec.podTemplate.spec.initContainers.livenessProbe.grpc`](#obj-specpodtemplatespecinitcontainerslivenessprobegrpc)
            * [`fn withPort(port)`](#fn-specpodtemplatespecinitcontainerslivenessprobegrpcwithport)
            * [`fn withService(service)`](#fn-specpodtemplatespecinitcontainerslivenessprobegrpcwithservice)
          * [`obj spec.podTemplate.spec.initContainers.livenessProbe.httpGet`](#obj-specpodtemplatespecinitcontainerslivenessprobehttpget)
            * [`fn withHost(host)`](#fn-specpodtemplatespecinitcontainerslivenessprobehttpgetwithhost)
            * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespecinitcontainerslivenessprobehttpgetwithhttpheaders)
            * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespecinitcontainerslivenessprobehttpgetwithhttpheadersmixin)
            * [`fn withPath(path)`](#fn-specpodtemplatespecinitcontainerslivenessprobehttpgetwithpath)
            * [`fn withPort(port)`](#fn-specpodtemplatespecinitcontainerslivenessprobehttpgetwithport)
            * [`fn withScheme(scheme)`](#fn-specpodtemplatespecinitcontainerslivenessprobehttpgetwithscheme)
            * [`obj spec.podTemplate.spec.initContainers.livenessProbe.httpGet.httpHeaders`](#obj-specpodtemplatespecinitcontainerslivenessprobehttpgethttpheaders)
              * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainerslivenessprobehttpgethttpheaderswithname)
              * [`fn withValue(value)`](#fn-specpodtemplatespecinitcontainerslivenessprobehttpgethttpheaderswithvalue)
          * [`obj spec.podTemplate.spec.initContainers.livenessProbe.tcpSocket`](#obj-specpodtemplatespecinitcontainerslivenessprobetcpsocket)
            * [`fn withHost(host)`](#fn-specpodtemplatespecinitcontainerslivenessprobetcpsocketwithhost)
            * [`fn withPort(port)`](#fn-specpodtemplatespecinitcontainerslivenessprobetcpsocketwithport)
        * [`obj spec.podTemplate.spec.initContainers.ports`](#obj-specpodtemplatespecinitcontainersports)
          * [`fn withContainerPort(containerPort)`](#fn-specpodtemplatespecinitcontainersportswithcontainerport)
          * [`fn withHostIP(hostIP)`](#fn-specpodtemplatespecinitcontainersportswithhostip)
          * [`fn withHostPort(hostPort)`](#fn-specpodtemplatespecinitcontainersportswithhostport)
          * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainersportswithname)
          * [`fn withProtocol(protocol)`](#fn-specpodtemplatespecinitcontainersportswithprotocol)
        * [`obj spec.podTemplate.spec.initContainers.readinessProbe`](#obj-specpodtemplatespecinitcontainersreadinessprobe)
          * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodtemplatespecinitcontainersreadinessprobewithfailurethreshold)
          * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodtemplatespecinitcontainersreadinessprobewithinitialdelayseconds)
          * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodtemplatespecinitcontainersreadinessprobewithperiodseconds)
          * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodtemplatespecinitcontainersreadinessprobewithsuccessthreshold)
          * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodtemplatespecinitcontainersreadinessprobewithterminationgraceperiodseconds)
          * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodtemplatespecinitcontainersreadinessprobewithtimeoutseconds)
          * [`obj spec.podTemplate.spec.initContainers.readinessProbe.exec`](#obj-specpodtemplatespecinitcontainersreadinessprobeexec)
            * [`fn withCommand(command)`](#fn-specpodtemplatespecinitcontainersreadinessprobeexecwithcommand)
            * [`fn withCommandMixin(command)`](#fn-specpodtemplatespecinitcontainersreadinessprobeexecwithcommandmixin)
          * [`obj spec.podTemplate.spec.initContainers.readinessProbe.grpc`](#obj-specpodtemplatespecinitcontainersreadinessprobegrpc)
            * [`fn withPort(port)`](#fn-specpodtemplatespecinitcontainersreadinessprobegrpcwithport)
            * [`fn withService(service)`](#fn-specpodtemplatespecinitcontainersreadinessprobegrpcwithservice)
          * [`obj spec.podTemplate.spec.initContainers.readinessProbe.httpGet`](#obj-specpodtemplatespecinitcontainersreadinessprobehttpget)
            * [`fn withHost(host)`](#fn-specpodtemplatespecinitcontainersreadinessprobehttpgetwithhost)
            * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespecinitcontainersreadinessprobehttpgetwithhttpheaders)
            * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespecinitcontainersreadinessprobehttpgetwithhttpheadersmixin)
            * [`fn withPath(path)`](#fn-specpodtemplatespecinitcontainersreadinessprobehttpgetwithpath)
            * [`fn withPort(port)`](#fn-specpodtemplatespecinitcontainersreadinessprobehttpgetwithport)
            * [`fn withScheme(scheme)`](#fn-specpodtemplatespecinitcontainersreadinessprobehttpgetwithscheme)
            * [`obj spec.podTemplate.spec.initContainers.readinessProbe.httpGet.httpHeaders`](#obj-specpodtemplatespecinitcontainersreadinessprobehttpgethttpheaders)
              * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainersreadinessprobehttpgethttpheaderswithname)
              * [`fn withValue(value)`](#fn-specpodtemplatespecinitcontainersreadinessprobehttpgethttpheaderswithvalue)
          * [`obj spec.podTemplate.spec.initContainers.readinessProbe.tcpSocket`](#obj-specpodtemplatespecinitcontainersreadinessprobetcpsocket)
            * [`fn withHost(host)`](#fn-specpodtemplatespecinitcontainersreadinessprobetcpsocketwithhost)
            * [`fn withPort(port)`](#fn-specpodtemplatespecinitcontainersreadinessprobetcpsocketwithport)
        * [`obj spec.podTemplate.spec.initContainers.resizePolicy`](#obj-specpodtemplatespecinitcontainersresizepolicy)
          * [`fn withResourceName(resourceName)`](#fn-specpodtemplatespecinitcontainersresizepolicywithresourcename)
          * [`fn withRestartPolicy(restartPolicy)`](#fn-specpodtemplatespecinitcontainersresizepolicywithrestartpolicy)
        * [`obj spec.podTemplate.spec.initContainers.resources`](#obj-specpodtemplatespecinitcontainersresources)
          * [`fn withClaims(claims)`](#fn-specpodtemplatespecinitcontainersresourceswithclaims)
          * [`fn withClaimsMixin(claims)`](#fn-specpodtemplatespecinitcontainersresourceswithclaimsmixin)
          * [`fn withLimits(limits)`](#fn-specpodtemplatespecinitcontainersresourceswithlimits)
          * [`fn withLimitsMixin(limits)`](#fn-specpodtemplatespecinitcontainersresourceswithlimitsmixin)
          * [`fn withRequests(requests)`](#fn-specpodtemplatespecinitcontainersresourceswithrequests)
          * [`fn withRequestsMixin(requests)`](#fn-specpodtemplatespecinitcontainersresourceswithrequestsmixin)
          * [`obj spec.podTemplate.spec.initContainers.resources.claims`](#obj-specpodtemplatespecinitcontainersresourcesclaims)
            * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainersresourcesclaimswithname)
            * [`fn withRequest(request)`](#fn-specpodtemplatespecinitcontainersresourcesclaimswithrequest)
        * [`obj spec.podTemplate.spec.initContainers.restartPolicyRules`](#obj-specpodtemplatespecinitcontainersrestartpolicyrules)
          * [`fn withAction(action)`](#fn-specpodtemplatespecinitcontainersrestartpolicyruleswithaction)
          * [`obj spec.podTemplate.spec.initContainers.restartPolicyRules.exitCodes`](#obj-specpodtemplatespecinitcontainersrestartpolicyrulesexitcodes)
            * [`fn withOperator(operator)`](#fn-specpodtemplatespecinitcontainersrestartpolicyrulesexitcodeswithoperator)
            * [`fn withValues(values)`](#fn-specpodtemplatespecinitcontainersrestartpolicyrulesexitcodeswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecinitcontainersrestartpolicyrulesexitcodeswithvaluesmixin)
        * [`obj spec.podTemplate.spec.initContainers.securityContext`](#obj-specpodtemplatespecinitcontainerssecuritycontext)
          * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specpodtemplatespecinitcontainerssecuritycontextwithallowprivilegeescalation)
          * [`fn withPrivileged(privileged)`](#fn-specpodtemplatespecinitcontainerssecuritycontextwithprivileged)
          * [`fn withProcMount(procMount)`](#fn-specpodtemplatespecinitcontainerssecuritycontextwithprocmount)
          * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specpodtemplatespecinitcontainerssecuritycontextwithreadonlyrootfilesystem)
          * [`fn withRunAsGroup(runAsGroup)`](#fn-specpodtemplatespecinitcontainerssecuritycontextwithrunasgroup)
          * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specpodtemplatespecinitcontainerssecuritycontextwithrunasnonroot)
          * [`fn withRunAsUser(runAsUser)`](#fn-specpodtemplatespecinitcontainerssecuritycontextwithrunasuser)
          * [`obj spec.podTemplate.spec.initContainers.securityContext.appArmorProfile`](#obj-specpodtemplatespecinitcontainerssecuritycontextapparmorprofile)
            * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodtemplatespecinitcontainerssecuritycontextapparmorprofilewithlocalhostprofile)
            * [`fn withType(type)`](#fn-specpodtemplatespecinitcontainerssecuritycontextapparmorprofilewithtype)
          * [`obj spec.podTemplate.spec.initContainers.securityContext.capabilities`](#obj-specpodtemplatespecinitcontainerssecuritycontextcapabilities)
            * [`fn withAdd(add)`](#fn-specpodtemplatespecinitcontainerssecuritycontextcapabilitieswithadd)
            * [`fn withAddMixin(add)`](#fn-specpodtemplatespecinitcontainerssecuritycontextcapabilitieswithaddmixin)
            * [`fn withDrop(drop)`](#fn-specpodtemplatespecinitcontainerssecuritycontextcapabilitieswithdrop)
            * [`fn withDropMixin(drop)`](#fn-specpodtemplatespecinitcontainerssecuritycontextcapabilitieswithdropmixin)
          * [`obj spec.podTemplate.spec.initContainers.securityContext.seLinuxOptions`](#obj-specpodtemplatespecinitcontainerssecuritycontextselinuxoptions)
            * [`fn withLevel(level)`](#fn-specpodtemplatespecinitcontainerssecuritycontextselinuxoptionswithlevel)
            * [`fn withRole(role)`](#fn-specpodtemplatespecinitcontainerssecuritycontextselinuxoptionswithrole)
            * [`fn withType(type)`](#fn-specpodtemplatespecinitcontainerssecuritycontextselinuxoptionswithtype)
            * [`fn withUser(user)`](#fn-specpodtemplatespecinitcontainerssecuritycontextselinuxoptionswithuser)
          * [`obj spec.podTemplate.spec.initContainers.securityContext.seccompProfile`](#obj-specpodtemplatespecinitcontainerssecuritycontextseccompprofile)
            * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodtemplatespecinitcontainerssecuritycontextseccompprofilewithlocalhostprofile)
            * [`fn withType(type)`](#fn-specpodtemplatespecinitcontainerssecuritycontextseccompprofilewithtype)
          * [`obj spec.podTemplate.spec.initContainers.securityContext.windowsOptions`](#obj-specpodtemplatespecinitcontainerssecuritycontextwindowsoptions)
            * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specpodtemplatespecinitcontainerssecuritycontextwindowsoptionswithgmsacredentialspec)
            * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specpodtemplatespecinitcontainerssecuritycontextwindowsoptionswithgmsacredentialspecname)
            * [`fn withHostProcess(hostProcess)`](#fn-specpodtemplatespecinitcontainerssecuritycontextwindowsoptionswithhostprocess)
            * [`fn withRunAsUserName(runAsUserName)`](#fn-specpodtemplatespecinitcontainerssecuritycontextwindowsoptionswithrunasusername)
        * [`obj spec.podTemplate.spec.initContainers.startupProbe`](#obj-specpodtemplatespecinitcontainersstartupprobe)
          * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodtemplatespecinitcontainersstartupprobewithfailurethreshold)
          * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodtemplatespecinitcontainersstartupprobewithinitialdelayseconds)
          * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodtemplatespecinitcontainersstartupprobewithperiodseconds)
          * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodtemplatespecinitcontainersstartupprobewithsuccessthreshold)
          * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodtemplatespecinitcontainersstartupprobewithterminationgraceperiodseconds)
          * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodtemplatespecinitcontainersstartupprobewithtimeoutseconds)
          * [`obj spec.podTemplate.spec.initContainers.startupProbe.exec`](#obj-specpodtemplatespecinitcontainersstartupprobeexec)
            * [`fn withCommand(command)`](#fn-specpodtemplatespecinitcontainersstartupprobeexecwithcommand)
            * [`fn withCommandMixin(command)`](#fn-specpodtemplatespecinitcontainersstartupprobeexecwithcommandmixin)
          * [`obj spec.podTemplate.spec.initContainers.startupProbe.grpc`](#obj-specpodtemplatespecinitcontainersstartupprobegrpc)
            * [`fn withPort(port)`](#fn-specpodtemplatespecinitcontainersstartupprobegrpcwithport)
            * [`fn withService(service)`](#fn-specpodtemplatespecinitcontainersstartupprobegrpcwithservice)
          * [`obj spec.podTemplate.spec.initContainers.startupProbe.httpGet`](#obj-specpodtemplatespecinitcontainersstartupprobehttpget)
            * [`fn withHost(host)`](#fn-specpodtemplatespecinitcontainersstartupprobehttpgetwithhost)
            * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodtemplatespecinitcontainersstartupprobehttpgetwithhttpheaders)
            * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodtemplatespecinitcontainersstartupprobehttpgetwithhttpheadersmixin)
            * [`fn withPath(path)`](#fn-specpodtemplatespecinitcontainersstartupprobehttpgetwithpath)
            * [`fn withPort(port)`](#fn-specpodtemplatespecinitcontainersstartupprobehttpgetwithport)
            * [`fn withScheme(scheme)`](#fn-specpodtemplatespecinitcontainersstartupprobehttpgetwithscheme)
            * [`obj spec.podTemplate.spec.initContainers.startupProbe.httpGet.httpHeaders`](#obj-specpodtemplatespecinitcontainersstartupprobehttpgethttpheaders)
              * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainersstartupprobehttpgethttpheaderswithname)
              * [`fn withValue(value)`](#fn-specpodtemplatespecinitcontainersstartupprobehttpgethttpheaderswithvalue)
          * [`obj spec.podTemplate.spec.initContainers.startupProbe.tcpSocket`](#obj-specpodtemplatespecinitcontainersstartupprobetcpsocket)
            * [`fn withHost(host)`](#fn-specpodtemplatespecinitcontainersstartupprobetcpsocketwithhost)
            * [`fn withPort(port)`](#fn-specpodtemplatespecinitcontainersstartupprobetcpsocketwithport)
        * [`obj spec.podTemplate.spec.initContainers.volumeDevices`](#obj-specpodtemplatespecinitcontainersvolumedevices)
          * [`fn withDevicePath(devicePath)`](#fn-specpodtemplatespecinitcontainersvolumedeviceswithdevicepath)
          * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainersvolumedeviceswithname)
        * [`obj spec.podTemplate.spec.initContainers.volumeMounts`](#obj-specpodtemplatespecinitcontainersvolumemounts)
          * [`fn withMountPath(mountPath)`](#fn-specpodtemplatespecinitcontainersvolumemountswithmountpath)
          * [`fn withMountPropagation(mountPropagation)`](#fn-specpodtemplatespecinitcontainersvolumemountswithmountpropagation)
          * [`fn withName(name)`](#fn-specpodtemplatespecinitcontainersvolumemountswithname)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecinitcontainersvolumemountswithreadonly)
          * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specpodtemplatespecinitcontainersvolumemountswithrecursivereadonly)
          * [`fn withSubPath(subPath)`](#fn-specpodtemplatespecinitcontainersvolumemountswithsubpath)
          * [`fn withSubPathExpr(subPathExpr)`](#fn-specpodtemplatespecinitcontainersvolumemountswithsubpathexpr)
      * [`obj spec.podTemplate.spec.os`](#obj-specpodtemplatespecos)
        * [`fn withName(name)`](#fn-specpodtemplatespecoswithname)
      * [`obj spec.podTemplate.spec.readinessGates`](#obj-specpodtemplatespecreadinessgates)
        * [`fn withConditionType(conditionType)`](#fn-specpodtemplatespecreadinessgateswithconditiontype)
      * [`obj spec.podTemplate.spec.resourceClaims`](#obj-specpodtemplatespecresourceclaims)
        * [`fn withName(name)`](#fn-specpodtemplatespecresourceclaimswithname)
        * [`fn withResourceClaimName(resourceClaimName)`](#fn-specpodtemplatespecresourceclaimswithresourceclaimname)
        * [`fn withResourceClaimTemplateName(resourceClaimTemplateName)`](#fn-specpodtemplatespecresourceclaimswithresourceclaimtemplatename)
      * [`obj spec.podTemplate.spec.resources`](#obj-specpodtemplatespecresources)
        * [`fn withClaims(claims)`](#fn-specpodtemplatespecresourceswithclaims)
        * [`fn withClaimsMixin(claims)`](#fn-specpodtemplatespecresourceswithclaimsmixin)
        * [`fn withLimits(limits)`](#fn-specpodtemplatespecresourceswithlimits)
        * [`fn withLimitsMixin(limits)`](#fn-specpodtemplatespecresourceswithlimitsmixin)
        * [`fn withRequests(requests)`](#fn-specpodtemplatespecresourceswithrequests)
        * [`fn withRequestsMixin(requests)`](#fn-specpodtemplatespecresourceswithrequestsmixin)
        * [`obj spec.podTemplate.spec.resources.claims`](#obj-specpodtemplatespecresourcesclaims)
          * [`fn withName(name)`](#fn-specpodtemplatespecresourcesclaimswithname)
          * [`fn withRequest(request)`](#fn-specpodtemplatespecresourcesclaimswithrequest)
      * [`obj spec.podTemplate.spec.schedulingGates`](#obj-specpodtemplatespecschedulinggates)
        * [`fn withName(name)`](#fn-specpodtemplatespecschedulinggateswithname)
      * [`obj spec.podTemplate.spec.securityContext`](#obj-specpodtemplatespecsecuritycontext)
        * [`fn withFsGroup(fsGroup)`](#fn-specpodtemplatespecsecuritycontextwithfsgroup)
        * [`fn withFsGroupChangePolicy(fsGroupChangePolicy)`](#fn-specpodtemplatespecsecuritycontextwithfsgroupchangepolicy)
        * [`fn withRunAsGroup(runAsGroup)`](#fn-specpodtemplatespecsecuritycontextwithrunasgroup)
        * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specpodtemplatespecsecuritycontextwithrunasnonroot)
        * [`fn withRunAsUser(runAsUser)`](#fn-specpodtemplatespecsecuritycontextwithrunasuser)
        * [`fn withSeLinuxChangePolicy(seLinuxChangePolicy)`](#fn-specpodtemplatespecsecuritycontextwithselinuxchangepolicy)
        * [`fn withSupplementalGroups(supplementalGroups)`](#fn-specpodtemplatespecsecuritycontextwithsupplementalgroups)
        * [`fn withSupplementalGroupsMixin(supplementalGroups)`](#fn-specpodtemplatespecsecuritycontextwithsupplementalgroupsmixin)
        * [`fn withSupplementalGroupsPolicy(supplementalGroupsPolicy)`](#fn-specpodtemplatespecsecuritycontextwithsupplementalgroupspolicy)
        * [`fn withSysctls(sysctls)`](#fn-specpodtemplatespecsecuritycontextwithsysctls)
        * [`fn withSysctlsMixin(sysctls)`](#fn-specpodtemplatespecsecuritycontextwithsysctlsmixin)
        * [`obj spec.podTemplate.spec.securityContext.appArmorProfile`](#obj-specpodtemplatespecsecuritycontextapparmorprofile)
          * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodtemplatespecsecuritycontextapparmorprofilewithlocalhostprofile)
          * [`fn withType(type)`](#fn-specpodtemplatespecsecuritycontextapparmorprofilewithtype)
        * [`obj spec.podTemplate.spec.securityContext.seLinuxOptions`](#obj-specpodtemplatespecsecuritycontextselinuxoptions)
          * [`fn withLevel(level)`](#fn-specpodtemplatespecsecuritycontextselinuxoptionswithlevel)
          * [`fn withRole(role)`](#fn-specpodtemplatespecsecuritycontextselinuxoptionswithrole)
          * [`fn withType(type)`](#fn-specpodtemplatespecsecuritycontextselinuxoptionswithtype)
          * [`fn withUser(user)`](#fn-specpodtemplatespecsecuritycontextselinuxoptionswithuser)
        * [`obj spec.podTemplate.spec.securityContext.seccompProfile`](#obj-specpodtemplatespecsecuritycontextseccompprofile)
          * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodtemplatespecsecuritycontextseccompprofilewithlocalhostprofile)
          * [`fn withType(type)`](#fn-specpodtemplatespecsecuritycontextseccompprofilewithtype)
        * [`obj spec.podTemplate.spec.securityContext.sysctls`](#obj-specpodtemplatespecsecuritycontextsysctls)
          * [`fn withName(name)`](#fn-specpodtemplatespecsecuritycontextsysctlswithname)
          * [`fn withValue(value)`](#fn-specpodtemplatespecsecuritycontextsysctlswithvalue)
        * [`obj spec.podTemplate.spec.securityContext.windowsOptions`](#obj-specpodtemplatespecsecuritycontextwindowsoptions)
          * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specpodtemplatespecsecuritycontextwindowsoptionswithgmsacredentialspec)
          * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specpodtemplatespecsecuritycontextwindowsoptionswithgmsacredentialspecname)
          * [`fn withHostProcess(hostProcess)`](#fn-specpodtemplatespecsecuritycontextwindowsoptionswithhostprocess)
          * [`fn withRunAsUserName(runAsUserName)`](#fn-specpodtemplatespecsecuritycontextwindowsoptionswithrunasusername)
      * [`obj spec.podTemplate.spec.tolerations`](#obj-specpodtemplatespectolerations)
        * [`fn withEffect(effect)`](#fn-specpodtemplatespectolerationswitheffect)
        * [`fn withKey(key)`](#fn-specpodtemplatespectolerationswithkey)
        * [`fn withOperator(operator)`](#fn-specpodtemplatespectolerationswithoperator)
        * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-specpodtemplatespectolerationswithtolerationseconds)
        * [`fn withValue(value)`](#fn-specpodtemplatespectolerationswithvalue)
      * [`obj spec.podTemplate.spec.topologySpreadConstraints`](#obj-specpodtemplatespectopologyspreadconstraints)
        * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpodtemplatespectopologyspreadconstraintswithmatchlabelkeys)
        * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpodtemplatespectopologyspreadconstraintswithmatchlabelkeysmixin)
        * [`fn withMaxSkew(maxSkew)`](#fn-specpodtemplatespectopologyspreadconstraintswithmaxskew)
        * [`fn withMinDomains(minDomains)`](#fn-specpodtemplatespectopologyspreadconstraintswithmindomains)
        * [`fn withNodeAffinityPolicy(nodeAffinityPolicy)`](#fn-specpodtemplatespectopologyspreadconstraintswithnodeaffinitypolicy)
        * [`fn withNodeTaintsPolicy(nodeTaintsPolicy)`](#fn-specpodtemplatespectopologyspreadconstraintswithnodetaintspolicy)
        * [`fn withTopologyKey(topologyKey)`](#fn-specpodtemplatespectopologyspreadconstraintswithtopologykey)
        * [`fn withWhenUnsatisfiable(whenUnsatisfiable)`](#fn-specpodtemplatespectopologyspreadconstraintswithwhenunsatisfiable)
        * [`obj spec.podTemplate.spec.topologySpreadConstraints.labelSelector`](#obj-specpodtemplatespectopologyspreadconstraintslabelselector)
          * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodtemplatespectopologyspreadconstraintslabelselectorwithmatchexpressions)
          * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodtemplatespectopologyspreadconstraintslabelselectorwithmatchexpressionsmixin)
          * [`fn withMatchLabels(matchLabels)`](#fn-specpodtemplatespectopologyspreadconstraintslabelselectorwithmatchlabels)
          * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodtemplatespectopologyspreadconstraintslabelselectorwithmatchlabelsmixin)
          * [`obj spec.podTemplate.spec.topologySpreadConstraints.labelSelector.matchExpressions`](#obj-specpodtemplatespectopologyspreadconstraintslabelselectormatchexpressions)
            * [`fn withKey(key)`](#fn-specpodtemplatespectopologyspreadconstraintslabelselectormatchexpressionswithkey)
            * [`fn withOperator(operator)`](#fn-specpodtemplatespectopologyspreadconstraintslabelselectormatchexpressionswithoperator)
            * [`fn withValues(values)`](#fn-specpodtemplatespectopologyspreadconstraintslabelselectormatchexpressionswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specpodtemplatespectopologyspreadconstraintslabelselectormatchexpressionswithvaluesmixin)
      * [`obj spec.podTemplate.spec.volumes`](#obj-specpodtemplatespecvolumes)
        * [`fn withName(name)`](#fn-specpodtemplatespecvolumeswithname)
        * [`obj spec.podTemplate.spec.volumes.awsElasticBlockStore`](#obj-specpodtemplatespecvolumesawselasticblockstore)
          * [`fn withFsType(fsType)`](#fn-specpodtemplatespecvolumesawselasticblockstorewithfstype)
          * [`fn withPartition(partition)`](#fn-specpodtemplatespecvolumesawselasticblockstorewithpartition)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumesawselasticblockstorewithreadonly)
          * [`fn withVolumeID(volumeID)`](#fn-specpodtemplatespecvolumesawselasticblockstorewithvolumeid)
        * [`obj spec.podTemplate.spec.volumes.azureDisk`](#obj-specpodtemplatespecvolumesazuredisk)
          * [`fn withCachingMode(cachingMode)`](#fn-specpodtemplatespecvolumesazurediskwithcachingmode)
          * [`fn withDiskName(diskName)`](#fn-specpodtemplatespecvolumesazurediskwithdiskname)
          * [`fn withDiskURI(diskURI)`](#fn-specpodtemplatespecvolumesazurediskwithdiskuri)
          * [`fn withFsType(fsType)`](#fn-specpodtemplatespecvolumesazurediskwithfstype)
          * [`fn withKind(kind)`](#fn-specpodtemplatespecvolumesazurediskwithkind)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumesazurediskwithreadonly)
        * [`obj spec.podTemplate.spec.volumes.azureFile`](#obj-specpodtemplatespecvolumesazurefile)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumesazurefilewithreadonly)
          * [`fn withSecretName(secretName)`](#fn-specpodtemplatespecvolumesazurefilewithsecretname)
          * [`fn withShareName(shareName)`](#fn-specpodtemplatespecvolumesazurefilewithsharename)
        * [`obj spec.podTemplate.spec.volumes.cephfs`](#obj-specpodtemplatespecvolumescephfs)
          * [`fn withMonitors(monitors)`](#fn-specpodtemplatespecvolumescephfswithmonitors)
          * [`fn withMonitorsMixin(monitors)`](#fn-specpodtemplatespecvolumescephfswithmonitorsmixin)
          * [`fn withPath(path)`](#fn-specpodtemplatespecvolumescephfswithpath)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumescephfswithreadonly)
          * [`fn withSecretFile(secretFile)`](#fn-specpodtemplatespecvolumescephfswithsecretfile)
          * [`fn withUser(user)`](#fn-specpodtemplatespecvolumescephfswithuser)
          * [`obj spec.podTemplate.spec.volumes.cephfs.secretRef`](#obj-specpodtemplatespecvolumescephfssecretref)
            * [`fn withName(name)`](#fn-specpodtemplatespecvolumescephfssecretrefwithname)
        * [`obj spec.podTemplate.spec.volumes.cinder`](#obj-specpodtemplatespecvolumescinder)
          * [`fn withFsType(fsType)`](#fn-specpodtemplatespecvolumescinderwithfstype)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumescinderwithreadonly)
          * [`fn withVolumeID(volumeID)`](#fn-specpodtemplatespecvolumescinderwithvolumeid)
          * [`obj spec.podTemplate.spec.volumes.cinder.secretRef`](#obj-specpodtemplatespecvolumescindersecretref)
            * [`fn withName(name)`](#fn-specpodtemplatespecvolumescindersecretrefwithname)
        * [`obj spec.podTemplate.spec.volumes.configMap`](#obj-specpodtemplatespecvolumesconfigmap)
          * [`fn withDefaultMode(defaultMode)`](#fn-specpodtemplatespecvolumesconfigmapwithdefaultmode)
          * [`fn withItems(items)`](#fn-specpodtemplatespecvolumesconfigmapwithitems)
          * [`fn withItemsMixin(items)`](#fn-specpodtemplatespecvolumesconfigmapwithitemsmixin)
          * [`fn withName(name)`](#fn-specpodtemplatespecvolumesconfigmapwithname)
          * [`fn withOptional(optional)`](#fn-specpodtemplatespecvolumesconfigmapwithoptional)
          * [`obj spec.podTemplate.spec.volumes.configMap.items`](#obj-specpodtemplatespecvolumesconfigmapitems)
            * [`fn withKey(key)`](#fn-specpodtemplatespecvolumesconfigmapitemswithkey)
            * [`fn withMode(mode)`](#fn-specpodtemplatespecvolumesconfigmapitemswithmode)
            * [`fn withPath(path)`](#fn-specpodtemplatespecvolumesconfigmapitemswithpath)
        * [`obj spec.podTemplate.spec.volumes.csi`](#obj-specpodtemplatespecvolumescsi)
          * [`fn withDriver(driver)`](#fn-specpodtemplatespecvolumescsiwithdriver)
          * [`fn withFsType(fsType)`](#fn-specpodtemplatespecvolumescsiwithfstype)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumescsiwithreadonly)
          * [`fn withVolumeAttributes(volumeAttributes)`](#fn-specpodtemplatespecvolumescsiwithvolumeattributes)
          * [`fn withVolumeAttributesMixin(volumeAttributes)`](#fn-specpodtemplatespecvolumescsiwithvolumeattributesmixin)
          * [`obj spec.podTemplate.spec.volumes.csi.nodePublishSecretRef`](#obj-specpodtemplatespecvolumescsinodepublishsecretref)
            * [`fn withName(name)`](#fn-specpodtemplatespecvolumescsinodepublishsecretrefwithname)
        * [`obj spec.podTemplate.spec.volumes.downwardAPI`](#obj-specpodtemplatespecvolumesdownwardapi)
          * [`fn withDefaultMode(defaultMode)`](#fn-specpodtemplatespecvolumesdownwardapiwithdefaultmode)
          * [`fn withItems(items)`](#fn-specpodtemplatespecvolumesdownwardapiwithitems)
          * [`fn withItemsMixin(items)`](#fn-specpodtemplatespecvolumesdownwardapiwithitemsmixin)
          * [`obj spec.podTemplate.spec.volumes.downwardAPI.items`](#obj-specpodtemplatespecvolumesdownwardapiitems)
            * [`fn withMode(mode)`](#fn-specpodtemplatespecvolumesdownwardapiitemswithmode)
            * [`fn withPath(path)`](#fn-specpodtemplatespecvolumesdownwardapiitemswithpath)
            * [`obj spec.podTemplate.spec.volumes.downwardAPI.items.fieldRef`](#obj-specpodtemplatespecvolumesdownwardapiitemsfieldref)
              * [`fn withApiVersion(apiVersion)`](#fn-specpodtemplatespecvolumesdownwardapiitemsfieldrefwithapiversion)
              * [`fn withFieldPath(fieldPath)`](#fn-specpodtemplatespecvolumesdownwardapiitemsfieldrefwithfieldpath)
            * [`obj spec.podTemplate.spec.volumes.downwardAPI.items.resourceFieldRef`](#obj-specpodtemplatespecvolumesdownwardapiitemsresourcefieldref)
              * [`fn withContainerName(containerName)`](#fn-specpodtemplatespecvolumesdownwardapiitemsresourcefieldrefwithcontainername)
              * [`fn withDivisor(divisor)`](#fn-specpodtemplatespecvolumesdownwardapiitemsresourcefieldrefwithdivisor)
              * [`fn withResource(resource)`](#fn-specpodtemplatespecvolumesdownwardapiitemsresourcefieldrefwithresource)
        * [`obj spec.podTemplate.spec.volumes.emptyDir`](#obj-specpodtemplatespecvolumesemptydir)
          * [`fn withMedium(medium)`](#fn-specpodtemplatespecvolumesemptydirwithmedium)
          * [`fn withSizeLimit(sizeLimit)`](#fn-specpodtemplatespecvolumesemptydirwithsizelimit)
        * [`obj spec.podTemplate.spec.volumes.ephemeral`](#obj-specpodtemplatespecvolumesephemeral)
          * [`obj spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate`](#obj-specpodtemplatespecvolumesephemeralvolumeclaimtemplate)
            * [`fn withMetadata(metadata)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatewithmetadata)
            * [`fn withMetadataMixin(metadata)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatewithmetadatamixin)
            * [`obj spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec`](#obj-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespec)
              * [`fn withAccessModes(accessModes)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecwithaccessmodes)
              * [`fn withAccessModesMixin(accessModes)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecwithaccessmodesmixin)
              * [`fn withStorageClassName(storageClassName)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecwithstorageclassname)
              * [`fn withVolumeAttributesClassName(volumeAttributesClassName)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecwithvolumeattributesclassname)
              * [`fn withVolumeMode(volumeMode)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecwithvolumemode)
              * [`fn withVolumeName(volumeName)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecwithvolumename)
              * [`obj spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource`](#obj-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasource)
                * [`fn withApiGroup(apiGroup)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcewithapigroup)
                * [`fn withKind(kind)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcewithkind)
                * [`fn withName(name)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcewithname)
              * [`obj spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef`](#obj-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourceref)
                * [`fn withApiGroup(apiGroup)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithapigroup)
                * [`fn withKind(kind)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithkind)
                * [`fn withName(name)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithname)
                * [`fn withNamespace(namespace)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithnamespace)
              * [`obj spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources`](#obj-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecresources)
                * [`fn withLimits(limits)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithlimits)
                * [`fn withLimitsMixin(limits)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithlimitsmixin)
                * [`fn withRequests(requests)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithrequests)
                * [`fn withRequestsMixin(requests)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithrequestsmixin)
              * [`obj spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector`](#obj-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabelsmixin)
                * [`obj spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions`](#obj-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvaluesmixin)
        * [`obj spec.podTemplate.spec.volumes.fc`](#obj-specpodtemplatespecvolumesfc)
          * [`fn withFsType(fsType)`](#fn-specpodtemplatespecvolumesfcwithfstype)
          * [`fn withLun(lun)`](#fn-specpodtemplatespecvolumesfcwithlun)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumesfcwithreadonly)
          * [`fn withTargetWWNs(targetWWNs)`](#fn-specpodtemplatespecvolumesfcwithtargetwwns)
          * [`fn withTargetWWNsMixin(targetWWNs)`](#fn-specpodtemplatespecvolumesfcwithtargetwwnsmixin)
          * [`fn withWwids(wwids)`](#fn-specpodtemplatespecvolumesfcwithwwids)
          * [`fn withWwidsMixin(wwids)`](#fn-specpodtemplatespecvolumesfcwithwwidsmixin)
        * [`obj spec.podTemplate.spec.volumes.flexVolume`](#obj-specpodtemplatespecvolumesflexvolume)
          * [`fn withDriver(driver)`](#fn-specpodtemplatespecvolumesflexvolumewithdriver)
          * [`fn withFsType(fsType)`](#fn-specpodtemplatespecvolumesflexvolumewithfstype)
          * [`fn withOptions(options)`](#fn-specpodtemplatespecvolumesflexvolumewithoptions)
          * [`fn withOptionsMixin(options)`](#fn-specpodtemplatespecvolumesflexvolumewithoptionsmixin)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumesflexvolumewithreadonly)
          * [`obj spec.podTemplate.spec.volumes.flexVolume.secretRef`](#obj-specpodtemplatespecvolumesflexvolumesecretref)
            * [`fn withName(name)`](#fn-specpodtemplatespecvolumesflexvolumesecretrefwithname)
        * [`obj spec.podTemplate.spec.volumes.flocker`](#obj-specpodtemplatespecvolumesflocker)
          * [`fn withDatasetName(datasetName)`](#fn-specpodtemplatespecvolumesflockerwithdatasetname)
          * [`fn withDatasetUUID(datasetUUID)`](#fn-specpodtemplatespecvolumesflockerwithdatasetuuid)
        * [`obj spec.podTemplate.spec.volumes.gcePersistentDisk`](#obj-specpodtemplatespecvolumesgcepersistentdisk)
          * [`fn withFsType(fsType)`](#fn-specpodtemplatespecvolumesgcepersistentdiskwithfstype)
          * [`fn withPartition(partition)`](#fn-specpodtemplatespecvolumesgcepersistentdiskwithpartition)
          * [`fn withPdName(pdName)`](#fn-specpodtemplatespecvolumesgcepersistentdiskwithpdname)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumesgcepersistentdiskwithreadonly)
        * [`obj spec.podTemplate.spec.volumes.gitRepo`](#obj-specpodtemplatespecvolumesgitrepo)
          * [`fn withDirectory(directory)`](#fn-specpodtemplatespecvolumesgitrepowithdirectory)
          * [`fn withRepository(repository)`](#fn-specpodtemplatespecvolumesgitrepowithrepository)
          * [`fn withRevision(revision)`](#fn-specpodtemplatespecvolumesgitrepowithrevision)
        * [`obj spec.podTemplate.spec.volumes.glusterfs`](#obj-specpodtemplatespecvolumesglusterfs)
          * [`fn withEndpoints(endpoints)`](#fn-specpodtemplatespecvolumesglusterfswithendpoints)
          * [`fn withPath(path)`](#fn-specpodtemplatespecvolumesglusterfswithpath)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumesglusterfswithreadonly)
        * [`obj spec.podTemplate.spec.volumes.hostPath`](#obj-specpodtemplatespecvolumeshostpath)
          * [`fn withPath(path)`](#fn-specpodtemplatespecvolumeshostpathwithpath)
          * [`fn withType(type)`](#fn-specpodtemplatespecvolumeshostpathwithtype)
        * [`obj spec.podTemplate.spec.volumes.image`](#obj-specpodtemplatespecvolumesimage)
          * [`fn withPullPolicy(pullPolicy)`](#fn-specpodtemplatespecvolumesimagewithpullpolicy)
          * [`fn withReference(reference)`](#fn-specpodtemplatespecvolumesimagewithreference)
        * [`obj spec.podTemplate.spec.volumes.iscsi`](#obj-specpodtemplatespecvolumesiscsi)
          * [`fn withChapAuthDiscovery(chapAuthDiscovery)`](#fn-specpodtemplatespecvolumesiscsiwithchapauthdiscovery)
          * [`fn withChapAuthSession(chapAuthSession)`](#fn-specpodtemplatespecvolumesiscsiwithchapauthsession)
          * [`fn withFsType(fsType)`](#fn-specpodtemplatespecvolumesiscsiwithfstype)
          * [`fn withInitiatorName(initiatorName)`](#fn-specpodtemplatespecvolumesiscsiwithinitiatorname)
          * [`fn withIqn(iqn)`](#fn-specpodtemplatespecvolumesiscsiwithiqn)
          * [`fn withIscsiInterface(iscsiInterface)`](#fn-specpodtemplatespecvolumesiscsiwithiscsiinterface)
          * [`fn withLun(lun)`](#fn-specpodtemplatespecvolumesiscsiwithlun)
          * [`fn withPortals(portals)`](#fn-specpodtemplatespecvolumesiscsiwithportals)
          * [`fn withPortalsMixin(portals)`](#fn-specpodtemplatespecvolumesiscsiwithportalsmixin)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumesiscsiwithreadonly)
          * [`fn withTargetPortal(targetPortal)`](#fn-specpodtemplatespecvolumesiscsiwithtargetportal)
          * [`obj spec.podTemplate.spec.volumes.iscsi.secretRef`](#obj-specpodtemplatespecvolumesiscsisecretref)
            * [`fn withName(name)`](#fn-specpodtemplatespecvolumesiscsisecretrefwithname)
        * [`obj spec.podTemplate.spec.volumes.nfs`](#obj-specpodtemplatespecvolumesnfs)
          * [`fn withPath(path)`](#fn-specpodtemplatespecvolumesnfswithpath)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumesnfswithreadonly)
          * [`fn withServer(server)`](#fn-specpodtemplatespecvolumesnfswithserver)
        * [`obj spec.podTemplate.spec.volumes.persistentVolumeClaim`](#obj-specpodtemplatespecvolumespersistentvolumeclaim)
          * [`fn withClaimName(claimName)`](#fn-specpodtemplatespecvolumespersistentvolumeclaimwithclaimname)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumespersistentvolumeclaimwithreadonly)
        * [`obj spec.podTemplate.spec.volumes.photonPersistentDisk`](#obj-specpodtemplatespecvolumesphotonpersistentdisk)
          * [`fn withFsType(fsType)`](#fn-specpodtemplatespecvolumesphotonpersistentdiskwithfstype)
          * [`fn withPdID(pdID)`](#fn-specpodtemplatespecvolumesphotonpersistentdiskwithpdid)
        * [`obj spec.podTemplate.spec.volumes.portworxVolume`](#obj-specpodtemplatespecvolumesportworxvolume)
          * [`fn withFsType(fsType)`](#fn-specpodtemplatespecvolumesportworxvolumewithfstype)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumesportworxvolumewithreadonly)
          * [`fn withVolumeID(volumeID)`](#fn-specpodtemplatespecvolumesportworxvolumewithvolumeid)
        * [`obj spec.podTemplate.spec.volumes.projected`](#obj-specpodtemplatespecvolumesprojected)
          * [`fn withDefaultMode(defaultMode)`](#fn-specpodtemplatespecvolumesprojectedwithdefaultmode)
          * [`fn withSources(sources)`](#fn-specpodtemplatespecvolumesprojectedwithsources)
          * [`fn withSourcesMixin(sources)`](#fn-specpodtemplatespecvolumesprojectedwithsourcesmixin)
          * [`obj spec.podTemplate.spec.volumes.projected.sources`](#obj-specpodtemplatespecvolumesprojectedsources)
            * [`obj spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle`](#obj-specpodtemplatespecvolumesprojectedsourcesclustertrustbundle)
              * [`fn withName(name)`](#fn-specpodtemplatespecvolumesprojectedsourcesclustertrustbundlewithname)
              * [`fn withOptional(optional)`](#fn-specpodtemplatespecvolumesprojectedsourcesclustertrustbundlewithoptional)
              * [`fn withPath(path)`](#fn-specpodtemplatespecvolumesprojectedsourcesclustertrustbundlewithpath)
              * [`fn withSignerName(signerName)`](#fn-specpodtemplatespecvolumesprojectedsourcesclustertrustbundlewithsignername)
              * [`obj spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector`](#obj-specpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabelsmixin)
                * [`obj spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions`](#obj-specpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.podTemplate.spec.volumes.projected.sources.configMap`](#obj-specpodtemplatespecvolumesprojectedsourcesconfigmap)
              * [`fn withItems(items)`](#fn-specpodtemplatespecvolumesprojectedsourcesconfigmapwithitems)
              * [`fn withItemsMixin(items)`](#fn-specpodtemplatespecvolumesprojectedsourcesconfigmapwithitemsmixin)
              * [`fn withName(name)`](#fn-specpodtemplatespecvolumesprojectedsourcesconfigmapwithname)
              * [`fn withOptional(optional)`](#fn-specpodtemplatespecvolumesprojectedsourcesconfigmapwithoptional)
              * [`obj spec.podTemplate.spec.volumes.projected.sources.configMap.items`](#obj-specpodtemplatespecvolumesprojectedsourcesconfigmapitems)
                * [`fn withKey(key)`](#fn-specpodtemplatespecvolumesprojectedsourcesconfigmapitemswithkey)
                * [`fn withMode(mode)`](#fn-specpodtemplatespecvolumesprojectedsourcesconfigmapitemswithmode)
                * [`fn withPath(path)`](#fn-specpodtemplatespecvolumesprojectedsourcesconfigmapitemswithpath)
            * [`obj spec.podTemplate.spec.volumes.projected.sources.downwardAPI`](#obj-specpodtemplatespecvolumesprojectedsourcesdownwardapi)
              * [`fn withItems(items)`](#fn-specpodtemplatespecvolumesprojectedsourcesdownwardapiwithitems)
              * [`fn withItemsMixin(items)`](#fn-specpodtemplatespecvolumesprojectedsourcesdownwardapiwithitemsmixin)
              * [`obj spec.podTemplate.spec.volumes.projected.sources.downwardAPI.items`](#obj-specpodtemplatespecvolumesprojectedsourcesdownwardapiitems)
                * [`fn withMode(mode)`](#fn-specpodtemplatespecvolumesprojectedsourcesdownwardapiitemswithmode)
                * [`fn withPath(path)`](#fn-specpodtemplatespecvolumesprojectedsourcesdownwardapiitemswithpath)
                * [`obj spec.podTemplate.spec.volumes.projected.sources.downwardAPI.items.fieldRef`](#obj-specpodtemplatespecvolumesprojectedsourcesdownwardapiitemsfieldref)
                  * [`fn withApiVersion(apiVersion)`](#fn-specpodtemplatespecvolumesprojectedsourcesdownwardapiitemsfieldrefwithapiversion)
                  * [`fn withFieldPath(fieldPath)`](#fn-specpodtemplatespecvolumesprojectedsourcesdownwardapiitemsfieldrefwithfieldpath)
                * [`obj spec.podTemplate.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef`](#obj-specpodtemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldref)
                  * [`fn withContainerName(containerName)`](#fn-specpodtemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithcontainername)
                  * [`fn withDivisor(divisor)`](#fn-specpodtemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithdivisor)
                  * [`fn withResource(resource)`](#fn-specpodtemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithresource)
            * [`obj spec.podTemplate.spec.volumes.projected.sources.podCertificate`](#obj-specpodtemplatespecvolumesprojectedsourcespodcertificate)
              * [`fn withCertificateChainPath(certificateChainPath)`](#fn-specpodtemplatespecvolumesprojectedsourcespodcertificatewithcertificatechainpath)
              * [`fn withCredentialBundlePath(credentialBundlePath)`](#fn-specpodtemplatespecvolumesprojectedsourcespodcertificatewithcredentialbundlepath)
              * [`fn withKeyPath(keyPath)`](#fn-specpodtemplatespecvolumesprojectedsourcespodcertificatewithkeypath)
              * [`fn withKeyType(keyType)`](#fn-specpodtemplatespecvolumesprojectedsourcespodcertificatewithkeytype)
              * [`fn withMaxExpirationSeconds(maxExpirationSeconds)`](#fn-specpodtemplatespecvolumesprojectedsourcespodcertificatewithmaxexpirationseconds)
              * [`fn withSignerName(signerName)`](#fn-specpodtemplatespecvolumesprojectedsourcespodcertificatewithsignername)
            * [`obj spec.podTemplate.spec.volumes.projected.sources.secret`](#obj-specpodtemplatespecvolumesprojectedsourcessecret)
              * [`fn withItems(items)`](#fn-specpodtemplatespecvolumesprojectedsourcessecretwithitems)
              * [`fn withItemsMixin(items)`](#fn-specpodtemplatespecvolumesprojectedsourcessecretwithitemsmixin)
              * [`fn withName(name)`](#fn-specpodtemplatespecvolumesprojectedsourcessecretwithname)
              * [`fn withOptional(optional)`](#fn-specpodtemplatespecvolumesprojectedsourcessecretwithoptional)
              * [`obj spec.podTemplate.spec.volumes.projected.sources.secret.items`](#obj-specpodtemplatespecvolumesprojectedsourcessecretitems)
                * [`fn withKey(key)`](#fn-specpodtemplatespecvolumesprojectedsourcessecretitemswithkey)
                * [`fn withMode(mode)`](#fn-specpodtemplatespecvolumesprojectedsourcessecretitemswithmode)
                * [`fn withPath(path)`](#fn-specpodtemplatespecvolumesprojectedsourcessecretitemswithpath)
            * [`obj spec.podTemplate.spec.volumes.projected.sources.serviceAccountToken`](#obj-specpodtemplatespecvolumesprojectedsourcesserviceaccounttoken)
              * [`fn withAudience(audience)`](#fn-specpodtemplatespecvolumesprojectedsourcesserviceaccounttokenwithaudience)
              * [`fn withExpirationSeconds(expirationSeconds)`](#fn-specpodtemplatespecvolumesprojectedsourcesserviceaccounttokenwithexpirationseconds)
              * [`fn withPath(path)`](#fn-specpodtemplatespecvolumesprojectedsourcesserviceaccounttokenwithpath)
        * [`obj spec.podTemplate.spec.volumes.quobyte`](#obj-specpodtemplatespecvolumesquobyte)
          * [`fn withGroup(group)`](#fn-specpodtemplatespecvolumesquobytewithgroup)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumesquobytewithreadonly)
          * [`fn withRegistry(registry)`](#fn-specpodtemplatespecvolumesquobytewithregistry)
          * [`fn withTenant(tenant)`](#fn-specpodtemplatespecvolumesquobytewithtenant)
          * [`fn withUser(user)`](#fn-specpodtemplatespecvolumesquobytewithuser)
          * [`fn withVolume(volume)`](#fn-specpodtemplatespecvolumesquobytewithvolume)
        * [`obj spec.podTemplate.spec.volumes.rbd`](#obj-specpodtemplatespecvolumesrbd)
          * [`fn withFsType(fsType)`](#fn-specpodtemplatespecvolumesrbdwithfstype)
          * [`fn withImage(image)`](#fn-specpodtemplatespecvolumesrbdwithimage)
          * [`fn withKeyring(keyring)`](#fn-specpodtemplatespecvolumesrbdwithkeyring)
          * [`fn withMonitors(monitors)`](#fn-specpodtemplatespecvolumesrbdwithmonitors)
          * [`fn withMonitorsMixin(monitors)`](#fn-specpodtemplatespecvolumesrbdwithmonitorsmixin)
          * [`fn withPool(pool)`](#fn-specpodtemplatespecvolumesrbdwithpool)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumesrbdwithreadonly)
          * [`fn withUser(user)`](#fn-specpodtemplatespecvolumesrbdwithuser)
          * [`obj spec.podTemplate.spec.volumes.rbd.secretRef`](#obj-specpodtemplatespecvolumesrbdsecretref)
            * [`fn withName(name)`](#fn-specpodtemplatespecvolumesrbdsecretrefwithname)
        * [`obj spec.podTemplate.spec.volumes.scaleIO`](#obj-specpodtemplatespecvolumesscaleio)
          * [`fn withFsType(fsType)`](#fn-specpodtemplatespecvolumesscaleiowithfstype)
          * [`fn withGateway(gateway)`](#fn-specpodtemplatespecvolumesscaleiowithgateway)
          * [`fn withProtectionDomain(protectionDomain)`](#fn-specpodtemplatespecvolumesscaleiowithprotectiondomain)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumesscaleiowithreadonly)
          * [`fn withSslEnabled(sslEnabled)`](#fn-specpodtemplatespecvolumesscaleiowithsslenabled)
          * [`fn withStorageMode(storageMode)`](#fn-specpodtemplatespecvolumesscaleiowithstoragemode)
          * [`fn withStoragePool(storagePool)`](#fn-specpodtemplatespecvolumesscaleiowithstoragepool)
          * [`fn withSystem(system)`](#fn-specpodtemplatespecvolumesscaleiowithsystem)
          * [`fn withVolumeName(volumeName)`](#fn-specpodtemplatespecvolumesscaleiowithvolumename)
          * [`obj spec.podTemplate.spec.volumes.scaleIO.secretRef`](#obj-specpodtemplatespecvolumesscaleiosecretref)
            * [`fn withName(name)`](#fn-specpodtemplatespecvolumesscaleiosecretrefwithname)
        * [`obj spec.podTemplate.spec.volumes.secret`](#obj-specpodtemplatespecvolumessecret)
          * [`fn withDefaultMode(defaultMode)`](#fn-specpodtemplatespecvolumessecretwithdefaultmode)
          * [`fn withItems(items)`](#fn-specpodtemplatespecvolumessecretwithitems)
          * [`fn withItemsMixin(items)`](#fn-specpodtemplatespecvolumessecretwithitemsmixin)
          * [`fn withOptional(optional)`](#fn-specpodtemplatespecvolumessecretwithoptional)
          * [`fn withSecretName(secretName)`](#fn-specpodtemplatespecvolumessecretwithsecretname)
          * [`obj spec.podTemplate.spec.volumes.secret.items`](#obj-specpodtemplatespecvolumessecretitems)
            * [`fn withKey(key)`](#fn-specpodtemplatespecvolumessecretitemswithkey)
            * [`fn withMode(mode)`](#fn-specpodtemplatespecvolumessecretitemswithmode)
            * [`fn withPath(path)`](#fn-specpodtemplatespecvolumessecretitemswithpath)
        * [`obj spec.podTemplate.spec.volumes.storageos`](#obj-specpodtemplatespecvolumesstorageos)
          * [`fn withFsType(fsType)`](#fn-specpodtemplatespecvolumesstorageoswithfstype)
          * [`fn withReadOnly(readOnly)`](#fn-specpodtemplatespecvolumesstorageoswithreadonly)
          * [`fn withVolumeName(volumeName)`](#fn-specpodtemplatespecvolumesstorageoswithvolumename)
          * [`fn withVolumeNamespace(volumeNamespace)`](#fn-specpodtemplatespecvolumesstorageoswithvolumenamespace)
          * [`obj spec.podTemplate.spec.volumes.storageos.secretRef`](#obj-specpodtemplatespecvolumesstorageossecretref)
            * [`fn withName(name)`](#fn-specpodtemplatespecvolumesstorageossecretrefwithname)
        * [`obj spec.podTemplate.spec.volumes.vsphereVolume`](#obj-specpodtemplatespecvolumesvspherevolume)
          * [`fn withFsType(fsType)`](#fn-specpodtemplatespecvolumesvspherevolumewithfstype)
          * [`fn withStoragePolicyID(storagePolicyID)`](#fn-specpodtemplatespecvolumesvspherevolumewithstoragepolicyid)
          * [`fn withStoragePolicyName(storagePolicyName)`](#fn-specpodtemplatespecvolumesvspherevolumewithstoragepolicyname)
          * [`fn withVolumePath(volumePath)`](#fn-specpodtemplatespecvolumesvspherevolumewithvolumepath)
  * [`obj spec.resources`](#obj-specresources)
    * [`fn withClaims(claims)`](#fn-specresourceswithclaims)
    * [`fn withClaimsMixin(claims)`](#fn-specresourceswithclaimsmixin)
    * [`fn withLimits(limits)`](#fn-specresourceswithlimits)
    * [`fn withLimitsMixin(limits)`](#fn-specresourceswithlimitsmixin)
    * [`fn withRequests(requests)`](#fn-specresourceswithrequests)
    * [`fn withRequestsMixin(requests)`](#fn-specresourceswithrequestsmixin)
    * [`obj spec.resources.claims`](#obj-specresourcesclaims)
      * [`fn withName(name)`](#fn-specresourcesclaimswithname)
      * [`fn withRequest(request)`](#fn-specresourcesclaimswithrequest)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of PrivateLoadZone

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



### fn spec.withImage

```ts
withImage(image)
```



### fn spec.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.withToken

```ts
withToken(token)
```



## obj spec.config



### fn spec.config.withSecrets

```ts
withSecrets(secrets)
```



### fn spec.config.withSecretsMixin

```ts
withSecretsMixin(secrets)
```



**Note:** This function appends passed data to existing values

## obj spec.config.secrets



## obj spec.config.secrets.configMapRef



### fn spec.config.secrets.configMapRef.withName

```ts
withName(name)
```



### fn spec.config.secrets.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.config.secrets.secretRef



### fn spec.config.secrets.secretRef.withName

```ts
withName(name)
```



### fn spec.config.secrets.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.imagePullSecrets



### fn spec.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.podTemplate



### fn spec.podTemplate.withMetadata

```ts
withMetadata(metadata)
```



### fn spec.podTemplate.withMetadataMixin

```ts
withMetadataMixin(metadata)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec



### fn spec.podTemplate.spec.withActiveDeadlineSeconds

```ts
withActiveDeadlineSeconds(activeDeadlineSeconds)
```



### fn spec.podTemplate.spec.withAutomountServiceAccountToken

```ts
withAutomountServiceAccountToken(automountServiceAccountToken)
```



### fn spec.podTemplate.spec.withContainers

```ts
withContainers(containers)
```



### fn spec.podTemplate.spec.withContainersMixin

```ts
withContainersMixin(containers)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.withDnsPolicy

```ts
withDnsPolicy(dnsPolicy)
```



### fn spec.podTemplate.spec.withEnableServiceLinks

```ts
withEnableServiceLinks(enableServiceLinks)
```



### fn spec.podTemplate.spec.withEphemeralContainers

```ts
withEphemeralContainers(ephemeralContainers)
```



### fn spec.podTemplate.spec.withEphemeralContainersMixin

```ts
withEphemeralContainersMixin(ephemeralContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.withHostAliases

```ts
withHostAliases(hostAliases)
```



### fn spec.podTemplate.spec.withHostAliasesMixin

```ts
withHostAliasesMixin(hostAliases)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.withHostIPC

```ts
withHostIPC(hostIPC)
```



### fn spec.podTemplate.spec.withHostNetwork

```ts
withHostNetwork(hostNetwork)
```



### fn spec.podTemplate.spec.withHostPID

```ts
withHostPID(hostPID)
```



### fn spec.podTemplate.spec.withHostUsers

```ts
withHostUsers(hostUsers)
```



### fn spec.podTemplate.spec.withHostname

```ts
withHostname(hostname)
```



### fn spec.podTemplate.spec.withHostnameOverride

```ts
withHostnameOverride(hostnameOverride)
```



### fn spec.podTemplate.spec.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.podTemplate.spec.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.podTemplate.spec.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.withNodeName

```ts
withNodeName(nodeName)
```



### fn spec.podTemplate.spec.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.podTemplate.spec.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.withOverhead

```ts
withOverhead(overhead)
```



### fn spec.podTemplate.spec.withOverheadMixin

```ts
withOverheadMixin(overhead)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.withPreemptionPolicy

```ts
withPreemptionPolicy(preemptionPolicy)
```



### fn spec.podTemplate.spec.withPriority

```ts
withPriority(priority)
```



### fn spec.podTemplate.spec.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.podTemplate.spec.withReadinessGates

```ts
withReadinessGates(readinessGates)
```



### fn spec.podTemplate.spec.withReadinessGatesMixin

```ts
withReadinessGatesMixin(readinessGates)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.withResourceClaims

```ts
withResourceClaims(resourceClaims)
```



### fn spec.podTemplate.spec.withResourceClaimsMixin

```ts
withResourceClaimsMixin(resourceClaims)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



### fn spec.podTemplate.spec.withRuntimeClassName

```ts
withRuntimeClassName(runtimeClassName)
```



### fn spec.podTemplate.spec.withSchedulerName

```ts
withSchedulerName(schedulerName)
```



### fn spec.podTemplate.spec.withSchedulingGates

```ts
withSchedulingGates(schedulingGates)
```



### fn spec.podTemplate.spec.withSchedulingGatesMixin

```ts
withSchedulingGatesMixin(schedulingGates)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.withServiceAccount

```ts
withServiceAccount(serviceAccount)
```



### fn spec.podTemplate.spec.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.podTemplate.spec.withSetHostnameAsFQDN

```ts
withSetHostnameAsFQDN(setHostnameAsFQDN)
```



### fn spec.podTemplate.spec.withShareProcessNamespace

```ts
withShareProcessNamespace(shareProcessNamespace)
```



### fn spec.podTemplate.spec.withSubdomain

```ts
withSubdomain(subdomain)
```



### fn spec.podTemplate.spec.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.podTemplate.spec.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.podTemplate.spec.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.withTopologySpreadConstraints

```ts
withTopologySpreadConstraints(topologySpreadConstraints)
```



### fn spec.podTemplate.spec.withTopologySpreadConstraintsMixin

```ts
withTopologySpreadConstraintsMixin(topologySpreadConstraints)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.podTemplate.spec.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity



## obj spec.podTemplate.spec.affinity.nodeAffinity



### fn spec.podTemplate.spec.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAffinity



### fn spec.podTemplate.spec.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.podTemplate.spec.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.podTemplate.spec.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAntiAffinity



### fn spec.podTemplate.spec.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.containers



### fn spec.podTemplate.spec.containers.withArgs

```ts
withArgs(args)
```



### fn spec.podTemplate.spec.containers.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.containers.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.withEnv

```ts
withEnv(env)
```



### fn spec.podTemplate.spec.containers.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.podTemplate.spec.containers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.withImage

```ts
withImage(image)
```



### fn spec.podTemplate.spec.containers.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.podTemplate.spec.containers.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.containers.withPorts

```ts
withPorts(ports)
```



### fn spec.podTemplate.spec.containers.withPortsMixin

```ts
withPortsMixin(ports)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.withResizePolicy

```ts
withResizePolicy(resizePolicy)
```



### fn spec.podTemplate.spec.containers.withResizePolicyMixin

```ts
withResizePolicyMixin(resizePolicy)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



### fn spec.podTemplate.spec.containers.withRestartPolicyRules

```ts
withRestartPolicyRules(restartPolicyRules)
```



### fn spec.podTemplate.spec.containers.withRestartPolicyRulesMixin

```ts
withRestartPolicyRulesMixin(restartPolicyRules)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.withStdin

```ts
withStdin(stdin)
```



### fn spec.podTemplate.spec.containers.withStdinOnce

```ts
withStdinOnce(stdinOnce)
```



### fn spec.podTemplate.spec.containers.withTerminationMessagePath

```ts
withTerminationMessagePath(terminationMessagePath)
```



### fn spec.podTemplate.spec.containers.withTerminationMessagePolicy

```ts
withTerminationMessagePolicy(terminationMessagePolicy)
```



### fn spec.podTemplate.spec.containers.withTty

```ts
withTty(tty)
```



### fn spec.podTemplate.spec.containers.withVolumeDevices

```ts
withVolumeDevices(volumeDevices)
```



### fn spec.podTemplate.spec.containers.withVolumeDevicesMixin

```ts
withVolumeDevicesMixin(volumeDevices)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.podTemplate.spec.containers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.withWorkingDir

```ts
withWorkingDir(workingDir)
```



## obj spec.podTemplate.spec.containers.env



### fn spec.podTemplate.spec.containers.env.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.containers.env.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.containers.env.valueFrom



## obj spec.podTemplate.spec.containers.env.valueFrom.configMapKeyRef



### fn spec.podTemplate.spec.containers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.containers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.containers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.containers.env.valueFrom.fieldRef



### fn spec.podTemplate.spec.containers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.podTemplate.spec.containers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.podTemplate.spec.containers.env.valueFrom.fileKeyRef



### fn spec.podTemplate.spec.containers.env.valueFrom.fileKeyRef.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.containers.env.valueFrom.fileKeyRef.withOptional

```ts
withOptional(optional)
```



### fn spec.podTemplate.spec.containers.env.valueFrom.fileKeyRef.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.containers.env.valueFrom.fileKeyRef.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.podTemplate.spec.containers.env.valueFrom.resourceFieldRef



### fn spec.podTemplate.spec.containers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.podTemplate.spec.containers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.podTemplate.spec.containers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.podTemplate.spec.containers.env.valueFrom.secretKeyRef



### fn spec.podTemplate.spec.containers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.containers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.containers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.containers.envFrom



### fn spec.podTemplate.spec.containers.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.podTemplate.spec.containers.envFrom.configMapRef



### fn spec.podTemplate.spec.containers.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.containers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.containers.envFrom.secretRef



### fn spec.podTemplate.spec.containers.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.containers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.containers.lifecycle



### fn spec.podTemplate.spec.containers.lifecycle.withStopSignal

```ts
withStopSignal(stopSignal)
```



## obj spec.podTemplate.spec.containers.lifecycle.postStart



## obj spec.podTemplate.spec.containers.lifecycle.postStart.exec



### fn spec.podTemplate.spec.containers.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.containers.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.containers.lifecycle.postStart.httpGet



### fn spec.podTemplate.spec.containers.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.containers.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.containers.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.containers.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.containers.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.containers.lifecycle.postStart.httpGet.httpHeaders



### fn spec.podTemplate.spec.containers.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.containers.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.containers.lifecycle.postStart.sleep



### fn spec.podTemplate.spec.containers.lifecycle.postStart.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.podTemplate.spec.containers.lifecycle.postStart.tcpSocket



### fn spec.podTemplate.spec.containers.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.containers.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.containers.lifecycle.preStop



## obj spec.podTemplate.spec.containers.lifecycle.preStop.exec



### fn spec.podTemplate.spec.containers.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.containers.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.containers.lifecycle.preStop.httpGet



### fn spec.podTemplate.spec.containers.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.containers.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.containers.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.containers.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.containers.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.containers.lifecycle.preStop.httpGet.httpHeaders



### fn spec.podTemplate.spec.containers.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.containers.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.containers.lifecycle.preStop.sleep



### fn spec.podTemplate.spec.containers.lifecycle.preStop.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.podTemplate.spec.containers.lifecycle.preStop.tcpSocket



### fn spec.podTemplate.spec.containers.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.containers.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.containers.livenessProbe



### fn spec.podTemplate.spec.containers.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.podTemplate.spec.containers.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.podTemplate.spec.containers.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.podTemplate.spec.containers.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.podTemplate.spec.containers.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.podTemplate.spec.containers.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.podTemplate.spec.containers.livenessProbe.exec



### fn spec.podTemplate.spec.containers.livenessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.containers.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.containers.livenessProbe.grpc



### fn spec.podTemplate.spec.containers.livenessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.containers.livenessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.podTemplate.spec.containers.livenessProbe.httpGet



### fn spec.podTemplate.spec.containers.livenessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.containers.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.containers.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.livenessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.containers.livenessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.containers.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.containers.livenessProbe.httpGet.httpHeaders



### fn spec.podTemplate.spec.containers.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.containers.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.containers.livenessProbe.tcpSocket



### fn spec.podTemplate.spec.containers.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.containers.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.containers.ports



### fn spec.podTemplate.spec.containers.ports.withContainerPort

```ts
withContainerPort(containerPort)
```



### fn spec.podTemplate.spec.containers.ports.withHostIP

```ts
withHostIP(hostIP)
```



### fn spec.podTemplate.spec.containers.ports.withHostPort

```ts
withHostPort(hostPort)
```



### fn spec.podTemplate.spec.containers.ports.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.containers.ports.withProtocol

```ts
withProtocol(protocol)
```



## obj spec.podTemplate.spec.containers.readinessProbe



### fn spec.podTemplate.spec.containers.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.podTemplate.spec.containers.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.podTemplate.spec.containers.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.podTemplate.spec.containers.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.podTemplate.spec.containers.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.podTemplate.spec.containers.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.podTemplate.spec.containers.readinessProbe.exec



### fn spec.podTemplate.spec.containers.readinessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.containers.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.containers.readinessProbe.grpc



### fn spec.podTemplate.spec.containers.readinessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.containers.readinessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.podTemplate.spec.containers.readinessProbe.httpGet



### fn spec.podTemplate.spec.containers.readinessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.containers.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.containers.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.readinessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.containers.readinessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.containers.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.containers.readinessProbe.httpGet.httpHeaders



### fn spec.podTemplate.spec.containers.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.containers.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.containers.readinessProbe.tcpSocket



### fn spec.podTemplate.spec.containers.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.containers.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.containers.resizePolicy



### fn spec.podTemplate.spec.containers.resizePolicy.withResourceName

```ts
withResourceName(resourceName)
```



### fn spec.podTemplate.spec.containers.resizePolicy.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



## obj spec.podTemplate.spec.containers.resources



### fn spec.podTemplate.spec.containers.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.podTemplate.spec.containers.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.podTemplate.spec.containers.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.podTemplate.spec.containers.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.containers.resources.claims



### fn spec.podTemplate.spec.containers.resources.claims.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.containers.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.podTemplate.spec.containers.restartPolicyRules



### fn spec.podTemplate.spec.containers.restartPolicyRules.withAction

```ts
withAction(action)
```



## obj spec.podTemplate.spec.containers.restartPolicyRules.exitCodes



### fn spec.podTemplate.spec.containers.restartPolicyRules.exitCodes.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.containers.restartPolicyRules.exitCodes.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.containers.restartPolicyRules.exitCodes.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.containers.securityContext



### fn spec.podTemplate.spec.containers.securityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.podTemplate.spec.containers.securityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.podTemplate.spec.containers.securityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.podTemplate.spec.containers.securityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.podTemplate.spec.containers.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.podTemplate.spec.containers.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.podTemplate.spec.containers.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.podTemplate.spec.containers.securityContext.appArmorProfile



### fn spec.podTemplate.spec.containers.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.podTemplate.spec.containers.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.podTemplate.spec.containers.securityContext.capabilities



### fn spec.podTemplate.spec.containers.securityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.podTemplate.spec.containers.securityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.securityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.podTemplate.spec.containers.securityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.containers.securityContext.seLinuxOptions



### fn spec.podTemplate.spec.containers.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.podTemplate.spec.containers.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.podTemplate.spec.containers.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.podTemplate.spec.containers.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.podTemplate.spec.containers.securityContext.seccompProfile



### fn spec.podTemplate.spec.containers.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.podTemplate.spec.containers.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.podTemplate.spec.containers.securityContext.windowsOptions



### fn spec.podTemplate.spec.containers.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.podTemplate.spec.containers.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.podTemplate.spec.containers.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.podTemplate.spec.containers.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.podTemplate.spec.containers.startupProbe



### fn spec.podTemplate.spec.containers.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.podTemplate.spec.containers.startupProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.podTemplate.spec.containers.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.podTemplate.spec.containers.startupProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.podTemplate.spec.containers.startupProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.podTemplate.spec.containers.startupProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.podTemplate.spec.containers.startupProbe.exec



### fn spec.podTemplate.spec.containers.startupProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.containers.startupProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.containers.startupProbe.grpc



### fn spec.podTemplate.spec.containers.startupProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.containers.startupProbe.grpc.withService

```ts
withService(service)
```



## obj spec.podTemplate.spec.containers.startupProbe.httpGet



### fn spec.podTemplate.spec.containers.startupProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.containers.startupProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.containers.startupProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.containers.startupProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.containers.startupProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.containers.startupProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.containers.startupProbe.httpGet.httpHeaders



### fn spec.podTemplate.spec.containers.startupProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.containers.startupProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.containers.startupProbe.tcpSocket



### fn spec.podTemplate.spec.containers.startupProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.containers.startupProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.containers.volumeDevices



### fn spec.podTemplate.spec.containers.volumeDevices.withDevicePath

```ts
withDevicePath(devicePath)
```



### fn spec.podTemplate.spec.containers.volumeDevices.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.containers.volumeMounts



### fn spec.podTemplate.spec.containers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.podTemplate.spec.containers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.podTemplate.spec.containers.volumeMounts.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.containers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.containers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.podTemplate.spec.containers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.podTemplate.spec.containers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.podTemplate.spec.dnsConfig



### fn spec.podTemplate.spec.dnsConfig.withNameservers

```ts
withNameservers(nameservers)
```



### fn spec.podTemplate.spec.dnsConfig.withNameserversMixin

```ts
withNameserversMixin(nameservers)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.dnsConfig.withOptions

```ts
withOptions(options)
```



### fn spec.podTemplate.spec.dnsConfig.withOptionsMixin

```ts
withOptionsMixin(options)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.dnsConfig.withSearches

```ts
withSearches(searches)
```



### fn spec.podTemplate.spec.dnsConfig.withSearchesMixin

```ts
withSearchesMixin(searches)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.dnsConfig.options



### fn spec.podTemplate.spec.dnsConfig.options.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.dnsConfig.options.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.ephemeralContainers



### fn spec.podTemplate.spec.ephemeralContainers.withArgs

```ts
withArgs(args)
```



### fn spec.podTemplate.spec.ephemeralContainers.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.ephemeralContainers.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.withEnv

```ts
withEnv(env)
```



### fn spec.podTemplate.spec.ephemeralContainers.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.podTemplate.spec.ephemeralContainers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.withImage

```ts
withImage(image)
```



### fn spec.podTemplate.spec.ephemeralContainers.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.podTemplate.spec.ephemeralContainers.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.ephemeralContainers.withPorts

```ts
withPorts(ports)
```



### fn spec.podTemplate.spec.ephemeralContainers.withPortsMixin

```ts
withPortsMixin(ports)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.withResizePolicy

```ts
withResizePolicy(resizePolicy)
```



### fn spec.podTemplate.spec.ephemeralContainers.withResizePolicyMixin

```ts
withResizePolicyMixin(resizePolicy)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



### fn spec.podTemplate.spec.ephemeralContainers.withRestartPolicyRules

```ts
withRestartPolicyRules(restartPolicyRules)
```



### fn spec.podTemplate.spec.ephemeralContainers.withRestartPolicyRulesMixin

```ts
withRestartPolicyRulesMixin(restartPolicyRules)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.withStdin

```ts
withStdin(stdin)
```



### fn spec.podTemplate.spec.ephemeralContainers.withStdinOnce

```ts
withStdinOnce(stdinOnce)
```



### fn spec.podTemplate.spec.ephemeralContainers.withTargetContainerName

```ts
withTargetContainerName(targetContainerName)
```



### fn spec.podTemplate.spec.ephemeralContainers.withTerminationMessagePath

```ts
withTerminationMessagePath(terminationMessagePath)
```



### fn spec.podTemplate.spec.ephemeralContainers.withTerminationMessagePolicy

```ts
withTerminationMessagePolicy(terminationMessagePolicy)
```



### fn spec.podTemplate.spec.ephemeralContainers.withTty

```ts
withTty(tty)
```



### fn spec.podTemplate.spec.ephemeralContainers.withVolumeDevices

```ts
withVolumeDevices(volumeDevices)
```



### fn spec.podTemplate.spec.ephemeralContainers.withVolumeDevicesMixin

```ts
withVolumeDevicesMixin(volumeDevices)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.podTemplate.spec.ephemeralContainers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.withWorkingDir

```ts
withWorkingDir(workingDir)
```



## obj spec.podTemplate.spec.ephemeralContainers.env



### fn spec.podTemplate.spec.ephemeralContainers.env.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.ephemeralContainers.env.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.ephemeralContainers.env.valueFrom



## obj spec.podTemplate.spec.ephemeralContainers.env.valueFrom.configMapKeyRef



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.ephemeralContainers.env.valueFrom.fieldRef



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.podTemplate.spec.ephemeralContainers.env.valueFrom.fileKeyRef



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.fileKeyRef.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.fileKeyRef.withOptional

```ts
withOptional(optional)
```



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.fileKeyRef.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.fileKeyRef.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.podTemplate.spec.ephemeralContainers.env.valueFrom.resourceFieldRef



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.podTemplate.spec.ephemeralContainers.env.valueFrom.secretKeyRef



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.ephemeralContainers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.ephemeralContainers.envFrom



### fn spec.podTemplate.spec.ephemeralContainers.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.podTemplate.spec.ephemeralContainers.envFrom.configMapRef



### fn spec.podTemplate.spec.ephemeralContainers.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.ephemeralContainers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.ephemeralContainers.envFrom.secretRef



### fn spec.podTemplate.spec.ephemeralContainers.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.ephemeralContainers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.ephemeralContainers.lifecycle



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.withStopSignal

```ts
withStopSignal(stopSignal)
```



## obj spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart



## obj spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.exec



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.sleep



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.tcpSocket



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop



## obj spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.exec



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.sleep



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.tcpSocket



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.ephemeralContainers.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.ephemeralContainers.livenessProbe



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.podTemplate.spec.ephemeralContainers.livenessProbe.exec



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.ephemeralContainers.livenessProbe.grpc



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.ephemeralContainers.livenessProbe.tcpSocket



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.ephemeralContainers.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.ephemeralContainers.ports



### fn spec.podTemplate.spec.ephemeralContainers.ports.withContainerPort

```ts
withContainerPort(containerPort)
```



### fn spec.podTemplate.spec.ephemeralContainers.ports.withHostIP

```ts
withHostIP(hostIP)
```



### fn spec.podTemplate.spec.ephemeralContainers.ports.withHostPort

```ts
withHostPort(hostPort)
```



### fn spec.podTemplate.spec.ephemeralContainers.ports.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.ephemeralContainers.ports.withProtocol

```ts
withProtocol(protocol)
```



## obj spec.podTemplate.spec.ephemeralContainers.readinessProbe



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.podTemplate.spec.ephemeralContainers.readinessProbe.exec



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.ephemeralContainers.readinessProbe.grpc



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.ephemeralContainers.readinessProbe.tcpSocket



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.ephemeralContainers.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.ephemeralContainers.resizePolicy



### fn spec.podTemplate.spec.ephemeralContainers.resizePolicy.withResourceName

```ts
withResourceName(resourceName)
```



### fn spec.podTemplate.spec.ephemeralContainers.resizePolicy.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



## obj spec.podTemplate.spec.ephemeralContainers.resources



### fn spec.podTemplate.spec.ephemeralContainers.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.podTemplate.spec.ephemeralContainers.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.podTemplate.spec.ephemeralContainers.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.podTemplate.spec.ephemeralContainers.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.ephemeralContainers.resources.claims



### fn spec.podTemplate.spec.ephemeralContainers.resources.claims.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.ephemeralContainers.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.podTemplate.spec.ephemeralContainers.restartPolicyRules



### fn spec.podTemplate.spec.ephemeralContainers.restartPolicyRules.withAction

```ts
withAction(action)
```



## obj spec.podTemplate.spec.ephemeralContainers.restartPolicyRules.exitCodes



### fn spec.podTemplate.spec.ephemeralContainers.restartPolicyRules.exitCodes.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.ephemeralContainers.restartPolicyRules.exitCodes.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.ephemeralContainers.restartPolicyRules.exitCodes.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.ephemeralContainers.securityContext



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.podTemplate.spec.ephemeralContainers.securityContext.appArmorProfile



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.podTemplate.spec.ephemeralContainers.securityContext.capabilities



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.securityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.ephemeralContainers.securityContext.seLinuxOptions



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.podTemplate.spec.ephemeralContainers.securityContext.seccompProfile



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.podTemplate.spec.ephemeralContainers.securityContext.windowsOptions



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.podTemplate.spec.ephemeralContainers.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.podTemplate.spec.ephemeralContainers.startupProbe



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.podTemplate.spec.ephemeralContainers.startupProbe.exec



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.ephemeralContainers.startupProbe.grpc



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.grpc.withService

```ts
withService(service)
```



## obj spec.podTemplate.spec.ephemeralContainers.startupProbe.httpGet



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.ephemeralContainers.startupProbe.tcpSocket



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.ephemeralContainers.startupProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.ephemeralContainers.volumeDevices



### fn spec.podTemplate.spec.ephemeralContainers.volumeDevices.withDevicePath

```ts
withDevicePath(devicePath)
```



### fn spec.podTemplate.spec.ephemeralContainers.volumeDevices.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.ephemeralContainers.volumeMounts



### fn spec.podTemplate.spec.ephemeralContainers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.podTemplate.spec.ephemeralContainers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.podTemplate.spec.ephemeralContainers.volumeMounts.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.ephemeralContainers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.ephemeralContainers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.podTemplate.spec.ephemeralContainers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.podTemplate.spec.ephemeralContainers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.podTemplate.spec.hostAliases



### fn spec.podTemplate.spec.hostAliases.withHostnames

```ts
withHostnames(hostnames)
```



### fn spec.podTemplate.spec.hostAliases.withHostnamesMixin

```ts
withHostnamesMixin(hostnames)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.hostAliases.withIp

```ts
withIp(ip)
```



## obj spec.podTemplate.spec.imagePullSecrets



### fn spec.podTemplate.spec.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.initContainers



### fn spec.podTemplate.spec.initContainers.withArgs

```ts
withArgs(args)
```



### fn spec.podTemplate.spec.initContainers.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.initContainers.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.withEnv

```ts
withEnv(env)
```



### fn spec.podTemplate.spec.initContainers.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.podTemplate.spec.initContainers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.withImage

```ts
withImage(image)
```



### fn spec.podTemplate.spec.initContainers.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.podTemplate.spec.initContainers.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.initContainers.withPorts

```ts
withPorts(ports)
```



### fn spec.podTemplate.spec.initContainers.withPortsMixin

```ts
withPortsMixin(ports)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.withResizePolicy

```ts
withResizePolicy(resizePolicy)
```



### fn spec.podTemplate.spec.initContainers.withResizePolicyMixin

```ts
withResizePolicyMixin(resizePolicy)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



### fn spec.podTemplate.spec.initContainers.withRestartPolicyRules

```ts
withRestartPolicyRules(restartPolicyRules)
```



### fn spec.podTemplate.spec.initContainers.withRestartPolicyRulesMixin

```ts
withRestartPolicyRulesMixin(restartPolicyRules)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.withStdin

```ts
withStdin(stdin)
```



### fn spec.podTemplate.spec.initContainers.withStdinOnce

```ts
withStdinOnce(stdinOnce)
```



### fn spec.podTemplate.spec.initContainers.withTerminationMessagePath

```ts
withTerminationMessagePath(terminationMessagePath)
```



### fn spec.podTemplate.spec.initContainers.withTerminationMessagePolicy

```ts
withTerminationMessagePolicy(terminationMessagePolicy)
```



### fn spec.podTemplate.spec.initContainers.withTty

```ts
withTty(tty)
```



### fn spec.podTemplate.spec.initContainers.withVolumeDevices

```ts
withVolumeDevices(volumeDevices)
```



### fn spec.podTemplate.spec.initContainers.withVolumeDevicesMixin

```ts
withVolumeDevicesMixin(volumeDevices)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.podTemplate.spec.initContainers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.withWorkingDir

```ts
withWorkingDir(workingDir)
```



## obj spec.podTemplate.spec.initContainers.env



### fn spec.podTemplate.spec.initContainers.env.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.initContainers.env.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.initContainers.env.valueFrom



## obj spec.podTemplate.spec.initContainers.env.valueFrom.configMapKeyRef



### fn spec.podTemplate.spec.initContainers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.initContainers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.initContainers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.initContainers.env.valueFrom.fieldRef



### fn spec.podTemplate.spec.initContainers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.podTemplate.spec.initContainers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.podTemplate.spec.initContainers.env.valueFrom.fileKeyRef



### fn spec.podTemplate.spec.initContainers.env.valueFrom.fileKeyRef.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.initContainers.env.valueFrom.fileKeyRef.withOptional

```ts
withOptional(optional)
```



### fn spec.podTemplate.spec.initContainers.env.valueFrom.fileKeyRef.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.initContainers.env.valueFrom.fileKeyRef.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.podTemplate.spec.initContainers.env.valueFrom.resourceFieldRef



### fn spec.podTemplate.spec.initContainers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.podTemplate.spec.initContainers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.podTemplate.spec.initContainers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.podTemplate.spec.initContainers.env.valueFrom.secretKeyRef



### fn spec.podTemplate.spec.initContainers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.initContainers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.initContainers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.initContainers.envFrom



### fn spec.podTemplate.spec.initContainers.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.podTemplate.spec.initContainers.envFrom.configMapRef



### fn spec.podTemplate.spec.initContainers.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.initContainers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.initContainers.envFrom.secretRef



### fn spec.podTemplate.spec.initContainers.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.initContainers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.initContainers.lifecycle



### fn spec.podTemplate.spec.initContainers.lifecycle.withStopSignal

```ts
withStopSignal(stopSignal)
```



## obj spec.podTemplate.spec.initContainers.lifecycle.postStart



## obj spec.podTemplate.spec.initContainers.lifecycle.postStart.exec



### fn spec.podTemplate.spec.initContainers.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.initContainers.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.initContainers.lifecycle.postStart.httpGet



### fn spec.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders



### fn spec.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.initContainers.lifecycle.postStart.sleep



### fn spec.podTemplate.spec.initContainers.lifecycle.postStart.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.podTemplate.spec.initContainers.lifecycle.postStart.tcpSocket



### fn spec.podTemplate.spec.initContainers.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.initContainers.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.initContainers.lifecycle.preStop



## obj spec.podTemplate.spec.initContainers.lifecycle.preStop.exec



### fn spec.podTemplate.spec.initContainers.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.initContainers.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.initContainers.lifecycle.preStop.httpGet



### fn spec.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders



### fn spec.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.initContainers.lifecycle.preStop.sleep



### fn spec.podTemplate.spec.initContainers.lifecycle.preStop.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.podTemplate.spec.initContainers.lifecycle.preStop.tcpSocket



### fn spec.podTemplate.spec.initContainers.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.initContainers.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.initContainers.livenessProbe



### fn spec.podTemplate.spec.initContainers.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.podTemplate.spec.initContainers.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.podTemplate.spec.initContainers.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.podTemplate.spec.initContainers.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.podTemplate.spec.initContainers.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.podTemplate.spec.initContainers.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.podTemplate.spec.initContainers.livenessProbe.exec



### fn spec.podTemplate.spec.initContainers.livenessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.initContainers.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.initContainers.livenessProbe.grpc



### fn spec.podTemplate.spec.initContainers.livenessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.initContainers.livenessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.podTemplate.spec.initContainers.livenessProbe.httpGet



### fn spec.podTemplate.spec.initContainers.livenessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.initContainers.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.initContainers.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.livenessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.initContainers.livenessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.initContainers.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.initContainers.livenessProbe.httpGet.httpHeaders



### fn spec.podTemplate.spec.initContainers.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.initContainers.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.initContainers.livenessProbe.tcpSocket



### fn spec.podTemplate.spec.initContainers.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.initContainers.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.initContainers.ports



### fn spec.podTemplate.spec.initContainers.ports.withContainerPort

```ts
withContainerPort(containerPort)
```



### fn spec.podTemplate.spec.initContainers.ports.withHostIP

```ts
withHostIP(hostIP)
```



### fn spec.podTemplate.spec.initContainers.ports.withHostPort

```ts
withHostPort(hostPort)
```



### fn spec.podTemplate.spec.initContainers.ports.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.initContainers.ports.withProtocol

```ts
withProtocol(protocol)
```



## obj spec.podTemplate.spec.initContainers.readinessProbe



### fn spec.podTemplate.spec.initContainers.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.podTemplate.spec.initContainers.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.podTemplate.spec.initContainers.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.podTemplate.spec.initContainers.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.podTemplate.spec.initContainers.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.podTemplate.spec.initContainers.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.podTemplate.spec.initContainers.readinessProbe.exec



### fn spec.podTemplate.spec.initContainers.readinessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.initContainers.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.initContainers.readinessProbe.grpc



### fn spec.podTemplate.spec.initContainers.readinessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.initContainers.readinessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.podTemplate.spec.initContainers.readinessProbe.httpGet



### fn spec.podTemplate.spec.initContainers.readinessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.initContainers.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.initContainers.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.readinessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.initContainers.readinessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.initContainers.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.initContainers.readinessProbe.httpGet.httpHeaders



### fn spec.podTemplate.spec.initContainers.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.initContainers.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.initContainers.readinessProbe.tcpSocket



### fn spec.podTemplate.spec.initContainers.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.initContainers.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.initContainers.resizePolicy



### fn spec.podTemplate.spec.initContainers.resizePolicy.withResourceName

```ts
withResourceName(resourceName)
```



### fn spec.podTemplate.spec.initContainers.resizePolicy.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



## obj spec.podTemplate.spec.initContainers.resources



### fn spec.podTemplate.spec.initContainers.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.podTemplate.spec.initContainers.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.podTemplate.spec.initContainers.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.podTemplate.spec.initContainers.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.initContainers.resources.claims



### fn spec.podTemplate.spec.initContainers.resources.claims.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.initContainers.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.podTemplate.spec.initContainers.restartPolicyRules



### fn spec.podTemplate.spec.initContainers.restartPolicyRules.withAction

```ts
withAction(action)
```



## obj spec.podTemplate.spec.initContainers.restartPolicyRules.exitCodes



### fn spec.podTemplate.spec.initContainers.restartPolicyRules.exitCodes.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.initContainers.restartPolicyRules.exitCodes.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.initContainers.restartPolicyRules.exitCodes.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.initContainers.securityContext



### fn spec.podTemplate.spec.initContainers.securityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.podTemplate.spec.initContainers.securityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.podTemplate.spec.initContainers.securityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.podTemplate.spec.initContainers.securityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.podTemplate.spec.initContainers.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.podTemplate.spec.initContainers.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.podTemplate.spec.initContainers.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.podTemplate.spec.initContainers.securityContext.appArmorProfile



### fn spec.podTemplate.spec.initContainers.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.podTemplate.spec.initContainers.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.podTemplate.spec.initContainers.securityContext.capabilities



### fn spec.podTemplate.spec.initContainers.securityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.podTemplate.spec.initContainers.securityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.securityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.podTemplate.spec.initContainers.securityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.initContainers.securityContext.seLinuxOptions



### fn spec.podTemplate.spec.initContainers.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.podTemplate.spec.initContainers.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.podTemplate.spec.initContainers.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.podTemplate.spec.initContainers.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.podTemplate.spec.initContainers.securityContext.seccompProfile



### fn spec.podTemplate.spec.initContainers.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.podTemplate.spec.initContainers.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.podTemplate.spec.initContainers.securityContext.windowsOptions



### fn spec.podTemplate.spec.initContainers.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.podTemplate.spec.initContainers.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.podTemplate.spec.initContainers.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.podTemplate.spec.initContainers.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.podTemplate.spec.initContainers.startupProbe



### fn spec.podTemplate.spec.initContainers.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.podTemplate.spec.initContainers.startupProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.podTemplate.spec.initContainers.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.podTemplate.spec.initContainers.startupProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.podTemplate.spec.initContainers.startupProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.podTemplate.spec.initContainers.startupProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.podTemplate.spec.initContainers.startupProbe.exec



### fn spec.podTemplate.spec.initContainers.startupProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.podTemplate.spec.initContainers.startupProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.initContainers.startupProbe.grpc



### fn spec.podTemplate.spec.initContainers.startupProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.initContainers.startupProbe.grpc.withService

```ts
withService(service)
```



## obj spec.podTemplate.spec.initContainers.startupProbe.httpGet



### fn spec.podTemplate.spec.initContainers.startupProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.initContainers.startupProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.podTemplate.spec.initContainers.startupProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.initContainers.startupProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.initContainers.startupProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.podTemplate.spec.initContainers.startupProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.podTemplate.spec.initContainers.startupProbe.httpGet.httpHeaders



### fn spec.podTemplate.spec.initContainers.startupProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.initContainers.startupProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.initContainers.startupProbe.tcpSocket



### fn spec.podTemplate.spec.initContainers.startupProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.podTemplate.spec.initContainers.startupProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.podTemplate.spec.initContainers.volumeDevices



### fn spec.podTemplate.spec.initContainers.volumeDevices.withDevicePath

```ts
withDevicePath(devicePath)
```



### fn spec.podTemplate.spec.initContainers.volumeDevices.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.initContainers.volumeMounts



### fn spec.podTemplate.spec.initContainers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.podTemplate.spec.initContainers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.podTemplate.spec.initContainers.volumeMounts.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.initContainers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.initContainers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.podTemplate.spec.initContainers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.podTemplate.spec.initContainers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.podTemplate.spec.os



### fn spec.podTemplate.spec.os.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.readinessGates



### fn spec.podTemplate.spec.readinessGates.withConditionType

```ts
withConditionType(conditionType)
```



## obj spec.podTemplate.spec.resourceClaims



### fn spec.podTemplate.spec.resourceClaims.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.resourceClaims.withResourceClaimName

```ts
withResourceClaimName(resourceClaimName)
```



### fn spec.podTemplate.spec.resourceClaims.withResourceClaimTemplateName

```ts
withResourceClaimTemplateName(resourceClaimTemplateName)
```



## obj spec.podTemplate.spec.resources



### fn spec.podTemplate.spec.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.podTemplate.spec.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.podTemplate.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.podTemplate.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.resources.claims



### fn spec.podTemplate.spec.resources.claims.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.podTemplate.spec.schedulingGates



### fn spec.podTemplate.spec.schedulingGates.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.securityContext



### fn spec.podTemplate.spec.securityContext.withFsGroup

```ts
withFsGroup(fsGroup)
```



### fn spec.podTemplate.spec.securityContext.withFsGroupChangePolicy

```ts
withFsGroupChangePolicy(fsGroupChangePolicy)
```



### fn spec.podTemplate.spec.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.podTemplate.spec.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.podTemplate.spec.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



### fn spec.podTemplate.spec.securityContext.withSeLinuxChangePolicy

```ts
withSeLinuxChangePolicy(seLinuxChangePolicy)
```



### fn spec.podTemplate.spec.securityContext.withSupplementalGroups

```ts
withSupplementalGroups(supplementalGroups)
```



### fn spec.podTemplate.spec.securityContext.withSupplementalGroupsMixin

```ts
withSupplementalGroupsMixin(supplementalGroups)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.securityContext.withSupplementalGroupsPolicy

```ts
withSupplementalGroupsPolicy(supplementalGroupsPolicy)
```



### fn spec.podTemplate.spec.securityContext.withSysctls

```ts
withSysctls(sysctls)
```



### fn spec.podTemplate.spec.securityContext.withSysctlsMixin

```ts
withSysctlsMixin(sysctls)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.securityContext.appArmorProfile



### fn spec.podTemplate.spec.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.podTemplate.spec.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.podTemplate.spec.securityContext.seLinuxOptions



### fn spec.podTemplate.spec.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.podTemplate.spec.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.podTemplate.spec.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.podTemplate.spec.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.podTemplate.spec.securityContext.seccompProfile



### fn spec.podTemplate.spec.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.podTemplate.spec.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.podTemplate.spec.securityContext.sysctls



### fn spec.podTemplate.spec.securityContext.sysctls.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.securityContext.sysctls.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.securityContext.windowsOptions



### fn spec.podTemplate.spec.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.podTemplate.spec.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.podTemplate.spec.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.podTemplate.spec.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.podTemplate.spec.tolerations



### fn spec.podTemplate.spec.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.podTemplate.spec.tolerations.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.podTemplate.spec.tolerations.withValue

```ts
withValue(value)
```



## obj spec.podTemplate.spec.topologySpreadConstraints



### fn spec.podTemplate.spec.topologySpreadConstraints.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.podTemplate.spec.topologySpreadConstraints.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.topologySpreadConstraints.withMaxSkew

```ts
withMaxSkew(maxSkew)
```



### fn spec.podTemplate.spec.topologySpreadConstraints.withMinDomains

```ts
withMinDomains(minDomains)
```



### fn spec.podTemplate.spec.topologySpreadConstraints.withNodeAffinityPolicy

```ts
withNodeAffinityPolicy(nodeAffinityPolicy)
```



### fn spec.podTemplate.spec.topologySpreadConstraints.withNodeTaintsPolicy

```ts
withNodeTaintsPolicy(nodeTaintsPolicy)
```



### fn spec.podTemplate.spec.topologySpreadConstraints.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



### fn spec.podTemplate.spec.topologySpreadConstraints.withWhenUnsatisfiable

```ts
withWhenUnsatisfiable(whenUnsatisfiable)
```



## obj spec.podTemplate.spec.topologySpreadConstraints.labelSelector



### fn spec.podTemplate.spec.topologySpreadConstraints.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.podTemplate.spec.topologySpreadConstraints.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.topologySpreadConstraints.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.podTemplate.spec.topologySpreadConstraints.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.topologySpreadConstraints.labelSelector.matchExpressions



### fn spec.podTemplate.spec.topologySpreadConstraints.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.topologySpreadConstraints.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.topologySpreadConstraints.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.topologySpreadConstraints.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.volumes



### fn spec.podTemplate.spec.volumes.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.volumes.awsElasticBlockStore



### fn spec.podTemplate.spec.volumes.awsElasticBlockStore.withFsType

```ts
withFsType(fsType)
```



### fn spec.podTemplate.spec.volumes.awsElasticBlockStore.withPartition

```ts
withPartition(partition)
```



### fn spec.podTemplate.spec.volumes.awsElasticBlockStore.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.volumes.awsElasticBlockStore.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.podTemplate.spec.volumes.azureDisk



### fn spec.podTemplate.spec.volumes.azureDisk.withCachingMode

```ts
withCachingMode(cachingMode)
```



### fn spec.podTemplate.spec.volumes.azureDisk.withDiskName

```ts
withDiskName(diskName)
```



### fn spec.podTemplate.spec.volumes.azureDisk.withDiskURI

```ts
withDiskURI(diskURI)
```



### fn spec.podTemplate.spec.volumes.azureDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.podTemplate.spec.volumes.azureDisk.withKind

```ts
withKind(kind)
```



### fn spec.podTemplate.spec.volumes.azureDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.podTemplate.spec.volumes.azureFile



### fn spec.podTemplate.spec.volumes.azureFile.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.volumes.azureFile.withSecretName

```ts
withSecretName(secretName)
```



### fn spec.podTemplate.spec.volumes.azureFile.withShareName

```ts
withShareName(shareName)
```



## obj spec.podTemplate.spec.volumes.cephfs



### fn spec.podTemplate.spec.volumes.cephfs.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.podTemplate.spec.volumes.cephfs.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.volumes.cephfs.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.volumes.cephfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.volumes.cephfs.withSecretFile

```ts
withSecretFile(secretFile)
```



### fn spec.podTemplate.spec.volumes.cephfs.withUser

```ts
withUser(user)
```



## obj spec.podTemplate.spec.volumes.cephfs.secretRef



### fn spec.podTemplate.spec.volumes.cephfs.secretRef.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.volumes.cinder



### fn spec.podTemplate.spec.volumes.cinder.withFsType

```ts
withFsType(fsType)
```



### fn spec.podTemplate.spec.volumes.cinder.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.volumes.cinder.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.podTemplate.spec.volumes.cinder.secretRef



### fn spec.podTemplate.spec.volumes.cinder.secretRef.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.volumes.configMap



### fn spec.podTemplate.spec.volumes.configMap.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.podTemplate.spec.volumes.configMap.withItems

```ts
withItems(items)
```



### fn spec.podTemplate.spec.volumes.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.volumes.configMap.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.volumes.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.volumes.configMap.items



### fn spec.podTemplate.spec.volumes.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.volumes.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.podTemplate.spec.volumes.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.podTemplate.spec.volumes.csi



### fn spec.podTemplate.spec.volumes.csi.withDriver

```ts
withDriver(driver)
```



### fn spec.podTemplate.spec.volumes.csi.withFsType

```ts
withFsType(fsType)
```



### fn spec.podTemplate.spec.volumes.csi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.volumes.csi.withVolumeAttributes

```ts
withVolumeAttributes(volumeAttributes)
```



### fn spec.podTemplate.spec.volumes.csi.withVolumeAttributesMixin

```ts
withVolumeAttributesMixin(volumeAttributes)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.volumes.csi.nodePublishSecretRef



### fn spec.podTemplate.spec.volumes.csi.nodePublishSecretRef.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.volumes.downwardAPI



### fn spec.podTemplate.spec.volumes.downwardAPI.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.podTemplate.spec.volumes.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.podTemplate.spec.volumes.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.volumes.downwardAPI.items



### fn spec.podTemplate.spec.volumes.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.podTemplate.spec.volumes.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.podTemplate.spec.volumes.downwardAPI.items.fieldRef



### fn spec.podTemplate.spec.volumes.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.podTemplate.spec.volumes.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.podTemplate.spec.volumes.downwardAPI.items.resourceFieldRef



### fn spec.podTemplate.spec.volumes.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.podTemplate.spec.volumes.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.podTemplate.spec.volumes.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.podTemplate.spec.volumes.emptyDir



### fn spec.podTemplate.spec.volumes.emptyDir.withMedium

```ts
withMedium(medium)
```



### fn spec.podTemplate.spec.volumes.emptyDir.withSizeLimit

```ts
withSizeLimit(sizeLimit)
```



## obj spec.podTemplate.spec.volumes.ephemeral



## obj spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.withMetadata

```ts
withMetadata(metadata)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.withMetadataMixin

```ts
withMetadataMixin(metadata)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModes

```ts
withAccessModes(accessModes)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModesMixin

```ts
withAccessModesMixin(accessModes)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.withStorageClassName

```ts
withStorageClassName(storageClassName)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeAttributesClassName

```ts
withVolumeAttributesClassName(volumeAttributesClassName)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeMode

```ts
withVolumeMode(volumeMode)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withKind

```ts
withKind(kind)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withKind

```ts
withKind(kind)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.volumes.fc



### fn spec.podTemplate.spec.volumes.fc.withFsType

```ts
withFsType(fsType)
```



### fn spec.podTemplate.spec.volumes.fc.withLun

```ts
withLun(lun)
```



### fn spec.podTemplate.spec.volumes.fc.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.volumes.fc.withTargetWWNs

```ts
withTargetWWNs(targetWWNs)
```



### fn spec.podTemplate.spec.volumes.fc.withTargetWWNsMixin

```ts
withTargetWWNsMixin(targetWWNs)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.volumes.fc.withWwids

```ts
withWwids(wwids)
```



### fn spec.podTemplate.spec.volumes.fc.withWwidsMixin

```ts
withWwidsMixin(wwids)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.volumes.flexVolume



### fn spec.podTemplate.spec.volumes.flexVolume.withDriver

```ts
withDriver(driver)
```



### fn spec.podTemplate.spec.volumes.flexVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.podTemplate.spec.volumes.flexVolume.withOptions

```ts
withOptions(options)
```



### fn spec.podTemplate.spec.volumes.flexVolume.withOptionsMixin

```ts
withOptionsMixin(options)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.volumes.flexVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.podTemplate.spec.volumes.flexVolume.secretRef



### fn spec.podTemplate.spec.volumes.flexVolume.secretRef.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.volumes.flocker



### fn spec.podTemplate.spec.volumes.flocker.withDatasetName

```ts
withDatasetName(datasetName)
```



### fn spec.podTemplate.spec.volumes.flocker.withDatasetUUID

```ts
withDatasetUUID(datasetUUID)
```



## obj spec.podTemplate.spec.volumes.gcePersistentDisk



### fn spec.podTemplate.spec.volumes.gcePersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.podTemplate.spec.volumes.gcePersistentDisk.withPartition

```ts
withPartition(partition)
```



### fn spec.podTemplate.spec.volumes.gcePersistentDisk.withPdName

```ts
withPdName(pdName)
```



### fn spec.podTemplate.spec.volumes.gcePersistentDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.podTemplate.spec.volumes.gitRepo



### fn spec.podTemplate.spec.volumes.gitRepo.withDirectory

```ts
withDirectory(directory)
```



### fn spec.podTemplate.spec.volumes.gitRepo.withRepository

```ts
withRepository(repository)
```



### fn spec.podTemplate.spec.volumes.gitRepo.withRevision

```ts
withRevision(revision)
```



## obj spec.podTemplate.spec.volumes.glusterfs



### fn spec.podTemplate.spec.volumes.glusterfs.withEndpoints

```ts
withEndpoints(endpoints)
```



### fn spec.podTemplate.spec.volumes.glusterfs.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.volumes.glusterfs.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.podTemplate.spec.volumes.hostPath



### fn spec.podTemplate.spec.volumes.hostPath.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.volumes.hostPath.withType

```ts
withType(type)
```



## obj spec.podTemplate.spec.volumes.image



### fn spec.podTemplate.spec.volumes.image.withPullPolicy

```ts
withPullPolicy(pullPolicy)
```



### fn spec.podTemplate.spec.volumes.image.withReference

```ts
withReference(reference)
```



## obj spec.podTemplate.spec.volumes.iscsi



### fn spec.podTemplate.spec.volumes.iscsi.withChapAuthDiscovery

```ts
withChapAuthDiscovery(chapAuthDiscovery)
```



### fn spec.podTemplate.spec.volumes.iscsi.withChapAuthSession

```ts
withChapAuthSession(chapAuthSession)
```



### fn spec.podTemplate.spec.volumes.iscsi.withFsType

```ts
withFsType(fsType)
```



### fn spec.podTemplate.spec.volumes.iscsi.withInitiatorName

```ts
withInitiatorName(initiatorName)
```



### fn spec.podTemplate.spec.volumes.iscsi.withIqn

```ts
withIqn(iqn)
```



### fn spec.podTemplate.spec.volumes.iscsi.withIscsiInterface

```ts
withIscsiInterface(iscsiInterface)
```



### fn spec.podTemplate.spec.volumes.iscsi.withLun

```ts
withLun(lun)
```



### fn spec.podTemplate.spec.volumes.iscsi.withPortals

```ts
withPortals(portals)
```



### fn spec.podTemplate.spec.volumes.iscsi.withPortalsMixin

```ts
withPortalsMixin(portals)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.volumes.iscsi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.volumes.iscsi.withTargetPortal

```ts
withTargetPortal(targetPortal)
```



## obj spec.podTemplate.spec.volumes.iscsi.secretRef



### fn spec.podTemplate.spec.volumes.iscsi.secretRef.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.volumes.nfs



### fn spec.podTemplate.spec.volumes.nfs.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.volumes.nfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.volumes.nfs.withServer

```ts
withServer(server)
```



## obj spec.podTemplate.spec.volumes.persistentVolumeClaim



### fn spec.podTemplate.spec.volumes.persistentVolumeClaim.withClaimName

```ts
withClaimName(claimName)
```



### fn spec.podTemplate.spec.volumes.persistentVolumeClaim.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.podTemplate.spec.volumes.photonPersistentDisk



### fn spec.podTemplate.spec.volumes.photonPersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.podTemplate.spec.volumes.photonPersistentDisk.withPdID

```ts
withPdID(pdID)
```



## obj spec.podTemplate.spec.volumes.portworxVolume



### fn spec.podTemplate.spec.volumes.portworxVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.podTemplate.spec.volumes.portworxVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.volumes.portworxVolume.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.podTemplate.spec.volumes.projected



### fn spec.podTemplate.spec.volumes.projected.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.podTemplate.spec.volumes.projected.withSources

```ts
withSources(sources)
```



### fn spec.podTemplate.spec.volumes.projected.withSourcesMixin

```ts
withSourcesMixin(sources)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.volumes.projected.sources



## obj spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle



### fn spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.withOptional

```ts
withOptional(optional)
```



### fn spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.withPath

```ts
withPath(path)
```



### fn spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.withSignerName

```ts
withSignerName(signerName)
```



## obj spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector



### fn spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions



### fn spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.volumes.projected.sources.configMap



### fn spec.podTemplate.spec.volumes.projected.sources.configMap.withItems

```ts
withItems(items)
```



### fn spec.podTemplate.spec.volumes.projected.sources.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.volumes.projected.sources.configMap.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.volumes.projected.sources.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.volumes.projected.sources.configMap.items



### fn spec.podTemplate.spec.volumes.projected.sources.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.volumes.projected.sources.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.podTemplate.spec.volumes.projected.sources.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.podTemplate.spec.volumes.projected.sources.downwardAPI



### fn spec.podTemplate.spec.volumes.projected.sources.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.podTemplate.spec.volumes.projected.sources.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.podTemplate.spec.volumes.projected.sources.downwardAPI.items



### fn spec.podTemplate.spec.volumes.projected.sources.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.podTemplate.spec.volumes.projected.sources.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.podTemplate.spec.volumes.projected.sources.downwardAPI.items.fieldRef



### fn spec.podTemplate.spec.volumes.projected.sources.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.podTemplate.spec.volumes.projected.sources.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.podTemplate.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef



### fn spec.podTemplate.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.podTemplate.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.podTemplate.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.podTemplate.spec.volumes.projected.sources.podCertificate



### fn spec.podTemplate.spec.volumes.projected.sources.podCertificate.withCertificateChainPath

```ts
withCertificateChainPath(certificateChainPath)
```



### fn spec.podTemplate.spec.volumes.projected.sources.podCertificate.withCredentialBundlePath

```ts
withCredentialBundlePath(credentialBundlePath)
```



### fn spec.podTemplate.spec.volumes.projected.sources.podCertificate.withKeyPath

```ts
withKeyPath(keyPath)
```



### fn spec.podTemplate.spec.volumes.projected.sources.podCertificate.withKeyType

```ts
withKeyType(keyType)
```



### fn spec.podTemplate.spec.volumes.projected.sources.podCertificate.withMaxExpirationSeconds

```ts
withMaxExpirationSeconds(maxExpirationSeconds)
```



### fn spec.podTemplate.spec.volumes.projected.sources.podCertificate.withSignerName

```ts
withSignerName(signerName)
```



## obj spec.podTemplate.spec.volumes.projected.sources.secret



### fn spec.podTemplate.spec.volumes.projected.sources.secret.withItems

```ts
withItems(items)
```



### fn spec.podTemplate.spec.volumes.projected.sources.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.volumes.projected.sources.secret.withName

```ts
withName(name)
```



### fn spec.podTemplate.spec.volumes.projected.sources.secret.withOptional

```ts
withOptional(optional)
```



## obj spec.podTemplate.spec.volumes.projected.sources.secret.items



### fn spec.podTemplate.spec.volumes.projected.sources.secret.items.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.volumes.projected.sources.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.podTemplate.spec.volumes.projected.sources.secret.items.withPath

```ts
withPath(path)
```



## obj spec.podTemplate.spec.volumes.projected.sources.serviceAccountToken



### fn spec.podTemplate.spec.volumes.projected.sources.serviceAccountToken.withAudience

```ts
withAudience(audience)
```



### fn spec.podTemplate.spec.volumes.projected.sources.serviceAccountToken.withExpirationSeconds

```ts
withExpirationSeconds(expirationSeconds)
```



### fn spec.podTemplate.spec.volumes.projected.sources.serviceAccountToken.withPath

```ts
withPath(path)
```



## obj spec.podTemplate.spec.volumes.quobyte



### fn spec.podTemplate.spec.volumes.quobyte.withGroup

```ts
withGroup(group)
```



### fn spec.podTemplate.spec.volumes.quobyte.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.volumes.quobyte.withRegistry

```ts
withRegistry(registry)
```



### fn spec.podTemplate.spec.volumes.quobyte.withTenant

```ts
withTenant(tenant)
```



### fn spec.podTemplate.spec.volumes.quobyte.withUser

```ts
withUser(user)
```



### fn spec.podTemplate.spec.volumes.quobyte.withVolume

```ts
withVolume(volume)
```



## obj spec.podTemplate.spec.volumes.rbd



### fn spec.podTemplate.spec.volumes.rbd.withFsType

```ts
withFsType(fsType)
```



### fn spec.podTemplate.spec.volumes.rbd.withImage

```ts
withImage(image)
```



### fn spec.podTemplate.spec.volumes.rbd.withKeyring

```ts
withKeyring(keyring)
```



### fn spec.podTemplate.spec.volumes.rbd.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.podTemplate.spec.volumes.rbd.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.volumes.rbd.withPool

```ts
withPool(pool)
```



### fn spec.podTemplate.spec.volumes.rbd.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.volumes.rbd.withUser

```ts
withUser(user)
```



## obj spec.podTemplate.spec.volumes.rbd.secretRef



### fn spec.podTemplate.spec.volumes.rbd.secretRef.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.volumes.scaleIO



### fn spec.podTemplate.spec.volumes.scaleIO.withFsType

```ts
withFsType(fsType)
```



### fn spec.podTemplate.spec.volumes.scaleIO.withGateway

```ts
withGateway(gateway)
```



### fn spec.podTemplate.spec.volumes.scaleIO.withProtectionDomain

```ts
withProtectionDomain(protectionDomain)
```



### fn spec.podTemplate.spec.volumes.scaleIO.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.volumes.scaleIO.withSslEnabled

```ts
withSslEnabled(sslEnabled)
```



### fn spec.podTemplate.spec.volumes.scaleIO.withStorageMode

```ts
withStorageMode(storageMode)
```



### fn spec.podTemplate.spec.volumes.scaleIO.withStoragePool

```ts
withStoragePool(storagePool)
```



### fn spec.podTemplate.spec.volumes.scaleIO.withSystem

```ts
withSystem(system)
```



### fn spec.podTemplate.spec.volumes.scaleIO.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.podTemplate.spec.volumes.scaleIO.secretRef



### fn spec.podTemplate.spec.volumes.scaleIO.secretRef.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.volumes.secret



### fn spec.podTemplate.spec.volumes.secret.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.podTemplate.spec.volumes.secret.withItems

```ts
withItems(items)
```



### fn spec.podTemplate.spec.volumes.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.podTemplate.spec.volumes.secret.withOptional

```ts
withOptional(optional)
```



### fn spec.podTemplate.spec.volumes.secret.withSecretName

```ts
withSecretName(secretName)
```



## obj spec.podTemplate.spec.volumes.secret.items



### fn spec.podTemplate.spec.volumes.secret.items.withKey

```ts
withKey(key)
```



### fn spec.podTemplate.spec.volumes.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.podTemplate.spec.volumes.secret.items.withPath

```ts
withPath(path)
```



## obj spec.podTemplate.spec.volumes.storageos



### fn spec.podTemplate.spec.volumes.storageos.withFsType

```ts
withFsType(fsType)
```



### fn spec.podTemplate.spec.volumes.storageos.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.podTemplate.spec.volumes.storageos.withVolumeName

```ts
withVolumeName(volumeName)
```



### fn spec.podTemplate.spec.volumes.storageos.withVolumeNamespace

```ts
withVolumeNamespace(volumeNamespace)
```



## obj spec.podTemplate.spec.volumes.storageos.secretRef



### fn spec.podTemplate.spec.volumes.storageos.secretRef.withName

```ts
withName(name)
```



## obj spec.podTemplate.spec.volumes.vsphereVolume



### fn spec.podTemplate.spec.volumes.vsphereVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.podTemplate.spec.volumes.vsphereVolume.withStoragePolicyID

```ts
withStoragePolicyID(storagePolicyID)
```



### fn spec.podTemplate.spec.volumes.vsphereVolume.withStoragePolicyName

```ts
withStoragePolicyName(storagePolicyName)
```



### fn spec.podTemplate.spec.volumes.vsphereVolume.withVolumePath

```ts
withVolumePath(volumePath)
```



## obj spec.resources



### fn spec.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.resources.claims



### fn spec.resources.claims.withName

```ts
withName(name)
```



### fn spec.resources.claims.withRequest

```ts
withRequest(request)
```

