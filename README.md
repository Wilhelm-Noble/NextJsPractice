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
