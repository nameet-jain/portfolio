---
layout: page
permalink: /contact/
---

<article class="contact active" data-page="contact">
    <header>
        <h2 class="h2 article-title">Get in Touch</h2>
    </header>

    <section class="contact-text">
        <p>
            I am always open to discussing new opportunities, architecture challenges, or open source collaborations.
            Feel free to reach out to me! 👋
        </p>
    </section>

    <section class="contact-links">
        <ul class="grid-list">
            <li class="contact-card-item">
                <a href="mailto:{{ site.author.email }}" class="contact-card-link">
                    <div class="card-icon-box">
                        <ion-icon name="mail-outline"></ion-icon>
                    </div>
                    <div class="card-content">
                        <p class="card-text">{{ site.author.email }}</p>
                    </div>
                </a>
            </li>
            <li class="contact-card-item">
                <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" target="_blank" class="contact-card-link">
                    <div class="card-icon-box">
                        <ion-icon name="logo-linkedin"></ion-icon>
                    </div>
                    <div class="card-content">
                        <p class="card-text">Connect on LinkedIn</p>
                    </div>
                </a>
            </li>
            <li class="contact-card-item">
                <a href="https://github.com/{{ site.author.github }}" target="_blank" class="contact-card-link">
                    <div class="card-icon-box">
                        <ion-icon name="logo-github"></ion-icon>
                    </div>
                    <div class="card-content">
                        <p class="card-text">Check my Code</p>
                    </div>
                </a>
            </li>
        </ul>
    </section>

</article>
