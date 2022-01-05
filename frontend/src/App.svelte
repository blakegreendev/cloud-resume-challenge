<script>
  import "../tailwind.css"
  let count = ''
  fetch(import.meta.env.VITE_APP_API_URL, {
    method: "POST",
  })
    .then((response) => response.text())
    .then((data) => {
      count = data;
  });
</script>

<body class="font-sans antialiased w-full">
    <div class="container mx-auto max-w-screen-xl">
      <main
        id="wrapper"
        class="flex flex-col sm:flex-row-reverse sm:m-12 shadow-2xl"
      >
        <div
          id="sidebar"
          class="w-full sm:max-w-sm p-8 bg-gradient-to-b from-indigo-300 via-green-300 to-white"
        >
          <div class="px-2 mb-12">
            <h1 class="text-center text-3xl font-semibold mb-2">Blake Green</h1>
            <h2 class="text-center text-xl font-light">Cloud Architect</h2>
          </div>

          <div class="font-light text-lg px-2 mb-12">
            <h2 class="text-xl font-semibold mb-4">Contact</h2>
            <div class="flex items-center my-3">
              <ion-icon
                name="mail-outline"
                size="large"
                class="inline w-6 mr-4"
                alt="Mail icon"
              />
              <a href="mailto:">blakegreen@msn.com</a>
            </div>
            <div class="flex items-center my-3">
              <ion-icon
                name="earth-outline"
                size="large"
                class="inline w-6 pb-1 mr-4"
                alt="House icon"
              />
              <div>
                <p>Charlotte, NC</p>
              </div>
            </div>
          </div>

          <div class="font-light text-lg px-2 mb-12">
            <h2 class="text-xl font-semibold mb-4">On the Web</h2>
            <div class="flex items-center my-3">
              <ion-icon
                name="globe-outline"
                size="large"
                class="inline w-6 mr-4"
                alt="Globe icon"
              />
              <a href="https://blakegreen.dev" target="_blank" rel="noopener noreferrer"
                >Website</a
              >
            </div>
            <div class="flex items-center my-3">
              <ion-icon
                name="logo-twitter"
                size="large"
                class="inline w-6 mr-4"
                alt="Twitter Logo"
              />
              <a href="https://twitter.com/blakegreendev" target="_blank" rel="noopener noreferrer"
                >Twitter</a
              >
            </div>
            <div class="flex items-center my-3">
              <ion-icon
                name="logo-github"
                size="large"
                class="inline w-6 mr-4"
                alt="GitHub Logo"
              />
              <a href="https://github.com/blakegreendev" target="_blank" rel="noopener noreferrer">GitHub</a>
            </div>
            <div class="flex items-center my-3">
              <ion-icon
                name="logo-linkedin"
                size="large"
                class="inline w-6 mr-4"
                alt="LinkedIn Logo"
              />
              <a href="https://www.linkedin.com/in/blakegreen2/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
            </div>

            <div class="flex items-center my-3">
              <ion-icon
                name="logo-youtube"
                class="inline w-6 mr-4"
                size="large"
                alt="Youtube Logo"
              />
              <a href="https://www.youtube.com/channel/UCMe8VAatUrLtJVRRM5300ug" target="_blank" rel="noopener noreferrer">YouTube</a>
            </div>

          </div>

          <div class="font-light text-lg px-2 mb-12">
            <h2 class="text-xl font-semibold mb-4">Skills</h2>
            <ul class="list-none">
              <li>
                <p class="leading-8">
                  <span class="rounded-xl bg-gray-300 px-3">AWS</span>
                  <span class="rounded-xl bg-gray-300 px-3">CDK</span>
                  <span class="rounded-xl bg-gray-300 px-3">Serverless</span>
                  <span class="rounded-xl bg-gray-300 px-3">DynamoDB</span>
                  <span class="rounded-xl bg-gray-300 px-3">Docker</span>
                  <span class="rounded-xl bg-gray-300 px-3">Python</span>
                  <span class="rounded-xl bg-gray-300 px-3">Typescript</span>
                  <span class="rounded-xl bg-gray-300 px-3">Github</span>
                </p>
              </li>
            </ul>
          </div>
          <div class="font-light text-lg px-2 mb-12">
            <h2 class="text-xl font-semibold mb-4">Certifications</h2>
            <ul class="list-none">
              <div class="flex items-center my-3">
                <ion-icon
                  name="trophy-outline"
                  size="large"
                  class="inline w-6 mr-4"
                  alt="Globe icon"
                />
                <a href="https://www.credly.com/badges/84a3f833-31ed-4afe-9002-61f644a1c0da/public_url" target="_blank" rel="noopener noreferrer"
                  >AWS Solutions Architect – Professional</a
                >
              </div>
              <div class="flex items-center my-3">
                <ion-icon
                  name="trophy-outline"
                  size="large"
                  class="inline w-6 mr-4"
                  alt="Globe icon"
                />
                <a href="https://www.credly.com/badges/f8cb4aad-8999-405a-a193-7de480491ac7/public_url" target="_blank" rel="noopener noreferrer"
                  >AWS DevOps Engineer – Professional</a
                >
              </div>
              <div class="flex items-center my-3">
                <ion-icon
                  name="trophy-outline"
                  size="large"
                  class="inline w-6 mr-4"
                  alt="Globe icon"
                />
                <a href="https://www.credly.com/badges/f7e47930-b686-4e8a-a7a7-8e93f6152bb1/public_url" target="_blank" rel="noopener noreferrer"
                  >AWS Security – Specialty</a
                >
              </div>
              <div class="flex items-center my-3">
                <ion-icon
                  name="trophy-outline"
                  size="large"
                  class="inline w-6 mr-4"
                  alt="Globe icon"
                />
                <a href="https://www.credly.com/badges/4d05fa7e-08b5-4bda-bd2c-a58bb9a0bb58/public_url" target="_blank" rel="noopener noreferrer"
                  >AWS Advanced Networking – Specialty</a
                >
              </div>
              <div class="flex items-center my-3">
                <ion-icon
                  name="trophy-outline"
                  size="large"
                  class="inline w-6 mr-4"
                  alt="Globe icon"
                />
                <a href="https://www.credly.com/badges/3c03c536-27d1-4a27-b904-829accbb454d/public_url" target="_blank" rel="noopener noreferrer"
                  >AWS Solutions Architect – Associate</a
                >
              </div>
              <div class="flex items-center my-3">
                <ion-icon
                  name="trophy-outline"
                  size="large"
                  class="inline w-6 mr-4"
                  alt="Globe icon"
                />
                <a href="https://www.credly.com/badges/f0b2e7cf-ab7c-4a02-b21a-373e02d7603e/public_url" target="_blank" rel="noopener noreferrer"
                  >AWS Developer – Associate</a
                >
              </div>
              <div class="flex items-center my-3">
                <ion-icon
                  name="trophy-outline"
                  size="large"
                  class="inline w-6 mr-4"
                  alt="Globe icon"
                />
                <a href="https://www.credly.com/badges/056a8fcd-c867-4eda-910b-1c6a7d21902f/public_url" target="_blank" rel="noopener noreferrer"
                  >AWS SysOps Administrator – Associate</a
                >
              </div>
              <div class="flex items-center my-3">
                <ion-icon
                  name="trophy-outline"
                  size="large"
                  class="inline w-6 mr-4"
                  alt="Globe icon"
                />
                <a href="https://www.credly.com/badges/6cd182f3-8b00-4a5c-a5a2-080bed8a3a36/public_url" target="_blank" rel="noopener noreferrer"
                  >HashiCorp - Terraform Associate</a
                >
              </div>
            </ul>
          </div>

          <div class="font-light text-lg px-2 mb-12">
            <h2 class="text-xl font-semibold mb-4">Education</h2>
            <h3 class="font-semibold">BS Computer Science</h3>
            <p>University of Maryland <br>Global Campus</p>
          </div>

        </div>
        <div class="content w-full p-12">
          <div id="profile" class="prose">
            <h2 class="section-headline">Profile</h2>
            <p>
              👋  Hi, I'm Blake Green. I am a Principal Cloud Architect and Delivery Lead. I am very passionate about cloud technology and delivering solutions to clients. I'm currently focused on cloud security and cloud infrastructure automation in AWS.  
            </p>
          </div>
          <hr class="mt-8 mb-12" />
          <div id="experience" class="prose">
            <h2 class="section-headline">Experience</h2>
            <div>
              <h3>InterVision Systems</h3>
              <section class="mb-6">
                <div class="lg:inline-block lg:w-3/12 lg:align-top italic mb-2">
                  May 2014 - Present:
                </div>
                <div class="lg:inline-block lg:w-8/12 w-full">
                  Principal Cloud Architect & Delivery Lead
                </div>
              </section>
              <section class="mb-6">
                <div class="lg:inline-block lg:w-3/12 lg:align-top italic mb-2">
                  Description:
                </div>
                <div class="lg:inline-block lg:w-8/12 w-full">
                  As a Principal Cloud Architect and Delivery Lead, I am responsible for leading the creation of a technology framework and providing technical leadership in support of client initiatives in cloud computing and automation, with a focus on the design of systems and services that run on cloud platforms. With this unique role, I work closely with clients during the presales solutioning all the way through the successful delivery of their cloud journey.
                </div>
              </section>
              <section class="mb-6">
                <div class="lg:inline-block lg:w-3/12 lg:align-top italic mb-2">
                  Tools:
                </div>
                <div class="lg:inline-block lg:w-8/12 w-full">
                  <span class="rounded-xl bg-gray-300 px-3">AWS</span>
                  <span class="rounded-xl bg-gray-300 px-3">Serverless</span>
                  <span class="rounded-xl bg-gray-300 px-3">Docker</span>
                  <span class="rounded-xl bg-gray-300 px-3">Github</span>
                </div>
              </section>
            </div>
          </div>
          <hr class="mt-8 mb-12" />
          <div id="projects" class="prose">
            <h2 class="section-headline">Projects</h2>
            <div class="mb-16">
              <h3 id="chrisko-headline">blakegreen.dev</h3>
              <section class="mb-6">
                <div class="lg:inline-block lg:w-3/12 lg:align-top italic mb-2">
                  Personal blog:
                </div>
                <div class="lg:inline-block lg:w-8/12 w-full">
                  My blog is the center of my online presence. Here, I share
                  posts about what I've learnt, tutorials and my thoughts on web
                  development in general.
                </div>
              </section>
              <section class="mb-6">
                <div class="lg:inline-block lg:w-3/12 lg:align-top italic mb-2">
                  Deployed to:
                </div>
                <div class="lg:inline-block lg:w-8/12 w-full">
                  <a
                    href="https://blakegreen.dev"
                    target="_blank"
                    rel="noopener noreferrer"
                    >blakegreen.dev</a
                  >
                </div>
              </section>
              <section class="mb-6">
                <div class="lg:inline-block lg:w-3/12 lg:align-top italic mb-2">
                  Code on:
                </div>
                <div class="lg:inline-block lg:w-8/12 w-full">
                  <a
                    href="#"
                    target="_blank"
                    rel="noopener noreferrer"
                    >GitHub/nextjs-blog</a
                  >
                </div>
              </section>
              <section class="mb-6">
                <div class="lg:inline-block lg:w-3/12 lg:align-top italic mb-2">
                  Features:
                </div>
                <div class="lg:inline-block lg:w-8/12 w-full">
                  <ul>
                    <li>Static generation</li>
                    <li>Blog content written in Markdown</li>
                    <li>Counter for pageviews and likes</li>
                    <li>My latest tweets</li>
                    <li>Featured images made with Inkscape</li>
                    <li>SEO</li>
                  </ul>
                </div>
              </section>

              <section class="mb-6">
                <div class="lg:inline-block lg:w-3/12 lg:align-top italic mb-2">
                  Built with:
                </div>
                <div class="lg:inline-block lg:w-8/12 w-full">
                  <span class="rounded-xl bg-gray-300 px-3">Next.js</span>
                  <span class="rounded-xl bg-gray-300 px-3">CSS</span>
                  <span class="rounded-xl bg-gray-300 px-3">styled-jsx</span>
                  <span class="rounded-xl bg-gray-300 px-3">DynamoDB</span>
                  <span class="rounded-xl bg-gray-300 px-3">Vercel</span>
                </div>
              </section>
            </div>
          </div>
        </div>
      </main>
    </div>
    <footer
      class="mt-12 text-center flex justify-center flex-col md:flex-row mx-12"
    >
      <a
        href="https://blakegreen.dev/"
        class="text-sm px-4 py-2 m-2 text-gray-600 border-gray-400 border-2 rounded flex-shrink-0"
        >Made with ❤️ by blakegreendev</a
      >
      <p
        class="text-sm px-4 py-2 m-2 text-gray-600 border-gray-400 border-2 rounded flex-shrink-0"
        >Number of Visitors: {count}
      </p>

    </footer>
    <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
  </body>
