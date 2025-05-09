---
title: "Seminar Liège: Deep Learning for Power System Reliability Assessments"
collection: talks
type: "Talk"
permalink: /talks/2025-05-liege-seminar
venue: "University of Liège"
date: 2025-05-09
location: "Liege, Belgium"
---

Preparing power systems for large-scale implementation of inverter-based generators and renewables requires future reliability tools to anticipate uncertainties in the monitoring and control that mitigate energy supply disruptions. Deep Learning (DL) approaches first proposed to the power system domain in the 90s have seen the first successes in the industry including renewable or load forecasting. 

Applying DL to more advanced power systems tasks like reliability management requires considering risks and resolving other barriers. This talk reviews the challenges of reliability management of power systems in the vein of large-scale renewables and inverter-based controls. Addressing some of these challenges, this talk introduces DL for two tasks within reliability management: N-k security-constrained optimal power flow and real-time dynamic security assessment. The conventional security-constrained optimal power flow problem (SCOPF) considers only N-1 contingencies as the probability of 2 contingencies is low and as the problem is computationally intractable for k > 1. However, cascading failures (k > 1) recently led to power blackouts. In response to this threat, DL could be used for N-k SCOPF. In this work, the loss function considers a polynomial, consecutive matrix multiplication of the post-fault DC power flows with line outage distribution factors (LODFs) applying the chain rule for efficient backpropagation and improved scaling with k. The implicit function theorem guarantees the pre-fault power flow is physically feasible, and the DL model learns pre-fault power settings that are N-k secure. Lastly, embedding DL in existing dynamic security assessment tools boosts the computational times to near real-time capabilities but risks need to be considered, specifically once the data is beyond what the DL model has been trained on. Case studies consider several IEEE bus systems, assessing the limitations and opportunities for applications in reliability management.

Slides: 
<iframe src="https://JochenC.github.io/files\Jochen%20Cremer%20AI%20in%20Power%20System%20Reliability%20Monitoring%20Liege%2009-05-2025.pdf" width="100%" height="600px">
    This browser does not support PDFs. Please download the PDF to view it: 
    <a href="https://JochenC.github.io/files\Jochen%20Cremer%20AI%20in%20Power%20System%20Reliability%20Monitoring%20Liege%2009-05-2025.pdf">Download PDF</a>.
</iframe>

This guest lecture was part of the course "Planning and operation of electric power and energy systems" [ELEC0448-1](https://www.programmes.uliege.be/cocoon/20242025/en/cours/ELEC0448-1.html).
