This repository is intended for presenting, visualizing, and explaining the results obtained from crystal structure searches.

# agent-shotgun-csp-viewer

Output results from `aiida-shotgun-csp`.

To view the HTML files, open:

https://nim-hrkn.github.io/agent-shotgun-csp-viewer/index.html

## Crystal Structure Search Workflow

Crystal structure searches are performed using `shotgun-csp next` through the following workflow:

Claude → MCP → aiida-shotgun-csp → AiiDA → computational PCs

Claude interacts with `aiida-shotgun-csp` via MCP. The calculations are managed by AiiDA and executed on computational PCs, where `shotgun-csp next` performs the crystal structure searches.

Hiori Kino, Sep. 17, 2026
