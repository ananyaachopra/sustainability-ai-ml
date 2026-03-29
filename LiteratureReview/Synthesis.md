## 1. From Awareness to Integration in Computing Education

Research on sustainability in computing education has grown significantly, but remains uneven in both scope and rigor. A recent systematic review highlights that many existing interventions are positioned as “add-ons” rather than as fundamental shifts in how computing is taught (Peters et al., 2024). This distinction is critical: while awareness-based approaches introduce sustainability as a concept, they often fail to influence the technical decision-making processes that define computing practice.

Earlier work on curriculum design outlines multiple integration strategies, including standalone courses, modular insertions, and distributed approaches across the curriculum (Cai, 2010). More recent efforts emphasize the importance of lowering adoption barriers for instructors by providing structured, reusable modules that align with existing course content (Ligozat et al., 2022). Experience reports further demonstrate that sustainability can be embedded across courses as a persistent theme, though these approaches often require institutional commitment and coordination (Alavala et al., 2025; Bambazek et al., 2025).

Taken together, this body of work suggests that scalable integration depends on **alignment with existing technical workflows**, rather than curricular expansion. This insight directly motivates the design of lightweight, course-integrated modules that embed sustainability into concepts students already engage with, such as model evaluation and performance trade-offs.


## 2. Sustainability in ML: Expanding Evaluation Beyond Accuracy

The “Green AI” paradigm reframes machine learning evaluation by arguing that model performance should be considered alongside computational cost, energy use, and efficiency (Schwartz et al., 2019; 2020). This shift is not only environmental but epistemic: accuracy alone provides an incomplete view of model quality, particularly when high performance is achieved through resource-intensive methods.

In educational settings, operationalizing this perspective requires tools that make resource usage visible. Systems such as CodeCarbon enable students to estimate emissions associated with model training and inference, providing a concrete entry point into sustainability-aware evaluation. However, these tools introduce a new layer of complexity: their outputs are inherently approximate, dependent on hardware assumptions, and shaped by underlying models of energy consumption and grid intensity.

Instructional materials developed by Climate Change AI address this gap by emphasizing **measurement literacy**, guiding students from raw estimation toward interpretation and decision-making. This pedagogical approach aligns well with machine learning education, where students are already accustomed to comparing models under multiple criteria.

At the same time, emerging work expands the sustainability lens beyond carbon alone. For instance, research on the water footprint of AI systems highlights additional resource constraints that are often invisible in standard evaluation pipelines (Li et al., 2025). Similarly, critical perspectives argue that efficiency improvements alone are insufficient to ensure environmentally sustainable outcomes (Wright et al., 2025).

These contributions collectively point to a key insight: **sustainability in ML is not a single metric problem, but a multi-dimensional evaluation challenge**. Effective teaching must therefore move beyond measurement toward structured reasoning about trade-offs and uncertainty.


## 3. Beyond Efficiency: Rebound Effects and Systems-Level Impacts

A central limitation of efficiency-focused approaches is that they do not account for system-level dynamics. The concept of rebound effects, often associated with Jevons paradox, captures this tension: improvements in efficiency can lead to increased total resource consumption due to expanded usage and demand.

Recent work situates this phenomenon within the context of AI, distinguishing between direct impacts (e.g., energy consumption, hardware use) and indirect effects driven by scale, incentives, and market dynamics (Luccioni et al., 2025). This perspective challenges the assumption that optimizing individual models necessarily leads to sustainable outcomes.

For computing education, this has important implications. If students are taught to equate efficiency with sustainability, they may overlook the broader systems in which their models operate. Instead, sustainability must be framed as a problem of **decision-making under constraints**, where technical improvements interact with social, economic, and infrastructural factors.

This motivates a pedagogical shift: sustainability education in machine learning should not only teach students how to measure resource use, but also how to interpret those measurements within a larger system.


## 4. Implications for Course-Integrated Design

Across these strands of literature, a consistent theme emerges: sustainability is most effective when it is embedded into core technical practices rather than treated as a peripheral topic. For machine learning education, this suggests that sustainability should be introduced through:

- **Evaluation workflows** (e.g., comparing models using performance and resource-aware metrics),
- **Measurement and interpretation** (e.g., understanding emissions estimates and their limitations),
- **Trade-off reasoning** (e.g., balancing accuracy, efficiency, and cost),
- and **systems thinking** (e.g., recognizing rebound effects and infrastructure constraints).

The goal is not to add new content, but to reshape how existing content is understood.

This project builds on these insights by developing a sustainability-aware module for undergraduate ML courses that is:
- lightweight and adoptable,
- technically grounded,
- and oriented toward reasoning rather than prescription.

In doing so, it aims to move sustainability in computing education from awareness to practice.