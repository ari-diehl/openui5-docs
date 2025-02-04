<!-- loiodad1905a07f849ce9c509721317d38d8 -->

| loio |
| -----|
| dad1905a07f849ce9c509721317d38d8 |

<div id="loio">

view on: [demo kit nightly build](https://sdk.openui5.org/nightly/#/topic/dad1905a07f849ce9c509721317d38d8) | [demo kit latest release](https://sdk.openui5.org/topic/dad1905a07f849ce9c509721317d38d8)</div>

## Walkthrough Tutorial \(TypeScript\)

In this tutorial we will introduce you to all major development paradigms of OpenUI5.

We first introduce you to the basic development paradigms like *Model-View-Controller* and establish a best-practice structure of our application. We'll do this along the classic example of “Hello World” and start a new app from scratch. Next, we'll introduce the fundamental data binding concepts of OpenUI5 and extend our app to show a list of invoices. We'll continue to add more functionality by adding navigation, extending controls, and making our app responsive. Finally we'll look at the testing features and the built-in support tools of OpenUI5.

***

### Preview

![Preview of the UI5 application that is going to be built in this tutorial. Contains a Hello World upper part with buttons and a text input. The lower part shows list of invoices with details, grouped by vendor names.](images/loiofb12cea5ac9b45bb9007aac5a1a8689f_LowRes.png)

***

> ### Tip:  
> You don't have to do all tutorial steps sequentially, you can also jump directly to any step you want. Just download the code from the previous step and make sure that the application runs as intended; for detailed instructions, see [Downloading Code for a Tutorial Step](Get_Started_Setup_Tutorials_and_Demo_Apps_8b49fc1.md#loio8b49fc198bf04b2d9800fc37fecbb218__tutorials_download).
> 
> You can view and download the samples for all steps in the Demo Kit at [Walkthrough](https://sdk.openui5.org/entity/sap.m.tutorial.walkthrough).
> 
> For more information, see the overview page: [Get Started: Setup, Tutorials, and Demo Apps](Get_Started_Setup_Tutorials_and_Demo_Apps_8b49fc1.md).

-   **[Step 1: Hello World!](Step_1_Hello_World_c20489e.md "As you know OpenUI5 is
		all about HTML5. Let’s get started with building a first “Hello World” with only
		HTML.")**  
As you know OpenUI5 is all about HTML5. Let’s get started with building a first “Hello World” with only HTML.
-   **[Step 2: Bootstrap](Step_2_Bootstrap_32b14d8.md "Before we can do something with OpenUI5, we need to load and
		initialize it. This process of loading and initializing OpenUI5 is called
			bootstrapping. Once this bootstrapping is finished, we simply
		display an alert.")**  
Before we can do something with OpenUI5, we need to load and initialize it. This process of loading and initializing OpenUI5 is called **bootstrapping**. Once this bootstrapping is finished, we simply display an alert.
-   **[Step 3: Controls](Step_3_Controls_0feb70c.md "Now it is time to build our first little UI by replacing the “Hello World” text in the HTML body by the OpenUI5 control sap/m/Text. In the beginning, we will use the
		JavaScript control interface to set up the UI, the control instance is then placed into the HTML body. ")**  
Now it is time to build our first little UI by replacing the “Hello World” text in the HTML body by the OpenUI5 control `sap/m/Text`. In the beginning, we will use the JavaScript control interface to set up the UI, the control instance is then placed into the HTML body.
-   **[Step 4: XML Views](Step_4_XML_Views_6c66ed8.md "Putting all our UI into the index.js file will very soon result in a messy setup, and there is quite a bit of work ahead
		of us. So let’s do a first modularization by putting the sap/m/Text control into a dedicated
		view.")**  
Putting all our UI into the `index.js` file will very soon result in a messy setup, and there is quite a bit of work ahead of us. So let’s do a first modularization by putting the `sap/m/Text` control into a dedicated `view`.
-   **[Step 5: Controllers](Step_5_Controllers_e5c58fe.md "In this step, we replace the text with a button and show the “Hello World” message
		when the button is pressed. The handling of the button's press event is
		implemented in the controller of the view.")**  
In this step, we replace the text with a button and show the “Hello World” message when the button is pressed. The handling of the button's `press` event is implemented in the controller of the view.
-   **[Step 6: Modules](Step_6_Modules_3510034.md "In OpenUI5, resources are often referred to as modules. In this step, we
		replace the alert from the last exercise with a proper Message Toast from the sap.m library.")**  
In OpenUI5, resources are often referred to as modules. In this step, we replace the alert from the last exercise with a proper Message Toast from the `sap.m` library.
-   **[Step 7: JSON Model](Step_7_JSON_Model_cfbbeab.md "Now that we have set up the view and controller, it’s about time to think about the M
		in MVC.")**  
Now that we have set up the view and controller, it’s about time to think about the M in MVC.
-   **[Step 8: Translatable Texts](Step_8_Translatable_Texts_4dcf52e.md "In this step we move the texts of our UI to a separate resource file.")**  
In this step we move the texts of our UI to a separate resource file.
-   **[Step 9: Component Configuration](Step_9_Component_Configuration_f9d0e2f.md "After we have introduced all three parts of the Model-View-Controller (MVC) concept,
		we now come to another important structural aspect of OpenUI5. ")**  
After we have introduced all three parts of the Model-View-Controller \(MVC\) concept, we now come to another important structural aspect of OpenUI5.
-   **[Step 10: Descriptor for Applications](Step_10_Descriptor_for_Applications_2a46b75.md "All application-specific configuration settings will now further be put in a separate
		descriptor file called manifest.json. This clearly separates the
		application coding from the configuration settings and makes our app even more flexible. For
		example, all SAP Fiori applications
		are realized as components and come with a descriptor file in order to be hosted in the
			SAP Fiori launchpad.")**  
All application-specific configuration settings will now further be put in a separate descriptor file called `manifest.json`. This clearly separates the application coding from the configuration settings and makes our app even more flexible. For example, all SAP Fiori applications are realized as components and come with a descriptor file in order to be hosted in the SAP Fiori launchpad.
-   **[Step 11: Pages and Panels](Step_11_Pages_and_Panels_feed613.md "After all the work on the app structure it’s time to improve the look of our app. We
		will use two controls from the sap.m library to add a bit more &quot;bling&quot; to
		our UI. You will also learn about control aggregations in this step.")**  
After all the work on the app structure it’s time to improve the look of our app. We will use two controls from the `sap.m` library to add a bit more "bling" to our UI. You will also learn about control aggregations in this step.
-   **[Step 12: Shell Control as Container](Step_12_Shell_Control_as_Container_4af44cb.md "Now we use a shell control as container for our app and use it as our new root
		element. The shell takes care of visual adaptation of the application to the device’s screen
		size by introducing a so-called letterbox on desktop screens.")**  
Now we use a shell control as container for our app and use it as our new root element. The shell takes care of visual adaptation of the application to the device’s screen size by introducing a so-called letterbox on desktop screens.
-   **[Step 13: Margins and Paddings](Step_13_Margins_and_Paddings_5826c0c.md "Our app content is still glued to the corners of the letterbox. To fine-tune our
		layout, we can add margins and paddings to the controls that we added in the previous step. ")**  
Our app content is still glued to the corners of the letterbox. To fine-tune our layout, we can add margins and paddings to the controls that we added in the previous step.
-   **[Step 14: Custom CSS and Theme Colors](Step_14_Custom_CSS_and_Theme_Colors_4cc841e.md "Sometimes we need to define some more fine-granular layouts and this is when we can
		use the flexibility of CSS by adding custom style classes to controls and style them as we
		like. ")**  
Sometimes we need to define some more fine-granular layouts and this is when we can use the flexibility of CSS by adding custom style classes to controls and style them as we like.
-   **[Step 15: Nested Views](Step_15_Nested_Views_9bbbfaa.md "Our panel content is getting more and more complex and now it is time to move the
      panel content to a separate view. With that approach, the application structure is much easier
      to understand, and the individual parts of the app can be reused.")**  
Our panel content is getting more and more complex and now it is time to move the panel content to a separate view. With that approach, the application structure is much easier to understand, and the individual parts of the app can be reused.
-   **[Step 16: Dialogs and Fragments](Step_16_Dialogs_and_Fragments_4b2e306.md "In this step, we will take a closer look at another element which can be used to
		assemble views: the fragment. ")**  
In this step, we will take a closer look at another element which can be used to assemble views: the fragment.
-   **[Step 17: Fragment Callbacks](Step_17_Fragment_Callbacks_f030afc.md "Now that we have integrated the dialog, it's time to add some user interaction. The
		user will definitely want to close the dialog again at some point, so we add a button to
		close the dialog and assign an event handler.")**  
Now that we have integrated the dialog, it's time to add some user interaction. The user will definitely want to close the dialog again at some point, so we add a button to close the dialog and assign an event handler.
-   **[Step 18: Icons](Step_18_Icons_49b1ac6.md "Our dialog is still pretty much empty. Since OpenUI5 is shipped with a large
		icon font that contains more than 500 icons, we will add an icon to greet our users when the
		dialog is opened.")**  
Our dialog is still pretty much empty. Since OpenUI5 is shipped with a large icon font that contains more than 500 icons, we will add an icon to greet our users when the dialog is opened.
-   **[Step 19: Aggregation Binding](Step_19_Aggregation_Binding_24580fb.md "Now that we have established a good structure for our app, it's time to add some more
		functionality. We start exploring more features of data binding by adding some invoice data
		in JSON format that we display in a list below the panel.")**  
Now that we have established a good structure for our app, it's time to add some more functionality. We start exploring more features of data binding by adding some invoice data in JSON format that we display in a list below the panel.
-   **[Step 20: Data Types](Step_20_Data_Types_0dad01a.md "The list of invoices is already looking nice, but what is an invoice without a price
		assigned? Typically prices are stored in a technical format and with a '.'
		delimiter in the data model. For example, our invoice for pineapples has the calculated
		price 87.2 without a currency. We are going to use the OpenUI5 data types to format the
		price properly, with a locale-dependent decimal separator and two digits after the
		separator.")**  
The list of invoices is already looking nice, but what is an invoice without a price assigned? Typically prices are stored in a technical format and with a '`.`' delimiter in the data model. For example, our invoice for pineapples has the calculated price `87.2` without a currency. We are going to use the OpenUI5 data types to format the price properly, with a locale-dependent decimal separator and two digits after the separator.
-   **[Step 21: Expression Binding](Step_21_Expression_Binding_8d67ba2.md "Sometimes the predefined types of OpenUI5 are not flexible enough
		and you want to do a simple calculation or formatting in the view - that is where
		expressions are really helpful. We use them to format our price according to the current
		number in the data model.")**  
Sometimes the predefined types of OpenUI5 are not flexible enough and you want to do a simple calculation or formatting in the view - that is where expressions are really helpful. We use them to format our price according to the current number in the data model.
-   **[Step 22: Custom Formatters](Step_22_Custom_Formatters_61d4e2b.md "If we want to do a more complex logic for formatting properties of our data model, we
		can also write a custom formatting function. We will now add a localized status with a
		custom formatter, because the status in our data model is in a rather technical
		format.")**  
If we want to do a more complex logic for formatting properties of our data model, we can also write a custom formatting function. We will now add a localized status with a custom formatter, because the status in our data model is in a rather technical format.
-   **[Step 23: Filtering](Step_23_Filtering_7f02e9d.md "In this step, we add a search field for our product list and define a filter that
		represents the search term. When searching, the list is automatically updated to show only
		the items that match the search term.")**  
In this step, we add a search field for our product list and define a filter that represents the search term. When searching, the list is automatically updated to show only the items that match the search term.
-   **[Step 24: Sorting and Grouping](Step_24_Sorting_and_Grouping_86bbe13.md "To make our list of invoices even more user-friendly, we sort it alphabetically
		instead of just showing the order from the data model. Additionally, we introduce groups and
		add the company that ships the products so that the data is easier to consume.")**  
To make our list of invoices even more user-friendly, we sort it alphabetically instead of just showing the order from the data model. Additionally, we introduce groups and add the company that ships the products so that the data is easier to consume.
-   **[Step 25: Remote OData Service](Step_25_Remote_OData_Service_b68d321.md "So far we have worked with local JSON data, but now we will access a real OData
		service to visualize remote data.")**  
So far we have worked with local JSON data, but now we will access a real OData service to visualize remote data.
-   **[Step 26: Mock Server Configuration](Step_26_Mock_Server_Configuration_3e1c64f.md "We just ran our app against a real service, but for developing and testing our app we
		do not want to rely on the availability of the “real” service or put additional load on the
		system where the data service is located.")**  
We just ran our app against a real service, but for developing and testing our app we do not want to rely on the availability of the “real” service or put additional load on the system where the data service is located.
-   **[Step 27: Unit Test with QUnit](Step_27_Unit_Test_with_QUnit_750c8c1.md "Now that we have a test folder in the app, we can start to increase our test
		coverage. ")**  
Now that we have a test folder in the app, we can start to increase our test coverage.
-   **[Step 28: Integration Test with OPA](Step_28_Integration_Test_with_OPA_412f0b6.md "If we want to test interaction patterns or more visual features of our app, we can
		also write an integration test. ")**  
If we want to test interaction patterns or more visual features of our app, we can also write an integration test.
-   **[Step 29: Debugging Tools](Step_29_Debugging_Tools_50990a0.md "Even though we have added a basic test coverage in the previous steps, it seems like
		we accidentally broke our app, because it does not display prices to our invoices anymore.
		We need to debug the issue and fix it before someone finds out.")**  
Even though we have added a basic test coverage in the previous steps, it seems like we accidentally broke our app, because it does not display prices to our invoices anymore. We need to debug the issue and fix it before someone finds out.
-   **[Step 30: Routing and Navigation](Step_30_Routing_and_Navigation_6173e3d.md "So far, we have put all app content on one single page. As we add more and more
		features, we want to split the content and put it on separate pages.")**  
So far, we have put all app content on one single page. As we add more and more features, we want to split the content and put it on separate pages.
-   **[Step 31: Routing with Parameters](Step_31_Routing_with_Parameters_afd5eb6.md "We can now navigate between the overview and the detail page, but the actual item
		that we selected in the overview is not displayed on the detail page yet. A typical use case
		for our app is to show additional information for the selected item on the detail page. ")**  
We can now navigate between the overview and the detail page, but the actual item that we selected in the overview is not displayed on the detail page yet. A typical use case for our app is to show additional information for the selected item on the detail page.
-   **[Step 32: Routing Back and History](Step_32_Routing_Back_and_History_ae61211.md "Now we can navigate to our detail page and display an invoice, but we cannot go back
		to the overview page yet. We'll add a back button to the detail page and implement a
		function that shows our overview page again.")**  
Now we can navigate to our detail page and display an invoice, but we cannot go back to the overview page yet. We'll add a back button to the detail page and implement a function that shows our overview page again.
-   **[Step 33: Custom Controls](Step_33_Custom_Controls_3cc020e.md "In this step, we are going to extend the functionality of OpenUI5 with a custom control.
		We want to rate the product shown on the detail page, so we create a composition of multiple
		standard controls using the OpenUI5 extension mechanism and
		add some glue code to make them work nicely together. This way, we can reuse the control
		across the app and keep all related functionality in one module.")**  
In this step, we are going to extend the functionality of OpenUI5 with a custom control. We want to rate the product shown on the detail page, so we create a composition of multiple standard controls using the OpenUI5 extension mechanism and add some glue code to make them work nicely together. This way, we can reuse the control across the app and keep all related functionality in one module.
-   **[Step 34: Responsiveness](Step_34_Responsiveness_e5577bb.md "In this step, we improve the responsiveness of our app. OpenUI5 applications can be run
		on phone, tablet, and desktop devices and we can configure the application to make best use
		of the screen estate for each scenario. Fortunately, OpenUI5 controls like the
			sap.m.Table already deliver a lot of features that we can
		use.")**  
In this step, we improve the responsiveness of our app. OpenUI5 applications can be run on phone, tablet, and desktop devices and we can configure the application to make best use of the screen estate for each scenario. Fortunately, OpenUI5 controls like the `sap.m.Table` already deliver a lot of features that we can use.
-   **[Step 35: Device Adaptation](Step_35_Device_Adaptation_ab8ed1b.md "We now configure the visibility and properties of controls based on the device that
		we run the application on. By making use of the sap.ui.Device API and
		defining a device model we will make the app look great on many devices.")**  
We now configure the visibility and properties of controls based on the device that we run the application on. By making use of the `sap.ui.Device` API and defining a device model we will make the app look great on many devices.
-   **[Step 36: Content Density](Step_36_Content_Density_667aa4a.md "In this step of our Walkthrough tutorial, we adjust the content density based on the
		user’s device. OpenUI5 contains
		different content densities allowing you to display larger controls for touch-enabled
		devices and a smaller, more compact design for devices that are operated by mouse. In our
		app, we will detect the device and adjust the density accordingly.")**  
In this step of our Walkthrough tutorial, we adjust the content density based on the user’s device. OpenUI5 contains different content densities allowing you to display larger controls for touch-enabled devices and a smaller, more compact design for devices that are operated by mouse. In our app, we will detect the device and adjust the density accordingly.
-   **[Step 37: Accessibility](Step_37_Accessibility_5a74cea.md "In this step we're going to improve the accessibility of our app.")**  
In this step we're going to improve the accessibility of our app.
-   **[Step 38: Build Your Application](Step_38_Build_Your_Application_be33d01.md "In this step we're going to build our application and consume the speed of a built OpenUI5 application.")**  
In this step we're going to build our application and consume the speed of a built OpenUI5 application.

