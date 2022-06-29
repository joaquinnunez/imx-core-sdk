[@imtbl/core-sdk](../README.md) / [Exports](../modules.md) / [factories](../modules/factories.md) / [contracts](../modules/factories.contracts.md) / Registration\_\_factory

# Class: Registration\_\_factory

[factories](../modules/factories.md).[contracts](../modules/factories.contracts.md).Registration__factory

## Hierarchy

- `ContractFactory`

  ↳ **`Registration__factory`**

## Table of contents

### Constructors

- [constructor](factories.contracts.Registration__factory.md#constructor)

### Properties

- [bytecode](factories.contracts.Registration__factory.md#bytecode)
- [interface](factories.contracts.Registration__factory.md#interface)
- [signer](factories.contracts.Registration__factory.md#signer)
- [abi](factories.contracts.Registration__factory.md#abi)
- [bytecode](factories.contracts.Registration__factory.md#bytecode-1)

### Methods

- [attach](factories.contracts.Registration__factory.md#attach)
- [connect](factories.contracts.Registration__factory.md#connect)
- [deploy](factories.contracts.Registration__factory.md#deploy)
- [getDeployTransaction](factories.contracts.Registration__factory.md#getdeploytransaction)
- [connect](factories.contracts.Registration__factory.md#connect-1)
- [createInterface](factories.contracts.Registration__factory.md#createinterface)
- [fromSolidity](factories.contracts.Registration__factory.md#fromsolidity)
- [getContract](factories.contracts.Registration__factory.md#getcontract)
- [getContractAddress](factories.contracts.Registration__factory.md#getcontractaddress)
- [getInterface](factories.contracts.Registration__factory.md#getinterface)

## Constructors

### constructor

• **new Registration__factory**(...`args`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `RegistrationConstructorParams` |

#### Overrides

ContractFactory.constructor

## Properties

### bytecode

• `Readonly` **bytecode**: `string`

#### Inherited from

ContractFactory.bytecode

#### Defined in

node_modules/@ethersproject/contracts/lib/index.d.ts:139

___

### interface

• `Readonly` **interface**: `Interface`

#### Inherited from

ContractFactory.interface

#### Defined in

node_modules/@ethersproject/contracts/lib/index.d.ts:138

___

### signer

• `Readonly` **signer**: `Signer`

#### Inherited from

ContractFactory.signer

#### Defined in

node_modules/@ethersproject/contracts/lib/index.d.ts:140

___

### abi

▪ `Static` `Readonly` **abi**: ({ `inputs`: { `internalType`: `string` = "contract Core"; `name`: `string` = "\_imx"; `type`: `string` = "address" }[] ; `name`: `undefined` = "isRegistered"; `outputs`: `undefined` ; `stateMutability`: `string` = "nonpayable"; `type`: `string` = "constructor" } \| { `inputs`: { `internalType`: `string` = "uint256"; `name`: `string` = "starkKey"; `type`: `string` = "uint256" }[] ; `name`: `string` = "isRegistered"; `outputs`: { `internalType`: `string` = "bool"; `name`: `string` = ""; `type`: `string` = "bool" }[] ; `stateMutability`: `string` = "view"; `type`: `string` = "function" })[] = `_abi`

#### Defined in

[src/contracts/factories/contracts/Registration__factory.ts:300](https://github.com/immutable/imx-core-sdk/blob/7204457/src/contracts/factories/contracts/Registration__factory.ts#L300)

___

### bytecode

▪ `Static` `Readonly` **bytecode**: ``"0x60806040523480156200001157600080fd5b5060405162001313380380620013138339818101604052810190620000379190620000fc565b806000806101000a81548173ffffffffffffffffffffffffffffffffffffffff021916908373ffffffffffffffffffffffffffffffffffffffff160217905550506200012e565b600080fd5b600073ffffffffffffffffffffffffffffffffffffffff82169050919050565b6000620000b08262000083565b9050919050565b6000620000c482620000a3565b9050919050565b620000d681620000b7565b8114620000e257600080fd5b50565b600081519050620000f681620000cb565b92915050565b6000602082840312156200011557620001146200007e565b5b60006200012584828501620000e5565b91505092915050565b6111d5806200013e6000396000f3fe608060405234801561001057600080fd5b50600436106100885760003560e01c80634280d50a1161005b5780634280d50a146100ff5780634627d5981461011b578063579a698814610137578063ea864adf1461016757610088565b80630a9c3beb1461008d5780630f08025f146100a95780631259cc6c146100c7578063352eb84c146100e3575b600080fd5b6100a760048036038101906100a29190610a72565b610183565b005b6100b16102ae565b6040516100be9190610b8d565b60405180910390f35b6100e160048036038101906100dc9190610ba8565b6102d2565b005b6100fd60048036038101906100f89190610c57565b6103fd565b005b61011960048036038101906101149190610cf1565b610525565b005b61013560048036038101906101309190610da0565b610650565b005b610151600480360381019061014c9190610e3a565b610778565b60405161015e9190610e82565b60405180910390f35b610181600480360381019061017c9190610e9d565b61084a565b005b60008054906101000a900473ffffffffffffffffffffffffffffffffffffffff1673ffffffffffffffffffffffffffffffffffffffff1663dd2414d4888888886040518563ffffffff1660e01b81526004016101e29493929190610fa1565b600060405180830381600087803b1580156101fc57600080fd5b505af1158015610210573d6000803e3d6000fd5b5050505060008054906101000a900473ffffffffffffffffffffffffffffffffffffffff1673ffffffffffffffffffffffffffffffffffffffff1663d91443b7878585856040518563ffffffff1660e01b81526004016102739493929190610fe1565b600060405180830381600087803b15801561028d57600080fd5b505af11580156102a1573d6000803e3d6000fd5b5050505050505050505050565b60008054906101000a900473ffffffffffffffffffffffffffffffffffffffff1681565b60008054906101000a900473ffffffffffffffffffffffffffffffffffffffff1673ffffffffffffffffffffffffffffffffffffffff1663dd2414d4888888886040518563ffffffff1660e01b81526004016103319493929190610fa1565b600060405180830381600087803b15801561034b57600080fd5b505af115801561035f573d6000803e3d6000fd5b5050505060008054906101000a900473ffffffffffffffffffffffffffffffffffffffff1673ffffffffffffffffffffffffffffffffffffffff1663ebef0fd0878585856040518563ffffffff1660e01b81526004016103c29493929190611021565b600060405180830381600087803b1580156103dc57600080fd5b505af11580156103f0573d6000803e3d6000fd5b5050505050505050505050565b60008054906101000a900473ffffffffffffffffffffffffffffffffffffffff1673ffffffffffffffffffffffffffffffffffffffff1663dd2414d4878787876040518563ffffffff1660e01b815260040161045c9493929190610fa1565b600060405180830381600087803b15801561047657600080fd5b505af115801561048a573d6000803e3d6000fd5b5050505060008054906101000a900473ffffffffffffffffffffffffffffffffffffffff1673ffffffffffffffffffffffffffffffffffffffff1663019b417a8684846040518463ffffffff1660e01b81526004016104eb93929190611066565b600060405180830381600087803b15801561050557600080fd5b505af1158015610519573d6000803e3d6000fd5b50505050505050505050565b60008054906101000a900473ffffffffffffffffffffffffffffffffffffffff1673ffffffffffffffffffffffffffffffffffffffff1663dd2414d4888888886040518563ffffffff1660e01b81526004016105849493929190610fa1565b600060405180830381600087803b15801561059e57600080fd5b505af11580156105b2573d6000803e3d6000fd5b5050505060008054906101000a900473ffffffffffffffffffffffffffffffffffffffff1673ffffffffffffffffffffffffffffffffffffffff1663ae1cdde6878585856040518563ffffffff1660e01b8152600401610615949392919061109d565b600060405180830381600087803b15801561062f57600080fd5b505af1158015610643573d6000803e3d6000fd5b5050505050505050505050565b60008054906101000a900473ffffffffffffffffffffffffffffffffffffffff1673ffffffffffffffffffffffffffffffffffffffff1663dd2414d4878787876040518563ffffffff1660e01b81526004016106af9493929190610fa1565b600060405180830381600087803b1580156106c957600080fd5b505af11580156106dd573d6000803e3d6000fd5b5050505060008054906101000a900473ffffffffffffffffffffffffffffffffffffffff1673ffffffffffffffffffffffffffffffffffffffff166314cd70e48684846040518463ffffffff1660e01b815260040161073e939291906110e2565b600060405180830381600087803b15801561075857600080fd5b505af115801561076c573d6000803e3d6000fd5b50505050505050505050565b60008073ffffffffffffffffffffffffffffffffffffffff1660008054906101000a900473ffffffffffffffffffffffffffffffffffffffff1673ffffffffffffffffffffffffffffffffffffffff16631dbd1da7846040518263ffffffff1660e01b81526004016107ea9190611119565b602060405180830381865afa158015610807573d6000803e3d6000fd5b505050506040513d601f19601f8201168201806040525081019061082b9190611149565b73ffffffffffffffffffffffffffffffffffffffff1614159050919050565b60008054906101000a900473ffffffffffffffffffffffffffffffffffffffff1673ffffffffffffffffffffffffffffffffffffffff1663dd2414d4868686866040518563ffffffff1660e01b81526004016108a99493929190610fa1565b600060405180830381600087803b1580156108c357600080fd5b505af11580156108d7573d6000803e3d6000fd5b5050505060008054906101000a900473ffffffffffffffffffffffffffffffffffffffff1673ffffffffffffffffffffffffffffffffffffffff1663441a3e7085836040518363ffffffff1660e01b8152600401610936929190611176565b600060405180830381600087803b15801561095057600080fd5b505af1158015610964573d6000803e3d6000fd5b505050505050505050565b600080fd5b600080fd5b600073ffffffffffffffffffffffffffffffffffffffff82169050919050565b60006109a482610979565b9050919050565b6109b481610999565b81146109bf57600080fd5b50565b6000813590506109d1816109ab565b92915050565b6000819050919050565b6109ea816109d7565b81146109f557600080fd5b50565b600081359050610a07816109e1565b92915050565b600080fd5b600080fd5b600080fd5b60008083601f840112610a3257610a31610a0d565b5b8235905067ffffffffffffffff811115610a4f57610a4e610a12565b5b602083019150836001820283011115610a6b57610a6a610a17565b5b9250929050565b600080600080600080600060a0888a031215610a9157610a9061096f565b5b6000610a9f8a828b016109c2565b9750506020610ab08a828b016109f8565b965050604088013567ffffffffffffffff811115610ad157610ad0610974565b5b610add8a828b01610a1c565b95509550506060610af08a828b016109f8565b935050608088013567ffffffffffffffff811115610b1157610b10610974565b5b610b1d8a828b01610a1c565b925092505092959891949750929550565b6000819050919050565b6000610b53610b4e610b4984610979565b610b2e565b610979565b9050919050565b6000610b6582610b38565b9050919050565b6000610b7782610b5a565b9050919050565b610b8781610b6c565b82525050565b6000602082019050610ba26000830184610b7e565b92915050565b600080600080600080600060c0888a031215610bc757610bc661096f565b5b6000610bd58a828b016109c2565b9750506020610be68a828b016109f8565b965050604088013567ffffffffffffffff811115610c0757610c06610974565b5b610c138a828b01610a1c565b95509550506060610c268a828b016109f8565b9350506080610c378a828b016109f8565b92505060a0610c488a828b016109c2565b91505092959891949750929550565b60008060008060008060a08789031215610c7457610c7361096f565b5b6000610c8289828a016109c2565b9650506020610c9389828a016109f8565b955050604087013567ffffffffffffffff811115610cb457610cb3610974565b5b610cc089828a01610a1c565b94509450506060610cd389828a016109f8565b9250506080610ce489828a016109f8565b9150509295509295509295565b600080600080600080600060c0888a031215610d1057610d0f61096f565b5b6000610d1e8a828b016109c2565b9750506020610d2f8a828b016109f8565b965050604088013567ffffffffffffffff811115610d5057610d4f610974565b5b610d5c8a828b01610a1c565b95509550506060610d6f8a828b016109f8565b9350506080610d808a828b016109f8565b92505060a0610d918a828b016109f8565b91505092959891949750929550565b60008060008060008060a08789031215610dbd57610dbc61096f565b5b6000610dcb89828a016109c2565b9650506020610ddc89828a016109f8565b955050604087013567ffffffffffffffff811115610dfd57610dfc610974565b5b610e0989828a01610a1c565b94509450506060610e1c89828a016109f8565b9250506080610e2d89828a016109c2565b9150509295509295509295565b600060208284031215610e5057610e4f61096f565b5b6000610e5e848285016109f8565b91505092915050565b60008115159050919050565b610e7c81610e67565b82525050565b6000602082019050610e976000830184610e73565b92915050565b600080600080600060808688031215610eb957610eb861096f565b5b6000610ec7888289016109c2565b9550506020610ed8888289016109f8565b945050604086013567ffffffffffffffff811115610ef957610ef8610974565b5b610f0588828901610a1c565b93509350506060610f18888289016109f8565b9150509295509295909350565b610f2e81610999565b82525050565b610f3d816109d7565b82525050565b600082825260208201905092915050565b82818337600083830152505050565b6000601f19601f8301169050919050565b6000610f808385610f43565b9350610f8d838584610f54565b610f9683610f63565b840190509392505050565b6000606082019050610fb66000830187610f25565b610fc36020830186610f34565b8181036040830152610fd6818486610f74565b905095945050505050565b6000606082019050610ff66000830187610f34565b6110036020830186610f34565b8181036040830152611016818486610f74565b905095945050505050565b60006080820190506110366000830187610f34565b6110436020830186610f34565b6110506040830185610f34565b61105d6060830184610f25565b95945050505050565b600060608201905061107b6000830186610f34565b6110886020830185610f34565b6110956040830184610f34565b949350505050565b60006080820190506110b26000830187610f34565b6110bf6020830186610f34565b6110cc6040830185610f34565b6110d96060830184610f34565b95945050505050565b60006060820190506110f76000830186610f34565b6111046020830185610f34565b6111116040830184610f25565b949350505050565b600060208201905061112e6000830184610f34565b92915050565b600081519050611143816109ab565b92915050565b60006020828403121561115f5761115e61096f565b5b600061116d84828501611134565b91505092915050565b600060408201905061118b6000830185610f34565b6111986020830184610f34565b939250505056fea264697066735822122032218b31f9c0e88bb1991ae2275255c3d0cb01b4bf63a689bcaeccdcc791192c64736f6c634300080b0033"``

#### Defined in

[src/contracts/factories/contracts/Registration__factory.ts:299](https://github.com/immutable/imx-core-sdk/blob/7204457/src/contracts/factories/contracts/Registration__factory.ts#L299)

## Methods

### attach

▸ **attach**(`address`): [`Registration`](../interfaces/contracts.Registration.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |

#### Returns

[`Registration`](../interfaces/contracts.Registration.md)

#### Overrides

ContractFactory.attach

___

### connect

▸ **connect**(`signer`): [`Registration__factory`](factories.contracts.Registration__factory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `signer` | `Signer` |

#### Returns

[`Registration__factory`](factories.contracts.Registration__factory.md)

#### Overrides

ContractFactory.connect

___

### deploy

▸ **deploy**(`_imx`, `overrides?`): `Promise`<[`Registration`](../interfaces/contracts.Registration.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `_imx` | `string` |
| `overrides?` | `Overrides` & { `from?`: `string` \| `Promise`<`string`\>  } |

#### Returns

`Promise`<[`Registration`](../interfaces/contracts.Registration.md)\>

#### Overrides

ContractFactory.deploy

___

### getDeployTransaction

▸ **getDeployTransaction**(`_imx`, `overrides?`): `TransactionRequest`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_imx` | `string` |
| `overrides?` | `Overrides` & { `from?`: `string` \| `Promise`<`string`\>  } |

#### Returns

`TransactionRequest`

#### Overrides

ContractFactory.getDeployTransaction

___

### connect

▸ `Static` **connect**(`address`, `signerOrProvider`): [`Registration`](../interfaces/contracts.Registration.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `signerOrProvider` | `Signer` \| `Provider` |

#### Returns

[`Registration`](../interfaces/contracts.Registration.md)

___

### createInterface

▸ `Static` **createInterface**(): `RegistrationInterface`

#### Returns

`RegistrationInterface`

___

### fromSolidity

▸ `Static` **fromSolidity**(`compilerOutput`, `signer?`): `ContractFactory`

#### Parameters

| Name | Type |
| :------ | :------ |
| `compilerOutput` | `any` |
| `signer?` | `Signer` |

#### Returns

`ContractFactory`

#### Inherited from

ContractFactory.fromSolidity

___

### getContract

▸ `Static` **getContract**(`address`, `contractInterface`, `signer?`): `Contract`

#### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `contractInterface` | `ContractInterface` |
| `signer?` | `Signer` |

#### Returns

`Contract`

#### Inherited from

ContractFactory.getContract

___

### getContractAddress

▸ `Static` **getContractAddress**(`tx`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tx` | `Object` |
| `tx.from` | `string` |
| `tx.nonce` | `number` \| `BytesLike` \| `BigNumber` |

#### Returns

`string`

#### Inherited from

ContractFactory.getContractAddress

___

### getInterface

▸ `Static` **getInterface**(`contractInterface`): `Interface`

#### Parameters

| Name | Type |
| :------ | :------ |
| `contractInterface` | `ContractInterface` |

#### Returns

`Interface`

#### Inherited from

ContractFactory.getInterface