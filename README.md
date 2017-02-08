# Tweets for the campaign period of the 2014 European Parliament election
This dataset contains the tweets for the campaign period (16th to 23th of April) of the 2014 European Parliament election (https://en.wikipedia.org/wiki/European_Parliament_election,_2014). 

The tweets were captured by following the mentions to a set of XXXX party Twitter accounts, selected based on the results of the previous election (check the parties.json file for a complete list of the political parties included in the study).

## Files

Three different files are included in the dataset:
* parties.json: contains information about the political parties taken into account (Party name, twitter id, location, european group)
* locations.json: includes a city/country mapping.
* european_parliament.2014.txt: the captured tweets.

### european_parliament.2014.txt format

The file is formatted with a tweet per line, each line with the following fields separated by commas:

```
tweet_id, username, md5_hash
```

The tweet_id and the username can be used to recover the tweet content, and the md5 hex hash to validate the tweet text. To comply with the Twitter TOS we do not provide the content ourselves.

## Reference

Please, use the following reference if you use this dataset for your research:

Aitor Almeida, Juan Sixto, Oscar Peña. Braulio Gomez, Guillem Martí 
Tweets for the campaign period of the 2014 European Parliament election. 
URL: https://github.com/aitoralmeida/european_parliament_election_2014/

## Other datasets

Take a look at our other datasets:
*  Political party and candidate tweets for the campaign period of the 2015 Spanish general election: https://github.com/aitoralmeida/spanish_general_election_2015
*  Political party and candidate tweets for the campaign period of the 2016 Spanish general election: https://github.com/aitoralmeida/spanish_general_election_2016



