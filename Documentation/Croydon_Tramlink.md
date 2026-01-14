# Croydon Tramlink

## Network

Croydon Tramlink (more recently known as London Trams) is a tram network in South London, primarily in the Borough of Croydon. The network is the fourth busiest light rail network in the UK, after the Docklands Light Railway, Manchester Metrolink, and Tyne & Wear Metro.

Tramlink originally opened in 2000 with 38 stops (Centrale being added in 2005), focused on a central loop around Croydon itself using on-street running. Branches to Wimbledon, Beckenham Junction, Elmers End and New Addington are primarily built on the trackbeds of disused railway lines. The system is electrified with 750V DC overhead line, and has a nominal top speed of 80km/h (although this has been reduced to 70km/h following the Sandilands tram accident in 2016).

Rolling stock consists of 23 Bombardier CR4000 trams from opening, and 12 Stadler Variobahn trams subsequently ordered for various service improvements.

The majority of Tramlink operates using line-of-sight, with limited signalling (mainly consisting of points indicators) provided to control access to the single line and interlaced track sections. There are also signals interlocked with traffic lights at road junctions where the tram is running on the street.

## About the RailOS Project

Due to the nature of RailOS, signals have been added to the network. These are incredibly frequent to replicate the line-of-sight nature of real operations. All distances are as accurate as possible, measured from MapMeurisse given a lack of available accurate data. 

Speed limits are set to 70km/h across the network, except for Sandilands Junction, the street running sections, and terminus platforms. Despite the existence of speed limit diagrams through FOI requests, it was decided that this would provide additional complications to modelling the network with limited benefit, as despite this trams keep to their schedule pretty well.

## Simulation

Several service patterns have existed since the network opened, with the latest reorganisation of routes in 2018. This saw the abolition of public facing route numbers, although they still exist internally.

Standard service patterns are as follows (Daytime/Evening):

- New Addington to Croydon Loop: 8tph / 4tph
- Beckenham Junction to Wimbledon: 6tph / 4tph
- Elmers End to Wimbledon: 6tph Daytime only
- Elmers End to Croydon Loop: 4tph Evening only

## Operational Tips

- Operation at 2x speed is just about possible throughout the day, although it may be preferable to operate on normal speed to learn the service patterns.
- Headcodes consist of a letter for the destination, then three numbers which increment throughout the day:
    - A: New Addington
    - B: Beckenham Junction
    - C: Centrale / Croydon Loop
    - E: Elmers End
    - T: Therapia Lane
    - W: Wimbledon
    - X: Depot Movements
- During the day, trams should pass at the following locations:
    - Dundonald Road
    - Mitcham
    - Avenue Road
 This will result in some trams stuck at red signals, but they should still be on time by the next stop.
- Keep an eye on arrival times at Centrale to ensure trams from Wimbledon and trams coming round the loop are routed in the right order.
- Keep an eye on arrival times at Sandilands to ensure trams from each branch are routed towards Croydon in the correct order.
- It may be necessary to hold a tram departing towards New Addington to let a tram from Beckenham Junction / Elmers End to cross the junction first.
- Some trams (particularly at the start of service and during the change from Daytime to Evening service), need to wait at Elmers End Loop or Beckenham Loop. These have the dwell scheduled in their timetables.
- The timetable spreadsheet includes a diagram of how trams should be parked in the depot. This doesn't have to be followed, with the exception of the four trams finishing in the workshop. Tram numbers are included in the description for each service.
