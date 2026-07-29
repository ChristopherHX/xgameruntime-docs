# IXNetworkingImpl

Interface Id: `37e56907-2f10-41e8-b72f-36edb185331a`

Inherits: IUnknown

Layout:
- [XNetworkingQueryPreferredLocalUdpMultiplayerPort](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkingquerypreferredlocaludpmultiplayerport)
- [XNetworkingQueryPreferredLocalUdpMultiplayerPortAsync](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkingquerypreferredlocaludpmultiplayerportasync)
- [XNetworkingQueryPreferredLocalUdpMultiplayerPortAsyncResult](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkingquerypreferredlocaludpmultiplayerportasyncresult)
- [XNetworkingRegisterPreferredLocalUdpMultiplayerPortChanged](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkingregisterpreferredlocaludpmultiplayerportchanged)
- [XNetworkingUnregisterPreferredLocalUdpMultiplayerPortChanged](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkingunregisterpreferredlocaludpmultiplayerportchanged)
- [XNetworkingQuerySecurityInformationForUrlAsync](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkingquerysecurityinformationforurlasync)
- [XNetworkingQuerySecurityInformationForUrlAsyncResultSize](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkingquerysecurityinformationforurlasyncresultsize)
- [XNetworkingQuerySecurityInformationForUrlAsyncResult](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkingquerysecurityinformationforurlasyncresult)
- [XNetworkingQuerySecurityInformationForUrlUtf16Async](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkingquerysecurityinformationforurlutf16async)
- [XNetworkingQuerySecurityInformationForUrlUtf16AsyncResultSize](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkingquerysecurityinformationforurlutf16asyncresultsize)
- [XNetworkingQuerySecurityInformationForUrlUtf16AsyncResult](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkingquerysecurityinformationforurlutf16asyncresult)
- [XNetworkingVerifyServerCertificate](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkingverifyservercertificate)
- [XNetworkingGetConnectivityHint](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkinggetconnectivityhint)
- [XNetworkingRegisterConnectivityHintChanged](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkingregisterconnectivityhintchanged)
- [XNetworkingUnregisterConnectivityHintChanged](https://learn.microsoft.com/gaming/gdk/docs/reference/networking/xnetworking/functions/xnetworkingunregisterconnectivityhintchanged)

## Known issues of titles requireing this feature

Some titles run with more relaxed requirements.

### Asphalt Legends
https://www.xbox.com/en-US/games/store/asphalt-legends/9nzqpt0mwtd0

XNetworkingGetConnectivityHint should not return 0 as ianaType, for the game to attempt XboxLive Authentication that is mandatory for this game to connect to the server.
