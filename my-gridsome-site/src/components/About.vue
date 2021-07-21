<template>
  <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="about">
    <div class="w-100">
      <h1 class="mb-0">
        Theeramate
        <span class="text-primary">Supasart</span>
      </h1>
      <div class="subheading mb-5">
        Bankkok Thailand,0800517063 ·
        <a
          href="6110110217@psu.ac.th"
        >6110110217@psu.ac.th</a>
      </div>
      <p
        class="lead mb-5"
      >My name is Theeramate Supasart Nickname Tee Age:21 Gender:Male<br> This Webside is part of a Class Web Engineering in Computer Engineering of PSU.<br>Learning to Use the SSG tool & web site  deployment on the cloud hosting platform. </p>
      <p class="lead mb-5">
        Resume started using this template with Gridsome here:
        <a
          href="https://github.com/theeramate1999"
          target="_blank"
          rel="noopener noreferrer"
        >Github repo</a>.
      </p>
      <div class="social-icons">

        <a href="https://github.com/theeramate1999" target="_blank" rel="noopener noreferrer" aria-label="GitHub Profile">
          <font-awesome :icon="['fab', 'github']"/>
        </a>
        <a href="https://www.facebook.com/TeeTheeramate/" target="_blank" rel="noopener noreferrer" aria-label="Facebook Profile">
          <font-awesome :icon="['fab', 'facebook']"/>
        </a>
        <a href="https://loke.dev" target="_blank" rel="noopener noreferrer" aria-label="Loke.dev">
          <font-awesome :icon="['fas', 'rss']"/>
        </a>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.social-icons a {
  cursor: pointer;
  display: inline-block;
  height: 3.5rem;
  width: 3.5rem;
  background-color: var(--secondary);
  color: #fff !important;
  border-radius: 100%;
  text-align: center;
  font-size: 1.5rem;
  line-height: 3.5rem;
  margin-right: 1rem;

  @media (max-width: 380px) {
    margin-right: 0.5rem;
  }

  @media (max-width: 350px) {
    margin-right: 0.2rem;
  }
}

.social-icons a:last-child {
  margin-right: 0;
}

.social-icons a:hover {
  background-color: var(--primary);
}
</style>
