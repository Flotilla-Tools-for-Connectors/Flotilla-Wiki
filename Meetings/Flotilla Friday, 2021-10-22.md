# Flotilla Friday, 2021-10-22

## Topics

- Radicle
- Vincent's back from Europe!
- FedWiki Phototelling
- firming up the Flotilla infrastructure and organization
    - knowing what we want to do
    - having better web endpoints
        - hackmd
        - website
        - manifesto
- Closing Some Flotilla Open Loops
- Netlify CMS?
- Project Clambake Maps

## Project Clambake Maps



## Where to collaborate

- one or several HackMD pages? a massive wiki?
- should allow editing from a phone
- Git on phone:
    - Git Journal
    - Working Copy
    - this (Hackmd on phone?) works fine! - vincent

### Resolved

- Massive Wiki for persistent, async collaboration
- HackMD "Flotilla Friday" for realtime collaboration during meetings
- HackMD "Flotilla Dashboard" for easy-to-use/find Flotilla
    - probably not the native HackMD GitHub sync
    - probably an API sync from HackMD to whatever endpoint - Google Docs, Trove, Massive Wiki



## Sync to/from HackMD

Options

- native HackMD GitHub sync
    - complex because of the way HackMD wants to be flexible about which HackMD version gets synced
- HackMD API-based sync, with a microservice we find/write
- Hedgedoc modifications to make GitHub sync more reasonable
- shortest path may be to control sync from tools we control (MassiveWiki, Trove)
- Most abstract idea: sync service
    - Each "source" should be able to provide snapshots and events, and absorb events from other sources (even if only in event form.)

## Some JavaScript Diagramming Libraries

- https://www.npmtrends.com/diagram-js-vs-gojs-vs-jointjs-vs-jsplumb-vs-mxgraph
- https://www.npmtrends.com/d3.js-vs-gojs-vs-jointjs-vs-jsplumb-vs-mxgraph
- https://www.npmtrends.com/flowchart.js-vs-jointjs-vs-mermaid