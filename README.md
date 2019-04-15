# Concourse Templates

a collection of templates to make it faster to add a project to Concourse for GovWifi.

## Filling in the gaps

Any content that needs changing will be wrapped in `<% ... %>` tags. They should have descriptive names.

You can find all references with `egrep "<%.+%>" * -R`.

## Structure

Within each directory will be references files that you can apply to your repos.

Read through the files, especially accompanying documentation, so you can apply them to your repository.

## govwifi-pr

Reference for setting up a Pull Request pipeline.
An implementation can be found here: https://github.com/alphagov/govwifi-logging-api/pull/145
