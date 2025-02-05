# API Reference

**Classes**

Name|Description
----|-----------
[dataNullDataSource.DataNullDataSource](#cdktf-provider-null-datanulldatasource-datanulldatasource)|Represents a {@link https://www.terraform.io/docs/providers/null/d/data_source null_data_source}.
[provider.NullProvider](#cdktf-provider-null-provider-nullprovider)|Represents a {@link https://www.terraform.io/docs/providers/null null}.
[resource.Resource](#cdktf-provider-null-resource-resource)|Represents a {@link https://www.terraform.io/docs/providers/null/r/resource null_resource}.


**Structs**

Name|Description
----|-----------
[dataNullDataSource.DataNullDataSourceConfig](#cdktf-provider-null-datanulldatasource-datanulldatasourceconfig)|*No description*
[provider.NullProviderConfig](#cdktf-provider-null-provider-nullproviderconfig)|*No description*
[resource.ResourceConfig](#cdktf-provider-null-resource-resourceconfig)|*No description*



## class DataNullDataSource  <a id="cdktf-provider-null-datanulldatasource-datanulldatasource"></a>

Represents a {@link https://www.terraform.io/docs/providers/null/d/data_source null_data_source}.

__Implements__: [IConstruct](#constructs-iconstruct), [IDependable](#constructs-idependable), [ITerraformResource](#cdktf-iterraformresource), [ITerraformDependable](#cdktf-iterraformdependable), [ITerraformAddressable](#cdktf-iterraformaddressable), [IInterpolatingParent](#cdktf-iinterpolatingparent)
__Submodule__: dataNullDataSource

__Extends__: [TerraformDataSource](#cdktf-terraformdatasource)

### Initializer


Create a new {@link https://www.terraform.io/docs/providers/null/d/data_source null_data_source} Data Source.

```ts
new dataNullDataSource.DataNullDataSource(scope: Construct, id: string, config?: DataNullDataSourceConfig)
```

* **scope** (<code>[Construct](#constructs-construct)</code>)  The scope in which to define this construct.
* **id** (<code>string</code>)  The scoped construct ID.
* **config** (<code>[dataNullDataSource.DataNullDataSourceConfig](#cdktf-provider-null-datanulldatasource-datanulldatasourceconfig)</code>)  *No description*
  * **connection** (<code>[SSHProvisionerConnection](#cdktf-sshprovisionerconnection) &#124; [WinrmProvisionerConnection](#cdktf-winrmprovisionerconnection)</code>)  *No description* __*Optional*__
  * **count** (<code>number</code>)  *No description* __*Optional*__
  * **dependsOn** (<code>Array<[ITerraformDependable](#cdktf-iterraformdependable)></code>)  *No description* __*Optional*__
  * **forEach** (<code>[ITerraformIterator](#cdktf-iterraformiterator)</code>)  *No description* __*Optional*__
  * **lifecycle** (<code>[TerraformResourceLifecycle](#cdktf-terraformresourcelifecycle)</code>)  *No description* __*Optional*__
  * **provider** (<code>[TerraformProvider](#cdktf-terraformprovider)</code>)  *No description* __*Optional*__
  * **provisioners** (<code>Array<[FileProvisioner](#cdktf-fileprovisioner) &#124; [LocalExecProvisioner](#cdktf-localexecprovisioner) &#124; [RemoteExecProvisioner](#cdktf-remoteexecprovisioner)></code>)  *No description* __*Optional*__
  * **hasComputedDefault** (<code>string</code>)  If set, its literal value will be stored and returned. __*Optional*__
  * **inputs** (<code>Map<string, string></code>)  A map of arbitrary strings that is copied into the `outputs` attribute, and accessible directly for interpolation. __*Optional*__



### Properties


Name | Type | Description 
-----|------|-------------
**hasComputedDefault** | <code>string</code> | <span></span>
**id** | <code>string</code> | <span></span>
**inputs** | <code>Map<string, string></code> | <span></span>
**outputs** | <code>[StringMap](#cdktf-stringmap)</code> | <span></span>
**random** | <code>string</code> | <span></span>
**hasComputedDefaultInput**? | <code>string</code> | __*Optional*__
**inputsInput**? | <code>Map<string, string></code> | __*Optional*__
*static* **tfResourceType** | <code>string</code> | <span></span>

### Methods


#### resetHasComputedDefault() <a id="cdktf-provider-null-datanulldatasource-datanulldatasource-resethascomputeddefault"></a>



```ts
resetHasComputedDefault(): void
```





#### resetInputs() <a id="cdktf-provider-null-datanulldatasource-datanulldatasource-resetinputs"></a>



```ts
resetInputs(): void
```





#### protected synthesizeAttributes() <a id="cdktf-provider-null-datanulldatasource-datanulldatasource-synthesizeattributes"></a>



```ts
protected synthesizeAttributes(): Map<string, any>
```


__Returns__:
* <code>Map<string, any></code>



## class NullProvider  <a id="cdktf-provider-null-provider-nullprovider"></a>

Represents a {@link https://www.terraform.io/docs/providers/null null}.

__Implements__: [IConstruct](#constructs-iconstruct), [IDependable](#constructs-idependable)
__Submodule__: provider

__Extends__: [TerraformProvider](#cdktf-terraformprovider)

### Initializer


Create a new {@link https://www.terraform.io/docs/providers/null null} Resource.

```ts
new provider.NullProvider(scope: Construct, id: string, config?: NullProviderConfig)
```

* **scope** (<code>[Construct](#constructs-construct)</code>)  The scope in which to define this construct.
* **id** (<code>string</code>)  The scoped construct ID.
* **config** (<code>[provider.NullProviderConfig](#cdktf-provider-null-provider-nullproviderconfig)</code>)  *No description*
  * **alias** (<code>string</code>)  Alias name. __*Optional*__



### Properties


Name | Type | Description 
-----|------|-------------
**alias**? | <code>string</code> | __*Optional*__
**aliasInput**? | <code>string</code> | __*Optional*__
*static* **tfResourceType** | <code>string</code> | <span></span>

### Methods


#### resetAlias() <a id="cdktf-provider-null-provider-nullprovider-resetalias"></a>



```ts
resetAlias(): void
```





#### protected synthesizeAttributes() <a id="cdktf-provider-null-provider-nullprovider-synthesizeattributes"></a>



```ts
protected synthesizeAttributes(): Map<string, any>
```


__Returns__:
* <code>Map<string, any></code>



## class Resource  <a id="cdktf-provider-null-resource-resource"></a>

Represents a {@link https://www.terraform.io/docs/providers/null/r/resource null_resource}.

__Implements__: [IConstruct](#constructs-iconstruct), [IDependable](#constructs-idependable), [ITerraformResource](#cdktf-iterraformresource), [ITerraformDependable](#cdktf-iterraformdependable), [ITerraformAddressable](#cdktf-iterraformaddressable), [IInterpolatingParent](#cdktf-iinterpolatingparent)
__Submodule__: resource

__Extends__: [TerraformResource](#cdktf-terraformresource)

### Initializer


Create a new {@link https://www.terraform.io/docs/providers/null/r/resource null_resource} Resource.

```ts
new resource.Resource(scope: Construct, id: string, config?: ResourceConfig)
```

* **scope** (<code>[Construct](#constructs-construct)</code>)  The scope in which to define this construct.
* **id** (<code>string</code>)  The scoped construct ID.
* **config** (<code>[resource.ResourceConfig](#cdktf-provider-null-resource-resourceconfig)</code>)  *No description*
  * **connection** (<code>[SSHProvisionerConnection](#cdktf-sshprovisionerconnection) &#124; [WinrmProvisionerConnection](#cdktf-winrmprovisionerconnection)</code>)  *No description* __*Optional*__
  * **count** (<code>number</code>)  *No description* __*Optional*__
  * **dependsOn** (<code>Array<[ITerraformDependable](#cdktf-iterraformdependable)></code>)  *No description* __*Optional*__
  * **forEach** (<code>[ITerraformIterator](#cdktf-iterraformiterator)</code>)  *No description* __*Optional*__
  * **lifecycle** (<code>[TerraformResourceLifecycle](#cdktf-terraformresourcelifecycle)</code>)  *No description* __*Optional*__
  * **provider** (<code>[TerraformProvider](#cdktf-terraformprovider)</code>)  *No description* __*Optional*__
  * **provisioners** (<code>Array<[FileProvisioner](#cdktf-fileprovisioner) &#124; [LocalExecProvisioner](#cdktf-localexecprovisioner) &#124; [RemoteExecProvisioner](#cdktf-remoteexecprovisioner)></code>)  *No description* __*Optional*__
  * **triggers** (<code>Map<string, string></code>)  A map of arbitrary strings that, when changed, will force the null resource to be replaced, re-running any associated provisioners. __*Optional*__



### Properties


Name | Type | Description 
-----|------|-------------
**id** | <code>string</code> | <span></span>
**triggers** | <code>Map<string, string></code> | <span></span>
**triggersInput**? | <code>Map<string, string></code> | __*Optional*__
*static* **tfResourceType** | <code>string</code> | <span></span>

### Methods


#### resetTriggers() <a id="cdktf-provider-null-resource-resource-resettriggers"></a>



```ts
resetTriggers(): void
```





#### protected synthesizeAttributes() <a id="cdktf-provider-null-resource-resource-synthesizeattributes"></a>



```ts
protected synthesizeAttributes(): Map<string, any>
```


__Returns__:
* <code>Map<string, any></code>



## struct DataNullDataSourceConfig  <a id="cdktf-provider-null-datanulldatasource-datanulldatasourceconfig"></a>






Name | Type | Description 
-----|------|-------------
**connection**?🔹 | <code>[SSHProvisionerConnection](#cdktf-sshprovisionerconnection) &#124; [WinrmProvisionerConnection](#cdktf-winrmprovisionerconnection)</code> | __*Optional*__
**count**?🔹 | <code>number</code> | __*Optional*__
**dependsOn**?🔹 | <code>Array<[ITerraformDependable](#cdktf-iterraformdependable)></code> | __*Optional*__
**forEach**?🔹 | <code>[ITerraformIterator](#cdktf-iterraformiterator)</code> | __*Optional*__
**hasComputedDefault**? | <code>string</code> | If set, its literal value will be stored and returned.<br/>__*Optional*__
**inputs**? | <code>Map<string, string></code> | A map of arbitrary strings that is copied into the `outputs` attribute, and accessible directly for interpolation.<br/>__*Optional*__
**lifecycle**?🔹 | <code>[TerraformResourceLifecycle](#cdktf-terraformresourcelifecycle)</code> | __*Optional*__
**provider**?🔹 | <code>[TerraformProvider](#cdktf-terraformprovider)</code> | __*Optional*__
**provisioners**?🔹 | <code>Array<[FileProvisioner](#cdktf-fileprovisioner) &#124; [LocalExecProvisioner](#cdktf-localexecprovisioner) &#124; [RemoteExecProvisioner](#cdktf-remoteexecprovisioner)></code> | __*Optional*__



## struct NullProviderConfig  <a id="cdktf-provider-null-provider-nullproviderconfig"></a>






Name | Type | Description 
-----|------|-------------
**alias**? | <code>string</code> | Alias name.<br/>__*Optional*__



## struct ResourceConfig  <a id="cdktf-provider-null-resource-resourceconfig"></a>






Name | Type | Description 
-----|------|-------------
**connection**?🔹 | <code>[SSHProvisionerConnection](#cdktf-sshprovisionerconnection) &#124; [WinrmProvisionerConnection](#cdktf-winrmprovisionerconnection)</code> | __*Optional*__
**count**?🔹 | <code>number</code> | __*Optional*__
**dependsOn**?🔹 | <code>Array<[ITerraformDependable](#cdktf-iterraformdependable)></code> | __*Optional*__
**forEach**?🔹 | <code>[ITerraformIterator](#cdktf-iterraformiterator)</code> | __*Optional*__
**lifecycle**?🔹 | <code>[TerraformResourceLifecycle](#cdktf-terraformresourcelifecycle)</code> | __*Optional*__
**provider**?🔹 | <code>[TerraformProvider](#cdktf-terraformprovider)</code> | __*Optional*__
**provisioners**?🔹 | <code>Array<[FileProvisioner](#cdktf-fileprovisioner) &#124; [LocalExecProvisioner](#cdktf-localexecprovisioner) &#124; [RemoteExecProvisioner](#cdktf-remoteexecprovisioner)></code> | __*Optional*__
**triggers**? | <code>Map<string, string></code> | A map of arbitrary strings that, when changed, will force the null resource to be replaced, re-running any associated provisioners.<br/>__*Optional*__



