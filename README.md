# DependabotTest2

[![Dependabot Updates](https://github.com/goswinr/DependabotTest2/actions/workflows/dependabot/dependabot-updates/badge.svg)](https://github.com/goswinr/DependabotTest2/actions/workflows/dependabot/dependabot-updates)

A minimal repo to demonstrate that dependabot is able to update FSharp.Core

only if

```xml
<DisableImplicitFSharpCoreReference>true</DisableImplicitFSharpCoreReference>
```
and
```xml
<PackageReference Include="FSharp.Core" Version="6.0.7" />
```
is present.
See PR created https://github.com/goswinr/DependabotTest2/pull/1

But it fails with the default
```xml
<PackageReference Update="FSharp.Core" Version="6.0.7" />
```
as seen in this other repo: https://github.com/goswinr/DependabotTest .


This issue is raised on the dependabot-core repo:  https://github.com/dependabot/dependabot-core/issues/10883
