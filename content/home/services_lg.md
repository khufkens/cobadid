+++
# Hero widget.
widget = "services_lg" 
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 35  # Order that this section will appear.

title = "Our approach"
subtitle = "tiered work"

[design.spacing]
# Customize the section spacing. Order is top, right, bottom, left.
padding = ["50px", "0", "50px", "0px"]

[[item]]

positionRight = false
image = "img/diagram.png"
title = "A callback API"
description = """
 
 We aim to develop callback API which serves (meta-)data and formatted calls to existing server infrastructure. The infrastructure therefore will provide a query of queries, downloaded by nested R packages (but also supporting python infrastructure). Our approach mimicks how the current ECMWF data API works, with downloads not centralized server but handled by user clients.
 
 """

[[item]]

positionRight = true
image = "img/docker_logo.png"
title = "A modular approach"
description = """

We will rely on a R based approach using the **rplumber API** backend served through **containerized** sever infrastructure. Data downloads by users will be dependent on R or python packages (we will develop R packages but the calls will be python readable).
 
"""

+++
