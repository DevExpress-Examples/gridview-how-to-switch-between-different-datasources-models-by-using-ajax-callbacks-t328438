# GridView - How to switch between different datasources (models) by using ajax callbacks


This example is an MVC-based analog of the <a href="https://www.devexpress.com/Support/Center/p/E2968">E2968 - How to bind ASPxGridView with autogenerated columns to different data sources at runtime</a> code example. Note that in the case of MVC, implementation is much simpler. We use an AJAX callback to reload the GridView extension with the selected datasource. In addition, it is necessary to pass the datasource Id to GridView-specific callbacks. We use the approach described in the <a href="https://documentation.devexpress.com/#AspNet/CustomDocument9941">Passing Values to a Controller Action through Callbacks</a> help section for this purpose.<br><br><strong>See Also:</strong><br><a href="https://www.devexpress.com/Support/Center/p/E4063">E4063 - How to use the jQuery.ajax function with DevExpress MVC Extensions</a> <br><a href="https://www.devexpress.com/Support/Center/p/T191698">T191698 - How to isolate extension settings into separate helper class and share a single partial view to display multiple extensions</a>

<br/>

