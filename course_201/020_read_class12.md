[Back to Main Page](https://roguestar112.github.io/reading-notes/)

# Chart.js, Canvas

The `<canvas>` lets you draw 2-dimensional graphics with JS.

The closing `</canvas>` tag, when content is in-between the opening and closing tags,
is what shows alternatively if the browser doesn't support `<canvas>`.

The getContext() method allows you to select a rendering type for the canvas, such as
2d.

Chart.js is a library that allows you to generate graphs in canvas tags, and can be brought by using Node package manager (npm). However since I'm not using Node.js/React yet, (yet...), we'll make do by using a CDN (content delivery network), which basically sends the code through a `<link>` html tag.

Chart.js allows you to create bar, line, pie, scatter charts, etc. You can even mix different types of charts in one canvas!

Chart.js charts typically don't take up as much space as an HTML table, and they can display trends in data.

The previously created applications, like my salmon cookies chart, could definitely be revamped by using a chart.
