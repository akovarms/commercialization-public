---
title: Parameters
description: Parameters
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: f46ca8b1-9de5-486c-a480-d245d51306d7
ms.prod: W10
ms.mktglfcycl: deploy
ms.sitesec: msdn
ms.author: alhopper
ms.date: 05/02/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-oem
---

# Parameters


`Parameters` specifies the arguments to add to [CustomPowerApplication1](microsoft-windows-stobject-custompowerapplication1.md).

This setting is optional.

## Values


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><em>Parameters</em></p></td>
<td><p>Specifies the arguments to use when running the application specified by [CustomPowerApplication1](microsoft-windows-stobject-custompowerapplication1.md).</p>
<p><em>Parameters</em> is a string.</p></td>
</tr>
</tbody>
</table>

 

This string type supports empty elements.

## Valid Passes


generalize

specialize

## Parent Hierarchy


[Microsoft-Windows-stobject](microsoft-windows-stobject.md) | [CustomPowerApplication1](microsoft-windows-stobject-custompowerapplication1.md) | **Parameters**

## Applies To


For the list of the supported Windows editions and architectures that this component supports, see [Microsoft-Windows-stobject](microsoft-windows-stobject.md).

## XML Example


The following XML output shows `CustomPowerApplication1` Application.exe with `parameter -param`. `IconID` and `ItemName` are included in Resource.dll.

``` syntax
<CustomPowerApplication1>
   <Application>C:\Program Files\CustomPower\Application.exe</Application>
   <IconID>@%ProgramFiles%\Microsoft Shared\Resource.dll,-200</IconID>
   <ItemName>%ProgramFiles%\Microsoft Shared\Resource.dll,-100</ItemName>
   <Parameters>-param</Parameters>
</CustomPowerApplication1>
```

## Related topics


[CustomPowerApplication1](microsoft-windows-stobject-custompowerapplication1.md)

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bp_unattend\p_unattend%5D:%20Parameters%20%20RELEASE:%20%2810/3/2016%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")





