# BSCLightClient





## Contents
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Globals](#globals)
- [Modifiers](#modifiers)
  - [onlySetter](#onlysetter)
- [Functions](#functions)
  - [changeSetter](#changesetter)
  - [constructor](#constructor)
  - [registry](#registry)
  - [verify_messages_proof](#verify_messages_proof)
  - [build_outlane](#build_outlane)
  - [build_message_keys](#build_message_keys)
  - [verify_messages_delivery_proof](#verify_messages_delivery_proof)
  - [toUint](#touint)
  - [toBytes32](#tobytes32)
  - [mapLocation](#maplocation)
- [Events](#events)
  - [Registry](#registry)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Globals

> Note this contains internal vars as well due to a bug in the docgen procedure

| Var | Type |
| --- | --- |
| BSC_BRIDGE_PRECOMPILE | address |
| THIS_CHAIN_POSITION | uint256 |
| LANE_IDENTIFY_SLOT | uint256 |
| LANE_NONCE_SLOT | uint256 |
| LANE_MESSAGE_SLOT | uint256 |
| lanes | mapping(uint32 => mapping(uint32 => address)) |
| setter | address |


## Modifiers

### onlySetter
No description


#### Declaration
```solidity
  modifier onlySetter
```



## Functions

### changeSetter
No description


#### Declaration
```solidity
  function changeSetter(
  ) external onlySetter
```

#### Modifiers:
| Modifier |
| --- |
| onlySetter |



### constructor
No description


#### Declaration
```solidity
  function constructor(
  ) public
```

#### Modifiers:
No modifiers



### registry
No description


#### Declaration
```solidity
  function registry(
  ) external onlySetter
```

#### Modifiers:
| Modifier |
| --- |
| onlySetter |



### verify_messages_proof
No description


#### Declaration
```solidity
  function verify_messages_proof(
  ) external returns (bool)
```

#### Modifiers:
No modifiers



### build_outlane
No description


#### Declaration
```solidity
  function build_outlane(
  ) internal returns (struct SourceChain.OutboundLaneData lane_data)
```

#### Modifiers:
No modifiers



### build_message_keys
No description


#### Declaration
```solidity
  function build_message_keys(
  ) internal returns (bytes32[])
```

#### Modifiers:
No modifiers



### verify_messages_delivery_proof
No description


#### Declaration
```solidity
  function verify_messages_delivery_proof(
  ) external returns (bool)
```

#### Modifiers:
No modifiers



### toUint
No description


#### Declaration
```solidity
  function toUint(
  ) internal returns (uint256 data)
```

#### Modifiers:
No modifiers



### toBytes32
No description


#### Declaration
```solidity
  function toBytes32(
  ) internal returns (bytes32 data)
```

#### Modifiers:
No modifiers



### mapLocation
No description


#### Declaration
```solidity
  function mapLocation(
  ) internal returns (uint256)
```

#### Modifiers:
No modifiers





## Events

### Registry
No description

  


