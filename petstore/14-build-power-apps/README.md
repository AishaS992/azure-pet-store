# 14 - Build a Power App that uses a Custom Connector to Pull Data

__This guide is part of the [Azure Pet Store App Dev Reference Guide](../README.md)__

In this section we'll look at how to develop an a Power App that consumes data from the Azure Function App that was built in the previous guide.

> 📝 **Please Note, we assume you have completed the [Configure Apps to use Application Insights](../stackedit.io/08-configure-apps-to-use-application-insights/README.md) guide and have a working Application Insights service that can be used by this Azure Function App.**

> 📝 **Please Note, we assume you have completed the [Build and Deploy Azure Functions](../13-build-deploy-azure-functions/README.md) guide and have a working Azure Function App that retrieves petStoreCurrentSessionTelemetry.**

Head over to https://powerapps.microsoft.com/ and sign in and selct the Home icon from the left navigation.

You should see the following:
  
![](images/pa1.png)

Before we create our Power App Canvas App, we are going to configure our Custom Data Connector. (It is possible to create the connectors at any point in time, for the sake of this guide, I decided to get the data integration implemented first)

Select Custom Connectors and then Select New custom connector (Create from blank)

You should see the following:
  
![](images/pa2.png)

Give your Connector a name (I'm using "Azure Pet Store Functions", this is the name of your app and how it will appear to your users.) And select "Continue"

You should see the following:
  
![](images/pa3.png)


You should see the following:
  
![](images/pa4.png)

You should see the following:
  
![](images/pa5.png)

You should see the following:
  
![](images/pa6.png)

You should see the following:
  
![](images/pa7.png)

You should see the following:
  
![](images/pa8.png)

You should see the following:
  
![](images/pa9.png)

You should see the following:
  
![](images/pa10.png)

You should see the following:
  
![](images/pa11.png)

You should see the following:
  
![](images/pa12.png)

You should see the following:
  
![](images/pa13.png)

You should see the following:
  
![](images/pa13_1.png)

You should see the following:
  
![](images/pa13_2.png)

You should see the following:
  
![](images/pa13_3.png)

You should see the following:
  
![](images/pa13_4.png)

You should see the following:
  
![](images/pa13_5.png)


You should see the following:
  
![](images/pa14.png)

You should see the following:
  
![](images/pa15.png)

You should see the following:
  
![](images/pa16.png)

You should see the following:
  
![](images/pa17.png)

You should see the following:
  
![](images/pa18.png)

You should see the following:
  
![](images/pa18_1.png)

You should see the following:
  
![](images/pa19.png)

You should see the following:
  
![](images/pa20.png)

You should see the following:
  
![](images/pa21.png)

You should see the following:
  
![](images/pa22.png)

You should see the following:
  
![](images/pa23.png)

You should see the following:
  
![](images/pa24.png)

You should see the following:
  
![](images/pa25.png)

You should see the following:
  
![](images/pa26.png)

You should see the following:
  
![](images/pa26_1.png)

You should see the following:
  
![](images/pa27.png)




Things you can now do now with this guide

☑️ Build a Power App with Custom Connectors
