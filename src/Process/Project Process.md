# Project Process

The goal of this document is to describe the expectations for how a project at Open SGF is completed.

Providing a written document for this is an important way to ensure that members of our group (both volunteers and organizers alike) are aligned in their work on a project and are working together towards the common goals.

## Project Phases

A project at Open SGF should go through the following phases:

- Definition
- Planning
- Execution
- Delivery

Each phase is made up of many smaller steps.

It's important to note that many projects at Open SGF will go through these phases in a repeated cycle, especially for larger projects. It's very difficult on some projects to try to define and plan all of the work up front as it may change during the lifecycle of the project.

### Definition

During this phase of a project, the focus should be on defining what we should build. This should include conversations with project stakeholders to capture information about their needs.

The results of these conversations should be documented in a PRD (Product Requirements Document). PRDs take many forms, but Open SGF has a [preferred template](<./PRD Template.md>) to use.

The goal when writing a PRD should be to provide enough detail such that designers, developers, and stakeholders all have a shared understanding of what's going to be built.

For projects that are intended to have multiple cycles, a Product Overview & Vision document is likely warranted. This will ensure the team remain consistent in it's goals over time.

Lastly the definition phase may need to include some level of review by Stakeholders before moving on to the next phase.

### Planning

During the planning phase, the team takes PRDs and works together to break those down into individual work items. This can be done by both design and development separately.

While planning work the team should:

- Break the work into manageable chunks for individual team members to tackle
- Identify blockers or dependencies between these chunks and other external items
- Identify complex requirements that need more details (more on this later)

The work that the team is planning should end up in some kind of project board. Currently the preferred tool is [Plane](https://plane.sgf.dev/open-sgf) (message an organizer if you need an invite).

Planning typically should happen during a Code & Demo night with an eye for planning at least enough work to keep the team busy until the next planning meeting.

### Execution

This is the phase where we begin building the projects. This is where design would begin adding to artboards and development would begin writing code and submitting pull requests.

#### Handling Complex Requirements

One part that ultimately comes up during execution is how to handle complex requirements aka Architecturally Significant Requirements. Wikipedia defines an ASR as "A requirement that has wide effect, targets trade-off points, is strict (constraining, limiting, non-negotiable), assumption breaking, or difficult to achieve".

When we see one of these, it's incredibly important for the team to document it's thought process and decision for handling that requirement. The ideal format for these is an ADR (Architecture Decision Record). ADRs take many forms, but Open SGF has a [preferred ADR template](https://github.com/Open-SGF/project-template/blob/main/docs/decisions/template.md) to use. For more detail on ADRs see the overview in our [project template](https://github.com/Open-SGF/project-template/blob/main/docs/decisions/README.md).

It's important that the actual decisions made in these ADRs are not made by a single person. An ADR should be rigorously reviewed and debated by the team before being accepted.

#### Reviewing and Accepting Work

Lastly, all work contributed to the project needs at least one review from a trusted reviewer before being accepted. In the early days of a project this will likely be an organizer, but as team members continue to show competency and commitment to the project, trusted reviewer status can be extended to them by an organizer.

Regardless, it is expected that even those with trusted reviewer status still use the review process to have their work accepted.

### Delivery

Our work is only useful if it actually gets shipped! During this phase of a project we deliver our work out to project stakeholders and later users.

Our Code & Demo Night meetings are the first major step towards delivery of our work. It is here where we show our work to project stakeholders and receive early feedback.

Every project should also strive to deploy work to at minimum some form of a staging environment. This allows other team members and project stake holders to review and test the project.

Once the work has been properly tested and reviewed it should then be finally delivered to production.
