---
title: Getting Started
page_title: .NET MAUI ComboBox Documentation - Getting Started
description: "Get started with the Telerik UI for .NET MAUI ComboBox and add the control to your .NET MAUI project."
position: 1
slug: combobox-getting-started
---

# Getting Started

This guide provides the information you need to start using the Telerik UI for .NET MAUI ComboBox by adding the control to your project.

At the end, you will be able to achieve the following result.

![ComboBox Getting Started](images/combobox-getting-started.png)

## Prerequisites

Before adding the ComboBox, you need to:

1. [Set up your .NET MAUI application]({%slug maui-getting-started %}#set-up-your-net-maui-application).

1. [Download Telerik UI for .NET MAUI]({% slug maui-getting-started %}#download-telerik-ui-for-net-maui).

1. [Install Telerik UI for .NET MAUI]({%slug maui-getting-started %}#install-telerik-ui-for-net-maui).

## Define the Control

When your .NET MAUI application is set up, you are ready to add a ComboBox control to your page. The following example demonstrates the definition of the `RadComboBox` with `ItemsSource` set to a static collection as well as bound to property from a ViewModel class.

### Using static data

<snippet id='combobox-getting-started-static-items-xaml'/>

Here is the result:

![ComboBox Getting Started](images/combobox-getting-started.png)

### Binding to a complex object

Here is the ComboBox definition in XAML:

<snippet id='combobox-getting-started-complex-object-xaml'/>

> When binding to a complex objects, ComboBox **DisplayMemberPath** property should be set.

the sample business model

<snippet id='combobox-city-businessmodel'/>

and the ViewModel used:

<snippet id='combobox-cities-viewmodel'/>

Here is the result:

![ComboBox Binding](images/combobox-getting-started-complex-data.png)

>important For the ComboBox Getting Started example refer to the [SDKBrowser Demo Application]({%slug sdkbrowser-app%}).

## Additional Resources

- [.NET MAUI ComboBox product page](https://www.telerik.com/maui-ui/checkbox)
- [.NET MAUI ComboBox forum page](https://www.telerik.com/forums/maui?tagId=1937)
- [Telerik .NET MAUI blogs](https://www.telerik.com/blogs/tag/.net-maui)
- [Telerik .NET MAUI roadmap](https://www.telerik.com/support/whats-new/maui-ui/roadmap)

## See Also

- [Configuration]({%slug combobox-configuration%})
- [Data Binding]({%slug combobox-databinding%})
- [Edit Mode & Search]({%slug combobox-editmode-and-search%}) 
- [Single and Multiple Selection]({%slug combobox-selection%})
