# Project1
Progetto parte del corso Passion in Action Social Media in Emergency Rapid Mapping.

Indicazioni:
<ul>
  <b>PP1</b>
  <li>import annotated table (Sandy Dataset)</li>
  <li> compute Vincent distance for two tweets, given their ids </li>
  <li> plot a table showing the total number of: not annotated, n.a., [], annotated with one location, annotated with two locations or more visualize them on a map </li>
  <b> PP2 </b>
  <li> import the full Sandy dataset .json file (benchmark_ny_annotated.withcopyright.json) </li>
<li> find the annotated locations in the and put them in a separate table. To do so, use the ""mention"" tag in the .json file. For eg: ""mentions"": [{""indices"": [37, 44], ""class"": ""Location"", ""subclass"": ""admin"", ""name"": ""new york""}] ) <i> dice in sostanza (sull'esempio dato) la parola New York e' menzionata nel testo del tweet dal carattere 37 al 44 </i> </li> 
<li> find locations with the ""name"" string of the full dataset inside New York City with Nominatim </li>
<li> compute the Vincent distances between locations of our annotated set and the full dataset and store them (if more than one location compute all combinations) </li>
  <li> (optional) try some analysis </li>
</ul>
