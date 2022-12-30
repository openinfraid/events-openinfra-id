# OpenInfra Days Indonesia

# Adding contents
You will need to install [Hugo CLI](https://gohugo.io/getting-started/installing/) to easily add contents.

To create new content, run the following command

```bash
# Create event content
hugo new --kind events events/<session-name>/_index.md

# Example: Create session content with title "OpenInfra Days Indonesia 2024"
hugo new --kind events events/openinfra.id-2021/_index.md
```

After that, You will find generated markdown file under `content` directory. Edit the markdown file to add details.
To add photo files, put files on content item directory.(The same path where content item's `_index.md` exists.)

# License
Code: MIT, Contents: CC BY 4.0
