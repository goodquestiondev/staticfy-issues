# Hello world javascript action

This action creates static files for every issue created including the title, content and comments in GitHub flavored mardown format.

## Inputs

### `folder-name`

**Required** The name of the folder to save the files Default `"issues"`.

## Outputs

### `time`

The time we the file was created.

### `fileName`

The name of the file created

## Example usage

uses: actions/staticfy-issues@v1
with:
folder-name: 'questions'
