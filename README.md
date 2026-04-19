# Cross-Site Request Forgery (CSRF) Interactive Learning Lab

## Overview

This project is a browser-based interactive lab designed to help learners understand Cross-Site Request Forgery (CSRF) through visual simulations and hands-on scenarios.

The lab focuses on how browsers handle authentication using cookies, how unintended requests are triggered, and how attackers exploit this behavior to perform actions on behalf of users without their knowledge.

All concepts are demonstrated in a safe, controlled environment for educational purposes.

## Objectives

* Explain how authentication using cookies works
* Demonstrate how browsers automatically send cookies with requests
* Show how CSRF attacks exploit trusted sessions
* Visualize the difference between user intention and authentication
* Provide interactive simulations of CSRF attack flow
* Teach practical prevention techniques

## Features

* Visual representation of authentication and request flow
* Interactive attack flow simulation (step-by-step)
* Demonstration of how malicious requests are triggered
* Clear visualization of browser behavior during requests
* Simulated real-world scenarios (password change, account actions)
* Explanation of prevention mechanisms such as CSRF tokens

## Covered Concepts

* Session-based authentication and cookies
* Browser request behavior
* CSRF vulnerability logic
* Difference between authentication and user intention
* CSRF attack flow (step-by-step)
* Conditions required for CSRF
* Comparison between CSRF and XSS
* Prevention techniques:

  * CSRF tokens
  * SameSite cookies
  * Origin/Referer validation

## How It Works

The lab is structured into progressive sections:

1. Authentication Flow
   Shows how login creates a trusted session

2. Browser Behavior
   Demonstrates automatic cookie handling

3. Attack Simulation
   Visualizes how a malicious request is triggered

4. Request Flow
   Shows how the server processes unintended actions

5. Impact
   Demonstrates real-world consequences of CSRF

6. Prevention
   Explains how proper validation prevents the attack

## Usage

This is a static web application and does not require installation.

To run the project:

* Download or clone the repository
* Open the main HTML file (e.g., `index.html`) in any modern web browser

No additional setup or dependencies are required.

## Important Note

This project is intended strictly for educational purposes.

All attack scenarios are simulated using mock data and controlled logic. The application does not perform real attacks and should not be used against real systems.

## Learning Use Cases

* Cybersecurity training sessions
* Classroom demonstrations
* Self-paced learning
* Web security fundamentals

## Future Improvements

* Advanced CSRF scenarios with token misconfigurations
* Integration with real-world testing workflows
* Enhanced visual diagrams for browser behavior
* Expanded challenge-based exercises

## Contribution

Contributions are welcome. Improvements to simulations, UI, or learning flow are encouraged.
