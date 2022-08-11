# .NET Workloads Reference
This repository is a compiled data set of the .NET Workloads and what versions of .NET MAUI, Uno Platform, and .NET Mobile (native) are compatible with each release.

## Pull Requests Welcomed ♥
The information contained in this repository is manually maintained by @SkyeHoefling, if you see something that needs updating or a new version. Please create a pull request or an issue

# .NET Workloads
The release bands for .NET Workloads and their compatible versions.

**NOTE** The SDK versions are incremented several times in a release band to stay up to date with the latest build tools from android, ios, mac, etc. The versions listed here are latest at time of writing and may be different than what is delivered in the dotnet workload.

## 6.0.4xx
| Product/Platform | Version                       |
|------------------|-------------------------------|
| Visual Studio    | 17.3                          |
| Xcode            | 13.3                          |
| iOS              | 15.4.430                      |
| tvOS             | 15.4.430                      |
| macOS            | 12.3.430                      |
| macCatalyst      | 15.4.430                      |
| Android          | 32.0.440                      |


## 6.0.3xx
| Product/Platform | Version                       |
|------------------|-------------------------------|
| Visual Studio    | 17.2                          |
| Xcode            | 13.3                          |
| iOS              | 15.4.315                      |
| tvOS             | 15.4.315                      |
| macOS            | 12.3.315                      |
| macCatalyst      | 15.4.315                      |
| Android          | 32.0.440                      |

# .NET MAUI
| dotnet workload | .NET MAUI                     | Notes |
| ----------------|-------------------------------|-------|
| 6.0.400         | 6.0.486 (Service Release 4)   |       |
| 6.0.400         | 6.0.424 (Service Release 3.1) | First version to reference .NET workload 6.0.400 explicitly |
| 6.0.300?        | 6.0.419 (Service Release 3)   | Unsure if this uses 6.0.300 or 6.0.400      |
| 6.0.300?        | 6.0.408 (Service Release 2)   | Unsure if this uses 6.0.300 or 6.0.400      |
| 6.0.300?        | 6.0.400 (Service Release 1)   | Unsure if this uses 6.0.300 or 6.0.400      |
| 6.0.300         | 6.0.312                       |       |

# Uno Platform
[Uno Platform](https://github.com/unoplatform/uno) is a 3rd party cross-platform UI tool and is not maintained by Microsoft. The build tools [Uno.Check](https://github.com/unoplatform/uno.check) uses the .NET workload and the releases of Uno Platform are independent of the .NET workload. The table below references the versions of uno.check and their compatibility with .NET workloads and Visual Studio.

| Uno Platform (uno.check) | dotnet workload | Visual Studio |
| -------------------------|-----------------|---------------|
| 1.5.3                    | 6.0.400         | 17.3.0        |
| 1.5.2                    | 6.0.300         | 17.2.0        |
| 1.5.1                    | 6.0.300         | 17.2.0        |
| 1.5.0                    | 6.0.300         | 17.2.0        |

# Created By Skye Hoefling
This repository is created by and maintained by [@SkyeHoefling](https://github.com/SkyeHoefling). The data is pulled from various repositories throughout the .NET Mobile and Cross-Platform community. Below is a list of sources where the data has been obtained from

* https://github.com/xamarin/xamarin-macios
* https://github.com/xamarin/xamarin-android
* https://github.com/dotnet/maui
* https://github.com/unoplatform/uno
* https://github.com/unoplatform/uno.check
* https://NuGet.org
* https://github.com/dotnet/sdk