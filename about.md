---
layout: default
title: About Long Haul
---
---
layout: default
title: About Long Haul
---

<div class="post">
    <h3 class="pageTitle" style="color: #2c3e50;">About the Workshop</h3>
    <section>
        <h4 class="pageTitle" style="color: #2c3e50;">Organizers</h4>
        <div class="organizers">
            <!-- First Row: 3 Organizers -->
            <div class="row">
                <div class="organizer">
                    <figure>
                        <img src="{{ '/organizers/ghada.jpg' | relative_url }}" alt="Dr. Ghada Zamzmi">
                        <figcaption>Dr. Ghada Zamzmi <br> FDA, USA</figcaption>
                    </figure>
                </div>
                <div class="organizer">
                    <figure>
                        <img src="{{ '/organizers/ravi.jpg' | relative_url }}" alt="Dr. Ravi Samala">
                        <figcaption>Dr. Ravi Samala <br> FDA, USA</figcaption>
                    </figure>
                </div>
                <div class="organizer">
                    <figure>
                        <img src="{{ '/organizers/touring.jpg' | relative_url }}" alt="Dr. Mariia Sidulova">
                        <figcaption>Dr. Mariia Sidulova <br> Medtronic, USA</figcaption>
                    </figure>
                </div>
            </div>
            <!-- Second Row: 3 Organizers -->
            <div class="row">
                <div class="organizer">
                    <figure>
                        <img src="{{ '/organizers/thijs.jpg' | relative_url }}" alt="Dr. Thijs Kooi">
                        <figcaption>Dr. Thijs Kooi <br> Lunit Inc, South Korea</figcaption>
                    </figure>
                </div>
                <div class="organizer">
                    <figure>
                        <img src="{{ '/organizers/xiaoxiao.jpg' | relative_url }}" alt="Dr. Xiaoxiao Li">
                        <figcaption>Dr. Xiaoxiao Li <br> UBC, Canada</figcaption>
                    </figure>
                </div>
                <div class="organizer">
                    <figure>
                        <img src="{{ '/organizers/annika.jpg' | relative_url }}" alt="Dr. Annika Reinke">
                        <figcaption>Dr. Annika Reinke <br> DKFZ, Germany</figcaption>
                    </figure>
                </div>
            </div>
        </div>
    </section>
    <section>
        <h4 class="pageTitle" style="color: #2c3e50;">Advisory Board</h4>
        <!-- First Row: 2 Advisors -->
        <div class="row">
            <div class="organizer">
                <figure>
                    <img src="{{ '/organizers/aldo.jpg' | relative_url }}" alt="Dr. Aldo Badano">
                    <figcaption>Dr. Aldo Badano <br> FDA, USA</figcaption>
                </figure>
            </div>
            <div class="organizer">
                <figure>
                    <img src="{{ '/organizers/touring.jpg' | relative_url }}" alt="Dr. Jana Delfino">
                    <figcaption>Dr. Jana Delfino <br> FDA, USA</figcaption>
                </figure>
            </div>
        </div>
        <!-- Second Row: 5 Advisors -->
        <div class="row">
            <div class="organizer">
                <figure>
                    <img src="{{ '/organizers/ehsan.jpg' | relative_url }}" alt="Dr. Ehsan Adeli">
                    <figcaption>Dr. Ehsan Adeli <br> Stanford, USA</figcaption>
                </figure>
            </div>
            <div class="organizer">
                <figure>
                    <img src="{{ '/organizers/marzyeh.jpg' | relative_url }}" alt="Dr. Marzyeh Ghassemi">
                    <figcaption>Dr. Marzyeh Ghassemi <br> MIT, USA</figcaption>
                </figure>
            </div>
            <div class="organizer">
                <figure>
                    <img src="{{ '/organizers/alejandro.jpg' | relative_url }}" alt="Dr. Alejandro Frangi">
                    <figcaption>Dr. Alejandro Frangi <br> University of Manchester, UK</figcaption>
                </figure>
            </div>
            <div class="organizer">
                <figure>
                    <img src="{{ '/organizers/lena.jpg' | relative_url }}" alt="Dr. Lena Maier-Hein">
                    <figcaption>Dr. Lena Maier-Hein <br> Heidelberg University, Germany</figcaption>
                </figure>
            </div>
            <div class="organizer">
                <figure>
                    <img src="{{ '/organizers/federica.jpg' | relative_url }}" alt="Dr. Federica Zanca">
                    <figcaption>Dr. Federica Zanca <br> EFOMP, Belgium</figcaption>
                </figure>
            </div>
        </div>
    </section>
    <section>
        <h4 class="pageTitle" style="color: #2c3e50;">Why this Workshop?</h4>
        <p>
            The accelerating pace of technological advancements in AI, primarily centered on evolving network architectures, 
            is outpacing the development of corresponding evaluation and regulation frameworks. This disconnect creates a 
            widening gap that not only hinders the effective integration of AI technologies into healthcare but also raises 
            significant concerns about patient safety. Without robust evaluation and regulatory frameworks, AI models may 
            fail to meet the stringent reliability and usability standards required for clinical deployment.
        </p>
        <p>
            While many workshops at MICCAI have explored important themes such as technical developments, ethics, and 
            explainability, there is a noticeable gap in addressing challenges related to evaluation, deployment, and 
            regulation. These challenges, if unaddressed, can significantly impact patient safety and outcomes.
        </p>
    </section>
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