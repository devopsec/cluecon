## DJ Flo!

DJ Flo is a live attendent that can take a song and remix it.  
This quick demo shows how one could use an SignalWire AI assistant to live remix a song.  
The demo uses SignalWire serverless SWML to create the AI assistant ([flo.swml](flo.swml)).  

## Demo

Call 13135474829 and DJ Flo will ask you what song you want to remix.  
Currently DJ Flo has a few songs that she can remix:

Tiktok - by Kesha  
Blank Space - by Taylor Swift  
Don't Start Now - by Dua Lipa  

She can go the next song by saying "next".

Telling Flo to "stop" will end the call.

## Future

One could utilize this same technique to remix songs in realtime from a data source.  
Flo would need to be updated to query the song from the data source and use a local LLM to remix the song.  
The demo was created by using the [Fadr](https://fadr.com/) LLM to process the music files and then served on a webserver that the AI agent streamed.

