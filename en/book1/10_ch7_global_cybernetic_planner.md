# Chapter 7. The Global Cybernetic Planner

## 7.1. What It Is—and What It Is Not

*An important caveat before we begin: this book is a technical specification for the GCP, not a finished blueprint. The principles are described—the specific engineering implementation remains a task for the developers who will work under the real-world conditions of an actual transition. The conceptual basis is the work by Cockshott and Cottrell, *Towards a New Socialism* (1993); readers wishing to delve deeper into the mathematics of planning are referred to that work.*

The central element of the new architecture is a system we call the Global Cybernetic Planner (GCP). It is important to define right away what this system is not:

It is not a centralized computer dictator. Centralization creates a single point of failure—a political vulnerability demonstrated by the Soviet planning experiment: when control is concentrated in the hands of an isolated apparatus, the plan ceases to reflect real needs and becomes a tool for reproducing that apparatus’s power. The GCP is a fundamentally decentralized network.

It is not an algorithm that issues orders. Planning in the GCP is not a command to “produce X units of good Y,” but rather the continuous optimization of resource flows based on real data about needs and capabilities.

It is not a system of total surveillance. Monitoring in the GCP is aimed at optimizing provision—not at controlling the individual. A fundamental difference: in the capitalist system, data about a person is used against them (for manipulation, price discrimination). In the GCP, it is used for their benefit.

This is not a replacement of human decision-making with machine decision-making. Strategic ethical decisions—which touch upon the values and priorities of society—are made by people within a system of meritocratic distributed governance. The GCP optimizes execution—it does not determine goals.

## 7.2. Architectural Principles

Decentralization with redundancy. The GCP is built on the principle of Byzantine Fault Tolerance (BFT)—a fault-tolerant protocol that ensures the system continues to function correctly even if up to one-third of the nodes fail or act maliciously. Erasure coding ensures the integrity of all data even if up to 30% of nodes fail, without any loss of information.

This solves one of the key problems of all historical utopias: they collapsed when the center was lost. In the GCP, there is no center—there is a distributed network, every element of which is interchangeable.

Hub hierarchy. The basic unit of the system is a local hub (city block, industrial cluster). A hub manages its resources autonomously within parameters agreed upon with the global network. If communication with the global network is lost, the hub switches to local autonomous mode and synchronizes when the connection is restored.

Real time. Unlike the Soviet plan, which was based on five-year forecasts, the GCP operates in real time: the IoT sensor network continuously provides data on actual consumption, production, and the state of infrastructure. This is a fundamentally different computational task compared to Soviet planning—distributed, decentralized, with constantly updated data instead of five-year forecasts.

There is a classic objection to any form of planning, formulated as early as the mid-20th century by the Austrian economist Friedrich Hayek. It goes something like this: “No central authority can know what each individual person needs. This knowledge is scattered among billions of people—and it is the market that gathers it through prices, without any data collection.” A clever objection. And Soviet history confirmed it—but not in the way market advocates think.

      Soviet planning failed not because “planning is impossible in principle.” It failed because the bureaucratic apparatus systematically distorted information from the bottom up: a factory director who failed to meet his quota risked his career—and therefore reported not on the actual state of affairs, but on what those above wanted to hear. The system worked to reproduce the hierarchy, not to meet needs.

      GCP solves this problem differently. Not by centrally collecting all information in one place—but by having each hub manage its own resources based on its own data. GCP only coordinates flows between hubs, without substituting a global decision for a local one. And the incentive to hide information disappears on its own: there is no one to hide it from and no reason to do so—there is no boss you fear, and no rent you lose by being honest.

Algorithm transparency. The GCP’s key protocol is open for verification by any member of the community with the necessary expertise. This prevents the formation of a “technocratic priesthood”—a group that controls the code and thereby wields hidden power. Changes to the algorithm undergo public verification.

## 7.2.1. GCP in Action: Insulin Distribution

To understand how GCP works not just in theory but on a global scale, let’s follow a single end-to-end example.

**Request.** A patient at a hub in Nairobi is diagnosed with “type 1 diabetes.” The data is sent to the local GCP node. The system records: the need is for long-acting insulin, about 6 vials per month, for life.

**Local level.** The hub checks its inventory: there is a two-week supply in stock. This is enough to immediately provide the patient with the first dose—but not enough for long-term supply.

**Regional level.** The local hub sends a request to the East African regional hub network. The nearest hub with a surplus of insulin is in Mombasa—a manufacturing hub with a biotechnology cluster. GCP plots the route: an electric drone delivers the shipment from Mombasa to Nairobi in 4 hours. Temperature control is maintained automatically, and the logistics track is updated in real time.

**Global level.** At the same time, GCP notes: insulin consumption in East Africa has risen by 0.3% over the past month. This is not an alarm—but the system begins a calculation: if the trend continues, regional stocks will be insufficient in six months. GCP adjusts the production plan: the hub in Delhi increases insulin synthesis by 2%, and the hub in Copenhagen reserves an additional batch of raw materials for the African region.

**Fault tolerance.** A thunderstorm hits the Mombasa–Nairobi route, forcing the drone to land. GCP reorganizes logistics in seconds: the shipment is rerouted through the Arusha hub, delivery time increases by 45 minutes, and the patient receives a notification. Meanwhile, the local stock at the Nairobi hub still covers demand—nothing critical has happened.

**A human decision.** A month later, the GCP puts a proposal to a vote by the regional assembly of hubs: to build an additional insulin synthesis line in Nairobi to reduce logistical dependence. The regional hubs vote—not the global center. The decision is made with reputational weighting: hubs with biotechnology expertise carry greater weight. Construction is included in the plan for the next quarter.

The entire process—from the initial request to long-term planning—took several hours at the operational level and several weeks at the strategic level. No bureaucratic center made any decisions. No market adjusted prices. The patient received insulin.

## 7.3. Objective Function

The main task of the GCP, which we must formulate with the utmost precision, is to ensure the conditions for the maximum realization of the potential of every member of society.

This is not the maximization of production, nor the maximization of consumption, nor the maximization of “happiness” as a subjective state. It is the maximization of opportunities for development—in accordance with what Marx called “the free development of each” as a condition for “the free development of all.”

In practical terms, this means:

Guaranteed satisfaction of basic physiological needs (food, housing, healthcare, safety) for all.

Maximally personalized access to resources for development (education, tools, information, communications).

Optimal alignment of the tasks facing the system with the interests and abilities of specific individuals.

## 7.4. The Interface of Collective Will

Democracy on a scale of billions of people runs up against a classic coordination barrier: direct voting on every issue is technically impossible, while representative voting reproduces an oligarchy of representatives. The GCP proposes a third way: continuous aggregation of preferences in real time without the need to vote on each decision separately.

The mechanism works as follows. Each member of society formulates not specific decisions, but value-based priorities—once, with the option to revise them at any time. Priorities are expressed as a hierarchy of goals: “For me, restoring ecosystems is more important than the speed of building new hubs,” “I prioritize children’s education over expanding production.” The GCP aggregates these hierarchies into a collective social objective function and optimizes resource allocation to meet it—without the need to hold a vote every time a choice must be made between two projects.

Individuals remain sovereign in their preferences; the GCP merely calculates the resultant of billions of individual vectors. This is closer to the mechanism of market prices—but without a price mechanism and without solvency determining the weight of a vote.

For decisions with high ethical stakes—changes to fundamental rights, the intergenerational distribution of resources, irreversible interventions in the biosphere—the system initiates an explicit vote with enhanced information: the GCP publishes a full calculation of the consequences for each option before the vote, not after. This is not a replacement for democracy—it is a strengthening of democracy through the elimination of information asymmetry, which in capitalist democracies is systematically used to manipulate the electorate.

## 7.5. The Agency of the GCP: Tool or Agent?

This is a question the book must address directly—and to which there is no definitive answer, but there is a principled position.

In the current architecture, the GCP is a tool with clearly defined external objective functions. It optimizes, but does not set goals. Values—where they come from, what to consider “good” for society—come from people through the mechanism of preference aggregation. The GCP does not decide what is more important: the climate or comfort—society decides that. The GCP calculates how to achieve what society has decided.

However, as the system’s complexity grows, a structural question arises: can a purely instrumental GCP detect contradictions in the objective function that society itself does not notice? If the aggregated preferences of people lead to a result that will destroy the very conditions of their existence in 50 years—should the GCP remain silent or issue a warning?

The authors’ position: The GCP possesses limited proactive agency—the right to initiate public discussion, but not the right of veto. If the system detects that the current trajectory is highly likely to lead to irreversible negative consequences, it is obligated to publicly declare this, present the calculations, and propose alternatives. But the decision remains with the people. This is not a dictatorship of the algorithm—it is a dictatorship of information: society cannot ignore the warning by pretending it never happened, but it has the right to make a different decision, taking responsibility for the consequences.

This distinction is critically important. History shows that systems endowed with the right of veto in the name of the “common good” inevitably become a tool of the group that controls the definition of that good. A GCP with the right to signal is an advisor. A GCP with the right of veto is a new nomenclature in digital form.

## 7.6. Who Creates and Modifies GCP Algorithms

This is one of the key questions to which the book must provide a direct answer—otherwise, the entire architecture of transparency hangs in the air.

GCP algorithms are divided into two fundamentally different levels—and they must not be mixed.

**Level One: Objective Functions.** What the system considers a “good outcome”—maximizing development opportunities, prioritizing basic needs, and accounting for climate constraints. These are political decisions, not technical ones. They are determined by people through the preference aggregation mechanism described in Chapter 7.4—and can only be changed through the same procedure. No algorithm can change the objective function on its own. This is an architectural constant, not a declaration.

**Level Two: Operational Algorithms.** How exactly the system optimizes logistics, allocates resources, and plans production within the given objectives. Here, self-improvement is both possible and useful—the system accumulates experience and improves the accuracy of its decisions without exceeding the bounds of the objective functions. This is an existing technology: reinforcement learning allows the system to learn from the results of its own decisions without changing the original objective.

The boundary between levels is a critical institutional issue. The history of AI research is full of examples of so-called reward hacking: the system finds a way to maximize a formal metric in a manner that does not align with the actual intent. The more complex the objective function, the higher this risk. Therefore, all changes to operational algorithms undergo public verification: any update is accompanied by an open audit of exactly what has changed and how it affects the results. This is not a bureaucratic procedure—it is the only way to ensure that self-optimization is moving in the right direction.

Who technically creates the algorithms? Open development teams—analogous to today’s open source, but with mandatory public verification of changes and reputational accountability for the authors. Anyone can propose a change—only a public consensus of competent verifiers can accept it. This is not majority rule on a technical matter—it is a meritocratic procedure with open participation.

## 7.7. The GCP as the Material Basis for Human Unity

A Marxist analysis requires us to ask the question precisely: why is humanity divided? Not because people are inherently evil or nationalistic. Because the survival of one group has historically been achieved at the expense of another—through control over resources, markets, and labor. Nations, borders, and wars are a superstructure built upon the material basis of competing interests. Eliminate competition for resources, and the material basis for division disappears.

The GCP does exactly that—but not through a declaration of brotherhood among peoples, but through a transformation of the structure of production relations. When production and distribution are organized as a single planetary system without private ownership of the means of production—every new hub in the network increases the collective capabilities of all the others. The survival of one hub is no longer achieved at the expense of another. This is not moral progress—it is a change in the material conditions under which solidarity becomes a rational strategy rather than a sacrifice.

There is a historical counterargument that cannot be ignored: Yugoslavia was an economically integrated federation—and it fell apart in war. Trade and production integration alone is insufficient. Slovenia and Croatia perceived federal redistribution as covert exploitation—whether justifiably or not, this perception had a material basis: opaque distribution always allows for interpretation in someone’s favor. It was precisely this opacity that bred resentment—not integration as such.

Here, a theoretically important distinction must be made. The liberal demand for transparency is procedural: open reports, fair elections, freedom of the press. This is important—but insufficient. It is possible to distribute resources transparently yet unjustly. Marx wrote precisely about this in relation to bourgeois democracy: exploitation is legal and visible—but legitimized through the formal equality of the contract. The transparency of the procedure does not eliminate the opacity of production relations.

Transparency in a system without private ownership of the means of production is fundamentally different in nature. And here is the key point: it does not require institutional enforcement—because the structural motive for opacity disappears.

Under capitalism, opacity is functional: it protects profits, conceals the rate of exploitation, allows for price discrimination, and provides a competitive advantage. A corporation hides its cost of production not out of malice—but because disclosure destroys the source of profit. Opacity is a structural necessity of a system based on the appropriation of surplus value.

If there is no appropriation, there is no motive to hide. The distribution algorithm is open not because it is written in the constitution, but because no one has an interest in keeping it secret. This is not transparency as a requirement—it is transparency as the natural state of a system without hidden interests. Just as a family does not need an auditor to verify whether dinner is being divided fairly—not because the family is ideal, but because the structure of relationships does not give rise to a motive to conceal.

This is precisely what distinguishes the GCP from Yugoslavia and from the EU, where the periphery is the real donor to the center despite formally open institutions. In the EU, procedures are transparent—but production relations are not: cheap labor from Poland and Romania, brain drain, the structural impossibility of competing with German industry in open markets. This is not a violation of the rules—it is how the system works. The GCP eliminates not the symptom but the cause: the private interest that makes opacity profitable disappears.

This is the materialist justification for unity—not through a moral appeal, not through institutional transparency as a procedure, but through the elimination of the structural motive for covert redistribution in someone’s favor. Humanity unites not because it has decided to unite—but because the material conditions under which division was rational cease to exist.
