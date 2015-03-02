---
# App Options
layout: fusion
title: Proizvodnja kafe...
description: U gridu i tablama možete videti podatke
author: Milos Rujevic
category: aplikacije
image: /img/app/fusion-grid-chart.png
# Grid Options
select: "Country, '2000/01' as Y2000, '2001/02' as Y2001, '2002/03' as Y2002, '2003/04' as Y2003, '2004/05' as Y2004, '2005/06' as Y2005, '2006/07' as Y2006, '2007/08' as Y2007, '2008/09' as Y2008"
from: "12Ky51FcTdAPYsnP42k3N4AtEB8EcxxfLMJ5rAnU"
filter: "Country"
# Chart Options
chart: bar
compare: "Coffee Production"
chart_height: 1200
---

{% include fusion-filter-grid.html %}
