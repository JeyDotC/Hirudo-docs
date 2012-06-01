

- - -

#Namespace Symfony\Component\DependencyInjection\Compiler#

<table class="title">
<tr><th colspan="2" class="title">Class Summary</th></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/analyzeservicereferencespass.html">AnalyzeServiceReferencesPass</a></td><td class="description">Run this pass before passes that need to know more about the relation of
your services.
</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/checkcircularreferencespass.html">CheckCircularReferencesPass</a></td><td class="description">Checks your services for circular referencesReferences from method calls are ignored since we might be able to resolve
these references depending on the order in which services are called.
</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/checkdefinitionvaliditypass.html">CheckDefinitionValidityPass</a></td><td class="description">This pass validates each definition individually only taking the information
into account which is contained in the definition itself.
</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/checkexceptiononinvalidreferencebehaviorpass.html">CheckExceptionOnInvalidReferenceBehaviorPass</a></td><td class="description">Checks that all references are pointing to a valid service.</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/checkreferencevaliditypass.html">CheckReferenceValidityPass</a></td><td class="description">Checks the validity of referencesThe following checks are performed by this pass:

target definitions are not abstract
target definitions are of equal or wider scope

- target definitions are in the same scope hierarchy</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/compiler.html">Compiler</a></td><td class="description">This class is used to remove circular dependencies between individual passes.</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/inlineservicedefinitionspass.html">InlineServiceDefinitionsPass</a></td><td class="description">Inline service definitions where this is possible.</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/loggingformatter.html">LoggingFormatter</a></td><td class="description">Used to format logging messages during the compilation.</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/mergeextensionconfigurationpass.html">MergeExtensionConfigurationPass</a></td><td class="description">Merges extension configs into the container builder</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/passconfig.html">PassConfig</a></td><td class="description">Compiler Pass ConfigurationThis class has a default configuration embedded.</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/removeabstractdefinitionspass.html">RemoveAbstractDefinitionsPass</a></td><td class="description">Removes abstract Definitions</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/removeprivatealiasespass.html">RemovePrivateAliasesPass</a></td><td class="description">Remove private aliases from the container. </td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/removeunuseddefinitionspass.html">RemoveUnusedDefinitionsPass</a></td><td class="description">Removes unused service definitions from the container.</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/repeatedpass.html">RepeatedPass</a></td><td class="description">A pass that might be run repeatedly.</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/replacealiasbyactualdefinitionpass.html">ReplaceAliasByActualDefinitionPass</a></td><td class="description">Replaces aliases with actual service definitions, effectively removing these
aliases.</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/resolvedefinitiontemplatespass.html">ResolveDefinitionTemplatesPass</a></td><td class="description">This replaces all DefinitionDecorator instances with their equivalent fully
merged Definition instance.</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/resolveinvalidreferencespass.html">ResolveInvalidReferencesPass</a></td><td class="description">Emulates the invalid behavior if the reference is not found within the
container.</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/resolveparameterplaceholderspass.html">ResolveParameterPlaceHoldersPass</a></td><td class="description">Resolves all parameter placeholders "%somevalue%" to their real values.</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/resolvereferencestoaliasespass.html">ResolveReferencesToAliasesPass</a></td><td class="description">Replaces all references to aliases with references to the actual service.</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/servicereferencegraph.html">ServiceReferenceGraph</a></td><td class="description">This is a directed graph of your services.
</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/servicereferencegraphedge.html">ServiceReferenceGraphEdge</a></td><td class="description">Represents an edge in your service graph.
</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/servicereferencegraphnode.html">ServiceReferenceGraphNode</a></td><td class="description">Represents a node in your service graph.
</td></tr>
</table>

<table class="title">
<tr><th colspan="2" class="title">Interface Summary</th></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/compilerpassinterface.html">CompilerPassInterface</a></td><td class="description">Interface that must be implemented by compilation passes</td></tr>
<tr><td class="name"><a href="https://github.com/JeyDotC/Hirudo-docs/blob/master/symfony/component/dependencyinjection/compiler/repeatablepassinterface.html">RepeatablePassInterface</a></td><td class="description">Interface that must be implemented by passes that are run as part of an
RepeatedPass.</td></tr>
</table>

<table class="title">
<tr><th colspan="2" class="title">Function Summary</th></tr>
<tr><td class="name"><a href="package-functions.md#addPass">addPass</a></td><td class="description">Adds a pass.</td></tr>
<tr><td class="name"><a href="package-functions.md#getAfterRemovingPasses">getAfterRemovingPasses</a></td><td class="description">Gets all passes for the AfterRemoving pass.</td></tr>
<tr><td class="name"><a href="package-functions.md#getBeforeOptimizationPasses">getBeforeOptimizationPasses</a></td><td class="description">Gets all passes for the BeforeOptimization pass.</td></tr>
<tr><td class="name"><a href="package-functions.md#getBeforeRemovingPasses">getBeforeRemovingPasses</a></td><td class="description">Gets all passes for the BeforeRemoving pass.</td></tr>
<tr><td class="name"><a href="package-functions.md#getMergePass">getMergePass</a></td><td class="description">Gets all passes for the Merge pass.</td></tr>
<tr><td class="name"><a href="package-functions.md#getOptimizationPasses">getOptimizationPasses</a></td><td class="description">Gets all passes for the Optimization pass.</td></tr>
<tr><td class="name"><a href="package-functions.md#getPasses">getPasses</a></td><td class="description">Returns all passes in order to be processed.</td></tr>
<tr><td class="name"><a href="package-functions.md#getRemovingPasses">getRemovingPasses</a></td><td class="description">Gets all passes for the Removing pass.</td></tr>
<tr><td class="name"><a href="package-functions.md#setAfterRemovingPasses">setAfterRemovingPasses</a></td><td class="description">Sets the AfterRemoving passes.</td></tr>
<tr><td class="name"><a href="package-functions.md#setBeforeOptimizationPasses">setBeforeOptimizationPasses</a></td><td class="description">Sets the BeforeOptimization passes.</td></tr>
<tr><td class="name"><a href="package-functions.md#setBeforeRemovingPasses">setBeforeRemovingPasses</a></td><td class="description">Sets the BeforeRemoving passes.</td></tr>
<tr><td class="name"><a href="package-functions.md#setMergePass">setMergePass</a></td><td class="description">Sets the Merge Pass.</td></tr>
<tr><td class="name"><a href="package-functions.md#setOptimizationPasses">setOptimizationPasses</a></td><td class="description">Sets the Optimization passes.</td></tr>
<tr><td class="name"><a href="package-functions.md#setRemovingPasses">setRemovingPasses</a></td><td class="description">Sets the Removing passes.</td></tr>
</table>

<table class="title">
<tr><th colspan="2" class="title">Global Summary</th></tr>
<tr><td class="name"><a href="package-globals.md#TYPE_AFTER_REMOVING">TYPE_AFTER_REMOVING</a></td><td class="description"></td></tr>
</table>

- - -

