---
lang: en-US
title: Product Security Ambassadors
author:
- Osman Esquivel and Ignacio Lopez
date: October 20^th^, 2022
theme: solarized
slideNumber: true
title-slide-attributes:
     data-background-image: title.png
     data-background-size: contain
     data-background-color: "rgb(0,48,87)"
include-after: |
     <div class="slides">
        <img class="footer" src="footer.png"/>
     </div>   
#<!--     data-background-color: "rgb(0,48,87)"-->
#<!--      background-color: #003057;-->

# pandoc --from markdown --to revealjs --embed-resources --include-in-header=slides.css --standalone -o PSA-WhatWeDo.html WhatWeDo.md

...

# Product Security Ambassadors <!-- Ignacio -->

## Product Security Champions who represent a team/region, as opposed to an application

## MXC Office

  + Osman Esquivel
  + Ignacio Lopez

## Shanghai Office

  - Mike Xu

## Deployment

  - Ed Southgate

## More PSA to be added

  - QE team

# What do they do? <!-- Ignacio -->

##

- Spread awareness of product security among development teams

- Share product security resources and information

- Gather feedback from development teams/regions regarding product security

- Auxiliary support in product security activities

# Our Current Activities <!-- Ignacio -->

## 1. Product Security Council meetings

   <!-- nothing here -->

## 2. Automation of SAST (Appscan)

  - A utility to setup and run a scheduled SAST (appscan scanning)

  - Documentation 
  
  - Support as needed

## 3. Help testing the new signing tool for the CI/CD pipeline

  - Using digest signing

# Why security matters? <!-- Osman -->

## 

[Cyber Security At its Best in 5 min](https://youtu.be/B6dZWe7eOpA)

## 

 - Minimize the risk
 
 - You are as secure as your weakest link
 
 - Fundamental to adopt strong security practices to avoid security breaches
 
## There is a cultural shift in Cybersecurity

 - Customers and government are raising expectations for cybersecurity 

 - Increased expectations on disclosure and visibility

 - We need to adjust our processes and activities to meet these new expectations

# Essential for security <!-- Osman -->

## Grow the security culture

# Security Champion  <!-- Osman -->

##

- Leadership + Mindset + Skill Set

- Handles the relation between its team and the security team

- Does security reviews

- They need to be interested in security 

- Collaborative 

- Good communicator

- Help keep everybody on target

# Evolving Security Champions Roles <!-- Osman -->

## New specialized roles

- Benefits / Purpose

  - Scale Up

  - Maturity

## Roles based on

 - Skills

 - Interests
 
 - Needs

# Proposed new roles <!-- Osman -->

## Risk Engineers (PSC roles)

. . .

  - Help review final version of Policy, Procedures, and Guidelines

  - Threat modeling

  - SAST scanning
  
  - Security Defects

  - Culture push

## Product Security Ambassadors

. . .

  - Represent a region
  
  - Provide feedback, policies, guidelines

  - Work on larger-scale initiatives

  - Will be supporting if there are considerations for the team they represent

## Security Practitioners

. . .

  - Assist in the development of security patterns and best practices

  - Assist in deeper dives into security technical issues

  - May be asked to help with Security Requirements 

    - Definition of controls and when to apply them

    - How to apply for different technologies or product context

## CI/CD → Continuous Integration / Continuous Deployment

. . . 

### (Checking in code and continuous building)

## 

 - It was emphasized on delivery not security

 - DevOps teams  may lack security knowledge

 - Traditional automated testing does not focus on Security Testing

 - Figure out the risk of the libraries on our applications

## OWASP

- Tools must be integrated into the pipeline

- Tools must not require security expertise

- Tools result must be accurate and important

- Engineers must have high confidence that fixing issues won't break other things

# Security Development Lifecycle (SDL) <!-- Ignacio -->

##

- Set of practices that support security assurance and compliance requirements 

- Help developers build more secure software 

  + By reducing the number and severity of vulnerabilities 

  + While reducing development cost

# SDL Timeline <!-- Ignacio -->

##

![](http://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RE2K1q8?ver=5f86)
*Source: [About Microsoft SDL, Microsoft 2022](https://www.microsoft.com/en-us/securityengineering/sdl/about)*

# Aspentech's SDL <!-- Ignacio -->

##

![](AspenSDL.png){width=100% height=auto}

## How to write secure code? 

. . . 

- For C++ first thing to do is:
  - Does your code compile with zero warnings?
  - Prevent people from using bad methods. 
  - We may be vulnerable with a buffer overflow

# SDL Practices <!-- Osman -->

##

- Provide security training (at least one a year on different things) 
  - DevOps
  - Data 
  - Social Engineering

- Cryptographic standards

- Threat modeling 

- Establish a standard incident response process

##

![](./deskbefore.jpg)

. . .

![](./deskafter.jpg)

## Social Engineering 
  - Phishing
  - Pretexting
  - Baiting
  - Quid Pro Quo
  - Tailgating

# High-Profile Security Breaches <!-- Osman -->
  
## 

![](./logo_solarwinds.png){transition=zoom}

## 

![](./equifax_logo.png){transition=zoom}

## 

![](./Target_logo.png){ width=30% transition=zoom}

# How are we doing?  <!-- Ignacio -->

##

- Understand what components make up your application

  - Purchased 3rd Party

  - OSS

- Licensing requirements

   - Apache 2.0

   - GPL is a security risk to the company

. . .

## [It can make our IP public!]{.mark}{transition=zoom}

# ![](logo.png) {background-color="rgb(0,120,201)" transition=convex}
