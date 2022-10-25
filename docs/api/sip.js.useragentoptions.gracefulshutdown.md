<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [UserAgentOptions](./sip.js.useragentoptions.md) &gt; [gracefulShutdown](./sip.js.useragentoptions.gracefulshutdown.md)

## UserAgentOptions.gracefulShutdown property

If `true`<!-- -->, the `stop()` method will attempt to gracefully end all dialogs and registrations before disconnecting. Otherwise `stop()` will transition immediately abandoning all dialogs and registrations.

<b>Signature:</b>

```typescript
gracefulShutdown?: boolean;
```