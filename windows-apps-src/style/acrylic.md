---


 - When the pane opens side-by-side with main app content, this should be [60% background acrylic](acrylic/#acrylic-theme-resources)

### Multiple acrylic panes
 - For the tertiary pane further away from primary content, use [60% background acrylic](acrylic/#acrylic-theme-resources)


> [!Note]
> Rendering acrylic surfaces can be GPU intensive, which can increase power consumption and shorten battery life on some devices. Acrylic effects are automatically disabled when devices enter battery saver mode, and users can disable acrylic effects for all apps, if they choose. 



<table>
        <th align="center">Tint opacity</th>
        <th align="center">[Fallback color](color.md)</th>
    </tr>
    </tr>
    </tr>
        <td> **Recommended usage:** These are general-purpose acrylic resources that work well in a wide variety of usages. If your app uses secondary text of AltMedium color with text size smaller than 18px, place an 80% acrylic resource behind the text to [meet contrast ratio requirements](../accessibility/accessible-text-requirements.md). </td>
    </tr>
    </tr>
    <tr>
        <td> **Recommended usage:** If your app uses secondary text of AltMedium color with a text size of 18px or larger, you can place these more transparent 70% acrylic resources behind the text. We recommend using these resources in your app's top horizontal navigation and commanding areas.  </td>
    </tr>
    </tr>
    <tr>
        <td> **Recommended usage:** When placing only primary text of AltHigh color over acrylic, your app can utilize these 60% resources. We recommend painting your app's [vertical navigation pane](../controls-and-patterns/navigationview-rs3.md), i.e. hamburger menu, with 60% acrylic. </td>
    </tr>
        <th align="center">Tint opacity</th>
        <th align="center">[Tint and Fallback colors](color.md)</th>
    </tr>
            BackgroundSource="HostBackdrop"
            BackgroundSource="HostBackdrop"
    myBrush.BackgroundSource = Windows.UI.Xaml.Media.AcrylicBackgroundSource.HostBackdrop;
    myBrush.TintColor = Color.FromArgb(255, 202, 24, 37);
