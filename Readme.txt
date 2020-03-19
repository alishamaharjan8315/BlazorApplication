Tutorial Link: https://www.youtube.com/playlist?list=PL6n9fhu94yhVowClAs8-6nYnfsOTma14P
1. Blazor 
	Blazor is a free and open-source web framework that enables developers to create web apps using C# and HTML.
	Blazor can run C# code on web browsers using Web Assembly.
2. Blazor Hosting Models
   a. Blazor Server
        The application is executed on the server. SignalR connection is established between client and server.
		Pros
		i. The application loads much faster.
		ii. Can take full advantage of server capabilities
		Cons
		i. Active server connection is required.
		ii. Asp.net core server is required.
		iii. Scalability can be a challenge. Supporting multiple clients by server. Although We can use azure signalR service.
   b. Blazor WebAssembly (Download Blazor WebAssembly template)(Also known as Client Side Hosting Model)
		The application runs directly in the browser on WebAssembly.
		So, everything the application needs i.e the compiled application code itself,
		it's dependencies and the .NET runtime are downloaded to the browser. 
		Pros
		i. Active server connection is not required.
		ii. Can be hosted on our own server, cloud, azure or CDN
		iii. Client resources and capabilities are used.
		Cons
		i. The very first request usually takes longer.
		ii. Restricted to the capabilities of browser.
		iii. Rerenders whole page.
		
		

