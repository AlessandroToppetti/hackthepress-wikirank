A tool to rank reliability of news articles by using the frequency of Wikipedia citations from different sources on a topic as a proxy for reliability.

## How the tool works

| Resource  | Description of the action |
| --- | --- |
| News article  | The user provides a news article for the tool to analyse. |
| Topic  | Perform keyword extraction to define the topic of the article. |
| Wikidata  | User defines the Wikidata item for the topic based on suggestions, the Wikidata item which links to Wikipedia articles  |
| Wikidata statements  | The tool uses Wikidata statements (e.g instance of and occupation to understand the context of the topic to form a Domain. |
| Wikipedia references  | Count the number of citations from each news source in Wikipedia articles in the ‘Domain’ to find the most used reference sources.  |