# Labweek23
LabWeek23 is Protocol Labs' annual decentralized global conference. It features several days of curated events, all organized by the visionary teams in Protocol Labs Network to advance our mission — to drive breakthroughs in computing to push humanity forward.

Join us this November as we invite builders, thinkers, innovators and leaders to share research and participate in a dynamic program of engineering workshops, summits, tracks and conversations. Let's shape the future together.

We are using [this github repository](https://github.com/memser-spaceport/labweek23-events) and [LabWeek23 website](https://labweek.plnetwork.io/) to coordinate event listings. You can submit the events both using this repo as well as the [LabWeek23 UI](https://labweek.plnetwork.io/events/host).

# LabWeek23 Location & Date
LabWeek 2023 is taking place from November 13th, Monday to November 17th, Friday at Istanbul.

# Decentralized Conference
A decentralized conference is a series of related events happening around the same place and time, put on by a community. The goal is to enable people and groups to host their own events, loosely coordinating with the rest of the community.

Events can be run in many formats: roundtables, talks with slides, hack sessions, whiteboard sessions, or more. Anyone can submit subevents, just follow the instructions below!

# Events Listing Service
This repo contains all the events being planned and hosted at labweek23.  Today, this represents a template for labweek23. But in the future it can hold any events created on behalf of any such decentralized conferences.

## Submitting Events using GitHub Pull Requests (PRs)
We encourage you to submit your events via a pull request on github, to do so..

1. Please download a copy of the template from the path: ```events_template/sample_event.json```
2. Using the template please fill details related to your event and rename the file as ```<your-event-name>.json```. Make sure you provide a valid filename, because sometimes event names can contain special characters that are not valid for a filename, in that case provide an alternate filename that will be valid, readable and resembles your event name.
3. Create a branch like ```event-<your-event-filename>```
3. Place the finished file in the path as mentioned: ```/events/<your-event-file-name>.json```
4. Create a PR from this branch to 'main' branch
5. The LabWeek event planning team will review and merge your event into the [LabWeek23 website](https://labweek.plnetwork.io/schedule).

## Important points before raising Pull Request
1. In the events template json file, fields commented as #mandatory are required fields for your event to be approved.
2. After the pull request is approved, please allow a maximum of 10 minutes for your events to be reflected in labweek schedule.
3. If you don't have details for the non-mandatory fields, you may not not include those field in your json instead of providing empty values.
4. For fields like event logo and host logo, make sure you host your images are in 1:1 ratio with maximum of 4MB 
5. Host the images in a publicly accessible place and provide the url for the same. We recommend checking out IPFS-based solutions like web3.storage.

## Editing Events
1.  You've already created your event but want to add or change details, make appropriate changes and raise another pull request to 'main' branch preferrably using the same branch name used when it was created.
2.  The LabWeek event planning team will review and merge your changes.
3.  Alternatively, you can also use the [LabWeek23 web UI](https://labweek.plnetwork.io/) to modify & update the event details.
