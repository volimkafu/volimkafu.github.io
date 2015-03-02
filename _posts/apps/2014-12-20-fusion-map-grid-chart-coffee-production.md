---
# App Options
layout: fusion
title: Interaktivna mapa
description: Interaktivna mapa sa podacima proizvodnje kafe
category: app
image: /img/app/fusion-map-grid-chart.png
# Grid Options
select: "Country, '2000/01' as Y2000, '2001/02' as Y2001, '2002/03' as Y2002, '2003/04' as Y2003, '2004/05' as Y2004, '2005/06' as Y2005, '2006/07' as Y2006, '2007/08' as Y2007, '2008/09' as Y2008"
from: "12Ky51FcTdAPYsnP42k3N4AtEB8EcxxfLMJ5rAnU"
filter: "Country"
# Chart Options
chart: bar
compare: "Coffee Production"
chart_height: 1200
---
Interaktivna mapa sa podacima proizvodnje kafe po državi.

<iframe width="100%" height="400" scrolling="no" frameborder="no" 
src="https://www.google.com/fusiontables/embedviz?q=select+col11+from+12Ky51FcTdAPYsnP42k3N4AtEB8EcxxfLMJ5rAnU&amp;viz=MAP&amp;h=false&amp;lat=8.769762156504258&amp;lng=91.99385124999992&amp;t=1&amp;z=2&amp;l=col11&amp;y=3&amp;tmplt=4&amp;hml=GEOCODABLE"></iframe>

{% include fusion-filter-grid.html %}
