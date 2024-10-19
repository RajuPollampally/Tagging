Story Tagging System Documentation
Overview
This document outlines a tagging system for managing stories in Digital.ai Agility. The system aims to improve ownership and decision-making regarding which stories should be included in specific release months.
Problem Statement
Currently, it's challenging to determine whether a completed story should be included in the immediate upcoming release or a future release. For example, if a story is completed in August, it's unclear whether it should be released in August (after testing) or held until October.
Proposed Solution
Implement a tagging system for stories to clearly indicate their intended release timeline.
Tag Structure
Each story will have two primary tags:

Completion Month: The month when the story is expected to be completed.
Target Release Month: The intended month for releasing the story.

Tag Format

Completion Month: CM-[Month]
Target Release Month: TRM-[Month]

Example: A story completed in August but targeted for October release would have tags:

CM-AUG
TRM-OCT

Implementation Process

Tag Creation: When a new story is created, the responsible team member assigns both the Completion Month and Target Release Month tags.
Tag Review: A supervisor reviews the assigned tags to ensure they are appropriate before submitting to the delivery manager.
Tag Updates: If the timeline changes during development, update the tags accordingly.
Release Planning: Use the Target Release Month tag to easily identify which stories are intended for each release.
Reporting: Generate reports based on these tags to track the pipeline of stories and their intended release dates.

Roles and Responsibilities

Team Members: Assign initial tags to stories.
Supervisors: Review and approve tags before submission to the delivery manager.
Delivery Manager: Use the tagging system for release planning and management.

Benefits

Clear ownership of stories
Improved visibility into release planning
Easier decision-making for including stories in specific releases
Better tracking of development progress against release targets

Next Steps

Implement the tagging system in Digital.ai Agility
Train team members on the new tagging process
Establish a regular review process to ensure tags are being used correctly
Gather feedback after 1-2 release cycles and adjust the system as needed
