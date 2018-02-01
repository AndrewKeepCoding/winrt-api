---
-api-id: T:Windows.Networking.NetworkOperators.ESimAuthenticationPreference
-api-type: winrt enum
---

<!-- Enumeration syntax.
public enum ESimAuthenticationPreference : int 
-->

# Windows.Networking.NetworkOperators.ESimAuthenticationPreference

## -description
Defines constants that specify under what conditions the user should be challenged for eSIM authentication credentials.

> [!NOTE]
> To use this API you will need to contact Microsoft to request the restricted capability **Microsoft.eSIMManagement_8wekyb3d8bbwe**. For more info, see the **Special and restricted capabilities** section under [App capability declarations](/windows/uwp/packaging/app-capability-declarations?branch=live).

## -enum-fields
### -field OnEntry:0
Indicates that credentials should be requested when the eSIM is entered.

### -field OnAction:1
Indicates that credentials should be requested when the eSIM is involved in an action.

### -field Never:2
Indicates that credentials should never be requested.

## -remarks

## -see-also

## -examples

## -capabilities
Microsoft.eSIMManagement_8wekyb3d8bbwe