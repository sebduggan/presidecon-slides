## srcset

```
<img src="small.jpg"
	srcset="medium.jpg 1000w, large 2000w"
	sizes="(max-width: 480px) 100vw, 50vw"
	alt="...">
```

<ul>
	<li class="fragment">Simplest method</li>
	<li class="fragment">Ideal for alternate resolutions (e.g. Retina)</li>
	<li class="fragment">Browser does the hard work</li>
	<li class="fragment"><code>sizes</code> is optional; assumes image is 100% wide</li>
	<li class="fragment">Falls back to <code>src</code> image if not supported</li>
</ul>