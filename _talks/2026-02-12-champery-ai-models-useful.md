---
title: "All AI models are wrong, but some are useful … for power systems"
collection: talks
type: "Invited Talk"
permalink: /talks/2026-02-12-champery-ai-models-useful
venue: "4th Champery Power Conference"
date: 2026-02-12
location: "Champéry, Switzerland"
---

Power systems are increasingly complex, high-dimensional, and dynamic, driven by renewable integration, inverter-based resources, and growing operational uncertainty. Machine learning (ML) offers powerful tools to approximate computationally expensive simulations and optimization problems; however, as George Box famously noted, all models are wrong, but some are useful. This talk examines what makes AI models useful for power system applications.

We begin with supervised surrogate models for fast dynamic security assessment and time-domain simulation, highlighting their speed advantages and limitations under system shift, topology changes, and out-of-distribution scenarios. We then discuss physics-informed learning, where physical residuals and domain structure are embedded into training objectives to improve generalization and reduce data requirements. Extending beyond fully labeled settings, we explore weakly supervised and constraint-driven learning approaches for large-scale security-constrained optimal power flow (SCOPF), demonstrating how embedding feasibility, contingency, and power balance constraints directly into the loss function enables scalable and computationally efficient solutions.

A central theme is generalization: power system ML must extrapolate across operating conditions, contingencies, time horizons, and even network topologies while facing the curse of dimensionality. We argue that injecting structure—physics, constraints, and graph topology—is essential for robustness. This perspective leads to a broader research question: Should power systems ML move toward foundation-style models trained via self-supervision on large-scale surrogate data? We outline how power flow formulations, residual modeling, and graph neural networks may provide the right abstractions for developing grid foundation models.

The talk concludes by arguing that the “Power System Neural Network” remains to be invented—one that combines domain bias, scalable architectures, and strong extrapolation capability to support secure, reliable, and efficient future grids.

Slides:  
<iframe src="https://JochenC.github.io/files/Champery-JochenCremer-12-02-2026.pdf" width="100%" height="600px">
    This browser does not support PDFs. Please download the PDF to view it: 
    <a href="https://JochenC.github.io/files/Jochen%20Cremer%2025-09%2050Hertz%20-%20public.pdf">Download PDF</a>.
</iframe>
