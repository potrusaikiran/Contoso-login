# ContosoUniversity and sample azure ad login application

** Before running solutions ** <br />
Make sure the vm's are having applicationstatus monitor installed.
# ContosoUniversity
 Please update the connectionstring in web.config and instumentation Key in ApplicationInsights.config
 <br />
Note: <br />
      1. The solution uses code first approach if we are providing valid connection string it creates database and tables. <br />
      2. We can find Instrumentation key in Application Insights under properties section in azure. <br />
# Login Application
 Please update the ConnectionString,ClientId,ClientSecret,Domain,TenantId in web.confg and instumentation Key in ApplicationInsights.config 
 <br />
 Note:  <br />
       1. The solution uses code first approach if we are providing valid connection string it creates database and tables. <br />
       2. Create an application registry with proper redirect urls and take values of ClientId,ClientSecret are available under application           registry. <br />
       3. Domain is Active directory domain name and TenantId is directoryId
