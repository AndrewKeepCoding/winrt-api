---
-api-id: T:Windows.UI.Xaml.LineStackingStrategy
-api-type: winrt enum
---

<!-- Enumeration syntax
public enum Windows.UI.Xaml.LineStackingStrategy : int
-->

# LineStackingStrategy

## -description
Describes the mechanism by which a line box is determined for each line.

Equivalent **WinUI 2 API for UWP**: [LineStackingStrategy](/windows/winui/api/microsoft.ui.xaml.linestackingstrategy) (for WinUI in the [Windows App SDK](/windows/apps/windows-app-sdk/), see the **[Windows App SDK namespaces](/windows/windows-app-sdk/api/winrt/)**).

## -xaml-syntax
```xaml
<object property="enumMemberName"/>
```


## -enum-fields
### -field MaxHeight:0
The stack height is the minimum of the extended block progression dimension (height) of all the inline elements when properly aligned and the [LineHeight](../windows.ui.xaml.documents/block_lineheight.md) value, if specified.

### -field BlockLineHeight:1
The stack height is determined by the block element's [LineHeight](../windows.ui.xaml.documents/block_lineheight.md) property value.

### -field BaselineToBaseline:2
The stack height is determined by adding [LineHeight](../windows.ui.xaml.documents/block_lineheight.md) to the baseline of the previous line.


## -remarks

## -examples

## -see-also
