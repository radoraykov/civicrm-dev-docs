# hook_civicrm_enable

## Description

This hook is called when an extension is re-enabled. To be specific,
when its status changes from ***disabled*** to ***enabled.*****It is**
**NOT called **when the status changes from ***uninstalled*** to
***enabled*. **Each module will receive hook_civicrm_enable during its
own re-enablement (but not during the re-enablement of unrelated
modules).

For more background, see also [API and the Art of
Installation](http://civicrm.org/blogs/totten/api-and-art-installation).

## Parameters

-   None

## Returns

-   Void