<template>
  <Layout>
    <header class="flex items-center justify-between px-5 py-8">
      <div>
        <g-link>
          <img
            class="h-6"
            src="@/assets/shared/desktop/logo-dark.png"
            alt="Logo"
          />
        </g-link>
      </div>

      <svg-menu class="h-9" />
    </header>

    <main>
      <!-- Hero -->
      <app-hero />

      <section class="px-5 py-7">
        <!-- Project -->
        <section>
          <section>
            <g-link to="/">
              <figure>
                <img
                  class="bg-cover"
                  src="@/assets/home/mobile/image-web-design.jpg"
                  alt="Web Design Image"
                />
              </figure>

              <div>
                <h2>Web Design</h2>
                <span>View Project</span>
              </div>
            </g-link>
          </section>
        </section>

        <!-- Feature -->
        <section></section>
      </section>
    </main>
  </Layout>
</template>

<script>
import SvgMenu from "@/components/svg/SvgMenu.vue";
import AppHero from "@/components/AppHero.vue";

export default {
  components: {
    SvgMenu,
    AppHero,
  },
  metaInfo: {
    title: "Hello, world!",
  },
};
</script>

<style scoped>
/* main {
	background: url(~@/assets/home/desktop/image-hero-phone.png) center 10px / 400px no-repeat,
		#f67b64 url(~@/assets/shared/mobile/bg-pattern-design-pages-intro-mobile.svg) right / cover no-repeat;
} */
</style>
