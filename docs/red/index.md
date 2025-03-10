# Welcome to Read

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
## Project mermaid
   <div class="mermaid"> ```mermaid graph LR
    hello --> world
    world --> again
    again --> hello ``` </div>
## test
    ```mermaid graph LR
    hello --> world
    world --> again
    again --> hello ```
 ## test 2
 ```mermaid
graph LR
  A[Start] --> B{Decision}
  B -->|Yes| C[End]
  B -->|No| A   