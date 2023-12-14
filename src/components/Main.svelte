<script>
    import Step from "./Step.svelte";

    let steps = [
        {
            name: "FilmHub",
            icon: "fa-solid fa-film",
            description:
                "Filmhub, is a dynamic web application built with React, leveraging the OMDb API. This innovative platform provides an interactive cinematic experience, allowing users to discover and explore a diverse selection of films, all within a user-friendly and immersive interface.",
        },
        {
            name: "Netfilx-clone",
            icon: "fa-solid fa-question",
            description:
            "  Embracing a challenge to enhance my skills, I undertook the ambitious project of creating a Netflix clone using Next.js, Tailwind CSS, NextAuth, and a MongoDB database with Prisma. This endeavor provided me with a valuable opportunity to learn and gain hands-on experience with Next.js, while delving into the intricacies of developing a complete application",
        },
     
    ];


</script>

<main class="flex flex-col flex-1 p-4">
    <section id="introPage" class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14">
        <div class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10">
            <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
                Hi! I'm <span class="poppins text-violet-400">Sèdjro Manoel </span>SELOVE <br/>Full Stack <span class="poppins text-violet-400">Developer</span>
            </h2>
            <p class="text-base sm:text-lg md:text-xl">
                My <span class="text-violet-400"> favorite tech </span> includes Javascript (NextJS,Typescript, React, Svelte, Sveltekit, Node JS + EXpressJS & Mongo DB), Tailwind CSS, PHP
            </p>
            <!--a  class=" blueShadow mx-auto lg:mr-auto text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950" href="#">
                <div
                class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
            />
            <h4 class="relative z-9">Get in touch &rarr;</h4>
            </a-->
        </div>
        <div class="relative shadow-2xl grid place-items-center">
            <img src={"images/profile.JPG"} alt="maphoto"
            class="object-cover z-[2] max-h-[70vh]">
        </div>
    </section>


    <!--Project Section-->

    <section id="projects" class="py-20 lg:py-32 flex flex-col gap-24">
        <div class="flex flex-col gap-2 text-center">
            <h6 class="text-lg sm:text-xl md:text-2xl">
                A few of my creative projects
            </h6>
            <h3>Curious to <span class="font-semibold text-3xl sm:text4xl md:text-5xl">
                see</span> my work ?
            </h3>
        </div> 

    

        <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10">
            <Step step = {steps[0]}>
                <p>
    
                </p>

            </Step>

            <Step step = {steps[1]}>
                <p>
                  
                </p>

            </Step>

          
        </div>
    </section>

    <!--about section-->

    <section id="about" class="-py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative">
        <div
        class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-violet-700 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-violet-700 py-4"
        >
        <h6 class="text-large sm:text-xl md:text-2xl">
            Want to know more?
        </h6>
        <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
            A bit <span class="poppins text-violet-400">about</span> me.
        </h3>
        </div>

        <!--Tableau des offres-->
        <h5 class={" text-2xl sm:text-3xl font-semibold text-center poppins "}>
            The <span class="text-violet-400">Complete</span> Package
        </h5>
        <div
            class="flex flex-col overflow-x-scroll gap-10 max-w-[800px] mx-auto w-full"
        >
            <table class="bg-white text-slate-700 rounded text-center">
                <thead class={"border-b border-solid border-slate-200  "}>
                    <tr class="">
                        <th />
                        <th class="whitespace-nowrap p-2 px-4">Candidate #1</th>
                        <th class="whitespace-nowrap p-2 px-4">Candidate #2</th>
                        <th class="whitespace-nowrap p-2 px-4">Candidate #3</th>
                        <th
                            class="bg-violet-700 text-white whitespace-nowrap p-4 px-8"
                            >Me</th
                        >
                    </tr>
                </thead>
                <tbody>
                    <tr class="border-b border-solid border-slate-200">
                        <td
                            class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                            >Soft Skils & Collaborative Team Player</td
                        >
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-green-500" /></td>
                    </tr>
                    <tr class="border-b border-solid border-slate-200">
                        <td
                            class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                            >Curiosity and Continuous Learning</td
                        >
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-green-500" /></td>
                    </tr>
                    <tr>
                        <td
                            class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                            > Collaboration and Communication</td
                        >
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-green-500" /></td>
                    </tr>
                    <tr class="border-t border-solid border-slate-200">
                        <td
                            class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                            >Progamming Ability & Problem Solving</td
                        >
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-green-500" /></td>
                    </tr>
                </tbody>
            </table>
        </div>
        <p class="mx-auto  font-bold text-5xl">So why not invest ?</p>

    </section>

</main>

   








  
  
  