<script setup>
import { Head, Link } from '@inertiajs/vue3';
import Navbar from '../Components/Navbar.vue';
import CircleProgress from '../Components/CircleProgress.vue';
import SimpleProgressBar from '../Components/SimpleProgressBar.vue';



</script>

<template>
    <Navbar />
    <!-- Profil -->
    <div class="h-screen w-[30%] bg-green-200 fixed flex -z-1">
        <img src="/images/1707585139520.jpg" alt="" class="object-cover block  w-full h-auto"/>
        <div class="absolute inset-0 bg-[#68e0cf] bg-opacity-50 pointer-events-none"></div>
    </div>
    <div
        class="font-poppins bg-[#373b40] relative p- h-screen flex flex-col justify-end ml-[30%] pt-[200px] border-b-[1px] pb-10">
        <div
            class="bg-[#373b40] absolute top-[70px] left-[-128px] rounded-full p-[20px] text-6xl text-white w-64 h-64 flex flex-col items-center justify-center font-extrabold">
            <p class="mb-4">Moh</p>
            <p>Sa'id</p>
        </div>
        <div class="ml-[70px]">
            <h1 class="text-sm font-bold text-[#68e0cf]">PROGRAMMER</h1>
            <p class="mt-[28px] text-white leading-7 text-sm w-[70%]">Hello! I am a
                freelance IT professional involved in various fields such as website development, data science projects,
                graphic design
                and more. Among all the IT products I have worked on, data science is the field I am most interested in.
                I have
                proficiency in several programming languages such as Python, PHP with Laravel framework, SQL, and
                JavaScript.</p>
            <button
                class="mt-8 font-bold text-xs rounded-full text-white py-6 px-8 border-gray-200 border-opacity-30 border-[1px] hover:bg-gray-700 focus:outline-none focus:bg-gray-700">
                CONTACT ME
            </button>
        </div>
    </div>
    <div id="about" class="font-poppins bg-[#373b40] pl-[70px] py-20  ml-[30%] border-b-[1px]">
        <div class="bg-[#373b40] text-6xl text-white font-extrabold">
            <p class="mb-4">About Me</p>
            <h1 class="text-sm font-bold text-[#68e0cf] uppercase ">My Story</h1>
        </div>
        <div class="text-white text-sm w-[90%]">
            <p class=" mt-[40px] leading-7">Since childhood, my curiosity about technology has driven me to explore and
                understand the intricacies of computers. This interest led me to pursue a Bachelor's degree in Computer
                Engineering at Trunojoyo University of Madura, where I honed my skills in programming, web development,
                and data science.</p>
            <p class=" mt-[40px] leading-7">My professional journey began as a research member at LPPM at Madura
                University, where I contributed to developing a web-based application for news sentiment analysis using
                various machine learning methods such as Naïve Bayes, SVM, and Neural Network. This research resulted in
                the publication of a scientific journal, reinforcing my passion for solving real-world problems through
                code and teamwork.</p>
            <div class="mt-[40px] font-bold grid grid-cols-2 gap-8 text-sm text-left">
                <div>
                    <div class="mb-4">
                        <span class="text-teal-400">AGE:</span>
                        <span class="ml-2">23</span>
                    </div>
                    <div class="mb-4">
                        <span class="text-teal-400">FREELANCE:</span>
                        <span class="ml-2">Available</span>
                    </div>
                    <div>
                        <span class="text-teal-400">PHONE:</span>
                        <span class="ml-2">+6282 331 522 877</span>
                    </div>
                </div>
                <div>
                    <div class="mb-4">
                        <span class="text-teal-400">RESIDENCE:</span>
                        <span class="ml-2">Indonesia</span>
                    </div>
                    <div class="mb-4">
                        <span class="text-teal-400">ADDRESS:</span>
                        <span class="ml-2">Sumenep</span>
                    </div>
                    <div>
                        <span class="text-teal-400">E-MAIL:</span>
                        <span class="ml-2">yanginiemailnyasaid@gmail.com</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="font-poppins bg-[#373b40] pl-[70px] py-20  ml-[30%] border-b-[1px]">
        <div class="bg-[#373b40] text-6xl text-white font-extrabold mb-[40px]">
            <p class="mb-4">Services</p>
            <h1 class="text-sm font-bold text-[#68e0cf] uppercase ">WHAT I DO</h1>
        </div>
        <div class="text-white text-sm w-[90%]">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="py-4">
                    <i class="fas fa-laptop-code text-[#68e0cf] text-4xl mb-5"></i>
                    <h3 class="text-base mb-5 font-bold">Web Development</h3>
                    <p class="text-sm leading-6">Professional web development services tailored to your needs. From
                        simple websites to complex
                        web applications, we've got you covered.</p>
                </div>
                <div class="py-4">
                    <i class="fas fa-paint-brush text-[#68e0cf] text-4xl mb-5"></i>
                    <h3 class="text-base mb-5 font-bold">Graphic Design</h3>
                    <p class="text-sm leading-6">Creative graphic design solutions to enhance your brand identity. Our
                        team will work with you
                        to create visually stunning designs that leave a lasting impression.</p>
                </div>
                <div class="py-4">
                    <i class="fas fa-chart-line text-[#68e0cf] text-4xl mb-5"></i>
                    <h3 class="text-base mb-5 font-bold">Data Science</h3>
                    <p class="text-sm leading-6">Data-driven insights and analytics services to help you make informed
                        decisions. Our data
                        scientists specialize in extracting valuable information from your data.</p>
                </div>
                <div class="py-4">
                    <i class="fas fa-gamepad text-[#68e0cf] text-4xl mb-5"></i>
                    <h3 class="text-base mb-5 font-bold">Mobile Game Development</h3>
                    <p class="text-sm leading-6">Custom mobile game development services for various platforms. Our
                        experienced developers can
                        turn your ideas into engaging and addictive mobile gaming experiences.</p>
                </div>
                <div class="py-4">
                    <i class="fas fa-book-open text-[#68e0cf] text-4xl mb-5"></i>
                    <h3 class="text-base mb-5 font-bold">Scientific Article Writing</h3>
                    <p class="text-sm leading-6">Expert scientific writing services for research articles, journals, and
                        academic papers. Our
                        team of writers ensures accurate and well-structured content tailored to your specific
                        requirements.</p>
                </div>
                <div class="py-4">
                    <i class="fas fa-cogs text-[#68e0cf] text-4xl mb-5"></i>
                    <h3 class="text-base mb-5 font-bold">Machine Learning</h3>
                    <p class="text-sm leading-6">Advanced machine learning solutions to optimize your processes and
                        improve efficiency. Our
                        machine learning experts develop custom models and algorithms to address your business
                        challenges.</p>
                </div>

            </div>
        </div>
    </div>

    <div id="resume"  class="font-poppins bg-[#373b40] pl-[70px] py-20  ml-[30%] border-b-[1px]">
        <div class="bg-[#373b40] text-6xl text-white font-extrabold mb-[40px] flex justify-between items-center">
            <div>
                <p class="mb-4">Experiences</p>
                <h1 class="text-sm font-bold text-[#68e0cf] uppercase">Project</h1>
            </div>
            <div class="relative pr-5">
                <button @click="scrollExp(-1)"
                    class="border-[1px] border-slate-400 rounded-full w-[80px] h-[80px] mr-[20px]">
                    < </button>
                        <button @click="scrollExp(1)"
                            class="border-[1px] border-slate-400 rounded-full w-[80px] h-[80px]">></button>
            </div>

        </div>
        <div class="text-white text-sm w-[90%]">
            <div class="relative overflow-hidden">
                <div class="flex transition-transform duration-300 ease-in-out"
                    :style="{ transform: `translateX(-${currentIndexExp * 50}%)` }">
                    <div v-for="(experience, index) in experiences" :key="index"
                        class="flex-shrink-0 w-80 text-sm mr-12">
                        <h2 class="text-sm leading-6 mb-4 text-[#68e0cf] font-extrabold">{{ experience.title }}</h2>
                        <p class="leading-6">{{ experience.description }}</p>
                    </div>
                </div>
            </div>

        </div>
    </div>



    <div class="font-poppins bg-[#373b40] pl-[70px] py-20  ml-[30%] border-b-[1px]">
        <div class="bg-[#373b40] text-6xl text-white font-extrabold mb-[40px] flex justify-between items-center">
            <div>
                <p class="mb-4">Education</p>
                <h1 class="text-sm font-bold text-[#68e0cf] uppercase">STUDIED AT</h1>
            </div>
            <div class="relative pr-5">
                <button @click="scrollEdu(-1)"
                    class="border-[1px] border-slate-400 rounded-full w-[80px] h-[80px] mr-[20px]">
                    < </button>
                        <button @click="scrollEdu(1)"
                            class="border-[1px] border-slate-400 rounded-full w-[80px] h-[80px]">></button>
            </div>

        </div>
        <div class="text-white text-sm w-[90%]">
            <div class="relative overflow-hidden">
                <div class="flex transition-transform duration-300 ease-in-out"
                    :style="{ transform: `translateX(-${currentIndexEdu * 50}%)` }">
                    <div v-for="(education, index) in educations" :key="index" class="flex-shrink-0 w-80 flex flex-col justify-between text-sm mr-12">
                        <div class="flex items-center mb-5">
                            <div class="text-[#68e0cf] font-bold text-[10px] rotate-270" style="writing-mode: vertical-rl;">{{ education.year }}
                            </div>
                            <h2 class="self-start text-xl leading-6 mb-4 text-white font-extrabold ">{{ education.school }}</h2>
                        </div>
                        <p class="leading-6">{{ education.description }}</p>
                    </div>
                </div>
            </div>

        </div>
    </div>


    <div id="skill" class="font-poppins bg-[#373b40] pl-[70px] py-20 ml-[30%] border-b-[1px]">
        <div class="bg-[#373b40] text-6xl text-white font-extrabold mb-[40px]">
            <p class="mb-4">Coding Skill</p>
            <h1 class="text-sm font-bold text-[#68e0cf] uppercase ">DEVELOPING ON</h1>
        </div>
        <div class="text-white text-sm w-[90%]">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="py-4">
                    <div class="text-[5px] mb-10">
                        <CircleProgress :percentage="90" />
                    </div>
                    <h3 class="text-sm mb-5 font-bold">PHP, MYSQL, POSTGRESQL</h3>
                    <p class="text-sm leading-6">Secure and clean Backend Development and Database Management</p>
                </div>
                <div class="py-4">
                    <div class="text-[5px] mb-10">
                        <CircleProgress :percentage="85" />
                    </div>
                    <h3 class="text-sm mb-5 font-bold">JAVASCRIPT</h3>
                    <p class="text-sm leading-6">Utilizing various JavaScript libraries for more interactive websites
                    </p>
                </div>
                <div class="py-4">
                    <div class="text-[5px] mb-10">
                        <CircleProgress :percentage="85" />
                    </div>
                    <h3 class="text-sm mb-5 font-bold">LARAVEL, VUEJS</h3>
                    <p class="text-sm leading-6">Utilizing Laravel and Vue.js for more interactive websites</p>
                </div>
                <div class="py-4">
                    <div class="text-[5px] mb-10">
                        <CircleProgress :percentage="90" />
                    </div>
                    <h3 class="text-sm mb-5 font-bold">PYTHON</h3>
                    <p class="text-sm leading-6">Utilized for machine learning and data science, such as text-mining and
                        image-mining</p>
                </div>
                <div class="py-4">
                    <div class="text-[5px] mb-10">
                        <CircleProgress :percentage="90" />
                    </div>
                    <h3 class="text-sm mb-5 font-bold">HTML, CSS</h3>
                    <p class="text-sm leading-6">Standard skills required for website development</p>
                </div>
                <div class="py-4">
                    <div class="text-[5px] mb-10">
                        <CircleProgress :percentage="70" />
                    </div>
                    <h3 class="text-sm mb-5 font-bold">C#, UNITY</h3>
                    <p class="text-sm leading-6">Used for creating games or simple mobile applications</p>
                </div>
            </div>
        </div>
    </div>

    <div class="font-poppins bg-[#373b40] pl-[70px] py-20 ml-[30%] border-b-[1px]">
        <div class="bg-[#373b40] text-6xl text-white font-extrabold mb-[40px]">
            <p class="mb-4">Design Skill</p>
            <h1 class="text-sm font-bold text-[#68e0cf] uppercase ">CREATIVE ABILITY</h1>
        </div>
        <div class="text-white text-sm w-[90%]">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="py-4 flex flex-col justify-between">
                    <h3 class="text-sm mb-5 font-bold">Web Layout</h3>
                    <p class="text-sm leading-6 self-start h-full">Tools used include FIGMA,
                        Inkscape, and GIMP.</p>
                    <div class="text-[5px] mb-10 mt-6">
                        <SimpleProgressBar :percentage="85" />
                    </div>
                </div>
                <div class="py-4 flex flex-col justify-between">
                    <h3 class="text-sm mb-5 font-bold">Graphic Design</h3>
                    <p class="text-sm leading-6 self-start h-full">Tools used include Inkscape,
                        Canva, and Adobe Illustrator.</p>
                    <div class="text-[5px] mb-10 mt-6">
                        <SimpleProgressBar :percentage="80" />
                    </div>
                </div>
                <div class="py-4 flex flex-col justify-between">
                    <h3 class="text-sm mb-5 font-bold">Photo Editing</h3>
                    <p class="text-sm leading-6 self-start h-full">Tools used include GIMP, Photoshop, and
                        Lightroom.</p>
                    <div class="text-[5px] mb-10 mt-6">
                        <SimpleProgressBar :percentage="75" />
                    </div>
                </div>
                <div class="py-4 flex flex-col justify-between">
                    <h3 class="text-sm mb-5 font-bold">Illustrations</h3>
                    <p class="text-sm leading-6 self-start h-full">Tools used include Inkscape and Adobe
                        Illustrator.</p>
                    <div class="text-[5px] mb-10 mt-6">
                        <SimpleProgressBar :percentage="75" />
                    </div>
                </div>
            </div>
        </div>
    </div>



    <div id="contact" class="font-poppins bg-[#373b40] pl-[70px] py-20  ml-[30%] border-b-[1px]">
        <div class="bg-[#373b40] text-6xl text-white font-extrabold mb-[40px]">
            <p class="mb-4">Contact</p>
            <h1 class="text-sm font-bold text-[#68e0cf] uppercase ">LET'S TALK</h1>
        </div>
        <div class="text-white text-sm w-[90%]">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="flex justify-between">
                    <a href="https://www.instagram.com/said.iiq/"
                        class="rounded-full h-min p-7 border-[1px] border-opacity-30 border-white fab fa-instagram text-3xl text-white">
                    </a>
                    <a href="https://www.tiktok.com/@mohsaid273"
                        class="rounded-full h-min p-7 border-[1px] border-opacity-30 border-white fab fa-tiktok text-3xl text-white">
                    </a>
                    <a href="https://wa.me/6282331522877"
                        class="rounded-full h-min p-7 border-[1px] border-opacity-30 border-white fab fa-whatsapp text-3xl text-white">
                    </a>
                </div>
                <div class="rounded-3xl p-8 border-[1px] border-white border-opacity-35">
                    <h1 class="font-extrabold text-3xl text-white mb-1">Moh Sa'id</h1>
                    <p class="text-[#68e0cf] mb-[40px] font-bold text-xs">Web Devolopment dan Data Sains</p>

                    <p class="mb-3 font-bold text-xs"><span class="font-bold text-[#68e0cf] mr-2">AGE:</span> 23</p>
                    <p class="mb-3 font-bold text-xs"><span class="font-bold text-[#68e0cf] mr-2">RESIDENCE:</span>
                        Indonesia</p>
                    <p class="mb-3 font-bold text-xs"><span class="font-bold text-[#68e0cf] mr-2">FREELANCE:</span>
                        Avaible</p>
                    <p class="mb-3 font-bold text-xs"><span class="font-bold text-[#68e0cf] mr-2">ADDRESS:</span>
                        Sumenep</p>
                    <p class="mb-3 font-bold text-xs"><span class="font-bold text-[#68e0cf] mr-2">Phone:</span> +628 233
                        1522 877</p>
                    <p class="mb-3 font-bold text-xs"><span class="font-bold text-[#68e0cf] mr-2">Email:</span>
                        yanginiemailnyasaid@gmail.com</p>

                    <h1 class="satisfy-regular text-[50px] mt-[60px] mb-[40px]">MohSaid</h1>
                </div>
            </div>
        </div>
    </div>

</template>
<script>
export default {
    data() {
        return {
            experiences: [
                {
                    title: "Forecasting application for predicting the number of Hospital patients",
                    description: "The forecasting calculation for the number of patients uses the SARIMA method. This web-based application is made for the needs of Belega Hospital, Bangkalan."
                },
                {
                    title: "Geographic information system for land and buildings in Bangkalan Regency",
                    description: "The Interactive Maps feature in this website uses the Leaflet JS library. This website is created for the needs of the Bangkalan Regional Government to access information regarding land and buildings in Bangkalan."
                },
                {
                    title: "Application for predicting the potential for hepatitis disease",
                    description: "This application is used to classify and predict hepatitis disease based on existing categories. The methods used are KNN and WKNN."
                },
                {
                    title: "Geographic information system for agricultural Bangkalan Regency",
                    description: "The mapping of rice fields in this data uses the geojson format. The geojson maps format used will be integrated with the Leaflet JS library."
                },
                {
                    title: "Customer satisfaction analysis application for TikTok Shop services.",
                    description: "This website analyzes customer data using the CSI method. It is integrated with PostgreSQL."
                },
                {
                    title: "Application for predicting the eligibility of Sumenep community in receiving basic foodstuffs",
                    description: "The classification calculation in this application uses the Naive Bayes method. The visualization in this application uses the Matplotlib library."
                },
                {
                    title: "Application for clustering divorce data in Lamongan regency",
                    description: "The clustering method used in this application is the K-Means method. The results of this clustering are used to analyze the factors causing divorce in marital relationships."
                }
                // Add more experiences as needed
            ],
            educations: [
                {
                    "school": "University of Trunojoyo Madura",
                    "year": "2019 - 2024",
                    "description": "Bachelor of Informatics Engineering | GPA: 3.68/4.00. My thesis titled 'Comparison of Feature Selection for Sentiment Classification Tourism News Using the Naïve Bayes Method.'"
                },
                {
                    "school": "Yayasan Syahamah",
                    "year": "2020 - Present",
                    "description": "At this foundation, I learn about religious life, tolerance, and caring for each other. This enhances spirituality, social awareness, and peace of mind."
                },
                {
                    "school": "MAN Sumenep",
                    "year": "2016 - 2019",
                    "description": "In this education, I majored in Science. This school also led me to obtain a non-test pathway to the Trunojoyo Madura University majoring in Informatics Engineering."
                }

            ],
            currentIndexExp: 0,
            currentIndexEdu: 0,
        };
    },
    methods: {
        scrollExp(direction) {
            const newIndex = this.currentIndexExp + direction;
            if (newIndex < 0) {
                this.currentIndexExp = this.experiences.length - 2;
            } else if (newIndex > this.experiences.length - 2) {
                this.currentIndexExp = 0;
            } else {
                this.currentIndexExp = newIndex;
            }
        },
        scrollEdu(direction) {
            const newIndex = this.currentIndexEdu + direction;
            if (newIndex < 0) {
                this.currentIndexEdu = this.educations.length - 2;
            } else if (newIndex > this.educations.length - 2) {
                this.currentIndexEdu = 0;
            } else {
                this.currentIndexEdu = newIndex;
            }
        },
    },
};
</script>
<style scoped>
.transition-transform {
    transition-property: transform;
}
</style>
<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Satisfy&display=swap');

.font-poppins {
    font-family: 'Poppins', sans-serif;
}

.satisfy-regular {
    font-family: "Satisfy", cursive;
    font-weight: 400;
    font-style: normal;
}
</style>
