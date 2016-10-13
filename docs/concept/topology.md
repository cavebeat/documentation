#Topology  

RetroShare builds a decentralized, distributed, serverless peer-to-peer network. 
Sounds like a lot of buzzwording nowadays, and is often misunderstood und 
interpreted differently. So let's explain what is what and why. 


![network types](../img/concept/networks.png "Network Types")  
Baran, Paul. [On Distributed Communication Networks](http://www.rand.org/pubs/research_memoranda/RM3420/RM3420-chapter1.html): 
I. Introduction to Distributed Communications Networks. Santa Monica, CA: RAND 
Corporation, 1964. http://www.rand.org/pubs/research_memoranda/RM3420.html. 
Also available in print form.


##Centralized Server
The first architecture of computer networks was a **client-server architecture**. A star topology 
with the server in the middle, and clients connected to it. That's an 
efficient way to run a network. Big Corporations run their service also 
in this fashion. Once you register an account with them, you have to stick 
with your data to them. It's not possible to move your account to a 
different provider. Communication is done always inside their network 
is barely going outside. It's a competitive the winner takes it all market 
which leads to monopoly's. 

![centralized network](../img/concept/centralized.png "Centralized Network")  

The downside of this network is, the central infrastructure is a single 
point of failure. If something happens with the server, all users are affected 
and the service is broken for all. 
Peer Pressure makes it hard to widthstand to not use these services.  
These Services are often free (as in free beer) but include hidden costs. 
User generated data is gathered all the time on each possible way.  
When a third party or the company wants to censor/filter/block parts of 
the communication they can do whenever they want with ease. 
They have the right to do this, because it's their property.  

##Decentralized / Federated Servers
E-Mail is a decentralized network by design. Everyone can run a Mail 
for it's own purpose. If a single Mail Server is offline for whatever 
reason, the other Mail Server's will still work and send mails. 
This **client-to-server-to-server-to-client architectures** is also 
referred as *Federated Network*. 

Besides e-mail, other known Social Networks with a federated structure 
are Diaspora and XMPP/Jabber. 

Users become a member of a server, and in principle only connect directly 
with their own server; these servers in turn are connected to each other 
to allow users in different server to interact with each other. 
This matches the **distributed network of centralized networks** description 
given above quite well.

In the case of e-mail, we can see, single persons still run their own 
personel mail servers, but most users stick to a few Mail Server Providers. 
This concentration renders the federation in fact useless and feels for the 
majority like a centralized network. The biggest mail provider has a market share 
of ~70% and growing. 
In fact e-Mail is nowadays a totally centralized network with all the 
downsides of centralized networks. 

![decentralized network](../img/concept/decentralized.png "decentralized Network") 

Small Mail Providers had also to shut down in the last years, for example 
the case of Lavabit. They did not comply with the government which ordered 
them to spy on their users. 
On the other hand, big Mail providers comply with these surveilance orders and 
hand over the infrastructure as a whole. Including all User Communications 
data. 

##Distributed / Decentralized  
One of the most for it's decentralization known networks is BitTorrent. 
It started with a torrent tracker, which in fact is a central server. 
This was a single point of failure. Someone had to operate and pay the server, 
and could be hold liable for the Users. Though Torrent Files are not 
containing any copyrighted material. 
This made it necessary to evolve BitTorrent into a Trackerless network 
where the work of the Tracker is **distributed** between all Torrent Nodes. 

All Users inside a Torrent Network may get connected with each other. 

![BitTorrent](../img/concept/torrent.gif "BitTorrent") 
Torrent Swarm with a central Torrent Tracker. 
