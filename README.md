# GPTalent Interviewer

![GPTalent Interviewer Logo](./Screenshot%202024-05-05%20at%2023.57.43.png)

## Introduction

The GPTalent Interviewer is an open-source web application designed to simplify and enhance the interview process for HR professionals and companies. By leveraging the power of OpenAI's ChatGPT and avatar technology, this application aims to reduce costs, save time, and improve the overall hiring experience.

## Why GPTalent Interviewer?

The traditional interview process often involves significant time and resources, from scheduling interviews to evaluating candidates. The GPTalent Interviewer revolutionizes this process by integrating cutting-edge technology into every step, offering several advantages:

### 1. Enhanced Efficiency

With GPTalent Interviewer, conducting interviews becomes faster and more efficient. ChatGPT's natural language processing capabilities enable seamless communication with candidates, eliminating the need for lengthy back-and-forth email exchanges or scheduling conflicts.

### 2. Cost Reduction

By leveraging AI-powered interviews, GPTalent Interviewer significantly reduces costs associated with traditional interview processes. There's no need for physical meeting spaces, travel expenses, or extensive coordination efforts. This cost-effective solution makes hiring accessible to companies of all sizes.

### 3. Time Savings

Time is a precious resource, especially in the fast-paced world of recruitment. GPTalent Interviewer streamlines the interview process, saving valuable time for both interviewers and candidates. Automated scheduling, instant communication, and efficient evaluation tools contribute to a smoother and faster hiring experience.

### 4. Improved Candidate Experience

A positive candidate experience is crucial for attracting top talent. GPTalent Interviewer enhances the candidate experience by providing a modern, user-friendly interface and personalized interactions. Candidates can showcase their skills and personality in a relaxed virtual environment, leading to better engagement and retention.

### 5. Data-Driven Insights

GPTalent Interviewer offers valuable insights into the hiring process through data analytics. Track candidate performance, analyze interview trends, and identify areas for improvement using comprehensive data reports. These insights empower recruiters to make informed decisions and optimize their hiring strategies.


# Get Started 


## Configuration Settings

Before running the application, you need to set up the following configurations:

### Azure Speech Resource

- **Description:** Azure Speech Resource is used for speech recognition capabilities within the application.
  
  - **Region:** Select the appropriate region where the Azure Speech service is deployed (e.g., West US, West Europe, Southeast Asia).
  
  - **Subscription Key:** Provide the Azure Speech subscription key.

### Azure OpenAI Resource

- **Description:** Azure OpenAI Resource is utilized for natural language processing tasks within the application.
  
  - **Endpoint:** Provide the Azure OpenAI endpoint.
  
  - **API Key:** Provide the Azure OpenAI API key.
  
  - **Deployment Name:** Specify the name of the deployment for the OpenAI model.

### Azure Cognitive Search Resource (Optional)

- **Description:** Azure Cognitive Search Resource, if needed, is used for searching functionality within the application.
  
  - **Endpoint:** Provide the Azure Cognitive Search endpoint.
  
  - **API Key:** Provide the Azure Cognitive Search API key.
  
  - **Index Name:** Specify the name of the search index.

### STT / TTS Configuration

- **Description:** STT (Speech-to-Text) / TTS (Text-to-Speech) Configuration settings determine the speech and voice interactions within the application.
  
  - **STT Locale(s):** Specify the locales for speech recognition (e.g., en-US, de-DE).
  
  - **TTS Voice:** Specify the text-to-speech voice.
  
  - **Custom Voice Deployment ID:** If applicable, provide the custom voice deployment ID.

### Avatar Configuration

- **Description:** Avatar Configuration settings define the appearance and behavior of the avatar used in the application.
  
  - **Avatar Character:** Specify the avatar character (e.g., lisa).
  
  - **Avatar Style:** Specify the avatar style (e.g., casual-sitting).
  
  - **Custom Avatar:** Check this box if using a custom avatar.

### Job Description

Before starting the session, please enter the job description in the provided text area.
## Contributing

We welcome contributions from the community to enhance the GPTalent Interviewer. To contribute, please follow these guidelines:

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenAI](https://openai.com) for providing the ChatGPT model.
- [text-to-speech-avatar]([https://github.com/alievk/avatarify](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/text-to-speech-avatar/what-is-text-to-speech-avatar)) for avatar technology inspiration.

## Contact

For questions or feedback, please contact us at [moti.malka25@gmail.com](moti.malka25@gmail.com).
