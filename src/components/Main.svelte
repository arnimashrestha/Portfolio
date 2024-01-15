<script>
  import Step from "./Step.svelte";
  let steps = [
    { 
        name: "DailyGlow", 
        href: "https://github.com/Breeze3250/DailyGlow"
     },
    {
        name: "AI Devangari Letter Recognizer",
        href: "https://github.com/arnimashrestha/ai-text-recognizer",
    },
    { 
        name: "Repro",
        href: "https://github.com/DarkDestroyer888/HT6_2023"
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
    { name: "Peristaltic Pump Rotor" },
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
        As a future biomedical engineer, my mission is clear: to engineer solutions that restore independence to bodies facing limitations.
        My ultimate goal is to design and develop technical and mechanical life-saving devices that contribute to fostering <span class="text-violet-400">equitable living conditions </span> for all.

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
        src={"images/profileportfolio.png"}
        alt="Profile image"
        class="object-cover z-[2] max-h-[70vh]"
      />
    </div>
  </section>

  <section id="projects" class="py-20 lg:py-32 flex flex-col gap-24">
    <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10">
      <Step step={steps[0]}>
        <p>
          Daily Glow is a responsive notification web application created with <strong
            class="text-violet-400"
            >Figma, JavaScript, HTML, CSS, Python Flask and Tiny Db!</strong
          > JavaScript, HTML and CSS form the foundation of the frontend, enabling
          an interactive user experience, while Python Flask and TinyDB handle the
          backend tasks, ensuring data storage, retriavble, overall application functionality
        </p>
      </Step>
      <Step step={steps[1]}>
        <p>
          AI Devangari Letter Recognizer is a deep learning language model
          created using <strong class="text-violet-400"
            >Python TensorFlow, NumPy, Pandas, cv2</strong
          >
          to predict user-drawn Devangari characters with a 93% accuracy.
          <strong class="text-violet-400">cV2</strong>
          allowed user's to use their trackpad to draw in an letter, and could use
          their trackpad.
          <strong class="text-violet-400">Tensorflow's Keras</strong> allowed for
          the detection of the correct letter
        </p>
      </Step>
      <Step step={steps[2]}>
        <p>
          Repro is an application for low-income women to aid their fertility
          journey using new temperature tracking based technology to track
          ovulation cycles created with <strong class="text-violet-400"
            >Figma, CSS, JavaScript and HTML.</strong
          >This was created in a mere 36 hours at Hack 6ix 2023
        </p>
      </Step>
      <Step step={steps[3]}>
        <p>
          Patient Record is a <strong class="text-violet-400"
            >C++
          </strong>program that sorts patient information stored in an external
          textfile according to user-input. The user is able to sort via 5
          categories: (Age, ID, First Name, Last Name, Sex) in the terminal, and
          will receive the sorted information back in the terminal
        </p>
      </Step>
      <Step step={steps[4]}>
        <p>
          Amode Beamforming was created using <strong class="text-violet-400"
            >C++</strong
          >. This program is for ultrasound imaging,which can reads echo data,
          perform beamforming calculations and write resulting scanline to an
          Excel file for display
        </p>
      </Step>
    <Step step= {steps[6]}>
        <p>
            Vision Grip is an 3-level adjustable glasses holder that is currently under developement using
            <strong class="text-violet-400"
            >SolidWorks</strong > Vision Grip meets <strong class="text-violet-400"
            >design standards</strong > as it is quick to assemble, has minimal parts
             and has intuitive asymmetrical attachments
        </p>
    </Step>
    <Step step= {steps[7]}>
        <p>
            Goostavo is a fun minature goose that was created using <strong class="text-violet-400">SolidWorks, Z-Suite and Solidworks Composer</strong > 
            Goostavo consists of 5 unique parts. Its body piece consists a  <strong class="text-violet-400"> slot mechanism,</strong> that allows its wings to flap when its head is pulled up and down
        </p>
    </Step>
    <Step step= {steps[5]}>
        <p> Hummingbird is an app that locates essential products for underprivileged communities in Waterloo. Hummingbird's initial design was created in <strong class="text-violet-400"> Figma</strong> and presented at the Smart Waterloo Region Innovation Fair and awared $2000
        </p>

    </Step>



    </div>
  </section>
</main>
