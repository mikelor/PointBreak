# PointBreak
Point of Interest client app for learning Blazor Web Assembly. I won't be exploring Blazor Server implementations, becuase I don't find them as interesting.
PointBreak will be a simple client that tracks points of interest, similar to how you can "Save" places on Google Maps. 

## Some Resources I'm Looking Into
* [2020.05.13 - Building a progressive web app with Blazor](https://devblogs.microsoft.com/visualstudio/building-a-progressive-web-app-with-blazor/)
* [What's behind the Blazor Hype](https://stackoverflow.blog/2020/02/26/whats-behind-the-hype-about-blazor/)
* [Best Practices Discussion on Stack Overflow](https://stackoverflow.com/questions/59538859/blazor-project-structure-best-practices)
* [Blazor MVVM Blog Posting](https://itnext.io/a-simple-mvvm-implementation-in-client-side-blazor-8c875c365435)
* [The Net Learner App MVC/Razor/Blazor (Server) and JavaScript Front Ends](https://github.com/shahedc/NetLearnerApp)
* [A Collection of Awesome Blazor Resources](https://github.com/AdrienTorris/awesome-blazor)

## Recent Presentations
* [Xamarin Assemble - Brandon Minnik's Creating Xamarin.Forms in C#](https://codetraveler.io/assemble-csharp-ui/)
* [2020-07-13 - Blazor + Xamarin Code Sharing / .Net Virtual User Group](https://www.youtube.com/watch?v=5P_rub2a4Eo&list=PL1rZQsJPBU2S4_ZjpE20DJcPT8okkXPja&index=2&t=4s)

## Helpful Software for Inner Loop Development
* [LiveSharp - Best hot-reload and live debugging for C# projects](https://www.livesharp.net/)

## Project Packages
### GeoLocation
Since .Net Core 3, does not have a good geolocation class library (whereas .Net Framework has System.Devices.Location), I'm going to be leverage [Scott Shluer's](https://github.com/scottschluer/) [Geolocation](https://github.com/scottschluer/geolocation) library/nuget package.

Time to go.
