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
					<a href="{{ site.base_url }}/assets/images/gallery/{{ image.file }}">
						<img class="lazy" src="{{ site.base_url }}/assets/images/placeholder.gif" data-src="{{ site.base_url }}/assets/images/gallery/{{ image.file }}" />
					</a>
				</div>
			</div>
			{% endfor %}
		</div>
	</div>
	{% endfor %}
</div>