---
-api-id: P:Microsoft.UI.Xaml.Controls.Primitives.ListViewItemPresenter.SelectedBorderThickness
-api-type: winrt property
---

<!-- Property syntax
public Windows.UI.Xaml.Thickness SelectedBorderThickness { get;  set; }
-->

# Microsoft.UI.Xaml.Controls.Primitives.ListViewItemPresenter.SelectedBorderThickness

## -description
Gets or sets the thickness of the border around an item that's selected. This property is ignored for a Windows 10 app.

**This documentation applies to WinUI 2 for UWP** (for [WinUI](/windows/apps/winui/winui3/) in the [Windows App SDK](/windows/apps/windows-app-sdk/), see the **[Windows App SDK namespaces](/windows/windows-app-sdk/api/winrt/)**).

## -xaml-syntax
```xaml
<listViewItemPresenter SelectedBorderThickness="uniform"/>
- or -
<listViewItemPresenter SelectedBorderThickness="left&right,top&bottom"/>
- or -
<listViewItemPresenter SelectedBorderThickness="left,top,right,bottom"/>
```


## -xaml-values
<dl><dt>uniform</dt><dd>uniformA numeric value that specifies a uniform Thickness. The uniform value is applied to all four Thickness values (Left, Top, Right, Bottom).</dd>
<dt>left&amp;right</dt><dd>left&amp;rightA numeric value that specifies the Left and Right values of a symmetrical Thickness.</dd>
<dt>top&amp;bottom</dt><dd>top&amp;bottomA numeric value that specifies the Top and Bottom values of a symmetrical Thickness.</dd>
<dt>left,top,right,bottom</dt><dd>left,top,right,bottomFloating-point values that specify the four possible dimension values of a Thickness structure (Left, Top, Right, Bottom).</dd>
</dl>
## -property-value
The thickness of the border around an item that's selected, as a [Thickness](../microsoft.ui.xaml/thickness.md) value.

## -remarks

## -examples

## -see-also
