---
title: KSPROPERTY\_CAMERACONTROL\_FLASH\_PROPERTY
description: User-mode clients use this property to get or set a camera's flash control characteristics. This property is optional.
keywords: ["KSPROPERTY_CAMERACONTROL_FLASH_PROPERTY Streaming Media Devices"]
topic_type:
- apiref
api_name:
- KSPROPERTY_CAMERACONTROL_FLASH_PROPERTY
api_location:
- Ksmedia.h
api_type:
- HeaderDef
ms.date: 11/28/2017
ms.localizationpriority: medium
---

# KSPROPERTY\_CAMERACONTROL\_FLASH\_PROPERTY


User-mode clients use this property to get or set a camera's flash control characteristics. This property is optional.

## <span id="ddk_ksproperty_cameracontrol_pan_ks"></span><span id="DDK_KSPROPERTY_CAMERACONTROL_PAN_KS"></span>


### Usage Summary Table

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>Get</th>
<th>Set</th>
<th>Target</th>
<th>Property descriptor type</th>
<th>Property value type</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Filter</p></td>
<td><p><a href="/windows-hardware/drivers/stream/ksproperty-structure" data-raw-source="[&lt;strong&gt;KSPROPERTY&lt;/strong&gt;](./ksproperty-structure.md)"><strong>KSPROPERTY</strong></a></p></td>
<td><a href="/windows-hardware/drivers/ddi/ksmedia/ns-ksmedia-ksproperty_cameracontrol_flash_s" data-raw-source="[&lt;strong&gt;KSPROPERTY_CAMERACONTROL_FLASH_S&lt;/strong&gt;](/windows-hardware/drivers/ddi/ksmedia/ns-ksmedia-ksproperty_cameracontrol_flash_s)"><strong>KSPROPERTY_CAMERACONTROL_FLASH_S</strong></a></td>
</tr>
</tbody>
</table>

 

## Remarks

The property ID is **KSPROPERTY\_CAMERACONTROL\_FLASH\_PROPERTY\_ID**.

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Header</p></td>
<td>Ksmedia.h (include Ksmedia.h)</td>
</tr>
</tbody>
</table>

## See also


[**KSPROPERTY**](ksproperty-structure.md)

[**KSPROPERTY\_CAMERACONTROL\_FLASH\_S**](/windows-hardware/drivers/ddi/ksmedia/ns-ksmedia-ksproperty_cameracontrol_flash_s)