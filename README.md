dailyblockchain
==

Simple page with instructions how to get bitcoin-qt client up to speed

### How to start bitcoin-qt in hours instead of days 

```
Below instructions are for Linux users        
If someone can test this on Windows or Mac and send me pull request to update the notes        
I will be very happy to do it         
```
* Install the bitcoin-qt qlient
* Start it and stop it
* Download the most fresh archive ( blockchain-dd-mm-yyy.zip )from [here](http://sourceforge.net/projects/dailyblockchain/files) It might take an hour or two depends on your connection
* Locate your bitcoin directory For linux it is ~/.bitcoin
* cd into it and:
    * remove everything from folder ** block ** 
    * and remove folders **chainstate, database** 
* Unzip the archive into ~/.bitcoin/block
* Start your client using command ** bitcoin-qt -reindex ** This might also take an hour or two depends on your CPU
* Once your client finish reindexing it will download quickly the remaining delta and you will be ready to go :-) 


### Found this helpful :-) Send some Satoshis here:

** 1EVH1zuB9U781fNp8YJsxhheRY5UFrB3Li ** 
