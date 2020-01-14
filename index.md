## Experience
### [ApSo s.r.o.](https://www.apso.cz/), 09/2014 - 10/2017
Position: Programmer Analyst

Responsibilities and achievements:
 
 - [Lead backend programmer](https://en.wikipedia.org/wiki/Lead_programmer) in OpenEdge ABL for projects with Android and web frontend
 - Initiation of VCS usage (git)
 - Setup and administration of GitLab
 - Tools development, e.g. [OpenEdge ABL language support for VS Code](https://marketplace.visualstudio.com/items?itemName=zvg.vscode-oeabl)

### [Quadient s.r.o.](https://www.quadient.com/), 11/2017 - present
Position:
 - Software Developer (11/2017 - 11/2018)
 - Product Owner/Delivery Manager/Project Manager (12/2018 - present)

Responsibilities and achievements:
 - Docker/Git/Linux evangelist
 - Responsible for project with manpower 40+ people (20 DEVs)

### [SimCompanies](https://www.simcompanies.com/), 01/2020 - present
Position: Software Developer (part-time)

## Personal traits and interests
 - Lazy
 - Inovative
 - Perfectionist
 - Seeking responsibility

## Interests
 - [Passionate reader](https://www.goodreads.com/user/show/54880174-v-clav-sobotka)
 - Mathematics, Physics, and Philosophy amateur
 - Entering the world of value investing since 2017
 - Explorer of programming languages and trending technologies
### Vertical Bar
{% highlight julia %}
using Vega

x = [1, 2, 3, 4, 5]
y = [1, 2, 3, 2, 1]

barplot(x = x, y = y)
{% endhighlight %}

 <div id="vis"></div>

 <script type="text/javascript">
// parse a spec and create a visualization view
function parse(spec) {
  vg.parse.spec(spec, function(chart) { chart({el:"#vis"}).update(); });
}
parse(

{"name":"Vega Visualization","height":450,"padding":"auto","marks":[{"properties":{"enter":{"x":{"field":"x","scale":"x"},"y2":{"field":"y2","scale":"y"},"width":{"offset":-1,"scale":"x","band":true},"fill":{"field":"group","scale":"group"},"y":{"field":"y","scale":"y"}}},"from":{"data":"table"},"type":"rect"}],"axes":[{"properties":{"title":{"fontSize":{"value":14}}},"title":"x","type":"x","scale":"x"},{"titleOffset":40,"properties":{"title":{"fontSize":{"value":14}}},"title":"y","type":"y","scale":"y"}],"data":[{"name":"table","values":[{"x":1,"y2":0,"group":1,"y":1},{"x":2,"y2":0,"group":1,"y":2},{"x":3,"y2":0,"group":1,"y":3},{"x":4,"y2":0,"group":1,"y":2},{"x":5,"y2":0,"group":1,"y":1}]}],"scales":[{"name":"x","range":"width","domain":{"data":"table","field":"x"},"type":"ordinal"},{"name":"y","range":"height","domain":{"data":"table","field":"y"},"type":"linear"},{"name":"group","range":["rgb(166,206,227)","rgb( 31,120,180)","rgb(178,223,138)","rgb( 51,160, 44)","rgb(251,154,153)","rgb(227, 26, 28)","rgb(253,191,111)","rgb(255,127,  0)","rgb(202,178,214)","rgb(106, 61,154)","rgb(255,255,153)","rgb(177, 89, 40)"],"domain":{"data":"table","field":"group"},"type":"ordinal"}],"width":450});
</script>
