## Publish Power BI report on Website

If you want to publish a Power BI report on our website, you have two options:

### WAY 1: Secure embedding

This method requires an access login and a Power BI license. Follow these steps:

1. From file menu Click on the "Embed" button.
2. Go to the "Website or portal" section.
![](../assets/20240830_113659_image.png)
3. Copy the generated iframe code.
4. Paste the iframe code into your website's HTML.

In this way, an access login is required. And you should have Power BI license (unless specific capacity size)

Here's an example of how the report appear:


<iframe title="AdventureWorks_Report" width="1140" height="541.25" src="https://app.powerbi.com/reportEmbed?reportId=a024583e-0c11-43b4-a8ba-799b6d36ee3a&autoAuth=true&ctid=e301c34d-8dfc-445f-b32f-9ce102596439" frameborder="0" allowFullScreen="true"></iframe>



### WAY 2: Publish to web

If you want to make the report accessible to anyone on the internet without requiring authentication, you can use the "Publish to web" feature. Follow these steps:

1. Read the [Publish to web documentation](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-publish-to-web) for more information.
2. Click on the "Publish to web" button.

![](../assets/20240830_114059_image.png)

3. Copy the generated iframe code.
4. Paste the iframe code into your website's HTML.

Here's an example of how the published report will look like:

<iframe title="AdventureWorks_Report" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiNDY0NGQ1MTctM2M5NC00NWFhLThkODctN2EzNWJiOGRlMjEyIiwidCI6ImUzMDFjMzRkLThkZmMtNDQ1Zi1iMzJmLTljZTEwMjU5NjQzOSIsImMiOjZ9" frameborder="0" allowFullScreen="true"></iframe>


- The report is interactive and can be fully navigated.
- The report can be viewed by anyone on the internet without authentication.

Please note that using the "Publish to web" feature has some limitations. Make sure to review them before making a decision.

#### Considerations and Limitations

Before publishing your Power BI report, consider the following limitations:


![](../assets/20240830_112926_image.png)


