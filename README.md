# Reading

An overview of my web reading setup.

# Stack

```mermaid
  graph TD;
      me[zdwolfe] -- read articles --> feedly;
      me -- read/write notes --> ever[evernote];
      me -- save links for later --> insta[instapaper];
      
      substack --> nEmail[newsletter gmail];
      nEmail -- forwarding filter --> feedly;
      
      medium -- sync bookmark --> iftttMedium[IFTTT Medium];
      iftttMedium -- save for later --> feedly;
      
      insta -- save for later --> iftttInsta[IFTTT Instapaper];
      iftttInsta -- sync saved --> feedly;
      
      feedly -- highlight --> iftttFeedlyH[IFTTT Feedly];
      iftttFeedlyH -- sync highlights --> ever;      
```

# References
1. https://refactoring.fm/p/how-to-read-online?utm_source=url
1. https://refactoring.fm/p/my-tools?utm_source=url
1. https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/
1. https://mermaid-js.github.io/mermaid
