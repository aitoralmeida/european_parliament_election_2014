# Tweets for the campaign period of the 2014 European Parliament election
This dataset contains the tweets for the campaign period (16th to 23th of April) of the 2014 European Parliament election (https://en.wikipedia.org/wiki/European_Parliament_election,_2014). 

The tweets were captured by following the mentions to a set of party Twitter accounts, selected based on the results of the previous election (check the parties.json file for a complete list of the political parties included in the study). The dataset contais a total of 47,761 tweets.

## Files

Four different files are included in the dataset:
* european_parliament.2014.txt: the captured tweets.
* locations.json: includes a city/country mapping.
* parties.json: contains information about the political parties taken into account for the study (Party name, twitter id, location, european group)
* parties_ids.json: includes a twitter id/party name mapping.

### european_parliament_2014.txt format

The file is formatted with a tweet per line, each line with the following fields separated by commas:

```
tweet_id, username, user_id, md5_hash
```

The tweet_id and the username can be used to recover the tweet content, and the md5 hex hash to validate the tweet text. To comply with the Twitter TOS we do not provide the content ourselves.

## Reference

Please, use the following reference if you use this dataset for your research:

Bilbao-Jayo, A., & Almeida, A. (2018). Automatic political discourse analysis with multi-scale convolutional neural networks and contextual data. International Journal of Distributed Sensor Networks, 14(11), 1550147718811827.

Aitor Almeida, Juan Sixto, Oscar Peña, Braulio Gomez, Guillem Martí. 
Tweets for the campaign period of the 2014 European Parliament election. 
URL: https://github.com/aitoralmeida/european_parliament_election_2014/

## Other datasets

Take a look at our other datasets:
* City4Age Behaviour dataset: https://zenodo.org/record/2602652#.XJtz26SkGUl
* Spanish 3B words Word2Vec Embeddings: https://github.com/aitoralmeida/spanish_word2vec
*  Political party and candidate tweets for the campaign period of the 2015 Spanish general election: https://github.com/aitoralmeida/spanish_general_election_2015
*  Political party and candidate tweets for the campaign period of the 2016 Spanish general election: https://github.com/aitoralmeida/spanish_general_election_2016



