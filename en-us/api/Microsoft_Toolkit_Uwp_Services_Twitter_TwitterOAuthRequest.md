---
permalink: /en-US/api/Microsoft_Toolkit_Uwp_Services_Twitter_TwitterOAuthRequest.htm
title: Microsoft.Toolkit.Uwp.Services.Twitter.TwitterOAuthRequest API 
description: API page for Microsoft.Toolkit.Uwp.Services.Twitter.TwitterOAuthRequest
keywords: windows, app, toolkit, UWP, API
layout: api
search.product: eADQiWindows 10XVcnh
---


# TwitterOAuthRequest class

OAuth request.

## Members

The **TwitterOAuthRequest** class has the following types of members:

### Methods

#### ExecuteGetAsync(System.Uri requestUri,Microsoft.Toolkit.Uwp.Services.Twitter.TwitterOAuthTokens tokens)

HTTP Get request to specified Uri.

##### Parameters



| Name | Description | Type || --- | --- | --- || requestUri | Uri to make OAuth request. | [Uri](https://msdn.microsoft.com/library/windows/apps/System.Uri) || tokens | Tokens to pass in request. | [TwitterOAuthTokens](Microsoft_Toolkit_Uwp_Services_Twitter_TwitterOAuthTokens.htm) || return |String result. |


#### ExecutePostAsync(System.Uri requestUri,Microsoft.Toolkit.Uwp.Services.Twitter.TwitterOAuthTokens tokens)

HTTP Post request to specified Uri.

##### Parameters



| Name | Description | Type || --- | --- | --- || requestUri | Uri to make OAuth request. | [Uri](https://msdn.microsoft.com/library/windows/apps/System.Uri) || tokens | Tokens to pass in request. | [TwitterOAuthTokens](Microsoft_Toolkit_Uwp_Services_Twitter_TwitterOAuthTokens.htm) || return |String result. |


#### ExecutePostMultipartAsync(System.Uri requestUri,Microsoft.Toolkit.Uwp.Services.Twitter.TwitterOAuthTokens tokens,System.String boundary,System.Byte[] content)

HTTP Post request to specified Uri.

##### Parameters



| Name | Description | Type || --- | --- | --- || requestUri | Uri to make OAuth request. | [Uri](https://msdn.microsoft.com/library/windows/apps/System.Uri) || tokens | Tokens to pass in request. | [TwitterOAuthTokens](Microsoft_Toolkit_Uwp_Services_Twitter_TwitterOAuthTokens.htm) || boundary | Boundary used to separate data. | [String](https://msdn.microsoft.com/library/windows/apps/System.String) || content | Data to post to server. | [Byte[]](https://msdn.microsoft.com/library/windows/apps/System.Byte) || return |String result. |

