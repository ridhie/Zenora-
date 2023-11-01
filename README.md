
# Zenora - Your AI Mental Health Companion

- [Project summary](#project-summary)
  
Zenora, our initiative, unveils an AI-powered mental health companion accessible via smartphones, smart speakers, and smartwatches. Harnessing the capabilities of natural language processing (NLP), it actively engages in conversations, extends emotional support, imparts coping strategies, and discerns patterns suggestive of declining mental well-being.

  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
    
Zenora aims to address the pressing issue of limited accessibility to mental health support, tackling challenges related to stigma, resource constraints, and the difficulty in recognizing one's mental health needs. The solution endeavors to break down these barriers, offering immediate, personalized support while studying voice and text components to discern changes in human behavior for a more comprehensive and adaptive approach.
 
    
  - [How our technology solution can help](#how-our-technology-solution-can-help)

Zenora, Our AI-powered conversational agent provides 24/7 equitable access to judgment-free mental health support through personalized counseling, proactive care, and crisis intervention tailored to each user's unique needs.

  - [Our idea](#our-idea)

Zenora: Transforming Mental Health Support with AI Companion

The profound challenges associated with mental health are universal, affecting millions globally. However, barriers such as cost, stigma, and limited provider availability often impede access to timely and personalized support. This issue hits close to home for me. Having relocated to another continent just before the pandemic, I found myself navigating life's complexities alone. There were moments when I yearned for a heartfelt conversation about my mental health, yet my family was miles away. As a minority woman transitioning from archaeology to tech, I became the sole black woman in a solutions architecture team of three women and way more men, just as you guessed. This transition introduced its own set of challenges, including bouts of imposter syndrome, leaving me feeling isolated and misunderstood. These personal experiences underscore the crucial need for accessible and empathetic mental health support, particularly when traditional avenues are geographically distant or lack cultural understanding to address the nuances of an individual's journey.

Zenora emerges as a groundbreaking solution designed to bridge the gaps in mental health support. It is an AI-driven mental health companion accessible through smartphones, smart speakers, and smartwatches. Leveraging advanced natural language processing (NLP) and machine learning algorithms, Zenora offers users a discreet avenue for emotional support, crisis intervention, and ongoing care through natural dialogue.

Zenora's innovative approach involves studying both text and speech components to discern subtle changes in human behavior, identifying signs of conditions like depression, anxiety, and PTSD. This nuanced understanding enables Zenora to provide tailored and adaptive responses, fostering a sense of connection akin to confiding in a trusted friend. For individuals facing urgent situations, Zenora can promptly connect them to human counselors or emergency services.

Improvement Over Existing Solutions:

Zenora represents a leap forward in mental health support with several key advantages:

1. Multi-Platform Accessibility: Zenora is available on smartphones, smart speakers, and smartwatches, ensuring users can access support anytime, overcoming geographical and temporal constraints.

2. Proactive Monitoring: By studying both voice and text components, Zenora proactively identifies patterns indicative of deteriorating mental health, enabling early intervention and support.

3. Cultural Sensitivity: Zenora is designed to provide culturally competent responses, recognizing the importance of cultural nuances in mental health support.

4. Global Reach: In a world where mental health challenges are universal, Zenora's global reach transcends geographical boundaries, providing support to individuals in remote areas or regions with limited mental health resources.

5. Continuous Learning: Zenora's machine learning algorithms facilitate continuous learning from user interactions, adapting and evolving over time to provide increasingly effective support.

6. Privacy-Centric Design: Zenora places a high emphasis on user privacy with robust data security measures, creating an environment of trust and openness.

7. Promoting Mental Health Literacy: Beyond immediate support, Zenora serves as an educational resource, promoting mental health literacy and reducing stigma through informative interactions.

Zenora aspires to be more than a technological solution; it seeks to be a compassionate companion on the journey to emotional well-being, fostering resilience and understanding in individuals facing mental health challenges. Our goal is to create a world where AI companions support mental well-being for all, breaking down barriers and fostering an environment of inclusivity and understanding.


- [Technology implementation](#technology-implementation)
  - [IBM AI service(s) used](#ibm-ai-services-used)
  - [Other IBM technology used](#other-ibm-technology-used)
  - [Solution architecture](#solution-architecture)
- [Presentation materials](#presentation-materials)
  - [Solution demo video](#solution-demo-video)
  - [Project development roadmap](#project-development-roadmap)
- [Additional details](#additional-details)
  - [How to run the project](#how-to-run-the-project)
  - [Live demo](#live-demo)
- [About this template](#about-this-template)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

_INSTRUCTIONS: Complete all required deliverable sections below._

## Project summary

### The issue we are hoping to solve

REPLACE THIS SENTENCE with a short description, 2-3 sentences in length, of the specific sustainability problem your solution is meant to address.

### How our technology solution can help

REPLACE THIS SENTENCE with a short description of your team's solution, in about 10 words.

### Our idea

INSTRUCTIONS: Replace this paragraph with a longer description of your solution. In about 500 words, describe your solution in more detail. Include the real-world problem you identified, describe the technological solution you have created, and explain how it’s an improvement over existing solutions. You can supply additional documentation in this source code repository that you link to as well.

More detail is available in our [description document](./docs/DESCRIPTION.md).

## Technology implementation

### IBM AI service(s) used

_INSTRUCTIONS: Included here is a list of commonly used IBM AI services. Remove any services you did not use, or add others from the linked catalog not already listed here. Leave only those included in your solution code. Provide details on where and how you used each IBM AI service to help judges review your implementation. Remove these instructions._

- [IBM Natural Language Understanding](https://cloud.ibm.com/catalog/services/natural-language-understanding) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Assistant](https://cloud.ibm.com/catalog/services/watson-assistant) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Discovery](https://cloud.ibm.com/catalog/services/watson-discovery) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Speech to Text](https://cloud.ibm.com/catalog/services/speech-to-text) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Text to Speech](https://cloud.ibm.com/catalog/services/text-to-speech) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- List any additional [IBM AI services](https://cloud.ibm.com/catalog?category=ai#services) used or remove this line

### Other IBM technology used

INSTRUCTIONS: List any other IBM technology used in your solution and describe how each component was used. If you can provide links to/details on exactly where these were used in your code, that would help the judges review your submission.

### Solution architecture

Diagram and step-by-step description of the flow of our solution:

![Video transcription/translaftion app](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png)

1. The user navigates to the site and uploads a video file.
2. Watson Speech to Text processes the audio and extracts the text.
3. Watson Translation (optionally) can translate the text to the desired language.
4. The app stores the translated text as a document within Object Storage.

## Presentation materials

_INSTRUCTIONS: The following deliverables should be officially posted to your My Team > Submissions section of the [Call for Code Global Challenge resources site](https://cfc-prod.skillsnetwork.site/), but you can also include them here for completeness. Replace the examples seen here with your own deliverable links._

### Solution demo video

[![Watch the video](https://raw.githubusercontent.com/Liquid-Prep/Liquid-Prep/main/images/readme/IBM-interview-video-image.png)](https://youtu.be/vOgCOoy_Bx0)

### Project development roadmap

The project currently does the following things.

- Feature 1
- Feature 2
- Feature 3

In the future we plan to...

See below for our proposed schedule on next steps after Call for Code 2023 submission.

![Roadmap](./images/roadmap.jpg)

## Additional details

_INSTRUCTIONS: The following deliverables are suggested, but **optional**. Additional details like this can help the judges better review your solution. Remove any sections you are not using._

### How to run the project

INSTRUCTIONS: In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

### Live demo

You can find a running system to test at...

See our [description document](./docs/DESCRIPTION.md) for log in credentials.

---

_INSTRUCTIONS: You can remove the below section from your specific project README._

## About this template

### Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

### Authors

<a href="https://github.com/Call-for-Code/Project-Sample/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=Call-for-Code/Project-Sample" />
</a>

- **Billie Thompson** - _Initial work_ - [PurpleBooth](https://github.com/PurpleBooth)

### License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).
