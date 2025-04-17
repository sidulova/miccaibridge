---
layout: default
title: About Long Haul
---
<div class="post">
    <h3 class="pageTitle" style="color: #2c3e50;">About the Workshop</h3>
    <figure>
		<img src="/organizers/Ghada.jpg" alt=""> 
		<figcaption>Fig1. - This is an example figcaption</figcaption>
	</figure>
	<figure>
        <img src="/assets/img/Ravi.jpg" alt="Dr. Ravi Samala">
        <figcaption>Dr. Ravi Samala, FDA, USA</figcaption>
    </figure>
  	<h4 class="pageTitle" style="color: #2c3e50;">Why this Workshop?</h4>
            The accelerating pace of technological advancements in AI, primarily centered on evolving network architectures, 
            is outpacing the development of corresponding evaluation and regulation frameworks. This disconnect creates a 
            widening gap that not only hinders the effective integration of AI technologies into healthcare but also raises 
            significant concerns about patient safety. Without robust evaluation and regulatory frameworks, AI models may 
            fail to meet the stringent reliability and usability standards required for clinical deployment.
            While many workshops at MICCAI have explored important themes such as technical developments, ethics, and 
            explainability, there is a noticeable gap in addressing challenges related to evaluation, deployment, and 
            regulation. These challenges, if unaddressed, can significantly impact patient safety and outcomes.

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