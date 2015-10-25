<script src="processing.min.js"></script>
<canvas datasrc="flutrace.pjs" width="800" height="360">`Can't load canvas`</canvas>	

This is a simulation of influenza H3N2 migration dynamics. Each circle represents a virus. Viruses replicate and die and migrate between regions. Viruses accumulate mutations which change their color, thereby representing strain variation. Seasonality is present, so that temperate regions show a summer trough and winter peak in flu incidence. China and Southeast Asia experiences weaker seasonal forcing and because of this they harbor year-round influenza infections. These endemic populations are where new successful variants emerge that eventually take over the entire virus population.

Simulation parameters are taken from [Bedford et al. 2010](http://bedford.io/papers/bedford-global-migration/). However, some liberties (like total number of viruses shown) have been taken to promote a visually cohesive display. This is meant as an illustration rather than a research tool.

Click on the animation and press H to bring up a listing of commands.
