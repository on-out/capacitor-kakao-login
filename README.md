# @onout/capacitor-kakao-login

capacitor for kakao login

## Install

```bash
npm install @onout/capacitor-kakao-login
npx cap sync
```

## API

<docgen-index>

* [`goLogin()`](#gologin)
* [`goLogout()`](#gologout)
* [`getUserInfo()`](#getuserinfo)
* [`sendLinkFeed(...)`](#sendlinkfeed)
* [`talkInChannel(...)`](#talkinchannel)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### goLogin()

```typescript
goLogin() => Promise<{ "accessToken": string; "expiredAt": string; "expiresIn": string; "refreshToken": string; "idToken": string; "refreshTokenExpiredAt": string; "refreshTokenExpiresIn": string; "tokenType": string; }>
```

**Returns:** <code>Promise&lt;{ accessToken: string; expiredAt: string; expiresIn: string; refreshToken: string; idToken: string; refreshTokenExpiredAt: string; refreshTokenExpiresIn: string; tokenType: string; }&gt;</code>

--------------------


### goLogout()

```typescript
goLogout() => Promise<any>
```

**Returns:** <code>Promise&lt;any&gt;</code>

--------------------


### getUserInfo()

```typescript
getUserInfo() => Promise<{ value: any; }>
```

**Returns:** <code>Promise&lt;{ value: any; }&gt;</code>

--------------------


### sendLinkFeed(...)

```typescript
sendLinkFeed(options: { title: string; description: string; imageUrl: string; imageLinkUrl: string; buttonTitle: string; imageWidth?: number; imageHeight?: number; }) => Promise<void>
```

| Param         | Type                                                                                                                                                         |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **`options`** | <code>{ title: string; description: string; imageUrl: string; imageLinkUrl: string; buttonTitle: string; imageWidth?: number; imageHeight?: number; }</code> |

--------------------


### talkInChannel(...)

```typescript
talkInChannel(options: { publicId: string; }) => Promise<any>
```

| Param         | Type                               |
| ------------- | ---------------------------------- |
| **`options`** | <code>{ publicId: string; }</code> |

**Returns:** <code>Promise&lt;any&gt;</code>

--------------------

</docgen-api>
