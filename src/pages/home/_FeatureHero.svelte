<script>
  import { Section, HeroHeader } from "flowbite-svelte-blocks";
  import { Button, DeviceMockup } from "flowbite-svelte";
  import { ArrowRightOutline } from "flowbite-svelte-icons";
  import ParallaxDevices from "./_ParallaxDevices.svelte";
</script>

<Section name="heroVisual">
  <div class="mx-auto place-self-center lg:col-span-7">

    <HeroHeader
      h1Class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight !leading-[1.05] md:text-5xl xl:text-6xl dark:text-white"
      pClass="max-w-2xl mb-6 font-light text-gray-500 lg:mb-8 md:text-lg lg:text-xl dark:text-gray-200"
    >
      <svelte:fragment slot="h1">
         <a
          href="https://notion.so"
          target="_blank"
          zclass="decoration-6 underline-offset-3 underline decoration-primary-200"
        >
          <!-- Notion -->
          <mark
            href="https://notion.so"
            class="my-1 rounded bg-primary-50 px-2 py-0 text-white dark:bg-primary-700"
            >Iván Mouzo</mark
          >
        </a>
        <p/>
        Backend developer
      </svelte:fragment>
      <svelte:fragment slot="paragraph">
        <div class="hidden sm:block">
          <span class="font-bold text-primary-200">¡Hola!</span>  Soy Iván Mouzo Bellino, 
          técnico electrónico y desarrollador de software con una gran pasión por la 
          <span class="font-bold text-primary-200">tecnología</span>, el mundo <span class="font-bold text-primary-200">DIY</span>
           y el <span class="font-bold text-primary-200">Machine Learning</span>.
          
        </div>
      </svelte:fragment>
    </HeroHeader>

    <div
      class="md:text-md lg:text-md mb-6 max-w-2xl font-light text-gray-500 dark:text-gray-200 lg:mb-8"
    ><p>Desde mis inicios en mantenimiento electrónico, he adquirido experiencia en el desarrollo de proyectos que combinan 
      la programación a bajo nivel con <span class="font-semibold">microcontroladores y PLCs</span>. A lo largo de mi carrera, he trabajado en áreas tan diversas 
      como la 
      <span class="font-semibold">electrónica de investigación oceanográfica</span>, automatización y el desarrollo de aplicaciones web y móviles. 
      Me considero una persona comprometida con el <span class="font-semibold">aprendizaje continuo y el desarrollo personal</span>, buscando siempre nuevos 
      retos que me permitan seguir creciendo.</p>
      <br>
      <p>
        Actualmente, trabajo como programador 
        <span style="color: #61368C;">backend en Duacode</span>, 
        donde utilizo tecnologías como 
        <span style="color: #93C745;">NodeJS</span> 
        con 
        <span style="color: #E2274F;">NestJS</span> 
        y <span style="color: #F5A623;">Express</span> para el desarrollo de servicios, 
        <span style="color: #FC6D26;">GitLab</span> para la integración continua, 
        <span style="color: #0DB7ED;">Docker Compose</span> para la virtualización, 
        <span style="color: #47A248;">MongoDB</span> y 
        <span style="color: #00758F;">MySQL</span> como bases de datos. Además, documento las APIs utilizando 
        <span style="color: #85EA2D;">Swagger</span>.
      </p>
      
      <div class="mt-8 flex flex-col gap-2 sm:flex-row sm:gap-0">

        <a
          href="https://github.com/Mouzotech"
          target="_blank"
          ><Button
            color="light"
            size="xl"
            class="inline-flex items-center justify-center"
            >Github</Button
          >
        </a>
      </div>
    </div>
  </div>
</Section>
