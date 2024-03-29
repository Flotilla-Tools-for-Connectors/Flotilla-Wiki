# Meeting Index

## About This Page

This page is used to automatically show indexes of all the Meeting pages in the wiki (or at least, all the pages that have metadata embedded).

To make it work, it uses the [[YAML Front Matter]] in the wiki pages, and a plugin for Obsidian called "Dataview".  Only the notes with `category` set to "Meeting" will show up here.

In Obsidian, view the page in **Preview** mode to see the indexes. If you are not seeing the indexes, please install the community plugin called "Dataview", enable the plugin, and re-open the vault.

If you see text like `dataview table rows.date` etc., your Massive Wiki viewer does not yet support the Dataview plugin.

## Meetings by Date (newest first)

```dataview
table
rows.date as "Date",
rows.meeting-series as "Meeting Series",
rows.file.link as "Meeting Notes",
rows.recording-video as "Video Link",
rows.file.size as "File Size"
where category = "Meeting"
sort date desc
group by file.path
```


## Meetings by Series (alpha) then Date (newest first)

```dataview
table
rows.meeting-series as "Meeting Series",
rows.date as "Date",
rows.file.link as "Meeting Notes",
rows.recording-video as "Video Link",
rows.file.size as "File Size"
where category = "Meeting"
sort meeting-series asc, date desc
group by file.path
```

## Manually Indexed Meetings

meeting notes here: [Flotilla Wiki/Meetings](https://github.com/Flotilla-Tools-for-Connectors/Flotilla-Wiki/tree/main/Meetings)

## 2021-10-22

https://www.youtube.com/watch?v=FUgyKf1yZsI

- Sync to/from HackMD
- Wendy's EverWise maps
- Vincent's The Press Conference mapping - Kumu, Airtable

## 2021-10-29

https://www.youtube.com/watch?v=VusZ9JpJnrA

* Pete's [OGM Thursday Call - 2021-10-28](https://ogm-thursday-2021-10-28.openglobalmind.com/) "hypertext knowledge workbook"
* Facebook's "Metaverse"
* Processing video meeting recordings

## 2021-11-05

https://www.youtube.com/watch?v=MWSAMr9_QD4

* Scopes, contexts, namespaces
* Vincent's physical metaphors for information spaces
* Vincent's grid of information space metaphors
* Search axes

## 2021-11-12

https://www.youtube.com/watch?v=8k4CCVUNUVs

* Interfaces to concepts
* Mind maps -> concept maps -> topic maps
* Upper ontologies



