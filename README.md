[![TvmSdk](https://img.shields.io/nuget/v/TvmSdk)](https://www.nuget.org/packages/TvmSdk/)
[![Chat on Telegram](https://img.shields.io/badge/chat-on%20telegram-9cf.svg)](https://t.me/tvm_sdk_dotnet)
[![Chat on Telegram](https://img.shields.io/badge/.NET-9-9cf.svg)](https://t.me/tvm_sdk_dotnet)
[<img src="https://avatars.githubusercontent.com/u/177059119?s=400&u=77d20c714206215623219ab13163ec5827481198&v=4" align="right" width="150">](https://freeton.org/)

# TVM SDK .NET Client

Client library for DApp development in TVM blockchains (TON, Acki Nacki, Venom Blockchain, Everscale.
- Built with latest .NET 9
- Client is automatically generated using Roslyn from [api.json](https://github.com/tvmlabs/tvm-sdk/blob/main/tools/api.json) (see [TVM SDK Client Generator](https://github.com/TvmBrotherhood/tvm-sdk-dotnet/tree/main/tools/TvmSdk.ClientGenerator))
- Uses `System.Text.Json` serializer with polymorphism
- Classes and modules has good built-in documentation

## Installation

```shell
dotnet add package TvmSdk
```

## Prerequisites
- [.NET SDK](https://dotnet.microsoft.com/download) (9.0 or later)

## API
[JSON schema](https://github.com/TvmGuild/tvm-sdk-dotnet/blob/main/tools/TvmSdk.ClientGenerator/api.json)
More of examples you can find in [tests](https://github.com/TvmGuild/tvm-sdk-dotnet/tree/main/tests/TvmSdk.Tests)

More documentation is available [here](https://github.com/tvmlabs/tvm-sdk/blob/master/docs/SUMMARY.md)

## TODO list
- [ ] Add usage examples
  - [ ] Simple console application
  - [ ] Complex example with contract and network usage - DePool election transaction automatic approval (It is already developed but needs refactoring)
  - [ ] Unity in game example
  - [ ] Blazor 
  - [ ] MAUI
- [ ] Add more tests
- [ ] Add dotnet standard support
- [ ] Generate API classes automatically + TvmClient
- [ ] Add benchmarks
