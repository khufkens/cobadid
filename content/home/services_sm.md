+++
# Hero widget.
widget = "services_sm" 
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Our approach"
subtitle = "tiered work"

[design.spacing]
# Customize the section spacing. Order is top, right, bottom, left.
padding = ["50px", "0", "50px", "0px"]

[[item]]
title = "Meta-Data Analysis"
description = """

We will compile an extensive meta-data database from which the final API will run. Data will be quality controlled and properly documented, adhering to ownership and copyright restrictins.

"""

icon = "database"
icon_pack = "fas"
name = "Statistics"


[[item]]
title = "Linking Data"
description = """

The callback API development will use the linked meta-data database to serve summary statistica as well as callback queries. Callback queries will be served and fullfilled through custom R packages.

"""
icon = "project-diagram"
icon_pack = "fas"
name = "Statistics"


[[item]]
title = "Science Communication"
description = """

We will provide a single website serving containerized instances of the callback API and provide easy access to ancillary documentation. In additon, stand alone machine learning datasets will be generated in collaboration with the user communities to support both research and education.

"""
icon = "file-alt"
icon_pack = "fas"
name = "Statistics"

+++
