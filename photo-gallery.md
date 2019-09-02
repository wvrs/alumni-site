---
layout: default
title: Photo Gallery
permalink: /photo-gallery/
custom_css: baguetteBox.min
custom_js: baguetteBox.min
---

<div id="gallery">
	{% for section in site.data.gallery %}
	<div class="gallery-section">
		<h2 class="h5">{{ section.title }}</h2>
		<div class="row">
			{% for image in section.images %}
			<div class="col-3">
				<div class="gallery-container">
					<a href="{{ image.file | prepend: '/assets/images/gallery/' | relative_url}}">
						<img class="lazy" src="{{ '/assets/images/placeholder.gif' | relative_url}}" data-src="{{ image.file | prepend: '/assets/images/gallery/' | relative_url}}" />
					</a>
				</div>
			</div>
			{% endfor %}
		</div>
	</div>
	{% endfor %}
</div>