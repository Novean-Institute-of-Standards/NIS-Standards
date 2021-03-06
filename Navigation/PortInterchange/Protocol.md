# Port Interchange Protocol: 1ST DRAFT - PROPOSAL

*Summary: A standard of customs to be utilized for take-off from, and landing at, locations in* Dual Universe.

- [Port Interchange Protocol: 1ST DRAFT - PROPOSAL](#port-interchange-protocol-1st-draft---proposal)
  - [Introduction](#introduction)
    - [Motivation](#motivation)
    - [Key Concepts](#key-concepts)
    - [Issues not addressed by this proposal](#issues-not-addressed-by-this-proposal)
  - [The Port Interchange](#the-port-interchange)
    - [Speed Zone](#speed-zone)
    - [Alignment Zone](#alignment-zone)
    - [Transition Zone](#transition-zone)
    - [Approach and Take-off Vectors](#approach-and-take-off-vectors)
    - [Vertical Take-off and Landing (VTOL) concepts](#vertical-take-off-and-landing-vtol-concepts)
  - [Implementation](#implementation)
    - [For Pilots and Navigators](#for-pilots-and-navigators)
    - [For Facility Owners](#for-facility-owners)


## Introduction

This document describes a proposal for a set of standards, customs, and definitions for a protocol to be used when travelling from one player-made point of interest to another, specifically for those that provide *Port Facilities*.  

It contains guidelines for a set of customs for players to follow when near such a location, and to define a set standards and practices to be implemented by Port Facility owners.

### Motivation

The primary motivation for this proposal is safety - to offer players a way to travel from one location to another while mitigating concerns of collisions with the landscape, buildings, players, and other vehicles.  

If a player can be assured that they have a specific plan to arrive at or depart from any given location, and that other players in the vicinity also have a similar plan, that player may develop a stronger sense of community within the game, simply because the act of travelling itself would be less worrisome.

Another motivation for this proposal is simplicity.  As of this document’s creation, Dual Universe has only one navigational indicator - the destination.  This indicator is simply a representation of a point in space relative to the player, along with the relative distance from the player to the location.  

This proposal currently utilizes this indicator, and builds its concepts around it.

### Key Concepts

Key concepts and definitions used in this section.

**Dead Reckoning.**  All elements of this standard are centered around information provided by waypoints (Destinations), therefore any element dealing with distance will use the player's distance from a particular waypoint.

**Zones.**  A *Zone* is an area, defined in its simplest form as a circle, and extended into cylinders and spheres, whose radii are derived from the distance from a location's waypoint,  Indicating a specific pattern of behavior for a pilot to adhere to within the specified area.

**Port Facilities.**  A *Port Facility* in the scope of this proposal is a specific, centralized location that any number of players may travel to and from using vehicles, and usually provides dedicated areas for landing, refitting/refueling, and take-off.  

Examples of port facilities are organization headquarters, surface-borne player-made spaceports and space stations.

**Navigational Aids.**  A *Navigational* Aid can be a waypoint(destination), or a vector indicator - a physical representation of the direction a vehicle should be travelling along when taking off or landing.  

Currently, the waypoint and vector indicator are the only tools provided in-game.

**Pilots’ priorities.**  Due to the nature of the information available to pilots and the current limitation, this proposal cannot completely ensure safe and unobstructed travel near port facilities.  

Therefore, pilots must still maintain situational awareness during flight within zones, and should yield to traffic already present in applicable zones.

**Space.**  For the purposes of this document, the term *space* will refer to both "airspace" - the area above ground in relation to various concepts, as well as the "space" around an asteroid or space station.

### Issues not addressed by this proposal

As of this document's creation, its sole purpose is to provide a singular standard for navigating the space associated with a location, using only in-game information available to any player.  

It *does not* define a standard for any other aspect of navigation associated with landing and take-off, whether done through active interaction with other players(Air Traffic Controllers), or with the use of in-game scripting. 
 
 This standard also does not define any sort of its own enforcement,  and its utilization should be done through mutual acceptance, or enforced from within a player's organization.

## The Port Interchange

All zones of the Port Interchange will be concentric to a waypoint, placed just above the landing/take-off area of a location.  

Typically, a map-generated waypoint will be inaccurate for the purposes of this standard, and therefore should be manually generated by a player/organization.  

In addition, this waypoint should be shared with all players who would have access to its associated location.

### Speed Zone

The *Speed Zone* of a location is the outermost boundary of the port interchange.  It is the first interaction with an interchange for players arriving to a location, and the last interaction for players travelling away from a location.  

For surface-based locations, it is a cylinder with a radius of *N* meters(m), with the base of which is coplanar with the surface around a location, extending upwards through a location's space.  

For locations *in space*, it is a sphere with a radius of *N* m.  While the player is inside of this zone, a vehicle's speed should remain as close to *N* kilometers per hour(km/h) as possible.

### Alignment Zone

The *Alignment Zone* of a location is next closest boundary of the Port Interchange, and is concentric with the Speed Zone.  For planar locations, it is a cylinder with a radius of *N* m, extending upward into the space around a location.  

For space-based locations, it is a sphere of *N* m, which is concentric to the Speed Zone.  The purpose of the Alignment Zone is to define an area from which a vehicle will change from travelling in a straight line towards/away from a location into the "circling" pattern defined by the Transition Zone.  

All guidelines for vehicles in the Speed zone also apply to this zone.

### Transition Zone

The *Transition Zone* of a location defines the path to be taken by vehicles before turning into *Approach* and *Take-off Vectors*.  For planar locations, this zone will be a circle with a radius of *N* m, and runs parallel at a pre-defined height above the surface.  

For orbital locations, this zone will be a circle that is coplanar with the approach and take-off vectors and aligned with the locations gravity(if any).  pilots will use this zone to maintain a set distance from the location's waypoint.  

Like the Alignment zone, the Transition zone is also within the speed zone, and all guidelines for vehicles within the speed zone apply to this zone as well.

### Approach and Take-off Vectors

The *Approach Vector* and *Take-off Vector* are separate direction indicators moving towards and away from a location, respectively.  

For vehicles on an Approach Vector, a location may have a lower speed and right-of-way guidelines for the purpose of taxiing out of the vector and onto a final landing point.  For vehicles intending to take off,  location-specific guidelines may be made concerning right-of-way when entering a Take-off Vector.

### Vertical Take-off and Landing (VTOL) concepts

further discussion on this set of concepts is needed.

## Implementation

### For Pilots and Navigators

Guidelines for Pilots and Navigators

**Speed Zone.**  For pilots approaching a location piloting vehicles that may not be able to completely slow their vehicle to the indicated limit *before* approaching the alignment zone, *must* start to reduce speed *before* entering the speed zone to ensure this limit is attainable.  

Along with adhering to the speed limits, a pilot approaching a location and moving within the speed zone should begin to alter their course from a straight line pointing towards a location's waypoint, to one that is a tangent to the boundary of the alignment zone, placing the waypoint on the L/R side of the approaching vehicle.

**Alignment Zone.**  This zone may also have a higher density of traffic, therefore pilots must be increasingly more cautious when entering and leaving this zone.  

When pilots are departing from a location and are in the Alignment zone to the speed zone, their waypoint can be changed another in regards to their destination, and then may proceed in a straight vector towards it, while yielding to any traffic merging in from the Speed Zone.

**Transition Zone.**   Approaching vehicles *must* remain in this zone until both a transition to the Approach Vector can be made without further intrusion into the location, and when there is no traffic blocking such a maneuver. 

Inversely, pilots with the intent to take-off and merge into the Transition Zone from the Take-off Vector must yield to traffic entering or already present in the Transition Zone, or traffic merging in from the Alignment Zone.

### For Facility Owners

Guidelines for Facility Owners

**Zone Sizes and Speed Limits.**  For the purposes of the proposal of this standard, none of distances and speeds referenced within this proposal have been given real values.  

Further discussion will be needed to discern the needs of this standard.

**Approach and Take-off Vector Indicators.**  As a Facility Owner,  there is no current guideline for the manner in which *Vector Indicators* should be advertised to Pilots, however, the visibility of these indicators should be clear and conspicuous to any pilot currently within the *Transition Zone*.  

Any combination of voxels and/or screens may be used to communicate this information; with a strong preference towards voxels, as their visibility is much clearer compared to screens.
