---
layout: default
title: About Long Haul
---

<div class="post" style="text-align: justify;">
    <h3 class="pageTitle" style="color: #2c3e50;">About the Workshop </h3>
    <body>
        <section>
            <h4 class="pageTitle" style="color: #2c3e50;">Organizers</h4>
            <div class="organizers">
                <!-- First Row: 4 Images -->
                <div class="row">
                    <div class="organizer">
                        <img src="./assets/img/Ghada.jpg" alt="Dr. Ghada Zamzmi">
                        <p>Dr. Ghada Zamzmi <br>Food and Drug Administration <br>  USA</p>
                    </div>
                    <div class="organizer">
                        <img src="assets/img/Ravi.jpg" alt="Dr. Ravi Samala">
                        <p>Dr. Ravi Samala <br>Food and Drug Administration <br> USA</p>
                    </div>
                    <div class="organizer">
                        <img src="assets/img/touring.jpg"> <br> 
                        Dr. Mariia Sidulova <br> Medtronic <br>  USA
                    </div>
                </div>
                <!-- Second Row: 3 Images -->
                <div class="row">
                    <div class="organizer">
                        <img src="assets/img/Thijs.jpg" alt="Dr. Thijs Kooi">
                        <p>Dr. Thijs Kooi <br>  Lunit Inc <br> South Korea</p>
                    </div>
                    <div class="organizer">
                        <img src="assets/img/Xiaoxiao.jpg" alt="Dr. Xiaoxiao Li">
                        <p>Dr. Xiaoxiao Li <br> University of British Columbia <br> Canada</p>
                    </div>
                    <div class="organizer">
                        <img src="assets/img/Annika.jpg" alt="Dr. Annika Reinke">
                        <p>Dr. Annika Reinke <br>  German Cancer Research Center <br>  Germany</p>
                    </div>
                </div>
            </div>
        </section>
        <!-- Other Sections -->
        <section>
            <h4 class="pageTitle" style="color: #2c3e50;">Advisory Board</h4>
            <div class="row">
                    <div class="organizer">
                        <img src="assets/img/Aldo.jpg" alt="Dr. Aldo Badano">
                        <p>Dr. Aldo Badano <br> Food and Drug Administration <br> USA</p>
                    </div>
                    <div class="organizer">
                        <img src="assets/img/touring.jpg" alt="Jana Delfino">
                        <p>Dr. Jana Delfino <br> Food and Drug Administration <br> USA </p>
                    </div>
                </div>
                    <div class="row">
                    <div class="organizer">
                        <img src="assets/img/Ehsan.jpg" alt="Ehsan Adeli">
                        <p>Dr. Ehsan Adeli <br>  Stanford University <br>  USA</p>
                    </div>
                    <div class="organizer">
                        <img src="assets/img/Marzyeh.jpg" alt="Marzyeh Ghassemi">
                        <p>Dr. Marzyeh Ghassemi <br>Massachusetts Institute of Technology <br> USA</p>
                    </div>
                    <div class="organizer">
                        <img src="assets/img/Alejandro.jpg" alt="Alejandro Frangi">
                        <p>Dr. Alejandro Frangi  <br> University of Manchester <br> UK</p>
                    </div>
                    <div class="organizer">
                        <img src="assets/img/Lena.jpg" alt="Lena Maier-Hein">
                        <p>Dr. Lena Maier-Hein <br> Heidelberg University <br> Germany</p>
                    </div>
                    <div class="organizer">
                        <img src="assets/img/Federica.jpg" alt="Federica Zanca">
                        <p>Dr. Federica Zanca <br> European Federation of Organizations for Medical Physics <br> Belgium</p>
                    </div>
                </div>
        </section>
        <section>
            <h4 class="pageTitle" style="color: #2c3e50;">Why this Workshop?</h4>
            
                The accelerating pace of technological advancements in AI, primarily centered on evolving network architectures, 
                is outpacing the development of corresponding evaluation and regulation frameworks. This disconnect creates a 
                widening gap that not only hinders the effective integration of AI technologies into healthcare but also raises 
                significant concerns about patient safety. Without robust evaluation and regulatory frameworks, AI models may 
                fail to meet the stringent reliability and usability standards required for clinical deployment. 
        <br><br>
        
                While many workshops at MICCAI have explored important themes such as technical developments, ethics, and 
                explainability, there is a noticeable gap in addressing challenges related to evaluation, deployment, and 
                regulation. These challenges, if unaddressed, can significantly impact patient safety and outcomes.
          
        </section>
    </body>
</div>

<style>
    .organizers {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 20px;
    }
    .row {
        display: flex;
        justify-content: center;
        width: 100%;
        gap: 20px;
    }
    .organizer {
        text-align: center;
        flex: 1 1 calc(25% - 20px); /* For 4 items per row */
    }
    .row:nth-child(2) .organizer {
        flex: 1 1 calc(33.33% - 20px); /* For 3 items per row */
    }
    .organizer img {
        width: 150px; /* Uniform width */
        height: 150px; /* Uniform height */
        object-fit: cover; /* Ensures consistent scaling */
        border-radius: 8px; /* Optional: Rounded corners */
    }
    .organizer p {
        margin-top: 10px;
        font-size: 14px;
    }
</style>

<!-- 

<style>
    .organizers {
        display: flex;
        flex-direction: column; /* Stack rows vertically */
        gap: 20px; /* Space between rows */
    }
    .row {
        display: flex;
        justify-content: space-evenly; /* Equal spacing between items in a row */
        width: 100%;
        gap: 20px;
    }
    .organizer {
        text-align: center;
    }
    .organizer img {
        width: 150px; /* Uniform width */
        height: 150px; /* Uniform height */
        object-fit: cover; /* Ensures consistent scaling */
        border-radius: 8px; /* Optional: Rounded corners */
    }
    .organizer p {
        margin-top: 10px;
        font-size: 14px;
    }
</style> -->