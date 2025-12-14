---
title: 'Fund Route F for Fishkill'
date: 2024-12-13
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Hochul Funded the Bridge. Fund Route F for Fishkill.
      text: A campaign to extend, expand, and eliminate fares on Dutchess County Public Transit Bus Route F connecting Fishkill to Beacon Metro-North station
      primary_action:
        text: Take Action
        url: "#take-action"
        icon: megaphone
      secondary_action:
        text: Read the Facts
        url: "#facts"
    design:
      css_class: "dark"
      background:
        color: "#054b7a"

  - block: markdown
    id: logo-display
    content:
      title: ""
      text: |
        ![Fund Route F for Fishkill](/media/bus-logo.jpg)
    design:
      css_class: "bg-white text-center"
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  - block: stats
    id: problem
    content:
      items:
        - statistic: "½ Mile Short"
          description: |
            Bus stops at the Beacon Post Office, not the Beacon Metro-North train station
        - statistic: "Bad for commuting"
          description: |
            8 trains leave before the first bus starts at 7:30AM.
            0 buses from Beacon to Fishkill during the 6PM hour.
        - statistic: "No Sundays"
          description: |
            Zero service for work, family, church, or errands
    design:
      css_class: "bg-orange-50"
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  - block: stats
    id: impact
    content:
      items:
        - statistic: "22K+"
          description: |
            Fishkill residents  
            need better transit
        - statistic: "7%"
          description: |
            of Dutchess households  
            have no car
        - statistic: "111K+"
          description: |
            seniors & youth  
            who can't drive
        - statistic: "1k%"
          description: |
            ridership increase when  
            Beacon Loop went free
    design:
      css_class: "bg-gray-100"
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  - block: features
    id: solution
    content:
      title: Five Actions to Fix Route F
      text: We're asking Dutchess County to make these changes
      items:
        - name: Run on Sundays
          icon: calendar
          description: Match the Beacon Free Loop's Sunday hours for work, church, and family visits.
        - name: Extend the Route
          icon: map-pin
          description: Reach Beacon Metro-North station—provide a true one-seat ride to rail for Fishkill commuters.
        - name: Start Earlier
          icon: clock
          description: Begin service by 5:30 AM so commuters can catch trains arriving in NYC by 8:00 AM.
        - name: Cover rush hour
          icon: calendar
          description: Run buses from Beacon Metro-North during evening commuter hours - there are no buses during the 6PM hour
        - name: Eliminate Fares
          icon: currency-dollar
          description: Follow the proven model that increased Beacon Loop ridership by over 1,000%.

  - block: cta-image-paragraph
    id: facts
    content:
      items:
        - title: Beacon Free Loop Success
          text: The proof is in the ridership numbers
          feature_icon: check
          features:
            - "Ridership jumped from 3,000 to 38,000+ after going fare-free"
            - "City invested just $11,000/year to subsidize fares"
            - "Sunday service added in January 2025 due to demand"
          image: build-website.png
          button:
            text: View Fact Sheet
            url: "#resources"
        - title: State Funding Supports This
          text: Better service means more state and federal dollars
          feature_icon: bolt
          features:
            - "NY's STOA program allocates ~$3.7M/year to DCPT based on ridership"
            - "Governor Hochul made the 2026 bridge shuttle fare-free all year"
            - "FTA Section 5307 formula funding increases with passenger miles"
          image: coffee.jpg
          button:
            text: Read Full Research
            url: "#resources"
    design:
      css_class: "bg-gray-100"

  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Sue Serino"
          role: "Dutchess County Executive, December 2024"
          image: "testimonial-1.jpg"
          text: "By linking our communities through public transit, we're expanding access to jobs, strengthening tourism, reducing traffic and emissions, and ensuring that residents from both sides of the Hudson River can move easily and affordably."
        - name: "Governor Kathy Hochul"
          role: "Announcing the fare-free bridge shuttle, December 2024"
          image: "testimonial-1.jpg"
          text: "Better access to fast and reliable transit is an affordability win for New Yorkers. This enhanced service will save people time, improve connections and strengthen communities."
    design:
      spacing:
        padding: ["6rem", 0, "2rem", 0]

  - block: cta-card
    id: take-action
    content:
      title: Make Your Voice Heard
      text: |
        Contact County Executive Sue Serino and ask her to fund Route F improvements.
        
        **Email:** CountyExec@dutchessny.gov  
        **Phone:** (845) 486-2000  
        **Address:** 22 Market Street, 6th Floor, Poughkeepsie, NY 12601
        
        **#ConnectFishkill  ·  #FundRouteF  ·  #SundaysCount**
      button:
        text: Send an Email Now
        url: "mailto:CountyExec@dutchessny.gov?subject=Fund%20Route%20F%20Improvements&body=Dear%20County%20Executive%20Serino%2C%0A%0AI%20am%20writing%20to%20ask%20you%20to%20improve%20DCPT%20Route%20F%20by%3A%0A%0A1.%20Extending%20the%20route%20to%20Beacon%20Metro-North%20station%0A2.%20Adding%20early%20morning%20service%20by%205%3A30%20AM%0A3.%20Implementing%20Sunday%20service%0A4.%20Eliminating%20fares%2C%20following%20the%20successful%20Beacon%20Free%20Loop%20model%0A%0AThank%20you%20for%20your%20consideration.%0A%0ASincerely%2C%0A%5BYour%20Name%5D"
    design:
      card:
        css_class: "bg-[#054b7a] text-white [&_*]:text-white"
        css_style: ""

  - block: markdown
    id: resources
    content:
      title: Resources & Downloads
      text: |
        ### Campaign Materials
        - [Campaign Fact Sheet (PDF)](/files/Route-F-Fact-Sheet.pdf) — One-page summary with key statistics
        - [Printable Flyer (PDF)](/files/Route-F-Campaign-Flyer.pdf) — Share with neighbors and post in your community
        
        ### Official Sources
        - [DCPT Route F Schedule](https://www.dutchessny.gov/Departments/Public-Transit/DCPT-Route-F.htm)
        - [Metro-North Hudson Line Schedule](https://www.mta.info/schedules)
        - [Moving Dutchess Forward (County Transit Plan)](https://movingdutchessforward.com/)
        - [Governor's Bridge Shuttle Announcement](https://www.governor.ny.gov/news/better-transit-hudson-valley-governor-hochul-announces-enhanced-newburgh-beacon-bridge-shuttle)
        
        ### Research Documents
        - [Full demographic and transit analysis](#) — Detailed research supporting this campaign
    design:
      css_class: "bg-gray-100"

  - block: cta-card
    content:
      title: "Sundays Count. So Do We."
      text: Join the campaign to connect Fishkill to opportunity.
      button:
        text: Take Action Now
        url: "#take-action"
    design:
      card:
        css_class: "bg-[#d94506] text-white [&_*]:text-white"
        css_style: ""
---
