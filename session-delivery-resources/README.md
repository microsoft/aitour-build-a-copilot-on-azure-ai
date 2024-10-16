## How To Use This

Welcome!

We're glad you are here and look forward to your delivery of this amazing content. As an experienced presenter, we know you know HOW to present so this guide will focus on WHAT you need to present. It will provide you a full run-through of the presentation created by the workshop content creation team.

Along with the video of the presentation, this document will link to all the assets you need to successfully present including PowerPoint slides, demo instructions & code.

1. Read document in its entirety.
2. Watch the video presentation.
3. Ask questions of the Lead Presenter.


## File Summary

| Resources | Links | Description |
|:---|:---|:---|
| Presentation Slides   | [PPT](https://aka.ms/AArxx4b) | Powerpoint deck for speaker intro |
| Presentation Video    | [Video](https://aka.ms/AAse6pr)| Recorded walkthrough of speaker deck   |
| Presentation Guidance | [Video](https://aka.ms/AAseehk) | Deck walkthrough with speaker tips |
| Contoso Outdoors Demo | [Video](https://aka.ms/AAsdlon) | Application Scenario walkthrough |
| Workshop Walkthrough  | [Video](https://aka.ms/AAse7mb) | Step-by-Step Walkthrough of workshop |
| | | |


The following resources are intended for a presenter to learn and deliver the session.


## Overview

This document is divided in to the following sections:

* [Workshop Format](#workshop-format)
* [Pre-Deployment](#pre-deployment)
* [Presenter Preparation](#presenter-preparation)
* [Proctor Preparation](#proctor-preparation)
* [Workshop Delivery](#workshop-delivery)

### Workshop Format

This is a 75-minute workshop. Participants will receive a link to the Skillable Lab that has an Azure subscription with _pre-provisioned resources_ as described below. 

| Start Time        | Description 
--------------|-------------
00:00 | Workshop session begins - introduce speaker, proctors
02:00 | Presenter delivers intro slides
10:00 | Participants begin following self-paced walkthrough
70:00 | Presenter delivers wrap-up slides
75:00 | Workshop ends

> [!TIP]
> Attendees will need to fork a sample repo and launch GitHub Codespaces to get started. _The codespaces setup can take a few minutes. Consider having attendees complete this step of the workshop before speaker delivers intro slides. This way, their Codespaces session is ready when speaker finishes, and they can dive in_.

Role | How many | What they do
-----|----------|--------------
Presenters | 1 | Delivers slide content, answers questions for the whole room
Proctors |2 | With Presenter, assists participants during the self-guided phase
| Participants | 50-200 |Listen to the presenter and follow instructions during the self-guided phase

## Pre-Deployment 

This workshop requires a number of Azure and AI resources to be pre-deployed before we can begin development. The [Contoso Chat application architecture](https://github.com/Azure-Samples/contoso-chat) gives us a sense of the resources involved. 

### Skillable-based labs

If you are using Skillable for your lab, each participant will have a temporary Azure subscription to use with all of the necessary resources pre-deployed. 

### Self-provisioned labs

If you are provisioning labs yourself, you will need to provide one Azure subscription per participant. Follow the directions in [this self-provision guide](https://github.com/Azure-Samples/contoso-chat/blob/main/docs/workshop/in-person-starts/00-self-preprovision.md)

## Presenter preparation

1. The [slides](https://aka.ms/AArxx4b) have presenter notes in each part of the session.
1. You will be provided a Lab Link to share with the participants. _This is the link that will each student will use to access the lab environment._
1. Download the slides to your laptop for presenting. _The slides have an embedded demo video you can save separately if needed_.
1. Edit Slide 5 to include the Lab Link **in a large font**. Leave this slide visible as participants walk in.
1. Edit Slide 6 to provide the photo, name, and LinkedIn profile of the presenter and (optionally) proctors.

Presenters act as additional proctors during the self-guided phase, and should follow the proctor preparation steps below as well.

## Proctor preparation

1. Familiarize yourself with the resources listed at the end of "2-Instructions.md".
1. Use the **WRK550 Tech Check link** you have been provided with to launch the student lab experience. Run through all the steps in the lab and familiarize yourself with the content.
1. Review the **WRK550** Walkthrough video shared with you to get a sense of the pacing and tips for troubleshooting key areas.

## Workshop delivery

This lab is intended to be delivered by a Presenter who will show the slides and demos and answer questions for the class, supported by one or more Proctors who provide individual assistance during
the lab. 

The workshop will be delivered by the Presenter. Check out the  for the overview.

by one or more Proctors who will provide individual assistant to participants during the lab.

### Launching the lab environment

When this lab is delivered during AI Tour, the [Skillable](https://docs.skillable.com/) platform provides a temporary Azure
account for each participant to use. After logging in, the environment provides a 
[Lab Manual](./LAB_MANUAL.md), the launching point for
the lab content and the source of individualized Azure credentials.

Depending on your role in the workshop, you will launch the Skillable lab environment using a dedicated link.

* **[Lab authors](https://labondemand.com/LabProfile/170937)**: This link is used by authors and maintainers of the lab content.
  You must log in using your Microsoft corporate credentials to access this link.
  **Note**: the lab environment will appear in 2-3 minutes,
  but you must wait up to 30 minutes more for Azure resources to deploy to the temporary Azure account
  before running the workshop.
  Log into the [Azure portal](https://portal.azure.com) using the credentials in the Lab Manual to monitor progress.  
* **Presenters and Proctors**: Launch Lab WRK550 from the Tech Check portal. (This link will be provided by your content owner 1-2
  weeks before lab events.) Use this link to test the lab using an environment identical to that provded to lab participants.
* **Partcipants**. Use the participant link provided by your lab presenter. Note: participant lab environments will only be
  active 15 minutes before through 30 minutes after the scheduled lab time.


