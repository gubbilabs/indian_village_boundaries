description:  Contributing to Indian Village Boundaries mapping project.

# Contributing to Indian Village Boundaries
We are open to contributions. Please read [DataMeet Community Code of Conduct](http://datameet.org/wiki/guidelines:datameet-community-code-of-conduct) before you start and also read our [license to familiarize yourself with ODBl](http://opendatacommons.org/licenses/odbl/) under which all our and your contributions will be distributed.

## Referencing the Source
For any change you make please link to a source. We prefer goverment websites or websites/apps like [OpenStreeMap](https://www.openstreetmap.org/
) who share the data under ODBl. You can add them to the state specific .md file, so they due credit. If they are generic then you can add it to the reference.md file.

## Format
All the village boundaries are available in geojson (WGS84, EPSG4326) format.

## Attributes
Each boundary will have the following attributes

- NAME : Name of the Village/Town as per census
- TYPE: Village or Town
- SUB_DISTRICT: Sub District name as per census
- DISTRICT : District name as per census
- STATE: State or UT name as per census
- CENSUS_CODE_2001: Code as per 2001 census, its a concatination of State Code, District Code, Sub-District Code, Village Code 2001.
- CENSUS_CODE_2011: Code as per 2011 census, its a concatination of State Code, District Code, Sub-District Code, Village Code 2001.

## How to contribute
- Fork the project
- Make changes
- Send a pull request

## Acceptance procedure
- One of the core volunteer will cross-check/validate with the references you add to pull request
- If everything is okay then will accept the pull request

## Adding new attribute or changing the value
Before adding any new attribute, discuss on the list. If you have any corrections to the value of attribute source it from an official goverment site or Census of India. Without reference we wont add.

## Adding new state
Refer the availabe state map files online. Generally state revenue department. If they are not availabe online, request through RTI. Digitize it. Add attributes and send a pull request. Before starting a new state put an [issue on the issue tracker](https://github.com/datameet/indian_village_boundaries/issues), so other know you are working on it. Also check the status on the README file.

## Reporting error
If you have any issues with the maps, please report them on the github repository. Give details and reference. One of us will pick it up.

 <a href="https://github.com/datameet/indian_village_boundaries/issues/new"><button class="btn btn-primary" type="submit">Report Issue</button></a>
<a href="https://github.com/datameet/indian_village_boundaries/issues"><button class="btn btn-primary" type="submit">Active Issues</button></a>

## Anything else
Start an [issue on the issue tracker](https://github.com/datameet/indian_village_boundaries/issues) or email on the list.

