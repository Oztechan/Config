# Contributing

## Branch

Branch name should start with `ISSUE_ID` and after the id there should be `-` and then it continues with description of branch or title of ticket. Use `_` for empty spaces.

Example:

```
123-My_Cool_Feature_Or_Bug
```

## Commit Message

Every commit message should match the following format `[{{ repository.owner }}/{{ repository.name }}#ISSUE_ID] Commit message`

Example:

```
[{{ repository.owner }}/{{ repository.name }}#ISSUE_ID] My cool feature
```

## Pull Request

### Title

Pull Request title should follow below format:

```
[{{ repository.owner }}/{{ repository.name }}#ISSUE_ID] ISSUE_TITLE
```

Example:

```
[{{ repository.owner }}/{{ repository.name }}#ISSUE_ID] Whatever the name of ticket is
```

### Description

Description has to have `Resolves {{ repository.owner }}/{{ repository.name }}#ISSUE_ID` with relevant issue. It will help project automations.

Example:

```
Resolves {{ repository.owner }}/{{ repository.name }}#123

Some description.
```
