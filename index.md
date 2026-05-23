---
layout: default
title: Niranjan Thanikachalam
---


# Niranjan Thanikachalam -- Portfolio

<p class="social-links" aria-label="Social links">
	<a href="https://github.com/tniranjan" aria-label="GitHub" target="_blank" rel="noopener noreferrer">
		<svg viewBox="0 0 16 16" aria-hidden="true" focusable="false">
			<path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.5-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82a7.66 7.66 0 0 1 4 0c1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.01 8.01 0 0 0 16 8c0-4.42-3.58-8-8-8z"/>
		</svg>
		<span>GitHub</span>
	</a>
	<a href="https://www.linkedin.com/in/niranjanthanikachalam/" aria-label="LinkedIn" target="_blank" rel="noopener noreferrer">
		<svg viewBox="0 0 16 16" aria-hidden="true" focusable="false">
			<path d="M0 1.15C0 .52.52 0 1.15 0h13.7C15.48 0 16 .52 16 1.15v13.7c0 .63-.52 1.15-1.15 1.15H1.15A1.15 1.15 0 0 1 0 14.85V1.15zM4.75 13.2V6.1H2.39v7.1h2.36zm-1.18-8.07c.82 0 1.33-.54 1.33-1.22-.02-.7-.51-1.22-1.31-1.22-.8 0-1.33.52-1.33 1.22 0 .68.51 1.22 1.29 1.22h.02zm10.06 8.07V9.24c0-2.12-1.13-3.1-2.64-3.1-1.22 0-1.77.67-2.08 1.14V6.1H6.56c.03.79 0 7.1 0 7.1h2.35V9.23c0-.21.01-.41.08-.56.16-.41.52-.84 1.14-.84.8 0 1.12.62 1.12 1.53v3.84h2.38z"/>
		</svg>
		<span>LinkedIn</span>
	</a>
	<a href="mailto:tniranjan@duck.com" aria-label="Email">
		<svg viewBox="0 0 16 16" aria-hidden="true" focusable="false">
			<path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v.22l-8 4.89-8-4.89V4zm0 1.38v6.62a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V5.38L8.42 10.3a1 1 0 0 1-1.04 0L0 5.38z"/>
		</svg>
		<span>Email</span>
	</a>
</p>

I am a Computer Vision engineer with a PhD from EPFL in Computational Imaging. I am interested in 3D reconstruction, segmentation, inverse rendering, inverse problems and numerical optimization.

---
{% for project in site.data.projects %}
{% include project_entry.html project=project %}
{% unless forloop.last %}
---
{% endunless %}
{% endfor %}