---

publish: true
icon: FasCampground
tags:
  - Category/Settlement
Community-Size: Outpost
Alignment: Chaotic Evil
Government: Autocracy
type: Settlement
politics: Lordship
leader: "[[Kantora]]"
guildsgroups: 
region:
  - This area
  - Of this area
size: Small camp
population: 0
commonraces:
  - Humans
  - Elves
religion: 
exports: 
imports:
---



> [!infobox]
> # `=this.file.name`
> ![[MapPlaceholder.png|cover hsmall]]
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Size | `=this.size` |
> Region | `=this.region` |
> ###### Travel (`=[[Travel Calculator]].HoursPerDay` hrs per day)
> ###### [[Travel Calculator]]  / [[Exhaustion]]:  `=[[Travel Calculator]].ExhaustionLevel`
> Destination |  Travel Days  |
> ---|---|
> [[Voonlar]] | 🕓: `VIEW[round((88* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
> ###### Politics
> Type |  Stat |
> ---|---|
> Govt Type | `=this.politics` |
> Ruler | `=this.leader` |
> Defense | `=this.defences` |
> ###### Society
> Type |  Stat |
> ---|---|
> Population | `=this.population` |
> Races | `=this.commonraces` |
> Temples | `=this.religion`  |
> ###### Commerce
> Type |  Stat |
> ---|---|
> Exports | `=this.exports` |
> Imports | `=this.imports` |
> ###### Organizations
> Type |  Stat |
> ---|---|
> ```dataview
table WITHOUT ID link(file.name) AS "Group", link(Leader) AS "Leader"
where contains( PrimaryHome, this.file.name)


# `=this.file.name`
## Overview
Placeholder


### Placeholder Map
![[MapPlaceholder.png|Placeholder Map]]

### Placeholder Picture
![[ImagePlaceholder.png|Placeholder Picture]]

Placeholder

## Notable NPCs
Placeholder

## Profile
Placeholder

## Story
Placeholder

## Points of Interest
Placeholder

## Valuables
Placeholder

## Internal Relationships
Placeholder

## Outward Relationships
Placeholder

## Background
Placeholder

## Additional Details
Placeholder

