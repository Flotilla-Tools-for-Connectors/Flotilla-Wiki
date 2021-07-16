---
category: Meeting
meeting-series: Flotilla Friday
source-channel: CSC Zoom
recording-video: https://www.youtube.com/watch?v=qkg0Kmwj1kE
transcript: (to be updated)
date: 2021-06-18
---
# Flotilla Friday, 2021-06-18

## Topics

- Mapping II
- Metadata Syndication and Aggregation

## Intentions / Commitments

- add five connections between our org and others

## Notes

- Nora Bateson, data and context (0:34)
- "fat edges" (0:34)
- "intentional event planning" focused working session (1:24)
    - pre- and post-event intentions in sensemaking, harvesting, curation

## Metadata Syndication and Aggregation

### murmurations website

```json
{
  "name": "Federated Wiki",
  "url": "http://ward.asia.wiki.org",
  "tagline": "Dreams and ToDos",
  "mission": "We explore opportunities for innovation in the context of federated wiki as a participant in a \\\"pod\\\" of developers.",
  "nodeTypes": "network",
  "location": "Singapore",
  "logo": "http://ward.asia.wiki.org/favicon.png",
  "feed": "",
  "tags": "wiki",
  "lat": "",
  "lon": "",
  "updated": 1590069679
}
```

### microformats2 person

```json
{
  "items": [{ 
    "type": ["h-card"],
    "properties": {
      "photo": ["https://webfwd.org/content/about-experts/300.mitchellbaker/mentor_mbaker.jpg"],
      "name": ["Mitchell Baker"],
      "url": [
        "http://blog.lizardwrangler.com/",
        "https://twitter.com/MitchellBaker"
      ],
      "org": ["Mozilla Foundation"],
      "note": ["Mitchell is responsible for setting the direction and scope of the Mozilla Foundation and its activities."],
      "category": [
        "Strategy",
        "Leadership"
      ]
    }
  }]
}
```

### microformats2 event

```json
{
  "items": [{ 
    "type": ["h-event"],
    "properties": {
      "name": ["IndieWebCamp 2012"],
      "url": ["http://indiewebcamp.com/2012"],
      "start": ["2012-06-30"],
      "end": ["2012-07-01"],
      "location": [{
        "value": "Geoloqi",
        "type": ["h-card"],
        "properties": {
          "name": ["Geoloqi"],
          "org": ["Geoloqi"],
          "url": ["http://geoloqi.com/"],
          "street-address": ["920 SW 3rd Ave. Suite 400"],
          "locality": ["Portland"],
          "region": ["Oregon"]
        }
      }]
    }
  }]
}
```


## Resources

- [microformats2](http://microformats.org/wiki/microformats2)
- [Murmurations Network](https://murmurations.network/)
    - [Murmurations Network Fields and Schemas](https://github.com/MurmurationsNetwork/MurmurationsLibrary)
- [FOAF](http://www.foaf-project.org/)
- [XFN](http://www.gmpg.org/xfn/)
- [json2yaml](https://www.json2yaml.com/)
- [Reverse domain name notation](https://en.wikipedia.org/wiki/Reverse_domain_name_notation) (Wikipedia)
- [Citation Typing Ontology (CiTO)](http://www.sparontologies.net/ontologies/cito)
- [Rise of the STUPID Network](https://isen.com/stupid.html) (David Isenberg)
- [Is Your Company Having A Chocolate Conversation?](https://www.forbes.com/sites/brycehoffman/2015/02/20/is-your-company-having-a-chocolate-conversation/)

JSON Schema, JSON-LD, Schema.org
- [JSON-Schema.org](https://json-schema.org/)
- [JSON Schema Miscellaneous Examples](https://json-schema.org/learn/miscellaneous-examples.html)
- [JSON Schema, Schema\.org, JSON\-LD: What’s the Difference?](https://medium.com/@dashjoin/json-schema-schema-org-json-ld-whats-the-difference-e30d7315686a) (by Andreas Eberhart) (Medium)
- [JSON-LD.org](https://json-ld.org/)
- [JSON-LD Playground](https://json-ld.org/playground/)
- [Schema.org](https://schema.org/)
    - _"high emphasis on vocabulary that is likely to be consumed, rather than merely published."_
    - [Microdata](https://en.wikipedia.org/wiki/Microdata_(HTML))
    - [GS1 Web Vocabulary](https://www.gs1.org/voc/) - externally hosted extensions to Schema.org