<template>
  <main class="grid grid-flow-row min-h-screen mb-20">
    <section>
      <div class="divide-y-2 divide-gray-800 divide-solid px-10">
        <div class="text-center py-2"></div>
        <div class="text-center py-2"></div>
      </div>
      <a href="https://codame.com" target="_blank" class="hover:text-teal-600">
        <h2 class="text-center p-4 hover:text-teal-600">
          Codame
        </h2></a
      >
      <article class="p-4">
        <p>
          Codame is a non-profit organization who has been supporting and
          advocating for the art + tech community since a decade ago.
        </p>
        <p>
          With the ever evolving content and initiatives, Codame's founding team
          is committed to redesign and rearchitect the online presence to
          improve the user experience and internal workflow. I've always been
          wanting to leverage technology to empower creative expressions. Hence,
          I decided to take on the challenge to lead the project.
        </p>
        <br />
        <p>
          Currently, codame.com is a custom built dynamic site using PHP for the
          frontend view and backend CMS editor. It served the purpose back then
          but the layout and workflow is no longer feasible for the content and
          functionalities. My plan is to use
          <a href="https://jamstack.org/">Jamstack</a> to decouple the view and
          the backend. The suitable candidates would be
          <a href="https://www.gatsbyjs.com/">Gatsby</a> or
          <a href="https://nextjs.org/">Next.js</a> for the frontend, and
          Sanity.io or <a href="https://strapi.io/">Strapi</a> as the CMS
          editor.
        </p>
        <br />
        <p>
          I started out laying out the project with a
          <a href="https://www.notion.so/">Notion</a> doc, and ran through a
          branding audit with the key stakeholders, to agree on the brand
          architecture and design elements. I then sketched out the new
          information architecture based on the main content and
          functionalities.
        </p>
        <br />
        <p>
          I used Balsalmic for the low fidelity wireframes. I decided to use
          Material's design system as a framework for Codame's design system,
          and moved onto Figma for the high fidelity mockups and a clickable
          prototype.
        </p>
      </article>
      <div class="flex flex-col md:flex-wrap md:flex-row xs:w-11/12">
        <img
          src="../assets/images/home.png"
          alt="Codame home page"
          class="md:w-7/12 p-2"
        />
        <img
          src="../assets/images/color-palette.png"
          alt="Codame color palette"
          class="md:w-5/12 p-2"
        />
        <img
          src="../assets/images/typography.png"
          alt="Codame typography"
          class="md:w-5/12 p-2"
        />
        <img
          src="../assets/images/events.png"
          alt="Codame events"
          class="md:w-7/12 p-2"
        />
      </div>
    </section>
    <div class="grid mt-20">
      <a href="http://cuttle.page/" target="_blank" class="hover:text-teal-600">
        <h2 class="text-center p-4 hover:text-teal-600">Cuttle</h2></a
      >
      <div class="flex flex-col p-4 lg:flex-row lg:justify-between">
        <section
          class="flex flex-col flex-initial gap-2 my-2 lg:my-0 lg:w-3/5 p-8 bg-teal-100 rounded-tl-xl border-2 border-teal-300"
        >
          <article class="mb-4">
            <p>
              Cuttle is a light weight video annotator built on top of Vue,
              video.js, Vimeo Player API, Firebase and Tailwind CSS.
            </p>
            <br />
            <p>
              The name Cuttle, is originally inspired by Cuttlefish, which
              symbolizes flexibility, creativity and intelligence.
            </p>
          </article>
          <div class="flex flex-row gap-x-6 items-center">
            <a
              href="https://cuttle.page"
              class="no-underline bg-pink-500 hover:bg-pink-300 text-white font-bold py-2 px-4 rounded border-b-4 border-pink-700 text-center"
            >
              Learn with Cuttle
            </a>
            <a href="https://github.com/lunaceee/cuttle">
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
                class="feather feather-github hover:text-pink-500"
              >
                <path
                  d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
                ></path>
              </svg>
            </a>
          </div>
        </section>
        <div class="md:px-4">
          <img
            class="border-4 border-pink-300 rounded-br-xl"
            src="../assets/images/cuttle-ux.gif"
            alt="Cuttle demo"
          />
        </div>
      </div>
    </div>
    <div class="grid mt-20">
      <a
        href="https://gato-shell-game.netlify.app/"
        target="_blank"
        class="hover:text-teal-600"
      >
        <h2 class="text-center p-4 hover:text-teal-600">
          Gato Shell Game
        </h2></a
      >
      <div class="flex flex-col-reverse p-4 lg:flex-row lg:justify-between">
        <div class="lg:px-4 my-2 lg:my-0">
          <img
            class="border-4 border-pink-300 rounded-bl-xl"
            src="../assets/images/gato-shell-game.gif"
            alt="Gato Shell Game"
          />
        </div>
        <section
          class="flex flex-col justify-between gap-2 lg:w-3/5 p-8 bg-teal-100 rounded-tr-xl border-2 border-teal-300"
        >
          <h3>
            Gato Shell Game
          </h3>
          <article class="mb-4">
            <p>
              Gato Shell Game is an experiment with vanilla SVG animation. Also
              just for fun.
            </p>
            <br />
            <p>
              After all, who wouldn't like to see a cat playing with shells?
            </p>
          </article>
          <div class="flex flex-row gap-x-6 items-center">
            <a
              href="https://gato-shell-game.netlify.app/"
              class="no-underline bg-pink-500 hover:bg-pink-300 text-white font-bold py-2 px-4 rounded border-b-4 border-pink-700 text-center"
            >
              Play with Gato
            </a>
            <a href="https://github.com/lunaceee/gato-shell-game"
              ><svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
                class="feather feather-github hover:text-pink-500"
              >
                <path
                  d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
                ></path></svg
            ></a>
          </div>
        </section>
      </div>
    </div>
    <div class="grid mt-20">
      <a
        href="https://www.netlify.com/"
        target="_blank"
        class="hover:text-teal-600"
      >
        <h2 class="text-center p-4 text-3xl hover:text-teal-600">
          Netlify
        </h2></a
      >

      <div class="flex w-full gap-x-8 justify-center p-10">
        <img class="p-2 w-1/4" src="../assets/images/form-illo.svg" alt="" />
        <img
          class="p-2 w-1/4"
          src="../assets/images/functions-illo.svg"
          alt=""
        />
        <img
          class="p-2 w-1/4"
          src="../assets/images/identity-illo.svg"
          alt=""
        />
        <img class="p-2 w-1/4" src="../assets/images/lm-illo.svg" alt="" />
      </div>
      <p class="text-center mb-10">
        <small class="text-teal-800">Imagery credits from netlify.com</small>
      </p>
      <section class="flex flex-col gap-2 lg:flex-row p-2 lg:gap-0">
        <article
          class="p-8 bg-teal-100 rounded-tl-xl border-2 border-teal-300 rounded-br-xl lg:my-0"
        >
          <p>
            I joined Netlify at early stage. As one of the three front end
            engineers, I helped build features for Netlify's developer admin
            interface, particularly for Forms, Functions, Identity and Large
            Media features.
          </p>
          <br />

          <p>
            Meanwhile, I was the key project owner and maintainer for the
            <a href="https://docs.netlify.com/">docs site</a> and the
            <a href="https://outbound-emails.netlify.com/"
              >outbound mailing system</a
            >.
          </p>
        </article>
        <img class="lg:px-4" src="../assets/images/form-illo-2.svg" alt="" />
      </section>
    </div>
  </main>
</template>
<script>
export default {
  name: "Main"
};
</script>