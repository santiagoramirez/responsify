#Responsify

Responsify is my take at creating a responsive grid system. It is somewhat based off of Bootstrap and Unsemantic.

The Responsify grid is uses percents. To sepcify the default percent of a div use `col-{percent}`, and use `col-tablet-{percent}` and `col-mobile-{percent}` for tablets and mobile phones.

**Example usage**
```
	<div class="container">
		<div class="col-33 col-tablet-50 col-mobile-100"></div>
		<div class="col-33 col-tablet-50 col-mobile-100"></div>
		<div class="col-33 col-tablet-100"></div>
	</div>
```
