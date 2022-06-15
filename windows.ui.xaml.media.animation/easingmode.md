---
-api-id: T:Windows.UI.Xaml.Media.Animation.EasingMode
-api-type: winrt enum
---

<!-- Enumeration syntax
public enum Windows.UI.Xaml.Media.Animation.EasingMode : int
-->

# EasingMode

## -description
Specifies how the animation associated with an easing function interpolates.

Equivalent **WinUI 2 API for UWP**: [EasingMode](/windows/winui/api/microsoft.ui.xaml.media.animation.easingmode) (for WinUI in the [Windows App SDK](/windows/apps/windows-app-sdk/), see the **[Windows App SDK namespaces](/windows/windows-app-sdk/api/winrt/)**).

## -xaml-syntax
```xaml
<object property="enumMemberName"/>
```


## -enum-fields
### -field EaseOut:0
Interpolation follows 100% interpolation minus the output of the formula associated with the easing function.

### -field EaseIn:1
Interpolation follows the mathematical formula associated with the easing function.

### -field EaseInOut:2
Interpolation uses **EaseIn** for the first half of the animation and **EaseOut** for the second half.


## -remarks

## -examples

## -see-also
