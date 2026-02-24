# Quarto Extension for Beautiful Mermaid

## Overview
The Quarto extension for Beautiful Mermaid provides an intuitive way to create beautiful and customizable diagrams using the Mermaid library within your Quarto documents. This extension allows users to seamlessly integrate stunning diagrams into their reports and presentations.

## Features
- Easy integration of Mermaid diagrams in Quarto documents.
- Customizable diagram styles.
- Support for various types of diagrams (flowcharts, sequence diagrams, gantt charts, etc.).

## Installation
To install the Beautiful Mermaid extension, include the following in your Quarto project's `_extensions.yml` file:
```yaml
extensions:
  - beautiful-mermaid
```

## Usage
### Including a Diagram
You can include a Mermaid diagram in your Quarto document by using the following syntax:
```markdown
```{mermaid}
graph TD
    A --> B
    B --> C
    C --> D
```
```

### Customizing Diagrams
You can customize your diagrams by using CSS styles. For example:
```markdown
<style>
.mermaid {
  background-color: #f9f9f9;
}
</style>
```

## Examples
### Flowchart Example
Below is an example of a simple flowchart diagram:
```markdown
```{mermaid}
flowchart TD
    A[Start] --> B{Is it?}
    B -- Yes --> C[Done]
    B -- No --> D[End]
```
```

## Contribution
Contributions to this extension are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Support
For support, please open an issue in the GitHub repository.

---

*Last updated: 2026-02-24*