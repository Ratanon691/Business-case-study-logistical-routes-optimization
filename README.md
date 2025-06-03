Feed Ingredient Logistics Optimization – Charoen Pokphand Foods (CPF)

Overview
This project addresses operational inefficiencies in the feed ingredient logistics planning process at Charoen Pokphand Foods (CPF), a leading agribusiness company in Thailand. The existing manual workflow for distributing over 20,000 tons of feed ingredients to 13 factories each week was time-consuming and prone to suboptimal decisions.
a mathematical optimization model was developed to automate shipment planning, minimize logistics costs, and improve warehouse utilization.

Business Problem
CPF faced several critical operational challenges:

* Time-Intensive Planning: Manual logistics planning required 2 full days per week from the logistics team.
* Inefficient Warehouse Utilization: Limited optimization of factory warehouse capacity led to an overreliance on expensive rented warehouse space.
* Complex Transportation Options: Multiple combinations of transport and storage routes made manual cost minimization infeasible.
* Data Silos: Disconnected communication among factories, warehouses, and shipping companies created friction and delays in the decision-making process.

The objective was to create an optimization solution that could:

* Reduce planning time
* Minimize total logistics costs (transportation + warehousing)
* Improve utilization of factory warehouses
* Enable scalable and consistent decision-making

Approach
1. Requirements Gathering and Process Mapping
* Conducted structured interviews with logistics planners and factory warehouse managers
* Observed and documented the complete 2-day planning workflow
* Mapped existing operations and identified constraints such as storage capacities, shipment timing, and port releases
* Translated business requirements into user stories and mathematical constraints

2. Model Development and MVP Design
Built a mathematical optimization model using linear programming with the following objectives:

* Minimize total logistics and storage costs
* Maximize utilization of factory warehouse space before using external rented storage
* Ensure timely deliveries to each factory without exceeding their receiving capacity
* The MVP was developed using Microsoft Excel for rapid testing and validation. Key features included:
* Cost comparison matrix for all shipping and warehousing options
* Constraint handling for factory capacities and delivery schedules
* Output visualizations comparing manual vs. optimized results

3. Pilot Testing and Validation
Conducted a parallel run using real shipment data for one month
* Compared performance between manual planning and model-based optimization
* Tracked metrics including cost per shipment, warehouse usage, and planning time
* Collected edge cases and operational exceptions for refinement

4. Stakeholder Engagement and Business Case Presentation
* Created visualizations to communicate performance improvements
* Delivered ROI analysis quantifying savings and operational impact

Results and Impact

Quantitative Improvements

* Planning Time	2 days/week	-> 30 minutes/week	97% reduction
* Reduce logistics Costs ~10% per shipment	~mid six-figures THB savings/month
* Warehouse Utilization	Suboptimal	+30% improvement	Reduced external storage

Qualitative Benefits
* Scalability: The system can support increased shipment volume without requiring additional staff
* Consistency: Reduced dependency on individual decision-makers
* Transparency: Clear audit trail of shipment decisions
* Staff Productivity: Freed up time for value-added analysis and coordination

Key Learnings
* Complex logistical workflows can be significantly improved through structured process analysis and mathematical modeling
* Prototyping with Excel facilitated low-risk experimentation before scaling to a full system
* Continuous stakeholder engagement ensured solution relevance and user adoption
* Visual communication of results played a key role in securing executive support

Areas for Future Improvement
* Automation and System Integration: Connect with real-time ERP data and shipment tracking
* User Interface: Develop an interactive dashboard for improved planner usability
* Data Feeds: Automate updates from port releases, warehouse capacity, and factory needs
* Scalable Infrastructure: Transition to a cloud-based environment for better performance and access control

Relevance
This project demonstrates the application of business analysis, process optimization, and quantitative modeling to solve a real-world operational challenge. It aligns with objectives around cost control, efficiency, and digital transformation in enterprise logistics.
