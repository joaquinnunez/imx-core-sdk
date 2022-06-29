[@imtbl/core-sdk](../README.md) / [Exports](../modules.md) / ConfigurationParameters

# Interface: ConfigurationParameters

Immutable X API
No description provided (generated by Openapi Generator https://github.com/openapitools/openapi-generator)

The version of the OpenAPI document: 0.1
Contact: support@immutable.com

NOTE: This class is auto generated by OpenAPI Generator (https://openapi-generator.tech).
https://openapi-generator.tech
Do not edit the class manually.

## Table of contents

### Properties

- [accessToken](ConfigurationParameters.md#accesstoken)
- [apiKey](ConfigurationParameters.md#apikey)
- [baseOptions](ConfigurationParameters.md#baseoptions)
- [basePath](ConfigurationParameters.md#basepath)
- [formDataCtor](ConfigurationParameters.md#formdatactor)
- [password](ConfigurationParameters.md#password)
- [username](ConfigurationParameters.md#username)

## Properties

### accessToken

• `Optional` **accessToken**: `string` \| `Promise`<`string`\> \| (`name?`: `string`, `scopes?`: `string`[]) => `string` \| (`name?`: `string`, `scopes?`: `string`[]) => `Promise`<`string`\>

#### Defined in

[src/api/configuration.ts:20](https://github.com/immutable/imx-core-sdk/blob/7204457/src/api/configuration.ts#L20)

___

### apiKey

• `Optional` **apiKey**: `string` \| `Promise`<`string`\> \| (`name`: `string`) => `string` \| (`name`: `string`) => `Promise`<`string`\>

#### Defined in

[src/api/configuration.ts:17](https://github.com/immutable/imx-core-sdk/blob/7204457/src/api/configuration.ts#L17)

___

### baseOptions

• `Optional` **baseOptions**: `any`

#### Defined in

[src/api/configuration.ts:22](https://github.com/immutable/imx-core-sdk/blob/7204457/src/api/configuration.ts#L22)

___

### basePath

• `Optional` **basePath**: `string`

#### Defined in

[src/api/configuration.ts:21](https://github.com/immutable/imx-core-sdk/blob/7204457/src/api/configuration.ts#L21)

___

### formDataCtor

• `Optional` **formDataCtor**: () => `any`

#### Type declaration

• **new ConfigurationParameters**()

#### Defined in

[src/api/configuration.ts:23](https://github.com/immutable/imx-core-sdk/blob/7204457/src/api/configuration.ts#L23)

___

### password

• `Optional` **password**: `string`

#### Defined in

[src/api/configuration.ts:19](https://github.com/immutable/imx-core-sdk/blob/7204457/src/api/configuration.ts#L19)

___

### username

• `Optional` **username**: `string`

#### Defined in

[src/api/configuration.ts:18](https://github.com/immutable/imx-core-sdk/blob/7204457/src/api/configuration.ts#L18)