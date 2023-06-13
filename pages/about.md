---
layout              : page-fullwidth
show_meta           : false
title               : "About the research group"
subheadline         : ""
teaser              : ""
permalink           : "/about/"
---
<style>
@media (min-width: 500px) {
    .media {
        display: grid;
        grid-template-columns: 1fr fit-content(330px);
        grid-template-rows:1fr auto;
        grid-template-areas:
            "content1 img1"
            "content2 img2"
            "content3 img3"
        grid-gap: 20px;
        margin-bottom: 4em;
    }
	
    .img1 {
        grid-area: image;
    }
  
    .img2 {
        grid-area: image;
    }
  
    .img3 {
        grid-area: image;
    }

    .content1 {
        grid-area: content;
    }
  
    .content2 {
        grid-area: content;
    }
  
    .content3 {
        grid-area: content;
    }

}
</style>


<div class="media">
	<div class="content1">
    		<p>We are a small research group at Ruhr University Bochum (Faculty of Medicine), consisting of [Prof. Dr. Xenia Kobeleva](/xenia-kobeleva/) and her [team](/team/).</p>
		<p>In the Computational Neurology group, we answer clinical relevant questions in the field of neuropsychiatry using computational methods. We analyze clinical and neuroimaging data using both a data-driven and a modelling-based approach (see Figure 1). This integration helps generating a better (qualitative) and robust (quantitative) understanding of pathophysiological processes of neurological diseases, as well as their diagnosis and treatment.</p>
	</div>
  	<div class="img1">
		<img src="/images/about_approaches.png">

	</div>
</div>





The data-driven approach mainly focusses on the analysis of neurological diseases with methods of machine learning in order to identify characteristic properties of the brain structure and brain function as clinical phenotypes. The model-driven approach builds on our findings from the data-driven approach. It formalizes a mechanistic relationship between clinical data and brain function via equations; in doing so, this relationship can be meaningfully interpreted, and it extends and goes beyond mere observations. Simulated brain models exert high congruence with actual brain data (compare Figure 2).

<img class="center" style="width:400px;" src="/images/about_simulatedvsempirical.png"><br>
*Figure 2: Brain networks can be realistically simulated with dynamical models. The simulated brain network (left) shows high conformity to the actual clinical data (right). © Xenia Kobeleva*

This kind of modelling might enable medical doctors to adapt their treatments based on patient-specific mathematical models.

<b>Methods we use in the research group:</b>
<ul>
  <li>Dynamical modelling (dynamic mean field, Hopf, etc.)</li>
  <li>Analyses of connectivity (structural connectivity, functional connectivity, dynamical functional connectivity, effective connectivity)</li>
  <li>Pre-processing of structural and functional MRT data (including preprocessing pipelines)</li>
  <li>Analyses of resting state fMRT and task fMRT</li>
  <li>Neurophysiology (TMS, EMG, EEG)</li>
  <li>Medical informatics</li>
  <li>Open science</li>
</ul>
