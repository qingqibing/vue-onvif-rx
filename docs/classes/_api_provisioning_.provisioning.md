[onvif-rx](../README.md) > ["api/provisioning"](../modules/_api_provisioning_.md) > [Provisioning](../classes/_api_provisioning_.provisioning.md)

# Class: Provisioning

## Hierarchy

**Provisioning**

## Index

### Constructors

* [constructor](_api_provisioning_.provisioning.md#constructor)

### Properties

* [config](_api_provisioning_.provisioning.md#config)

### Methods

* [FocusMove](_api_provisioning_.provisioning.md#focusmove)
* [GetServiceCapabilities](_api_provisioning_.provisioning.md#getservicecapabilities)
* [GetUsage](_api_provisioning_.provisioning.md#getusage)
* [PanMove](_api_provisioning_.provisioning.md#panmove)
* [RollMove](_api_provisioning_.provisioning.md#rollmove)
* [Stop](_api_provisioning_.provisioning.md#stop)
* [TiltMove](_api_provisioning_.provisioning.md#tiltmove)
* [ZoomMove](_api_provisioning_.provisioning.md#zoommove)
* [FocusMove](_api_provisioning_.provisioning.md#focusmove-1)
* [GetServiceCapabilities](_api_provisioning_.provisioning.md#getservicecapabilities-1)
* [GetUsage](_api_provisioning_.provisioning.md#getusage-1)
* [PanMove](_api_provisioning_.provisioning.md#panmove-1)
* [RollMove](_api_provisioning_.provisioning.md#rollmove-1)
* [Stop](_api_provisioning_.provisioning.md#stop-1)
* [TiltMove](_api_provisioning_.provisioning.md#tiltmove-1)
* [ZoomMove](_api_provisioning_.provisioning.md#zoommove-1)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new Provisioning**(config: *[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md)*): [Provisioning](_api_provisioning_.provisioning.md)

*Defined in [api/provisioning.ts:5](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L5)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| config | [IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md) |

**Returns:** [Provisioning](_api_provisioning_.provisioning.md)

___

## Properties

<a id="config"></a>

### `<Private>` config

**● config**: *[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md)*

*Defined in [api/provisioning.ts:6](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L6)*

___

## Methods

<a id="focusmove"></a>

###  FocusMove

▸ **FocusMove**(): `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

*Defined in [api/provisioning.ts:119](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L119)*

Moves device on the focus axis.

**Returns:** `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

___
<a id="getservicecapabilities"></a>

###  GetServiceCapabilities

▸ **GetServiceCapabilities**(): `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

*Defined in [api/provisioning.ts:84](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L84)*

Returns the capabilities of the provisioning service.

**Returns:** `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

___
<a id="getusage"></a>

###  GetUsage

▸ **GetUsage**(): `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

*Defined in [api/provisioning.ts:133](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L133)*

Returns the lifetime move counts.

**Returns:** `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

___
<a id="panmove"></a>

###  PanMove

▸ **PanMove**(): `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

*Defined in [api/provisioning.ts:91](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L91)*

Moves device on the pan axis.

**Returns:** `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

___
<a id="rollmove"></a>

###  RollMove

▸ **RollMove**(): `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

*Defined in [api/provisioning.ts:112](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L112)*

Moves device on the roll axis.

**Returns:** `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

___
<a id="stop"></a>

###  Stop

▸ **Stop**(): `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

*Defined in [api/provisioning.ts:126](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L126)*

Stops device motion on all axes.

**Returns:** `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

___
<a id="tiltmove"></a>

###  TiltMove

▸ **TiltMove**(): `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

*Defined in [api/provisioning.ts:98](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L98)*

Moves device on the tilt axis.

**Returns:** `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

___
<a id="zoommove"></a>

###  ZoomMove

▸ **ZoomMove**(): `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

*Defined in [api/provisioning.ts:105](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L105)*

Moves device on the zoom axis.

**Returns:** `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>

___
<a id="focusmove-1"></a>

### `<Static>` FocusMove

▸ **FocusMove**(): `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

*Defined in [api/provisioning.ts:57](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L57)*

Moves device on the focus axis.

**Returns:** `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

___
<a id="getservicecapabilities-1"></a>

### `<Static>` GetServiceCapabilities

▸ **GetServiceCapabilities**(): `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

*Defined in [api/provisioning.ts:12](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L12)*

Returns the capabilities of the provisioning service.

**Returns:** `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

___
<a id="getusage-1"></a>

### `<Static>` GetUsage

▸ **GetUsage**(): `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

*Defined in [api/provisioning.ts:75](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L75)*

Returns the lifetime move counts.

**Returns:** `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

___
<a id="panmove-1"></a>

### `<Static>` PanMove

▸ **PanMove**(): `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

*Defined in [api/provisioning.ts:21](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L21)*

Moves device on the pan axis.

**Returns:** `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

___
<a id="rollmove-1"></a>

### `<Static>` RollMove

▸ **RollMove**(): `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

*Defined in [api/provisioning.ts:48](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L48)*

Moves device on the roll axis.

**Returns:** `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

___
<a id="stop-1"></a>

### `<Static>` Stop

▸ **Stop**(): `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

*Defined in [api/provisioning.ts:66](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L66)*

Stops device motion on all axes.

**Returns:** `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

___
<a id="tiltmove-1"></a>

### `<Static>` TiltMove

▸ **TiltMove**(): `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

*Defined in [api/provisioning.ts:30](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L30)*

Moves device on the tilt axis.

**Returns:** `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

___
<a id="zoommove-1"></a>

### `<Static>` ZoomMove

▸ **ZoomMove**(): `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

*Defined in [api/provisioning.ts:39](https://github.com/patrickmichalina/onvif-rx/blob/1596479/src/api/provisioning.ts#L39)*

Moves device on the zoom axis.

**Returns:** `IReader`<[IDeviceConfig](../interfaces/_config_interfaces_.ideviceconfig.md), `Observable`<`IResult`<`any`, [ITransportPayloadXml](../interfaces/_soap_request_.itransportpayloadxml.md)>>>

___
