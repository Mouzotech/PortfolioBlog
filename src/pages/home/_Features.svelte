<script lang="ts">
  import { Section, HeroHeader, FeatureDefault, FeatureItem } from "flowbite-svelte-blocks";
  import nodeLogo from '/public/images/node-logo.png';
  
</script>

<Section name="feature">
  <HeroHeader
    class="mx-auto mb-8 max-w-screen-md sm:mx-0 lg:mb-16"
    h2Class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white"
    pClass="text-gray-500 sm:text-xl dark:text-gray-400"
  >
    <svelte:fragment slot="h2">Mis Habilidades y Competencias</svelte:fragment>
    <svelte:fragment slot="paragraph">
      Desarrollador enfocado en tecnologías modernas, programación avanzada y soluciones robustas.
    </svelte:fragment>
  </HeroHeader>

  <FeatureDefault>
    <!-- Java -->
    <FeatureItem>
      <svelte:fragment slot="icon">
        <img src="/images/Java logo.webp" alt="Java logo" class="w-12 h-12" />
      </svelte:fragment>
      <svelte:fragment slot="h3">Java</svelte:fragment>
      <svelte:fragment slot="paragraph">
        Desarrollo de aplicaciones robustas en backend con Java y Spring Boot.
      </svelte:fragment>
    </FeatureItem>

    <!-- NodeJS -->
    <FeatureItem>
      <svelte:fragment slot="icon">
        <img src="/images/node-logo.png" alt="NodeJS logo" class="w-12 h-12" />
      </svelte:fragment>
      <svelte:fragment slot="h3">NodeJS (NestJS y Express)</svelte:fragment>
      <svelte:fragment slot="paragraph">
        Creación de APIs eficientes y escalables para el backend.
      </svelte:fragment>
    </FeatureItem>

    <!-- Docker -->      
    <FeatureItem>
      <svelte:fragment slot="icon">
        <img src="/images/docker-logo.png" alt="Docker logo" class="w-12 h-12" />
      </svelte:fragment>
      <svelte:fragment slot="h3">Docker & Docker Compose</svelte:fragment>
      <svelte:fragment slot="paragraph">
        Virtualización y despliegue de entornos en contenedores.
      </svelte:fragment>
    </FeatureItem>

    <!-- MySQL -->
    <FeatureItem>
      <svelte:fragment slot="icon">
        <img src="/images/mysql-logo.png" alt="MySQL logo" class="w-12 h-12" />
      </svelte:fragment>
      <svelte:fragment slot="h3">MongoDB y MySQL</svelte:fragment>
      <svelte:fragment slot="paragraph">
        Gestión de bases de datos NoSQL y SQL.
      </svelte:fragment>
    </FeatureItem>

    <!-- Linux -->
    <FeatureItem>
      <svelte:fragment slot="icon">
        <img src="/images/linux-logo.png" alt="Linux logo" class="w-12 h-12" />
      </svelte:fragment>
      <svelte:fragment slot="h3">Linux</svelte:fragment>
      <svelte:fragment slot="paragraph">
        Gestión avanzada de sistemas Linux para desarrollo y administración.
      </svelte:fragment>
    </FeatureItem>

    <!-- Git -->
    <FeatureItem>
      <svelte:fragment slot="icon">
        <img src="/images/git-logo.webp" alt="Git logo" class="w-12 h-12" />
      </svelte:fragment>
      <svelte:fragment slot="h3">Git & GitLab</svelte:fragment>
      <svelte:fragment slot="paragraph">
        Control de versiones y CI/CD para proyectos colaborativos.
      </svelte:fragment>
    </FeatureItem>

    <!-- Swagger -->
    <FeatureItem>
      <svelte:fragment slot="icon">
        <img src="/images/Swagger-logo.jpg" alt="Swagger logo" class="w-12 h-12" />
      </svelte:fragment>
      <svelte:fragment slot="h3">Swagger</svelte:fragment>
      <svelte:fragment slot="paragraph">
        Documentación y testing de APIs REST.
      </svelte:fragment>
    </FeatureItem>

    <!-- Arduino -->
    <FeatureItem>
      <svelte:fragment slot="icon">
        <img src="/images/arduino-logo.png" alt="Arduino logo" class="w-12 h-12" />
      </svelte:fragment>
      <svelte:fragment slot="h3">Arduino & Raspberry Pi</svelte:fragment>
      <svelte:fragment slot="paragraph">
        Programación en C para sistemas embebidos y automatización.
      </svelte:fragment>
    </FeatureItem>

    <!-- Inglés Técnico -->
    <FeatureItem>
      
      <svelte:fragment slot="icon">
        
        <img src="/images/diploma-logo.jpg" alt="Inglés técnico logo" class="w-12 h-12" />
      </svelte:fragment>
      <svelte:fragment slot="h3">Inglés Técnico</svelte:fragment>
      <svelte:fragment slot="paragraph">
        Nivel C1, con experiencia en documentación y comunicación fluida en entornos profesionales.
      </svelte:fragment>
    </FeatureItem>
  </FeatureDefault>
  
</Section>
