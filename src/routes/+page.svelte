<script>
  const projects = [
    {
      title: "Koikoi – Booking App (2024)",
      description: "A ticket booking platform built using Next.js, MongoDB, NextAuth, Zod, and Tailwind CSS. Includes SEO, dynamic sitemap/robots, and responsive UI.",
      link: "https://koikoi.vercel.app"
    }
  ];
</script>

<section class="max-w-2xl mx-auto px-4 py-16 space-y-16">

  <!-- HERO -->
  <div class="text-center space-y-3">
    <h1 class="text-3xl font-bold">Thangjam Binson Singh</h1>
    <p class="text-gray-600 text-base">
      Frontend Developer • Svelte & SvelteKit
    </p>

    <div class="flex justify-center gap-4 text-sm">
      <a href="https://github.com/binnixie01" target="_blank" class="underline text-blue-600">
        GitHub
      </a>
      <a href="https://www.linkedin.com/in/binson-thangjam" target="_blank" class="underline text-blue-600">
        LinkedIn
      </a>
      <a href="mailto:binsonthangjam7@gmail.com" class="underline text-blue-600">
        Email
      </a>
    </div>
  </div>

  <!-- ABOUT -->
  <div class="space-y-2">
    <h2 class="text-xl font-semibold">About Me</h2>
    <p class="text-gray-700 leading-6 text-sm">
      I’m a frontend developer focused on building clean, fast, and user-friendly interfaces.
      I work with Svelte, SvelteKit, Tailwind CSS, and modern web tools to create smooth and
      responsive web experiences.
    </p>
  </div>
<!-- EXPERIENCE -->
<div>
  <h2 class="text-xl font-semibold mb-2">Experience</h2>

  <div class="border border-gray-300 rounded-xl p-4 text-sm space-y-2">
    <h3 class="font-semibold text-gray-900">
      Frontend Developer — MakerStudio (Full-time)
    </h3>

    <p class="text-gray-600">
      Oct 2024 – Present • Remote (Wyoming, United States)
    </p>

    <ul class="list-disc ml-5 space-y-1 text-gray-700">
      <li>Building responsive and user-friendly interfaces for web applications.</li>
      <li>Developing reusable frontend components and improving overall UI consistency.</li>
      <li>Working with dynamic data, interactive elements, and modern frontend workflows.</li>
      <li>Collaborating with remote teams and maintaining clean, structured code.</li>
    </ul>
  </div>
</div>

  <!-- SKILLS -->
  <div>
    <h2 class="text-xl font-semibold mb-2">Skills</h2>

    <div class="flex gap-2 overflow-x-auto pb-2 text-sm">
      {#each [
        "Svelte",
        "SvelteKit",
        "JavaScript",
        "TypeScript",
        "Next.js",
        "React",
        "Flutter",
        "React Native",
        "Tailwind CSS",
        "Skeleton UI",
        "REST APIs",
        "Zod",
        "Git",
        "MongoDB"
      ] as skill}
        <span class="border border-gray-300 whitespace-nowrap px-3 py-1 rounded-lg">
          {skill}
        </span>
      {/each}
    </div>
  </div>

  <!-- PROJECTS -->
  <div>
    <h2 class="text-xl font-semibold mb-4">Projects</h2>

    <div class="space-y-5">
      {#each projects as p}
        <div class="border border-gray-300 rounded-xl p-4">
          <h3 class="text-lg font-semibold text-gray-900">{p.title}</h3>

          <p class="text-gray-700 text-sm my-1">
            {p.description}
          </p>

          <a href={p.link}
             target="_blank"
             class="text-blue-600 text-sm underline">
            View Project
          </a>
        </div>
      {/each}
    </div>
  </div>
  <!-- EDUCATION -->
<div>
  <h2 class="text-xl font-semibold mb-2">Education</h2>

  <div class="border border-gray-300 rounded-xl p-4 text-sm space-y-2">
    <div>
      <h3 class="font-semibold">D.M. College of Science, Dhanamanjuri University Manipur</h3>
      <p class="text-gray-600">B.Sc (Hons) in Computer Science • Aug 2021 – Jun 2024</p>
    </div>

    <div class="pt-2">
      <h3 class="font-semibold">Army Public School, Pune</h3>
      <p class="text-gray-600">Apr 2013 – Mar 2020</p>
    </div>
  </div>
</div>


  <!-- CONTACT -->
  <div class="space-y-1">
    <h2 class="text-xl font-semibold">Contact</h2>
    <p class="text-gray-700 text-sm">
      Email:
      <a href="mailto:binsonthangjam7@gmail.com"
         class="underline text-blue-600">
        binsonthangjam7@gmail.com
      </a>
    </p>

    <p class="text-gray-700 text-sm">
      Phone: +91 6009786052
    </p>
  </div>

</section>
