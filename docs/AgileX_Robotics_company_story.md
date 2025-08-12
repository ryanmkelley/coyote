# AgileX Robotics Deep Dive

## Why?
AgileX represents a advanced market player that has been operating since 2016 selling generic ROS enabled robotic rover chasses 

Beyond this report, [here is the story from their mouths](https://global.agilex.ai/blogs/news/agilex-ups-downs-and-ups-of-a-robotics-startup?)

# AgileX Robotics — Company Deep Dive

Here’s the AgileX story as it actually appears from the public record—warts, pivots, and all—and what we can (and can’t) infer about their scale.

AgileX Robotics was founded in 2016 in the Greater Bay Area (Songshan Lake/Xbot Park, later adding a Shenzhen sales office) by DJI alum Wei Jidong with early teammate Jiang Yixuan. Their first act was a parking robot—exactly what it sounds like. It didn’t stick. By late 2018 they admitted the idea lacked fit (few truly automated parking garages, high deployment friction) and pivoted to UGV chassis: standardized, ROS-friendly bases that other teams could build on. That pivot is the core of AgileX’s identity today. 
Agilex Robotics

They raised a RMB 4 million angel round in 2017 (Legend Star), then in August 2021 closed a Series A of ~RMB 100 million (~US $15.4 million) with a blue-chip China roster—Sequoia Capital China, 5Y Capital, Vertex Ventures China, and Hong Kong X-Tech Fund. The company’s own blog announced it in November 2021; third-party deal trackers peg the round at $15.4M. No subsequent rounds are public. 
Agilex Robotics
+1
Global Venturing
Tracxn

The product move—sell the “rice” (a robust base) rather than the full “meal”—got immediate traction. In a 2021 profile they claimed “50–60 units per month” across models, with list prices then “tens of thousands of yuan” (the top model “just over RMB 100k”). That implies an early run-rate on the order of ~600–720 units/year, and—if we assume a 2021 ASP around RMB 60–100k—back-of-the-envelope revenue of ~US $5–11M. Treat this as directional, not audited: it’s a company blog + my ASP assumption from their own pricing language. 
Agilex Robotics

Since then, AgileX has doubled-down on two levers:

Breadth of chassis (SCOUT wheeled, HUNTER Ackermann, BUNKER tracked, RANGER omni) plus edu/research kits (LIMO, ROS1/ROS2 bundles, “Cobot” kits). Their site also markets NAVIS autonomy and OEM customization. The strategy is to make the base easy, then sell kits that shorten time-to-demo for labs and integrators. 
Agilex Robotics

Global distribution rather than heavy direct sales. You see official distributor listings across North America and Europe; U.S. retail partners like Trossen and RobotLAB openly publish prices, which also serves as market signaling. 
Agilex Robotics
Trossen Robotics
RobotLAB

On pricing and channel tell-tales: current U.S. reseller pricing shows healthy gross room versus 2021 China-list talk. Examples: BUNKER Mini around $27.6k, RANGER Mini 3.0 around $44.8k, and RANGER (full-size omni) listed near $75.9k at a major U.S. distributor. Meanwhile, entry platforms like SCOUT 2.0 appear around $14.2k via education channels. That visible spread suggests AgileX meets both research budgets and heavier industrial pilots without changing brand. 
Trossen Robotics
+2
Trossen Robotics
+2
RobotLAB

What about headcount and revenue today? As a private Chinese company, clarity is limited. Public trackers consistently show small-to-mid size:

Employees: “25–100” (Owler), “51–200” (Tracxn), and “100–200” (SignalHire profile). I’d triangulate to double-digit to low-hundreds—plausible for a hardware firm with contract manufacturing and a distributor-first GTM. 
Owler
Tracxn
SignalHire

Revenue: Owler pegs a broad estimate of $100k–$5M (likely conservative and dated for a global distro network), while the 2021 unit-run anecdote plus today’s U.S. price points argue that >$5M annual revenue is feasible if volumes held or grew. No audited figures are published; PitchBook/Tracxn list ~$15.4M total funding with no disclosed 2022–2025 rounds. 
Owler
PitchBook
Tracxn

Strategically, AgileX has carved out a repeatable niche: become the “standard dev chassis” for labs, universities, and early-stage integrators; then creep upward into applied industrial work through partners. Their site and blog point to OEM/custom work and an autonomy stack (NAVIS), but the visible brand energy remains around platforms + kits—which is exactly why you see them everywhere from university syllabi to pilot projects. 
Agilex Robotics

A few additional signals worth noting:

Founders’ origin story & incubation (Xbot Park) matters. It gave them community, early hires, and a cred path similar to DJI’s ecosystem—useful when courting Sequoia/5Y/Vertex in 2021. 
Agilex Robotics

Channel proof via price transparency. Unlike many defense-leaning UGV vendors, AgileX lets resellers publish prices. That accelerates procurement for edu/research buyers and sets anchors for integrators building quotes. The U.S./EU MSRP levels show headroom for distributor margin and service packages. 
Trossen Robotics
+1
RobotLAB

Product cadence. Their catalog shows continuous refreshes (e.g., RANGER Mini 3.0), plus small “gateway” robots like LIMO/PiPER that seed classrooms and hobbyist labs—classic ecosystem thinking. 
Agilex Robotics
+1

What this means for your thesis
AgileX demonstrates that a chassis-first, kit-heavy, distributor-led business can scale globally without massive field-sales burn—especially if you own the BOM, keep SKUs modular, and let partners do payload and autonomy.

Their 2021 self-reported 50–60 units/month proves there’s steady demand for reliable, ROS-native outdoor bases at research/POC price points. The current U.S. MSRP spread shows room to graduate customers into higher-margin, mission-ready bundles. 
Agilex Robotics
Trossen Robotics
+2
Trossen Robotics
+2

The data opacity (funding since 2021, audited revenue) is normal for PRC private hardware firms. If you’re benchmarking, rely on unit-flow evidence (published distributor inventory/pricing, lead times, case studies) rather than model-shop market reports.

If you want, I can pull together a one-pager that contrasts AgileX’s playbook with Robotnik and Clearpath’s research-platform lines (channel, SKU architecture, accessories, warranty, and visible ASP tiers), and then map where a 150–300 kg-payload, teleop-first platform could wedge in U.S. industrial inspection without colliding head-on with their channel.