# docker-agent-two

if we want seperate docker container for both of my stages in that case 
have to go configure option new containerperStage 
now we are going to create new container for each and every stage

Beauty of seperate container we can build seperate enviornment based on what stage we have  
Example -In realtime senario not using same agent for both build and deploy as well as test activities 
we keep always seperate machine for build activities seperate machine for test activities and seperate machine for test enviornment
like unit test, selenum test etc 
