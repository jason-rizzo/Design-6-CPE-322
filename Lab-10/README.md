# CPE 322 - Lab 10 
## Blockchain 
--- 
### Part 1: SnakeCoin 

This lab began by running the file `hash_value.py` twice and comparing the results it provides. The file hashed the first 3 numerical values the same both times, but the other 3 values were hashed differently, indicating the presence of randomization in the hashing process for object types. 

![Hash Comparison](hashvalue.png) 

The next file tested was `snakecoin.py`, a very simple implementation of a blockchain. Running the file produces a simple blockchain, in which 20 blocks are mined and their hashes are printed. 

![SnakeCoin Results](snakecoin.png) 

The next iteration of the SnakeCoin project ran through the file `snakecoin-server-full-code.py`, which runs a Flask server when executed. This server allowed blocks to be mined by accessing its "mine" page. 

![Starting SnakeCoin Server](snakecoin-server.png) 

Another terminal was opened, and a block was mined on it. It is notable that the "curl" command was rejected by the server from the Windows terminal, so an Msys2 terminal was used instead, which did work properly, and the blockchain was initialized with a block mined. 

![Mining a Block](mine.png) 

Blocks could also be mined by accessing the page through a browser directly. 

![MIning a Block in the Browser](mineresult.png) 

### Part 2: Python Blockchain App 

The second portion of this lab focused on a more specific application of blockchain running on two different servers in the terminal. 

The necessary Python files were cloned using the "git clone" command, which was successful. 

![Cloning the App](cloneapp.png) 

The app was then executed from the cloned folder, with two files being used. `node_server.py` was executed first to host the blockchain, then `run_app.py` was executed to host the content sharing application server that interacted with the blockchain. 

![Running the Node Server](nodeserver.png) 

![Running the App](runapp.png) 

