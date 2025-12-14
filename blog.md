---
layout: default
title: Technical Blog
permalink: /blog/
---

<div class="content-section">
    <h1>📝 Technical Blog</h1>
    <p>Welcome to my technical blog where I share insights, learnings, and explorations in software engineering, machine learning, and emerging technologies.</p>
</div>

{% assign posts = site.posts %}
{% if posts and posts.size > 0 %}
<div class="blog-grid">
    {% for post in posts %}
    <article class="blog-card">
        <a href="{{ post.url | relative_url }}">
            <h3>{{ post.title }}</h3>
            <div class="blog-date">{{ post.date | date: "%B %d, %Y" }}</div>
            {% if post.excerpt %}
                <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
            {% else %}
                <p>{{ post.content | strip_html | truncatewords: 30 }}</p>
            {% endif %}
            
            {% if post.tags and post.tags.size > 0 %}
            <div class="blog-tags">
                {% for tag in post.tags limit: 3 %}
                    <span class="tag">{{ tag }}</span>
                {% endfor %}
            </div>
            {% endif %}
        </a>
    </article>
    {% endfor %}
</div>
{% else %}
<div class="content-section">
    <p>🚧 Blog posts coming soon! I'm currently working on sharing more insights and technical deep-dives.</p>
    
    <h3>What to expect:</h3>
    <ul>
        <li><strong>CUDA & GPU Programming:</strong> Performance optimization techniques and best practices</li>
        <li><strong>Machine Learning Engineering:</strong> From model development to production deployment</li>
        <li><strong>High-Performance Computing:</strong> Distributed systems and parallel computing</li>
        <li><strong>Cloud Platform Engineering:</strong> Infrastructure, DevOps, and scalability</li>
        <li><strong>Trading Technology:</strong> Low-latency systems and financial engineering</li>
    </ul>
    
    <p>Check back soon for new content, or <a href="{{ site.social_links.linkedin }}" target="_blank">connect with me on LinkedIn</a> for updates!</p>
</div>
{% endif %}