+++
# Date this page was created.
date = "2008-07-07"

# Project title.
title = "Pedestrian Dead Reckoning"

# Project summary to display on homepage.
summary = "Indoor tracking using IMU"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "thumbnail/pdr.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["other", "pedestrian dead reckoning", "imu"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
#image = ""
#caption = ""

+++
{{< youtube E899UohcpRw >}}

There are limitations when it comes to tracking firefighters. Often the firefighters must work in indoors and the GPS signal can be weak. The foundation systems can be destroyed in some cases leading to difficulty in using an existing position tracking system to locate one. In such cases, Inertial Navigation System is more appropriate. However, the usage of Inertial Navigation System on pedestrians leads to accumulative errors. Therefore there is a need to calculate each stride and steps in order to prevent anticipated problems.
