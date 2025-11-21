# zazafiles
My windows dotfiles
<details>
<summary>Main WIndhawk Mods</summary>
  
  1. Modernize File Picker Dialog
  2. Translucent windows
  ```json
{"RenderingMod.ThemeBackground":1,"RenderingMod.AccentColorControls":1,"RenderingMod.TextAlphaBlend":1,"type":"mica","AccentBlurBehind":"88202020","ImmersiveDarkTitle":1,"ExtendFrame":1,"CornerOption":"default","RainbowSpeed":1,"TitlebarColor.ColorTitlebar":0,"TitlebarColor.RainbowTitlebar":0,"TitlebarColor.titlerbarstyles_active":"2","TitlebarColor.titlerbarstyles_inactive":"00FFFF","TitlebarTextColor.ColorTitlebarText":0,"TitlebarTextColor.RainbowTextColor":0,"TitlebarTextColor.titlerbarcolorstyles_active":"FF0000","TitlebarTextColor.titlerbarcolorstyles_inactive":"00FFFF","BorderColor.ColorBorder":0,"BorderColor.RainbowBorder":0,"BorderColor.borderstyles_active":"2","BorderColor.borderstyles_inactive":"1","BorderColor.MenuBorderColor":0,"RuledPrograms[0].target":"olk.exe","RuledPrograms[0].type":"acrylicblur","RuledPrograms[0].AccentBlurBehind":"88202020","RuledPrograms[0].ImmersiveDarkTitle":0,"RuledPrograms[0].ExtendFrame":0,"RuledPrograms[0].CornerOption":"default","RuledPrograms[0].RainbowSpeed":1,"RuledPrograms[0].TitlebarColor.ColorTitlebar":0,"RuledPrograms[0].TitlebarColor.RainbowTitlebar":0,"RuledPrograms[0].TitlebarColor.titlerbarstyles_active":"2","RuledPrograms[0].TitlebarColor.titlerbarstyles_inactive":"1","RuledPrograms[0].TitlebarTextColor.ColorTitlebarText":0,"RuledPrograms[0].TitlebarTextColor.RainbowTextColor":0,"RuledPrograms[0].TitlebarTextColor.titlerbarcolorstyles_active":"FF0000","RuledPrograms[0].TitlebarTextColor.titlerbarcolorstyles_inactive":"00FFFF","RuledPrograms[0].BorderColor.ColorBorder":0,"RuledPrograms[0].BorderColor.RainbowBorder":0,"RuledPrograms[0].BorderColor.borderstyles_active":"2","RuledPrograms[0].BorderColor.borderstyles_inactive":"1"}
```
  4. Turn off change file extension warning

</details>

## 1. Modern Dock
<details>
<summary>Contents</summary>
  
![](https://raw.githubusercontent.com/zzsmkr/zazafiles/refs/heads/main/Previews/%7BD01B8BF8-F8FB-4D3D-8341-3EC215016642%7D.png)
### 1. Windows 11 Taskbar Styler
```json
{
  "controlStyles[0].target": "Taskbar.TaskbarFrame#TaskbarFrame",
  "controlStyles[0].styles[1]": "HorizontalAlignment=Center",
  "controlStyles[0].styles[2]": "Width=Auto",
  "controlStyles[1].target": "Taskbar.TaskbarFrame#TaskbarFrame > Grid#RootGrid",
  "controlStyles[1].styles[0]": "Padding=-1,-3,0,-2.5",
  "controlStyles[1].styles[1]": "Margin=0,0,0,3",
  "controlStyles[1].styles[2]": "BorderThickness=1",
  "controlStyles[1].styles[3]": "BorderBrush:=<SolidColorBrush Color=\"{ThemeResource SurfaceStrokeColorDefault}\" Opacity=\"0.5\" />",
  "controlStyles[2].target": "Rectangle#BackgroundFill",
  "controlStyles[2].styles[0]": "Visibility=Collapsed",
  "controlStyles[3].target": "Rectangle#BackgroundStroke",
  "controlStyles[3].styles[0]": "Visibility=Collapsed",
  "controlStyles[4].target": "Taskbar.AugmentedEntryPointButton#AugmentedEntryPointButton > Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel",
  "controlStyles[4].styles[0]": "Margin=0",
  "controlStyles[5].target": "Grid#SystemTrayFrameGrid",
  "controlStyles[5].styles[0]": "Background:=#00000000",
  "controlStyles[5].styles[1]": "CornerRadius=10",
  "controlStyles[5].styles[2]": "BackgroundSizing=InnerBorderEdge",
  "controlStyles[5].styles[3]": "Margin=-240,-3,176,1",
  "controlStyles[5].styles[4]": "BorderThickness=5",
  "controlStyles[6].target": "SystemTray.ChevronIconView",
  "controlStyles[6].styles[0]": "Padding=0",
  "controlStyles[7].target": "SystemTray.NotifyIconView#NotifyItemIcon",
  "controlStyles[7].styles[0]": "Padding=0",
  "controlStyles[8].target": "SystemTray.OmniButton",
  "controlStyles[8].styles[0]": "Padding=0",
  "controlStyles[9].target": "SystemTray.CopilotIcon",
  "controlStyles[9].styles[0]": "Padding=0",
  "controlStyles[10].target": "SystemTray.OmniButton#NotificationCenterButton > Grid > ContentPresenter > ItemsPresenter > StackPanel > ContentPresenter > systemtray:IconView#SystemTrayIcon > Grid",
  "controlStyles[10].styles[0]": "Padding=4,0,4,0",
  "controlStyles[11].target": "SystemTray.IconView#SystemTrayIcon > Grid#ContainerGrid > ContentPresenter#ContentPresenter > Grid#ContentGrid > SystemTray.TextIconContent > Grid#ContainerGrid",
  "controlStyles[11].styles[0]": "Padding=0",
  "controlStyles[12].target": "SystemTray.StackListView#IconStack > ItemsPresenter > StackPanel > ContentPresenter > SystemTray.IconView#SystemTrayIcon",
  "controlStyles[12].styles[0]": "Padding=0",
  "controlStyles[13].target": "SystemTray.Stack#ShowDesktopStack",
  "controlStyles[13].styles[0]": "Margin=0,-4,-12,-4",
  "controlStyles[14].target": "Taskbar.Gripper#GripperControl",
  "controlStyles[14].styles[0]": "Width=Auto",
  "controlStyles[14].styles[1]": "MinWidth=24",
  "controlStyles[1].styles[4]": "CornerRadius=6",
  "controlStyles[1].styles[5]": "Background:=<AcrylicBrush TintColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" FallbackColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" TintOpacity=\"0\" TintLuminosityOpacity=\".85\" Opacity=\"1\"/>",
  "controlStyles[0].styles[0]": "MaxWidth=1350",
  "controlStyles[0].styles[3]": "MinWidth=1350",
  "controlStyles[5].styles[5]": "HorizontalAlignment=1",
  "controlStyles[5].styles[6]": "Padding=0,0,0,0",
  "controlStyles[15].target": "TextBlock#DateInnerTextBlock",
  "controlStyles[15].styles[0]": "Visibility=Collapsed",
  "controlStyles[16].target": "TextBlock#TimeInnerTextBlock",
  "controlStyles[16].styles[0]": "FontSize=13"
}
```
### 2. Taskbar height and icon size
```json
{"TaskbarHeight":43,"IconSize":24,"TaskbarButtonWidth":38,"IconSizeSmall":16,"TaskbarButtonWidthSmall":32}
```

### 3. Windows 11 Start Menu Styler
```json
{
  "controlStyles[0].target": "Grid#ShowMoreSuggestions",
  "controlStyles[0].styles[0]": "Visibility=1",
  "controlStyles[1].target": "Grid#SuggestionsParentContainer",
  "controlStyles[1].styles[0]": "Visibility=1",
  "controlStyles[2].target": "Grid#TopLevelSuggestionsListHeader",
  "controlStyles[2].styles[0]": "Visibility=1",
  "controlStyles[3].target": "StartMenu.SearchBoxToggleButton",
  "controlStyles[3].styles[0]": "Margin=5,2,-5,-2",
  "controlStyles[4].target": "Border#AcrylicBorder",
  "controlStyles[4].styles[0]": "Background:=<AcrylicBrush TintColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" FallbackColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" TintOpacity=\"0\" TintLuminosityOpacity=\".85\" Opacity=\"1\"/>",
  "controlStyles[4].styles[1]": "CornerRadius=12",
  "controlStyles[4].styles[2]": "BorderBrush:=<SolidColorBrush Color=\"{ThemeResource SurfaceStrokeColorDefault}\" Opacity=\"0.5\" />",
  "controlStyles[5].target": "Grid#MainContent",
  "controlStyles[5].styles[0]": "CornerRadius=12",
  "controlStyles[6].target": "StartMenu.PinnedList",
  "controlStyles[6].styles[0]": "MaxWidth=650",
  "controlStyles[6].styles[1]": "Margin=-14,14,4,0",
  "controlStyles[7].target": "TextBlock#DisplayName",
  "controlStyles[7].styles[0]": "Margin=0,8,0,-8",
  "controlStyles[7].styles[1]": "FontSize=13",
  "controlStyles[7].styles[2]": "FontFamily=Aptos",
  "controlStyles[7].styles[3]": "Opacity=.75",
  "controlStyles[7].styles[4]": "FontWeight=500",
  "controlStyles[7].styles[5]": "Padding=14,0,14,0",
  "controlStyles[8].target": "TextBlock#PinnedListHeaderText",
  "controlStyles[8].styles[0]": "FontFamily=Aptos",
  "controlStyles[8].styles[1]": "Opacity=.85",
  "controlStyles[8].styles[2]": "FontSize=16",
  "controlStyles[8].styles[3]": "Margin=40,0,-40,0",
  "controlStyles[9].target": "Border#TaskbarSearchBackground",
  "controlStyles[9].styles[0]": "Visibility=1",
  "controlStyles[10].target": "Border#AppBorder",
  "controlStyles[10].styles[0]": "Background:=<AcrylicBrush TintColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" FallbackColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" TintOpacity=\"0\" TintLuminosityOpacity=\".85\" Opacity=\"1\"/>",
  "controlStyles[10].styles[1]": "BorderBrush:=<SolidColorBrush Color=\"{ThemeResource SurfaceStrokeColorDefault}\" Opacity=\"0.5\" />",
  "controlStyles[10].styles[2]": "CornerRadius=12",
  "controlStyles[11].target": "Border#StartDropShadow",
  "controlStyles[11].styles[0]": "CornerRadius=12",
  "controlStyles[11].styles[1]": "Margin=-1",
  "controlStyles[12].target": "Cortana.UI.Views.RichSearchBoxControl#SearchBoxControl",
  "controlStyles[12].styles[0]": "Margin=33,33,33,10",
  "controlStyles[13].target": "TextBlock#UserTileNameText",
  "controlStyles[13].styles[0]": "Visibility=1",
  "controlStyles[14].target": "TextBlock#AllListHeadingText",
  "controlStyles[14].styles[0]": "FontFamily=Aptos",
  "controlStyles[14].styles[1]": "Margin=50,5,0,0",
  "controlStyles[14].styles[2]": "FontSize=16",
  "controlStyles[14].styles[3]": "Opacity=.85",
  "controlStyles[15].target": "Border#ContentBorder",
  "controlStyles[15].styles[0]": "CornerRadius=6",
  "controlStyles[16].target": "StartMenu.SearchBoxToggleButton > Grid > ContentPresenter > TextBlock#PlaceholderText",
  "controlStyles[16].styles[0]": "Text=",
  "controlStyles[16].styles[1]": "FontWeight=700",
  "controlStyles[16].styles[2]": "FontFamily=Aptos",
  "controlStyles[16].styles[3]": "FontSize=24",
  "controlStyles[16].styles[4]": "Foreground:=<SolidColorBrush Color=\"{ThemeResource FocusStrokeColorOuter}\" Opacity=\".85\"/>",
  "controlStyles[16].styles[5]": "Margin=2,0,0,0",
  "controlStyles[17].target": "StartMenu.SearchBoxToggleButton > Grid > Border",
  "controlStyles[17].styles[0]": "Background=Transparent",
  "controlStyles[17].styles[1]": "BorderBrush=Transparent",
  "controlStyles[18].target": "StartMenu.SearchBoxToggleButton > Grid > FontIcon",
  "controlStyles[18].styles[0]": "Transform3D:=<CompositeTransform3D TranslateX=\"165\" TranslateY=\"-1\"/>",
  "controlStyles[18].styles[1]": "Foreground:=<SolidColorBrush Color=\"{ThemeResource FocusStrokeColorOuter}\" FallbackColor=\"{ThemeResource FocusStrokeColorOuter}\" Opacity=\".85\"/>",
  "controlStyles[18].styles[2]": "FontSize=24",
  "controlStyles[19].target": "Grid#TopLevelRoot",
  "controlStyles[19].styles[0]": "Margin=0,-8,0,0",
  "controlStyles[20].target": "StartDocked.UserTileView",
  "controlStyles[21].target": "StartDocked.UserTileView > StartDocked.NavigationPaneButton > Grid > Border",
  "controlStyles[21].styles[0]": "CornerRadius=99",
  "controlStyles[21].styles[1]": "Margin=7,0,8,1",
  "controlStyles[22].styles[0]": "RenderTransform:=<TranslateTransform X=\"-14\" Y=\"-685\" />",
  "controlStyles[22].target": "StartDocked.PowerOptionsView",
  "controlStyles[22].styles[1]": "CornerRadius=99",
  "controlStyles[22].styles[2]": "Opacity=.85",
  "controlStyles[23].target": "Border#AcrylicOverlay",
  "controlStyles[23].styles[0]": "Visibility=1",
  "controlStyles[24].target": "TextBlock#AppDisplayName",
  "controlStyles[24].styles[0]": "FontFamily=Aptos",
  "controlStyles[24].styles[1]": "Opacity=.85",
  "controlStyles[24].styles[2]": "Margin=4,0,0,4",
  "controlStyles[24].styles[3]": "FontWeight=500",
  "controlStyles[25].target": "Button#Header > Border > TextBlock",
  "controlStyles[25].styles[0]": "FontFamily=Aptos",
  "controlStyles[25].styles[1]": "FontWeight=600",
  "controlStyles[25].styles[2]": "Opacity=.85",
  "controlStyles[26].target": "StartDocked.PowerOptionsView > StartDocked.NavigationPaneButton > Grid > Border",
  "controlStyles[26].styles[0]": "CornerRadius=99",
  "controlStyles[26].styles[1]": "Margin=1",
  "controlStyles[27].target": "ListViewItem",
  "controlStyles[27].styles[0]": "Margin=1,5,-5,-5",
  "controlStyles[27].styles[1]": "CornerRadius=4",
  "controlStyles[28].target": "Button#Header",
  "controlStyles[28].styles[0]": "Margin=4,0,-3,-5",
  "controlStyles[29].target": "TextBlock#PlaceholderTextContentPresenter",
  "controlStyles[29].styles[0]": "FontFamily=Aptos",
  "controlStyles[29].styles[1]": "FontSize=24",
  "controlStyles[29].styles[2]": "FontWeight=700",
  "controlStyles[29].styles[3]": "Foreground:=<SolidColorBrush Color=\"{ThemeResource FocusStrokeColorOuter}\" Opacity=\".7\"/>",
  "controlStyles[30].target": "Microsoft.UI.Xaml.Controls.AnimatedIcon#SearchIconPlayer",
  "controlStyles[30].styles[0]": "Visibility=1",
  "controlStyles[31].target": "Button#SearchGlyphContainer",
  "controlStyles[31].styles[0]": "FontSize=32",
  "controlStyles[31].styles[1]": "Visibility=1",
  "controlStyles[32].target": "Cortana.UI.Views.CortanaRichSearchBox#SearchTextBox",
  "controlStyles[32].styles[0]": "FontSize=24",
  "controlStyles[32].styles[1]": "Foreground:=<SolidColorBrush Color=\"{ThemeResource TextFillColorPrimary}\" Opacity=\".85\"/>",
  "controlStyles[32].styles[2]": "FontFamily=Aptos",
  "controlStyles[32].styles[3]": "Opacity=.85",
  "controlStyles[32].styles[4]": "FontWeight=ExtraBold",
  "controlStyles[33].target": "Border#LayerBorder",
  "controlStyles[33].styles[0]": "Visibility=1",
  "controlStyles[34].target": "Windows.UI.Xaml.Controls.FontIcon#SearchBoxOnTaskbarSearchGlyph",
  "controlStyles[34].styles[0]": "Visibility=0",
  "controlStyles[34].styles[1]": "Margin=0",
  "controlStyles[34].styles[2]": "FontSize=32",
  "controlStyles[34].styles[3]": "Opacity=.85",
  "controlStyles[35].target": "Cortana.UI.Views.RichSearchBoxControl#SearchBoxControl",
  "controlStyles[35].styles[0]": "Margin=31,31,17,17",
  "controlStyles[36].target": "Grid#WebViewGrid",
  "controlStyles[36].styles[0]": "Margin=-13,0,-10,15",
  "controlStyles[37].target": "TextBlock#StatusMessage",
  "controlStyles[37].styles[0]": "Visibility=1",
  "controlStyles[38].target": "Border#StartDropShadow",
  "controlStyles[38].styles[0]": "CornerRadius=12",
  "controlStyles[38].styles[1]": "Margin=-1",
  "controlStyles[39].target": "Border#StartDropShadowDismissTarget",
  "controlStyles[39].styles[0]": "CornerRadius=12",
  "controlStyles[40].target": "Windows.UI.Xaml.Controls.FlyoutPresenter[1]",
  "controlStyles[40].styles[0]": "Margin=-250,50,0,0",
  "controlStyles[41].target": "Windows.UI.Xaml.Controls.FlyoutPresenter",
  "controlStyles[41].styles[0]": "Margin=-250,0,0,0",
  "controlStyles[42].target": "StartMenu.SearchBoxToggleButton > Grid > FontIcon#SearchGlyph",
  "controlStyles[42].styles[0]": "Margin=0,-3,0,0",
  "controlStyles[42].styles[1]": "FontSize=25",
  "controlStyles[42].styles[2]": "Foreground:=<SolidColorBrush Color=\"{ThemeResource FocusStrokeColorOuter}\" Opacity=\".85\"/>",
  "controlStyles[43].target": "StartMenu.ExpandedFolderList > Grid#Root > Border",
  "controlStyles[43].styles[0]": "Height=420",
  "controlStyles[44].target": "TextBox#ExpandedFolderNameTextBox",
  "controlStyles[44].styles[0]": "Margin=-15,-15,15,20",
  "controlStyles[45].target": "Windows.UI.Xaml.Controls.GridView#FolderList > Border",
  "controlStyles[45].styles[0]": "Margin=0,0,0,-60",
  "controlStyles[46].target": "StartDocked.NavigationPaneView#NavigationPane > Grid > StartDocked.AppListView",
  "controlStyles[46].styles[0]": "Margin=0,0,-36,0",
  "controlStyles[47].target": "Image#SearchIconOn",
  "controlStyles[47].styles[0]": "Visibility=1",
  "controlStyles[48].target": "Grid#TopLevelSuggestionsContainer",
  "controlStyles[48].styles[0]": "Visibility=1",
  "controlStyles[49].target": "Image#SearchIconOff",
  "controlStyles[49].styles[0]": "Visibility=1",
  "controlStyles[50].target": "Grid#ContentBorder > Border#BackgroundBorder",
  "controlStyles[50].styles[0]": "CornerRadius=99",
  "controlStyles[50].styles[1]": "Height=38",
  "controlStyles[50].styles[2]": "Width=38",
  "controlStyles[51].target": "Grid#ContentBorder > ContentPresenter > FontIcon",
  "controlStyles[51].styles[0]": "Opacity=.85",
  "controlStyles[52].target": "StartDocked.AppListView#NavigationPanePlacesListView",
  "controlStyles[52].styles[0]": "Padding=2,0,6,0",
  "controlStyles[53].target": "StartDocked.AppListView#NavigationPanePlacesListView > Border > ScrollViewer > Border#Root > Grid > ScrollContentPresenter > ItemsPresenter > ItemsStackPanel > ListViewItem",
  "controlStyles[53].styles[0]": "Margin=-2,0,0,0",
  "controlStyles[54].target": "StartDocked.AppListView#NavigationPanePlacesListView",
  "controlStyles[54].styles[0]": "Margin=0,0,-46,0",
  "controlStyles[55].target": "Windows.UI.Xaml.Controls.Primitives.ScrollBar",
  "controlStyles[55].styles[0]": "Transform3D:=<CompositeTransform3D TranslateX=\"-10\" TranslateY=\"3\"/>",
  "controlStyles[56].target": "Grid#ContentBorder > Border#BorderBackground",
  "controlStyles[56].styles[0]": "Margin=1,0,-1,0",
  "controlStyles[57].target": "StackPanel#RootPanel > Button#Header > Border#Border",
  "controlStyles[57].styles[0]": "Margin=0,0,-1,0",
  "controlStyles[58].styles[0]": "Visibility=Collapsed",
  "controlStyles[58].target": "Rectangle#TextCaret",
  "controlStyles[59].target": "Grid#RootGrid@SearchBoxLocationStates ",
  "controlStyles[59].styles[0]": "Margin@SearchBoxOnBottomWithoutQFMargin=-32,10,32,-10",
  "controlStyles[60].styles[0]": "FontSize=16",
  "controlStyles[60].target": "Grid#RootGrid@SearchBoxLocationStates > Cortana.UI.Views.CortanaRichSearchBox > Grid > TextBlock#PlaceholderTextContentPresenter",
  "controlStyles[20].styles[0]": "RenderTransform:=<TranslateTransform X=\"512\" Y=\"-685\" />",
  "controlStyles[55].styles[1]": "Height=615",
  "controlStyles[61].target": "Grid#MainMenu",
  "controlStyles[61].styles[0]": "Width=630",
  "controlStyles[62].target": "Grid#FrameRoot",
  "controlStyles[62].styles[0]": "MaxHeight=775",
  "controlStyles[63].target": "ListView#ZoomedOutListView",
  "controlStyles[63].styles[0]": "Margin=0,-150,0,0",
  "controlStyles[64].target": "GridView#AllAppsGrid > Border > ScrollViewer > Border#Root > Grid > ScrollContentPresenter > ItemsPresenter > ItemsWrapGrid",
  "controlStyles[64].styles[0]": "RenderTransform:=<TranslateTransform X=\"-8\" />",
  "controlStyles[64].styles[1]": "Margin=0",
  "controlStyles[64].styles[2]": "Width=540",
  "controlStyles[65].target": "StartMenu.CategoryControl",
  "controlStyles[65].styles[0]": "Margin=0,0,-8,-8",
  "controlStyles[65].styles[1]": "RenderTransform:=<TranslateTransform X=\"14\" />",
  "controlStyles[66].target": "Microsoft.UI.Xaml.Controls.DropDownButton > Grid > ContentPresenter > TextBlock",
  "controlStyles[66].styles[0]": "FontFamily=Aptos",
  "controlStyles[66].styles[1]": "FontSize=16",
  "controlStyles[67].target": "TextBlock#ShowMorePinnedButtonText",
  "controlStyles[67].styles[0]": "FontFamily=Aptos",
  "controlStyles[67].styles[1]": "FontSize=16",
  "controlStyles[68].styles[0]": "Visibility=Collapsed",
  "controlStyles[68].target": "Grid#TopLevelSuggestionsRoot",
  "controlStyles[69].target": "Windows.UI.Xaml.Controls.Primitives.ToggleButton",
  "controlStyles[69].styles[0]": "Margin=-80,0,80,0"
}
```

### 4. Taskbar Labels for Windows 11 (version 1.1.5, Oct 3, 2023)
```json
{"taskbarItemWidth":160,"runningIndicatorStyle":"centerDynamic","progressIndicatorStyle":"fullWidth","fontSize":13,"leftAndRightPaddingSize":6,"spaceBetweenIconAndLabel":8,"labelForSingleItem":"%name%","labelForMultipleItems":"[%amount%] %name%"}
```

### 5. Taskbar tray icon spacing and grid
```json
{"notificationIconWidth":23,"notificationIconRows":1,"overflowIconWidth":23,"overflowIconsPerRow":3}
```

### 6. Windows 11 Notification Center Styler
```json
{"controlStyles[0].target":"Grid#NotificationCenterGrid","controlStyles[0].styles[0]":"Background:=$CommonBgBrush","controlStyles[0].styles[1]":"BorderThickness=0,0,0,0","controlStyles[0].styles[2]":"CornerRadius=15","controlStyles[1].target":"Grid#CalendarCenterGrid","controlStyles[1].styles[0]":"Background:=$CommonBgBrush","controlStyles[1].styles[1]":"BorderThickness=0,0,0,0","controlStyles[1].styles[2]":"CornerRadius=15","controlStyles[2].target":"ScrollViewer#CalendarControlScrollViewer","controlStyles[2].styles[0]":"Background=Transparent","controlStyles[3].target":"Border#CalendarHeaderMinimizedOverlay","controlStyles[3].styles[0]":"Background=Transparent","controlStyles[4].target":"ActionCenter.FocusSessionControl#FocusSessionControl > Grid#FocusGrid","controlStyles[4].styles[0]":"Background=Transparent","controlStyles[5].target":"MenuFlyoutPresenter > Border","controlStyles[5].styles[0]":"Background:=<WindhawkBlur BlurAmount=\"25\" TintColor=\"#00000000\"/>","controlStyles[5].styles[1]":"BorderThickness=0,0,0,0","controlStyles[5].styles[2]":"CornerRadius=15","controlStyles[5].styles[3]":"Padding=2,4,2,4","controlStyles[6].target":"Border#JumpListRestyledAcrylic","controlStyles[6].styles[0]":"Background:=$CommonBgBrush","controlStyles[6].styles[1]":"BorderThickness=0,0,0,0","controlStyles[6].styles[2]":"CornerRadius=15","controlStyles[6].styles[3]":"Margin=-2,-2,-2,-2","controlStyles[7].target":"Grid#ControlCenterRegion","controlStyles[7].styles[0]":"Background:=$CommonBgBrush","controlStyles[7].styles[1]":"BorderThickness=0,0,0,0","controlStyles[7].styles[2]":"CornerRadius=15","controlStyles[8].target":"Windows.UI.Xaml.Controls.Grid#L1Grid > Border","controlStyles[8].styles[0]":"Background:=<SolidColorBrush Color=\"Transparent\"/>","controlStyles[9].target":"Windows.UI.Xaml.Controls.Grid#MediaTransportControlsRegion","controlStyles[9].styles[0]":"Background:=$CommonBgBrush","controlStyles[9].styles[1]":"BorderThickness=0,0,0,0","controlStyles[9].styles[2]":"CornerRadius=15","controlStyles[10].target":"Grid#MediaTransportControlsRoot","controlStyles[10].styles[0]":"Background:=<SolidColorBrush Color=\"Transparent\"/>","controlStyles[11].target":"ContentPresenter#PageContent","controlStyles[11].styles[0]":"Background:=<SolidColorBrush Color=\"Transparent\"/>","controlStyles[12].target":"ContentPresenter#PageContent > Grid > Border","controlStyles[12].styles[0]":"Background:=<SolidColorBrush Color=\"Transparent\"/>","controlStyles[13].target":"QuickActions.ControlCenter.AccessibleWindow#PageWindow > ContentPresenter > Grid#FullScreenPageRoot","controlStyles[13].styles[0]":"Background:=<SolidColorBrush Color=\"Transparent\"/>","controlStyles[14].target":"QuickActions.ControlCenter.AccessibleWindow#PageWindow > ContentPresenter > Grid#FullScreenPageRoot > ContentPresenter#PageHeader","controlStyles[14].styles[0]":"Background:=<SolidColorBrush Color=\"Transparent\"/>","controlStyles[15].target":"ScrollViewer#ListContent","controlStyles[15].styles[0]":"Background:=<SolidColorBrush Color=\"Transparent\"/>","controlStyles[16].target":"ActionCenter.FlexibleToastView#FlexibleNormalToastView","controlStyles[16].styles[0]":"Background:=<SolidColorBrush Color=\"Transparent\"/>","controlStyles[17].target":"Border#ToastBackgroundBorder2","controlStyles[17].styles[0]":"Background:=$CommonBgBrush","controlStyles[17].styles[1]":"BorderThickness=0,0,0,0","controlStyles[17].styles[2]":"CornerRadius=15","controlStyles[18].target":"JumpViewUI.SystemItemListViewItem > Grid#LayoutRoot > Border#BackgroundBorder","controlStyles[18].styles[0]":"FocusVisualPrimaryThickness=0,0,0,0","controlStyles[18].styles[1]":"FocusVisualSecondaryThickness=0,0,0,0","controlStyles[19].target":"JumpViewUI.JumpListListViewItem > Grid#LayoutRoot > Border#BackgroundBorder","controlStyles[19].styles[0]":"FocusVisualPrimaryThickness=0,0,0,0","controlStyles[20].target":"ActionCenter.FlexibleItemView","controlStyles[20].styles[0]":"CornerRadius=15","controlStyles[21].target":"ControlCenter.MediaTransportControls#MediaTransportControls > Windows.UI.Xaml.Controls.Grid#MediaTransportControlsRegion","controlStyles[21].styles[0]":"Height=470","controlStyles[22].target":"Windows.UI.Xaml.Controls.Grid#AlbumTextAndArtContainer","controlStyles[22].styles[0]":"Height=350","controlStyles[23].target":"Windows.UI.Xaml.Controls.Grid#ThumbnailImage","controlStyles[23].styles[0]":"Width=300","controlStyles[23].styles[1]":"Height=300","controlStyles[23].styles[2]":"HorizontalAlignment=Center","controlStyles[23].styles[3]":"VerticalAlignment=Top","controlStyles[23].styles[4]":"Grid.Column=1","controlStyles[24].target":"Windows.UI.Xaml.Controls.Grid#ThumbnailImage > Windows.UI.Xaml.Controls.Border","controlStyles[24].styles[0]":"CornerRadius=10","controlStyles[25].target":"Windows.UI.Xaml.Controls.StackPanel#PrimaryAndSecondaryTextContainer","controlStyles[25].styles[0]":"VerticalAlignment=Bottom","controlStyles[25].styles[1]":"Grid.Column=0","controlStyles[26].target":"Windows.UI.Xaml.Controls.StackPanel#PrimaryAndSecondaryTextContainer > Windows.UI.Xaml.Controls.TextBlock#TitleText","controlStyles[26].styles[0]":"TextAlignment=Center","controlStyles[27].target":"Windows.UI.Xaml.Controls.StackPanel#PrimaryAndSecondaryTextContainer > Windows.UI.Xaml.Controls.TextBlock#SubtitleText","controlStyles[27].styles[0]":"TextAlignment=Center","theme":"","resourceVariables[0].variableKey":"","resourceVariables[0].value":"","styleConstants[0]":"CommonBgBrush=<AcrylicBrush TintColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" FallbackColor=\"{ThemeResource CardStrokeColorDefaultSolid}\" TintOpacity=\"0\" TintLuminosityOpacity=\".85\" Opacity=\"1\"/>"}
```

</details>


## 2. Extra Animated
<details>
<summary>Contents</summary>

![](https://raw.githubusercontent.com/zzsmkr/zazafiles/refs/heads/main/Previews/image.png)

### 1. Windows 11 Taskbar Styler
```json
{"controlStyles[0].target":"TextBlock#DateInnerTextBlock","controlStyles[0].styles[0]":"Visibility=Collapsed","controlStyles[1].target":"TextBlock#TimeInnerTextBlock","controlStyles[1].styles[0]":"FontSize=13","controlStyles[2].target":"Taskbar.TaskbarFrame#TaskbarFrame > Grid#RootGrid","controlStyles[2].styles[0]":"Padding=0,-1,0,-1","controlStyles[3].target":"Grid#SystemTrayFrameGrid","controlStyles[3].styles[0]":"Margin=-55,0,-10,0","controlStyles[3].styles[1]":"Padding=0,-1,0,-1"}
```
### 2. Taskbar height and icon size
```json
{"TaskbarHeight":38,"IconSize":24,"TaskbarButtonWidth":35,"IconSizeSmall":16,"TaskbarButtonWidthSmall":32}
```
### 3. Windows 11 Start Menu Styler
```json
{"controlStyles[0].target":"Border#ContentBorder@CommonStates > Grid > Border#BackgroundBorder","controlStyles[0].styles[0]":"BorderThickness=2","controlStyles[0].styles[1]":"BorderBrush@PointerOver:=$borderColor","controlStyles[0].styles[2]":"BorderBrush@Pressed:=$borderColor","controlStyles[1].target":"Button > Grid@CommonStates > Border#BackgroundBorder","controlStyles[1].styles[0]":"BorderThickness=2","controlStyles[1].styles[1]":"BorderBrush@PointerOver:=$borderColor","controlStyles[1].styles[2]":"BorderBrush@Pressed:=$borderColor","controlStyles[1].styles[3]":"BackgroundSizing=InnerBorderEdge","controlStyles[2].target":"StartMenu.CategoryControl > Grid > Border","controlStyles[2].styles[0]":"BorderThickness=2","controlStyles[2].styles[1]":"BorderBrush:=$borderColor","controlStyles[2].styles[2]":"BackgroundSizing=InnerBorderEdge","controlStyles[2].styles[3]":"Background:=<SolidColorBrush Color=\"{ThemeResource ControlFillColorDefault}\" />","controlStyles[2].styles[4]":"Opacity=0.8","controlStyles[3].target":"Grid#LayoutRoot","controlStyles[3].styles[0]":"BackgroundTransition:=<BrushTransition Duration=\"0:0:0.083\" />","controlStyles[4].target":"Border#BackgroundBorder","controlStyles[4].styles[0]":"BackgroundTransition:=<BrushTransition Duration=\"0:0:0.083\" />","controlStyles[5].target":"Button#Header > Border@CommonStates","controlStyles[5].styles[0]":"BorderThickness=2","controlStyles[5].styles[1]":"BorderBrush@PointerOver:=$borderColor","controlStyles[5].styles[2]":"BorderBrush@Pressed:=$borderColor","controlStyles[5].styles[3]":"BackgroundSizing=InnerBorderEdge","controlStyles[6].target":"ListViewItem > Grid@CommonStates > Border#BorderBackground","controlStyles[6].styles[0]":"BorderThickness=2","controlStyles[6].styles[1]":"BorderBrush@PointerOver:=$borderColor","controlStyles[6].styles[2]":"BorderBrush@Pressed:=$borderColor","controlStyles[6].styles[3]":"BackgroundSizing=InnerBorderEdge","controlStyles[7].target":"StartMenu.SearchBoxToggleButton > Grid@CommonStates > Border#BorderElement","controlStyles[7].styles[0]":"CornerRadius=16","controlStyles[7].styles[1]":"BorderThickness=1","controlStyles[7].styles[2]":"BorderBrush:=$borderColor","controlStyles[7].styles[3]":"Background@Checked:=$backgroundNormal","controlStyles[7].styles[4]":"Background@CheckedPointerOver:=$backgroundHover","controlStyles[7].styles[5]":"Background@CheckedPressed:=$backgroundPressed","controlStyles[7].styles[6]":"BackgroundTransition:=<BrushTransition Duration=\"0:0:0.083\" />","controlStyles[8].target":"Button#HideMoreSuggestionsButton > Grid@CommonStates > Border#BackgroundBorder","controlStyles[8].styles[0]":"Background@Normal:=$backgroundNormal","controlStyles[8].styles[1]":"BorderBrush@Normal:=$borderColor","controlStyles[8].styles[2]":"BorderBrush@PointerOver:=$borderColor","controlStyles[8].styles[3]":"BorderBrush@Pressed:=$borderColor","controlStyles[8].styles[4]":"Background@PointerOver:=$backgroundHover","controlStyles[8].styles[5]":"Background@Pressed:=$backgroundPressed","controlStyles[8].styles[6]":"BorderThickness=1","controlStyles[8].styles[7]":"Margin=2","controlStyles[9].target":"Button#ShowMoreSuggestionsButton > Grid@CommonStates > Border#BackgroundBorder","controlStyles[9].styles[0]":"Background@Normal:=$backgroundNormal","controlStyles[9].styles[1]":"BorderBrush@Normal:=$borderColor","controlStyles[9].styles[2]":"BorderBrush@PointerOver:=$borderColor","controlStyles[9].styles[3]":"BorderBrush@Pressed:=$borderColor","controlStyles[9].styles[4]":"Background@PointerOver:=$backgroundHover","controlStyles[9].styles[5]":"Background@Pressed:=$backgroundPressed","controlStyles[9].styles[6]":"BorderThickness=1","controlStyles[9].styles[7]":"Margin=2","controlStyles[10].target":"StartMenu.FolderModal > Grid#Root > Border","controlStyles[10].styles[0]":"BorderThickness=1","controlStyles[10].styles[1]":"BorderBrush:=$borderColor","controlStyles[11].target":"MenuFlyoutPresenter > Border","controlStyles[11].styles[0]":"BorderThickness=1","controlStyles[11].styles[1]":"BorderBrush:=$borderColor","controlStyles[12].target":"Border#ContentBorder@CommonStates > Grid#DroppedFlickerWorkaroundWrapper > ContentPresenter#ContentPresenter > ContentControl > Grid#RootGrid > Border#LogoBackgroundPlate > Image#AllAppsItemLogo","controlStyles[12].styles[0]":"RenderTransform@Pressed:=<ScaleTransform ScaleX=\"0.8\" ScaleY=\"0.8\" />","controlStyles[12].styles[1]":"RenderTransformOrigin=0.5,0.5","controlStyles[13].target":"StartDocked.NavigationPaneButton > Grid@CommonStates > Border#BackgroundBorder","controlStyles[13].styles[0]":"BorderThickness=1","controlStyles[13].styles[1]":"BorderBrush@PointerOver:=$borderColor","controlStyles[13].styles[2]":"BorderBrush@Pressed:=$borderColor","controlStyles[13].styles[3]":"BackgroundSizing=InnerBorderEdge","controlStyles[14].target":"StartDocked.AppListViewItem > Grid@CommonStates > Border#BackgroundBorder","controlStyles[14].styles[0]":"BorderThickness=1","controlStyles[14].styles[1]":"BorderBrush@PointerOver:=$borderColor","controlStyles[14].styles[2]":"BorderBrush@Pressed:=$borderColor","controlStyles[14].styles[3]":"BackgroundSizing=InnerBorderEdge","controlStyles[15].target":"Microsoft.UI.Xaml.Controls.DropDownButton > Grid@CommonStates","controlStyles[15].styles[0]":"Background@PointerOver:=$backgroundHover","controlStyles[15].styles[1]":"Background@Pressed:=$backgroundPressed","controlStyles[15].styles[2]":"BorderBrush@PointerOver:=$borderColor","controlStyles[15].styles[3]":"BorderBrush@Pressed:=$borderColor","controlStyles[15].styles[4]":"BackgroundSizing=InnerBorderEdge","controlStyles[15].styles[5]":"Background@Normal:=$backgroundNormal","controlStyles[15].styles[6]":"BorderBrush@Normal:=$borderColor","controlStyles[15].styles[7]":"Padding=9,3,7,4","controlStyles[16].target":"Border#ContentBorder@CommonStates > Grid#DroppedFlickerWorkaroundWrapper > ContentPresenter#ContentPresenter > ContentControl > Grid#RootGrid > Grid#LogoContainer > Image#AllAppsTileLogo","controlStyles[16].styles[0]":"RenderTransform@Pressed:=<ScaleTransform ScaleX=\"0.8\" ScaleY=\"0.8\" />","controlStyles[16].styles[1]":"RenderTransformOrigin=0.5,0.5","controlStyles[17].target":"Border#ContentBorder@CommonStates > Grid#DroppedFlickerWorkaroundWrapper > ContentPresenter > Grid > Grid#LogoContainer > Grid","controlStyles[17].styles[0]":"RenderTransform@Pressed:=<ScaleTransform ScaleX=\"0.8\" ScaleY=\"0.8\" />","controlStyles[17].styles[1]":"RenderTransformOrigin=0.5,0.5","controlStyles[18].target":"Grid#ContentBorder@CommonStates > Grid#DroppedFlickerWorkaroundWrapper > ContentPresenter > Grid > Grid#LogoContainer > Grid","controlStyles[18].styles[0]":"RenderTransform@Pressed:=<ScaleTransform ScaleX=\"0.8\" ScaleY=\"0.8\" />","controlStyles[18].styles[1]":"RenderTransformOrigin=0.5,0.5","controlStyles[19].target":"ScrollViewer#MenuFlyoutPresenterScrollViewer > Border > Grid > ScrollContentPresenter > ItemsPresenter > StackPanel","controlStyles[19].styles[0]":"ChildrenTransitions:=<TransitionCollection><EntranceThemeTransition IsStaggeringEnabled=\"False\" FromHorizontalOffset=\"-25\" FromVerticalOffset=\"0\" /></TransitionCollection>","controlStyles[20].target":"FlyoutPresenter > Border > ScrollViewer > Border > Grid > ScrollContentPresenter > ContentPresenter > Border","controlStyles[20].styles[0]":"BorderBrush:=$borderColor","controlStyles[20].styles[1]":"BorderThickness=1","controlStyles[21].target":"Button > ContentPresenter#ContentPresenter@CommonStates","controlStyles[21].styles[0]":"Background@PointerOver:=$backgroundHover","controlStyles[21].styles[1]":"Background@Pressed:=$backgroundPressed","controlStyles[21].styles[2]":"BorderBrush@PointerOver:=$borderColor","controlStyles[21].styles[3]":"BorderBrush@Pressed:=$borderColor","controlStyles[21].styles[4]":"BorderThickness=1","controlStyles[21].styles[5]":"Background@Normal=Transparent","controlStyles[22].target":"Grid@SearchBoxInputStates > Border#TaskbarSearchBackground","controlStyles[22].styles[0]":"CornerRadius=16","controlStyles[22].styles[1]":"Background@ActiveInput:=$backgroundNormal","controlStyles[22].styles[2]":"BorderBrush:=$borderColor","controlStyles[22].styles[3]":"BorderThickness=1","controlStyles[22].styles[4]":"Background@SearchBoxHover:=$backgroundHover","controlStyles[22].styles[5]":"Background@NoFocus:=$backgroundNormal","controlStyles[22].styles[6]":"BackgroundTransition:=<BrushTransition Duration=\"0:0:0.083\" />","controlStyles[23].target":"Border@CommonStates > Grid#DroppedFlickerWorkaroundWrapper > ContentPresenter > Grid > Grid#LogoContainer > Image","controlStyles[23].styles[0]":"RenderTransform@Pressed:=<ScaleTransform ScaleX=\"0.8\" ScaleY=\"0.8\" />","controlStyles[23].styles[1]":"RenderTransformOrigin=0.5,0.5","controlStyles[24].target":"Grid#ContentBorder@CommonStates > ContentPresenter > Grid > Grid#LogoContainer > Grid","controlStyles[24].styles[0]":"RenderTransform@Pressed:=<ScaleTransform ScaleX=\"0.8\" ScaleY=\"0.8\" />","controlStyles[24].styles[1]":"RenderTransformOrigin=0.5,0.5","webContentStyles[0].target":"*","webContentStyles[0].styles[0]":"transition: background-color 0.083s ease-in-out !important","styleConstants[0]":"borderColor=<LinearGradientBrush x:Key=\"ShellTaskbarItemGradientStrokeColorSecondaryBrush\" MappingMode=\"Absolute\" StartPoint=\"0,0\" EndPoint=\"0,3\"><LinearGradientBrush.GradientStops><GradientStop Offset=\"0.33\" Color=\"#1AFFFFFF\" /><GradientStop Offset=\"1\" Color=\"#0FFFFFFF\" /></LinearGradientBrush.GradientStops></LinearGradientBrush>","styleConstants[1]":"backgroundNormal=<SolidColorBrush Color=\"{ThemeResource ControlFillColorDefault}\" />","styleConstants[2]":"backgroundHover=<SolidColorBrush Color=\"{ThemeResource ControlFillColorSecondary}\" />","styleConstants[3]":"backgroundPressed=<SolidColorBrush Color=\"{ThemeResource ControlFillColorTertiary}\" />","controlStyles[25].target":"Grid#MainMenu","controlStyles[25].styles[0]":"Width=776","controlStyles[26].target":"Grid#FrameRoot","controlStyles[26].styles[0]":"MaxHeight=750","controlStyles[27].target":"StartMenu.CategoryControl","controlStyles[27].styles[0]":"Margin=0,0,-12,-8","controlStyles[28].target":"StartMenu.StartHome","controlStyles[28].styles[0]":"Margin=-11,0,-11,0","controlStyles[29].target":"StartMenu.PinnedList#StartMenuPinnedList","controlStyles[29].styles[0]":"Margin=30,0,30,-20","controlStyles[30].target":"TextBlock#PinnedListHeaderText","controlStyles[30].styles[0]":"Margin=60,-15,0,10"}
```

### 4. Taskbar Labels for Windows 11 1.1.5
```json
{"taskbarItemWidth":160,"runningIndicatorStyle":"centerDynamic","progressIndicatorStyle":"fullWidth","fontSize":13,"leftAndRightPaddingSize":4,"spaceBetweenIconAndLabel":8,"labelForSingleItem":"%name%","labelForMultipleItems":"[%amount%] %name%"}
```

### 5. Taskbar tray icon spacing and grid
```json
{"notificationIconWidth":23,"notificationIconRows":1,"overflowIconWidth":23,"overflowIconsPerRow":3}
```

### 6. Taskbar Dock Animation
```json
{"MaxScale":105,"EffectRadius":50,"SpacingFactor":0,"BounceDelay":10000}
```
</details>


## 3. Windows Glass
<details>
<summary>Contents</summary>

![](https://raw.githubusercontent.com/zzsmkr/zazafiles/refs/heads/main/Previews/image.png)
### 1. Windows 11 Taskbar Styler
```json
{"controlStyles[0].target":"Taskbar.TaskbarFrame#TaskbarFrame","controlStyles[0].styles[1]":"HorizontalAlignment=Auto","controlStyles[0].styles[2]":"Width=Auto","controlStyles[0].styles[0]":"MaxWidth:=1300","controlStyles[0].styles[3]":"MinWidth:=500","controlStyles[1].target":"Taskbar.TaskbarFrame#TaskbarFrame > Grid#RootGrid","controlStyles[1].styles[0]":"Margin=30,0,30,5","controlStyles[1].styles[1]":"BorderThickness=$BorderThickness","controlStyles[1].styles[2]":"BorderBrush:=$BorderBrush","controlStyles[1].styles[3]":"CornerRadius=$CornerRadius","controlStyles[1].styles[4]":"Background:=Transparent","controlStyles[2].target":"Rectangle#BackgroundFill","controlStyles[2].styles[0]":"Visibility=Visible","controlStyles[2].styles[1]":"Fill:=$Background","controlStyles[3].target":"Rectangle#BackgroundStroke","controlStyles[3].styles[0]":"Visibility=Collapsed","controlStyles[4].target":"Taskbar.AugmentedEntryPointButton#AugmentedEntryPointButton > Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel","controlStyles[4].styles[0]":"Margin=4","controlStyles[4].styles[1]":"Background:=$ElementBG","controlStyles[4].styles[2]":"CornerRadius=12","controlStyles[5].target":"Grid#SystemTrayFrameGrid","controlStyles[5].styles[0]":"Margin=-183,7,133,7","controlStyles[5].styles[1]":"RenderTransform:=<TranslateTransform X=\"-105\" Y=\"-2\"/>","controlStyles[5].styles[2]":"Padding=0,0,-12,0","controlStyles[5].styles[3]":"Background:=$ElementBG","controlStyles[5].styles[4]":"CornerRadius=12","controlStyles[6].target":"SystemTray.ChevronIconView","controlStyles[6].styles[0]":"Padding=$TrayPadding","controlStyles[6].styles[1]":"CornerRadius=10","controlStyles[7].target":"SystemTray.NotifyIconView#NotifyItemIcon","controlStyles[7].styles[0]":"Padding=$TrayPadding","controlStyles[7].styles[1]":"CornerRadius=10","controlStyles[8].target":"SystemTray.OmniButton","controlStyles[8].styles[0]":"Padding=$TrayPadding","controlStyles[8].styles[1]":"CornerRadius=10","controlStyles[9].target":"SystemTray.CopilotIcon","controlStyles[9].styles[0]":"Padding=$TrayPadding","controlStyles[10].target":"SystemTray.OmniButton#NotificationCenterButton > Grid > ContentPresenter > ItemsPresenter > StackPanel > ContentPresenter > systemtray:IconView#SystemTrayIcon > Grid","controlStyles[10].styles[0]":"Padding=$TrayPadding","controlStyles[11].target":"SystemTray.IconView#SystemTrayIcon > Grid#ContainerGrid > ContentPresenter#ContentPresenter > Grid#ContentGrid > SystemTray.TextIconContent > Grid#ContainerGrid","controlStyles[11].styles[0]":"Padding=10","controlStyles[11].styles[1]":"CornerRadius=10","controlStyles[12].target":"SystemTray.StackListView#IconStack > ItemsPresenter > StackPanel > ContentPresenter > SystemTray.IconView#SystemTrayIcon","controlStyles[12].styles[0]":"Padding=0","controlStyles[13].target":"SystemTray.Stack#ShowDesktopStack","controlStyles[13].styles[0]":"Visibility=Visible","controlStyles[14].target":"Taskbar.Gripper#GripperControl","controlStyles[14].styles[0]":"Width=Auto","controlStyles[14].styles[1]":"MinWidth=24","controlStyles[15].target":"Windows.UI.Xaml.Controls.Grid#AugmentedEntryPointContentGrid","controlStyles[15].styles[0]":"Margin=4,0,0,0","controlStyles[15].styles[1]":"HorizontalAlignment=Left","controlStyles[16].target":"TextBlock#TimeInnerTextBlock","controlStyles[16].styles[0]":"FontSize=13","controlStyles[16].styles[1]":"Margin=0","controlStyles[16].styles[2]":"Padding=0","controlStyles[16].styles[3]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"0\" />","controlStyles[17].target":"TextBlock#DateInnerTextBlock","controlStyles[17].styles[0]":"Visibility=Collapsed","controlStyles[17].styles[1]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"-9\" />","controlStyles[17].styles[2]":"FontSize=11","controlStyles[18].target":"Windows.UI.Xaml.Controls.Grid#ConfirmatorMainGrid","controlStyles[18].styles[0]":"CornerRadius=22","controlStyles[18].styles[1]":"BorderThickness=$BorderThickness","controlStyles[18].styles[2]":"BorderBrush:=$BorderBrush","controlStyles[18].styles[3]":"Background:=$Background","controlStyles[19].target":"TextBlock#SearchBoxTextBlock","controlStyles[19].styles[0]":"Text=Search This Precision","controlStyles[19].styles[1]":"FontSize=10","controlStyles[19].styles[2]":"FontFamily=vivo Sans EN VF","controlStyles[20].target":"SystemTray.OmniButton#NotificationCenterButton > Grid > ContentPresenter > ItemsPresenter > StackPanel > ContentPresenter > SystemTray.IconView#SystemTrayIcon > Grid > Grid > SystemTray.TextIconContent","controlStyles[20].styles[0]":"Visibility=Collapsed","controlStyles[21].target":"Windows.UI.Xaml.Controls.Button","controlStyles[21].styles[0]":"BorderThickness=$BorderThickness","controlStyles[22].target":"Windows.UI.Xaml.Controls.Border#OverflowFlyoutBackgroundBorder","controlStyles[22].styles[0]":"BorderThickness=$BorderThickness","controlStyles[22].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[22].styles[2]":"Background:=$Background","controlStyles[22].styles[3]":"CornerRadius=$CornerRadius","controlStyles[23].target":"WindowsInternal.ComposableShell.Experiences.Switcher.AltTab > Windows.UI.Xaml.Controls.Grid#ModalRootGrid > Border","controlStyles[23].styles[0]":"BorderThickness=$BorderThickness","controlStyles[23].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[23].styles[2]":"Background:=<AcrylicBrush TintColor=\"#10000020\"/>","controlStyles[23].styles[3]":"CornerRadius=20","controlStyles[24].target":"WindowsInternal.ComposableShell.Experiences.Switcher.VirtualDesktopBarElement#VirtualDesktopBar","controlStyles[24].styles[0]":"//RenderTransform:=<TranslateTransform X=\"0\" Y=\"60\" />","controlStyles[24].styles[1]":"CornerRadius=$CornerRadius","controlStyles[24].styles[2]":"Background:=$Background","controlStyles[25].target":"Windows.UI.Xaml.Controls.Border#BackgroundDimmingLayer","controlStyles[25].styles[0]":"Background:=$Background","controlStyles[26].target":"Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel > Windows.UI.Xaml.Controls.Border#BackgroundElement","controlStyles[26].styles[0]":"CornerRadius=10","controlStyles[27].target":"Taskbar.TaskListButton#TaskListButton","controlStyles[27].styles[0]":"CornerRadius=10","controlStyles[28].target":"Windows.UI.Xaml.Controls.Border#SnapBarBorder","controlStyles[28].styles[0]":"Background:=$Background","controlStyles[28].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[28].styles[2]":"CornerRadius=$CornerRadius","controlStyles[28].styles[3]":"BorderThickness=$BorderThickness","controlStyles[28].styles[4]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"10\" />","controlStyles[28].styles[5]":"Margin=0,0,0,-10","controlStyles[29].target":"Windows.UI.Xaml.Controls.Border#SnapPickerBorder","controlStyles[29].styles[0]":"Background:=$Background","controlStyles[29].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[29].styles[2]":"CornerRadius=$CornerRadius","controlStyles[29].styles[3]":"BorderThickness=$BorderThickness","controlStyles[30].target":"Windows.UI.Xaml.Controls.Border#SearchPillBackgroundElement","controlStyles[30].styles[0]":"BorderBrush:=$ElementBorderBrush","controlStyles[30].styles[1]":"CornerRadius=$ElementCornerRadius","controlStyles[30].styles[2]":"BorderThickness=$ElementBorderThickness","controlStyles[30].styles[3]":"Margin=0","controlStyles[31].target":"Taskbar.TaskbarExtensionElement","controlStyles[31].styles[0]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"0\" />","controlStyles[32].target":"Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel","controlStyles[32].styles[0]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"0\" />","controlStyles[33].target":"Windows.UI.Xaml.Controls.ToolTip > Windows.UI.Xaml.Controls.ContentPresenter#LayoutRoot","controlStyles[33].styles[0]":"Background:=$Background","controlStyles[33].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[33].styles[2]":"BorderThickness:=$BorderThickness","controlStyles[33].styles[3]":"CornerRadius=12","controlStyles[34].target":"SearchUx.SearchUI.SearchButtonControl","controlStyles[34].styles[0]":"MaxWidth=130","controlStyles[34].styles[1]":"Margin=-1,0,-1,0","controlStyles[35].target":"WindowsInternal.ComposableShell.Experiences.Switcher.VirtualDesktopBarElement > Windows.UI.Xaml.Controls.Grid#GridElement > Windows.UI.Xaml.Controls.Border#VirtualDesktopSwitcherBackground","controlStyles[35].styles[0]":"BorderBrush:=$BorderBrush","controlStyles[35].styles[1]":"BorderThickness=$BorderThickness","controlStyles[35].styles[2]":"CornerRadius=$CornerRadius","controlStyles[35].styles[3]":"Background=Transparent","controlStyles[36].target":"WindowsInternal.ComposableShell.Experiences.Switcher.SwitchItemListViewItem > Grid > Border","controlStyles[36].styles[0]":"Background:=<AcrylicBrush TintColor=\"#10000020\"/>","controlStyles[37].styles[0]":"Background:=<AcrylicBrush TintColor=\"#10000020\"/>","controlStyles[37].target":"Border#VirtualDesktopBarBackground","controlStyles[37].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[37].styles[2]":"BorderThickness=$BorderThickness","controlStyles[37].styles[3]":"CornerRadius=$CornerRadius","styleConstants[0]":"Background=<WindhawkBlur BlurAmount=\"15\" TintColor=\"#10808080\"/>","styleConstants[1]":"BorderBrush2=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"{ThemeResource SystemChromeHighColor}\" Offset=\"0.0\" /><GradientStop Color=\"{ThemeResource SystemChromeLowColor}\" Offset=\"0.25\" /><GradientStop Color=\"{ThemeResource SystemChromeHighColor}\" Offset=\"1\" /></LinearGradientBrush>","styleConstants[2]":"BorderThickness=0.3,1,0.3,0.3","styleConstants[3]":"CornerRadius=15","styleConstants[4]":"BorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"#50808080\" Offset=\"0.0\" /><GradientStop Color=\"#50404040\" Offset=\"0.25\" /><GradientStop Color=\"#50808080\" Offset=\"1\" /></LinearGradientBrush>","styleConstants[5]":"Background2=<AcrylicBrush TintColor=\"{ThemeResource SystemChromeAltHighColor}\" TintOpacity=\"0.3\" FallbackColor=\"{ThemeResource SystemChromeAltHighColor}\" />","styleConstants[6]":"TrayPadding=2","styleConstants[7]":"ElementBG=<SolidColorBrush Color=\"{ThemeResource SystemChromeAltHighColor}\" Opacity=\"0.3\" />","styleConstants[8]":"ElementBorderThickness=0.3,0.3,0.3,1","styleConstants[9]":"ElementBorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"#50808080\" Offset=\"1\" /><GradientStop Color=\"#50606060\" Offset=\"0.15\" /></LinearGradientBrush>","styleConstants[10]":"ElementCornerRadius=12","controlStyles[1].styles[5]":"Padding=0,-3,0,-2"}
```

## 2. Windows 11 Start Menu Styler
```json
{"controlStyles[0].target":"Border#AcrylicOverlay","controlStyles[0].styles[0]":"Margin=0","controlStyles[0].styles[1]":"BorderThickness=0","controlStyles[0].styles[2]":"CornerRadius=10","controlStyles[0].styles[3]":"Visibility=Collapsed","controlStyles[1].target":"Border#AcrylicBorder","controlStyles[1].styles[0]":"Background:=$Glass","controlStyles[1].styles[1]":"CornerRadius=$CornerRadius","controlStyles[1].styles[2]":"BorderThickness=$BorderThickness","controlStyles[1].styles[3]":"BorderBrush:=$BorderBrush","controlStyles[2].target":"StartMenu.SearchBoxToggleButton#SearchBoxToggleButton","controlStyles[2].styles[0]":"Visibility=Visible","controlStyles[2].styles[1]":"Width=500","controlStyles[2].styles[2]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"30\"/>","controlStyles[2].styles[3]":"Margin=0,-10,0,20","controlStyles[3].target":"Windows.UI.Xaml.Controls.Border#AppBorder","controlStyles[3].styles[0]":"Background:=$Glass","controlStyles[3].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[3].styles[2]":"BorderThickness=$BorderThickness","controlStyles[4].target":"StartMenu.SearchBoxToggleButton#SearchBoxToggleButton > Windows.UI.Xaml.Controls.Grid > Windows.UI.Xaml.Controls.Border#BorderElement","controlStyles[4].styles[0]":"BorderThickness=$BorderThickness","controlStyles[4].styles[1]":"CornerRadius=$CornerRadius","controlStyles[5].target":"Windows.UI.Xaml.Controls.Border#AppBorder","controlStyles[5].styles[0]":"Background:=$Glass","controlStyles[5].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[5].styles[2]":"BorderThickness=$BorderThickness","controlStyles[5].styles[3]":"CornerRadius=$CornerRadius","controlStyles[6].target":"Windows.UI.Xaml.Controls.Border#BorderElement","controlStyles[6].styles[0]":"Background=Transparent","controlStyles[6].styles[1]":"BorderThickness=$BorderThickness","controlStyles[7].target":"StartMenu.CategoryControl > Windows.UI.Xaml.Controls.Grid#RootGrid > Windows.UI.Xaml.Controls.Border ","controlStyles[7].styles[0]":"BorderThickness=$ElementBorderThickness","controlStyles[7].styles[1]":"CornerRadius=$ElementCornerRadius","controlStyles[7].styles[2]":"BorderBrush:=$ElementBorderBrush","controlStyles[7].styles[3]":"Background:=$ElementBG","controlStyles[8].target":"Windows.UI.Xaml.Controls.Border#BorderUnderline","controlStyles[8].styles[0]":"Visibility=Visible","controlStyles[9].target":"Windows.UI.Xaml.Controls.Grid#WidgetFrameGrid","controlStyles[9].styles[0]":"Background:=$Glass","controlStyles[9].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[9].styles[2]":"BorderThickness=$BorderThickness","controlStyles[9].styles[3]":"CornerRadius=$CornerRadius","controlStyles[10].target":"Windows.UI.Xaml.Controls.Grid#WidgetCanvasPanel","controlStyles[10].styles[0]":"HorizontalAlignment=Center","controlStyles[10].styles[1]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"50\" />","controlStyles[11].target":"Windows.UI.Xaml.Controls.Grid#MediaTransportControls","controlStyles[11].styles[0]":"Background:=$Glass","controlStyles[11].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[11].styles[2]":"BorderThickness=$BorderThickness","controlStyles[11].styles[3]":"CornerRadius=$CornerRadius","controlStyles[12].target":"Windows.UI.Xaml.Controls.Grid#MediaControlsContainer","controlStyles[12].styles[0]":"Visibility=Visible","controlStyles[12].styles[1]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"0\" />","controlStyles[12].styles[2]":"Margin=0,-800,0,800","controlStyles[12].styles[3]":"CornerRadius=$CornerRadius","controlStyles[12].styles[4]":"VerticalAlignment=Center","controlStyles[12].styles[5]":"HorizontalAlignment=Center","controlStyles[13].target":"Windows.UI.Xaml.Controls.Border#BorderElement","controlStyles[13].styles[0]":"CornerRadius=$CornerRadius","controlStyles[14].target":"Windows.UI.Xaml.Controls.Primitives.ToggleButton#ShowHideCompanion","controlStyles[14].styles[0]":"RenderTransform:=<TranslateTransform X=\"-120\" />","controlStyles[14].styles[1]":"Visibility=Collapsed","controlStyles[15].target":"Windows.UI.Xaml.Controls.Grid#CompanionRoot > Windows.UI.Xaml.Controls.Border#AcrylicOverlay","controlStyles[15].styles[0]":"BorderThickness=0","controlStyles[15].styles[1]":"Visibility=Collapsed","controlStyles[16].target":"Windows.UI.Xaml.Controls.Grid#Root > Windows.UI.Xaml.Controls.Border","controlStyles[16].styles[0]":"BorderBrush:=$BorderBrush","controlStyles[16].styles[1]":"Background:=$Glass","controlStyles[16].styles[2]":"BorderThickness=$BorderThickness","controlStyles[16].styles[3]":"CornerRadius=$CornerRadius","controlStyles[17].target":"Windows.UI.Xaml.Controls.Border#StartDropShadow","controlStyles[17].styles[0]":"CornerRadius=$CornerRadius","controlStyles[18].target":"Windows.UI.Xaml.Controls.Border#RightCompanionDropShadow","controlStyles[18].styles[0]":"CornerRadius=$CornerRadius","controlStyles[18].styles[1]":"Visibility=1","controlStyles[19].target":"Windows.UI.Xaml.Controls.Grid#DroppedFlickerWorkaroundWrapper > Windows.UI.Xaml.Controls.Border#BackgroundBorder","controlStyles[19].styles[0]":"Background@PointerOver:=$Glass","controlStyles[19].styles[1]":"Background@Pressed:=$Glass","controlStyles[19].styles[2]":"Background@Selected:=$Glass","controlStyles[20].target":"Windows.UI.Xaml.Controls.Border#BackgroundBorder","controlStyles[20].styles[0]":"CornerRadius=10","controlStyles[21].target":"Windows.UI.Xaml.Controls.Grid#ContentBorder","controlStyles[21].styles[0]":"CornerRadius=10","controlStyles[22].target":"Windows.UI.Xaml.Controls.Border#LayerBorder","controlStyles[22].styles[0]":"CornerRadius=$CornerRadius","controlStyles[23].target":"Windows.UI.Xaml.Controls.Grid#OuterBorderGrid","controlStyles[23].styles[0]":"CornerRadius=$CornerRadius","controlStyles[24].target":"Windows.UI.Xaml.PopupRoot","controlStyles[24].styles[0]":"CornerRadius=$CornerRadius","controlStyles[25].target":"Windows.UI.Xaml.Controls.Grid#RightCompanionContainerGrid","controlStyles[25].styles[0]":"Visibility=Collapsed","controlStyles[26].target":"StartMenu.PinnedList#StartMenuPinnedList","controlStyles[26].styles[0]":"Visibility=0","controlStyles[26].styles[1]":"Margin=0,0,0,65","controlStyles[26].styles[2]":"RenderTransform:=<TranslateTransform X=\"-0\" Y=\"0\" />","controlStyles[26].styles[3]":"Height=Auto","controlStyles[26].styles[4]":"MinHeight:=100","controlStyles[26].styles[5]":"MaxHeight:=1000","controlStyles[27].target":"Windows.UI.Xaml.Controls.TextBlock#PinnedListHeaderText","controlStyles[27].styles[0]":"Visibility=0","controlStyles[27].styles[1]":"Margin=0,10,0,0","controlStyles[27].styles[2]":"RenderTransform:=<TranslateTransform X=\"60\" Y=\"-10\" />","controlStyles[28].target":"Microsoft.UI.Xaml.Controls.DropDownButton#ViewSelectionButton","controlStyles[28].styles[0]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"0\" />","controlStyles[29].target":"Windows.UI.Xaml.Controls.Grid#NavPanePlaceholder","controlStyles[29].styles[0]":"Width=630","controlStyles[29].styles[1]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"0\" />","controlStyles[29].styles[2]":"Background:=$ElementBG","controlStyles[29].styles[3]":"BorderBrush:=$ElementBorderBrush","controlStyles[29].styles[4]":"CornerRadius=$ElementCornerRadius","controlStyles[29].styles[5]":"BorderThickness=$ElementBorderThickness","controlStyles[29].styles[6]":"Height=55","controlStyles[29].styles[7]":"Padding=5","controlStyles[29].styles[8]":"Margin=0,-30,0,0","controlStyles[29].styles[9]":"MaxWidth:=600","controlStyles[29].styles[10]":"MinWidth=600","controlStyles[30].target":"Windows.UI.Xaml.Controls.Primitives.ScrollBar#VerticalScrollBar","controlStyles[30].styles[0]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"0\" />","controlStyles[31].target":"StartMenu.PinnedList#StartMenuPinnedList > Windows.UI.Xaml.Controls.Grid#Root > Windows.UI.Xaml.Controls.GridView#PinnedList > Windows.UI.Xaml.Controls.Border","controlStyles[31].styles[0]":"Background:=$ElementBG","controlStyles[31].styles[1]":"BorderBrush:=$ElementBorderBrush","controlStyles[31].styles[2]":"CornerRadius=$CornerRadius","controlStyles[31].styles[3]":"BorderThickness=$ElementBorderThickness","controlStyles[31].styles[4]":"Padding:=10,5,0,5","controlStyles[32].target":"Windows.UI.Xaml.Controls.Grid#AllListHeading","controlStyles[32].styles[0]":"RenderTransform:=<TranslateTransform X=\"0\" Y=\"-70\" />","controlStyles[33].target":"StartMenu.PinnedListTile > Windows.UI.Xaml.Controls.Grid#Root > Windows.UI.Xaml.Controls.Grid#DisplayNameAndDownloadIconContainer > Windows.UI.Xaml.Controls.TextBlock","controlStyles[33].styles[0]":"Visibility=0","controlStyles[34].target":"StartMenu.StartHome","controlStyles[34].styles[0]":"Margin=-15,0,-15,10","controlStyles[34].styles[1]":"Padding=0","controlStyles[35].target":"StartMenu.StartMenuCompanion#RightCompanion > Windows.UI.Xaml.Controls.Grid#CompanionRoot > Windows.UI.Xaml.Controls.Border#AcrylicBorder","controlStyles[35].styles[0]":"Background:=$ElementBG","controlStyles[35].styles[1]":"BorderBrush:=$ElementBorderBrush","controlStyles[35].styles[2]":"BorderThickness=$ElementBorderThickness","controlStyles[35].styles[3]":"CornerRadius=$ElementCornerRadius","controlStyles[36].target":"Windows.UI.Xaml.Controls.Grid#TopLevelHeader > Windows.UI.Xaml.Controls.Grid > Windows.UI.Xaml.Controls.Button","controlStyles[36].styles[0]":"Visibility=1","controlStyles[37].target":"Windows.UI.Xaml.Controls.MenuFlyoutPresenter > Windows.UI.Xaml.Controls.Border","controlStyles[37].styles[0]":"BorderBrush:=$BorderBrush","controlStyles[37].styles[1]":"Background:=$Glass","controlStyles[37].styles[2]":"CornerRadius=15","controlStyles[37].styles[3]":"BorderThickness=$BorderThickness","controlStyles[38].target":"Windows.UI.Xaml.Controls.ToolTip > Windows.UI.Xaml.Controls.ContentPresenter#LayoutRoot","controlStyles[38].styles[0]":"Background:=$Glass","controlStyles[38].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[38].styles[2]":"BorderThickness=$BorderThickness","controlStyles[38].styles[3]":"CornerRadius=15","controlStyles[39].target":"#Windows.UI.Xaml.Controls.Button#AddButton","controlStyles[39].styles[0]":"Background:=$Glass","controlStyles[39].styles[1]":"BorderBrush:=$BorderBrush","controlStyles[39].styles[2]":"BorderThickness=$BorderThickness","controlStyles[39].styles[3]":"CornerRadius=15","controlStyles[40].target":"#Windows.UI.Xaml.Controls.Grid#MainMenu","controlStyles[40].styles[0]":"MaxWidth:=400","controlStyles[41].target":"#Windows.UI.Xaml.Controls.GridView#PinnedList > Border > Windows.UI.Xaml.Controls.ScrollViewer","controlStyles[41].styles[0]":"ScrollViewer.VerticalScrollMode=2","controlStyles[41].styles[1]":"MaxHeight:=330","controlStyles[41].styles[2]":"MinHeight:=100","controlStyles[41].styles[3]":"Height=Auto","controlStyles[42].target":"StartMenu.CategoryControl","controlStyles[42].styles[0]":"Margin=0,-110,-8,-8","controlStyles[43].target":"Windows.UI.Xaml.Controls.GridViewHeaderItem > Windows.UI.Xaml.Controls.Border > Windows.UI.Xaml.Controls.ContentPresenter#ContentPresenter > Windows.UI.Xaml.Controls.Button#Header > Windows.UI.Xaml.Controls.Border#Border","controlStyles[43].styles[0]":"CornerRadius=10","controlStyles[44].target":"StartMenu.FolderModal#StartFolderModal > Windows.UI.Xaml.Controls.Grid#Root > Windows.UI.Xaml.Controls.ContentControl#ContentControl > Windows.UI.Xaml.Controls.ContentPresenter > StartMenu.UniversalTileContainer#UniversalTileContainer > Windows.UI.Xaml.Controls.Grid#GridViewContainer","controlStyles[44].styles[0]":"Width=350","controlStyles[44].styles[1]":"Height=350","controlStyles[45].target":"StartMenu.SearchBoxToggleButton#SearchBoxToggleButton > Windows.UI.Xaml.Controls.Grid","controlStyles[45].styles[0]":"Background:=$ElementBG","controlStyles[45].styles[1]":"BorderBrush:=$ElementBorderBrush","controlStyles[45].styles[2]":"BorderThickness=$ElementBorderThickness","controlStyles[45].styles[3]":"CornerRadius=15","controlStyles[46].target":"#StartMenu.StartBlendedFlexFrame","controlStyles[46].styles[0]":"Width=630","controlStyles[47].target":"Grid#TopLevelSuggestionsListHeader","controlStyles[47].styles[0]":"Margin=-5,-40,5,0","controlStyles[48].target":"Windows.UI.Xaml.Controls.GridView#RecommendedList","controlStyles[48].styles[0]":"Margin=-5,-60,5,60","controlStyles[49].target":"Button#ShowMoreSuggestionsButton","controlStyles[49].styles[0]":"Margin=-55,-64,55,64","controlStyles[50].target":"Windows.UI.Xaml.Controls.GridView#RecommendedList > Border > Windows.UI.Xaml.Controls.ScrollViewer > Border > Grid > Windows.UI.Xaml.Controls.ScrollContentPresenter > Windows.UI.Xaml.Controls.ItemsPresenter > Windows.UI.Xaml.Controls.ItemsWrapGrid > Windows.UI.Xaml.Controls.GridViewItem","controlStyles[50].styles[0]":"MaxWidth=310","controlStyles[50].styles[1]":"Width=310","styleConstants[0]":"Glass=<WindhawkBlur BlurAmount=\"15\" TintColor=\"#10808080\"/>","styleConstants[1]":"BorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"#50808080\" Offset=\"0.0\" /><GradientStop Color=\"#50404040\" Offset=\"0.25\" /><GradientStop Color=\"#50808080\" Offset=\"1\" /></LinearGradientBrush>","styleConstants[2]":"BorderBrush2=<WindhawkBlur BlurAmount=\"10\" TintColor=\"#909090\" TintOpacity=\"0.3\"/>","styleConstants[3]":"ClockBG=<WindhawkBlur BlurAmount=\"15\" TintColor=\"{ThemeResource SystemAccentColorLight2}\" TintOpacity=\"0.3\" />","styleConstants[4]":"BorderThickness=0.3,1,0.3,1","styleConstants[5]":"CornerRadius=25","styleConstants[6]":"SearchBoxRadius=15","styleConstants[7]":"ElementBG=<SolidColorBrush Color=\"{ThemeResource SystemChromeAltHighColor}\" Opacity=\"0.3\" />","styleConstants[8]":"ElementBorderThickness=0.3,0.3,0.3,1","styleConstants[9]":"ElementCornerRadius=20","styleConstants[10]":"ElementBorderBrush=<LinearGradientBrush StartPoint=\"0,0\" EndPoint=\"0,1\"><GradientStop Color=\"#50808080\" Offset=\"1\" /><GradientStop Color=\"#50606060\" Offset=\"0.15\" /></LinearGradientBrush>","styleConstants[11]":"ElementBorderBrush2=<WindhawkBlur BlurAmount=\"30\" TintColor=\"#909090\" TintOpacity=\"0.3\"/>","controlStyles[51].target":"Grid#FrameRoot","controlStyles[51].styles[0]":"MaxHeight=775","controlStyles[52].target":"Grid#MainMenu","controlStyles[52].styles[0]":"Width=630","controlStyles[42].styles[1]":"RenderTransform:=<TranslateTransform X=\\\"14\\\" />","controlStyles[31].styles[5]":"Margin:=30,15,30,0"}
```

## 3. Taskbar height and icon size
```json
{"TaskbarHeight":44,"IconSize":24,"TaskbarButtonWidth":37,"IconSizeSmall":16,"TaskbarButtonWidthSmall":32}
```
</details>

