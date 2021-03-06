---
-api-id: P:Windows.UI.ApplicationSettings.SettingsPaneCommandsRequest.ApplicationCommands
-api-type: winrt property
---

<!-- Property syntax
public Windows.Foundation.Collections.IVector<Windows.UI.ApplicationSettings.SettingsCommand> ApplicationCommands { get; }
-->

# Windows.UI.ApplicationSettings.SettingsPaneCommandsRequest.ApplicationCommands

## -description
> [!NOTE]
> [SettingsPaneCommandsRequest](settingspanecommandsrequest.md) may be altered or unavailable for releases after Windows 10. Instead of using a [SettingsPane](settingspane.md), integrate settings options into the app experience. For more info, see [Guidelines for app settings](http://msdn.microsoft.com/library/2d765e90-3fa0-42f5-a5cb-bedc14c3f60a).

A vector that is available during the [CommandsRequested](settingspane_commandsrequested.md) event. Append [SettingsCommand](settingscommand.md) objects to it to make them available to the [SettingsPane](settingspane.md)UI.

## -property-value
The vector of [SettingsCommand](settingscommand.md) objects.

## -remarks

## -examples

## -see-also
