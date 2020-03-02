# PDQ-Hiring-Solutions-Engineer-Network-Admin

Please read the instructions and questions *carefully*. This is an open-book assignment, so feel free to use your highly honed Google-Fu skills, but please don't copy the work of others or have anyone else help you. The entire team will evaluate your homework, which means you are free to use acronyms and technical/industry-specific language where appropriate and expedient.

Create/open a plain .txt file and answer the following:

1. Briefly describe your experience using PDQ Deploy and PDQ Inventory.

2. You have a machine that responds to ping, but when you try to access it you discover you're accessing another machine entirely. Why? How do you troubleshoot and resolve this issue?

3. What are some common ways to make sure an application installation runs silently?

4. In your AD domain, you have computers frequently switching between different networks: VPN, wireless, wired, and VLANs. You are using Microsoft’s implementation of DHCP and DNS. Describe how you would configure DHCP or DNS (or both) to handle those computers.

5. Please describe in as much detail as you see necessary how you would design a network for a mixed environment (Windows, Linux, \*BSD) to meet the following requirements:
   1. Discrete network segments for the following business groups
      1. Sales & Marketing
      2. Development
      4. Testing & QA
      5. Operations
   2. Each network segment should be able to use a single organizational file server.
   3. Each business group should be able to traverse the network to all other business groups except for Sales and Marketing; they should only be able to access their own network.

6. Please select the five characteristics of a job or work environment that are the most important to you and rank them in order of importance (1 being most important).

```_____ Mentoring others
_____ Working with smart people ("A Players")
_____ Learning from others
_____ Working with nice people
_____ Doing things the "Right Way"
_____ Solving hard technical problems
_____ Making customers happy
_____ Working closely with a customer
_____ Opportunity for travel
_____ Creating innovative solutions
_____ Leading a team
_____ Developing / Providing high quality solutions
_____ Working on a team
_____ Opportunity for advancement
_____ Other: _____________________________
```

### For the following, please submit the respective XML files in the same .zip archive used for the scripting exercises at the end of this assessment.

1. In PDQ Inventory, create a registry scanner that checks for the default RDP port. Create two collections based on the results: one collection for machines with the default port and one collection for machines not using the default port. Please include the XML files for the scanner and both collections.

2. Using PDQ Deploy, create a package to deploy Office 365. Please include any config files you would use and the XML of the package.

### Scripting exercise:
Write a script (PowerShell preferred, but certainly not required) that does the following: 
* Find all json files located within each user's `%AppData%` directory.
* Output to the console in the following format: `.json files found in`

## Final Step:
When finished, zip up the following into one archive, ensuring the single .zip file contains your name:
- [x] The plain .txt file containing the questions and answers to the first 15 questions
- [x] The XML files from the seven PDQ Inventory and PDQ Deploy questions. The XML files should be tied logically to their respective exercises. How you decide to do that is part of the assessment.
- [x] The script from the scripting exercise

Once you have completed the above, upload the .zip file to https://link.pdq.com/application (no account required). Submissions are reviewed within 3 - 6 business days by the entire team and considered for an interview.

## :warning: Important
*Do not include anything in your homework submission (other than your name as the zip file) that could identify you. Submissions are anonymized on receipt so our team does not know whose homework they are evaluating.*
