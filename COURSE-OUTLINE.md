# Detailed course outline

[Course home](README.md) · [Syllabus](SYLLABUS.md)

**Status:** curriculum outline v0.1.0. Full lessons and executable labs are not yet published. Each module has Core, Applied and optional Extension tracks, and a transfer exercise.

## Think ABOUT Physical AI

Foundations: understand the world of physical intelligence

### [01. Physical Thinking](course/01-think-about-physical-ai/01-physical-thinking/README.md)

**Question:** What changes when intelligence enters the physical world?

**Mental model:** Intelligence must answer to physics; intended action is not the same as achieved physical effect.

**Core topics:**
- Physical AI, embodied AI and cyber-physical systems: definitions and overlaps
- Space, geometry, gravity, friction, inertia, contact and energy: intuitive physical constraints
- Sense → estimate → decide → act → observe/verify: feedback and physical state change
- Partial observations, reversible and irreversible effects, and consequences of error

**Planned studio:** One instruction, different physical worlds.

**Portfolio:** Physical Intelligence Loop Map.

**Transfer:** Apply the same loop to a greenhouse irrigation controller or an assistive device.

### [02. Embodied Thinking](course/01-think-about-physical-ai/02-embodied-thinking/README.md)

**Question:** How do body, intelligence and environment shape one another?

**Mental model:** Embodiment creates both affordances and constraints; form follows work and environment.

**Core topics:**
- Embodiment, morphology, degrees of freedom and affordances
- Sensors, actuators, end-effectors, energy, compute and service access
- Navigation, manipulation, reach, balance, payload, accuracy and repeatability
- Task-shaped bodies, mobile robots, arms, humanoids, drones and intelligent infrastructure

**Planned studio:** One job, five embodiments.

**Portfolio:** Embodiment and Environment Comparison.

**Transfer:** Compare alternative ways to harvest fruit or assist a person with mobility.

### [03. Systems Thinking](course/01-think-about-physical-ai/03-systems-thinking/README.md)

**Question:** How do perception, knowledge, planning, feedback and action work together?

**Mental model:** The world, observations, estimated state and physical outcomes are different things; interfaces and feedback determine system behavior.

**Core topics:**
- World state, observations, state estimation, partial observability and uncertainty
- Sensors and fusion, localization, calibration and degraded sensing
- Planning, policy, control, actuation and independent protective functions
- Feedback, latency, timing, disturbances and physical interaction
- Edge/cloud boundaries, telemetry, integration, people and service

**Planned studio:** Seeing is not knowing; delayed feedback.

**Portfolio:** Physical AI System Map and Failure-Path Analysis.

**Transfer:** Diagnose an autonomous irrigation system that waters an already saturated field.

**Stage checkpoint:** Explain and diagnose an intelligent physical system using physical, embodied and systems reasoning.

## Think WITH Physical AI

Application: collaborate, investigate and design intelligent physical work

### [04. Work-Centric Thinking](course/02-think-with-physical-ai/04-work-centric-thinking/README.md)

**Question:** What meaningful physical work should intelligent systems perform?

**Mental model:** Start with the work and accepted outcome, not the robot or model.

**Core topics:**
- Purpose, jobs, workflows, tasks, skills, actions and physical effects
- Field discovery: buyers, operators, maintainers, nearby workers and supervisors
- Current process, baseline, variations, bottlenecks, workarounds and exceptions
- Task eligibility, acceptance criteria, alternative solutions and initial operating scope

**Planned studio:** Observe before automating.

**Portfolio:** Physical Work and Opportunity Map.

**Transfer:** Apply the method to hospital supply restocking or food preparation.

### [05. Intelligence Thinking](course/02-think-with-physical-ai/05-intelligence-thinking/README.md)

**Question:** What intelligence is needed, and how should we collaborate with it?

**Mental model:** Use appropriate intelligence at the appropriate layer; a plausible plan is not physical competence or permission.

**Core topics:**
- Reactive, deliberative, predictive, classical, learned and hybrid intelligence
- Perception-to-action representations; skill policies and hierarchical planning
- Language and vision models, vision-language-action models and world models
- Counterfactual prediction, uncertainty, preconditions and physical feasibility
- Human goal communication, agentic orchestration, skill contracts and independent protective functions

**Planned studio:** Design and challenge a robot brain.

**Portfolio:** Physical Intelligence Architecture.

**Transfer:** Choose intelligence approaches for an adaptive building or agricultural inspection system.

### [06. Experiential Thinking](course/02-think-with-physical-ai/06-experiential-thinking/README.md)

**Question:** How can machines acquire and improve physical skills through experience?

**Mental model:** Experience shapes capability; diverse, representative evaluation establishes its limits.

**Core topics:**
- Learning from demonstrations, imitation, rewards, exploration and feedback
- Do as I do: demonstration, teleoperation, video and embodiment transfer
- Trajectories, sensor streams, labels, failures, consent and physical data logistics
- Simulation, digital twins, domain randomization and sim-to-real discrepancy
- Fleet feedback, data curation and controlled policy/model releases

**Planned studio:** Teach a virtual machine, then challenge its experience.

**Portfolio:** Learning and Data Strategy.

**Transfer:** Design a learning strategy for a robot handling irregular produce or an adaptive assistive device.

### [07. Autonomy Thinking](course/02-think-with-physical-ai/07-autonomy-thinking/README.md)

**Question:** How should humans and machines share control, authority and responsibility?

**Mental model:** Capability does not confer authority; autonomy is an allocation of responsibility.

**Core topics:**
- Manual, teleoperated, assisted, supervised and bounded autonomous operation
- Authority release, operating envelope and sector-specific ODD terminology
- Human-robot interaction, legibility, trust calibration, ergonomics and accessibility
- Exceptions, escalation, handoff, intervention, recovery and return-to-service authorization
- Workforce participation, augmentation, substitution and hidden labor

**Planned studio:** Who decides, acts and intervenes?.

**Portfolio:** Autonomy, Authority and Human Collaboration Map.

**Transfer:** Apply the same allocation of responsibility to an assistive device or intelligent greenhouse.

**Stage checkpoint:** Frame a real work problem, compare intelligence and learning approaches, and allocate authority and assistance.

## Think IN Physical AI

Integration: exercise independent, responsible judgment

### [08. Assurance Thinking](course/03-think-in-physical-ai/08-assurance-thinking/README.md)

**Question:** What must be true before intelligent physical action is permitted?

**Mental model:** Risk reduction and authorization are independent gates; performance cannot substitute for assurance.

**Core topics:**
- Hazard, risk, foreseeable misuse and affected parties
- Risk assessment, protective functions, degraded modes and recovery
- Performance evidence versus safety evidence; independent acceptance gates
- Cyber-physical security, permissions, privacy and controlled updates
- Ethics, accountability, workforce and relevant specialist responsibilities

**Planned studio:** Failure-first assurance review.

**Portfolio:** Hazard, Responsibility and Assurance Map.

**Transfer:** Compare a factory robot and a public-space mobile system without assuming identical compliance rules.

### [09. Evidence Thinking](course/03-think-in-physical-ai/09-evidence-thinking/README.md)

**Question:** How do we establish that an intelligent physical system works?

**Mental model:** A demonstration establishes possibility, not dependability; the denominator and conditions define the claim.

**Core topics:**
- Capability demonstration versus deployment evidence
- Experimental hypotheses, baselines, test conditions, confounding factors and uncertainty
- Evaluation layers from components to integrated workflows
- Eligibility, attempts, retries, autonomous/assisted completions and total demand
- Evidence ladder: simulation, controlled tests, authorized pilot, endurance and replication

**Planned studio:** The 95% success-rate challenge.

**Portfolio:** Evaluation Plan and Evidence Register.

**Transfer:** Evaluate an agricultural robot’s harvest success across different crop and weather conditions.

### [10. Product Thinking](course/03-think-in-physical-ai/10-product-thinking/README.md)

**Question:** How does physical intelligence become a valuable product or service?

**Mental model:** The complete operated system is the unit of product value; minimize the breadth of the promise, not essential completeness.

**Core topics:**
- Physical outcome products, capability products and enabling infrastructure
- Work discovery, value proposition, bounded promise and operating envelope
- Minimum Product Thinking: Physical MAC/MAP concepts from the companion book
- 4D readiness: Done, Dependable, Desired, Duplicated; evidence maturity versus attainment
- Hardware/software/model lifecycle; NPI, pilots, integration, service and repeatability

**Planned studio:** Turn a demo into a product decision.

**Portfolio:** Physical AI Product Canvas and 4D Readiness Profile.

**Transfer:** Apply the method to a robotic skill API or a simulation/evaluation platform.

### [11. Economic Thinking](course/03-think-in-physical-ai/11-economic-thinking/README.md)

**Question:** Can intelligent physical systems create sustainable human and economic value?

**Mental model:** Measure the cost and value of accepted work; capacity released is not automatically cash saved.

**Core topics:**
- Robonomics: accepted work, throughput, quality, labor and capacity
- Availability, productive utilization, coverage and workflow bottlenecks
- Total lifecycle cost, cost-to-serve and customer/provider economics
- Business models: sale, lease, RaaS, per-hour, per-task and licensing
- Break-even, sensitivity, willingness to pay and investment decision criteria

**Planned studio:** The apparently cheaper robot.

**Portfolio:** Robonomics Model and Business-Model Decision.

**Transfer:** Compare alternatives for food preparation or infrastructure inspection using accepted outcomes.

### [12. Evolutionary Thinking](course/03-think-in-physical-ai/12-evolutionary-thinking/README.md)

**Question:** How do intelligent machines improve, scale and participate in larger systems?

**Mental model:** Earn generality and scale through evidence; collective behavior is not the sum of individual intelligence.

**Core topics:**
- Monitoring, maintenance, calibration, drift, failure harvesting and regression evidence
- Versioned software, models, hardware and configuration; staged updates and change control
- Repeatable deployment, manufacturing, support and site-specific variation
- Multi-robot coordination, shared knowledge, domain-specific brains and correlated failures
- Human-machine workforces, intelligent environments, societal impacts and responsible retirement

**Planned studio:** From one machine to a coordinated fleet.

**Portfolio:** Evolution and Replication Strategy.

**Transfer:** Reason about a distributed intelligent building or multi-machine agricultural operation.

**Stage checkpoint:** Evaluate evidence and assurance, assess complete system value and defend a lifecycle decision in an unfamiliar context.

## Next step

Develop and pilot [Module 01](course/01-think-about-physical-ai/01-physical-thinking/README.md) before authoring the full remaining course.
