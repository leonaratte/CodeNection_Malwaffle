# Project Overview 
## The Problem: The "Scattered Planning" Chaos

Modern travel planning is a high-friction, fragmented experience. Travelers are forced to manually bridge the gap between flights, accommodations, fluctuating budgets, and diverse group preferences. Currently, this critical data is never centralized, typically ending up scattered across five or more different apps and buried within disorganized group chat threads.

## Existing market solutions suffer from three core architectural failures:
1. Manual Data Piecing: Most platforms are siloed, specializing in only one vertical—either booking, budgeting, or itinerary    mapping—forcing the user to act as the manual integrator.

2. Group Coordination Friction: Aligning multiple schedules, budget constraints, and personal interests is a logistical      
   nightmare that current tools fail to synchronize effectively.

3. Static Planning vs. Dynamic Reality: When "life happens"—such as a flight delay or a closed venue—existing plans become      obsolete instantly, offering no automated support for mid-trip adjustments.

## The Solution: The All-in-One AI Planner
TravelSync is a comprehensive travel management ecosystem designed to orchestrate the entire travel lifecycle. By centralizing preference syncing, automated budgeting, and intelligent itinerary building, the platform reduces cognitive load for solo travelers and eliminates the "planning fatigue" of group organizers.

Value Proposition: TravelSync evolves travel planning from a static, manual chore into a dynamic, AI-assisted automation experience. It transitions the itinerary from a fixed document into a living, real-time "single source of truth" that adapts to the group’s needs.

## Key Features & Functionality
1. AI-Powered Itinerary Generation
The platform utilizes advanced LLM logic to transform raw user inputs (budget, interests) into a coherent plan. A key technical differentiator is the "Itinerary Susun" (Arrangement) Logic: the AI uses the user's selected Hotel as the primary anchor point. All suggested activities and food spots are sorted and clustered based on their physical distance from the accommodation to minimize transit time and maximize exploration.

2. Collaborative Group Voting & State Management
To solve the "Group Chat Chaos," TravelSync implements a structured voting module. Participants vote on four critical dimensions:
Date (Tarikh): Temporal alignment.
Budget (Min/Max): Financial boundaries.
Place (Tempat): Geographic destinations.
Activity (Aktiviti): Experiential preferences.
Consensus Logic: The UI displays the "Average Budget" to all members in real-time, allowing the system to suggest a "Majority" path that satisfies the most constraints while maintaining financial transparency.

3. Intelligent Category Browsing
Travelers can discover vetted locations via a categorized interface. Each search is refined by a Country/State filter metadata layer to ensure localized relevance.
Category                                         Description
Nature                                           Scenic landscapes, parks, and natural wonders.
Adventure                                        High-energy activities and outdoor excursions.
Cafe                                             Curated local dining and coffee culture.
Souvenir                                         Local crafts and retail landmarks.

4. Integrated Booking & Reservations
TravelSync closes the loop between planning and execution through deep-linking and API integrations:
Accommodations: Direct hand-off to Hotel providers (Booking.com, Airbnb).
Activities & Transport: Real-time ticket procurement via Klook and integrated transport booking.
Dining: Integrated restaurant reservation management.

## User Journey & App Flow
Authentication: Secure Login/Registration.

Mode Selection: Selection between "Individual" or "Group" orchestration modes.

Input Phase: Users define budget ceilings across four specific buckets: Makan (Food), Activity, Transport, and Hotel.

AI Curation: The engine generates "Place/Activity/Food" suggestions. Crucially, the user chooses which specific activities to accept into the master plan.

Refinement: Final manual "Add/Remove" adjustments to the suggested itinerary.

