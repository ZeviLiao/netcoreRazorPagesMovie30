in mac env  


ref:  

sample code / steps

https://github.com/aspnet/AspNetCore.Docs/tree/master/aspnetcore/tutorials/razor-pages/razor-pages-start/sample/RazorPagesMovie30

https://docs.microsoft.com/en-us/aspnet/core/tutorials/razor-pages/model?ranMID=24542&ranEAID=je6NUbpObpQ&ranSiteID=je6NUbpObpQ-WBbzff5O6TzouTL.4DmK9g&epi=je6NUbpObpQ-WBbzff5O6TzouTL.4DmK9g&irgwc=1&OCID=AID2000142_aff_7593_1243925&tduid=(ir__19o0xv6sm9kftwrlkk0sohzx0e2xlui11dbm3xtb00)(7593)(1243925)(je6NUbpObpQ-WBbzff5O6TzouTL.4DmK9g)()&irclickid=_19o0xv6sm9kftwrlkk0sohzx0e2xlui11dbm3xtb00&view=aspnetcore-3.1&tabs=visual-studio


migration - check 'Visual Studio for Mac' tab
Add EF tools
```
dotnet tool install --global dotnet-ef
```


```
dotnet ef migrations add InitialCreate
dotnet ef database update
```



mssql for mac by docker  
https://dotblogs.com.tw/explooosion/2018/11/10/212333
