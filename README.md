# EmoAdGen
EmoAdGen is an innovative tool designed for marketers, advertisers, and business owners who seek to create emotionally resonant advertising content with ease and precision. This tool harnesses the power of advanced language models, leveraging AWS Bedrock and open-source LLMs, to generate impactful ad texts that align with specific emotions selected by the user.

Key Features:

1. **Emotion-Driven Customization:** Users can select an emotion from a comprehensive dropdown menu, ensuring that the ad text resonates with the desired emotional appeal.

2. **Flexible Input Options:** EmoAdGen accommodates diverse product descriptions, allowing users to input information either through text or by uploading an image.

3. **User-Friendly Interface:** Designed with simplicity in mind, the tool offers a straightforward and intuitive UI, making it accessible for users with varying levels of technical expertise.

4. **Interactive Feedback System:** Users can rate and provide feedback on the generated ad texts, contributing to the continuous learning and improvement of the tool.

5. **Real-Time Previews and Examples:** The tool provides previews of how ad texts might look in real-world contexts and showcases examples from various emotions and products for user reference.

6. **Collaborative Features:** EmoAdGen supports collaborative efforts, allowing teams to jointly work on and review ad campaigns.

7. **Market Trend Analysis:** The tool integrates AI-driven analysis to suggest the most effective emotional approaches based on current market trends.

8. **Direct Publishing Integration:** Users can directly publish their ads to various marketing and social media platforms, streamlining the ad creation and deployment process.

EmoAdGen aims to revolutionize the way advertising content is created, making it more targeted, emotionally engaging, and effective in capturing consumer attention.

## Use cases

As an **engineer**, I want to:

1. See an LLM generate impactful ad text based on an emotion (from a dropdown and product description (either as text or image) provided as inputs.
2. Have a lightweight UI where users can choose an emotion from a dropdown menu and input a product description as an option to upload an image or text box
3. Have robust sandbox environment packaged as a self-hosted app
4. Use AWS Bedrock to make chained calls to open-source LLMs.
5. Implement a feedback mechanism where users can rate the generated ad text for continuous learning and improvement of the model.
6. Ensure compatibility with different file formats for image uploads and efficient text extraction from images.
7. Integrate analytics to track user engagement and preferences for different emotions and product types.
8. Implement storage for LLM outputs to identify edges cases the model did not do well on to test for.
9. Explore the use of AWS's scalability features to handle high volumes of requests efficiently.
10. Make sure an LLM can access external APIs such as company product catalogue (product descriptions and product images) to generate ad copies without having to copy paste product descriptions.
11. Build guardrails into the LLM to avoid prompt injections and stop inappopriate input product images and descriptions before text generation.

As a **user**, I want to:

1. Select an emotion from a dropdown menu and input my product description, either by uploading an image or entering text, to create a custom ad.
2. Receive a generated ad text that effectively conveys the chosen emotion and accurately represents the product.
3. Have the option to modify or suggest changes to the generated ad text for better alignment with my expectations or brand tone.
4. View examples of previously generated ads for different emotions and products to understand the capabilities and limitations of the system.
5. Add user demographics as a separate input to improve the relevance and impact of generated ad texts
6. Access this service through a user-friendly interface that requires minimal technical knowledge.
7. Incorporate AI-driven market trend analysis to suggest the most effective emotions and ad styles based on current consumer behavior.
8. Include a feature that allows users to see how varying emotions affect the same product description in the generated ad text.
9. Provide a glossary or help section explaining different emotions and their typical impact in advertising to guide users in their selection.
10. Be able to input customisation options such as language, tone, and style to cater to diverse user needs and preferences.
11. Have a preview feature that shows how the ad text would look in a real-world context, like on a website or social media post.
12. Provide integration capabilities with popular marketing and social media platforms for direct publishing of ads.
