---
publish: true
created: 2025-06-12T16:25:12.136+02:00
modified: 2026-03-23T13:41:59.441+01:00
---


<div id="p5-container"></div>


```html
<script src="https://cdn.jsdelivr.net/npm/p5@1.9.0/lib/p5.min.js"></script>
<script>
  new p5(p => {
    p.setup = function () {
      p.createCanvas(200, 200);
      p.background(220);
    };
    p.draw = function () {
      p.ellipse(p.mouseX, p.mouseY, 20, 20);
    };
  }, 'p5-container');
</script>
```

