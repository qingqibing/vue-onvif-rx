[onvif-rx](../README.md) > ["api/types"](../modules/_api_types_.md) > [ActionEngineEventPayload](../interfaces/_api_types_.actionengineeventpayload.md)

# Interface: ActionEngineEventPayload

Action Engine Event Payload data structure contains the information about the ONVIF command invocations. Since this event could be generated by other or proprietary actions, the command invocation specific fields are defined as optional and additional extension mechanism is provided for future or additional action definitions.

## Hierarchy

**ActionEngineEventPayload**

## Index

### Properties

* [Extension](_api_types_.actionengineeventpayload.md#extension)
* [Fault](_api_types_.actionengineeventpayload.md#fault)
* [RequestInfo](_api_types_.actionengineeventpayload.md#requestinfo)
* [ResponseInfo](_api_types_.actionengineeventpayload.md#responseinfo)

---

## Properties

<a id="extension"></a>

### `<Optional>` Extension

**● Extension**: *[ActionEngineEventPayloadExtension](_api_types_.actionengineeventpayloadextension.md)*

*Defined in [api/types.ts:4066](https://github.com/patrickmichalina/onvif-rx/blob/f117e44/src/api/types.ts#L4066)*

___
<a id="fault"></a>

### `<Optional>` Fault

**● Fault**: *[Fault](_api_types_.actionengineeventpayload.md#fault)*

*Defined in [api/types.ts:4065](https://github.com/patrickmichalina/onvif-rx/blob/f117e44/src/api/types.ts#L4065)*

___
<a id="requestinfo"></a>

### `<Optional>` RequestInfo

**● RequestInfo**: *[Envelope](_api_types_.envelope.md)*

*Defined in [api/types.ts:4063](https://github.com/patrickmichalina/onvif-rx/blob/f117e44/src/api/types.ts#L4063)*

___
<a id="responseinfo"></a>

### `<Optional>` ResponseInfo

**● ResponseInfo**: *[Envelope](_api_types_.envelope.md)*

*Defined in [api/types.ts:4064](https://github.com/patrickmichalina/onvif-rx/blob/f117e44/src/api/types.ts#L4064)*

___

