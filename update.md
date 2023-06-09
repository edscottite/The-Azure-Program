# Developer Notes:

04/04/23 

> UI Framework + Design, command integration ( File Opening, Network Response, Intro the Administration settings and Local Device Information Capture. I failed on integrating a command output for the graph on which displays the traffic through a graph model. ( I was tired at the time and my brain had started to hurt along with starting to become frustrated with the issues beforehnd. 

12/04/23

> Created the document and repository, no code edits. 

13/04/23

> Designed the basis of the Engine architecture, first thought on how the traffic data model will be represented ( A∈ = MS  - Not set on this idea as I'm unsure of its stability. Too many quaries will cause network disruption. 

> Structure and operational features of the graph display have been established, with traffic being depicted through an average of the refresh rate (measured in milliseconds), thus creating a real-time display effect. However, integration with the engine has yet to be done.

14/04/23 

> Currently overviewing the stability and security. While stable, it's sending a query to the local network every 500 miliseconds. The IT people at school would be able to detect this easily and would regard this as a security threat.  I'm brainstorming on ideas on how I could minimise this ( Randomise the quaries by 0 - 500 miliseconds, the requests being seen as "performance issues".

> Due to being unsure as to how they're surfing the network, I need to be precise on how I'm doing this. The program cannot be ran for over a minute, it would cause suspicion ( Perhaps 30seconds alone would cause suspicion ). Along with the issue of that they have full control over each device and could easily identify what device is causing the outrage as the traffic would be essentially scambled ( for that device ). 

> Thinking on it now, they can see what and who logs into what for each chromebook.

17/04/23

> Designed the logo along with implementing it as apart of the Docks. 

> Integrated Windows and MacoS, latest version ( Along with Big Sur compatability).

> The security concern won't appear as an issue upon the Administratives devices ( I hope )
> Still iffy on the UI and name. Name has went from Remenue -> Scift -> Azure. 

> Most functions/commands are completed. Files having been made exeuctable on both MacOS and Windows has yet to be done. 

09/06/2023

> Encountered various issues relating to the JAVA pathway on my Mac, pending resolve.
