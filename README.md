# Joomla Academy Onboarding Documentation

## Welcome to the Joomla Academy!

The Joomla Academy is a global program that aims to bring new contributors and improved features to Joomla by providing mentored coaching and teaching for students with PHP, JavaScript, UX, and UI skills. This initiative, managed by Open Source Matters (OSM), creates a pathway for students to learn about open-source development while contributing meaningful code to the Joomla ecosystem.

## About the Joomla Academy

Building on the success of previous Google Summer of Code (GSoC) and Summer of Code (SOC) collaborations, the Joomla Academy takes control of our own educational initiatives. The Academy aligns with Joomla's release cycle to ensure student contributions make it into production.

### Program Structure
- **Two intakes per year**: April and October
- **Six-month development terms**
- **$3,000 stipend** per student
- **Comprehensive mentorship** and training
- **Alignment with Joomla's release schedule**

## Timeline for April 2025 Intake

| Date | Event |
|------|-------|
| March 10 - April 22, 2025 | Application period |
| May 13, 2025 | Final selection announced |
| May 13-20, 2025 | Community bonding period (1 week) |
| May 20 - September 30, 2025 | Work period |
| July 15, 2025 | Midterm evaluations |
| September 30, 2025 | Final submission deadline |
| October 1-15, 2025 | Final evaluations and results announced |

## Timeline for October 2025 Intake

| Date | Event |
|------|-------|
| July 1 - August 15, 2025 | Application period |
| September 15, 2025 | Final selection announced |
| September 16-30, 2025 | Community bonding period |
| October 1, 2025 - March 31, 2026 | Work period |
| January 15, 2026 | Midterm evaluations |
| March 31, 2026 | Final submission deadline |
| April 1-15, 2026 | Final evaluations and results announced |

## Available Projects for 2025

The Joomla Academy is launching with two flagship projects that build upon previous successful initiatives:

### 1. Enhanced SEO Integration

Building upon the successful GSoC 2022 SEO project, this initiative aims to further integrate and enhance Joomla's SEO capabilities.

**Project Objectives:**
- Improve core SEO tab functionality
- Enhance content analysis tools
- Implement advanced metadata management
- Optimize image compression features
- Develop new social media integration capabilities

**Project Resources:**
- GSoC 2022 Project: [https://summerofcode.withgoogle.com/archive/2022/projects/7uMIihJR](https://summerofcode.withgoogle.com/archive/2022/projects/7uMIihJR)
- GitHub Repository: [https://github.com/alisha-kamat/GSoC-2022-Work-Report](https://github.com/alisha-kamat/GSoC-2022-Work-Report)

**Technical Focus:**
- Convert existing proof-of-concept code into production-ready plugins
- Ensure compatibility with Joomla 5.x codebase
- Implement secure coding practices
- Create proper documentation

**Mentorship Team:**
- Martina Scholz
- Benjamin Trenkle
- Louise Hawkins
- Phil Walton

### 2. Advanced Migration Tools

This project focuses on expanding Joomla's migration capabilities, building on the foundation laid by the WordPress migration tool.

**Project Objectives:**
- Develop a framework-agnostic migration system
- Enhance media transfer capabilities
- Improve database migration processes
- Create comprehensive logging and error handling
- Implement user-friendly progress tracking

**Project Resources:**
- GitHub Repository: [https://github.com/joomla-projects/soc23_joomla-converter](https://github.com/joomla-projects/soc23_joomla-converter)
- Academy Repository(new): [https://github.com/joomla-projects/JA-Advanced-Migration-Tool](https://github.com/joomla-projects/JA-Advanced-Migration-Tool)
- Mattermost Channel: [https://joomlacommunity.cloud.mattermost.com/main/channels/ospp-23---wordpress-to-joomla-migration-tests](https://joomlacommunity.cloud.mattermost.com/main/channels/ospp-23---wordpress-to-joomla-migration-tests)

**Technical Focus:**
- Extend the migration tool to support additional CMS platforms
- Improve user experience during migration process
- Implement robust error handling
- Ensure security during the migration process

**Mentorship Team:**
- Manu Beladevan 
- Brian Mitchell
- Shirielle Williams
- Gary Barclay

## Eligibility Requirements

To participate in the Joomla Academy, you must:

- Be at least 18 years old at the time of application
- Not be from a US-embargoed country (see note below)
- Be able to commit to 6 months of development work
- Possess basic programming knowledge in PHP, JavaScript, and/or UI/UX design
- Have a passion for open-source development

**Note on US Embargoes:** As Open Source Matters is a US-based organization, we must comply with US trade restrictions. Currently, comprehensive sanctions are in place for countries such as Cuba, Iran, North Korea, Syria, and the Crimea region of Ukraine. The specific details and list of countries may change over time.

## How to Apply

1. Fill out the application form: [https://docs.google.com/forms/d/e/1FAIpQLSd1rRIOJ6otnTZJ5OSpVR8braqXbmBP8MfgSlxADdbRWrDi3Q/viewform](https://docs.google.com/forms/d/e/1FAIpQLSd1rRIOJ6otnTZJ5OSpVR8braqXbmBP8MfgSlxADdbRWrDi3Q/viewform)
2. Familiarize yourself with the project resources mentioned above
3. Start exploring the Joomla codebase and development environment

## Development Environment Setup

To contribute to Joomla, you'll need to set up a proper development environment:

### System Requirements
- PHP 8.1 or higher
- MySQL 5.7 or higher / PostgreSQL 12.0 or higher
- Apache 2.4 or higher / Nginx 1.18 or higher

### Recommended Development Tools
- Git for version control
- GitHub account for code submissions
- Code editor with PHP support (VS Code, PhpStorm, etc.)
- Composer for PHP dependency management
- Node.js and npm for JavaScript development

### Setting Up Joomla Locally
1. Clone the Joomla repository: `git clone https://github.com/joomla/joomla-cms.git`
2. Install dependencies: `composer install`
3. Set up a local web server (Apache, Nginx, or built-in PHP server)
4. Create a MySQL/PostgreSQL database
5. Run the Joomla installer by accessing your local site in a browser

## Working with the Joomla Codebase

### Joomla 5.x Coding Standards
- Follow PSR-12 coding standards for PHP
- Use ESLint standards for JavaScript
- Follow Joomla naming conventions
- Write secure code: validate all inputs, escape all outputs, use prepared statements for database queries

### Git Workflow
1. Fork the project repository
2. Create a feature branch for your work
3. Make your changes in small, logical commits
4. Write clear commit messages
5. Submit pull requests for review
6. Address feedback and make requested changes

## Student Responsibilities

As a Joomla Academy participant, you are expected to:

- Submit high-quality work (code and documentation)
- Communicate regularly about progress, plans, and obstacles
- Re-evaluate work scope when significantly ahead or behind schedule
- Engage with both mentors and the broader Joomla community
- Promptly inform about any reduction in work capacity
- Respond constructively to feedback

## Sponsorship and Funding

The Joomla Academy is funded through generous sponsors from the Joomla community. We'd like to recognize our founding sponsors who have helped raise $17,000 to launch the program:

- JAB eV
- reDim
- djumla, David Jardin
- Phil Walton, SoftForge
- tec-promotion, Stefan Wendhausen
- yootheme
- David Schmitthusen
- formativ.net
- Verein Open Source CMS Austria
- Corinne Meister
- Yannick Gaultier
- Guido De Guido
- Geraint Edwards
- Adi Heutschi
- Alexander Girod
- Claudia Weber-Lenck
- Christine Trutt-Ibing
- Beat Bachmann, Webhand Webdesign GmbH
- Niko Winkel
- Andreas Heisinger

## Contact and Support

For questions or additional information:

- **Student Channel on Mattermost**: [https://joomlacommunity.cloud.mattermost.com/main/channels/ja-students](https://joomlacommunity.cloud.mattermost.com/main/channels/ja-students)
- **General Inquiries**: [vicepresident@opensourcematters.org](mailto:vicepresident@opensourcematters.org)

## Conclusion

The Joomla Academy represents a significant step forward in Joomla's commitment to open-source education and development. By participating, you're not only gaining valuable experience and a stipend, but you're also making a meaningful contribution to one of the world's leading content management systems. We look forward to welcoming you to our community!
