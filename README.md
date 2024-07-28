# Automated Event Creation for the Company

## Table of Contents

- [Purpose](https://www.notion.so/Socal-media-20c1863f243948b6ac71ed311195a29d?pvs=21)
- [Original Working Model](https://www.notion.so/Socal-media-20c1863f243948b6ac71ed311195a29d?pvs=21)
- [PowerAutomate Flow](https://www.notion.so/Socal-media-20c1863f243948b6ac71ed311195a29d?pvs=21)
- [Installation](https://www.notion.so/Socal-media-20c1863f243948b6ac71ed311195a29d?pvs=21)
- [Usage](https://www.notion.so/Socal-media-20c1863f243948b6ac71ed311195a29d?pvs=21)

## Purpose

The purpose of this PowerAutomate flow is to automate repetitive activities in companies, especially when information needs to be transmitted during the creation of events on the Teams platform.

## Original Working Model

The original working model involved requesting permission from the planning department to reserve equipment for testing. After receiving permission, the planners noted it in the plans, and the initiator filled in a file with the date and other information. This information was then used for long-term planning and to create an event on the Teams platform to inform all interested parties. However, this process was cumbersome and often steps were missed.

## PowerAutomate Flow

To streamline this process, a PowerAutomate Flow was created. Initiators now fill in the same file, adding additional information needed by interested parties when creating an event on the Teams platform. Subsequently, the planning department receives a request regarding the desired reservation, and if approved, the event is created automatically.

## Installation

To use this automated flow, download the PowerAutomate Flow.

## Usage

To use the PowerAutomate Flow:

1. Set the frequency of checking the table for new requests.
2. Specify the location of the aggregated data.
3. Define conditions for triggering the flow, such as checking whether the event is needed and whether it has been created. If required and not created, the flow initiates.
4. Wait for approval, specifying the type of approval required and filling in necessary details.
5. Once approved, the flow proceeds to create a Team event with the specified information.
6. Update the request line in the form and mark the event as created.
