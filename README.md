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

### Add arrow pointers

To show arrow pointers on the cards pointing toward the timeline node, add the **arrows** class. The gap between the card and the dot will automatically account for the arrow size.

```
<section class="timeline arrows">
```

### Add vertical offset between cards (desktop only)

To apply a vertical offset between cards on desktop — useful for a staggered look — add the **offset** class. The offset amount is controlled via the `--timeline-card-offset-y` CSS variable (negative values pull cards upward).

```
<section class="timeline offset">
```

### Combine options

These classes can be combined depending on the behavior you want.

```
<section class="timeline animation counter alternate arrows offset">
```

If you combine **right** and **alternate**, **right** controls the mobile direction and **alternate** controls the desktop starting side.

```
<section class="timeline animation counter alternate right arrows">
```

[Demo](https://macurious.github.io/Responsive-Vertical-Timeline/)
