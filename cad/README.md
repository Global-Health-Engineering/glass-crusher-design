# cad

Directory containing CAD drawings in `.stp`, `.prt`, and `.pdf` formats.

| `dir` name                                | Description                                                   |
| ----------------------------------------- | ------------------------------------------------------------- |
| `A_Glass_Crusher_Full_Assembly.*`         | Final assembly of the glass crusher in three formats          |
| `standard_parts`                          | Drawings of standard parts, e.g., screws, nuts, washers       |
| `sub-assemblies`                          | All subassemblies used in `A_Glass_Crusher_Full_Assembly.stp` |
| `sub-assemblies/cover`                    | Drawings of the crusher's cover                               |
| `sub-assemblies/extended_frame`           | Drawings of the assembled, extended frame                     |
| `sub-assemblies/motorcycle_chains`        | Drawings of the motorcycle chain                              |
| `sub-assemblies/roller_mounting_platform` | Drawings of the rolling mounting platform                     |
| `sub-assemblies/rollers`                  | Rollers' drawings                                             |
| `sub-assemblies/sprocket_module_large`    | Drawings of the large sprocket module                         |
| `sub-assemblies/sprocket_module_small`    | Drawings of the small sprocket module                         |
| `sub-assemblies/upper_side_panels`        | Drawings of the upper side panels                             |

Each directory with an assembly contains the `parts` directory with the simplest part drawings.

# tree

    .
    ├── A_Glass_Crusher_Full_Assembly.prt
    ├── A_Glass_Crusher_Full_Assembly.stp
    ├── A_Glass_Crusher_Full_Assembly_dwg.pdf
    ├── standard_parts
    └── sub-assemblies
        ├── cover
        │   └── parts
        ├── extended_frame
        │   ├── parts
        │   └── subassemblies
        │       ├── crank
        │       │   └── parts
        │       ├── crank_side_panel
        │       │   └── parts
        │       ├── drivetrain_panel
        │       │   ├── parts
        │       │   └── subassemblies
        │       │       └── chain_guides
        │       │           └── parts
        │       └── frame
        │           └── parts
        ├── motorcycle_chains
        │   └── subassemblies
        │       └── chain_subunits
        │           └── parts
        ├── roller_mounting_platform
        │   └── parts
        ├── rollers
        │   ├── parts
        │   └── subassemblies
        │       └── roller_bearing_brackets
        │           └── parts
        ├── sprocket_module_large
        │   └── parts
        ├── sprocket_module_small
        │   └── parts
        └── upper_side_panels
            └── parts
