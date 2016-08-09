---
permalink: /en-US/helpers/imagecache.htm
title: ImageCache utility
description: ImageCache provides methods and tools to cache images in a temporary local folder
keywords: windows, app, toolkit, UWP, helpers, image, cache
layout: default
search.product: eADQiWindows 10XVcnh
---

# ImageCache

The **ImageCache** provides methods and tools to cache images in a temporary local folder.

## Example

```C#
	var distantUri = new Uri("http://www.myserver.com/image.jpg");

	// Load a specific image from the cache. If the image is not in the cache, ImageCache will try to download and store it
	var bitmapImage = await ImageCache.GetFromCacheAsync(distantUri);

	// Gets the local cache file name associated with a specified Uri
	var localFilename = ImageCache.GetCacheFileName(distantUri);

	// Clear the cache. Please note that you can provide a parameter to define a timespan from now to select cache entries to delete.
	await ImageCache.ClearAsync();

	// Set cache duration
	ImageCache.CacheDuration = TimeSpan.FromHours(24);

```

## Platforms

Windows 10 SDK 10586 or higher

## API

* [ImageCache source code](https://github.com/Microsoft/UWPCommunityToolkit/blob/master/Microsoft.Toolkit.Uwp.UI/ImageCache/ImageCache.cs)
* [ImageCache API documentation]({{site.baseurl}}/api/Microsoft_Toolkit_Uwp_UI_ImageCache.htm)
