---
-api-id: T:Windows.UI.WebUI.WebUIPrintTaskSettingsActivatedEventArgs
-api-type: winrt class
---

<!-- Class syntax.
public class WebUIPrintTaskSettingsActivatedEventArgs : Windows.ApplicationModel.Activation.IActivatedEventArgs, Windows.ApplicationModel.Activation.IPrintTaskSettingsActivatedEventArgs, Windows.UI.WebUI.IActivatedEventArgsDeferral
-->

# Windows.UI.WebUI.WebUIPrintTaskSettingsActivatedEventArgs

## -description
Provided in response to the event that is raised when print task settings are activated.

## -remarks
This object is accessed when you implement an event handler for the [WinJS.Application.Onactivated](https://docs.microsoft.com/previous-versions/windows/apps/br212679(v=win.10)) or the [Windows.UI.WebUI.WebUIApplication.activated](webuiapplication_activated.md) events when [ActivationKind](../windows.applicationmodel.activation/activationkind.md) is **printTaskSettings**.



> [!NOTE]
> : This class is not agile, which means that you need to consider its threading model and marshaling behavior. For more info, see [Threading and Marshaling (C++/CX)](http://msdn.microsoft.com/en-us/library/windows/apps/hh771042.aspx)
<!--[jjacks - removed this link (https://go.microsoft.com/fwlink/p/?linkid=258277 404->http://msdn.microsoft.com/library/windows/apps/jj157115.aspx) because it doesn't work] and Using Windows Runtime objects in a multithreaded environment (.NET)-->
.

## -examples

## -see-also
