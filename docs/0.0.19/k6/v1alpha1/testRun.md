---
permalink: /0.0.19/k6/v1alpha1/testRun/
---

# k6.v1alpha1.testRun



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
  * [`fn withArguments(arguments)`](#fn-specwitharguments)
  * [`fn withCleanup(cleanup)`](#fn-specwithcleanup)
  * [`fn withParallelism(parallelism)`](#fn-specwithparallelism)
  * [`fn withPaused(paused)`](#fn-specwithpaused)
  * [`fn withPorts(ports)`](#fn-specwithports)
  * [`fn withPortsMixin(ports)`](#fn-specwithportsmixin)
  * [`fn withQuiet(quiet)`](#fn-specwithquiet)
  * [`fn withSeparate(separate)`](#fn-specwithseparate)
  * [`fn withTestRunId(testRunId)`](#fn-specwithtestrunid)
  * [`fn withToken(token)`](#fn-specwithtoken)
  * [`obj spec.initializer`](#obj-specinitializer)
    * [`fn withAutomountServiceAccountToken(automountServiceAccountToken)`](#fn-specinitializerwithautomountserviceaccounttoken)
    * [`fn withEnv(env)`](#fn-specinitializerwithenv)
    * [`fn withEnvFrom(envFrom)`](#fn-specinitializerwithenvfrom)
    * [`fn withEnvFromMixin(envFrom)`](#fn-specinitializerwithenvfrommixin)
    * [`fn withEnvMixin(env)`](#fn-specinitializerwithenvmixin)
    * [`fn withImage(image)`](#fn-specinitializerwithimage)
    * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specinitializerwithimagepullpolicy)
    * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-specinitializerwithimagepullsecrets)
    * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-specinitializerwithimagepullsecretsmixin)
    * [`fn withInitContainers(initContainers)`](#fn-specinitializerwithinitcontainers)
    * [`fn withInitContainersMixin(initContainers)`](#fn-specinitializerwithinitcontainersmixin)
    * [`fn withNodeSelector(nodeSelector)`](#fn-specinitializerwithnodeselector)
    * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-specinitializerwithnodeselectormixin)
    * [`fn withServiceAccountName(serviceAccountName)`](#fn-specinitializerwithserviceaccountname)
    * [`fn withTolerations(tolerations)`](#fn-specinitializerwithtolerations)
    * [`fn withTolerationsMixin(tolerations)`](#fn-specinitializerwithtolerationsmixin)
    * [`fn withTopologySpreadConstraints(topologySpreadConstraints)`](#fn-specinitializerwithtopologyspreadconstraints)
    * [`fn withTopologySpreadConstraintsMixin(topologySpreadConstraints)`](#fn-specinitializerwithtopologyspreadconstraintsmixin)
    * [`fn withVolumeMounts(volumeMounts)`](#fn-specinitializerwithvolumemounts)
    * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specinitializerwithvolumemountsmixin)
    * [`fn withVolumes(volumes)`](#fn-specinitializerwithvolumes)
    * [`fn withVolumesMixin(volumes)`](#fn-specinitializerwithvolumesmixin)
    * [`obj spec.initializer.affinity`](#obj-specinitializeraffinity)
      * [`obj spec.initializer.affinity.nodeAffinity`](#obj-specinitializeraffinitynodeaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specinitializeraffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specinitializeraffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
            * [`fn withMatchFields(matchFields)`](#fn-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
            * [`fn withMatchFieldsMixin(matchFields)`](#fn-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
            * [`obj spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
              * [`fn withKey(key)`](#fn-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
            * [`obj spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
              * [`fn withKey(key)`](#fn-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
              * [`fn withOperator(operator)`](#fn-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
              * [`fn withValues(values)`](#fn-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specinitializeraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
        * [`obj spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
          * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
          * [`obj spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
            * [`fn withMatchFields(matchFields)`](#fn-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
            * [`fn withMatchFieldsMixin(matchFields)`](#fn-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
            * [`obj spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
              * [`fn withKey(key)`](#fn-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
            * [`obj spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
              * [`fn withKey(key)`](#fn-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
              * [`fn withOperator(operator)`](#fn-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
              * [`fn withValues(values)`](#fn-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specinitializeraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
      * [`obj spec.initializer.affinity.podAffinity`](#obj-specinitializeraffinitypodaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specinitializeraffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specinitializeraffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specinitializeraffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specinitializeraffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
            * [`obj spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
              * [`obj spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specinitializeraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
          * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
          * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
          * [`fn withNamespaces(namespaces)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
          * [`obj spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
            * [`obj spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specinitializeraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.initializer.affinity.podAntiAffinity`](#obj-specinitializeraffinitypodantiaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specinitializeraffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specinitializeraffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specinitializeraffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specinitializeraffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
            * [`obj spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
              * [`obj spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specinitializeraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
          * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
          * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
          * [`fn withNamespaces(namespaces)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
          * [`obj spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
            * [`obj spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specinitializeraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
    * [`obj spec.initializer.containerSecurityContext`](#obj-specinitializercontainersecuritycontext)
      * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specinitializercontainersecuritycontextwithallowprivilegeescalation)
      * [`fn withPrivileged(privileged)`](#fn-specinitializercontainersecuritycontextwithprivileged)
      * [`fn withProcMount(procMount)`](#fn-specinitializercontainersecuritycontextwithprocmount)
      * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specinitializercontainersecuritycontextwithreadonlyrootfilesystem)
      * [`fn withRunAsGroup(runAsGroup)`](#fn-specinitializercontainersecuritycontextwithrunasgroup)
      * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specinitializercontainersecuritycontextwithrunasnonroot)
      * [`fn withRunAsUser(runAsUser)`](#fn-specinitializercontainersecuritycontextwithrunasuser)
      * [`obj spec.initializer.containerSecurityContext.appArmorProfile`](#obj-specinitializercontainersecuritycontextapparmorprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specinitializercontainersecuritycontextapparmorprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specinitializercontainersecuritycontextapparmorprofilewithtype)
      * [`obj spec.initializer.containerSecurityContext.capabilities`](#obj-specinitializercontainersecuritycontextcapabilities)
        * [`fn withAdd(add)`](#fn-specinitializercontainersecuritycontextcapabilitieswithadd)
        * [`fn withAddMixin(add)`](#fn-specinitializercontainersecuritycontextcapabilitieswithaddmixin)
        * [`fn withDrop(drop)`](#fn-specinitializercontainersecuritycontextcapabilitieswithdrop)
        * [`fn withDropMixin(drop)`](#fn-specinitializercontainersecuritycontextcapabilitieswithdropmixin)
      * [`obj spec.initializer.containerSecurityContext.seLinuxOptions`](#obj-specinitializercontainersecuritycontextselinuxoptions)
        * [`fn withLevel(level)`](#fn-specinitializercontainersecuritycontextselinuxoptionswithlevel)
        * [`fn withRole(role)`](#fn-specinitializercontainersecuritycontextselinuxoptionswithrole)
        * [`fn withType(type)`](#fn-specinitializercontainersecuritycontextselinuxoptionswithtype)
        * [`fn withUser(user)`](#fn-specinitializercontainersecuritycontextselinuxoptionswithuser)
      * [`obj spec.initializer.containerSecurityContext.seccompProfile`](#obj-specinitializercontainersecuritycontextseccompprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specinitializercontainersecuritycontextseccompprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specinitializercontainersecuritycontextseccompprofilewithtype)
      * [`obj spec.initializer.containerSecurityContext.windowsOptions`](#obj-specinitializercontainersecuritycontextwindowsoptions)
        * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specinitializercontainersecuritycontextwindowsoptionswithgmsacredentialspec)
        * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specinitializercontainersecuritycontextwindowsoptionswithgmsacredentialspecname)
        * [`fn withHostProcess(hostProcess)`](#fn-specinitializercontainersecuritycontextwindowsoptionswithhostprocess)
        * [`fn withRunAsUserName(runAsUserName)`](#fn-specinitializercontainersecuritycontextwindowsoptionswithrunasusername)
    * [`obj spec.initializer.env`](#obj-specinitializerenv)
      * [`fn withName(name)`](#fn-specinitializerenvwithname)
      * [`fn withValue(value)`](#fn-specinitializerenvwithvalue)
      * [`obj spec.initializer.env.valueFrom`](#obj-specinitializerenvvaluefrom)
        * [`obj spec.initializer.env.valueFrom.configMapKeyRef`](#obj-specinitializerenvvaluefromconfigmapkeyref)
          * [`fn withKey(key)`](#fn-specinitializerenvvaluefromconfigmapkeyrefwithkey)
          * [`fn withName(name)`](#fn-specinitializerenvvaluefromconfigmapkeyrefwithname)
          * [`fn withOptional(optional)`](#fn-specinitializerenvvaluefromconfigmapkeyrefwithoptional)
        * [`obj spec.initializer.env.valueFrom.fieldRef`](#obj-specinitializerenvvaluefromfieldref)
          * [`fn withApiVersion(apiVersion)`](#fn-specinitializerenvvaluefromfieldrefwithapiversion)
          * [`fn withFieldPath(fieldPath)`](#fn-specinitializerenvvaluefromfieldrefwithfieldpath)
        * [`obj spec.initializer.env.valueFrom.resourceFieldRef`](#obj-specinitializerenvvaluefromresourcefieldref)
          * [`fn withContainerName(containerName)`](#fn-specinitializerenvvaluefromresourcefieldrefwithcontainername)
          * [`fn withDivisor(divisor)`](#fn-specinitializerenvvaluefromresourcefieldrefwithdivisor)
          * [`fn withResource(resource)`](#fn-specinitializerenvvaluefromresourcefieldrefwithresource)
        * [`obj spec.initializer.env.valueFrom.secretKeyRef`](#obj-specinitializerenvvaluefromsecretkeyref)
          * [`fn withKey(key)`](#fn-specinitializerenvvaluefromsecretkeyrefwithkey)
          * [`fn withName(name)`](#fn-specinitializerenvvaluefromsecretkeyrefwithname)
          * [`fn withOptional(optional)`](#fn-specinitializerenvvaluefromsecretkeyrefwithoptional)
    * [`obj spec.initializer.envFrom`](#obj-specinitializerenvfrom)
      * [`fn withPrefix(prefix)`](#fn-specinitializerenvfromwithprefix)
      * [`obj spec.initializer.envFrom.configMapRef`](#obj-specinitializerenvfromconfigmapref)
        * [`fn withName(name)`](#fn-specinitializerenvfromconfigmaprefwithname)
        * [`fn withOptional(optional)`](#fn-specinitializerenvfromconfigmaprefwithoptional)
      * [`obj spec.initializer.envFrom.secretRef`](#obj-specinitializerenvfromsecretref)
        * [`fn withName(name)`](#fn-specinitializerenvfromsecretrefwithname)
        * [`fn withOptional(optional)`](#fn-specinitializerenvfromsecretrefwithoptional)
    * [`obj spec.initializer.imagePullSecrets`](#obj-specinitializerimagepullsecrets)
      * [`fn withName(name)`](#fn-specinitializerimagepullsecretswithname)
    * [`obj spec.initializer.initContainers`](#obj-specinitializerinitcontainers)
      * [`fn withArgs(args)`](#fn-specinitializerinitcontainerswithargs)
      * [`fn withArgsMixin(args)`](#fn-specinitializerinitcontainerswithargsmixin)
      * [`fn withCommand(command)`](#fn-specinitializerinitcontainerswithcommand)
      * [`fn withCommandMixin(command)`](#fn-specinitializerinitcontainerswithcommandmixin)
      * [`fn withEnv(env)`](#fn-specinitializerinitcontainerswithenv)
      * [`fn withEnvFrom(envFrom)`](#fn-specinitializerinitcontainerswithenvfrom)
      * [`fn withEnvFromMixin(envFrom)`](#fn-specinitializerinitcontainerswithenvfrommixin)
      * [`fn withEnvMixin(env)`](#fn-specinitializerinitcontainerswithenvmixin)
      * [`fn withImage(image)`](#fn-specinitializerinitcontainerswithimage)
      * [`fn withName(name)`](#fn-specinitializerinitcontainerswithname)
      * [`fn withVolumeMounts(volumeMounts)`](#fn-specinitializerinitcontainerswithvolumemounts)
      * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specinitializerinitcontainerswithvolumemountsmixin)
      * [`fn withWorkingDir(workingDir)`](#fn-specinitializerinitcontainerswithworkingdir)
      * [`obj spec.initializer.initContainers.env`](#obj-specinitializerinitcontainersenv)
        * [`fn withName(name)`](#fn-specinitializerinitcontainersenvwithname)
        * [`fn withValue(value)`](#fn-specinitializerinitcontainersenvwithvalue)
        * [`obj spec.initializer.initContainers.env.valueFrom`](#obj-specinitializerinitcontainersenvvaluefrom)
          * [`obj spec.initializer.initContainers.env.valueFrom.configMapKeyRef`](#obj-specinitializerinitcontainersenvvaluefromconfigmapkeyref)
            * [`fn withKey(key)`](#fn-specinitializerinitcontainersenvvaluefromconfigmapkeyrefwithkey)
            * [`fn withName(name)`](#fn-specinitializerinitcontainersenvvaluefromconfigmapkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-specinitializerinitcontainersenvvaluefromconfigmapkeyrefwithoptional)
          * [`obj spec.initializer.initContainers.env.valueFrom.fieldRef`](#obj-specinitializerinitcontainersenvvaluefromfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-specinitializerinitcontainersenvvaluefromfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-specinitializerinitcontainersenvvaluefromfieldrefwithfieldpath)
          * [`obj spec.initializer.initContainers.env.valueFrom.resourceFieldRef`](#obj-specinitializerinitcontainersenvvaluefromresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-specinitializerinitcontainersenvvaluefromresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-specinitializerinitcontainersenvvaluefromresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-specinitializerinitcontainersenvvaluefromresourcefieldrefwithresource)
          * [`obj spec.initializer.initContainers.env.valueFrom.secretKeyRef`](#obj-specinitializerinitcontainersenvvaluefromsecretkeyref)
            * [`fn withKey(key)`](#fn-specinitializerinitcontainersenvvaluefromsecretkeyrefwithkey)
            * [`fn withName(name)`](#fn-specinitializerinitcontainersenvvaluefromsecretkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-specinitializerinitcontainersenvvaluefromsecretkeyrefwithoptional)
      * [`obj spec.initializer.initContainers.envFrom`](#obj-specinitializerinitcontainersenvfrom)
        * [`fn withPrefix(prefix)`](#fn-specinitializerinitcontainersenvfromwithprefix)
        * [`obj spec.initializer.initContainers.envFrom.configMapRef`](#obj-specinitializerinitcontainersenvfromconfigmapref)
          * [`fn withName(name)`](#fn-specinitializerinitcontainersenvfromconfigmaprefwithname)
          * [`fn withOptional(optional)`](#fn-specinitializerinitcontainersenvfromconfigmaprefwithoptional)
        * [`obj spec.initializer.initContainers.envFrom.secretRef`](#obj-specinitializerinitcontainersenvfromsecretref)
          * [`fn withName(name)`](#fn-specinitializerinitcontainersenvfromsecretrefwithname)
          * [`fn withOptional(optional)`](#fn-specinitializerinitcontainersenvfromsecretrefwithoptional)
      * [`obj spec.initializer.initContainers.volumeMounts`](#obj-specinitializerinitcontainersvolumemounts)
        * [`fn withMountPath(mountPath)`](#fn-specinitializerinitcontainersvolumemountswithmountpath)
        * [`fn withMountPropagation(mountPropagation)`](#fn-specinitializerinitcontainersvolumemountswithmountpropagation)
        * [`fn withName(name)`](#fn-specinitializerinitcontainersvolumemountswithname)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializerinitcontainersvolumemountswithreadonly)
        * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specinitializerinitcontainersvolumemountswithrecursivereadonly)
        * [`fn withSubPath(subPath)`](#fn-specinitializerinitcontainersvolumemountswithsubpath)
        * [`fn withSubPathExpr(subPathExpr)`](#fn-specinitializerinitcontainersvolumemountswithsubpathexpr)
    * [`obj spec.initializer.livenessProbe`](#obj-specinitializerlivenessprobe)
      * [`fn withFailureThreshold(failureThreshold)`](#fn-specinitializerlivenessprobewithfailurethreshold)
      * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specinitializerlivenessprobewithinitialdelayseconds)
      * [`fn withPeriodSeconds(periodSeconds)`](#fn-specinitializerlivenessprobewithperiodseconds)
      * [`fn withSuccessThreshold(successThreshold)`](#fn-specinitializerlivenessprobewithsuccessthreshold)
      * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specinitializerlivenessprobewithterminationgraceperiodseconds)
      * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specinitializerlivenessprobewithtimeoutseconds)
      * [`obj spec.initializer.livenessProbe.exec`](#obj-specinitializerlivenessprobeexec)
        * [`fn withCommand(command)`](#fn-specinitializerlivenessprobeexecwithcommand)
        * [`fn withCommandMixin(command)`](#fn-specinitializerlivenessprobeexecwithcommandmixin)
      * [`obj spec.initializer.livenessProbe.grpc`](#obj-specinitializerlivenessprobegrpc)
        * [`fn withPort(port)`](#fn-specinitializerlivenessprobegrpcwithport)
        * [`fn withService(service)`](#fn-specinitializerlivenessprobegrpcwithservice)
      * [`obj spec.initializer.livenessProbe.httpGet`](#obj-specinitializerlivenessprobehttpget)
        * [`fn withHost(host)`](#fn-specinitializerlivenessprobehttpgetwithhost)
        * [`fn withHttpHeaders(httpHeaders)`](#fn-specinitializerlivenessprobehttpgetwithhttpheaders)
        * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specinitializerlivenessprobehttpgetwithhttpheadersmixin)
        * [`fn withPath(path)`](#fn-specinitializerlivenessprobehttpgetwithpath)
        * [`fn withPort(port)`](#fn-specinitializerlivenessprobehttpgetwithport)
        * [`fn withScheme(scheme)`](#fn-specinitializerlivenessprobehttpgetwithscheme)
        * [`obj spec.initializer.livenessProbe.httpGet.httpHeaders`](#obj-specinitializerlivenessprobehttpgethttpheaders)
          * [`fn withName(name)`](#fn-specinitializerlivenessprobehttpgethttpheaderswithname)
          * [`fn withValue(value)`](#fn-specinitializerlivenessprobehttpgethttpheaderswithvalue)
      * [`obj spec.initializer.livenessProbe.tcpSocket`](#obj-specinitializerlivenessprobetcpsocket)
        * [`fn withHost(host)`](#fn-specinitializerlivenessprobetcpsocketwithhost)
        * [`fn withPort(port)`](#fn-specinitializerlivenessprobetcpsocketwithport)
    * [`obj spec.initializer.metadata`](#obj-specinitializermetadata)
      * [`fn withAnnotations(annotations)`](#fn-specinitializermetadatawithannotations)
      * [`fn withAnnotationsMixin(annotations)`](#fn-specinitializermetadatawithannotationsmixin)
      * [`fn withLabels(labels)`](#fn-specinitializermetadatawithlabels)
      * [`fn withLabelsMixin(labels)`](#fn-specinitializermetadatawithlabelsmixin)
    * [`obj spec.initializer.readinessProbe`](#obj-specinitializerreadinessprobe)
      * [`fn withFailureThreshold(failureThreshold)`](#fn-specinitializerreadinessprobewithfailurethreshold)
      * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specinitializerreadinessprobewithinitialdelayseconds)
      * [`fn withPeriodSeconds(periodSeconds)`](#fn-specinitializerreadinessprobewithperiodseconds)
      * [`fn withSuccessThreshold(successThreshold)`](#fn-specinitializerreadinessprobewithsuccessthreshold)
      * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specinitializerreadinessprobewithterminationgraceperiodseconds)
      * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specinitializerreadinessprobewithtimeoutseconds)
      * [`obj spec.initializer.readinessProbe.exec`](#obj-specinitializerreadinessprobeexec)
        * [`fn withCommand(command)`](#fn-specinitializerreadinessprobeexecwithcommand)
        * [`fn withCommandMixin(command)`](#fn-specinitializerreadinessprobeexecwithcommandmixin)
      * [`obj spec.initializer.readinessProbe.grpc`](#obj-specinitializerreadinessprobegrpc)
        * [`fn withPort(port)`](#fn-specinitializerreadinessprobegrpcwithport)
        * [`fn withService(service)`](#fn-specinitializerreadinessprobegrpcwithservice)
      * [`obj spec.initializer.readinessProbe.httpGet`](#obj-specinitializerreadinessprobehttpget)
        * [`fn withHost(host)`](#fn-specinitializerreadinessprobehttpgetwithhost)
        * [`fn withHttpHeaders(httpHeaders)`](#fn-specinitializerreadinessprobehttpgetwithhttpheaders)
        * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specinitializerreadinessprobehttpgetwithhttpheadersmixin)
        * [`fn withPath(path)`](#fn-specinitializerreadinessprobehttpgetwithpath)
        * [`fn withPort(port)`](#fn-specinitializerreadinessprobehttpgetwithport)
        * [`fn withScheme(scheme)`](#fn-specinitializerreadinessprobehttpgetwithscheme)
        * [`obj spec.initializer.readinessProbe.httpGet.httpHeaders`](#obj-specinitializerreadinessprobehttpgethttpheaders)
          * [`fn withName(name)`](#fn-specinitializerreadinessprobehttpgethttpheaderswithname)
          * [`fn withValue(value)`](#fn-specinitializerreadinessprobehttpgethttpheaderswithvalue)
      * [`obj spec.initializer.readinessProbe.tcpSocket`](#obj-specinitializerreadinessprobetcpsocket)
        * [`fn withHost(host)`](#fn-specinitializerreadinessprobetcpsocketwithhost)
        * [`fn withPort(port)`](#fn-specinitializerreadinessprobetcpsocketwithport)
    * [`obj spec.initializer.resources`](#obj-specinitializerresources)
      * [`fn withClaims(claims)`](#fn-specinitializerresourceswithclaims)
      * [`fn withClaimsMixin(claims)`](#fn-specinitializerresourceswithclaimsmixin)
      * [`fn withLimits(limits)`](#fn-specinitializerresourceswithlimits)
      * [`fn withLimitsMixin(limits)`](#fn-specinitializerresourceswithlimitsmixin)
      * [`fn withRequests(requests)`](#fn-specinitializerresourceswithrequests)
      * [`fn withRequestsMixin(requests)`](#fn-specinitializerresourceswithrequestsmixin)
      * [`obj spec.initializer.resources.claims`](#obj-specinitializerresourcesclaims)
        * [`fn withName(name)`](#fn-specinitializerresourcesclaimswithname)
        * [`fn withRequest(request)`](#fn-specinitializerresourcesclaimswithrequest)
    * [`obj spec.initializer.securityContext`](#obj-specinitializersecuritycontext)
      * [`fn withFsGroup(fsGroup)`](#fn-specinitializersecuritycontextwithfsgroup)
      * [`fn withFsGroupChangePolicy(fsGroupChangePolicy)`](#fn-specinitializersecuritycontextwithfsgroupchangepolicy)
      * [`fn withRunAsGroup(runAsGroup)`](#fn-specinitializersecuritycontextwithrunasgroup)
      * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specinitializersecuritycontextwithrunasnonroot)
      * [`fn withRunAsUser(runAsUser)`](#fn-specinitializersecuritycontextwithrunasuser)
      * [`fn withSupplementalGroups(supplementalGroups)`](#fn-specinitializersecuritycontextwithsupplementalgroups)
      * [`fn withSupplementalGroupsMixin(supplementalGroups)`](#fn-specinitializersecuritycontextwithsupplementalgroupsmixin)
      * [`fn withSupplementalGroupsPolicy(supplementalGroupsPolicy)`](#fn-specinitializersecuritycontextwithsupplementalgroupspolicy)
      * [`fn withSysctls(sysctls)`](#fn-specinitializersecuritycontextwithsysctls)
      * [`fn withSysctlsMixin(sysctls)`](#fn-specinitializersecuritycontextwithsysctlsmixin)
      * [`obj spec.initializer.securityContext.appArmorProfile`](#obj-specinitializersecuritycontextapparmorprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specinitializersecuritycontextapparmorprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specinitializersecuritycontextapparmorprofilewithtype)
      * [`obj spec.initializer.securityContext.seLinuxOptions`](#obj-specinitializersecuritycontextselinuxoptions)
        * [`fn withLevel(level)`](#fn-specinitializersecuritycontextselinuxoptionswithlevel)
        * [`fn withRole(role)`](#fn-specinitializersecuritycontextselinuxoptionswithrole)
        * [`fn withType(type)`](#fn-specinitializersecuritycontextselinuxoptionswithtype)
        * [`fn withUser(user)`](#fn-specinitializersecuritycontextselinuxoptionswithuser)
      * [`obj spec.initializer.securityContext.seccompProfile`](#obj-specinitializersecuritycontextseccompprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specinitializersecuritycontextseccompprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specinitializersecuritycontextseccompprofilewithtype)
      * [`obj spec.initializer.securityContext.sysctls`](#obj-specinitializersecuritycontextsysctls)
        * [`fn withName(name)`](#fn-specinitializersecuritycontextsysctlswithname)
        * [`fn withValue(value)`](#fn-specinitializersecuritycontextsysctlswithvalue)
      * [`obj spec.initializer.securityContext.windowsOptions`](#obj-specinitializersecuritycontextwindowsoptions)
        * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specinitializersecuritycontextwindowsoptionswithgmsacredentialspec)
        * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specinitializersecuritycontextwindowsoptionswithgmsacredentialspecname)
        * [`fn withHostProcess(hostProcess)`](#fn-specinitializersecuritycontextwindowsoptionswithhostprocess)
        * [`fn withRunAsUserName(runAsUserName)`](#fn-specinitializersecuritycontextwindowsoptionswithrunasusername)
    * [`obj spec.initializer.tolerations`](#obj-specinitializertolerations)
      * [`fn withEffect(effect)`](#fn-specinitializertolerationswitheffect)
      * [`fn withKey(key)`](#fn-specinitializertolerationswithkey)
      * [`fn withOperator(operator)`](#fn-specinitializertolerationswithoperator)
      * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-specinitializertolerationswithtolerationseconds)
      * [`fn withValue(value)`](#fn-specinitializertolerationswithvalue)
    * [`obj spec.initializer.topologySpreadConstraints`](#obj-specinitializertopologyspreadconstraints)
      * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specinitializertopologyspreadconstraintswithmatchlabelkeys)
      * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specinitializertopologyspreadconstraintswithmatchlabelkeysmixin)
      * [`fn withMaxSkew(maxSkew)`](#fn-specinitializertopologyspreadconstraintswithmaxskew)
      * [`fn withMinDomains(minDomains)`](#fn-specinitializertopologyspreadconstraintswithmindomains)
      * [`fn withNodeAffinityPolicy(nodeAffinityPolicy)`](#fn-specinitializertopologyspreadconstraintswithnodeaffinitypolicy)
      * [`fn withNodeTaintsPolicy(nodeTaintsPolicy)`](#fn-specinitializertopologyspreadconstraintswithnodetaintspolicy)
      * [`fn withTopologyKey(topologyKey)`](#fn-specinitializertopologyspreadconstraintswithtopologykey)
      * [`fn withWhenUnsatisfiable(whenUnsatisfiable)`](#fn-specinitializertopologyspreadconstraintswithwhenunsatisfiable)
      * [`obj spec.initializer.topologySpreadConstraints.labelSelector`](#obj-specinitializertopologyspreadconstraintslabelselector)
        * [`fn withMatchExpressions(matchExpressions)`](#fn-specinitializertopologyspreadconstraintslabelselectorwithmatchexpressions)
        * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specinitializertopologyspreadconstraintslabelselectorwithmatchexpressionsmixin)
        * [`fn withMatchLabels(matchLabels)`](#fn-specinitializertopologyspreadconstraintslabelselectorwithmatchlabels)
        * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specinitializertopologyspreadconstraintslabelselectorwithmatchlabelsmixin)
        * [`obj spec.initializer.topologySpreadConstraints.labelSelector.matchExpressions`](#obj-specinitializertopologyspreadconstraintslabelselectormatchexpressions)
          * [`fn withKey(key)`](#fn-specinitializertopologyspreadconstraintslabelselectormatchexpressionswithkey)
          * [`fn withOperator(operator)`](#fn-specinitializertopologyspreadconstraintslabelselectormatchexpressionswithoperator)
          * [`fn withValues(values)`](#fn-specinitializertopologyspreadconstraintslabelselectormatchexpressionswithvalues)
          * [`fn withValuesMixin(values)`](#fn-specinitializertopologyspreadconstraintslabelselectormatchexpressionswithvaluesmixin)
    * [`obj spec.initializer.volumeMounts`](#obj-specinitializervolumemounts)
      * [`fn withMountPath(mountPath)`](#fn-specinitializervolumemountswithmountpath)
      * [`fn withMountPropagation(mountPropagation)`](#fn-specinitializervolumemountswithmountpropagation)
      * [`fn withName(name)`](#fn-specinitializervolumemountswithname)
      * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumemountswithreadonly)
      * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specinitializervolumemountswithrecursivereadonly)
      * [`fn withSubPath(subPath)`](#fn-specinitializervolumemountswithsubpath)
      * [`fn withSubPathExpr(subPathExpr)`](#fn-specinitializervolumemountswithsubpathexpr)
    * [`obj spec.initializer.volumes`](#obj-specinitializervolumes)
      * [`fn withName(name)`](#fn-specinitializervolumeswithname)
      * [`obj spec.initializer.volumes.awsElasticBlockStore`](#obj-specinitializervolumesawselasticblockstore)
        * [`fn withFsType(fsType)`](#fn-specinitializervolumesawselasticblockstorewithfstype)
        * [`fn withPartition(partition)`](#fn-specinitializervolumesawselasticblockstorewithpartition)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumesawselasticblockstorewithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-specinitializervolumesawselasticblockstorewithvolumeid)
      * [`obj spec.initializer.volumes.azureDisk`](#obj-specinitializervolumesazuredisk)
        * [`fn withCachingMode(cachingMode)`](#fn-specinitializervolumesazurediskwithcachingmode)
        * [`fn withDiskName(diskName)`](#fn-specinitializervolumesazurediskwithdiskname)
        * [`fn withDiskURI(diskURI)`](#fn-specinitializervolumesazurediskwithdiskuri)
        * [`fn withFsType(fsType)`](#fn-specinitializervolumesazurediskwithfstype)
        * [`fn withKind(kind)`](#fn-specinitializervolumesazurediskwithkind)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumesazurediskwithreadonly)
      * [`obj spec.initializer.volumes.azureFile`](#obj-specinitializervolumesazurefile)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumesazurefilewithreadonly)
        * [`fn withSecretName(secretName)`](#fn-specinitializervolumesazurefilewithsecretname)
        * [`fn withShareName(shareName)`](#fn-specinitializervolumesazurefilewithsharename)
      * [`obj spec.initializer.volumes.cephfs`](#obj-specinitializervolumescephfs)
        * [`fn withMonitors(monitors)`](#fn-specinitializervolumescephfswithmonitors)
        * [`fn withMonitorsMixin(monitors)`](#fn-specinitializervolumescephfswithmonitorsmixin)
        * [`fn withPath(path)`](#fn-specinitializervolumescephfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumescephfswithreadonly)
        * [`fn withSecretFile(secretFile)`](#fn-specinitializervolumescephfswithsecretfile)
        * [`fn withUser(user)`](#fn-specinitializervolumescephfswithuser)
        * [`obj spec.initializer.volumes.cephfs.secretRef`](#obj-specinitializervolumescephfssecretref)
          * [`fn withName(name)`](#fn-specinitializervolumescephfssecretrefwithname)
      * [`obj spec.initializer.volumes.cinder`](#obj-specinitializervolumescinder)
        * [`fn withFsType(fsType)`](#fn-specinitializervolumescinderwithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumescinderwithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-specinitializervolumescinderwithvolumeid)
        * [`obj spec.initializer.volumes.cinder.secretRef`](#obj-specinitializervolumescindersecretref)
          * [`fn withName(name)`](#fn-specinitializervolumescindersecretrefwithname)
      * [`obj spec.initializer.volumes.configMap`](#obj-specinitializervolumesconfigmap)
        * [`fn withDefaultMode(defaultMode)`](#fn-specinitializervolumesconfigmapwithdefaultmode)
        * [`fn withItems(items)`](#fn-specinitializervolumesconfigmapwithitems)
        * [`fn withItemsMixin(items)`](#fn-specinitializervolumesconfigmapwithitemsmixin)
        * [`fn withName(name)`](#fn-specinitializervolumesconfigmapwithname)
        * [`fn withOptional(optional)`](#fn-specinitializervolumesconfigmapwithoptional)
        * [`obj spec.initializer.volumes.configMap.items`](#obj-specinitializervolumesconfigmapitems)
          * [`fn withKey(key)`](#fn-specinitializervolumesconfigmapitemswithkey)
          * [`fn withMode(mode)`](#fn-specinitializervolumesconfigmapitemswithmode)
          * [`fn withPath(path)`](#fn-specinitializervolumesconfigmapitemswithpath)
      * [`obj spec.initializer.volumes.csi`](#obj-specinitializervolumescsi)
        * [`fn withDriver(driver)`](#fn-specinitializervolumescsiwithdriver)
        * [`fn withFsType(fsType)`](#fn-specinitializervolumescsiwithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumescsiwithreadonly)
        * [`fn withVolumeAttributes(volumeAttributes)`](#fn-specinitializervolumescsiwithvolumeattributes)
        * [`fn withVolumeAttributesMixin(volumeAttributes)`](#fn-specinitializervolumescsiwithvolumeattributesmixin)
        * [`obj spec.initializer.volumes.csi.nodePublishSecretRef`](#obj-specinitializervolumescsinodepublishsecretref)
          * [`fn withName(name)`](#fn-specinitializervolumescsinodepublishsecretrefwithname)
      * [`obj spec.initializer.volumes.downwardAPI`](#obj-specinitializervolumesdownwardapi)
        * [`fn withDefaultMode(defaultMode)`](#fn-specinitializervolumesdownwardapiwithdefaultmode)
        * [`fn withItems(items)`](#fn-specinitializervolumesdownwardapiwithitems)
        * [`fn withItemsMixin(items)`](#fn-specinitializervolumesdownwardapiwithitemsmixin)
        * [`obj spec.initializer.volumes.downwardAPI.items`](#obj-specinitializervolumesdownwardapiitems)
          * [`fn withMode(mode)`](#fn-specinitializervolumesdownwardapiitemswithmode)
          * [`fn withPath(path)`](#fn-specinitializervolumesdownwardapiitemswithpath)
          * [`obj spec.initializer.volumes.downwardAPI.items.fieldRef`](#obj-specinitializervolumesdownwardapiitemsfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-specinitializervolumesdownwardapiitemsfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-specinitializervolumesdownwardapiitemsfieldrefwithfieldpath)
          * [`obj spec.initializer.volumes.downwardAPI.items.resourceFieldRef`](#obj-specinitializervolumesdownwardapiitemsresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-specinitializervolumesdownwardapiitemsresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-specinitializervolumesdownwardapiitemsresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-specinitializervolumesdownwardapiitemsresourcefieldrefwithresource)
      * [`obj spec.initializer.volumes.emptyDir`](#obj-specinitializervolumesemptydir)
        * [`fn withMedium(medium)`](#fn-specinitializervolumesemptydirwithmedium)
        * [`fn withSizeLimit(sizeLimit)`](#fn-specinitializervolumesemptydirwithsizelimit)
      * [`obj spec.initializer.volumes.ephemeral`](#obj-specinitializervolumesephemeral)
        * [`obj spec.initializer.volumes.ephemeral.volumeClaimTemplate`](#obj-specinitializervolumesephemeralvolumeclaimtemplate)
          * [`fn withMetadata(metadata)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatewithmetadata)
          * [`fn withMetadataMixin(metadata)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatewithmetadatamixin)
          * [`obj spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec`](#obj-specinitializervolumesephemeralvolumeclaimtemplatespec)
            * [`fn withAccessModes(accessModes)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecwithaccessmodes)
            * [`fn withAccessModesMixin(accessModes)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecwithaccessmodesmixin)
            * [`fn withStorageClassName(storageClassName)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecwithstorageclassname)
            * [`fn withVolumeAttributesClassName(volumeAttributesClassName)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecwithvolumeattributesclassname)
            * [`fn withVolumeMode(volumeMode)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecwithvolumemode)
            * [`fn withVolumeName(volumeName)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecwithvolumename)
            * [`obj spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.dataSource`](#obj-specinitializervolumesephemeralvolumeclaimtemplatespecdatasource)
              * [`fn withApiGroup(apiGroup)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecdatasourcewithapigroup)
              * [`fn withKind(kind)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecdatasourcewithkind)
              * [`fn withName(name)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecdatasourcewithname)
            * [`obj spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef`](#obj-specinitializervolumesephemeralvolumeclaimtemplatespecdatasourceref)
              * [`fn withApiGroup(apiGroup)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecdatasourcerefwithapigroup)
              * [`fn withKind(kind)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecdatasourcerefwithkind)
              * [`fn withName(name)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecdatasourcerefwithname)
              * [`fn withNamespace(namespace)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecdatasourcerefwithnamespace)
            * [`obj spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.resources`](#obj-specinitializervolumesephemeralvolumeclaimtemplatespecresources)
              * [`fn withLimits(limits)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecresourceswithlimits)
              * [`fn withLimitsMixin(limits)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecresourceswithlimitsmixin)
              * [`fn withRequests(requests)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecresourceswithrequests)
              * [`fn withRequestsMixin(requests)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecresourceswithrequestsmixin)
            * [`obj spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.selector`](#obj-specinitializervolumesephemeralvolumeclaimtemplatespecselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabelsmixin)
              * [`obj spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions`](#obj-specinitializervolumesephemeralvolumeclaimtemplatespecselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specinitializervolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvaluesmixin)
      * [`obj spec.initializer.volumes.fc`](#obj-specinitializervolumesfc)
        * [`fn withFsType(fsType)`](#fn-specinitializervolumesfcwithfstype)
        * [`fn withLun(lun)`](#fn-specinitializervolumesfcwithlun)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumesfcwithreadonly)
        * [`fn withTargetWWNs(targetWWNs)`](#fn-specinitializervolumesfcwithtargetwwns)
        * [`fn withTargetWWNsMixin(targetWWNs)`](#fn-specinitializervolumesfcwithtargetwwnsmixin)
        * [`fn withWwids(wwids)`](#fn-specinitializervolumesfcwithwwids)
        * [`fn withWwidsMixin(wwids)`](#fn-specinitializervolumesfcwithwwidsmixin)
      * [`obj spec.initializer.volumes.flexVolume`](#obj-specinitializervolumesflexvolume)
        * [`fn withDriver(driver)`](#fn-specinitializervolumesflexvolumewithdriver)
        * [`fn withFsType(fsType)`](#fn-specinitializervolumesflexvolumewithfstype)
        * [`fn withOptions(options)`](#fn-specinitializervolumesflexvolumewithoptions)
        * [`fn withOptionsMixin(options)`](#fn-specinitializervolumesflexvolumewithoptionsmixin)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumesflexvolumewithreadonly)
        * [`obj spec.initializer.volumes.flexVolume.secretRef`](#obj-specinitializervolumesflexvolumesecretref)
          * [`fn withName(name)`](#fn-specinitializervolumesflexvolumesecretrefwithname)
      * [`obj spec.initializer.volumes.flocker`](#obj-specinitializervolumesflocker)
        * [`fn withDatasetName(datasetName)`](#fn-specinitializervolumesflockerwithdatasetname)
        * [`fn withDatasetUUID(datasetUUID)`](#fn-specinitializervolumesflockerwithdatasetuuid)
      * [`obj spec.initializer.volumes.gcePersistentDisk`](#obj-specinitializervolumesgcepersistentdisk)
        * [`fn withFsType(fsType)`](#fn-specinitializervolumesgcepersistentdiskwithfstype)
        * [`fn withPartition(partition)`](#fn-specinitializervolumesgcepersistentdiskwithpartition)
        * [`fn withPdName(pdName)`](#fn-specinitializervolumesgcepersistentdiskwithpdname)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumesgcepersistentdiskwithreadonly)
      * [`obj spec.initializer.volumes.gitRepo`](#obj-specinitializervolumesgitrepo)
        * [`fn withDirectory(directory)`](#fn-specinitializervolumesgitrepowithdirectory)
        * [`fn withRepository(repository)`](#fn-specinitializervolumesgitrepowithrepository)
        * [`fn withRevision(revision)`](#fn-specinitializervolumesgitrepowithrevision)
      * [`obj spec.initializer.volumes.glusterfs`](#obj-specinitializervolumesglusterfs)
        * [`fn withEndpoints(endpoints)`](#fn-specinitializervolumesglusterfswithendpoints)
        * [`fn withPath(path)`](#fn-specinitializervolumesglusterfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumesglusterfswithreadonly)
      * [`obj spec.initializer.volumes.hostPath`](#obj-specinitializervolumeshostpath)
        * [`fn withPath(path)`](#fn-specinitializervolumeshostpathwithpath)
        * [`fn withType(type)`](#fn-specinitializervolumeshostpathwithtype)
      * [`obj spec.initializer.volumes.image`](#obj-specinitializervolumesimage)
        * [`fn withPullPolicy(pullPolicy)`](#fn-specinitializervolumesimagewithpullpolicy)
        * [`fn withReference(reference)`](#fn-specinitializervolumesimagewithreference)
      * [`obj spec.initializer.volumes.iscsi`](#obj-specinitializervolumesiscsi)
        * [`fn withChapAuthDiscovery(chapAuthDiscovery)`](#fn-specinitializervolumesiscsiwithchapauthdiscovery)
        * [`fn withChapAuthSession(chapAuthSession)`](#fn-specinitializervolumesiscsiwithchapauthsession)
        * [`fn withFsType(fsType)`](#fn-specinitializervolumesiscsiwithfstype)
        * [`fn withInitiatorName(initiatorName)`](#fn-specinitializervolumesiscsiwithinitiatorname)
        * [`fn withIqn(iqn)`](#fn-specinitializervolumesiscsiwithiqn)
        * [`fn withIscsiInterface(iscsiInterface)`](#fn-specinitializervolumesiscsiwithiscsiinterface)
        * [`fn withLun(lun)`](#fn-specinitializervolumesiscsiwithlun)
        * [`fn withPortals(portals)`](#fn-specinitializervolumesiscsiwithportals)
        * [`fn withPortalsMixin(portals)`](#fn-specinitializervolumesiscsiwithportalsmixin)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumesiscsiwithreadonly)
        * [`fn withTargetPortal(targetPortal)`](#fn-specinitializervolumesiscsiwithtargetportal)
        * [`obj spec.initializer.volumes.iscsi.secretRef`](#obj-specinitializervolumesiscsisecretref)
          * [`fn withName(name)`](#fn-specinitializervolumesiscsisecretrefwithname)
      * [`obj spec.initializer.volumes.nfs`](#obj-specinitializervolumesnfs)
        * [`fn withPath(path)`](#fn-specinitializervolumesnfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumesnfswithreadonly)
        * [`fn withServer(server)`](#fn-specinitializervolumesnfswithserver)
      * [`obj spec.initializer.volumes.persistentVolumeClaim`](#obj-specinitializervolumespersistentvolumeclaim)
        * [`fn withClaimName(claimName)`](#fn-specinitializervolumespersistentvolumeclaimwithclaimname)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumespersistentvolumeclaimwithreadonly)
      * [`obj spec.initializer.volumes.photonPersistentDisk`](#obj-specinitializervolumesphotonpersistentdisk)
        * [`fn withFsType(fsType)`](#fn-specinitializervolumesphotonpersistentdiskwithfstype)
        * [`fn withPdID(pdID)`](#fn-specinitializervolumesphotonpersistentdiskwithpdid)
      * [`obj spec.initializer.volumes.portworxVolume`](#obj-specinitializervolumesportworxvolume)
        * [`fn withFsType(fsType)`](#fn-specinitializervolumesportworxvolumewithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumesportworxvolumewithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-specinitializervolumesportworxvolumewithvolumeid)
      * [`obj spec.initializer.volumes.projected`](#obj-specinitializervolumesprojected)
        * [`fn withDefaultMode(defaultMode)`](#fn-specinitializervolumesprojectedwithdefaultmode)
        * [`fn withSources(sources)`](#fn-specinitializervolumesprojectedwithsources)
        * [`fn withSourcesMixin(sources)`](#fn-specinitializervolumesprojectedwithsourcesmixin)
        * [`obj spec.initializer.volumes.projected.sources`](#obj-specinitializervolumesprojectedsources)
          * [`obj spec.initializer.volumes.projected.sources.clusterTrustBundle`](#obj-specinitializervolumesprojectedsourcesclustertrustbundle)
            * [`fn withName(name)`](#fn-specinitializervolumesprojectedsourcesclustertrustbundlewithname)
            * [`fn withOptional(optional)`](#fn-specinitializervolumesprojectedsourcesclustertrustbundlewithoptional)
            * [`fn withPath(path)`](#fn-specinitializervolumesprojectedsourcesclustertrustbundlewithpath)
            * [`fn withSignerName(signerName)`](#fn-specinitializervolumesprojectedsourcesclustertrustbundlewithsignername)
            * [`obj spec.initializer.volumes.projected.sources.clusterTrustBundle.labelSelector`](#obj-specinitializervolumesprojectedsourcesclustertrustbundlelabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specinitializervolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specinitializervolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specinitializervolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specinitializervolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabelsmixin)
              * [`obj spec.initializer.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions`](#obj-specinitializervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specinitializervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specinitializervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specinitializervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specinitializervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.initializer.volumes.projected.sources.configMap`](#obj-specinitializervolumesprojectedsourcesconfigmap)
            * [`fn withItems(items)`](#fn-specinitializervolumesprojectedsourcesconfigmapwithitems)
            * [`fn withItemsMixin(items)`](#fn-specinitializervolumesprojectedsourcesconfigmapwithitemsmixin)
            * [`fn withName(name)`](#fn-specinitializervolumesprojectedsourcesconfigmapwithname)
            * [`fn withOptional(optional)`](#fn-specinitializervolumesprojectedsourcesconfigmapwithoptional)
            * [`obj spec.initializer.volumes.projected.sources.configMap.items`](#obj-specinitializervolumesprojectedsourcesconfigmapitems)
              * [`fn withKey(key)`](#fn-specinitializervolumesprojectedsourcesconfigmapitemswithkey)
              * [`fn withMode(mode)`](#fn-specinitializervolumesprojectedsourcesconfigmapitemswithmode)
              * [`fn withPath(path)`](#fn-specinitializervolumesprojectedsourcesconfigmapitemswithpath)
          * [`obj spec.initializer.volumes.projected.sources.downwardAPI`](#obj-specinitializervolumesprojectedsourcesdownwardapi)
            * [`fn withItems(items)`](#fn-specinitializervolumesprojectedsourcesdownwardapiwithitems)
            * [`fn withItemsMixin(items)`](#fn-specinitializervolumesprojectedsourcesdownwardapiwithitemsmixin)
            * [`obj spec.initializer.volumes.projected.sources.downwardAPI.items`](#obj-specinitializervolumesprojectedsourcesdownwardapiitems)
              * [`fn withMode(mode)`](#fn-specinitializervolumesprojectedsourcesdownwardapiitemswithmode)
              * [`fn withPath(path)`](#fn-specinitializervolumesprojectedsourcesdownwardapiitemswithpath)
              * [`obj spec.initializer.volumes.projected.sources.downwardAPI.items.fieldRef`](#obj-specinitializervolumesprojectedsourcesdownwardapiitemsfieldref)
                * [`fn withApiVersion(apiVersion)`](#fn-specinitializervolumesprojectedsourcesdownwardapiitemsfieldrefwithapiversion)
                * [`fn withFieldPath(fieldPath)`](#fn-specinitializervolumesprojectedsourcesdownwardapiitemsfieldrefwithfieldpath)
              * [`obj spec.initializer.volumes.projected.sources.downwardAPI.items.resourceFieldRef`](#obj-specinitializervolumesprojectedsourcesdownwardapiitemsresourcefieldref)
                * [`fn withContainerName(containerName)`](#fn-specinitializervolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithcontainername)
                * [`fn withDivisor(divisor)`](#fn-specinitializervolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithdivisor)
                * [`fn withResource(resource)`](#fn-specinitializervolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithresource)
          * [`obj spec.initializer.volumes.projected.sources.secret`](#obj-specinitializervolumesprojectedsourcessecret)
            * [`fn withItems(items)`](#fn-specinitializervolumesprojectedsourcessecretwithitems)
            * [`fn withItemsMixin(items)`](#fn-specinitializervolumesprojectedsourcessecretwithitemsmixin)
            * [`fn withName(name)`](#fn-specinitializervolumesprojectedsourcessecretwithname)
            * [`fn withOptional(optional)`](#fn-specinitializervolumesprojectedsourcessecretwithoptional)
            * [`obj spec.initializer.volumes.projected.sources.secret.items`](#obj-specinitializervolumesprojectedsourcessecretitems)
              * [`fn withKey(key)`](#fn-specinitializervolumesprojectedsourcessecretitemswithkey)
              * [`fn withMode(mode)`](#fn-specinitializervolumesprojectedsourcessecretitemswithmode)
              * [`fn withPath(path)`](#fn-specinitializervolumesprojectedsourcessecretitemswithpath)
          * [`obj spec.initializer.volumes.projected.sources.serviceAccountToken`](#obj-specinitializervolumesprojectedsourcesserviceaccounttoken)
            * [`fn withAudience(audience)`](#fn-specinitializervolumesprojectedsourcesserviceaccounttokenwithaudience)
            * [`fn withExpirationSeconds(expirationSeconds)`](#fn-specinitializervolumesprojectedsourcesserviceaccounttokenwithexpirationseconds)
            * [`fn withPath(path)`](#fn-specinitializervolumesprojectedsourcesserviceaccounttokenwithpath)
      * [`obj spec.initializer.volumes.quobyte`](#obj-specinitializervolumesquobyte)
        * [`fn withGroup(group)`](#fn-specinitializervolumesquobytewithgroup)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumesquobytewithreadonly)
        * [`fn withRegistry(registry)`](#fn-specinitializervolumesquobytewithregistry)
        * [`fn withTenant(tenant)`](#fn-specinitializervolumesquobytewithtenant)
        * [`fn withUser(user)`](#fn-specinitializervolumesquobytewithuser)
        * [`fn withVolume(volume)`](#fn-specinitializervolumesquobytewithvolume)
      * [`obj spec.initializer.volumes.rbd`](#obj-specinitializervolumesrbd)
        * [`fn withFsType(fsType)`](#fn-specinitializervolumesrbdwithfstype)
        * [`fn withImage(image)`](#fn-specinitializervolumesrbdwithimage)
        * [`fn withKeyring(keyring)`](#fn-specinitializervolumesrbdwithkeyring)
        * [`fn withMonitors(monitors)`](#fn-specinitializervolumesrbdwithmonitors)
        * [`fn withMonitorsMixin(monitors)`](#fn-specinitializervolumesrbdwithmonitorsmixin)
        * [`fn withPool(pool)`](#fn-specinitializervolumesrbdwithpool)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumesrbdwithreadonly)
        * [`fn withUser(user)`](#fn-specinitializervolumesrbdwithuser)
        * [`obj spec.initializer.volumes.rbd.secretRef`](#obj-specinitializervolumesrbdsecretref)
          * [`fn withName(name)`](#fn-specinitializervolumesrbdsecretrefwithname)
      * [`obj spec.initializer.volumes.scaleIO`](#obj-specinitializervolumesscaleio)
        * [`fn withFsType(fsType)`](#fn-specinitializervolumesscaleiowithfstype)
        * [`fn withGateway(gateway)`](#fn-specinitializervolumesscaleiowithgateway)
        * [`fn withProtectionDomain(protectionDomain)`](#fn-specinitializervolumesscaleiowithprotectiondomain)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumesscaleiowithreadonly)
        * [`fn withSslEnabled(sslEnabled)`](#fn-specinitializervolumesscaleiowithsslenabled)
        * [`fn withStorageMode(storageMode)`](#fn-specinitializervolumesscaleiowithstoragemode)
        * [`fn withStoragePool(storagePool)`](#fn-specinitializervolumesscaleiowithstoragepool)
        * [`fn withSystem(system)`](#fn-specinitializervolumesscaleiowithsystem)
        * [`fn withVolumeName(volumeName)`](#fn-specinitializervolumesscaleiowithvolumename)
        * [`obj spec.initializer.volumes.scaleIO.secretRef`](#obj-specinitializervolumesscaleiosecretref)
          * [`fn withName(name)`](#fn-specinitializervolumesscaleiosecretrefwithname)
      * [`obj spec.initializer.volumes.secret`](#obj-specinitializervolumessecret)
        * [`fn withDefaultMode(defaultMode)`](#fn-specinitializervolumessecretwithdefaultmode)
        * [`fn withItems(items)`](#fn-specinitializervolumessecretwithitems)
        * [`fn withItemsMixin(items)`](#fn-specinitializervolumessecretwithitemsmixin)
        * [`fn withOptional(optional)`](#fn-specinitializervolumessecretwithoptional)
        * [`fn withSecretName(secretName)`](#fn-specinitializervolumessecretwithsecretname)
        * [`obj spec.initializer.volumes.secret.items`](#obj-specinitializervolumessecretitems)
          * [`fn withKey(key)`](#fn-specinitializervolumessecretitemswithkey)
          * [`fn withMode(mode)`](#fn-specinitializervolumessecretitemswithmode)
          * [`fn withPath(path)`](#fn-specinitializervolumessecretitemswithpath)
      * [`obj spec.initializer.volumes.storageos`](#obj-specinitializervolumesstorageos)
        * [`fn withFsType(fsType)`](#fn-specinitializervolumesstorageoswithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specinitializervolumesstorageoswithreadonly)
        * [`fn withVolumeName(volumeName)`](#fn-specinitializervolumesstorageoswithvolumename)
        * [`fn withVolumeNamespace(volumeNamespace)`](#fn-specinitializervolumesstorageoswithvolumenamespace)
        * [`obj spec.initializer.volumes.storageos.secretRef`](#obj-specinitializervolumesstorageossecretref)
          * [`fn withName(name)`](#fn-specinitializervolumesstorageossecretrefwithname)
      * [`obj spec.initializer.volumes.vsphereVolume`](#obj-specinitializervolumesvspherevolume)
        * [`fn withFsType(fsType)`](#fn-specinitializervolumesvspherevolumewithfstype)
        * [`fn withStoragePolicyID(storagePolicyID)`](#fn-specinitializervolumesvspherevolumewithstoragepolicyid)
        * [`fn withStoragePolicyName(storagePolicyName)`](#fn-specinitializervolumesvspherevolumewithstoragepolicyname)
        * [`fn withVolumePath(volumePath)`](#fn-specinitializervolumesvspherevolumewithvolumepath)
  * [`obj spec.ports`](#obj-specports)
    * [`fn withContainerPort(containerPort)`](#fn-specportswithcontainerport)
    * [`fn withHostIP(hostIP)`](#fn-specportswithhostip)
    * [`fn withHostPort(hostPort)`](#fn-specportswithhostport)
    * [`fn withName(name)`](#fn-specportswithname)
    * [`fn withProtocol(protocol)`](#fn-specportswithprotocol)
  * [`obj spec.runner`](#obj-specrunner)
    * [`fn withAutomountServiceAccountToken(automountServiceAccountToken)`](#fn-specrunnerwithautomountserviceaccounttoken)
    * [`fn withEnv(env)`](#fn-specrunnerwithenv)
    * [`fn withEnvFrom(envFrom)`](#fn-specrunnerwithenvfrom)
    * [`fn withEnvFromMixin(envFrom)`](#fn-specrunnerwithenvfrommixin)
    * [`fn withEnvMixin(env)`](#fn-specrunnerwithenvmixin)
    * [`fn withImage(image)`](#fn-specrunnerwithimage)
    * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specrunnerwithimagepullpolicy)
    * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-specrunnerwithimagepullsecrets)
    * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-specrunnerwithimagepullsecretsmixin)
    * [`fn withInitContainers(initContainers)`](#fn-specrunnerwithinitcontainers)
    * [`fn withInitContainersMixin(initContainers)`](#fn-specrunnerwithinitcontainersmixin)
    * [`fn withNodeSelector(nodeSelector)`](#fn-specrunnerwithnodeselector)
    * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-specrunnerwithnodeselectormixin)
    * [`fn withServiceAccountName(serviceAccountName)`](#fn-specrunnerwithserviceaccountname)
    * [`fn withTolerations(tolerations)`](#fn-specrunnerwithtolerations)
    * [`fn withTolerationsMixin(tolerations)`](#fn-specrunnerwithtolerationsmixin)
    * [`fn withTopologySpreadConstraints(topologySpreadConstraints)`](#fn-specrunnerwithtopologyspreadconstraints)
    * [`fn withTopologySpreadConstraintsMixin(topologySpreadConstraints)`](#fn-specrunnerwithtopologyspreadconstraintsmixin)
    * [`fn withVolumeMounts(volumeMounts)`](#fn-specrunnerwithvolumemounts)
    * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specrunnerwithvolumemountsmixin)
    * [`fn withVolumes(volumes)`](#fn-specrunnerwithvolumes)
    * [`fn withVolumesMixin(volumes)`](#fn-specrunnerwithvolumesmixin)
    * [`obj spec.runner.affinity`](#obj-specrunneraffinity)
      * [`obj spec.runner.affinity.nodeAffinity`](#obj-specrunneraffinitynodeaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specrunneraffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specrunneraffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
            * [`fn withMatchFields(matchFields)`](#fn-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
            * [`fn withMatchFieldsMixin(matchFields)`](#fn-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
            * [`obj spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
              * [`fn withKey(key)`](#fn-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
            * [`obj spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
              * [`fn withKey(key)`](#fn-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
              * [`fn withOperator(operator)`](#fn-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
              * [`fn withValues(values)`](#fn-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specrunneraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
        * [`obj spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
          * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
          * [`obj spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
            * [`fn withMatchFields(matchFields)`](#fn-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
            * [`fn withMatchFieldsMixin(matchFields)`](#fn-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
            * [`obj spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
              * [`fn withKey(key)`](#fn-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
            * [`obj spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
              * [`fn withKey(key)`](#fn-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
              * [`fn withOperator(operator)`](#fn-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
              * [`fn withValues(values)`](#fn-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specrunneraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
      * [`obj spec.runner.affinity.podAffinity`](#obj-specrunneraffinitypodaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specrunneraffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specrunneraffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specrunneraffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specrunneraffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
            * [`obj spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
              * [`obj spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specrunneraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
          * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
          * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
          * [`fn withNamespaces(namespaces)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
          * [`obj spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
            * [`obj spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specrunneraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.runner.affinity.podAntiAffinity`](#obj-specrunneraffinitypodantiaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specrunneraffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specrunneraffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specrunneraffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specrunneraffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
            * [`obj spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
              * [`obj spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specrunneraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
          * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
          * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
          * [`fn withNamespaces(namespaces)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
          * [`obj spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
            * [`obj spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specrunneraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
    * [`obj spec.runner.containerSecurityContext`](#obj-specrunnercontainersecuritycontext)
      * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specrunnercontainersecuritycontextwithallowprivilegeescalation)
      * [`fn withPrivileged(privileged)`](#fn-specrunnercontainersecuritycontextwithprivileged)
      * [`fn withProcMount(procMount)`](#fn-specrunnercontainersecuritycontextwithprocmount)
      * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specrunnercontainersecuritycontextwithreadonlyrootfilesystem)
      * [`fn withRunAsGroup(runAsGroup)`](#fn-specrunnercontainersecuritycontextwithrunasgroup)
      * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specrunnercontainersecuritycontextwithrunasnonroot)
      * [`fn withRunAsUser(runAsUser)`](#fn-specrunnercontainersecuritycontextwithrunasuser)
      * [`obj spec.runner.containerSecurityContext.appArmorProfile`](#obj-specrunnercontainersecuritycontextapparmorprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specrunnercontainersecuritycontextapparmorprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specrunnercontainersecuritycontextapparmorprofilewithtype)
      * [`obj spec.runner.containerSecurityContext.capabilities`](#obj-specrunnercontainersecuritycontextcapabilities)
        * [`fn withAdd(add)`](#fn-specrunnercontainersecuritycontextcapabilitieswithadd)
        * [`fn withAddMixin(add)`](#fn-specrunnercontainersecuritycontextcapabilitieswithaddmixin)
        * [`fn withDrop(drop)`](#fn-specrunnercontainersecuritycontextcapabilitieswithdrop)
        * [`fn withDropMixin(drop)`](#fn-specrunnercontainersecuritycontextcapabilitieswithdropmixin)
      * [`obj spec.runner.containerSecurityContext.seLinuxOptions`](#obj-specrunnercontainersecuritycontextselinuxoptions)
        * [`fn withLevel(level)`](#fn-specrunnercontainersecuritycontextselinuxoptionswithlevel)
        * [`fn withRole(role)`](#fn-specrunnercontainersecuritycontextselinuxoptionswithrole)
        * [`fn withType(type)`](#fn-specrunnercontainersecuritycontextselinuxoptionswithtype)
        * [`fn withUser(user)`](#fn-specrunnercontainersecuritycontextselinuxoptionswithuser)
      * [`obj spec.runner.containerSecurityContext.seccompProfile`](#obj-specrunnercontainersecuritycontextseccompprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specrunnercontainersecuritycontextseccompprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specrunnercontainersecuritycontextseccompprofilewithtype)
      * [`obj spec.runner.containerSecurityContext.windowsOptions`](#obj-specrunnercontainersecuritycontextwindowsoptions)
        * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specrunnercontainersecuritycontextwindowsoptionswithgmsacredentialspec)
        * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specrunnercontainersecuritycontextwindowsoptionswithgmsacredentialspecname)
        * [`fn withHostProcess(hostProcess)`](#fn-specrunnercontainersecuritycontextwindowsoptionswithhostprocess)
        * [`fn withRunAsUserName(runAsUserName)`](#fn-specrunnercontainersecuritycontextwindowsoptionswithrunasusername)
    * [`obj spec.runner.env`](#obj-specrunnerenv)
      * [`fn withName(name)`](#fn-specrunnerenvwithname)
      * [`fn withValue(value)`](#fn-specrunnerenvwithvalue)
      * [`obj spec.runner.env.valueFrom`](#obj-specrunnerenvvaluefrom)
        * [`obj spec.runner.env.valueFrom.configMapKeyRef`](#obj-specrunnerenvvaluefromconfigmapkeyref)
          * [`fn withKey(key)`](#fn-specrunnerenvvaluefromconfigmapkeyrefwithkey)
          * [`fn withName(name)`](#fn-specrunnerenvvaluefromconfigmapkeyrefwithname)
          * [`fn withOptional(optional)`](#fn-specrunnerenvvaluefromconfigmapkeyrefwithoptional)
        * [`obj spec.runner.env.valueFrom.fieldRef`](#obj-specrunnerenvvaluefromfieldref)
          * [`fn withApiVersion(apiVersion)`](#fn-specrunnerenvvaluefromfieldrefwithapiversion)
          * [`fn withFieldPath(fieldPath)`](#fn-specrunnerenvvaluefromfieldrefwithfieldpath)
        * [`obj spec.runner.env.valueFrom.resourceFieldRef`](#obj-specrunnerenvvaluefromresourcefieldref)
          * [`fn withContainerName(containerName)`](#fn-specrunnerenvvaluefromresourcefieldrefwithcontainername)
          * [`fn withDivisor(divisor)`](#fn-specrunnerenvvaluefromresourcefieldrefwithdivisor)
          * [`fn withResource(resource)`](#fn-specrunnerenvvaluefromresourcefieldrefwithresource)
        * [`obj spec.runner.env.valueFrom.secretKeyRef`](#obj-specrunnerenvvaluefromsecretkeyref)
          * [`fn withKey(key)`](#fn-specrunnerenvvaluefromsecretkeyrefwithkey)
          * [`fn withName(name)`](#fn-specrunnerenvvaluefromsecretkeyrefwithname)
          * [`fn withOptional(optional)`](#fn-specrunnerenvvaluefromsecretkeyrefwithoptional)
    * [`obj spec.runner.envFrom`](#obj-specrunnerenvfrom)
      * [`fn withPrefix(prefix)`](#fn-specrunnerenvfromwithprefix)
      * [`obj spec.runner.envFrom.configMapRef`](#obj-specrunnerenvfromconfigmapref)
        * [`fn withName(name)`](#fn-specrunnerenvfromconfigmaprefwithname)
        * [`fn withOptional(optional)`](#fn-specrunnerenvfromconfigmaprefwithoptional)
      * [`obj spec.runner.envFrom.secretRef`](#obj-specrunnerenvfromsecretref)
        * [`fn withName(name)`](#fn-specrunnerenvfromsecretrefwithname)
        * [`fn withOptional(optional)`](#fn-specrunnerenvfromsecretrefwithoptional)
    * [`obj spec.runner.imagePullSecrets`](#obj-specrunnerimagepullsecrets)
      * [`fn withName(name)`](#fn-specrunnerimagepullsecretswithname)
    * [`obj spec.runner.initContainers`](#obj-specrunnerinitcontainers)
      * [`fn withArgs(args)`](#fn-specrunnerinitcontainerswithargs)
      * [`fn withArgsMixin(args)`](#fn-specrunnerinitcontainerswithargsmixin)
      * [`fn withCommand(command)`](#fn-specrunnerinitcontainerswithcommand)
      * [`fn withCommandMixin(command)`](#fn-specrunnerinitcontainerswithcommandmixin)
      * [`fn withEnv(env)`](#fn-specrunnerinitcontainerswithenv)
      * [`fn withEnvFrom(envFrom)`](#fn-specrunnerinitcontainerswithenvfrom)
      * [`fn withEnvFromMixin(envFrom)`](#fn-specrunnerinitcontainerswithenvfrommixin)
      * [`fn withEnvMixin(env)`](#fn-specrunnerinitcontainerswithenvmixin)
      * [`fn withImage(image)`](#fn-specrunnerinitcontainerswithimage)
      * [`fn withName(name)`](#fn-specrunnerinitcontainerswithname)
      * [`fn withVolumeMounts(volumeMounts)`](#fn-specrunnerinitcontainerswithvolumemounts)
      * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specrunnerinitcontainerswithvolumemountsmixin)
      * [`fn withWorkingDir(workingDir)`](#fn-specrunnerinitcontainerswithworkingdir)
      * [`obj spec.runner.initContainers.env`](#obj-specrunnerinitcontainersenv)
        * [`fn withName(name)`](#fn-specrunnerinitcontainersenvwithname)
        * [`fn withValue(value)`](#fn-specrunnerinitcontainersenvwithvalue)
        * [`obj spec.runner.initContainers.env.valueFrom`](#obj-specrunnerinitcontainersenvvaluefrom)
          * [`obj spec.runner.initContainers.env.valueFrom.configMapKeyRef`](#obj-specrunnerinitcontainersenvvaluefromconfigmapkeyref)
            * [`fn withKey(key)`](#fn-specrunnerinitcontainersenvvaluefromconfigmapkeyrefwithkey)
            * [`fn withName(name)`](#fn-specrunnerinitcontainersenvvaluefromconfigmapkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-specrunnerinitcontainersenvvaluefromconfigmapkeyrefwithoptional)
          * [`obj spec.runner.initContainers.env.valueFrom.fieldRef`](#obj-specrunnerinitcontainersenvvaluefromfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-specrunnerinitcontainersenvvaluefromfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-specrunnerinitcontainersenvvaluefromfieldrefwithfieldpath)
          * [`obj spec.runner.initContainers.env.valueFrom.resourceFieldRef`](#obj-specrunnerinitcontainersenvvaluefromresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-specrunnerinitcontainersenvvaluefromresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-specrunnerinitcontainersenvvaluefromresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-specrunnerinitcontainersenvvaluefromresourcefieldrefwithresource)
          * [`obj spec.runner.initContainers.env.valueFrom.secretKeyRef`](#obj-specrunnerinitcontainersenvvaluefromsecretkeyref)
            * [`fn withKey(key)`](#fn-specrunnerinitcontainersenvvaluefromsecretkeyrefwithkey)
            * [`fn withName(name)`](#fn-specrunnerinitcontainersenvvaluefromsecretkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-specrunnerinitcontainersenvvaluefromsecretkeyrefwithoptional)
      * [`obj spec.runner.initContainers.envFrom`](#obj-specrunnerinitcontainersenvfrom)
        * [`fn withPrefix(prefix)`](#fn-specrunnerinitcontainersenvfromwithprefix)
        * [`obj spec.runner.initContainers.envFrom.configMapRef`](#obj-specrunnerinitcontainersenvfromconfigmapref)
          * [`fn withName(name)`](#fn-specrunnerinitcontainersenvfromconfigmaprefwithname)
          * [`fn withOptional(optional)`](#fn-specrunnerinitcontainersenvfromconfigmaprefwithoptional)
        * [`obj spec.runner.initContainers.envFrom.secretRef`](#obj-specrunnerinitcontainersenvfromsecretref)
          * [`fn withName(name)`](#fn-specrunnerinitcontainersenvfromsecretrefwithname)
          * [`fn withOptional(optional)`](#fn-specrunnerinitcontainersenvfromsecretrefwithoptional)
      * [`obj spec.runner.initContainers.volumeMounts`](#obj-specrunnerinitcontainersvolumemounts)
        * [`fn withMountPath(mountPath)`](#fn-specrunnerinitcontainersvolumemountswithmountpath)
        * [`fn withMountPropagation(mountPropagation)`](#fn-specrunnerinitcontainersvolumemountswithmountpropagation)
        * [`fn withName(name)`](#fn-specrunnerinitcontainersvolumemountswithname)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnerinitcontainersvolumemountswithreadonly)
        * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specrunnerinitcontainersvolumemountswithrecursivereadonly)
        * [`fn withSubPath(subPath)`](#fn-specrunnerinitcontainersvolumemountswithsubpath)
        * [`fn withSubPathExpr(subPathExpr)`](#fn-specrunnerinitcontainersvolumemountswithsubpathexpr)
    * [`obj spec.runner.livenessProbe`](#obj-specrunnerlivenessprobe)
      * [`fn withFailureThreshold(failureThreshold)`](#fn-specrunnerlivenessprobewithfailurethreshold)
      * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specrunnerlivenessprobewithinitialdelayseconds)
      * [`fn withPeriodSeconds(periodSeconds)`](#fn-specrunnerlivenessprobewithperiodseconds)
      * [`fn withSuccessThreshold(successThreshold)`](#fn-specrunnerlivenessprobewithsuccessthreshold)
      * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specrunnerlivenessprobewithterminationgraceperiodseconds)
      * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specrunnerlivenessprobewithtimeoutseconds)
      * [`obj spec.runner.livenessProbe.exec`](#obj-specrunnerlivenessprobeexec)
        * [`fn withCommand(command)`](#fn-specrunnerlivenessprobeexecwithcommand)
        * [`fn withCommandMixin(command)`](#fn-specrunnerlivenessprobeexecwithcommandmixin)
      * [`obj spec.runner.livenessProbe.grpc`](#obj-specrunnerlivenessprobegrpc)
        * [`fn withPort(port)`](#fn-specrunnerlivenessprobegrpcwithport)
        * [`fn withService(service)`](#fn-specrunnerlivenessprobegrpcwithservice)
      * [`obj spec.runner.livenessProbe.httpGet`](#obj-specrunnerlivenessprobehttpget)
        * [`fn withHost(host)`](#fn-specrunnerlivenessprobehttpgetwithhost)
        * [`fn withHttpHeaders(httpHeaders)`](#fn-specrunnerlivenessprobehttpgetwithhttpheaders)
        * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specrunnerlivenessprobehttpgetwithhttpheadersmixin)
        * [`fn withPath(path)`](#fn-specrunnerlivenessprobehttpgetwithpath)
        * [`fn withPort(port)`](#fn-specrunnerlivenessprobehttpgetwithport)
        * [`fn withScheme(scheme)`](#fn-specrunnerlivenessprobehttpgetwithscheme)
        * [`obj spec.runner.livenessProbe.httpGet.httpHeaders`](#obj-specrunnerlivenessprobehttpgethttpheaders)
          * [`fn withName(name)`](#fn-specrunnerlivenessprobehttpgethttpheaderswithname)
          * [`fn withValue(value)`](#fn-specrunnerlivenessprobehttpgethttpheaderswithvalue)
      * [`obj spec.runner.livenessProbe.tcpSocket`](#obj-specrunnerlivenessprobetcpsocket)
        * [`fn withHost(host)`](#fn-specrunnerlivenessprobetcpsocketwithhost)
        * [`fn withPort(port)`](#fn-specrunnerlivenessprobetcpsocketwithport)
    * [`obj spec.runner.metadata`](#obj-specrunnermetadata)
      * [`fn withAnnotations(annotations)`](#fn-specrunnermetadatawithannotations)
      * [`fn withAnnotationsMixin(annotations)`](#fn-specrunnermetadatawithannotationsmixin)
      * [`fn withLabels(labels)`](#fn-specrunnermetadatawithlabels)
      * [`fn withLabelsMixin(labels)`](#fn-specrunnermetadatawithlabelsmixin)
    * [`obj spec.runner.readinessProbe`](#obj-specrunnerreadinessprobe)
      * [`fn withFailureThreshold(failureThreshold)`](#fn-specrunnerreadinessprobewithfailurethreshold)
      * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specrunnerreadinessprobewithinitialdelayseconds)
      * [`fn withPeriodSeconds(periodSeconds)`](#fn-specrunnerreadinessprobewithperiodseconds)
      * [`fn withSuccessThreshold(successThreshold)`](#fn-specrunnerreadinessprobewithsuccessthreshold)
      * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specrunnerreadinessprobewithterminationgraceperiodseconds)
      * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specrunnerreadinessprobewithtimeoutseconds)
      * [`obj spec.runner.readinessProbe.exec`](#obj-specrunnerreadinessprobeexec)
        * [`fn withCommand(command)`](#fn-specrunnerreadinessprobeexecwithcommand)
        * [`fn withCommandMixin(command)`](#fn-specrunnerreadinessprobeexecwithcommandmixin)
      * [`obj spec.runner.readinessProbe.grpc`](#obj-specrunnerreadinessprobegrpc)
        * [`fn withPort(port)`](#fn-specrunnerreadinessprobegrpcwithport)
        * [`fn withService(service)`](#fn-specrunnerreadinessprobegrpcwithservice)
      * [`obj spec.runner.readinessProbe.httpGet`](#obj-specrunnerreadinessprobehttpget)
        * [`fn withHost(host)`](#fn-specrunnerreadinessprobehttpgetwithhost)
        * [`fn withHttpHeaders(httpHeaders)`](#fn-specrunnerreadinessprobehttpgetwithhttpheaders)
        * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specrunnerreadinessprobehttpgetwithhttpheadersmixin)
        * [`fn withPath(path)`](#fn-specrunnerreadinessprobehttpgetwithpath)
        * [`fn withPort(port)`](#fn-specrunnerreadinessprobehttpgetwithport)
        * [`fn withScheme(scheme)`](#fn-specrunnerreadinessprobehttpgetwithscheme)
        * [`obj spec.runner.readinessProbe.httpGet.httpHeaders`](#obj-specrunnerreadinessprobehttpgethttpheaders)
          * [`fn withName(name)`](#fn-specrunnerreadinessprobehttpgethttpheaderswithname)
          * [`fn withValue(value)`](#fn-specrunnerreadinessprobehttpgethttpheaderswithvalue)
      * [`obj spec.runner.readinessProbe.tcpSocket`](#obj-specrunnerreadinessprobetcpsocket)
        * [`fn withHost(host)`](#fn-specrunnerreadinessprobetcpsocketwithhost)
        * [`fn withPort(port)`](#fn-specrunnerreadinessprobetcpsocketwithport)
    * [`obj spec.runner.resources`](#obj-specrunnerresources)
      * [`fn withClaims(claims)`](#fn-specrunnerresourceswithclaims)
      * [`fn withClaimsMixin(claims)`](#fn-specrunnerresourceswithclaimsmixin)
      * [`fn withLimits(limits)`](#fn-specrunnerresourceswithlimits)
      * [`fn withLimitsMixin(limits)`](#fn-specrunnerresourceswithlimitsmixin)
      * [`fn withRequests(requests)`](#fn-specrunnerresourceswithrequests)
      * [`fn withRequestsMixin(requests)`](#fn-specrunnerresourceswithrequestsmixin)
      * [`obj spec.runner.resources.claims`](#obj-specrunnerresourcesclaims)
        * [`fn withName(name)`](#fn-specrunnerresourcesclaimswithname)
        * [`fn withRequest(request)`](#fn-specrunnerresourcesclaimswithrequest)
    * [`obj spec.runner.securityContext`](#obj-specrunnersecuritycontext)
      * [`fn withFsGroup(fsGroup)`](#fn-specrunnersecuritycontextwithfsgroup)
      * [`fn withFsGroupChangePolicy(fsGroupChangePolicy)`](#fn-specrunnersecuritycontextwithfsgroupchangepolicy)
      * [`fn withRunAsGroup(runAsGroup)`](#fn-specrunnersecuritycontextwithrunasgroup)
      * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specrunnersecuritycontextwithrunasnonroot)
      * [`fn withRunAsUser(runAsUser)`](#fn-specrunnersecuritycontextwithrunasuser)
      * [`fn withSupplementalGroups(supplementalGroups)`](#fn-specrunnersecuritycontextwithsupplementalgroups)
      * [`fn withSupplementalGroupsMixin(supplementalGroups)`](#fn-specrunnersecuritycontextwithsupplementalgroupsmixin)
      * [`fn withSupplementalGroupsPolicy(supplementalGroupsPolicy)`](#fn-specrunnersecuritycontextwithsupplementalgroupspolicy)
      * [`fn withSysctls(sysctls)`](#fn-specrunnersecuritycontextwithsysctls)
      * [`fn withSysctlsMixin(sysctls)`](#fn-specrunnersecuritycontextwithsysctlsmixin)
      * [`obj spec.runner.securityContext.appArmorProfile`](#obj-specrunnersecuritycontextapparmorprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specrunnersecuritycontextapparmorprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specrunnersecuritycontextapparmorprofilewithtype)
      * [`obj spec.runner.securityContext.seLinuxOptions`](#obj-specrunnersecuritycontextselinuxoptions)
        * [`fn withLevel(level)`](#fn-specrunnersecuritycontextselinuxoptionswithlevel)
        * [`fn withRole(role)`](#fn-specrunnersecuritycontextselinuxoptionswithrole)
        * [`fn withType(type)`](#fn-specrunnersecuritycontextselinuxoptionswithtype)
        * [`fn withUser(user)`](#fn-specrunnersecuritycontextselinuxoptionswithuser)
      * [`obj spec.runner.securityContext.seccompProfile`](#obj-specrunnersecuritycontextseccompprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specrunnersecuritycontextseccompprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specrunnersecuritycontextseccompprofilewithtype)
      * [`obj spec.runner.securityContext.sysctls`](#obj-specrunnersecuritycontextsysctls)
        * [`fn withName(name)`](#fn-specrunnersecuritycontextsysctlswithname)
        * [`fn withValue(value)`](#fn-specrunnersecuritycontextsysctlswithvalue)
      * [`obj spec.runner.securityContext.windowsOptions`](#obj-specrunnersecuritycontextwindowsoptions)
        * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specrunnersecuritycontextwindowsoptionswithgmsacredentialspec)
        * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specrunnersecuritycontextwindowsoptionswithgmsacredentialspecname)
        * [`fn withHostProcess(hostProcess)`](#fn-specrunnersecuritycontextwindowsoptionswithhostprocess)
        * [`fn withRunAsUserName(runAsUserName)`](#fn-specrunnersecuritycontextwindowsoptionswithrunasusername)
    * [`obj spec.runner.tolerations`](#obj-specrunnertolerations)
      * [`fn withEffect(effect)`](#fn-specrunnertolerationswitheffect)
      * [`fn withKey(key)`](#fn-specrunnertolerationswithkey)
      * [`fn withOperator(operator)`](#fn-specrunnertolerationswithoperator)
      * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-specrunnertolerationswithtolerationseconds)
      * [`fn withValue(value)`](#fn-specrunnertolerationswithvalue)
    * [`obj spec.runner.topologySpreadConstraints`](#obj-specrunnertopologyspreadconstraints)
      * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specrunnertopologyspreadconstraintswithmatchlabelkeys)
      * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specrunnertopologyspreadconstraintswithmatchlabelkeysmixin)
      * [`fn withMaxSkew(maxSkew)`](#fn-specrunnertopologyspreadconstraintswithmaxskew)
      * [`fn withMinDomains(minDomains)`](#fn-specrunnertopologyspreadconstraintswithmindomains)
      * [`fn withNodeAffinityPolicy(nodeAffinityPolicy)`](#fn-specrunnertopologyspreadconstraintswithnodeaffinitypolicy)
      * [`fn withNodeTaintsPolicy(nodeTaintsPolicy)`](#fn-specrunnertopologyspreadconstraintswithnodetaintspolicy)
      * [`fn withTopologyKey(topologyKey)`](#fn-specrunnertopologyspreadconstraintswithtopologykey)
      * [`fn withWhenUnsatisfiable(whenUnsatisfiable)`](#fn-specrunnertopologyspreadconstraintswithwhenunsatisfiable)
      * [`obj spec.runner.topologySpreadConstraints.labelSelector`](#obj-specrunnertopologyspreadconstraintslabelselector)
        * [`fn withMatchExpressions(matchExpressions)`](#fn-specrunnertopologyspreadconstraintslabelselectorwithmatchexpressions)
        * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specrunnertopologyspreadconstraintslabelselectorwithmatchexpressionsmixin)
        * [`fn withMatchLabels(matchLabels)`](#fn-specrunnertopologyspreadconstraintslabelselectorwithmatchlabels)
        * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specrunnertopologyspreadconstraintslabelselectorwithmatchlabelsmixin)
        * [`obj spec.runner.topologySpreadConstraints.labelSelector.matchExpressions`](#obj-specrunnertopologyspreadconstraintslabelselectormatchexpressions)
          * [`fn withKey(key)`](#fn-specrunnertopologyspreadconstraintslabelselectormatchexpressionswithkey)
          * [`fn withOperator(operator)`](#fn-specrunnertopologyspreadconstraintslabelselectormatchexpressionswithoperator)
          * [`fn withValues(values)`](#fn-specrunnertopologyspreadconstraintslabelselectormatchexpressionswithvalues)
          * [`fn withValuesMixin(values)`](#fn-specrunnertopologyspreadconstraintslabelselectormatchexpressionswithvaluesmixin)
    * [`obj spec.runner.volumeMounts`](#obj-specrunnervolumemounts)
      * [`fn withMountPath(mountPath)`](#fn-specrunnervolumemountswithmountpath)
      * [`fn withMountPropagation(mountPropagation)`](#fn-specrunnervolumemountswithmountpropagation)
      * [`fn withName(name)`](#fn-specrunnervolumemountswithname)
      * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumemountswithreadonly)
      * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specrunnervolumemountswithrecursivereadonly)
      * [`fn withSubPath(subPath)`](#fn-specrunnervolumemountswithsubpath)
      * [`fn withSubPathExpr(subPathExpr)`](#fn-specrunnervolumemountswithsubpathexpr)
    * [`obj spec.runner.volumes`](#obj-specrunnervolumes)
      * [`fn withName(name)`](#fn-specrunnervolumeswithname)
      * [`obj spec.runner.volumes.awsElasticBlockStore`](#obj-specrunnervolumesawselasticblockstore)
        * [`fn withFsType(fsType)`](#fn-specrunnervolumesawselasticblockstorewithfstype)
        * [`fn withPartition(partition)`](#fn-specrunnervolumesawselasticblockstorewithpartition)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumesawselasticblockstorewithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-specrunnervolumesawselasticblockstorewithvolumeid)
      * [`obj spec.runner.volumes.azureDisk`](#obj-specrunnervolumesazuredisk)
        * [`fn withCachingMode(cachingMode)`](#fn-specrunnervolumesazurediskwithcachingmode)
        * [`fn withDiskName(diskName)`](#fn-specrunnervolumesazurediskwithdiskname)
        * [`fn withDiskURI(diskURI)`](#fn-specrunnervolumesazurediskwithdiskuri)
        * [`fn withFsType(fsType)`](#fn-specrunnervolumesazurediskwithfstype)
        * [`fn withKind(kind)`](#fn-specrunnervolumesazurediskwithkind)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumesazurediskwithreadonly)
      * [`obj spec.runner.volumes.azureFile`](#obj-specrunnervolumesazurefile)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumesazurefilewithreadonly)
        * [`fn withSecretName(secretName)`](#fn-specrunnervolumesazurefilewithsecretname)
        * [`fn withShareName(shareName)`](#fn-specrunnervolumesazurefilewithsharename)
      * [`obj spec.runner.volumes.cephfs`](#obj-specrunnervolumescephfs)
        * [`fn withMonitors(monitors)`](#fn-specrunnervolumescephfswithmonitors)
        * [`fn withMonitorsMixin(monitors)`](#fn-specrunnervolumescephfswithmonitorsmixin)
        * [`fn withPath(path)`](#fn-specrunnervolumescephfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumescephfswithreadonly)
        * [`fn withSecretFile(secretFile)`](#fn-specrunnervolumescephfswithsecretfile)
        * [`fn withUser(user)`](#fn-specrunnervolumescephfswithuser)
        * [`obj spec.runner.volumes.cephfs.secretRef`](#obj-specrunnervolumescephfssecretref)
          * [`fn withName(name)`](#fn-specrunnervolumescephfssecretrefwithname)
      * [`obj spec.runner.volumes.cinder`](#obj-specrunnervolumescinder)
        * [`fn withFsType(fsType)`](#fn-specrunnervolumescinderwithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumescinderwithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-specrunnervolumescinderwithvolumeid)
        * [`obj spec.runner.volumes.cinder.secretRef`](#obj-specrunnervolumescindersecretref)
          * [`fn withName(name)`](#fn-specrunnervolumescindersecretrefwithname)
      * [`obj spec.runner.volumes.configMap`](#obj-specrunnervolumesconfigmap)
        * [`fn withDefaultMode(defaultMode)`](#fn-specrunnervolumesconfigmapwithdefaultmode)
        * [`fn withItems(items)`](#fn-specrunnervolumesconfigmapwithitems)
        * [`fn withItemsMixin(items)`](#fn-specrunnervolumesconfigmapwithitemsmixin)
        * [`fn withName(name)`](#fn-specrunnervolumesconfigmapwithname)
        * [`fn withOptional(optional)`](#fn-specrunnervolumesconfigmapwithoptional)
        * [`obj spec.runner.volumes.configMap.items`](#obj-specrunnervolumesconfigmapitems)
          * [`fn withKey(key)`](#fn-specrunnervolumesconfigmapitemswithkey)
          * [`fn withMode(mode)`](#fn-specrunnervolumesconfigmapitemswithmode)
          * [`fn withPath(path)`](#fn-specrunnervolumesconfigmapitemswithpath)
      * [`obj spec.runner.volumes.csi`](#obj-specrunnervolumescsi)
        * [`fn withDriver(driver)`](#fn-specrunnervolumescsiwithdriver)
        * [`fn withFsType(fsType)`](#fn-specrunnervolumescsiwithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumescsiwithreadonly)
        * [`fn withVolumeAttributes(volumeAttributes)`](#fn-specrunnervolumescsiwithvolumeattributes)
        * [`fn withVolumeAttributesMixin(volumeAttributes)`](#fn-specrunnervolumescsiwithvolumeattributesmixin)
        * [`obj spec.runner.volumes.csi.nodePublishSecretRef`](#obj-specrunnervolumescsinodepublishsecretref)
          * [`fn withName(name)`](#fn-specrunnervolumescsinodepublishsecretrefwithname)
      * [`obj spec.runner.volumes.downwardAPI`](#obj-specrunnervolumesdownwardapi)
        * [`fn withDefaultMode(defaultMode)`](#fn-specrunnervolumesdownwardapiwithdefaultmode)
        * [`fn withItems(items)`](#fn-specrunnervolumesdownwardapiwithitems)
        * [`fn withItemsMixin(items)`](#fn-specrunnervolumesdownwardapiwithitemsmixin)
        * [`obj spec.runner.volumes.downwardAPI.items`](#obj-specrunnervolumesdownwardapiitems)
          * [`fn withMode(mode)`](#fn-specrunnervolumesdownwardapiitemswithmode)
          * [`fn withPath(path)`](#fn-specrunnervolumesdownwardapiitemswithpath)
          * [`obj spec.runner.volumes.downwardAPI.items.fieldRef`](#obj-specrunnervolumesdownwardapiitemsfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-specrunnervolumesdownwardapiitemsfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-specrunnervolumesdownwardapiitemsfieldrefwithfieldpath)
          * [`obj spec.runner.volumes.downwardAPI.items.resourceFieldRef`](#obj-specrunnervolumesdownwardapiitemsresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-specrunnervolumesdownwardapiitemsresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-specrunnervolumesdownwardapiitemsresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-specrunnervolumesdownwardapiitemsresourcefieldrefwithresource)
      * [`obj spec.runner.volumes.emptyDir`](#obj-specrunnervolumesemptydir)
        * [`fn withMedium(medium)`](#fn-specrunnervolumesemptydirwithmedium)
        * [`fn withSizeLimit(sizeLimit)`](#fn-specrunnervolumesemptydirwithsizelimit)
      * [`obj spec.runner.volumes.ephemeral`](#obj-specrunnervolumesephemeral)
        * [`obj spec.runner.volumes.ephemeral.volumeClaimTemplate`](#obj-specrunnervolumesephemeralvolumeclaimtemplate)
          * [`fn withMetadata(metadata)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatewithmetadata)
          * [`fn withMetadataMixin(metadata)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatewithmetadatamixin)
          * [`obj spec.runner.volumes.ephemeral.volumeClaimTemplate.spec`](#obj-specrunnervolumesephemeralvolumeclaimtemplatespec)
            * [`fn withAccessModes(accessModes)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecwithaccessmodes)
            * [`fn withAccessModesMixin(accessModes)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecwithaccessmodesmixin)
            * [`fn withStorageClassName(storageClassName)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecwithstorageclassname)
            * [`fn withVolumeAttributesClassName(volumeAttributesClassName)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecwithvolumeattributesclassname)
            * [`fn withVolumeMode(volumeMode)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecwithvolumemode)
            * [`fn withVolumeName(volumeName)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecwithvolumename)
            * [`obj spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.dataSource`](#obj-specrunnervolumesephemeralvolumeclaimtemplatespecdatasource)
              * [`fn withApiGroup(apiGroup)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecdatasourcewithapigroup)
              * [`fn withKind(kind)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecdatasourcewithkind)
              * [`fn withName(name)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecdatasourcewithname)
            * [`obj spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef`](#obj-specrunnervolumesephemeralvolumeclaimtemplatespecdatasourceref)
              * [`fn withApiGroup(apiGroup)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecdatasourcerefwithapigroup)
              * [`fn withKind(kind)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecdatasourcerefwithkind)
              * [`fn withName(name)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecdatasourcerefwithname)
              * [`fn withNamespace(namespace)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecdatasourcerefwithnamespace)
            * [`obj spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.resources`](#obj-specrunnervolumesephemeralvolumeclaimtemplatespecresources)
              * [`fn withLimits(limits)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecresourceswithlimits)
              * [`fn withLimitsMixin(limits)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecresourceswithlimitsmixin)
              * [`fn withRequests(requests)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecresourceswithrequests)
              * [`fn withRequestsMixin(requests)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecresourceswithrequestsmixin)
            * [`obj spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.selector`](#obj-specrunnervolumesephemeralvolumeclaimtemplatespecselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabelsmixin)
              * [`obj spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions`](#obj-specrunnervolumesephemeralvolumeclaimtemplatespecselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specrunnervolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvaluesmixin)
      * [`obj spec.runner.volumes.fc`](#obj-specrunnervolumesfc)
        * [`fn withFsType(fsType)`](#fn-specrunnervolumesfcwithfstype)
        * [`fn withLun(lun)`](#fn-specrunnervolumesfcwithlun)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumesfcwithreadonly)
        * [`fn withTargetWWNs(targetWWNs)`](#fn-specrunnervolumesfcwithtargetwwns)
        * [`fn withTargetWWNsMixin(targetWWNs)`](#fn-specrunnervolumesfcwithtargetwwnsmixin)
        * [`fn withWwids(wwids)`](#fn-specrunnervolumesfcwithwwids)
        * [`fn withWwidsMixin(wwids)`](#fn-specrunnervolumesfcwithwwidsmixin)
      * [`obj spec.runner.volumes.flexVolume`](#obj-specrunnervolumesflexvolume)
        * [`fn withDriver(driver)`](#fn-specrunnervolumesflexvolumewithdriver)
        * [`fn withFsType(fsType)`](#fn-specrunnervolumesflexvolumewithfstype)
        * [`fn withOptions(options)`](#fn-specrunnervolumesflexvolumewithoptions)
        * [`fn withOptionsMixin(options)`](#fn-specrunnervolumesflexvolumewithoptionsmixin)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumesflexvolumewithreadonly)
        * [`obj spec.runner.volumes.flexVolume.secretRef`](#obj-specrunnervolumesflexvolumesecretref)
          * [`fn withName(name)`](#fn-specrunnervolumesflexvolumesecretrefwithname)
      * [`obj spec.runner.volumes.flocker`](#obj-specrunnervolumesflocker)
        * [`fn withDatasetName(datasetName)`](#fn-specrunnervolumesflockerwithdatasetname)
        * [`fn withDatasetUUID(datasetUUID)`](#fn-specrunnervolumesflockerwithdatasetuuid)
      * [`obj spec.runner.volumes.gcePersistentDisk`](#obj-specrunnervolumesgcepersistentdisk)
        * [`fn withFsType(fsType)`](#fn-specrunnervolumesgcepersistentdiskwithfstype)
        * [`fn withPartition(partition)`](#fn-specrunnervolumesgcepersistentdiskwithpartition)
        * [`fn withPdName(pdName)`](#fn-specrunnervolumesgcepersistentdiskwithpdname)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumesgcepersistentdiskwithreadonly)
      * [`obj spec.runner.volumes.gitRepo`](#obj-specrunnervolumesgitrepo)
        * [`fn withDirectory(directory)`](#fn-specrunnervolumesgitrepowithdirectory)
        * [`fn withRepository(repository)`](#fn-specrunnervolumesgitrepowithrepository)
        * [`fn withRevision(revision)`](#fn-specrunnervolumesgitrepowithrevision)
      * [`obj spec.runner.volumes.glusterfs`](#obj-specrunnervolumesglusterfs)
        * [`fn withEndpoints(endpoints)`](#fn-specrunnervolumesglusterfswithendpoints)
        * [`fn withPath(path)`](#fn-specrunnervolumesglusterfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumesglusterfswithreadonly)
      * [`obj spec.runner.volumes.hostPath`](#obj-specrunnervolumeshostpath)
        * [`fn withPath(path)`](#fn-specrunnervolumeshostpathwithpath)
        * [`fn withType(type)`](#fn-specrunnervolumeshostpathwithtype)
      * [`obj spec.runner.volumes.image`](#obj-specrunnervolumesimage)
        * [`fn withPullPolicy(pullPolicy)`](#fn-specrunnervolumesimagewithpullpolicy)
        * [`fn withReference(reference)`](#fn-specrunnervolumesimagewithreference)
      * [`obj spec.runner.volumes.iscsi`](#obj-specrunnervolumesiscsi)
        * [`fn withChapAuthDiscovery(chapAuthDiscovery)`](#fn-specrunnervolumesiscsiwithchapauthdiscovery)
        * [`fn withChapAuthSession(chapAuthSession)`](#fn-specrunnervolumesiscsiwithchapauthsession)
        * [`fn withFsType(fsType)`](#fn-specrunnervolumesiscsiwithfstype)
        * [`fn withInitiatorName(initiatorName)`](#fn-specrunnervolumesiscsiwithinitiatorname)
        * [`fn withIqn(iqn)`](#fn-specrunnervolumesiscsiwithiqn)
        * [`fn withIscsiInterface(iscsiInterface)`](#fn-specrunnervolumesiscsiwithiscsiinterface)
        * [`fn withLun(lun)`](#fn-specrunnervolumesiscsiwithlun)
        * [`fn withPortals(portals)`](#fn-specrunnervolumesiscsiwithportals)
        * [`fn withPortalsMixin(portals)`](#fn-specrunnervolumesiscsiwithportalsmixin)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumesiscsiwithreadonly)
        * [`fn withTargetPortal(targetPortal)`](#fn-specrunnervolumesiscsiwithtargetportal)
        * [`obj spec.runner.volumes.iscsi.secretRef`](#obj-specrunnervolumesiscsisecretref)
          * [`fn withName(name)`](#fn-specrunnervolumesiscsisecretrefwithname)
      * [`obj spec.runner.volumes.nfs`](#obj-specrunnervolumesnfs)
        * [`fn withPath(path)`](#fn-specrunnervolumesnfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumesnfswithreadonly)
        * [`fn withServer(server)`](#fn-specrunnervolumesnfswithserver)
      * [`obj spec.runner.volumes.persistentVolumeClaim`](#obj-specrunnervolumespersistentvolumeclaim)
        * [`fn withClaimName(claimName)`](#fn-specrunnervolumespersistentvolumeclaimwithclaimname)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumespersistentvolumeclaimwithreadonly)
      * [`obj spec.runner.volumes.photonPersistentDisk`](#obj-specrunnervolumesphotonpersistentdisk)
        * [`fn withFsType(fsType)`](#fn-specrunnervolumesphotonpersistentdiskwithfstype)
        * [`fn withPdID(pdID)`](#fn-specrunnervolumesphotonpersistentdiskwithpdid)
      * [`obj spec.runner.volumes.portworxVolume`](#obj-specrunnervolumesportworxvolume)
        * [`fn withFsType(fsType)`](#fn-specrunnervolumesportworxvolumewithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumesportworxvolumewithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-specrunnervolumesportworxvolumewithvolumeid)
      * [`obj spec.runner.volumes.projected`](#obj-specrunnervolumesprojected)
        * [`fn withDefaultMode(defaultMode)`](#fn-specrunnervolumesprojectedwithdefaultmode)
        * [`fn withSources(sources)`](#fn-specrunnervolumesprojectedwithsources)
        * [`fn withSourcesMixin(sources)`](#fn-specrunnervolumesprojectedwithsourcesmixin)
        * [`obj spec.runner.volumes.projected.sources`](#obj-specrunnervolumesprojectedsources)
          * [`obj spec.runner.volumes.projected.sources.clusterTrustBundle`](#obj-specrunnervolumesprojectedsourcesclustertrustbundle)
            * [`fn withName(name)`](#fn-specrunnervolumesprojectedsourcesclustertrustbundlewithname)
            * [`fn withOptional(optional)`](#fn-specrunnervolumesprojectedsourcesclustertrustbundlewithoptional)
            * [`fn withPath(path)`](#fn-specrunnervolumesprojectedsourcesclustertrustbundlewithpath)
            * [`fn withSignerName(signerName)`](#fn-specrunnervolumesprojectedsourcesclustertrustbundlewithsignername)
            * [`obj spec.runner.volumes.projected.sources.clusterTrustBundle.labelSelector`](#obj-specrunnervolumesprojectedsourcesclustertrustbundlelabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specrunnervolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specrunnervolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specrunnervolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specrunnervolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabelsmixin)
              * [`obj spec.runner.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions`](#obj-specrunnervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specrunnervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specrunnervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specrunnervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specrunnervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.runner.volumes.projected.sources.configMap`](#obj-specrunnervolumesprojectedsourcesconfigmap)
            * [`fn withItems(items)`](#fn-specrunnervolumesprojectedsourcesconfigmapwithitems)
            * [`fn withItemsMixin(items)`](#fn-specrunnervolumesprojectedsourcesconfigmapwithitemsmixin)
            * [`fn withName(name)`](#fn-specrunnervolumesprojectedsourcesconfigmapwithname)
            * [`fn withOptional(optional)`](#fn-specrunnervolumesprojectedsourcesconfigmapwithoptional)
            * [`obj spec.runner.volumes.projected.sources.configMap.items`](#obj-specrunnervolumesprojectedsourcesconfigmapitems)
              * [`fn withKey(key)`](#fn-specrunnervolumesprojectedsourcesconfigmapitemswithkey)
              * [`fn withMode(mode)`](#fn-specrunnervolumesprojectedsourcesconfigmapitemswithmode)
              * [`fn withPath(path)`](#fn-specrunnervolumesprojectedsourcesconfigmapitemswithpath)
          * [`obj spec.runner.volumes.projected.sources.downwardAPI`](#obj-specrunnervolumesprojectedsourcesdownwardapi)
            * [`fn withItems(items)`](#fn-specrunnervolumesprojectedsourcesdownwardapiwithitems)
            * [`fn withItemsMixin(items)`](#fn-specrunnervolumesprojectedsourcesdownwardapiwithitemsmixin)
            * [`obj spec.runner.volumes.projected.sources.downwardAPI.items`](#obj-specrunnervolumesprojectedsourcesdownwardapiitems)
              * [`fn withMode(mode)`](#fn-specrunnervolumesprojectedsourcesdownwardapiitemswithmode)
              * [`fn withPath(path)`](#fn-specrunnervolumesprojectedsourcesdownwardapiitemswithpath)
              * [`obj spec.runner.volumes.projected.sources.downwardAPI.items.fieldRef`](#obj-specrunnervolumesprojectedsourcesdownwardapiitemsfieldref)
                * [`fn withApiVersion(apiVersion)`](#fn-specrunnervolumesprojectedsourcesdownwardapiitemsfieldrefwithapiversion)
                * [`fn withFieldPath(fieldPath)`](#fn-specrunnervolumesprojectedsourcesdownwardapiitemsfieldrefwithfieldpath)
              * [`obj spec.runner.volumes.projected.sources.downwardAPI.items.resourceFieldRef`](#obj-specrunnervolumesprojectedsourcesdownwardapiitemsresourcefieldref)
                * [`fn withContainerName(containerName)`](#fn-specrunnervolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithcontainername)
                * [`fn withDivisor(divisor)`](#fn-specrunnervolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithdivisor)
                * [`fn withResource(resource)`](#fn-specrunnervolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithresource)
          * [`obj spec.runner.volumes.projected.sources.secret`](#obj-specrunnervolumesprojectedsourcessecret)
            * [`fn withItems(items)`](#fn-specrunnervolumesprojectedsourcessecretwithitems)
            * [`fn withItemsMixin(items)`](#fn-specrunnervolumesprojectedsourcessecretwithitemsmixin)
            * [`fn withName(name)`](#fn-specrunnervolumesprojectedsourcessecretwithname)
            * [`fn withOptional(optional)`](#fn-specrunnervolumesprojectedsourcessecretwithoptional)
            * [`obj spec.runner.volumes.projected.sources.secret.items`](#obj-specrunnervolumesprojectedsourcessecretitems)
              * [`fn withKey(key)`](#fn-specrunnervolumesprojectedsourcessecretitemswithkey)
              * [`fn withMode(mode)`](#fn-specrunnervolumesprojectedsourcessecretitemswithmode)
              * [`fn withPath(path)`](#fn-specrunnervolumesprojectedsourcessecretitemswithpath)
          * [`obj spec.runner.volumes.projected.sources.serviceAccountToken`](#obj-specrunnervolumesprojectedsourcesserviceaccounttoken)
            * [`fn withAudience(audience)`](#fn-specrunnervolumesprojectedsourcesserviceaccounttokenwithaudience)
            * [`fn withExpirationSeconds(expirationSeconds)`](#fn-specrunnervolumesprojectedsourcesserviceaccounttokenwithexpirationseconds)
            * [`fn withPath(path)`](#fn-specrunnervolumesprojectedsourcesserviceaccounttokenwithpath)
      * [`obj spec.runner.volumes.quobyte`](#obj-specrunnervolumesquobyte)
        * [`fn withGroup(group)`](#fn-specrunnervolumesquobytewithgroup)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumesquobytewithreadonly)
        * [`fn withRegistry(registry)`](#fn-specrunnervolumesquobytewithregistry)
        * [`fn withTenant(tenant)`](#fn-specrunnervolumesquobytewithtenant)
        * [`fn withUser(user)`](#fn-specrunnervolumesquobytewithuser)
        * [`fn withVolume(volume)`](#fn-specrunnervolumesquobytewithvolume)
      * [`obj spec.runner.volumes.rbd`](#obj-specrunnervolumesrbd)
        * [`fn withFsType(fsType)`](#fn-specrunnervolumesrbdwithfstype)
        * [`fn withImage(image)`](#fn-specrunnervolumesrbdwithimage)
        * [`fn withKeyring(keyring)`](#fn-specrunnervolumesrbdwithkeyring)
        * [`fn withMonitors(monitors)`](#fn-specrunnervolumesrbdwithmonitors)
        * [`fn withMonitorsMixin(monitors)`](#fn-specrunnervolumesrbdwithmonitorsmixin)
        * [`fn withPool(pool)`](#fn-specrunnervolumesrbdwithpool)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumesrbdwithreadonly)
        * [`fn withUser(user)`](#fn-specrunnervolumesrbdwithuser)
        * [`obj spec.runner.volumes.rbd.secretRef`](#obj-specrunnervolumesrbdsecretref)
          * [`fn withName(name)`](#fn-specrunnervolumesrbdsecretrefwithname)
      * [`obj spec.runner.volumes.scaleIO`](#obj-specrunnervolumesscaleio)
        * [`fn withFsType(fsType)`](#fn-specrunnervolumesscaleiowithfstype)
        * [`fn withGateway(gateway)`](#fn-specrunnervolumesscaleiowithgateway)
        * [`fn withProtectionDomain(protectionDomain)`](#fn-specrunnervolumesscaleiowithprotectiondomain)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumesscaleiowithreadonly)
        * [`fn withSslEnabled(sslEnabled)`](#fn-specrunnervolumesscaleiowithsslenabled)
        * [`fn withStorageMode(storageMode)`](#fn-specrunnervolumesscaleiowithstoragemode)
        * [`fn withStoragePool(storagePool)`](#fn-specrunnervolumesscaleiowithstoragepool)
        * [`fn withSystem(system)`](#fn-specrunnervolumesscaleiowithsystem)
        * [`fn withVolumeName(volumeName)`](#fn-specrunnervolumesscaleiowithvolumename)
        * [`obj spec.runner.volumes.scaleIO.secretRef`](#obj-specrunnervolumesscaleiosecretref)
          * [`fn withName(name)`](#fn-specrunnervolumesscaleiosecretrefwithname)
      * [`obj spec.runner.volumes.secret`](#obj-specrunnervolumessecret)
        * [`fn withDefaultMode(defaultMode)`](#fn-specrunnervolumessecretwithdefaultmode)
        * [`fn withItems(items)`](#fn-specrunnervolumessecretwithitems)
        * [`fn withItemsMixin(items)`](#fn-specrunnervolumessecretwithitemsmixin)
        * [`fn withOptional(optional)`](#fn-specrunnervolumessecretwithoptional)
        * [`fn withSecretName(secretName)`](#fn-specrunnervolumessecretwithsecretname)
        * [`obj spec.runner.volumes.secret.items`](#obj-specrunnervolumessecretitems)
          * [`fn withKey(key)`](#fn-specrunnervolumessecretitemswithkey)
          * [`fn withMode(mode)`](#fn-specrunnervolumessecretitemswithmode)
          * [`fn withPath(path)`](#fn-specrunnervolumessecretitemswithpath)
      * [`obj spec.runner.volumes.storageos`](#obj-specrunnervolumesstorageos)
        * [`fn withFsType(fsType)`](#fn-specrunnervolumesstorageoswithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specrunnervolumesstorageoswithreadonly)
        * [`fn withVolumeName(volumeName)`](#fn-specrunnervolumesstorageoswithvolumename)
        * [`fn withVolumeNamespace(volumeNamespace)`](#fn-specrunnervolumesstorageoswithvolumenamespace)
        * [`obj spec.runner.volumes.storageos.secretRef`](#obj-specrunnervolumesstorageossecretref)
          * [`fn withName(name)`](#fn-specrunnervolumesstorageossecretrefwithname)
      * [`obj spec.runner.volumes.vsphereVolume`](#obj-specrunnervolumesvspherevolume)
        * [`fn withFsType(fsType)`](#fn-specrunnervolumesvspherevolumewithfstype)
        * [`fn withStoragePolicyID(storagePolicyID)`](#fn-specrunnervolumesvspherevolumewithstoragepolicyid)
        * [`fn withStoragePolicyName(storagePolicyName)`](#fn-specrunnervolumesvspherevolumewithstoragepolicyname)
        * [`fn withVolumePath(volumePath)`](#fn-specrunnervolumesvspherevolumewithvolumepath)
  * [`obj spec.script`](#obj-specscript)
    * [`fn withLocalFile(localFile)`](#fn-specscriptwithlocalfile)
    * [`obj spec.script.configMap`](#obj-specscriptconfigmap)
      * [`fn withFile(file)`](#fn-specscriptconfigmapwithfile)
      * [`fn withName(name)`](#fn-specscriptconfigmapwithname)
    * [`obj spec.script.volumeClaim`](#obj-specscriptvolumeclaim)
      * [`fn withFile(file)`](#fn-specscriptvolumeclaimwithfile)
      * [`fn withName(name)`](#fn-specscriptvolumeclaimwithname)
      * [`fn withReadOnly(readOnly)`](#fn-specscriptvolumeclaimwithreadonly)
  * [`obj spec.scuttle`](#obj-specscuttle)
    * [`fn withDisableLogging(disableLogging)`](#fn-specscuttlewithdisablelogging)
    * [`fn withEnabled(enabled)`](#fn-specscuttlewithenabled)
    * [`fn withEnvoyAdminApi(envoyAdminApi)`](#fn-specscuttlewithenvoyadminapi)
    * [`fn withGenericQuitEndpoint(genericQuitEndpoint)`](#fn-specscuttlewithgenericquitendpoint)
    * [`fn withIstioQuitApi(istioQuitApi)`](#fn-specscuttlewithistioquitapi)
    * [`fn withNeverKillIstio(neverKillIstio)`](#fn-specscuttlewithneverkillistio)
    * [`fn withNeverKillIstioOnFailure(neverKillIstioOnFailure)`](#fn-specscuttlewithneverkillistioonfailure)
    * [`fn withQuitWithoutEnvoyTimeout(quitWithoutEnvoyTimeout)`](#fn-specscuttlewithquitwithoutenvoytimeout)
    * [`fn withStartWithoutEnvoy(startWithoutEnvoy)`](#fn-specscuttlewithstartwithoutenvoy)
    * [`fn withWaitForEnvoyTimeout(waitForEnvoyTimeout)`](#fn-specscuttlewithwaitforenvoytimeout)
  * [`obj spec.starter`](#obj-specstarter)
    * [`fn withAutomountServiceAccountToken(automountServiceAccountToken)`](#fn-specstarterwithautomountserviceaccounttoken)
    * [`fn withEnv(env)`](#fn-specstarterwithenv)
    * [`fn withEnvFrom(envFrom)`](#fn-specstarterwithenvfrom)
    * [`fn withEnvFromMixin(envFrom)`](#fn-specstarterwithenvfrommixin)
    * [`fn withEnvMixin(env)`](#fn-specstarterwithenvmixin)
    * [`fn withImage(image)`](#fn-specstarterwithimage)
    * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specstarterwithimagepullpolicy)
    * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-specstarterwithimagepullsecrets)
    * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-specstarterwithimagepullsecretsmixin)
    * [`fn withInitContainers(initContainers)`](#fn-specstarterwithinitcontainers)
    * [`fn withInitContainersMixin(initContainers)`](#fn-specstarterwithinitcontainersmixin)
    * [`fn withNodeSelector(nodeSelector)`](#fn-specstarterwithnodeselector)
    * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-specstarterwithnodeselectormixin)
    * [`fn withServiceAccountName(serviceAccountName)`](#fn-specstarterwithserviceaccountname)
    * [`fn withTolerations(tolerations)`](#fn-specstarterwithtolerations)
    * [`fn withTolerationsMixin(tolerations)`](#fn-specstarterwithtolerationsmixin)
    * [`fn withTopologySpreadConstraints(topologySpreadConstraints)`](#fn-specstarterwithtopologyspreadconstraints)
    * [`fn withTopologySpreadConstraintsMixin(topologySpreadConstraints)`](#fn-specstarterwithtopologyspreadconstraintsmixin)
    * [`fn withVolumeMounts(volumeMounts)`](#fn-specstarterwithvolumemounts)
    * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specstarterwithvolumemountsmixin)
    * [`fn withVolumes(volumes)`](#fn-specstarterwithvolumes)
    * [`fn withVolumesMixin(volumes)`](#fn-specstarterwithvolumesmixin)
    * [`obj spec.starter.affinity`](#obj-specstarteraffinity)
      * [`obj spec.starter.affinity.nodeAffinity`](#obj-specstarteraffinitynodeaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specstarteraffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specstarteraffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
            * [`fn withMatchFields(matchFields)`](#fn-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
            * [`fn withMatchFieldsMixin(matchFields)`](#fn-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
            * [`obj spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
              * [`fn withKey(key)`](#fn-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
            * [`obj spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
              * [`fn withKey(key)`](#fn-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
              * [`fn withOperator(operator)`](#fn-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
              * [`fn withValues(values)`](#fn-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specstarteraffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
        * [`obj spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
          * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
          * [`obj spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
            * [`fn withMatchFields(matchFields)`](#fn-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
            * [`fn withMatchFieldsMixin(matchFields)`](#fn-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
            * [`obj spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
              * [`fn withKey(key)`](#fn-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
            * [`obj spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
              * [`fn withKey(key)`](#fn-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
              * [`fn withOperator(operator)`](#fn-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
              * [`fn withValues(values)`](#fn-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specstarteraffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
      * [`obj spec.starter.affinity.podAffinity`](#obj-specstarteraffinitypodaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specstarteraffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specstarteraffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specstarteraffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specstarteraffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
            * [`obj spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
              * [`obj spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specstarteraffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
          * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
          * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
          * [`fn withNamespaces(namespaces)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
          * [`obj spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
            * [`obj spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specstarteraffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.starter.affinity.podAntiAffinity`](#obj-specstarteraffinitypodantiaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specstarteraffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specstarteraffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specstarteraffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specstarteraffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
            * [`obj spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
              * [`obj spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specstarteraffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
          * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
          * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
          * [`fn withNamespaces(namespaces)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
          * [`obj spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
            * [`obj spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specstarteraffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
    * [`obj spec.starter.containerSecurityContext`](#obj-specstartercontainersecuritycontext)
      * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specstartercontainersecuritycontextwithallowprivilegeescalation)
      * [`fn withPrivileged(privileged)`](#fn-specstartercontainersecuritycontextwithprivileged)
      * [`fn withProcMount(procMount)`](#fn-specstartercontainersecuritycontextwithprocmount)
      * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specstartercontainersecuritycontextwithreadonlyrootfilesystem)
      * [`fn withRunAsGroup(runAsGroup)`](#fn-specstartercontainersecuritycontextwithrunasgroup)
      * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specstartercontainersecuritycontextwithrunasnonroot)
      * [`fn withRunAsUser(runAsUser)`](#fn-specstartercontainersecuritycontextwithrunasuser)
      * [`obj spec.starter.containerSecurityContext.appArmorProfile`](#obj-specstartercontainersecuritycontextapparmorprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specstartercontainersecuritycontextapparmorprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specstartercontainersecuritycontextapparmorprofilewithtype)
      * [`obj spec.starter.containerSecurityContext.capabilities`](#obj-specstartercontainersecuritycontextcapabilities)
        * [`fn withAdd(add)`](#fn-specstartercontainersecuritycontextcapabilitieswithadd)
        * [`fn withAddMixin(add)`](#fn-specstartercontainersecuritycontextcapabilitieswithaddmixin)
        * [`fn withDrop(drop)`](#fn-specstartercontainersecuritycontextcapabilitieswithdrop)
        * [`fn withDropMixin(drop)`](#fn-specstartercontainersecuritycontextcapabilitieswithdropmixin)
      * [`obj spec.starter.containerSecurityContext.seLinuxOptions`](#obj-specstartercontainersecuritycontextselinuxoptions)
        * [`fn withLevel(level)`](#fn-specstartercontainersecuritycontextselinuxoptionswithlevel)
        * [`fn withRole(role)`](#fn-specstartercontainersecuritycontextselinuxoptionswithrole)
        * [`fn withType(type)`](#fn-specstartercontainersecuritycontextselinuxoptionswithtype)
        * [`fn withUser(user)`](#fn-specstartercontainersecuritycontextselinuxoptionswithuser)
      * [`obj spec.starter.containerSecurityContext.seccompProfile`](#obj-specstartercontainersecuritycontextseccompprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specstartercontainersecuritycontextseccompprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specstartercontainersecuritycontextseccompprofilewithtype)
      * [`obj spec.starter.containerSecurityContext.windowsOptions`](#obj-specstartercontainersecuritycontextwindowsoptions)
        * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specstartercontainersecuritycontextwindowsoptionswithgmsacredentialspec)
        * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specstartercontainersecuritycontextwindowsoptionswithgmsacredentialspecname)
        * [`fn withHostProcess(hostProcess)`](#fn-specstartercontainersecuritycontextwindowsoptionswithhostprocess)
        * [`fn withRunAsUserName(runAsUserName)`](#fn-specstartercontainersecuritycontextwindowsoptionswithrunasusername)
    * [`obj spec.starter.env`](#obj-specstarterenv)
      * [`fn withName(name)`](#fn-specstarterenvwithname)
      * [`fn withValue(value)`](#fn-specstarterenvwithvalue)
      * [`obj spec.starter.env.valueFrom`](#obj-specstarterenvvaluefrom)
        * [`obj spec.starter.env.valueFrom.configMapKeyRef`](#obj-specstarterenvvaluefromconfigmapkeyref)
          * [`fn withKey(key)`](#fn-specstarterenvvaluefromconfigmapkeyrefwithkey)
          * [`fn withName(name)`](#fn-specstarterenvvaluefromconfigmapkeyrefwithname)
          * [`fn withOptional(optional)`](#fn-specstarterenvvaluefromconfigmapkeyrefwithoptional)
        * [`obj spec.starter.env.valueFrom.fieldRef`](#obj-specstarterenvvaluefromfieldref)
          * [`fn withApiVersion(apiVersion)`](#fn-specstarterenvvaluefromfieldrefwithapiversion)
          * [`fn withFieldPath(fieldPath)`](#fn-specstarterenvvaluefromfieldrefwithfieldpath)
        * [`obj spec.starter.env.valueFrom.resourceFieldRef`](#obj-specstarterenvvaluefromresourcefieldref)
          * [`fn withContainerName(containerName)`](#fn-specstarterenvvaluefromresourcefieldrefwithcontainername)
          * [`fn withDivisor(divisor)`](#fn-specstarterenvvaluefromresourcefieldrefwithdivisor)
          * [`fn withResource(resource)`](#fn-specstarterenvvaluefromresourcefieldrefwithresource)
        * [`obj spec.starter.env.valueFrom.secretKeyRef`](#obj-specstarterenvvaluefromsecretkeyref)
          * [`fn withKey(key)`](#fn-specstarterenvvaluefromsecretkeyrefwithkey)
          * [`fn withName(name)`](#fn-specstarterenvvaluefromsecretkeyrefwithname)
          * [`fn withOptional(optional)`](#fn-specstarterenvvaluefromsecretkeyrefwithoptional)
    * [`obj spec.starter.envFrom`](#obj-specstarterenvfrom)
      * [`fn withPrefix(prefix)`](#fn-specstarterenvfromwithprefix)
      * [`obj spec.starter.envFrom.configMapRef`](#obj-specstarterenvfromconfigmapref)
        * [`fn withName(name)`](#fn-specstarterenvfromconfigmaprefwithname)
        * [`fn withOptional(optional)`](#fn-specstarterenvfromconfigmaprefwithoptional)
      * [`obj spec.starter.envFrom.secretRef`](#obj-specstarterenvfromsecretref)
        * [`fn withName(name)`](#fn-specstarterenvfromsecretrefwithname)
        * [`fn withOptional(optional)`](#fn-specstarterenvfromsecretrefwithoptional)
    * [`obj spec.starter.imagePullSecrets`](#obj-specstarterimagepullsecrets)
      * [`fn withName(name)`](#fn-specstarterimagepullsecretswithname)
    * [`obj spec.starter.initContainers`](#obj-specstarterinitcontainers)
      * [`fn withArgs(args)`](#fn-specstarterinitcontainerswithargs)
      * [`fn withArgsMixin(args)`](#fn-specstarterinitcontainerswithargsmixin)
      * [`fn withCommand(command)`](#fn-specstarterinitcontainerswithcommand)
      * [`fn withCommandMixin(command)`](#fn-specstarterinitcontainerswithcommandmixin)
      * [`fn withEnv(env)`](#fn-specstarterinitcontainerswithenv)
      * [`fn withEnvFrom(envFrom)`](#fn-specstarterinitcontainerswithenvfrom)
      * [`fn withEnvFromMixin(envFrom)`](#fn-specstarterinitcontainerswithenvfrommixin)
      * [`fn withEnvMixin(env)`](#fn-specstarterinitcontainerswithenvmixin)
      * [`fn withImage(image)`](#fn-specstarterinitcontainerswithimage)
      * [`fn withName(name)`](#fn-specstarterinitcontainerswithname)
      * [`fn withVolumeMounts(volumeMounts)`](#fn-specstarterinitcontainerswithvolumemounts)
      * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specstarterinitcontainerswithvolumemountsmixin)
      * [`fn withWorkingDir(workingDir)`](#fn-specstarterinitcontainerswithworkingdir)
      * [`obj spec.starter.initContainers.env`](#obj-specstarterinitcontainersenv)
        * [`fn withName(name)`](#fn-specstarterinitcontainersenvwithname)
        * [`fn withValue(value)`](#fn-specstarterinitcontainersenvwithvalue)
        * [`obj spec.starter.initContainers.env.valueFrom`](#obj-specstarterinitcontainersenvvaluefrom)
          * [`obj spec.starter.initContainers.env.valueFrom.configMapKeyRef`](#obj-specstarterinitcontainersenvvaluefromconfigmapkeyref)
            * [`fn withKey(key)`](#fn-specstarterinitcontainersenvvaluefromconfigmapkeyrefwithkey)
            * [`fn withName(name)`](#fn-specstarterinitcontainersenvvaluefromconfigmapkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-specstarterinitcontainersenvvaluefromconfigmapkeyrefwithoptional)
          * [`obj spec.starter.initContainers.env.valueFrom.fieldRef`](#obj-specstarterinitcontainersenvvaluefromfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-specstarterinitcontainersenvvaluefromfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-specstarterinitcontainersenvvaluefromfieldrefwithfieldpath)
          * [`obj spec.starter.initContainers.env.valueFrom.resourceFieldRef`](#obj-specstarterinitcontainersenvvaluefromresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-specstarterinitcontainersenvvaluefromresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-specstarterinitcontainersenvvaluefromresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-specstarterinitcontainersenvvaluefromresourcefieldrefwithresource)
          * [`obj spec.starter.initContainers.env.valueFrom.secretKeyRef`](#obj-specstarterinitcontainersenvvaluefromsecretkeyref)
            * [`fn withKey(key)`](#fn-specstarterinitcontainersenvvaluefromsecretkeyrefwithkey)
            * [`fn withName(name)`](#fn-specstarterinitcontainersenvvaluefromsecretkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-specstarterinitcontainersenvvaluefromsecretkeyrefwithoptional)
      * [`obj spec.starter.initContainers.envFrom`](#obj-specstarterinitcontainersenvfrom)
        * [`fn withPrefix(prefix)`](#fn-specstarterinitcontainersenvfromwithprefix)
        * [`obj spec.starter.initContainers.envFrom.configMapRef`](#obj-specstarterinitcontainersenvfromconfigmapref)
          * [`fn withName(name)`](#fn-specstarterinitcontainersenvfromconfigmaprefwithname)
          * [`fn withOptional(optional)`](#fn-specstarterinitcontainersenvfromconfigmaprefwithoptional)
        * [`obj spec.starter.initContainers.envFrom.secretRef`](#obj-specstarterinitcontainersenvfromsecretref)
          * [`fn withName(name)`](#fn-specstarterinitcontainersenvfromsecretrefwithname)
          * [`fn withOptional(optional)`](#fn-specstarterinitcontainersenvfromsecretrefwithoptional)
      * [`obj spec.starter.initContainers.volumeMounts`](#obj-specstarterinitcontainersvolumemounts)
        * [`fn withMountPath(mountPath)`](#fn-specstarterinitcontainersvolumemountswithmountpath)
        * [`fn withMountPropagation(mountPropagation)`](#fn-specstarterinitcontainersvolumemountswithmountpropagation)
        * [`fn withName(name)`](#fn-specstarterinitcontainersvolumemountswithname)
        * [`fn withReadOnly(readOnly)`](#fn-specstarterinitcontainersvolumemountswithreadonly)
        * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specstarterinitcontainersvolumemountswithrecursivereadonly)
        * [`fn withSubPath(subPath)`](#fn-specstarterinitcontainersvolumemountswithsubpath)
        * [`fn withSubPathExpr(subPathExpr)`](#fn-specstarterinitcontainersvolumemountswithsubpathexpr)
    * [`obj spec.starter.livenessProbe`](#obj-specstarterlivenessprobe)
      * [`fn withFailureThreshold(failureThreshold)`](#fn-specstarterlivenessprobewithfailurethreshold)
      * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specstarterlivenessprobewithinitialdelayseconds)
      * [`fn withPeriodSeconds(periodSeconds)`](#fn-specstarterlivenessprobewithperiodseconds)
      * [`fn withSuccessThreshold(successThreshold)`](#fn-specstarterlivenessprobewithsuccessthreshold)
      * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specstarterlivenessprobewithterminationgraceperiodseconds)
      * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specstarterlivenessprobewithtimeoutseconds)
      * [`obj spec.starter.livenessProbe.exec`](#obj-specstarterlivenessprobeexec)
        * [`fn withCommand(command)`](#fn-specstarterlivenessprobeexecwithcommand)
        * [`fn withCommandMixin(command)`](#fn-specstarterlivenessprobeexecwithcommandmixin)
      * [`obj spec.starter.livenessProbe.grpc`](#obj-specstarterlivenessprobegrpc)
        * [`fn withPort(port)`](#fn-specstarterlivenessprobegrpcwithport)
        * [`fn withService(service)`](#fn-specstarterlivenessprobegrpcwithservice)
      * [`obj spec.starter.livenessProbe.httpGet`](#obj-specstarterlivenessprobehttpget)
        * [`fn withHost(host)`](#fn-specstarterlivenessprobehttpgetwithhost)
        * [`fn withHttpHeaders(httpHeaders)`](#fn-specstarterlivenessprobehttpgetwithhttpheaders)
        * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specstarterlivenessprobehttpgetwithhttpheadersmixin)
        * [`fn withPath(path)`](#fn-specstarterlivenessprobehttpgetwithpath)
        * [`fn withPort(port)`](#fn-specstarterlivenessprobehttpgetwithport)
        * [`fn withScheme(scheme)`](#fn-specstarterlivenessprobehttpgetwithscheme)
        * [`obj spec.starter.livenessProbe.httpGet.httpHeaders`](#obj-specstarterlivenessprobehttpgethttpheaders)
          * [`fn withName(name)`](#fn-specstarterlivenessprobehttpgethttpheaderswithname)
          * [`fn withValue(value)`](#fn-specstarterlivenessprobehttpgethttpheaderswithvalue)
      * [`obj spec.starter.livenessProbe.tcpSocket`](#obj-specstarterlivenessprobetcpsocket)
        * [`fn withHost(host)`](#fn-specstarterlivenessprobetcpsocketwithhost)
        * [`fn withPort(port)`](#fn-specstarterlivenessprobetcpsocketwithport)
    * [`obj spec.starter.metadata`](#obj-specstartermetadata)
      * [`fn withAnnotations(annotations)`](#fn-specstartermetadatawithannotations)
      * [`fn withAnnotationsMixin(annotations)`](#fn-specstartermetadatawithannotationsmixin)
      * [`fn withLabels(labels)`](#fn-specstartermetadatawithlabels)
      * [`fn withLabelsMixin(labels)`](#fn-specstartermetadatawithlabelsmixin)
    * [`obj spec.starter.readinessProbe`](#obj-specstarterreadinessprobe)
      * [`fn withFailureThreshold(failureThreshold)`](#fn-specstarterreadinessprobewithfailurethreshold)
      * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specstarterreadinessprobewithinitialdelayseconds)
      * [`fn withPeriodSeconds(periodSeconds)`](#fn-specstarterreadinessprobewithperiodseconds)
      * [`fn withSuccessThreshold(successThreshold)`](#fn-specstarterreadinessprobewithsuccessthreshold)
      * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specstarterreadinessprobewithterminationgraceperiodseconds)
      * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specstarterreadinessprobewithtimeoutseconds)
      * [`obj spec.starter.readinessProbe.exec`](#obj-specstarterreadinessprobeexec)
        * [`fn withCommand(command)`](#fn-specstarterreadinessprobeexecwithcommand)
        * [`fn withCommandMixin(command)`](#fn-specstarterreadinessprobeexecwithcommandmixin)
      * [`obj spec.starter.readinessProbe.grpc`](#obj-specstarterreadinessprobegrpc)
        * [`fn withPort(port)`](#fn-specstarterreadinessprobegrpcwithport)
        * [`fn withService(service)`](#fn-specstarterreadinessprobegrpcwithservice)
      * [`obj spec.starter.readinessProbe.httpGet`](#obj-specstarterreadinessprobehttpget)
        * [`fn withHost(host)`](#fn-specstarterreadinessprobehttpgetwithhost)
        * [`fn withHttpHeaders(httpHeaders)`](#fn-specstarterreadinessprobehttpgetwithhttpheaders)
        * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specstarterreadinessprobehttpgetwithhttpheadersmixin)
        * [`fn withPath(path)`](#fn-specstarterreadinessprobehttpgetwithpath)
        * [`fn withPort(port)`](#fn-specstarterreadinessprobehttpgetwithport)
        * [`fn withScheme(scheme)`](#fn-specstarterreadinessprobehttpgetwithscheme)
        * [`obj spec.starter.readinessProbe.httpGet.httpHeaders`](#obj-specstarterreadinessprobehttpgethttpheaders)
          * [`fn withName(name)`](#fn-specstarterreadinessprobehttpgethttpheaderswithname)
          * [`fn withValue(value)`](#fn-specstarterreadinessprobehttpgethttpheaderswithvalue)
      * [`obj spec.starter.readinessProbe.tcpSocket`](#obj-specstarterreadinessprobetcpsocket)
        * [`fn withHost(host)`](#fn-specstarterreadinessprobetcpsocketwithhost)
        * [`fn withPort(port)`](#fn-specstarterreadinessprobetcpsocketwithport)
    * [`obj spec.starter.resources`](#obj-specstarterresources)
      * [`fn withClaims(claims)`](#fn-specstarterresourceswithclaims)
      * [`fn withClaimsMixin(claims)`](#fn-specstarterresourceswithclaimsmixin)
      * [`fn withLimits(limits)`](#fn-specstarterresourceswithlimits)
      * [`fn withLimitsMixin(limits)`](#fn-specstarterresourceswithlimitsmixin)
      * [`fn withRequests(requests)`](#fn-specstarterresourceswithrequests)
      * [`fn withRequestsMixin(requests)`](#fn-specstarterresourceswithrequestsmixin)
      * [`obj spec.starter.resources.claims`](#obj-specstarterresourcesclaims)
        * [`fn withName(name)`](#fn-specstarterresourcesclaimswithname)
        * [`fn withRequest(request)`](#fn-specstarterresourcesclaimswithrequest)
    * [`obj spec.starter.securityContext`](#obj-specstartersecuritycontext)
      * [`fn withFsGroup(fsGroup)`](#fn-specstartersecuritycontextwithfsgroup)
      * [`fn withFsGroupChangePolicy(fsGroupChangePolicy)`](#fn-specstartersecuritycontextwithfsgroupchangepolicy)
      * [`fn withRunAsGroup(runAsGroup)`](#fn-specstartersecuritycontextwithrunasgroup)
      * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specstartersecuritycontextwithrunasnonroot)
      * [`fn withRunAsUser(runAsUser)`](#fn-specstartersecuritycontextwithrunasuser)
      * [`fn withSupplementalGroups(supplementalGroups)`](#fn-specstartersecuritycontextwithsupplementalgroups)
      * [`fn withSupplementalGroupsMixin(supplementalGroups)`](#fn-specstartersecuritycontextwithsupplementalgroupsmixin)
      * [`fn withSupplementalGroupsPolicy(supplementalGroupsPolicy)`](#fn-specstartersecuritycontextwithsupplementalgroupspolicy)
      * [`fn withSysctls(sysctls)`](#fn-specstartersecuritycontextwithsysctls)
      * [`fn withSysctlsMixin(sysctls)`](#fn-specstartersecuritycontextwithsysctlsmixin)
      * [`obj spec.starter.securityContext.appArmorProfile`](#obj-specstartersecuritycontextapparmorprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specstartersecuritycontextapparmorprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specstartersecuritycontextapparmorprofilewithtype)
      * [`obj spec.starter.securityContext.seLinuxOptions`](#obj-specstartersecuritycontextselinuxoptions)
        * [`fn withLevel(level)`](#fn-specstartersecuritycontextselinuxoptionswithlevel)
        * [`fn withRole(role)`](#fn-specstartersecuritycontextselinuxoptionswithrole)
        * [`fn withType(type)`](#fn-specstartersecuritycontextselinuxoptionswithtype)
        * [`fn withUser(user)`](#fn-specstartersecuritycontextselinuxoptionswithuser)
      * [`obj spec.starter.securityContext.seccompProfile`](#obj-specstartersecuritycontextseccompprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specstartersecuritycontextseccompprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specstartersecuritycontextseccompprofilewithtype)
      * [`obj spec.starter.securityContext.sysctls`](#obj-specstartersecuritycontextsysctls)
        * [`fn withName(name)`](#fn-specstartersecuritycontextsysctlswithname)
        * [`fn withValue(value)`](#fn-specstartersecuritycontextsysctlswithvalue)
      * [`obj spec.starter.securityContext.windowsOptions`](#obj-specstartersecuritycontextwindowsoptions)
        * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specstartersecuritycontextwindowsoptionswithgmsacredentialspec)
        * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specstartersecuritycontextwindowsoptionswithgmsacredentialspecname)
        * [`fn withHostProcess(hostProcess)`](#fn-specstartersecuritycontextwindowsoptionswithhostprocess)
        * [`fn withRunAsUserName(runAsUserName)`](#fn-specstartersecuritycontextwindowsoptionswithrunasusername)
    * [`obj spec.starter.tolerations`](#obj-specstartertolerations)
      * [`fn withEffect(effect)`](#fn-specstartertolerationswitheffect)
      * [`fn withKey(key)`](#fn-specstartertolerationswithkey)
      * [`fn withOperator(operator)`](#fn-specstartertolerationswithoperator)
      * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-specstartertolerationswithtolerationseconds)
      * [`fn withValue(value)`](#fn-specstartertolerationswithvalue)
    * [`obj spec.starter.topologySpreadConstraints`](#obj-specstartertopologyspreadconstraints)
      * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specstartertopologyspreadconstraintswithmatchlabelkeys)
      * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specstartertopologyspreadconstraintswithmatchlabelkeysmixin)
      * [`fn withMaxSkew(maxSkew)`](#fn-specstartertopologyspreadconstraintswithmaxskew)
      * [`fn withMinDomains(minDomains)`](#fn-specstartertopologyspreadconstraintswithmindomains)
      * [`fn withNodeAffinityPolicy(nodeAffinityPolicy)`](#fn-specstartertopologyspreadconstraintswithnodeaffinitypolicy)
      * [`fn withNodeTaintsPolicy(nodeTaintsPolicy)`](#fn-specstartertopologyspreadconstraintswithnodetaintspolicy)
      * [`fn withTopologyKey(topologyKey)`](#fn-specstartertopologyspreadconstraintswithtopologykey)
      * [`fn withWhenUnsatisfiable(whenUnsatisfiable)`](#fn-specstartertopologyspreadconstraintswithwhenunsatisfiable)
      * [`obj spec.starter.topologySpreadConstraints.labelSelector`](#obj-specstartertopologyspreadconstraintslabelselector)
        * [`fn withMatchExpressions(matchExpressions)`](#fn-specstartertopologyspreadconstraintslabelselectorwithmatchexpressions)
        * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specstartertopologyspreadconstraintslabelselectorwithmatchexpressionsmixin)
        * [`fn withMatchLabels(matchLabels)`](#fn-specstartertopologyspreadconstraintslabelselectorwithmatchlabels)
        * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specstartertopologyspreadconstraintslabelselectorwithmatchlabelsmixin)
        * [`obj spec.starter.topologySpreadConstraints.labelSelector.matchExpressions`](#obj-specstartertopologyspreadconstraintslabelselectormatchexpressions)
          * [`fn withKey(key)`](#fn-specstartertopologyspreadconstraintslabelselectormatchexpressionswithkey)
          * [`fn withOperator(operator)`](#fn-specstartertopologyspreadconstraintslabelselectormatchexpressionswithoperator)
          * [`fn withValues(values)`](#fn-specstartertopologyspreadconstraintslabelselectormatchexpressionswithvalues)
          * [`fn withValuesMixin(values)`](#fn-specstartertopologyspreadconstraintslabelselectormatchexpressionswithvaluesmixin)
    * [`obj spec.starter.volumeMounts`](#obj-specstartervolumemounts)
      * [`fn withMountPath(mountPath)`](#fn-specstartervolumemountswithmountpath)
      * [`fn withMountPropagation(mountPropagation)`](#fn-specstartervolumemountswithmountpropagation)
      * [`fn withName(name)`](#fn-specstartervolumemountswithname)
      * [`fn withReadOnly(readOnly)`](#fn-specstartervolumemountswithreadonly)
      * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specstartervolumemountswithrecursivereadonly)
      * [`fn withSubPath(subPath)`](#fn-specstartervolumemountswithsubpath)
      * [`fn withSubPathExpr(subPathExpr)`](#fn-specstartervolumemountswithsubpathexpr)
    * [`obj spec.starter.volumes`](#obj-specstartervolumes)
      * [`fn withName(name)`](#fn-specstartervolumeswithname)
      * [`obj spec.starter.volumes.awsElasticBlockStore`](#obj-specstartervolumesawselasticblockstore)
        * [`fn withFsType(fsType)`](#fn-specstartervolumesawselasticblockstorewithfstype)
        * [`fn withPartition(partition)`](#fn-specstartervolumesawselasticblockstorewithpartition)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumesawselasticblockstorewithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-specstartervolumesawselasticblockstorewithvolumeid)
      * [`obj spec.starter.volumes.azureDisk`](#obj-specstartervolumesazuredisk)
        * [`fn withCachingMode(cachingMode)`](#fn-specstartervolumesazurediskwithcachingmode)
        * [`fn withDiskName(diskName)`](#fn-specstartervolumesazurediskwithdiskname)
        * [`fn withDiskURI(diskURI)`](#fn-specstartervolumesazurediskwithdiskuri)
        * [`fn withFsType(fsType)`](#fn-specstartervolumesazurediskwithfstype)
        * [`fn withKind(kind)`](#fn-specstartervolumesazurediskwithkind)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumesazurediskwithreadonly)
      * [`obj spec.starter.volumes.azureFile`](#obj-specstartervolumesazurefile)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumesazurefilewithreadonly)
        * [`fn withSecretName(secretName)`](#fn-specstartervolumesazurefilewithsecretname)
        * [`fn withShareName(shareName)`](#fn-specstartervolumesazurefilewithsharename)
      * [`obj spec.starter.volumes.cephfs`](#obj-specstartervolumescephfs)
        * [`fn withMonitors(monitors)`](#fn-specstartervolumescephfswithmonitors)
        * [`fn withMonitorsMixin(monitors)`](#fn-specstartervolumescephfswithmonitorsmixin)
        * [`fn withPath(path)`](#fn-specstartervolumescephfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumescephfswithreadonly)
        * [`fn withSecretFile(secretFile)`](#fn-specstartervolumescephfswithsecretfile)
        * [`fn withUser(user)`](#fn-specstartervolumescephfswithuser)
        * [`obj spec.starter.volumes.cephfs.secretRef`](#obj-specstartervolumescephfssecretref)
          * [`fn withName(name)`](#fn-specstartervolumescephfssecretrefwithname)
      * [`obj spec.starter.volumes.cinder`](#obj-specstartervolumescinder)
        * [`fn withFsType(fsType)`](#fn-specstartervolumescinderwithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumescinderwithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-specstartervolumescinderwithvolumeid)
        * [`obj spec.starter.volumes.cinder.secretRef`](#obj-specstartervolumescindersecretref)
          * [`fn withName(name)`](#fn-specstartervolumescindersecretrefwithname)
      * [`obj spec.starter.volumes.configMap`](#obj-specstartervolumesconfigmap)
        * [`fn withDefaultMode(defaultMode)`](#fn-specstartervolumesconfigmapwithdefaultmode)
        * [`fn withItems(items)`](#fn-specstartervolumesconfigmapwithitems)
        * [`fn withItemsMixin(items)`](#fn-specstartervolumesconfigmapwithitemsmixin)
        * [`fn withName(name)`](#fn-specstartervolumesconfigmapwithname)
        * [`fn withOptional(optional)`](#fn-specstartervolumesconfigmapwithoptional)
        * [`obj spec.starter.volumes.configMap.items`](#obj-specstartervolumesconfigmapitems)
          * [`fn withKey(key)`](#fn-specstartervolumesconfigmapitemswithkey)
          * [`fn withMode(mode)`](#fn-specstartervolumesconfigmapitemswithmode)
          * [`fn withPath(path)`](#fn-specstartervolumesconfigmapitemswithpath)
      * [`obj spec.starter.volumes.csi`](#obj-specstartervolumescsi)
        * [`fn withDriver(driver)`](#fn-specstartervolumescsiwithdriver)
        * [`fn withFsType(fsType)`](#fn-specstartervolumescsiwithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumescsiwithreadonly)
        * [`fn withVolumeAttributes(volumeAttributes)`](#fn-specstartervolumescsiwithvolumeattributes)
        * [`fn withVolumeAttributesMixin(volumeAttributes)`](#fn-specstartervolumescsiwithvolumeattributesmixin)
        * [`obj spec.starter.volumes.csi.nodePublishSecretRef`](#obj-specstartervolumescsinodepublishsecretref)
          * [`fn withName(name)`](#fn-specstartervolumescsinodepublishsecretrefwithname)
      * [`obj spec.starter.volumes.downwardAPI`](#obj-specstartervolumesdownwardapi)
        * [`fn withDefaultMode(defaultMode)`](#fn-specstartervolumesdownwardapiwithdefaultmode)
        * [`fn withItems(items)`](#fn-specstartervolumesdownwardapiwithitems)
        * [`fn withItemsMixin(items)`](#fn-specstartervolumesdownwardapiwithitemsmixin)
        * [`obj spec.starter.volumes.downwardAPI.items`](#obj-specstartervolumesdownwardapiitems)
          * [`fn withMode(mode)`](#fn-specstartervolumesdownwardapiitemswithmode)
          * [`fn withPath(path)`](#fn-specstartervolumesdownwardapiitemswithpath)
          * [`obj spec.starter.volumes.downwardAPI.items.fieldRef`](#obj-specstartervolumesdownwardapiitemsfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-specstartervolumesdownwardapiitemsfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-specstartervolumesdownwardapiitemsfieldrefwithfieldpath)
          * [`obj spec.starter.volumes.downwardAPI.items.resourceFieldRef`](#obj-specstartervolumesdownwardapiitemsresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-specstartervolumesdownwardapiitemsresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-specstartervolumesdownwardapiitemsresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-specstartervolumesdownwardapiitemsresourcefieldrefwithresource)
      * [`obj spec.starter.volumes.emptyDir`](#obj-specstartervolumesemptydir)
        * [`fn withMedium(medium)`](#fn-specstartervolumesemptydirwithmedium)
        * [`fn withSizeLimit(sizeLimit)`](#fn-specstartervolumesemptydirwithsizelimit)
      * [`obj spec.starter.volumes.ephemeral`](#obj-specstartervolumesephemeral)
        * [`obj spec.starter.volumes.ephemeral.volumeClaimTemplate`](#obj-specstartervolumesephemeralvolumeclaimtemplate)
          * [`fn withMetadata(metadata)`](#fn-specstartervolumesephemeralvolumeclaimtemplatewithmetadata)
          * [`fn withMetadataMixin(metadata)`](#fn-specstartervolumesephemeralvolumeclaimtemplatewithmetadatamixin)
          * [`obj spec.starter.volumes.ephemeral.volumeClaimTemplate.spec`](#obj-specstartervolumesephemeralvolumeclaimtemplatespec)
            * [`fn withAccessModes(accessModes)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecwithaccessmodes)
            * [`fn withAccessModesMixin(accessModes)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecwithaccessmodesmixin)
            * [`fn withStorageClassName(storageClassName)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecwithstorageclassname)
            * [`fn withVolumeAttributesClassName(volumeAttributesClassName)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecwithvolumeattributesclassname)
            * [`fn withVolumeMode(volumeMode)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecwithvolumemode)
            * [`fn withVolumeName(volumeName)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecwithvolumename)
            * [`obj spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.dataSource`](#obj-specstartervolumesephemeralvolumeclaimtemplatespecdatasource)
              * [`fn withApiGroup(apiGroup)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecdatasourcewithapigroup)
              * [`fn withKind(kind)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecdatasourcewithkind)
              * [`fn withName(name)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecdatasourcewithname)
            * [`obj spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef`](#obj-specstartervolumesephemeralvolumeclaimtemplatespecdatasourceref)
              * [`fn withApiGroup(apiGroup)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecdatasourcerefwithapigroup)
              * [`fn withKind(kind)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecdatasourcerefwithkind)
              * [`fn withName(name)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecdatasourcerefwithname)
              * [`fn withNamespace(namespace)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecdatasourcerefwithnamespace)
            * [`obj spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.resources`](#obj-specstartervolumesephemeralvolumeclaimtemplatespecresources)
              * [`fn withLimits(limits)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecresourceswithlimits)
              * [`fn withLimitsMixin(limits)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecresourceswithlimitsmixin)
              * [`fn withRequests(requests)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecresourceswithrequests)
              * [`fn withRequestsMixin(requests)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecresourceswithrequestsmixin)
            * [`obj spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.selector`](#obj-specstartervolumesephemeralvolumeclaimtemplatespecselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabelsmixin)
              * [`obj spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions`](#obj-specstartervolumesephemeralvolumeclaimtemplatespecselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specstartervolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvaluesmixin)
      * [`obj spec.starter.volumes.fc`](#obj-specstartervolumesfc)
        * [`fn withFsType(fsType)`](#fn-specstartervolumesfcwithfstype)
        * [`fn withLun(lun)`](#fn-specstartervolumesfcwithlun)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumesfcwithreadonly)
        * [`fn withTargetWWNs(targetWWNs)`](#fn-specstartervolumesfcwithtargetwwns)
        * [`fn withTargetWWNsMixin(targetWWNs)`](#fn-specstartervolumesfcwithtargetwwnsmixin)
        * [`fn withWwids(wwids)`](#fn-specstartervolumesfcwithwwids)
        * [`fn withWwidsMixin(wwids)`](#fn-specstartervolumesfcwithwwidsmixin)
      * [`obj spec.starter.volumes.flexVolume`](#obj-specstartervolumesflexvolume)
        * [`fn withDriver(driver)`](#fn-specstartervolumesflexvolumewithdriver)
        * [`fn withFsType(fsType)`](#fn-specstartervolumesflexvolumewithfstype)
        * [`fn withOptions(options)`](#fn-specstartervolumesflexvolumewithoptions)
        * [`fn withOptionsMixin(options)`](#fn-specstartervolumesflexvolumewithoptionsmixin)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumesflexvolumewithreadonly)
        * [`obj spec.starter.volumes.flexVolume.secretRef`](#obj-specstartervolumesflexvolumesecretref)
          * [`fn withName(name)`](#fn-specstartervolumesflexvolumesecretrefwithname)
      * [`obj spec.starter.volumes.flocker`](#obj-specstartervolumesflocker)
        * [`fn withDatasetName(datasetName)`](#fn-specstartervolumesflockerwithdatasetname)
        * [`fn withDatasetUUID(datasetUUID)`](#fn-specstartervolumesflockerwithdatasetuuid)
      * [`obj spec.starter.volumes.gcePersistentDisk`](#obj-specstartervolumesgcepersistentdisk)
        * [`fn withFsType(fsType)`](#fn-specstartervolumesgcepersistentdiskwithfstype)
        * [`fn withPartition(partition)`](#fn-specstartervolumesgcepersistentdiskwithpartition)
        * [`fn withPdName(pdName)`](#fn-specstartervolumesgcepersistentdiskwithpdname)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumesgcepersistentdiskwithreadonly)
      * [`obj spec.starter.volumes.gitRepo`](#obj-specstartervolumesgitrepo)
        * [`fn withDirectory(directory)`](#fn-specstartervolumesgitrepowithdirectory)
        * [`fn withRepository(repository)`](#fn-specstartervolumesgitrepowithrepository)
        * [`fn withRevision(revision)`](#fn-specstartervolumesgitrepowithrevision)
      * [`obj spec.starter.volumes.glusterfs`](#obj-specstartervolumesglusterfs)
        * [`fn withEndpoints(endpoints)`](#fn-specstartervolumesglusterfswithendpoints)
        * [`fn withPath(path)`](#fn-specstartervolumesglusterfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumesglusterfswithreadonly)
      * [`obj spec.starter.volumes.hostPath`](#obj-specstartervolumeshostpath)
        * [`fn withPath(path)`](#fn-specstartervolumeshostpathwithpath)
        * [`fn withType(type)`](#fn-specstartervolumeshostpathwithtype)
      * [`obj spec.starter.volumes.image`](#obj-specstartervolumesimage)
        * [`fn withPullPolicy(pullPolicy)`](#fn-specstartervolumesimagewithpullpolicy)
        * [`fn withReference(reference)`](#fn-specstartervolumesimagewithreference)
      * [`obj spec.starter.volumes.iscsi`](#obj-specstartervolumesiscsi)
        * [`fn withChapAuthDiscovery(chapAuthDiscovery)`](#fn-specstartervolumesiscsiwithchapauthdiscovery)
        * [`fn withChapAuthSession(chapAuthSession)`](#fn-specstartervolumesiscsiwithchapauthsession)
        * [`fn withFsType(fsType)`](#fn-specstartervolumesiscsiwithfstype)
        * [`fn withInitiatorName(initiatorName)`](#fn-specstartervolumesiscsiwithinitiatorname)
        * [`fn withIqn(iqn)`](#fn-specstartervolumesiscsiwithiqn)
        * [`fn withIscsiInterface(iscsiInterface)`](#fn-specstartervolumesiscsiwithiscsiinterface)
        * [`fn withLun(lun)`](#fn-specstartervolumesiscsiwithlun)
        * [`fn withPortals(portals)`](#fn-specstartervolumesiscsiwithportals)
        * [`fn withPortalsMixin(portals)`](#fn-specstartervolumesiscsiwithportalsmixin)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumesiscsiwithreadonly)
        * [`fn withTargetPortal(targetPortal)`](#fn-specstartervolumesiscsiwithtargetportal)
        * [`obj spec.starter.volumes.iscsi.secretRef`](#obj-specstartervolumesiscsisecretref)
          * [`fn withName(name)`](#fn-specstartervolumesiscsisecretrefwithname)
      * [`obj spec.starter.volumes.nfs`](#obj-specstartervolumesnfs)
        * [`fn withPath(path)`](#fn-specstartervolumesnfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumesnfswithreadonly)
        * [`fn withServer(server)`](#fn-specstartervolumesnfswithserver)
      * [`obj spec.starter.volumes.persistentVolumeClaim`](#obj-specstartervolumespersistentvolumeclaim)
        * [`fn withClaimName(claimName)`](#fn-specstartervolumespersistentvolumeclaimwithclaimname)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumespersistentvolumeclaimwithreadonly)
      * [`obj spec.starter.volumes.photonPersistentDisk`](#obj-specstartervolumesphotonpersistentdisk)
        * [`fn withFsType(fsType)`](#fn-specstartervolumesphotonpersistentdiskwithfstype)
        * [`fn withPdID(pdID)`](#fn-specstartervolumesphotonpersistentdiskwithpdid)
      * [`obj spec.starter.volumes.portworxVolume`](#obj-specstartervolumesportworxvolume)
        * [`fn withFsType(fsType)`](#fn-specstartervolumesportworxvolumewithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumesportworxvolumewithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-specstartervolumesportworxvolumewithvolumeid)
      * [`obj spec.starter.volumes.projected`](#obj-specstartervolumesprojected)
        * [`fn withDefaultMode(defaultMode)`](#fn-specstartervolumesprojectedwithdefaultmode)
        * [`fn withSources(sources)`](#fn-specstartervolumesprojectedwithsources)
        * [`fn withSourcesMixin(sources)`](#fn-specstartervolumesprojectedwithsourcesmixin)
        * [`obj spec.starter.volumes.projected.sources`](#obj-specstartervolumesprojectedsources)
          * [`obj spec.starter.volumes.projected.sources.clusterTrustBundle`](#obj-specstartervolumesprojectedsourcesclustertrustbundle)
            * [`fn withName(name)`](#fn-specstartervolumesprojectedsourcesclustertrustbundlewithname)
            * [`fn withOptional(optional)`](#fn-specstartervolumesprojectedsourcesclustertrustbundlewithoptional)
            * [`fn withPath(path)`](#fn-specstartervolumesprojectedsourcesclustertrustbundlewithpath)
            * [`fn withSignerName(signerName)`](#fn-specstartervolumesprojectedsourcesclustertrustbundlewithsignername)
            * [`obj spec.starter.volumes.projected.sources.clusterTrustBundle.labelSelector`](#obj-specstartervolumesprojectedsourcesclustertrustbundlelabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specstartervolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specstartervolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specstartervolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specstartervolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabelsmixin)
              * [`obj spec.starter.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions`](#obj-specstartervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specstartervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specstartervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specstartervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specstartervolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.starter.volumes.projected.sources.configMap`](#obj-specstartervolumesprojectedsourcesconfigmap)
            * [`fn withItems(items)`](#fn-specstartervolumesprojectedsourcesconfigmapwithitems)
            * [`fn withItemsMixin(items)`](#fn-specstartervolumesprojectedsourcesconfigmapwithitemsmixin)
            * [`fn withName(name)`](#fn-specstartervolumesprojectedsourcesconfigmapwithname)
            * [`fn withOptional(optional)`](#fn-specstartervolumesprojectedsourcesconfigmapwithoptional)
            * [`obj spec.starter.volumes.projected.sources.configMap.items`](#obj-specstartervolumesprojectedsourcesconfigmapitems)
              * [`fn withKey(key)`](#fn-specstartervolumesprojectedsourcesconfigmapitemswithkey)
              * [`fn withMode(mode)`](#fn-specstartervolumesprojectedsourcesconfigmapitemswithmode)
              * [`fn withPath(path)`](#fn-specstartervolumesprojectedsourcesconfigmapitemswithpath)
          * [`obj spec.starter.volumes.projected.sources.downwardAPI`](#obj-specstartervolumesprojectedsourcesdownwardapi)
            * [`fn withItems(items)`](#fn-specstartervolumesprojectedsourcesdownwardapiwithitems)
            * [`fn withItemsMixin(items)`](#fn-specstartervolumesprojectedsourcesdownwardapiwithitemsmixin)
            * [`obj spec.starter.volumes.projected.sources.downwardAPI.items`](#obj-specstartervolumesprojectedsourcesdownwardapiitems)
              * [`fn withMode(mode)`](#fn-specstartervolumesprojectedsourcesdownwardapiitemswithmode)
              * [`fn withPath(path)`](#fn-specstartervolumesprojectedsourcesdownwardapiitemswithpath)
              * [`obj spec.starter.volumes.projected.sources.downwardAPI.items.fieldRef`](#obj-specstartervolumesprojectedsourcesdownwardapiitemsfieldref)
                * [`fn withApiVersion(apiVersion)`](#fn-specstartervolumesprojectedsourcesdownwardapiitemsfieldrefwithapiversion)
                * [`fn withFieldPath(fieldPath)`](#fn-specstartervolumesprojectedsourcesdownwardapiitemsfieldrefwithfieldpath)
              * [`obj spec.starter.volumes.projected.sources.downwardAPI.items.resourceFieldRef`](#obj-specstartervolumesprojectedsourcesdownwardapiitemsresourcefieldref)
                * [`fn withContainerName(containerName)`](#fn-specstartervolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithcontainername)
                * [`fn withDivisor(divisor)`](#fn-specstartervolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithdivisor)
                * [`fn withResource(resource)`](#fn-specstartervolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithresource)
          * [`obj spec.starter.volumes.projected.sources.secret`](#obj-specstartervolumesprojectedsourcessecret)
            * [`fn withItems(items)`](#fn-specstartervolumesprojectedsourcessecretwithitems)
            * [`fn withItemsMixin(items)`](#fn-specstartervolumesprojectedsourcessecretwithitemsmixin)
            * [`fn withName(name)`](#fn-specstartervolumesprojectedsourcessecretwithname)
            * [`fn withOptional(optional)`](#fn-specstartervolumesprojectedsourcessecretwithoptional)
            * [`obj spec.starter.volumes.projected.sources.secret.items`](#obj-specstartervolumesprojectedsourcessecretitems)
              * [`fn withKey(key)`](#fn-specstartervolumesprojectedsourcessecretitemswithkey)
              * [`fn withMode(mode)`](#fn-specstartervolumesprojectedsourcessecretitemswithmode)
              * [`fn withPath(path)`](#fn-specstartervolumesprojectedsourcessecretitemswithpath)
          * [`obj spec.starter.volumes.projected.sources.serviceAccountToken`](#obj-specstartervolumesprojectedsourcesserviceaccounttoken)
            * [`fn withAudience(audience)`](#fn-specstartervolumesprojectedsourcesserviceaccounttokenwithaudience)
            * [`fn withExpirationSeconds(expirationSeconds)`](#fn-specstartervolumesprojectedsourcesserviceaccounttokenwithexpirationseconds)
            * [`fn withPath(path)`](#fn-specstartervolumesprojectedsourcesserviceaccounttokenwithpath)
      * [`obj spec.starter.volumes.quobyte`](#obj-specstartervolumesquobyte)
        * [`fn withGroup(group)`](#fn-specstartervolumesquobytewithgroup)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumesquobytewithreadonly)
        * [`fn withRegistry(registry)`](#fn-specstartervolumesquobytewithregistry)
        * [`fn withTenant(tenant)`](#fn-specstartervolumesquobytewithtenant)
        * [`fn withUser(user)`](#fn-specstartervolumesquobytewithuser)
        * [`fn withVolume(volume)`](#fn-specstartervolumesquobytewithvolume)
      * [`obj spec.starter.volumes.rbd`](#obj-specstartervolumesrbd)
        * [`fn withFsType(fsType)`](#fn-specstartervolumesrbdwithfstype)
        * [`fn withImage(image)`](#fn-specstartervolumesrbdwithimage)
        * [`fn withKeyring(keyring)`](#fn-specstartervolumesrbdwithkeyring)
        * [`fn withMonitors(monitors)`](#fn-specstartervolumesrbdwithmonitors)
        * [`fn withMonitorsMixin(monitors)`](#fn-specstartervolumesrbdwithmonitorsmixin)
        * [`fn withPool(pool)`](#fn-specstartervolumesrbdwithpool)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumesrbdwithreadonly)
        * [`fn withUser(user)`](#fn-specstartervolumesrbdwithuser)
        * [`obj spec.starter.volumes.rbd.secretRef`](#obj-specstartervolumesrbdsecretref)
          * [`fn withName(name)`](#fn-specstartervolumesrbdsecretrefwithname)
      * [`obj spec.starter.volumes.scaleIO`](#obj-specstartervolumesscaleio)
        * [`fn withFsType(fsType)`](#fn-specstartervolumesscaleiowithfstype)
        * [`fn withGateway(gateway)`](#fn-specstartervolumesscaleiowithgateway)
        * [`fn withProtectionDomain(protectionDomain)`](#fn-specstartervolumesscaleiowithprotectiondomain)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumesscaleiowithreadonly)
        * [`fn withSslEnabled(sslEnabled)`](#fn-specstartervolumesscaleiowithsslenabled)
        * [`fn withStorageMode(storageMode)`](#fn-specstartervolumesscaleiowithstoragemode)
        * [`fn withStoragePool(storagePool)`](#fn-specstartervolumesscaleiowithstoragepool)
        * [`fn withSystem(system)`](#fn-specstartervolumesscaleiowithsystem)
        * [`fn withVolumeName(volumeName)`](#fn-specstartervolumesscaleiowithvolumename)
        * [`obj spec.starter.volumes.scaleIO.secretRef`](#obj-specstartervolumesscaleiosecretref)
          * [`fn withName(name)`](#fn-specstartervolumesscaleiosecretrefwithname)
      * [`obj spec.starter.volumes.secret`](#obj-specstartervolumessecret)
        * [`fn withDefaultMode(defaultMode)`](#fn-specstartervolumessecretwithdefaultmode)
        * [`fn withItems(items)`](#fn-specstartervolumessecretwithitems)
        * [`fn withItemsMixin(items)`](#fn-specstartervolumessecretwithitemsmixin)
        * [`fn withOptional(optional)`](#fn-specstartervolumessecretwithoptional)
        * [`fn withSecretName(secretName)`](#fn-specstartervolumessecretwithsecretname)
        * [`obj spec.starter.volumes.secret.items`](#obj-specstartervolumessecretitems)
          * [`fn withKey(key)`](#fn-specstartervolumessecretitemswithkey)
          * [`fn withMode(mode)`](#fn-specstartervolumessecretitemswithmode)
          * [`fn withPath(path)`](#fn-specstartervolumessecretitemswithpath)
      * [`obj spec.starter.volumes.storageos`](#obj-specstartervolumesstorageos)
        * [`fn withFsType(fsType)`](#fn-specstartervolumesstorageoswithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specstartervolumesstorageoswithreadonly)
        * [`fn withVolumeName(volumeName)`](#fn-specstartervolumesstorageoswithvolumename)
        * [`fn withVolumeNamespace(volumeNamespace)`](#fn-specstartervolumesstorageoswithvolumenamespace)
        * [`obj spec.starter.volumes.storageos.secretRef`](#obj-specstartervolumesstorageossecretref)
          * [`fn withName(name)`](#fn-specstartervolumesstorageossecretrefwithname)
      * [`obj spec.starter.volumes.vsphereVolume`](#obj-specstartervolumesvspherevolume)
        * [`fn withFsType(fsType)`](#fn-specstartervolumesvspherevolumewithfstype)
        * [`fn withStoragePolicyID(storagePolicyID)`](#fn-specstartervolumesvspherevolumewithstoragepolicyid)
        * [`fn withStoragePolicyName(storagePolicyName)`](#fn-specstartervolumesvspherevolumewithstoragepolicyname)
        * [`fn withVolumePath(volumePath)`](#fn-specstartervolumesvspherevolumewithvolumepath)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of TestRun

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



### fn spec.withArguments

```ts
withArguments(arguments)
```



### fn spec.withCleanup

```ts
withCleanup(cleanup)
```



### fn spec.withParallelism

```ts
withParallelism(parallelism)
```



### fn spec.withPaused

```ts
withPaused(paused)
```



### fn spec.withPorts

```ts
withPorts(ports)
```



### fn spec.withPortsMixin

```ts
withPortsMixin(ports)
```



**Note:** This function appends passed data to existing values

### fn spec.withQuiet

```ts
withQuiet(quiet)
```



### fn spec.withSeparate

```ts
withSeparate(separate)
```



### fn spec.withTestRunId

```ts
withTestRunId(testRunId)
```



### fn spec.withToken

```ts
withToken(token)
```



## obj spec.initializer



### fn spec.initializer.withAutomountServiceAccountToken

```ts
withAutomountServiceAccountToken(automountServiceAccountToken)
```



### fn spec.initializer.withEnv

```ts
withEnv(env)
```



### fn spec.initializer.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.initializer.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.withImage

```ts
withImage(image)
```



### fn spec.initializer.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.initializer.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.initializer.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.initializer.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.initializer.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.initializer.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.initializer.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.withTopologySpreadConstraints

```ts
withTopologySpreadConstraints(topologySpreadConstraints)
```



### fn spec.initializer.withTopologySpreadConstraintsMixin

```ts
withTopologySpreadConstraintsMixin(topologySpreadConstraints)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.initializer.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.initializer.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity



## obj spec.initializer.affinity.nodeAffinity



### fn spec.initializer.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.initializer.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.initializer.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.initializer.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAffinity



### fn spec.initializer.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.initializer.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.initializer.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.initializer.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.initializer.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAntiAffinity



### fn spec.initializer.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.initializer.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.initializer.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.initializer.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.initializer.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.containerSecurityContext



### fn spec.initializer.containerSecurityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.initializer.containerSecurityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.initializer.containerSecurityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.initializer.containerSecurityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.initializer.containerSecurityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.initializer.containerSecurityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.initializer.containerSecurityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.initializer.containerSecurityContext.appArmorProfile



### fn spec.initializer.containerSecurityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.initializer.containerSecurityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.initializer.containerSecurityContext.capabilities



### fn spec.initializer.containerSecurityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.initializer.containerSecurityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.containerSecurityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.initializer.containerSecurityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.containerSecurityContext.seLinuxOptions



### fn spec.initializer.containerSecurityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.initializer.containerSecurityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.initializer.containerSecurityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.initializer.containerSecurityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.initializer.containerSecurityContext.seccompProfile



### fn spec.initializer.containerSecurityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.initializer.containerSecurityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.initializer.containerSecurityContext.windowsOptions



### fn spec.initializer.containerSecurityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.initializer.containerSecurityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.initializer.containerSecurityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.initializer.containerSecurityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.initializer.env



### fn spec.initializer.env.withName

```ts
withName(name)
```



### fn spec.initializer.env.withValue

```ts
withValue(value)
```



## obj spec.initializer.env.valueFrom



## obj spec.initializer.env.valueFrom.configMapKeyRef



### fn spec.initializer.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.initializer.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.initializer.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.initializer.env.valueFrom.fieldRef



### fn spec.initializer.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.initializer.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.initializer.env.valueFrom.resourceFieldRef



### fn spec.initializer.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.initializer.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.initializer.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.initializer.env.valueFrom.secretKeyRef



### fn spec.initializer.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.initializer.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.initializer.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.initializer.envFrom



### fn spec.initializer.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.initializer.envFrom.configMapRef



### fn spec.initializer.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.initializer.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.initializer.envFrom.secretRef



### fn spec.initializer.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.initializer.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.initializer.imagePullSecrets



### fn spec.initializer.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.initializer.initContainers



### fn spec.initializer.initContainers.withArgs

```ts
withArgs(args)
```



### fn spec.initializer.initContainers.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.initContainers.withCommand

```ts
withCommand(command)
```



### fn spec.initializer.initContainers.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.initContainers.withEnv

```ts
withEnv(env)
```



### fn spec.initializer.initContainers.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.initializer.initContainers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.initContainers.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.initContainers.withImage

```ts
withImage(image)
```



### fn spec.initializer.initContainers.withName

```ts
withName(name)
```



### fn spec.initializer.initContainers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.initializer.initContainers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.initContainers.withWorkingDir

```ts
withWorkingDir(workingDir)
```



## obj spec.initializer.initContainers.env



### fn spec.initializer.initContainers.env.withName

```ts
withName(name)
```



### fn spec.initializer.initContainers.env.withValue

```ts
withValue(value)
```



## obj spec.initializer.initContainers.env.valueFrom



## obj spec.initializer.initContainers.env.valueFrom.configMapKeyRef



### fn spec.initializer.initContainers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.initializer.initContainers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.initializer.initContainers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.initializer.initContainers.env.valueFrom.fieldRef



### fn spec.initializer.initContainers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.initializer.initContainers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.initializer.initContainers.env.valueFrom.resourceFieldRef



### fn spec.initializer.initContainers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.initializer.initContainers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.initializer.initContainers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.initializer.initContainers.env.valueFrom.secretKeyRef



### fn spec.initializer.initContainers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.initializer.initContainers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.initializer.initContainers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.initializer.initContainers.envFrom



### fn spec.initializer.initContainers.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.initializer.initContainers.envFrom.configMapRef



### fn spec.initializer.initContainers.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.initializer.initContainers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.initializer.initContainers.envFrom.secretRef



### fn spec.initializer.initContainers.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.initializer.initContainers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.initializer.initContainers.volumeMounts



### fn spec.initializer.initContainers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.initializer.initContainers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.initializer.initContainers.volumeMounts.withName

```ts
withName(name)
```



### fn spec.initializer.initContainers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.initContainers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.initializer.initContainers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.initializer.initContainers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.initializer.livenessProbe



### fn spec.initializer.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.initializer.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.initializer.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.initializer.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.initializer.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.initializer.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.initializer.livenessProbe.exec



### fn spec.initializer.livenessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.initializer.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.livenessProbe.grpc



### fn spec.initializer.livenessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.initializer.livenessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.initializer.livenessProbe.httpGet



### fn spec.initializer.livenessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.initializer.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.initializer.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.livenessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.initializer.livenessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.initializer.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.initializer.livenessProbe.httpGet.httpHeaders



### fn spec.initializer.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.initializer.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.initializer.livenessProbe.tcpSocket



### fn spec.initializer.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.initializer.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.initializer.metadata



### fn spec.initializer.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.initializer.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.initializer.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.readinessProbe



### fn spec.initializer.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.initializer.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.initializer.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.initializer.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.initializer.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.initializer.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.initializer.readinessProbe.exec



### fn spec.initializer.readinessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.initializer.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.readinessProbe.grpc



### fn spec.initializer.readinessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.initializer.readinessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.initializer.readinessProbe.httpGet



### fn spec.initializer.readinessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.initializer.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.initializer.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.readinessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.initializer.readinessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.initializer.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.initializer.readinessProbe.httpGet.httpHeaders



### fn spec.initializer.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.initializer.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.initializer.readinessProbe.tcpSocket



### fn spec.initializer.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.initializer.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.initializer.resources



### fn spec.initializer.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.initializer.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.initializer.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.initializer.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.resources.claims



### fn spec.initializer.resources.claims.withName

```ts
withName(name)
```



### fn spec.initializer.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.initializer.securityContext



### fn spec.initializer.securityContext.withFsGroup

```ts
withFsGroup(fsGroup)
```



### fn spec.initializer.securityContext.withFsGroupChangePolicy

```ts
withFsGroupChangePolicy(fsGroupChangePolicy)
```



### fn spec.initializer.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.initializer.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.initializer.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



### fn spec.initializer.securityContext.withSupplementalGroups

```ts
withSupplementalGroups(supplementalGroups)
```



### fn spec.initializer.securityContext.withSupplementalGroupsMixin

```ts
withSupplementalGroupsMixin(supplementalGroups)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.securityContext.withSupplementalGroupsPolicy

```ts
withSupplementalGroupsPolicy(supplementalGroupsPolicy)
```



### fn spec.initializer.securityContext.withSysctls

```ts
withSysctls(sysctls)
```



### fn spec.initializer.securityContext.withSysctlsMixin

```ts
withSysctlsMixin(sysctls)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.securityContext.appArmorProfile



### fn spec.initializer.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.initializer.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.initializer.securityContext.seLinuxOptions



### fn spec.initializer.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.initializer.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.initializer.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.initializer.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.initializer.securityContext.seccompProfile



### fn spec.initializer.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.initializer.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.initializer.securityContext.sysctls



### fn spec.initializer.securityContext.sysctls.withName

```ts
withName(name)
```



### fn spec.initializer.securityContext.sysctls.withValue

```ts
withValue(value)
```



## obj spec.initializer.securityContext.windowsOptions



### fn spec.initializer.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.initializer.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.initializer.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.initializer.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.initializer.tolerations



### fn spec.initializer.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.initializer.tolerations.withKey

```ts
withKey(key)
```



### fn spec.initializer.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.initializer.tolerations.withValue

```ts
withValue(value)
```



## obj spec.initializer.topologySpreadConstraints



### fn spec.initializer.topologySpreadConstraints.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.initializer.topologySpreadConstraints.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.topologySpreadConstraints.withMaxSkew

```ts
withMaxSkew(maxSkew)
```



### fn spec.initializer.topologySpreadConstraints.withMinDomains

```ts
withMinDomains(minDomains)
```



### fn spec.initializer.topologySpreadConstraints.withNodeAffinityPolicy

```ts
withNodeAffinityPolicy(nodeAffinityPolicy)
```



### fn spec.initializer.topologySpreadConstraints.withNodeTaintsPolicy

```ts
withNodeTaintsPolicy(nodeTaintsPolicy)
```



### fn spec.initializer.topologySpreadConstraints.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



### fn spec.initializer.topologySpreadConstraints.withWhenUnsatisfiable

```ts
withWhenUnsatisfiable(whenUnsatisfiable)
```



## obj spec.initializer.topologySpreadConstraints.labelSelector



### fn spec.initializer.topologySpreadConstraints.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.initializer.topologySpreadConstraints.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.topologySpreadConstraints.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.initializer.topologySpreadConstraints.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.topologySpreadConstraints.labelSelector.matchExpressions



### fn spec.initializer.topologySpreadConstraints.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.initializer.topologySpreadConstraints.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.topologySpreadConstraints.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.initializer.topologySpreadConstraints.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.volumeMounts



### fn spec.initializer.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.initializer.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.initializer.volumeMounts.withName

```ts
withName(name)
```



### fn spec.initializer.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.initializer.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.initializer.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.initializer.volumes



### fn spec.initializer.volumes.withName

```ts
withName(name)
```



## obj spec.initializer.volumes.awsElasticBlockStore



### fn spec.initializer.volumes.awsElasticBlockStore.withFsType

```ts
withFsType(fsType)
```



### fn spec.initializer.volumes.awsElasticBlockStore.withPartition

```ts
withPartition(partition)
```



### fn spec.initializer.volumes.awsElasticBlockStore.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.volumes.awsElasticBlockStore.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.initializer.volumes.azureDisk



### fn spec.initializer.volumes.azureDisk.withCachingMode

```ts
withCachingMode(cachingMode)
```



### fn spec.initializer.volumes.azureDisk.withDiskName

```ts
withDiskName(diskName)
```



### fn spec.initializer.volumes.azureDisk.withDiskURI

```ts
withDiskURI(diskURI)
```



### fn spec.initializer.volumes.azureDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.initializer.volumes.azureDisk.withKind

```ts
withKind(kind)
```



### fn spec.initializer.volumes.azureDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.initializer.volumes.azureFile



### fn spec.initializer.volumes.azureFile.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.volumes.azureFile.withSecretName

```ts
withSecretName(secretName)
```



### fn spec.initializer.volumes.azureFile.withShareName

```ts
withShareName(shareName)
```



## obj spec.initializer.volumes.cephfs



### fn spec.initializer.volumes.cephfs.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.initializer.volumes.cephfs.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.volumes.cephfs.withPath

```ts
withPath(path)
```



### fn spec.initializer.volumes.cephfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.volumes.cephfs.withSecretFile

```ts
withSecretFile(secretFile)
```



### fn spec.initializer.volumes.cephfs.withUser

```ts
withUser(user)
```



## obj spec.initializer.volumes.cephfs.secretRef



### fn spec.initializer.volumes.cephfs.secretRef.withName

```ts
withName(name)
```



## obj spec.initializer.volumes.cinder



### fn spec.initializer.volumes.cinder.withFsType

```ts
withFsType(fsType)
```



### fn spec.initializer.volumes.cinder.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.volumes.cinder.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.initializer.volumes.cinder.secretRef



### fn spec.initializer.volumes.cinder.secretRef.withName

```ts
withName(name)
```



## obj spec.initializer.volumes.configMap



### fn spec.initializer.volumes.configMap.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.initializer.volumes.configMap.withItems

```ts
withItems(items)
```



### fn spec.initializer.volumes.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.volumes.configMap.withName

```ts
withName(name)
```



### fn spec.initializer.volumes.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.initializer.volumes.configMap.items



### fn spec.initializer.volumes.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.initializer.volumes.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.initializer.volumes.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.initializer.volumes.csi



### fn spec.initializer.volumes.csi.withDriver

```ts
withDriver(driver)
```



### fn spec.initializer.volumes.csi.withFsType

```ts
withFsType(fsType)
```



### fn spec.initializer.volumes.csi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.volumes.csi.withVolumeAttributes

```ts
withVolumeAttributes(volumeAttributes)
```



### fn spec.initializer.volumes.csi.withVolumeAttributesMixin

```ts
withVolumeAttributesMixin(volumeAttributes)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.volumes.csi.nodePublishSecretRef



### fn spec.initializer.volumes.csi.nodePublishSecretRef.withName

```ts
withName(name)
```



## obj spec.initializer.volumes.downwardAPI



### fn spec.initializer.volumes.downwardAPI.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.initializer.volumes.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.initializer.volumes.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.volumes.downwardAPI.items



### fn spec.initializer.volumes.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.initializer.volumes.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.initializer.volumes.downwardAPI.items.fieldRef



### fn spec.initializer.volumes.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.initializer.volumes.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.initializer.volumes.downwardAPI.items.resourceFieldRef



### fn spec.initializer.volumes.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.initializer.volumes.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.initializer.volumes.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.initializer.volumes.emptyDir



### fn spec.initializer.volumes.emptyDir.withMedium

```ts
withMedium(medium)
```



### fn spec.initializer.volumes.emptyDir.withSizeLimit

```ts
withSizeLimit(sizeLimit)
```



## obj spec.initializer.volumes.ephemeral



## obj spec.initializer.volumes.ephemeral.volumeClaimTemplate



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.withMetadata

```ts
withMetadata(metadata)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.withMetadataMixin

```ts
withMetadataMixin(metadata)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModes

```ts
withAccessModes(accessModes)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModesMixin

```ts
withAccessModesMixin(accessModes)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.withStorageClassName

```ts
withStorageClassName(storageClassName)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeAttributesClassName

```ts
withVolumeAttributesClassName(volumeAttributesClassName)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeMode

```ts
withVolumeMode(volumeMode)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.dataSource



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withKind

```ts
withKind(kind)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withName

```ts
withName(name)
```



## obj spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withKind

```ts
withKind(kind)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withName

```ts
withName(name)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.resources



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.selector



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.initializer.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.volumes.fc



### fn spec.initializer.volumes.fc.withFsType

```ts
withFsType(fsType)
```



### fn spec.initializer.volumes.fc.withLun

```ts
withLun(lun)
```



### fn spec.initializer.volumes.fc.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.volumes.fc.withTargetWWNs

```ts
withTargetWWNs(targetWWNs)
```



### fn spec.initializer.volumes.fc.withTargetWWNsMixin

```ts
withTargetWWNsMixin(targetWWNs)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.volumes.fc.withWwids

```ts
withWwids(wwids)
```



### fn spec.initializer.volumes.fc.withWwidsMixin

```ts
withWwidsMixin(wwids)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.volumes.flexVolume



### fn spec.initializer.volumes.flexVolume.withDriver

```ts
withDriver(driver)
```



### fn spec.initializer.volumes.flexVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.initializer.volumes.flexVolume.withOptions

```ts
withOptions(options)
```



### fn spec.initializer.volumes.flexVolume.withOptionsMixin

```ts
withOptionsMixin(options)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.volumes.flexVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.initializer.volumes.flexVolume.secretRef



### fn spec.initializer.volumes.flexVolume.secretRef.withName

```ts
withName(name)
```



## obj spec.initializer.volumes.flocker



### fn spec.initializer.volumes.flocker.withDatasetName

```ts
withDatasetName(datasetName)
```



### fn spec.initializer.volumes.flocker.withDatasetUUID

```ts
withDatasetUUID(datasetUUID)
```



## obj spec.initializer.volumes.gcePersistentDisk



### fn spec.initializer.volumes.gcePersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.initializer.volumes.gcePersistentDisk.withPartition

```ts
withPartition(partition)
```



### fn spec.initializer.volumes.gcePersistentDisk.withPdName

```ts
withPdName(pdName)
```



### fn spec.initializer.volumes.gcePersistentDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.initializer.volumes.gitRepo



### fn spec.initializer.volumes.gitRepo.withDirectory

```ts
withDirectory(directory)
```



### fn spec.initializer.volumes.gitRepo.withRepository

```ts
withRepository(repository)
```



### fn spec.initializer.volumes.gitRepo.withRevision

```ts
withRevision(revision)
```



## obj spec.initializer.volumes.glusterfs



### fn spec.initializer.volumes.glusterfs.withEndpoints

```ts
withEndpoints(endpoints)
```



### fn spec.initializer.volumes.glusterfs.withPath

```ts
withPath(path)
```



### fn spec.initializer.volumes.glusterfs.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.initializer.volumes.hostPath



### fn spec.initializer.volumes.hostPath.withPath

```ts
withPath(path)
```



### fn spec.initializer.volumes.hostPath.withType

```ts
withType(type)
```



## obj spec.initializer.volumes.image



### fn spec.initializer.volumes.image.withPullPolicy

```ts
withPullPolicy(pullPolicy)
```



### fn spec.initializer.volumes.image.withReference

```ts
withReference(reference)
```



## obj spec.initializer.volumes.iscsi



### fn spec.initializer.volumes.iscsi.withChapAuthDiscovery

```ts
withChapAuthDiscovery(chapAuthDiscovery)
```



### fn spec.initializer.volumes.iscsi.withChapAuthSession

```ts
withChapAuthSession(chapAuthSession)
```



### fn spec.initializer.volumes.iscsi.withFsType

```ts
withFsType(fsType)
```



### fn spec.initializer.volumes.iscsi.withInitiatorName

```ts
withInitiatorName(initiatorName)
```



### fn spec.initializer.volumes.iscsi.withIqn

```ts
withIqn(iqn)
```



### fn spec.initializer.volumes.iscsi.withIscsiInterface

```ts
withIscsiInterface(iscsiInterface)
```



### fn spec.initializer.volumes.iscsi.withLun

```ts
withLun(lun)
```



### fn spec.initializer.volumes.iscsi.withPortals

```ts
withPortals(portals)
```



### fn spec.initializer.volumes.iscsi.withPortalsMixin

```ts
withPortalsMixin(portals)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.volumes.iscsi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.volumes.iscsi.withTargetPortal

```ts
withTargetPortal(targetPortal)
```



## obj spec.initializer.volumes.iscsi.secretRef



### fn spec.initializer.volumes.iscsi.secretRef.withName

```ts
withName(name)
```



## obj spec.initializer.volumes.nfs



### fn spec.initializer.volumes.nfs.withPath

```ts
withPath(path)
```



### fn spec.initializer.volumes.nfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.volumes.nfs.withServer

```ts
withServer(server)
```



## obj spec.initializer.volumes.persistentVolumeClaim



### fn spec.initializer.volumes.persistentVolumeClaim.withClaimName

```ts
withClaimName(claimName)
```



### fn spec.initializer.volumes.persistentVolumeClaim.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.initializer.volumes.photonPersistentDisk



### fn spec.initializer.volumes.photonPersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.initializer.volumes.photonPersistentDisk.withPdID

```ts
withPdID(pdID)
```



## obj spec.initializer.volumes.portworxVolume



### fn spec.initializer.volumes.portworxVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.initializer.volumes.portworxVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.volumes.portworxVolume.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.initializer.volumes.projected



### fn spec.initializer.volumes.projected.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.initializer.volumes.projected.withSources

```ts
withSources(sources)
```



### fn spec.initializer.volumes.projected.withSourcesMixin

```ts
withSourcesMixin(sources)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.volumes.projected.sources



## obj spec.initializer.volumes.projected.sources.clusterTrustBundle



### fn spec.initializer.volumes.projected.sources.clusterTrustBundle.withName

```ts
withName(name)
```



### fn spec.initializer.volumes.projected.sources.clusterTrustBundle.withOptional

```ts
withOptional(optional)
```



### fn spec.initializer.volumes.projected.sources.clusterTrustBundle.withPath

```ts
withPath(path)
```



### fn spec.initializer.volumes.projected.sources.clusterTrustBundle.withSignerName

```ts
withSignerName(signerName)
```



## obj spec.initializer.volumes.projected.sources.clusterTrustBundle.labelSelector



### fn spec.initializer.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.initializer.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.initializer.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions



### fn spec.initializer.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.initializer.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.initializer.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.initializer.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.volumes.projected.sources.configMap



### fn spec.initializer.volumes.projected.sources.configMap.withItems

```ts
withItems(items)
```



### fn spec.initializer.volumes.projected.sources.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.volumes.projected.sources.configMap.withName

```ts
withName(name)
```



### fn spec.initializer.volumes.projected.sources.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.initializer.volumes.projected.sources.configMap.items



### fn spec.initializer.volumes.projected.sources.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.initializer.volumes.projected.sources.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.initializer.volumes.projected.sources.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.initializer.volumes.projected.sources.downwardAPI



### fn spec.initializer.volumes.projected.sources.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.initializer.volumes.projected.sources.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.initializer.volumes.projected.sources.downwardAPI.items



### fn spec.initializer.volumes.projected.sources.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.initializer.volumes.projected.sources.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.initializer.volumes.projected.sources.downwardAPI.items.fieldRef



### fn spec.initializer.volumes.projected.sources.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.initializer.volumes.projected.sources.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.initializer.volumes.projected.sources.downwardAPI.items.resourceFieldRef



### fn spec.initializer.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.initializer.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.initializer.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.initializer.volumes.projected.sources.secret



### fn spec.initializer.volumes.projected.sources.secret.withItems

```ts
withItems(items)
```



### fn spec.initializer.volumes.projected.sources.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.volumes.projected.sources.secret.withName

```ts
withName(name)
```



### fn spec.initializer.volumes.projected.sources.secret.withOptional

```ts
withOptional(optional)
```



## obj spec.initializer.volumes.projected.sources.secret.items



### fn spec.initializer.volumes.projected.sources.secret.items.withKey

```ts
withKey(key)
```



### fn spec.initializer.volumes.projected.sources.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.initializer.volumes.projected.sources.secret.items.withPath

```ts
withPath(path)
```



## obj spec.initializer.volumes.projected.sources.serviceAccountToken



### fn spec.initializer.volumes.projected.sources.serviceAccountToken.withAudience

```ts
withAudience(audience)
```



### fn spec.initializer.volumes.projected.sources.serviceAccountToken.withExpirationSeconds

```ts
withExpirationSeconds(expirationSeconds)
```



### fn spec.initializer.volumes.projected.sources.serviceAccountToken.withPath

```ts
withPath(path)
```



## obj spec.initializer.volumes.quobyte



### fn spec.initializer.volumes.quobyte.withGroup

```ts
withGroup(group)
```



### fn spec.initializer.volumes.quobyte.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.volumes.quobyte.withRegistry

```ts
withRegistry(registry)
```



### fn spec.initializer.volumes.quobyte.withTenant

```ts
withTenant(tenant)
```



### fn spec.initializer.volumes.quobyte.withUser

```ts
withUser(user)
```



### fn spec.initializer.volumes.quobyte.withVolume

```ts
withVolume(volume)
```



## obj spec.initializer.volumes.rbd



### fn spec.initializer.volumes.rbd.withFsType

```ts
withFsType(fsType)
```



### fn spec.initializer.volumes.rbd.withImage

```ts
withImage(image)
```



### fn spec.initializer.volumes.rbd.withKeyring

```ts
withKeyring(keyring)
```



### fn spec.initializer.volumes.rbd.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.initializer.volumes.rbd.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.volumes.rbd.withPool

```ts
withPool(pool)
```



### fn spec.initializer.volumes.rbd.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.volumes.rbd.withUser

```ts
withUser(user)
```



## obj spec.initializer.volumes.rbd.secretRef



### fn spec.initializer.volumes.rbd.secretRef.withName

```ts
withName(name)
```



## obj spec.initializer.volumes.scaleIO



### fn spec.initializer.volumes.scaleIO.withFsType

```ts
withFsType(fsType)
```



### fn spec.initializer.volumes.scaleIO.withGateway

```ts
withGateway(gateway)
```



### fn spec.initializer.volumes.scaleIO.withProtectionDomain

```ts
withProtectionDomain(protectionDomain)
```



### fn spec.initializer.volumes.scaleIO.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.volumes.scaleIO.withSslEnabled

```ts
withSslEnabled(sslEnabled)
```



### fn spec.initializer.volumes.scaleIO.withStorageMode

```ts
withStorageMode(storageMode)
```



### fn spec.initializer.volumes.scaleIO.withStoragePool

```ts
withStoragePool(storagePool)
```



### fn spec.initializer.volumes.scaleIO.withSystem

```ts
withSystem(system)
```



### fn spec.initializer.volumes.scaleIO.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.initializer.volumes.scaleIO.secretRef



### fn spec.initializer.volumes.scaleIO.secretRef.withName

```ts
withName(name)
```



## obj spec.initializer.volumes.secret



### fn spec.initializer.volumes.secret.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.initializer.volumes.secret.withItems

```ts
withItems(items)
```



### fn spec.initializer.volumes.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.initializer.volumes.secret.withOptional

```ts
withOptional(optional)
```



### fn spec.initializer.volumes.secret.withSecretName

```ts
withSecretName(secretName)
```



## obj spec.initializer.volumes.secret.items



### fn spec.initializer.volumes.secret.items.withKey

```ts
withKey(key)
```



### fn spec.initializer.volumes.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.initializer.volumes.secret.items.withPath

```ts
withPath(path)
```



## obj spec.initializer.volumes.storageos



### fn spec.initializer.volumes.storageos.withFsType

```ts
withFsType(fsType)
```



### fn spec.initializer.volumes.storageos.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initializer.volumes.storageos.withVolumeName

```ts
withVolumeName(volumeName)
```



### fn spec.initializer.volumes.storageos.withVolumeNamespace

```ts
withVolumeNamespace(volumeNamespace)
```



## obj spec.initializer.volumes.storageos.secretRef



### fn spec.initializer.volumes.storageos.secretRef.withName

```ts
withName(name)
```



## obj spec.initializer.volumes.vsphereVolume



### fn spec.initializer.volumes.vsphereVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.initializer.volumes.vsphereVolume.withStoragePolicyID

```ts
withStoragePolicyID(storagePolicyID)
```



### fn spec.initializer.volumes.vsphereVolume.withStoragePolicyName

```ts
withStoragePolicyName(storagePolicyName)
```



### fn spec.initializer.volumes.vsphereVolume.withVolumePath

```ts
withVolumePath(volumePath)
```



## obj spec.ports



### fn spec.ports.withContainerPort

```ts
withContainerPort(containerPort)
```



### fn spec.ports.withHostIP

```ts
withHostIP(hostIP)
```



### fn spec.ports.withHostPort

```ts
withHostPort(hostPort)
```



### fn spec.ports.withName

```ts
withName(name)
```



### fn spec.ports.withProtocol

```ts
withProtocol(protocol)
```



## obj spec.runner



### fn spec.runner.withAutomountServiceAccountToken

```ts
withAutomountServiceAccountToken(automountServiceAccountToken)
```



### fn spec.runner.withEnv

```ts
withEnv(env)
```



### fn spec.runner.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.runner.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.withImage

```ts
withImage(image)
```



### fn spec.runner.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.runner.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.runner.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.runner.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.runner.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.runner.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.runner.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.withTopologySpreadConstraints

```ts
withTopologySpreadConstraints(topologySpreadConstraints)
```



### fn spec.runner.withTopologySpreadConstraintsMixin

```ts
withTopologySpreadConstraintsMixin(topologySpreadConstraints)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.runner.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.runner.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity



## obj spec.runner.affinity.nodeAffinity



### fn spec.runner.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.runner.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.runner.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.runner.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAffinity



### fn spec.runner.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.runner.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.runner.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.runner.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.runner.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAntiAffinity



### fn spec.runner.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.runner.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.runner.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.runner.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.runner.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.containerSecurityContext



### fn spec.runner.containerSecurityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.runner.containerSecurityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.runner.containerSecurityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.runner.containerSecurityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.runner.containerSecurityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.runner.containerSecurityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.runner.containerSecurityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.runner.containerSecurityContext.appArmorProfile



### fn spec.runner.containerSecurityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.runner.containerSecurityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.runner.containerSecurityContext.capabilities



### fn spec.runner.containerSecurityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.runner.containerSecurityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.containerSecurityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.runner.containerSecurityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.containerSecurityContext.seLinuxOptions



### fn spec.runner.containerSecurityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.runner.containerSecurityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.runner.containerSecurityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.runner.containerSecurityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.runner.containerSecurityContext.seccompProfile



### fn spec.runner.containerSecurityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.runner.containerSecurityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.runner.containerSecurityContext.windowsOptions



### fn spec.runner.containerSecurityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.runner.containerSecurityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.runner.containerSecurityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.runner.containerSecurityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.runner.env



### fn spec.runner.env.withName

```ts
withName(name)
```



### fn spec.runner.env.withValue

```ts
withValue(value)
```



## obj spec.runner.env.valueFrom



## obj spec.runner.env.valueFrom.configMapKeyRef



### fn spec.runner.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.runner.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.runner.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.runner.env.valueFrom.fieldRef



### fn spec.runner.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.runner.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.runner.env.valueFrom.resourceFieldRef



### fn spec.runner.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.runner.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.runner.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.runner.env.valueFrom.secretKeyRef



### fn spec.runner.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.runner.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.runner.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.runner.envFrom



### fn spec.runner.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.runner.envFrom.configMapRef



### fn spec.runner.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.runner.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.runner.envFrom.secretRef



### fn spec.runner.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.runner.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.runner.imagePullSecrets



### fn spec.runner.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.runner.initContainers



### fn spec.runner.initContainers.withArgs

```ts
withArgs(args)
```



### fn spec.runner.initContainers.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.initContainers.withCommand

```ts
withCommand(command)
```



### fn spec.runner.initContainers.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.initContainers.withEnv

```ts
withEnv(env)
```



### fn spec.runner.initContainers.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.runner.initContainers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.initContainers.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.initContainers.withImage

```ts
withImage(image)
```



### fn spec.runner.initContainers.withName

```ts
withName(name)
```



### fn spec.runner.initContainers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.runner.initContainers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.initContainers.withWorkingDir

```ts
withWorkingDir(workingDir)
```



## obj spec.runner.initContainers.env



### fn spec.runner.initContainers.env.withName

```ts
withName(name)
```



### fn spec.runner.initContainers.env.withValue

```ts
withValue(value)
```



## obj spec.runner.initContainers.env.valueFrom



## obj spec.runner.initContainers.env.valueFrom.configMapKeyRef



### fn spec.runner.initContainers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.runner.initContainers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.runner.initContainers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.runner.initContainers.env.valueFrom.fieldRef



### fn spec.runner.initContainers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.runner.initContainers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.runner.initContainers.env.valueFrom.resourceFieldRef



### fn spec.runner.initContainers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.runner.initContainers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.runner.initContainers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.runner.initContainers.env.valueFrom.secretKeyRef



### fn spec.runner.initContainers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.runner.initContainers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.runner.initContainers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.runner.initContainers.envFrom



### fn spec.runner.initContainers.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.runner.initContainers.envFrom.configMapRef



### fn spec.runner.initContainers.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.runner.initContainers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.runner.initContainers.envFrom.secretRef



### fn spec.runner.initContainers.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.runner.initContainers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.runner.initContainers.volumeMounts



### fn spec.runner.initContainers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.runner.initContainers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.runner.initContainers.volumeMounts.withName

```ts
withName(name)
```



### fn spec.runner.initContainers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.initContainers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.runner.initContainers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.runner.initContainers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.runner.livenessProbe



### fn spec.runner.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.runner.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.runner.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.runner.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.runner.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.runner.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.runner.livenessProbe.exec



### fn spec.runner.livenessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.runner.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.livenessProbe.grpc



### fn spec.runner.livenessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.runner.livenessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.runner.livenessProbe.httpGet



### fn spec.runner.livenessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.runner.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.runner.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.livenessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.runner.livenessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.runner.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.runner.livenessProbe.httpGet.httpHeaders



### fn spec.runner.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.runner.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.runner.livenessProbe.tcpSocket



### fn spec.runner.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.runner.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.runner.metadata



### fn spec.runner.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.runner.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.runner.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.readinessProbe



### fn spec.runner.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.runner.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.runner.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.runner.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.runner.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.runner.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.runner.readinessProbe.exec



### fn spec.runner.readinessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.runner.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.readinessProbe.grpc



### fn spec.runner.readinessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.runner.readinessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.runner.readinessProbe.httpGet



### fn spec.runner.readinessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.runner.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.runner.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.readinessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.runner.readinessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.runner.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.runner.readinessProbe.httpGet.httpHeaders



### fn spec.runner.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.runner.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.runner.readinessProbe.tcpSocket



### fn spec.runner.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.runner.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.runner.resources



### fn spec.runner.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.runner.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.runner.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.runner.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.resources.claims



### fn spec.runner.resources.claims.withName

```ts
withName(name)
```



### fn spec.runner.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.runner.securityContext



### fn spec.runner.securityContext.withFsGroup

```ts
withFsGroup(fsGroup)
```



### fn spec.runner.securityContext.withFsGroupChangePolicy

```ts
withFsGroupChangePolicy(fsGroupChangePolicy)
```



### fn spec.runner.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.runner.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.runner.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



### fn spec.runner.securityContext.withSupplementalGroups

```ts
withSupplementalGroups(supplementalGroups)
```



### fn spec.runner.securityContext.withSupplementalGroupsMixin

```ts
withSupplementalGroupsMixin(supplementalGroups)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.securityContext.withSupplementalGroupsPolicy

```ts
withSupplementalGroupsPolicy(supplementalGroupsPolicy)
```



### fn spec.runner.securityContext.withSysctls

```ts
withSysctls(sysctls)
```



### fn spec.runner.securityContext.withSysctlsMixin

```ts
withSysctlsMixin(sysctls)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.securityContext.appArmorProfile



### fn spec.runner.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.runner.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.runner.securityContext.seLinuxOptions



### fn spec.runner.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.runner.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.runner.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.runner.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.runner.securityContext.seccompProfile



### fn spec.runner.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.runner.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.runner.securityContext.sysctls



### fn spec.runner.securityContext.sysctls.withName

```ts
withName(name)
```



### fn spec.runner.securityContext.sysctls.withValue

```ts
withValue(value)
```



## obj spec.runner.securityContext.windowsOptions



### fn spec.runner.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.runner.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.runner.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.runner.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.runner.tolerations



### fn spec.runner.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.runner.tolerations.withKey

```ts
withKey(key)
```



### fn spec.runner.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.runner.tolerations.withValue

```ts
withValue(value)
```



## obj spec.runner.topologySpreadConstraints



### fn spec.runner.topologySpreadConstraints.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.runner.topologySpreadConstraints.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.topologySpreadConstraints.withMaxSkew

```ts
withMaxSkew(maxSkew)
```



### fn spec.runner.topologySpreadConstraints.withMinDomains

```ts
withMinDomains(minDomains)
```



### fn spec.runner.topologySpreadConstraints.withNodeAffinityPolicy

```ts
withNodeAffinityPolicy(nodeAffinityPolicy)
```



### fn spec.runner.topologySpreadConstraints.withNodeTaintsPolicy

```ts
withNodeTaintsPolicy(nodeTaintsPolicy)
```



### fn spec.runner.topologySpreadConstraints.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



### fn spec.runner.topologySpreadConstraints.withWhenUnsatisfiable

```ts
withWhenUnsatisfiable(whenUnsatisfiable)
```



## obj spec.runner.topologySpreadConstraints.labelSelector



### fn spec.runner.topologySpreadConstraints.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.runner.topologySpreadConstraints.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.topologySpreadConstraints.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.runner.topologySpreadConstraints.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.topologySpreadConstraints.labelSelector.matchExpressions



### fn spec.runner.topologySpreadConstraints.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.runner.topologySpreadConstraints.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.topologySpreadConstraints.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.runner.topologySpreadConstraints.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.volumeMounts



### fn spec.runner.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.runner.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.runner.volumeMounts.withName

```ts
withName(name)
```



### fn spec.runner.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.runner.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.runner.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.runner.volumes



### fn spec.runner.volumes.withName

```ts
withName(name)
```



## obj spec.runner.volumes.awsElasticBlockStore



### fn spec.runner.volumes.awsElasticBlockStore.withFsType

```ts
withFsType(fsType)
```



### fn spec.runner.volumes.awsElasticBlockStore.withPartition

```ts
withPartition(partition)
```



### fn spec.runner.volumes.awsElasticBlockStore.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.volumes.awsElasticBlockStore.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.runner.volumes.azureDisk



### fn spec.runner.volumes.azureDisk.withCachingMode

```ts
withCachingMode(cachingMode)
```



### fn spec.runner.volumes.azureDisk.withDiskName

```ts
withDiskName(diskName)
```



### fn spec.runner.volumes.azureDisk.withDiskURI

```ts
withDiskURI(diskURI)
```



### fn spec.runner.volumes.azureDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.runner.volumes.azureDisk.withKind

```ts
withKind(kind)
```



### fn spec.runner.volumes.azureDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.runner.volumes.azureFile



### fn spec.runner.volumes.azureFile.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.volumes.azureFile.withSecretName

```ts
withSecretName(secretName)
```



### fn spec.runner.volumes.azureFile.withShareName

```ts
withShareName(shareName)
```



## obj spec.runner.volumes.cephfs



### fn spec.runner.volumes.cephfs.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.runner.volumes.cephfs.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.volumes.cephfs.withPath

```ts
withPath(path)
```



### fn spec.runner.volumes.cephfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.volumes.cephfs.withSecretFile

```ts
withSecretFile(secretFile)
```



### fn spec.runner.volumes.cephfs.withUser

```ts
withUser(user)
```



## obj spec.runner.volumes.cephfs.secretRef



### fn spec.runner.volumes.cephfs.secretRef.withName

```ts
withName(name)
```



## obj spec.runner.volumes.cinder



### fn spec.runner.volumes.cinder.withFsType

```ts
withFsType(fsType)
```



### fn spec.runner.volumes.cinder.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.volumes.cinder.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.runner.volumes.cinder.secretRef



### fn spec.runner.volumes.cinder.secretRef.withName

```ts
withName(name)
```



## obj spec.runner.volumes.configMap



### fn spec.runner.volumes.configMap.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.runner.volumes.configMap.withItems

```ts
withItems(items)
```



### fn spec.runner.volumes.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.volumes.configMap.withName

```ts
withName(name)
```



### fn spec.runner.volumes.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.runner.volumes.configMap.items



### fn spec.runner.volumes.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.runner.volumes.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.runner.volumes.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.runner.volumes.csi



### fn spec.runner.volumes.csi.withDriver

```ts
withDriver(driver)
```



### fn spec.runner.volumes.csi.withFsType

```ts
withFsType(fsType)
```



### fn spec.runner.volumes.csi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.volumes.csi.withVolumeAttributes

```ts
withVolumeAttributes(volumeAttributes)
```



### fn spec.runner.volumes.csi.withVolumeAttributesMixin

```ts
withVolumeAttributesMixin(volumeAttributes)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.volumes.csi.nodePublishSecretRef



### fn spec.runner.volumes.csi.nodePublishSecretRef.withName

```ts
withName(name)
```



## obj spec.runner.volumes.downwardAPI



### fn spec.runner.volumes.downwardAPI.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.runner.volumes.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.runner.volumes.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.volumes.downwardAPI.items



### fn spec.runner.volumes.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.runner.volumes.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.runner.volumes.downwardAPI.items.fieldRef



### fn spec.runner.volumes.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.runner.volumes.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.runner.volumes.downwardAPI.items.resourceFieldRef



### fn spec.runner.volumes.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.runner.volumes.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.runner.volumes.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.runner.volumes.emptyDir



### fn spec.runner.volumes.emptyDir.withMedium

```ts
withMedium(medium)
```



### fn spec.runner.volumes.emptyDir.withSizeLimit

```ts
withSizeLimit(sizeLimit)
```



## obj spec.runner.volumes.ephemeral



## obj spec.runner.volumes.ephemeral.volumeClaimTemplate



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.withMetadata

```ts
withMetadata(metadata)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.withMetadataMixin

```ts
withMetadataMixin(metadata)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.volumes.ephemeral.volumeClaimTemplate.spec



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModes

```ts
withAccessModes(accessModes)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModesMixin

```ts
withAccessModesMixin(accessModes)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.withStorageClassName

```ts
withStorageClassName(storageClassName)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeAttributesClassName

```ts
withVolumeAttributesClassName(volumeAttributesClassName)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeMode

```ts
withVolumeMode(volumeMode)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.dataSource



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withKind

```ts
withKind(kind)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withName

```ts
withName(name)
```



## obj spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withKind

```ts
withKind(kind)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withName

```ts
withName(name)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.resources



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.selector



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.runner.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.volumes.fc



### fn spec.runner.volumes.fc.withFsType

```ts
withFsType(fsType)
```



### fn spec.runner.volumes.fc.withLun

```ts
withLun(lun)
```



### fn spec.runner.volumes.fc.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.volumes.fc.withTargetWWNs

```ts
withTargetWWNs(targetWWNs)
```



### fn spec.runner.volumes.fc.withTargetWWNsMixin

```ts
withTargetWWNsMixin(targetWWNs)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.volumes.fc.withWwids

```ts
withWwids(wwids)
```



### fn spec.runner.volumes.fc.withWwidsMixin

```ts
withWwidsMixin(wwids)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.volumes.flexVolume



### fn spec.runner.volumes.flexVolume.withDriver

```ts
withDriver(driver)
```



### fn spec.runner.volumes.flexVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.runner.volumes.flexVolume.withOptions

```ts
withOptions(options)
```



### fn spec.runner.volumes.flexVolume.withOptionsMixin

```ts
withOptionsMixin(options)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.volumes.flexVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.runner.volumes.flexVolume.secretRef



### fn spec.runner.volumes.flexVolume.secretRef.withName

```ts
withName(name)
```



## obj spec.runner.volumes.flocker



### fn spec.runner.volumes.flocker.withDatasetName

```ts
withDatasetName(datasetName)
```



### fn spec.runner.volumes.flocker.withDatasetUUID

```ts
withDatasetUUID(datasetUUID)
```



## obj spec.runner.volumes.gcePersistentDisk



### fn spec.runner.volumes.gcePersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.runner.volumes.gcePersistentDisk.withPartition

```ts
withPartition(partition)
```



### fn spec.runner.volumes.gcePersistentDisk.withPdName

```ts
withPdName(pdName)
```



### fn spec.runner.volumes.gcePersistentDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.runner.volumes.gitRepo



### fn spec.runner.volumes.gitRepo.withDirectory

```ts
withDirectory(directory)
```



### fn spec.runner.volumes.gitRepo.withRepository

```ts
withRepository(repository)
```



### fn spec.runner.volumes.gitRepo.withRevision

```ts
withRevision(revision)
```



## obj spec.runner.volumes.glusterfs



### fn spec.runner.volumes.glusterfs.withEndpoints

```ts
withEndpoints(endpoints)
```



### fn spec.runner.volumes.glusterfs.withPath

```ts
withPath(path)
```



### fn spec.runner.volumes.glusterfs.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.runner.volumes.hostPath



### fn spec.runner.volumes.hostPath.withPath

```ts
withPath(path)
```



### fn spec.runner.volumes.hostPath.withType

```ts
withType(type)
```



## obj spec.runner.volumes.image



### fn spec.runner.volumes.image.withPullPolicy

```ts
withPullPolicy(pullPolicy)
```



### fn spec.runner.volumes.image.withReference

```ts
withReference(reference)
```



## obj spec.runner.volumes.iscsi



### fn spec.runner.volumes.iscsi.withChapAuthDiscovery

```ts
withChapAuthDiscovery(chapAuthDiscovery)
```



### fn spec.runner.volumes.iscsi.withChapAuthSession

```ts
withChapAuthSession(chapAuthSession)
```



### fn spec.runner.volumes.iscsi.withFsType

```ts
withFsType(fsType)
```



### fn spec.runner.volumes.iscsi.withInitiatorName

```ts
withInitiatorName(initiatorName)
```



### fn spec.runner.volumes.iscsi.withIqn

```ts
withIqn(iqn)
```



### fn spec.runner.volumes.iscsi.withIscsiInterface

```ts
withIscsiInterface(iscsiInterface)
```



### fn spec.runner.volumes.iscsi.withLun

```ts
withLun(lun)
```



### fn spec.runner.volumes.iscsi.withPortals

```ts
withPortals(portals)
```



### fn spec.runner.volumes.iscsi.withPortalsMixin

```ts
withPortalsMixin(portals)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.volumes.iscsi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.volumes.iscsi.withTargetPortal

```ts
withTargetPortal(targetPortal)
```



## obj spec.runner.volumes.iscsi.secretRef



### fn spec.runner.volumes.iscsi.secretRef.withName

```ts
withName(name)
```



## obj spec.runner.volumes.nfs



### fn spec.runner.volumes.nfs.withPath

```ts
withPath(path)
```



### fn spec.runner.volumes.nfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.volumes.nfs.withServer

```ts
withServer(server)
```



## obj spec.runner.volumes.persistentVolumeClaim



### fn spec.runner.volumes.persistentVolumeClaim.withClaimName

```ts
withClaimName(claimName)
```



### fn spec.runner.volumes.persistentVolumeClaim.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.runner.volumes.photonPersistentDisk



### fn spec.runner.volumes.photonPersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.runner.volumes.photonPersistentDisk.withPdID

```ts
withPdID(pdID)
```



## obj spec.runner.volumes.portworxVolume



### fn spec.runner.volumes.portworxVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.runner.volumes.portworxVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.volumes.portworxVolume.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.runner.volumes.projected



### fn spec.runner.volumes.projected.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.runner.volumes.projected.withSources

```ts
withSources(sources)
```



### fn spec.runner.volumes.projected.withSourcesMixin

```ts
withSourcesMixin(sources)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.volumes.projected.sources



## obj spec.runner.volumes.projected.sources.clusterTrustBundle



### fn spec.runner.volumes.projected.sources.clusterTrustBundle.withName

```ts
withName(name)
```



### fn spec.runner.volumes.projected.sources.clusterTrustBundle.withOptional

```ts
withOptional(optional)
```



### fn spec.runner.volumes.projected.sources.clusterTrustBundle.withPath

```ts
withPath(path)
```



### fn spec.runner.volumes.projected.sources.clusterTrustBundle.withSignerName

```ts
withSignerName(signerName)
```



## obj spec.runner.volumes.projected.sources.clusterTrustBundle.labelSelector



### fn spec.runner.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.runner.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.runner.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions



### fn spec.runner.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.runner.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.runner.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.runner.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.volumes.projected.sources.configMap



### fn spec.runner.volumes.projected.sources.configMap.withItems

```ts
withItems(items)
```



### fn spec.runner.volumes.projected.sources.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.volumes.projected.sources.configMap.withName

```ts
withName(name)
```



### fn spec.runner.volumes.projected.sources.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.runner.volumes.projected.sources.configMap.items



### fn spec.runner.volumes.projected.sources.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.runner.volumes.projected.sources.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.runner.volumes.projected.sources.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.runner.volumes.projected.sources.downwardAPI



### fn spec.runner.volumes.projected.sources.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.runner.volumes.projected.sources.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.runner.volumes.projected.sources.downwardAPI.items



### fn spec.runner.volumes.projected.sources.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.runner.volumes.projected.sources.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.runner.volumes.projected.sources.downwardAPI.items.fieldRef



### fn spec.runner.volumes.projected.sources.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.runner.volumes.projected.sources.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.runner.volumes.projected.sources.downwardAPI.items.resourceFieldRef



### fn spec.runner.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.runner.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.runner.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.runner.volumes.projected.sources.secret



### fn spec.runner.volumes.projected.sources.secret.withItems

```ts
withItems(items)
```



### fn spec.runner.volumes.projected.sources.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.volumes.projected.sources.secret.withName

```ts
withName(name)
```



### fn spec.runner.volumes.projected.sources.secret.withOptional

```ts
withOptional(optional)
```



## obj spec.runner.volumes.projected.sources.secret.items



### fn spec.runner.volumes.projected.sources.secret.items.withKey

```ts
withKey(key)
```



### fn spec.runner.volumes.projected.sources.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.runner.volumes.projected.sources.secret.items.withPath

```ts
withPath(path)
```



## obj spec.runner.volumes.projected.sources.serviceAccountToken



### fn spec.runner.volumes.projected.sources.serviceAccountToken.withAudience

```ts
withAudience(audience)
```



### fn spec.runner.volumes.projected.sources.serviceAccountToken.withExpirationSeconds

```ts
withExpirationSeconds(expirationSeconds)
```



### fn spec.runner.volumes.projected.sources.serviceAccountToken.withPath

```ts
withPath(path)
```



## obj spec.runner.volumes.quobyte



### fn spec.runner.volumes.quobyte.withGroup

```ts
withGroup(group)
```



### fn spec.runner.volumes.quobyte.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.volumes.quobyte.withRegistry

```ts
withRegistry(registry)
```



### fn spec.runner.volumes.quobyte.withTenant

```ts
withTenant(tenant)
```



### fn spec.runner.volumes.quobyte.withUser

```ts
withUser(user)
```



### fn spec.runner.volumes.quobyte.withVolume

```ts
withVolume(volume)
```



## obj spec.runner.volumes.rbd



### fn spec.runner.volumes.rbd.withFsType

```ts
withFsType(fsType)
```



### fn spec.runner.volumes.rbd.withImage

```ts
withImage(image)
```



### fn spec.runner.volumes.rbd.withKeyring

```ts
withKeyring(keyring)
```



### fn spec.runner.volumes.rbd.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.runner.volumes.rbd.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.volumes.rbd.withPool

```ts
withPool(pool)
```



### fn spec.runner.volumes.rbd.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.volumes.rbd.withUser

```ts
withUser(user)
```



## obj spec.runner.volumes.rbd.secretRef



### fn spec.runner.volumes.rbd.secretRef.withName

```ts
withName(name)
```



## obj spec.runner.volumes.scaleIO



### fn spec.runner.volumes.scaleIO.withFsType

```ts
withFsType(fsType)
```



### fn spec.runner.volumes.scaleIO.withGateway

```ts
withGateway(gateway)
```



### fn spec.runner.volumes.scaleIO.withProtectionDomain

```ts
withProtectionDomain(protectionDomain)
```



### fn spec.runner.volumes.scaleIO.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.volumes.scaleIO.withSslEnabled

```ts
withSslEnabled(sslEnabled)
```



### fn spec.runner.volumes.scaleIO.withStorageMode

```ts
withStorageMode(storageMode)
```



### fn spec.runner.volumes.scaleIO.withStoragePool

```ts
withStoragePool(storagePool)
```



### fn spec.runner.volumes.scaleIO.withSystem

```ts
withSystem(system)
```



### fn spec.runner.volumes.scaleIO.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.runner.volumes.scaleIO.secretRef



### fn spec.runner.volumes.scaleIO.secretRef.withName

```ts
withName(name)
```



## obj spec.runner.volumes.secret



### fn spec.runner.volumes.secret.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.runner.volumes.secret.withItems

```ts
withItems(items)
```



### fn spec.runner.volumes.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.runner.volumes.secret.withOptional

```ts
withOptional(optional)
```



### fn spec.runner.volumes.secret.withSecretName

```ts
withSecretName(secretName)
```



## obj spec.runner.volumes.secret.items



### fn spec.runner.volumes.secret.items.withKey

```ts
withKey(key)
```



### fn spec.runner.volumes.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.runner.volumes.secret.items.withPath

```ts
withPath(path)
```



## obj spec.runner.volumes.storageos



### fn spec.runner.volumes.storageos.withFsType

```ts
withFsType(fsType)
```



### fn spec.runner.volumes.storageos.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.runner.volumes.storageos.withVolumeName

```ts
withVolumeName(volumeName)
```



### fn spec.runner.volumes.storageos.withVolumeNamespace

```ts
withVolumeNamespace(volumeNamespace)
```



## obj spec.runner.volumes.storageos.secretRef



### fn spec.runner.volumes.storageos.secretRef.withName

```ts
withName(name)
```



## obj spec.runner.volumes.vsphereVolume



### fn spec.runner.volumes.vsphereVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.runner.volumes.vsphereVolume.withStoragePolicyID

```ts
withStoragePolicyID(storagePolicyID)
```



### fn spec.runner.volumes.vsphereVolume.withStoragePolicyName

```ts
withStoragePolicyName(storagePolicyName)
```



### fn spec.runner.volumes.vsphereVolume.withVolumePath

```ts
withVolumePath(volumePath)
```



## obj spec.script



### fn spec.script.withLocalFile

```ts
withLocalFile(localFile)
```



## obj spec.script.configMap



### fn spec.script.configMap.withFile

```ts
withFile(file)
```



### fn spec.script.configMap.withName

```ts
withName(name)
```



## obj spec.script.volumeClaim



### fn spec.script.volumeClaim.withFile

```ts
withFile(file)
```



### fn spec.script.volumeClaim.withName

```ts
withName(name)
```



### fn spec.script.volumeClaim.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.scuttle



### fn spec.scuttle.withDisableLogging

```ts
withDisableLogging(disableLogging)
```



### fn spec.scuttle.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.scuttle.withEnvoyAdminApi

```ts
withEnvoyAdminApi(envoyAdminApi)
```



### fn spec.scuttle.withGenericQuitEndpoint

```ts
withGenericQuitEndpoint(genericQuitEndpoint)
```



### fn spec.scuttle.withIstioQuitApi

```ts
withIstioQuitApi(istioQuitApi)
```



### fn spec.scuttle.withNeverKillIstio

```ts
withNeverKillIstio(neverKillIstio)
```



### fn spec.scuttle.withNeverKillIstioOnFailure

```ts
withNeverKillIstioOnFailure(neverKillIstioOnFailure)
```



### fn spec.scuttle.withQuitWithoutEnvoyTimeout

```ts
withQuitWithoutEnvoyTimeout(quitWithoutEnvoyTimeout)
```



### fn spec.scuttle.withStartWithoutEnvoy

```ts
withStartWithoutEnvoy(startWithoutEnvoy)
```



### fn spec.scuttle.withWaitForEnvoyTimeout

```ts
withWaitForEnvoyTimeout(waitForEnvoyTimeout)
```



## obj spec.starter



### fn spec.starter.withAutomountServiceAccountToken

```ts
withAutomountServiceAccountToken(automountServiceAccountToken)
```



### fn spec.starter.withEnv

```ts
withEnv(env)
```



### fn spec.starter.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.starter.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.withImage

```ts
withImage(image)
```



### fn spec.starter.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.starter.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.starter.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.starter.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.starter.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.starter.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.starter.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.withTopologySpreadConstraints

```ts
withTopologySpreadConstraints(topologySpreadConstraints)
```



### fn spec.starter.withTopologySpreadConstraintsMixin

```ts
withTopologySpreadConstraintsMixin(topologySpreadConstraints)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.starter.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.starter.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity



## obj spec.starter.affinity.nodeAffinity



### fn spec.starter.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.starter.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.starter.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.starter.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAffinity



### fn spec.starter.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.starter.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.starter.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.starter.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.starter.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAntiAffinity



### fn spec.starter.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.starter.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.starter.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.starter.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.starter.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.containerSecurityContext



### fn spec.starter.containerSecurityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.starter.containerSecurityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.starter.containerSecurityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.starter.containerSecurityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.starter.containerSecurityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.starter.containerSecurityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.starter.containerSecurityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.starter.containerSecurityContext.appArmorProfile



### fn spec.starter.containerSecurityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.starter.containerSecurityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.starter.containerSecurityContext.capabilities



### fn spec.starter.containerSecurityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.starter.containerSecurityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.containerSecurityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.starter.containerSecurityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.containerSecurityContext.seLinuxOptions



### fn spec.starter.containerSecurityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.starter.containerSecurityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.starter.containerSecurityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.starter.containerSecurityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.starter.containerSecurityContext.seccompProfile



### fn spec.starter.containerSecurityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.starter.containerSecurityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.starter.containerSecurityContext.windowsOptions



### fn spec.starter.containerSecurityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.starter.containerSecurityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.starter.containerSecurityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.starter.containerSecurityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.starter.env



### fn spec.starter.env.withName

```ts
withName(name)
```



### fn spec.starter.env.withValue

```ts
withValue(value)
```



## obj spec.starter.env.valueFrom



## obj spec.starter.env.valueFrom.configMapKeyRef



### fn spec.starter.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.starter.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.starter.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.starter.env.valueFrom.fieldRef



### fn spec.starter.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.starter.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.starter.env.valueFrom.resourceFieldRef



### fn spec.starter.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.starter.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.starter.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.starter.env.valueFrom.secretKeyRef



### fn spec.starter.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.starter.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.starter.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.starter.envFrom



### fn spec.starter.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.starter.envFrom.configMapRef



### fn spec.starter.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.starter.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.starter.envFrom.secretRef



### fn spec.starter.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.starter.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.starter.imagePullSecrets



### fn spec.starter.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.starter.initContainers



### fn spec.starter.initContainers.withArgs

```ts
withArgs(args)
```



### fn spec.starter.initContainers.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.initContainers.withCommand

```ts
withCommand(command)
```



### fn spec.starter.initContainers.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.initContainers.withEnv

```ts
withEnv(env)
```



### fn spec.starter.initContainers.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.starter.initContainers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.initContainers.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.initContainers.withImage

```ts
withImage(image)
```



### fn spec.starter.initContainers.withName

```ts
withName(name)
```



### fn spec.starter.initContainers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.starter.initContainers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.initContainers.withWorkingDir

```ts
withWorkingDir(workingDir)
```



## obj spec.starter.initContainers.env



### fn spec.starter.initContainers.env.withName

```ts
withName(name)
```



### fn spec.starter.initContainers.env.withValue

```ts
withValue(value)
```



## obj spec.starter.initContainers.env.valueFrom



## obj spec.starter.initContainers.env.valueFrom.configMapKeyRef



### fn spec.starter.initContainers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.starter.initContainers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.starter.initContainers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.starter.initContainers.env.valueFrom.fieldRef



### fn spec.starter.initContainers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.starter.initContainers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.starter.initContainers.env.valueFrom.resourceFieldRef



### fn spec.starter.initContainers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.starter.initContainers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.starter.initContainers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.starter.initContainers.env.valueFrom.secretKeyRef



### fn spec.starter.initContainers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.starter.initContainers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.starter.initContainers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.starter.initContainers.envFrom



### fn spec.starter.initContainers.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.starter.initContainers.envFrom.configMapRef



### fn spec.starter.initContainers.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.starter.initContainers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.starter.initContainers.envFrom.secretRef



### fn spec.starter.initContainers.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.starter.initContainers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.starter.initContainers.volumeMounts



### fn spec.starter.initContainers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.starter.initContainers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.starter.initContainers.volumeMounts.withName

```ts
withName(name)
```



### fn spec.starter.initContainers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.initContainers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.starter.initContainers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.starter.initContainers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.starter.livenessProbe



### fn spec.starter.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.starter.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.starter.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.starter.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.starter.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.starter.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.starter.livenessProbe.exec



### fn spec.starter.livenessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.starter.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.livenessProbe.grpc



### fn spec.starter.livenessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.starter.livenessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.starter.livenessProbe.httpGet



### fn spec.starter.livenessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.starter.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.starter.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.livenessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.starter.livenessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.starter.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.starter.livenessProbe.httpGet.httpHeaders



### fn spec.starter.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.starter.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.starter.livenessProbe.tcpSocket



### fn spec.starter.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.starter.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.starter.metadata



### fn spec.starter.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.starter.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.starter.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.readinessProbe



### fn spec.starter.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.starter.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.starter.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.starter.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.starter.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.starter.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.starter.readinessProbe.exec



### fn spec.starter.readinessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.starter.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.readinessProbe.grpc



### fn spec.starter.readinessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.starter.readinessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.starter.readinessProbe.httpGet



### fn spec.starter.readinessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.starter.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.starter.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.readinessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.starter.readinessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.starter.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.starter.readinessProbe.httpGet.httpHeaders



### fn spec.starter.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.starter.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.starter.readinessProbe.tcpSocket



### fn spec.starter.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.starter.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.starter.resources



### fn spec.starter.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.starter.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.starter.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.starter.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.resources.claims



### fn spec.starter.resources.claims.withName

```ts
withName(name)
```



### fn spec.starter.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.starter.securityContext



### fn spec.starter.securityContext.withFsGroup

```ts
withFsGroup(fsGroup)
```



### fn spec.starter.securityContext.withFsGroupChangePolicy

```ts
withFsGroupChangePolicy(fsGroupChangePolicy)
```



### fn spec.starter.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.starter.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.starter.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



### fn spec.starter.securityContext.withSupplementalGroups

```ts
withSupplementalGroups(supplementalGroups)
```



### fn spec.starter.securityContext.withSupplementalGroupsMixin

```ts
withSupplementalGroupsMixin(supplementalGroups)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.securityContext.withSupplementalGroupsPolicy

```ts
withSupplementalGroupsPolicy(supplementalGroupsPolicy)
```



### fn spec.starter.securityContext.withSysctls

```ts
withSysctls(sysctls)
```



### fn spec.starter.securityContext.withSysctlsMixin

```ts
withSysctlsMixin(sysctls)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.securityContext.appArmorProfile



### fn spec.starter.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.starter.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.starter.securityContext.seLinuxOptions



### fn spec.starter.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.starter.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.starter.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.starter.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.starter.securityContext.seccompProfile



### fn spec.starter.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.starter.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.starter.securityContext.sysctls



### fn spec.starter.securityContext.sysctls.withName

```ts
withName(name)
```



### fn spec.starter.securityContext.sysctls.withValue

```ts
withValue(value)
```



## obj spec.starter.securityContext.windowsOptions



### fn spec.starter.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.starter.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.starter.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.starter.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.starter.tolerations



### fn spec.starter.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.starter.tolerations.withKey

```ts
withKey(key)
```



### fn spec.starter.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.starter.tolerations.withValue

```ts
withValue(value)
```



## obj spec.starter.topologySpreadConstraints



### fn spec.starter.topologySpreadConstraints.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.starter.topologySpreadConstraints.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.topologySpreadConstraints.withMaxSkew

```ts
withMaxSkew(maxSkew)
```



### fn spec.starter.topologySpreadConstraints.withMinDomains

```ts
withMinDomains(minDomains)
```



### fn spec.starter.topologySpreadConstraints.withNodeAffinityPolicy

```ts
withNodeAffinityPolicy(nodeAffinityPolicy)
```



### fn spec.starter.topologySpreadConstraints.withNodeTaintsPolicy

```ts
withNodeTaintsPolicy(nodeTaintsPolicy)
```



### fn spec.starter.topologySpreadConstraints.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



### fn spec.starter.topologySpreadConstraints.withWhenUnsatisfiable

```ts
withWhenUnsatisfiable(whenUnsatisfiable)
```



## obj spec.starter.topologySpreadConstraints.labelSelector



### fn spec.starter.topologySpreadConstraints.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.starter.topologySpreadConstraints.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.topologySpreadConstraints.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.starter.topologySpreadConstraints.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.topologySpreadConstraints.labelSelector.matchExpressions



### fn spec.starter.topologySpreadConstraints.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.starter.topologySpreadConstraints.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.topologySpreadConstraints.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.starter.topologySpreadConstraints.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.volumeMounts



### fn spec.starter.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.starter.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.starter.volumeMounts.withName

```ts
withName(name)
```



### fn spec.starter.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.starter.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.starter.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.starter.volumes



### fn spec.starter.volumes.withName

```ts
withName(name)
```



## obj spec.starter.volumes.awsElasticBlockStore



### fn spec.starter.volumes.awsElasticBlockStore.withFsType

```ts
withFsType(fsType)
```



### fn spec.starter.volumes.awsElasticBlockStore.withPartition

```ts
withPartition(partition)
```



### fn spec.starter.volumes.awsElasticBlockStore.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.volumes.awsElasticBlockStore.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.starter.volumes.azureDisk



### fn spec.starter.volumes.azureDisk.withCachingMode

```ts
withCachingMode(cachingMode)
```



### fn spec.starter.volumes.azureDisk.withDiskName

```ts
withDiskName(diskName)
```



### fn spec.starter.volumes.azureDisk.withDiskURI

```ts
withDiskURI(diskURI)
```



### fn spec.starter.volumes.azureDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.starter.volumes.azureDisk.withKind

```ts
withKind(kind)
```



### fn spec.starter.volumes.azureDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.starter.volumes.azureFile



### fn spec.starter.volumes.azureFile.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.volumes.azureFile.withSecretName

```ts
withSecretName(secretName)
```



### fn spec.starter.volumes.azureFile.withShareName

```ts
withShareName(shareName)
```



## obj spec.starter.volumes.cephfs



### fn spec.starter.volumes.cephfs.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.starter.volumes.cephfs.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.volumes.cephfs.withPath

```ts
withPath(path)
```



### fn spec.starter.volumes.cephfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.volumes.cephfs.withSecretFile

```ts
withSecretFile(secretFile)
```



### fn spec.starter.volumes.cephfs.withUser

```ts
withUser(user)
```



## obj spec.starter.volumes.cephfs.secretRef



### fn spec.starter.volumes.cephfs.secretRef.withName

```ts
withName(name)
```



## obj spec.starter.volumes.cinder



### fn spec.starter.volumes.cinder.withFsType

```ts
withFsType(fsType)
```



### fn spec.starter.volumes.cinder.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.volumes.cinder.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.starter.volumes.cinder.secretRef



### fn spec.starter.volumes.cinder.secretRef.withName

```ts
withName(name)
```



## obj spec.starter.volumes.configMap



### fn spec.starter.volumes.configMap.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.starter.volumes.configMap.withItems

```ts
withItems(items)
```



### fn spec.starter.volumes.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.volumes.configMap.withName

```ts
withName(name)
```



### fn spec.starter.volumes.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.starter.volumes.configMap.items



### fn spec.starter.volumes.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.starter.volumes.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.starter.volumes.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.starter.volumes.csi



### fn spec.starter.volumes.csi.withDriver

```ts
withDriver(driver)
```



### fn spec.starter.volumes.csi.withFsType

```ts
withFsType(fsType)
```



### fn spec.starter.volumes.csi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.volumes.csi.withVolumeAttributes

```ts
withVolumeAttributes(volumeAttributes)
```



### fn spec.starter.volumes.csi.withVolumeAttributesMixin

```ts
withVolumeAttributesMixin(volumeAttributes)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.volumes.csi.nodePublishSecretRef



### fn spec.starter.volumes.csi.nodePublishSecretRef.withName

```ts
withName(name)
```



## obj spec.starter.volumes.downwardAPI



### fn spec.starter.volumes.downwardAPI.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.starter.volumes.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.starter.volumes.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.volumes.downwardAPI.items



### fn spec.starter.volumes.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.starter.volumes.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.starter.volumes.downwardAPI.items.fieldRef



### fn spec.starter.volumes.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.starter.volumes.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.starter.volumes.downwardAPI.items.resourceFieldRef



### fn spec.starter.volumes.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.starter.volumes.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.starter.volumes.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.starter.volumes.emptyDir



### fn spec.starter.volumes.emptyDir.withMedium

```ts
withMedium(medium)
```



### fn spec.starter.volumes.emptyDir.withSizeLimit

```ts
withSizeLimit(sizeLimit)
```



## obj spec.starter.volumes.ephemeral



## obj spec.starter.volumes.ephemeral.volumeClaimTemplate



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.withMetadata

```ts
withMetadata(metadata)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.withMetadataMixin

```ts
withMetadataMixin(metadata)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.volumes.ephemeral.volumeClaimTemplate.spec



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModes

```ts
withAccessModes(accessModes)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModesMixin

```ts
withAccessModesMixin(accessModes)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.withStorageClassName

```ts
withStorageClassName(storageClassName)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeAttributesClassName

```ts
withVolumeAttributesClassName(volumeAttributesClassName)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeMode

```ts
withVolumeMode(volumeMode)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.dataSource



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withKind

```ts
withKind(kind)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withName

```ts
withName(name)
```



## obj spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withKind

```ts
withKind(kind)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withName

```ts
withName(name)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.resources



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.selector



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.starter.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.volumes.fc



### fn spec.starter.volumes.fc.withFsType

```ts
withFsType(fsType)
```



### fn spec.starter.volumes.fc.withLun

```ts
withLun(lun)
```



### fn spec.starter.volumes.fc.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.volumes.fc.withTargetWWNs

```ts
withTargetWWNs(targetWWNs)
```



### fn spec.starter.volumes.fc.withTargetWWNsMixin

```ts
withTargetWWNsMixin(targetWWNs)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.volumes.fc.withWwids

```ts
withWwids(wwids)
```



### fn spec.starter.volumes.fc.withWwidsMixin

```ts
withWwidsMixin(wwids)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.volumes.flexVolume



### fn spec.starter.volumes.flexVolume.withDriver

```ts
withDriver(driver)
```



### fn spec.starter.volumes.flexVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.starter.volumes.flexVolume.withOptions

```ts
withOptions(options)
```



### fn spec.starter.volumes.flexVolume.withOptionsMixin

```ts
withOptionsMixin(options)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.volumes.flexVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.starter.volumes.flexVolume.secretRef



### fn spec.starter.volumes.flexVolume.secretRef.withName

```ts
withName(name)
```



## obj spec.starter.volumes.flocker



### fn spec.starter.volumes.flocker.withDatasetName

```ts
withDatasetName(datasetName)
```



### fn spec.starter.volumes.flocker.withDatasetUUID

```ts
withDatasetUUID(datasetUUID)
```



## obj spec.starter.volumes.gcePersistentDisk



### fn spec.starter.volumes.gcePersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.starter.volumes.gcePersistentDisk.withPartition

```ts
withPartition(partition)
```



### fn spec.starter.volumes.gcePersistentDisk.withPdName

```ts
withPdName(pdName)
```



### fn spec.starter.volumes.gcePersistentDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.starter.volumes.gitRepo



### fn spec.starter.volumes.gitRepo.withDirectory

```ts
withDirectory(directory)
```



### fn spec.starter.volumes.gitRepo.withRepository

```ts
withRepository(repository)
```



### fn spec.starter.volumes.gitRepo.withRevision

```ts
withRevision(revision)
```



## obj spec.starter.volumes.glusterfs



### fn spec.starter.volumes.glusterfs.withEndpoints

```ts
withEndpoints(endpoints)
```



### fn spec.starter.volumes.glusterfs.withPath

```ts
withPath(path)
```



### fn spec.starter.volumes.glusterfs.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.starter.volumes.hostPath



### fn spec.starter.volumes.hostPath.withPath

```ts
withPath(path)
```



### fn spec.starter.volumes.hostPath.withType

```ts
withType(type)
```



## obj spec.starter.volumes.image



### fn spec.starter.volumes.image.withPullPolicy

```ts
withPullPolicy(pullPolicy)
```



### fn spec.starter.volumes.image.withReference

```ts
withReference(reference)
```



## obj spec.starter.volumes.iscsi



### fn spec.starter.volumes.iscsi.withChapAuthDiscovery

```ts
withChapAuthDiscovery(chapAuthDiscovery)
```



### fn spec.starter.volumes.iscsi.withChapAuthSession

```ts
withChapAuthSession(chapAuthSession)
```



### fn spec.starter.volumes.iscsi.withFsType

```ts
withFsType(fsType)
```



### fn spec.starter.volumes.iscsi.withInitiatorName

```ts
withInitiatorName(initiatorName)
```



### fn spec.starter.volumes.iscsi.withIqn

```ts
withIqn(iqn)
```



### fn spec.starter.volumes.iscsi.withIscsiInterface

```ts
withIscsiInterface(iscsiInterface)
```



### fn spec.starter.volumes.iscsi.withLun

```ts
withLun(lun)
```



### fn spec.starter.volumes.iscsi.withPortals

```ts
withPortals(portals)
```



### fn spec.starter.volumes.iscsi.withPortalsMixin

```ts
withPortalsMixin(portals)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.volumes.iscsi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.volumes.iscsi.withTargetPortal

```ts
withTargetPortal(targetPortal)
```



## obj spec.starter.volumes.iscsi.secretRef



### fn spec.starter.volumes.iscsi.secretRef.withName

```ts
withName(name)
```



## obj spec.starter.volumes.nfs



### fn spec.starter.volumes.nfs.withPath

```ts
withPath(path)
```



### fn spec.starter.volumes.nfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.volumes.nfs.withServer

```ts
withServer(server)
```



## obj spec.starter.volumes.persistentVolumeClaim



### fn spec.starter.volumes.persistentVolumeClaim.withClaimName

```ts
withClaimName(claimName)
```



### fn spec.starter.volumes.persistentVolumeClaim.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.starter.volumes.photonPersistentDisk



### fn spec.starter.volumes.photonPersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.starter.volumes.photonPersistentDisk.withPdID

```ts
withPdID(pdID)
```



## obj spec.starter.volumes.portworxVolume



### fn spec.starter.volumes.portworxVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.starter.volumes.portworxVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.volumes.portworxVolume.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.starter.volumes.projected



### fn spec.starter.volumes.projected.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.starter.volumes.projected.withSources

```ts
withSources(sources)
```



### fn spec.starter.volumes.projected.withSourcesMixin

```ts
withSourcesMixin(sources)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.volumes.projected.sources



## obj spec.starter.volumes.projected.sources.clusterTrustBundle



### fn spec.starter.volumes.projected.sources.clusterTrustBundle.withName

```ts
withName(name)
```



### fn spec.starter.volumes.projected.sources.clusterTrustBundle.withOptional

```ts
withOptional(optional)
```



### fn spec.starter.volumes.projected.sources.clusterTrustBundle.withPath

```ts
withPath(path)
```



### fn spec.starter.volumes.projected.sources.clusterTrustBundle.withSignerName

```ts
withSignerName(signerName)
```



## obj spec.starter.volumes.projected.sources.clusterTrustBundle.labelSelector



### fn spec.starter.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.starter.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.starter.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions



### fn spec.starter.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.starter.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.starter.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.starter.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.volumes.projected.sources.configMap



### fn spec.starter.volumes.projected.sources.configMap.withItems

```ts
withItems(items)
```



### fn spec.starter.volumes.projected.sources.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.volumes.projected.sources.configMap.withName

```ts
withName(name)
```



### fn spec.starter.volumes.projected.sources.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.starter.volumes.projected.sources.configMap.items



### fn spec.starter.volumes.projected.sources.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.starter.volumes.projected.sources.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.starter.volumes.projected.sources.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.starter.volumes.projected.sources.downwardAPI



### fn spec.starter.volumes.projected.sources.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.starter.volumes.projected.sources.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.starter.volumes.projected.sources.downwardAPI.items



### fn spec.starter.volumes.projected.sources.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.starter.volumes.projected.sources.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.starter.volumes.projected.sources.downwardAPI.items.fieldRef



### fn spec.starter.volumes.projected.sources.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.starter.volumes.projected.sources.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.starter.volumes.projected.sources.downwardAPI.items.resourceFieldRef



### fn spec.starter.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.starter.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.starter.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.starter.volumes.projected.sources.secret



### fn spec.starter.volumes.projected.sources.secret.withItems

```ts
withItems(items)
```



### fn spec.starter.volumes.projected.sources.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.volumes.projected.sources.secret.withName

```ts
withName(name)
```



### fn spec.starter.volumes.projected.sources.secret.withOptional

```ts
withOptional(optional)
```



## obj spec.starter.volumes.projected.sources.secret.items



### fn spec.starter.volumes.projected.sources.secret.items.withKey

```ts
withKey(key)
```



### fn spec.starter.volumes.projected.sources.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.starter.volumes.projected.sources.secret.items.withPath

```ts
withPath(path)
```



## obj spec.starter.volumes.projected.sources.serviceAccountToken



### fn spec.starter.volumes.projected.sources.serviceAccountToken.withAudience

```ts
withAudience(audience)
```



### fn spec.starter.volumes.projected.sources.serviceAccountToken.withExpirationSeconds

```ts
withExpirationSeconds(expirationSeconds)
```



### fn spec.starter.volumes.projected.sources.serviceAccountToken.withPath

```ts
withPath(path)
```



## obj spec.starter.volumes.quobyte



### fn spec.starter.volumes.quobyte.withGroup

```ts
withGroup(group)
```



### fn spec.starter.volumes.quobyte.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.volumes.quobyte.withRegistry

```ts
withRegistry(registry)
```



### fn spec.starter.volumes.quobyte.withTenant

```ts
withTenant(tenant)
```



### fn spec.starter.volumes.quobyte.withUser

```ts
withUser(user)
```



### fn spec.starter.volumes.quobyte.withVolume

```ts
withVolume(volume)
```



## obj spec.starter.volumes.rbd



### fn spec.starter.volumes.rbd.withFsType

```ts
withFsType(fsType)
```



### fn spec.starter.volumes.rbd.withImage

```ts
withImage(image)
```



### fn spec.starter.volumes.rbd.withKeyring

```ts
withKeyring(keyring)
```



### fn spec.starter.volumes.rbd.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.starter.volumes.rbd.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.volumes.rbd.withPool

```ts
withPool(pool)
```



### fn spec.starter.volumes.rbd.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.volumes.rbd.withUser

```ts
withUser(user)
```



## obj spec.starter.volumes.rbd.secretRef



### fn spec.starter.volumes.rbd.secretRef.withName

```ts
withName(name)
```



## obj spec.starter.volumes.scaleIO



### fn spec.starter.volumes.scaleIO.withFsType

```ts
withFsType(fsType)
```



### fn spec.starter.volumes.scaleIO.withGateway

```ts
withGateway(gateway)
```



### fn spec.starter.volumes.scaleIO.withProtectionDomain

```ts
withProtectionDomain(protectionDomain)
```



### fn spec.starter.volumes.scaleIO.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.volumes.scaleIO.withSslEnabled

```ts
withSslEnabled(sslEnabled)
```



### fn spec.starter.volumes.scaleIO.withStorageMode

```ts
withStorageMode(storageMode)
```



### fn spec.starter.volumes.scaleIO.withStoragePool

```ts
withStoragePool(storagePool)
```



### fn spec.starter.volumes.scaleIO.withSystem

```ts
withSystem(system)
```



### fn spec.starter.volumes.scaleIO.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.starter.volumes.scaleIO.secretRef



### fn spec.starter.volumes.scaleIO.secretRef.withName

```ts
withName(name)
```



## obj spec.starter.volumes.secret



### fn spec.starter.volumes.secret.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.starter.volumes.secret.withItems

```ts
withItems(items)
```



### fn spec.starter.volumes.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.starter.volumes.secret.withOptional

```ts
withOptional(optional)
```



### fn spec.starter.volumes.secret.withSecretName

```ts
withSecretName(secretName)
```



## obj spec.starter.volumes.secret.items



### fn spec.starter.volumes.secret.items.withKey

```ts
withKey(key)
```



### fn spec.starter.volumes.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.starter.volumes.secret.items.withPath

```ts
withPath(path)
```



## obj spec.starter.volumes.storageos



### fn spec.starter.volumes.storageos.withFsType

```ts
withFsType(fsType)
```



### fn spec.starter.volumes.storageos.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.starter.volumes.storageos.withVolumeName

```ts
withVolumeName(volumeName)
```



### fn spec.starter.volumes.storageos.withVolumeNamespace

```ts
withVolumeNamespace(volumeNamespace)
```



## obj spec.starter.volumes.storageos.secretRef



### fn spec.starter.volumes.storageos.secretRef.withName

```ts
withName(name)
```



## obj spec.starter.volumes.vsphereVolume



### fn spec.starter.volumes.vsphereVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.starter.volumes.vsphereVolume.withStoragePolicyID

```ts
withStoragePolicyID(storagePolicyID)
```



### fn spec.starter.volumes.vsphereVolume.withStoragePolicyName

```ts
withStoragePolicyName(storagePolicyName)
```



### fn spec.starter.volumes.vsphereVolume.withVolumePath

```ts
withVolumePath(volumePath)
```

