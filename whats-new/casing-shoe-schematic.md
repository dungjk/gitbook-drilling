# Well casing shoe schematic

{% hint style="info" %}
plugin-casing-shoe 1.2.0 and plugin-wells 4.0.0 minimum versions required
{% endhint %}

The casing shoe schematic chart provides a visualization of the transversal section of a well, illustrating the well construction and previewing the bit depth position in real time. The schematic shows casing structures such as liners, slotted liners, lithology, target formations by depth of the casing string.

![Preview of casing shoe schematic chart with phases and lithology by depth](<../.gitbook/assets/image (354).png>)

{% hint style="warning" %}
The casing-shoe chart consumes static data from well design overview information at the well parameters tab and the bit depth real time standard channel
{% endhint %}

Static data used to render the casing shoe schematic at well parameters tab:

![Well design overview static information used to plot the chart](<../.gitbook/assets/image (17).png>)

Advantages **:**\\

***

* Preview well design phase information such as casing diameters, bit depth, lithology, and target formations, and casing structure including liners, screen, slotted liners or open hole by depth
* Go along with the real time bit depth position using the standard configured channel
* Use well casing shoe chart for different wells with dashboards filters or a predefined well
* Plan ahead knowing where it is advantageous to set the casing, defining where important formations are located

To include the chart go to edit mode at the dashboard and the option for casing shoe schematic widget will be available:

![Casing shoe schematic widget at the dashboard](<../.gitbook/assets/image (228).png>)

It is possible configure the chart to select the well by available wells list or with dashboard filter:

![Casing shoe well configuration](<../.gitbook/assets/image (58).png>)

If the well is selected directly in the widget, without using filters, it is possible to define the source of the data to be displayed. Options include “Execution” (from well parameters), “Design” (from well designs), or “Intervention”.

![Casing Shoe source data configuration](<../.gitbook/assets/image (537).png>)

For the well design, a selector is displayed with the design options registered for the well.

![Well design selected as source](<../.gitbook/assets/image (538).png>)

For the interventions, a selector is displayed with the options 'executed' or 'planned'.

![Intervention selected as source](<../.gitbook/assets/image (539).png>)

If the configuration is selected with dashboard filter it is possible to select the asset at the dashboard:

![well selection mode with dashboard filter](<../.gitbook/assets/image (475).png>)

![Well selected with dashboard filter](<../.gitbook/assets/image (398).png>)

It is possible to configure the graph styling by changing the presentation format to mirrored or simple. Additionally, you can choose whether or not to display the lithology and decide if the section details will be presented in a long or short format:

![Casing shoe chart configuration](<../.gitbook/assets/image (212).png>)

![Casing shoe chart configuration with simple visualization](<../.gitbook/assets/image (540).png>)

To show the bit position in real time the bit depth standard channel must be configured and with the data management enabled for the used well:

![Bit depth standard channels configuration](<../.gitbook/assets/image (113).png>)

![Bit depth channel at data management](<../.gitbook/assets/image (424).png>)

![Bit depth channel receiving values](<../.gitbook/assets/image (519).png>)

Then by hovering the mouse over the bit it will show the depth position:

![Bit depth position visualization](<../.gitbook/assets/image (464).png>)

It is possible to configure the objectives at the well parameters tab to preview by depth in the chart:

![Objectives configuration](<../.gitbook/assets/image (56).png>)

![Preview of objectives and formation in chart](<../.gitbook/assets/image (308).png>)

If the well is configured as onshore the surface is displayed instead of water depth:

![Onshore well visualization](<../.gitbook/assets/image (506).png>)

![Onshore well configured at well parameters tab](<../.gitbook/assets/image (231).png>)
