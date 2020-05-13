# Curl Command
This command is used to communicate data to and from the server. By using this command we can communicate to the server. 
####  ```Curl "https://en.wikipedia.org/wiki/Ecosystem"```
In this way we will reterive  content from particular url.
# Transform(tr)
This command is used to modify and perform different operations like inserting, deleting, replacing,transforming on strings.
#### ```tr ' ' '\12' < data.txt```
The above command will replace the space in data.txt with '\12' ASCI Value.
#### ```tr ' ' '\12' < data.txt | sort```
Here we are using pipe(|) this is used to transform output of one command to input of other command. In above example the output of space replacement command is send to sort in which it will sort the resultant data.
#### ```tr ' ' '\12' < data.txt | sort | uniq -c```
This command is used to count the number of unique words present in file after sorting.
#### ```tr ' ' '\12' < data.txt | sort | uniq -c | sort -nr```
This command is used to sort the result of unique words from above command.
#### ```tr ' ' '\12' < data.txt | sort | uniq -c | sort -nr > result.txt```
This command is used to transfer resultant data to result.txt file.

