# scrumptious-issues

Issue forms, templates, and other fun things!  This is a demonstration of a whole bunch of best practices and other bits and pieces of figuring out how to work in GitHub - less of a cohesive whole and more a bunch of shiny things to take and make your own.

The project board that goes with this repository is [here](https://github.com/users/some-natalie/projects/6).

## What's going on here

### Create a weekly retro

This [workflow](https://github.com/some-natalie/scrumptious-issues/actions/workflows/retro.yml) creates a new issue on a schedule based on a template for a retrospective.

There's 2 files needed for this:

- the [template](.github/ISSUE_TEMPLATE/retro.md) defines the structure of the issue opened
- the [workflow](.github/workflows/retro.yml) runs and fills parts of it out on a schedule
