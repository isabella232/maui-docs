---
title: Disabled Segments
page_title: .NET MAUI SegmentedControl Documentation - Disabled Segments
description: Check our &quot;Disable a Segment&quot; documentation article for Telerik SegmentedControl for .NET MAUI control.
position: 3
slug: segmentedcontrol-disable-segment
---

# Disabled Segments

The SegmentedControl allows you to disable each of its segments individually.

To disable a segment, use the `SetSegmentEnabled` method, which accepts the following arguments:

* `index` determines the index of the segment.

* `isEnabled` determines whether the item is enabled or not.

You can also check if an item is enabled through the `IsSegmentEnabled` method. The method accepts a single `index` argument.

## Setting the Text Color

You can set the text color of the disabled segment through the `DisabledSegmentTextColor`.

## Example

The following example shows how to disable a segment and define a color for it.

Define the control.

<snippet id='segmentcontrol-disablesegment-xaml' />

You can disable any segment with `SetSegmentEnabled` method:

<snippet id='segmentcontrol-disablesegment-setsegmentenabled' />

The following image shows the end result.

![SegmentedControl disable segment](images/segmentcontrol-features-disablesegment-0.png)

## See Also

- [Customizing the Segment Colors]({%slug segmentedcontrol-styling%})
