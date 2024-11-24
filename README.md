# DependabotTest2

[![Dependabot Updates](https://github.com/goswinr/DependabotTest2/actions/workflows/dependabot/dependabot-updates/badge.svg)](https://github.com/goswinr/DependabotTest2/actions/workflows/dependabot/dependabot-updates)

To demonstrate that dependabot is able to update FSharp.Core

if

```xml
<DisableImplicitFSharpCoreReference>true</DisableImplicitFSharpCoreReference>

...

<PackageReference Include="FSharp.Core" Version="6.0.7" />
```
is present

https://github.com/goswinr/DependabotTest2/pull/1

for issue https://github.com/dependabot/dependabot-core/issues/10883
