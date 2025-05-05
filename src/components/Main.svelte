<script>
    import Step from "./Step.svelte";
    let steps = [
    {
        name:'NSA Website Development', 
        href:'https://aspiring-postage-b52.notion.site/NSA-Website-Development-1dbc68326201807ca046d0be1938cb28',
    }, 
    {
        name:'Health Hop',
        href:'https://aspiring-postage-b52.notion.site/Health-Hop-1dbc6832620180d8bf6ae292bc4a3fb5'
      },
      { 
          name: "Design and Optimization of a Foot Prosthesis", 
          href: "https://aspiring-postage-b52.notion.site/Design-and-Optimization-of-a-Foot-Prosthesis-174c683262018076949ff894e14d13f7"
       },
      {
          name: "Task Flow",
          href: "https://aspiring-postage-b52.notion.site/TaskFlow-1dcc683262018010ad1bca9baa5569f3?pvs=73",
      },
      { 
          name: "Splint Assist",
          href: "https://aspiring-postage-b52.notion.site/Splint-Assist-1dbc683262018023ba91e46605f3079c?pvs=73"
   },
  
      { name: "Patient Record" }, 
      { 
          name: "Amode Beamforming",
          href: "https://github.com/arnimashrestha/Ultrasound-A-Mode-Beamforming"
       },
      { name: "Hummingbird",
        href: "https://www.figma.com/file/gStyIoM7HrAdjHtf5uGnLa/Hummingbird?type=design&node-id=0%3A1&mode=design&t=s0C3zfAWPOybJ8IN-1"
       },
      {   name: "Vision Grip" ,
          href: "https://docs.google.com/document/d/10IKcVfJ7fYEUTWrPLGE3EPQcIUSwL8C5LTAZVRvqHME/edit?usp=sharing"
      },
      {   name: "Goostavo",
          href: "https://github.com/arnimashrestha/Goostavo/tree/main"
  
      },
    ];
  </script>
  
  <main class="flex flex-col flex-1 p-4">
    <section
      id="introPage"
      class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14"
    >
      <div
        class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
      >
        <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
          Hi! I'm <span class="poppins text-violet-400">Arnima </span> Shrestha
          <br />
          <span class="poppins text-violet-400">Biomedical Engineering</span> Student
        </h2>
        <h1 class= "font-semibold text-4xl sm:text-2xl md:text-3xl">At the University of <span class="poppins text-violet-400">Waterloo </span></h1>
        <p class="text-base sm:text-lg md:text-xl">
          My <span class="text-violet-400"> favourite tool's and tech </span> includes
          JavaScript(SvelteKit), TailwindCSS, HTML, C++, Python, TensorFlow, Figma,
          Solidworks, MatLab! <br>
                              <br>
                              As a Biomedical Engineering student passionate about  <span class="text-violet-400">human-centered design</span>  , I’ve had the opportunity to work across a wide range of scales—from engineering antibiotic-loaded microrobots for targeted drug delivery to exploring the use of social robots to support vulnerable populations. This range of experiences has deepened my interest in how technology can be thoughtfully designed to meet real human needs.
                              <br>
                              <br>
                              Most recently, I will be joining the <span class="text-violet-400">Social and Intelligent Robotics Research Lab</span>  as an undergraduate research assistant, where I’ll be working on the user interface and interaction design of social robots to improve engagement and accessibility for end users.
                                     
  
        <p>
          <!--<a class= "blueShadow mx-auto lg:mr-auto text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950 cursor-pointer"
                      href="a"
                      target="_blank"
                      >
                          <div 
                              class= "absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
                          />
                          <h4 class= "relative z-9"> Get in touch &rarr;</h4>
  
                      </a>
                  -->
        </p>
      </div>
      <div class="relative shadow-2xl grid place-items-center">
        <img
          src={"images/portpic2.png"}
          alt="Profile image"
          class="object-cover z-[2] max-h-[70vh]"
        />
      </div>
    </section>
  
    <section id="projects" class="py-20 lg:py-32 flex flex-col gap-24">
      <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10">
        <Step step= {steps[0]}>
          <p>
          A responsive web-app that follows mobile-first principle created for the UW Nepalese Student Association  
          <strong
              class="text-violet-400"> React, TailwindCSS and ShadCN UI
            </strong>
            was used to develop the front-end, 
            <strong
              class="text-violet-400"> Firebase
            </strong>
            was used to collect and store email submissions from new members
  
          </p>
        </Step>
        <Step step={steps[1]}>
          
          <p>
            Health Hop is a a UI/UX prototype that uses AI to analyze patient symptoms, providing verified professional and community insights. It connects users with local small business clinics, enhancing primary care efficiency and reducing ER and walk-in clinic stress. This prototype was created using <strong
              class="text-violet-400"
              >Figma</strong
            > using the M3 Design Frameworks! We won "Most Creative Prototype" at the UX/UW Frame Designathon out of 20 teams.
          </p>
        </Step>
        <Step step={steps[2]}>
          
          <p>
            This project aimed to validate and optimize the design of a prosthetic foot using Finite Element Analysis (FEA)  <strong
              class="text-violet-400"
              >in SolidWorks!</strong>
           While  <strong
           class="text-violet-400"> Python
         </strong> was used to analyze the resulting force and displacement after conducing a tensile test on a 3D printed PLA dogbone sample, simulating the material behaviour of the prosthetic foot.  
          </p>
        </Step>
        <Step step={steps[3]}>
          <p>
            TaskFlow is a prototype of a web-app productivity app focused on planning features, which was created using <strong class="text-violet-400"
              >Figma, Maze, and Google Forms</strong
            >
            This project focused on the fundamentals of 
            <strong class="text-violet-400">UX research, UI Design and Usability Testing</strong>
           
          </p>
        </Step>
        <Step step={steps[4]}>
          <p>
            SplintAssist was developed to design a biomedical solution to support stroke survivor, where skills such as   <strong class="text-violet-400"
              >Needs Assessment & Requirement Engineering, Prototyping and Rapid Iteration, CAD Modelling, Engineering Analysis, Materials Research and Selection</strong
            > were strengthened. This was created in a mere 36 hours at MedSprint 2024 at McMaster University
          </p>
        </Step>
        <Step step={steps[5]}>
          <p>
            Patient Record is a <strong class="text-violet-400"
              >C++
            </strong>program that sorts patient information stored in an external
            textfile according to user-input. The user is able to sort via 5
            categories: (Age, ID, First Name, Last Name, Sex) in the terminal, and
            will receive the sorted information back in the terminal
          </p>
        </Step>
        <Step step={steps[6]}>
          <p>
            Amode Beamforming was created using <strong class="text-violet-400"
              >C++</strong
            >. This program is for ultrasound imaging,which can reads echo data,
            perform beamforming calculations and write resulting scanline to an
            Excel file for display
          </p>
        </Step>
    

  
  
  
      </div>
    </section>
  </main>
  