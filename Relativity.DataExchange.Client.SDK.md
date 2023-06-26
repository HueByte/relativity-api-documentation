# Relativity.DataExchange.Client.SDK Version Compatibility

[![nuget](https://img.shields.io/nuget/v/Relativity.DataExchange.Client.SDK.svg)](https://www.nuget.org/packages/Relativity.DataExchange.Client.SDK)

The Relativity data exchange client SDK .NET package.

## v1.20.26

### Release Notes

#### Fixed

* Add EnableTextFileSizeCheck app configuration parameter - force checking file size
* Multi page tiff validation
* Detection of unsupportedby viewer value for first loadfile records only

### Supported Relativity Version Range

Lowest Version | Highest Version
---  | ---
14.4 | latest

## v1.17.7

### Release Notes

#### Fixed

* Removed usage of BCP path

### Supported Relativity Version Range

Lowest Version | Highest Version
---  | ---
13.2 | latest

## v1.17.2

### Release Notes

#### Fixed

* Added retry transfer using aspera/direct mode before switching to a web mode
* Updated Relativity.Telemetry.Services.Interface version
  Updated Relativity.Transfer.Client version
* Fixed counting Extracted Text size from files on the server to correctly count against ImportBatchMaxVolume
* Improved audit and errors when there was no batch executed during Image import

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
9.7 | latest

## v1.15.33

### Release Notes

#### Fixed

* ImportAPI uses BeginBatesFieldArtifactID as an Overlay identifier

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
9.7 | latest

## v1.15.30

### Release Notes

#### Fixed

* Updated Relativity.Telemetry.Services.Interface version

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
9.7 | latest

## v1.15.29

### Release Notes

#### Fixed

* Updated Relativity.Transfer.Client version
* Updated Relativity.Telemetry.Services.Interface version

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
9.7 | latest

## v1.15.27

### Release Notes

* Updated Release Notes URL in a nuget

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
9.7 | latest

## v1.15.22

### Release Notes

#### Fixed

* Support for Kepler API, replacment for WebAPI services
* Improved performance
* Updated Relativity.OutsideIn version
* Updated Relativity.Transfer.Client version

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
9.7 | latest

## v1.14.13

### Release Notes

#### Fixed

* Improved performance of logging
* Updated Relativity.OutsideIn version
* Updated Relativity.Transfer.Client version

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
9.7 | 12.2

## v1.13.28

### Release Notes

#### Fixed

* Removed vulnerable FreeImage library
* Updated OutsideIn library due to security vulnerability

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
9.7 | 12.1

## v1.13.16

### Release Notes

Initial Version

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
9.7 | 12.1
