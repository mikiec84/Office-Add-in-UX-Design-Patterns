# Office Add-in UX Design Patterns
This repository is a library of common UX design patterns for Office Add-ins. It represents a set of best practices for add-in interfaces. The patterns are built using Office UI Fabric components and styling. They complement Office experiences and follow add-in UX design principles. As you design your own Office Add-in, refer to the patterns, download the templates to quickly create your own mock-ups using Adobe Illustrator, or download the [code](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code "code").

## Table of contents

- [Get started](#user-content-get-started)
- [UX design patterns list](#user-content-ux-design-patterns-list)
- [Design Resources](#user-content-design-resources)
- [Known issues](#user-content-known-issues)
- [Additional Resources](#user-content-additional-resources)

## Get started
<Add directions on how to >

## UX design patterns list

#### Authentication

  * [Authentication Dialog Flow - Multiple Identity](src/docs/auth-multi.md) - Present a multi authentication screen to your end users.
  * [Authentication Dialog Flow - Single Identity](src/docs/auth-single.md) - Present a single identity authentication screen to your end users.

#### Branding
  
  * [Brand Bar](src/docs/brand-bar.md) - A space in the footer to include your brand name, logo and an optional settings access location.
  * [Splash Screen](src/docs/splash-screen.md) - This is a screen to display your company branding while the add-in is loading.
 
#### First-Run

  * [Carousel](src/docs/carousel.md) - Takes users through a series of features or informational steps before they start.
  * [Value Placemat](src/docs/value-placemat.md) - Provides a clear value proposition and list of features.
  * [Video Placemat](src/docs/video-placemat.md) - Provides value through video content.

#### Navigation

  * [Back Button](src/docs/back-button.md) - Shows a task pane with Back and Next Page buttons.
  * [Contextual Menu](src/docs/contextual-menu.md) - Provides links to the main areas of an add-in. Also called "left nav" or "navigation pane."
  * [Pivot](src/docs/pivot.md) - Allows users to navigate between different content. 
  * [Tab Bar](src/docs/tab-bar.md) - Shows navigation links at the top of the add-in space using icons and labels.

#### Utility

  * [Command Bar](src/docs/command-bar.md) - A surface that houses commands that operate on the content or parent region it resides above.
  * [Embedded Dialog](src/docs/embedded-dialog.md) - Displays a dialog inside of the task pane or content add-in.
  * [Settings](src/docs/settings.md) - Displays common components that may be used within an add-in's settings menu.
  
#### Notification

  * [Progress Indicator](src/docs/progress-indicator.md) - Shows the completion status of an operation lasting more than 2 seconds.
  * [Spinner](src/docs/spinner.md) - Indicates to the user that things are processing.
  * [Toast](src/docs/toast.md) - Provides a brief message that fades away after a few seconds.

## Design Resources

* Prototyping
  * [Components](src/assets/design-resources/AddinUXDesign_UIComponents.ai)
  * [Patterns](src/assets/design-resources/AddinUXDesign_UXPatterns.ai)
* Outlook Mobile
  * [iOS](src/assets/design-resources/iOS-Addins-Components-Final.sketch)

## Change Log
* 10/3/2016 - Added rudimentary in app store template.
* 9/22/2016 - Updates to authtentication patterns, adding new files for single and multiple identity provider patterns. 
* 8/9/2016 - Updates to cross-link markdowns with code samples
* 7/29/2016 - New pattern added, multisection. 
* 5/19/2016 - Added Brand Bar code link.
* 5/16/2016 - Added markdown files for each pattern.
* 5/6/2016 - Added links to code repo.
* 4/7/16 - Updates to the auth flows and dialog patterns
* 3/31/16 - Updates to dialog patterns files and other minor fixes
* 3/30/16 - Added 4 new first run patterns, updated brand_bar and notifications_inline_messages pattern
* 3/25/16 - Additional templates and patterns added
* 3/24/16 - Initial read-me and patterns release

## Additional resources

* [Best practices for developing Office Add-ins](https://dev.office.com/docs/add-ins/overview/add-in-development-best-practices)
* [Office UI Fabric](http://dev.office.com/fabric/)

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

Copyright © 2017 Microsoft Corporation. All rights reserved.