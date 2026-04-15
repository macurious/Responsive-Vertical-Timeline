# Simple responsive vertical timeline with animation

```
<section class="timeline">
	<ul>
		<li>
			<div>
				<h4>Your date or title</h4>
				<p>Your text content</p>
			</div>
		</li>
		...
	</ul>
</section>
```

### Add animation

To animate the timeline on scroll add the **animation** class

```
<section class="timeline animation">
```

### Add counter numbers

To show incrementing numbers inside the timeline nodes add the **counter** class.

```
<section class="timeline counter">
```

### Add timeline right option

On mobile devices the timeline is aligned to the left by default. If you want it on the right instead just add the additional **right** class.

```
<section class="timeline right">
```

### Flip the desktop alternating direction

On desktop the timeline alternates by default with the first item starting on the left. Add the **alternate** class if you want the first item to start on the right instead.

```
<section class="timeline alternate">
```

### Combine options

These classes can be combined depending on the behavior you want.

```
<section class="timeline animation counter alternate">
```

If you combine **right** and **alternate**, **right** controls the mobile direction and **alternate** controls the desktop starting side.

```
<section class="timeline animation counter alternate right">
```

[Demo](https://macurious.github.io/Responsive-Vertical-Timeline/)
