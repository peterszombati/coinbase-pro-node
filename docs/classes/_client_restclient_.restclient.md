[coinbase-pro-node](../README.md) › [Globals](../globals.md) › ["client/RESTClient"](../modules/_client_restclient_.md) › [RESTClient](_client_restclient_.restclient.md)

# Class: RESTClient

## Hierarchy

- EventEmitter

  ↳ **RESTClient**

## Index

### Constructors

- [constructor](_client_restclient_.restclient.md#constructor)

### Properties

- [account](_client_restclient_.restclient.md#account)
- [currency](_client_restclient_.restclient.md#currency)
- [fee](_client_restclient_.restclient.md#fee)
- [fill](_client_restclient_.restclient.md#fill)
- [order](_client_restclient_.restclient.md#order)
- [product](_client_restclient_.restclient.md#product)
- [profile](_client_restclient_.restclient.md#profile)
- [user](_client_restclient_.restclient.md#user)
- [defaultMaxListeners](_client_restclient_.restclient.md#static-defaultmaxlisteners)

### Accessors

- [defaults](_client_restclient_.restclient.md#defaults)
- [interceptors](_client_restclient_.restclient.md#interceptors)

### Methods

- [addListener](_client_restclient_.restclient.md#addlistener)
- [emit](_client_restclient_.restclient.md#emit)
- [eventNames](_client_restclient_.restclient.md#eventnames)
- [getMaxListeners](_client_restclient_.restclient.md#getmaxlisteners)
- [listenerCount](_client_restclient_.restclient.md#listenercount)
- [listeners](_client_restclient_.restclient.md#listeners)
- [off](_client_restclient_.restclient.md#off)
- [on](_client_restclient_.restclient.md#on)
- [once](_client_restclient_.restclient.md#once)
- [prependListener](_client_restclient_.restclient.md#prependlistener)
- [prependOnceListener](_client_restclient_.restclient.md#prependoncelistener)
- [rawListeners](_client_restclient_.restclient.md#rawlisteners)
- [removeAllListeners](_client_restclient_.restclient.md#removealllisteners)
- [removeListener](_client_restclient_.restclient.md#removelistener)
- [setMaxListeners](_client_restclient_.restclient.md#setmaxlisteners)
- [listenerCount](_client_restclient_.restclient.md#static-listenercount)
- [stringifyPayload](_client_restclient_.restclient.md#static-stringifypayload)

## Constructors

### constructor

\+ **new RESTClient**(`baseURL`: string, `signRequest`: function): _[RESTClient](_client_restclient_.restclient.md)_

_Defined in [src/client/RESTClient.ts:46](https://github.com/bennyn/coinbase-pro-node/blob/1a12582/src/client/RESTClient.ts#L46)_

**Parameters:**

▪ **baseURL**: _string_

▪ **signRequest**: _function_

▸ (`setup`: [RequestSetup](../interfaces/_auth_requestsigner_.requestsetup.md)): _Promise‹[SignedRequest](../interfaces/_auth_requestsigner_.signedrequest.md)›_

**Parameters:**

| Name    | Type                                                               |
| ------- | ------------------------------------------------------------------ |
| `setup` | [RequestSetup](../interfaces/_auth_requestsigner_.requestsetup.md) |

**Returns:** _[RESTClient](_client_restclient_.restclient.md)_

## Properties

### account

• **account**: _[AccountAPI](_account_accountapi_.accountapi.md)_

_Defined in [src/client/RESTClient.ts:36](https://github.com/bennyn/coinbase-pro-node/blob/1a12582/src/client/RESTClient.ts#L36)_

---

### currency

• **currency**: _[CurrencyAPI](_currency_currencyapi_.currencyapi.md)_

_Defined in [src/client/RESTClient.ts:43](https://github.com/bennyn/coinbase-pro-node/blob/1a12582/src/client/RESTClient.ts#L43)_

---

### fee

• **fee**: _[FeeAPI](_fee_feeapi_.feeapi.md)_

_Defined in [src/client/RESTClient.ts:37](https://github.com/bennyn/coinbase-pro-node/blob/1a12582/src/client/RESTClient.ts#L37)_

---

### fill

• **fill**: _[FillAPI](_fill_fillapi_.fillapi.md)_

_Defined in [src/client/RESTClient.ts:38](https://github.com/bennyn/coinbase-pro-node/blob/1a12582/src/client/RESTClient.ts#L38)_

---

### order

• **order**: _[OrderAPI](_order_orderapi_.orderapi.md)_

_Defined in [src/client/RESTClient.ts:39](https://github.com/bennyn/coinbase-pro-node/blob/1a12582/src/client/RESTClient.ts#L39)_

---

### product

• **product**: _[ProductAPI](_product_productapi_.productapi.md)_

_Defined in [src/client/RESTClient.ts:40](https://github.com/bennyn/coinbase-pro-node/blob/1a12582/src/client/RESTClient.ts#L40)_

---

### profile

• **profile**: _[ProfileAPI](_profile_profileapi_.profileapi.md)_

_Defined in [src/client/RESTClient.ts:41](https://github.com/bennyn/coinbase-pro-node/blob/1a12582/src/client/RESTClient.ts#L41)_

---

### user

• **user**: _[UserAPI](_user_userapi_.userapi.md)_

_Defined in [src/client/RESTClient.ts:42](https://github.com/bennyn/coinbase-pro-node/blob/1a12582/src/client/RESTClient.ts#L42)_

---

### `Static` defaultMaxListeners

▪ **defaultMaxListeners**: _number_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[defaultMaxListeners](_client_websocketclient_.websocketclient.md#static-defaultmaxlisteners)_

Defined in node_modules/@types/node/events.d.ts:18

## Accessors

### defaults

• **get defaults**(): _AxiosRequestConfig_

_Defined in [src/client/RESTClient.ts:25](https://github.com/bennyn/coinbase-pro-node/blob/1a12582/src/client/RESTClient.ts#L25)_

**Returns:** _AxiosRequestConfig_

---

### interceptors

• **get interceptors**(): _object_

_Defined in [src/client/RESTClient.ts:29](https://github.com/bennyn/coinbase-pro-node/blob/1a12582/src/client/RESTClient.ts#L29)_

**Returns:** _object_

- **request**: _AxiosInterceptorManager‹AxiosRequestConfig›_

- **response**: _AxiosInterceptorManager‹AxiosResponse›_

## Methods

### addListener

▸ **addListener**(`event`: string | symbol, `listener`: function): _this_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[addListener](_client_websocketclient_.websocketclient.md#addlistener)_

_Overrides void_

Defined in node_modules/@types/node/events.d.ts:20

**Parameters:**

▪ **event**: _string | symbol_

▪ **listener**: _function_

▸ (...`args`: any[]): _void_

**Parameters:**

| Name      | Type  |
| --------- | ----- |
| `...args` | any[] |

**Returns:** _this_

---

### emit

▸ **emit**(`event`: string | symbol, ...`args`: any[]): _boolean_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[emit](_client_websocketclient_.websocketclient.md#emit)_

_Overrides void_

Defined in node_modules/@types/node/events.d.ts:32

**Parameters:**

| Name      | Type                 |
| --------- | -------------------- |
| `event`   | string &#124; symbol |
| `...args` | any[]                |

**Returns:** _boolean_

---

### eventNames

▸ **eventNames**(): _Array‹string | symbol›_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[eventNames](_client_websocketclient_.websocketclient.md#eventnames)_

_Overrides void_

Defined in node_modules/@types/node/events.d.ts:33

**Returns:** _Array‹string | symbol›_

---

### getMaxListeners

▸ **getMaxListeners**(): _number_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[getMaxListeners](_client_websocketclient_.websocketclient.md#getmaxlisteners)_

_Overrides void_

Defined in node_modules/@types/node/events.d.ts:29

**Returns:** _number_

---

### listenerCount

▸ **listenerCount**(`type`: string | symbol): _number_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[listenerCount](_client_websocketclient_.websocketclient.md#static-listenercount)_

_Overrides void_

Defined in node_modules/@types/node/events.d.ts:34

**Parameters:**

| Name   | Type                 |
| ------ | -------------------- |
| `type` | string &#124; symbol |

**Returns:** _number_

---

### listeners

▸ **listeners**(`event`: string | symbol): _Function[]_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[listeners](_client_websocketclient_.websocketclient.md#listeners)_

_Overrides void_

Defined in node_modules/@types/node/events.d.ts:30

**Parameters:**

| Name    | Type                 |
| ------- | -------------------- |
| `event` | string &#124; symbol |

**Returns:** _Function[]_

---

### off

▸ **off**(`event`: string | symbol, `listener`: function): _this_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[off](_client_websocketclient_.websocketclient.md#off)_

_Overrides void_

Defined in node_modules/@types/node/events.d.ts:26

**Parameters:**

▪ **event**: _string | symbol_

▪ **listener**: _function_

▸ (...`args`: any[]): _void_

**Parameters:**

| Name      | Type  |
| --------- | ----- |
| `...args` | any[] |

**Returns:** _this_

---

### on

▸ **on**(`event`: [NEW_CANDLE](../enums/_product_productapi_.productevent.md#new_candle), `listener`: function): _this_

_Overrides void_

_Defined in [src/client/RESTClient.ts:18](https://github.com/bennyn/coinbase-pro-node/blob/1a12582/src/client/RESTClient.ts#L18)_

**Parameters:**

▪ **event**: _[NEW_CANDLE](../enums/_product_productapi_.productevent.md#new_candle)_

▪ **listener**: _function_

▸ (`productId`: string, `granularity`: [CandleGranularity](../enums/_product_productapi_.candlegranularity.md), `candle`: [Candle](../interfaces/_product_productapi_.candle.md)): _void_

**Parameters:**

| Name          | Type                                                                    |
| ------------- | ----------------------------------------------------------------------- |
| `productId`   | string                                                                  |
| `granularity` | [CandleGranularity](../enums/_product_productapi_.candlegranularity.md) |
| `candle`      | [Candle](../interfaces/_product_productapi_.candle.md)                  |

**Returns:** _this_

---

### once

▸ **once**(`event`: string | symbol, `listener`: function): _this_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[once](_client_websocketclient_.websocketclient.md#once)_

_Overrides void_

Defined in node_modules/@types/node/events.d.ts:22

**Parameters:**

▪ **event**: _string | symbol_

▪ **listener**: _function_

▸ (...`args`: any[]): _void_

**Parameters:**

| Name      | Type  |
| --------- | ----- |
| `...args` | any[] |

**Returns:** _this_

---

### prependListener

▸ **prependListener**(`event`: string | symbol, `listener`: function): _this_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[prependListener](_client_websocketclient_.websocketclient.md#prependlistener)_

_Overrides void_

Defined in node_modules/@types/node/events.d.ts:23

**Parameters:**

▪ **event**: _string | symbol_

▪ **listener**: _function_

▸ (...`args`: any[]): _void_

**Parameters:**

| Name      | Type  |
| --------- | ----- |
| `...args` | any[] |

**Returns:** _this_

---

### prependOnceListener

▸ **prependOnceListener**(`event`: string | symbol, `listener`: function): _this_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[prependOnceListener](_client_websocketclient_.websocketclient.md#prependoncelistener)_

_Overrides void_

Defined in node_modules/@types/node/events.d.ts:24

**Parameters:**

▪ **event**: _string | symbol_

▪ **listener**: _function_

▸ (...`args`: any[]): _void_

**Parameters:**

| Name      | Type  |
| --------- | ----- |
| `...args` | any[] |

**Returns:** _this_

---

### rawListeners

▸ **rawListeners**(`event`: string | symbol): _Function[]_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[rawListeners](_client_websocketclient_.websocketclient.md#rawlisteners)_

_Overrides void_

Defined in node_modules/@types/node/events.d.ts:31

**Parameters:**

| Name    | Type                 |
| ------- | -------------------- |
| `event` | string &#124; symbol |

**Returns:** _Function[]_

---

### removeAllListeners

▸ **removeAllListeners**(`event?`: string | symbol): _this_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[removeAllListeners](_client_websocketclient_.websocketclient.md#removealllisteners)_

_Overrides void_

Defined in node_modules/@types/node/events.d.ts:27

**Parameters:**

| Name     | Type                 |
| -------- | -------------------- |
| `event?` | string &#124; symbol |

**Returns:** _this_

---

### removeListener

▸ **removeListener**(`event`: string | symbol, `listener`: function): _this_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[removeListener](_client_websocketclient_.websocketclient.md#removelistener)_

_Overrides void_

Defined in node_modules/@types/node/events.d.ts:25

**Parameters:**

▪ **event**: _string | symbol_

▪ **listener**: _function_

▸ (...`args`: any[]): _void_

**Parameters:**

| Name      | Type  |
| --------- | ----- |
| `...args` | any[] |

**Returns:** _this_

---

### setMaxListeners

▸ **setMaxListeners**(`n`: number): _this_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[setMaxListeners](_client_websocketclient_.websocketclient.md#setmaxlisteners)_

_Overrides void_

Defined in node_modules/@types/node/events.d.ts:28

**Parameters:**

| Name | Type   |
| ---- | ------ |
| `n`  | number |

**Returns:** _this_

---

### `Static` listenerCount

▸ **listenerCount**(`emitter`: EventEmitter, `event`: string | symbol): _number_

_Inherited from [WebSocketClient](_client_websocketclient_.websocketclient.md).[listenerCount](_client_websocketclient_.websocketclient.md#static-listenercount)_

Defined in node_modules/@types/node/events.d.ts:17

**`deprecated`** since v4.0.0

**Parameters:**

| Name      | Type                 |
| --------- | -------------------- |
| `emitter` | EventEmitter         |
| `event`   | string &#124; symbol |

**Returns:** _number_

---

### `Static` stringifyPayload

▸ **stringifyPayload**(`config`: AxiosRequestConfig): _string_

_Defined in [src/client/RESTClient.ts:109](https://github.com/bennyn/coinbase-pro-node/blob/1a12582/src/client/RESTClient.ts#L109)_

**Parameters:**

| Name     | Type               |
| -------- | ------------------ |
| `config` | AxiosRequestConfig |

**Returns:** _string_
