iNaturalist-viz
===============

Visualizations using the iNaturalist API

Uses [iNaturalist API](http://www.inaturalist.org/pages/api+reference)

API call for this project:

    $.ajax( url: http://www.inaturalist.org/observations.json?d1=2014-11-14T14%3A00%3A00-05%3A00&d2=2014-11-16T08%3A00%3A00-05%3A00&page=1&per_page=200&place_id=65597, success: function(d) { data = d } });
    
Repeat a few times to get all the results (this gives 200 at a time) and concatenate. Output for this event is in the [data folder](https://raw.githubusercontent.com/drewbo/iNaturalist-viz/master/data/data.json) as [data.json](https://github.com/drewbo/iNaturalist-viz/blob/master/data/data.json)
