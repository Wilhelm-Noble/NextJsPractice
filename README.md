notes to self, 

learn

valtios
radix
rive
asdf
configured wsl
ubuntu/linux commands check
swr hook


practice codebase tomorrow
wasnt able to practice, but well thats why its a weekend lol...

need to update stuff
study the valtio already - done
utilize obsidian


while not using obisdian here we will put our docu for next


first part 

REACT Server Components 


Server vs Client Components
they arent next js features, they are react and next just utilizes them differently 

Next js is thhe most robust for server componentts 

TLDR, dont need to use useEffect, direct call the API, makes things easier

the reason why you don't have to is beacuase next can render on the server side as well, mean that it doesnt have to run on the client/browser side which can be used to handle data


to handle errors in server components, just make an error file and a loading file 


server 
        -page.tsx
        -error.tx

every code in the server will not be seem im the client side 

benefits of server components
 -loads faster
 -secruity cuz its not being seen on the client 
 -bundle size will be processed only in the server


 so why not make all things server compoenets?

 there is no interactivy in server components
 evts will not be availabel there
 can't use useEffect,useState and any hook


WTF Do These Even Mean- web dev simplified


Types of rendering 
SSR 
CSR
SSG
ISR



"
Most important things one needs to know are:

Client is just the browser

Server is a computer that serves HTML, CSS, and JS files to the browser(a server can do a lot more, but we are talking about web server)

Browsers were designed to run HTML, CSS and JS code, which were intended as a way to beautify the website

But people realised the power of JS in this, so now we got JS-based apps in CSR, where JS does everything you need in the application, and only requesting business data(basically the data they can't store in your PC because it's valuable and/or large data)

But then, people realised that this doesn't benefit clients who have their PC cooking up the room with all the JS it's running, so they made it so that the entire logic is handled in the web server itself, and what we get in the end is just enough markup, styles and code to present the website, and everything else related to the application is done by the server

And anything else is clever techniques in between these two
"  - analogy of a random youtuber


How this renders influence your build 


CSR - Client  Side Rendering

 this is a lot of how sites is used to makw back in the day

 build, all is made on the build side and their is barely any service run on the server and is mostly on the client

SSR - Server Side Rendering
  kinda same as CSR, but when you get a request on the server it will load all the HTML content before it gets sent to the client side, 
  
  more work gets done on the server side rather than the client side

SSG - Static Site Generation

    We are now focusing on build side and most of the work is done there, everything is being loaded all at once, so the server and client side doesnt work on this much

    this feels like how games are loading


ISR = Incremental Static Regeneration

    combines SSG with SSR, in which you will have faster load times since eveything is loaded and you will have dynamic content cuz of the server side rendering

    just means that some pages are SSG, and those who needs to be on SRR will be loaded ther



need to setup the stuff already 



