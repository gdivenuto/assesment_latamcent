# Assesment in LatamCent

The job generator form (https://latamcent.com/form-description-generator/) works well, I have completed the three steps, and it correctly generates the job text based on the requested information.
In turn, I have noticed that it allows the download of the generated text, in docx format.

Below are some suggestions to add to said form:

1. First stage: Basic job information.
- Salary or Salary range: Include an optional section to indicate a salary range, in which currency, since many candidates look for this information when evaluating job offers.
- Work schedule, which can be implemented through a drop-down list (select) or radio buttons to make a quick selection and avoid formatting errors. For example: Full time, Part time, Flexible.
- Add options for the type of contract, such as Freelance or Temporary Contract.
- Location: Specify whether the job is remote, in-person or hybrid, and add an option to show the geographic location if applicable.

2. Second stage: Requirements, Responsibilities and Benefits.
- Job Category: Add a field to select the job category (for example, "Technology", "Sales", "Administration") to facilitate sorting and searching.
- Additional Requirements: Include a section of "desirable skills" or "preferred knowledge" that are not exclusive but can be a plus for the candidate.
- Benefits Format: Instead of a simple text field, checkboxes or drop-down lists could be used with options such as "Health Insurance", "Bonuses", "Vacation Days", etc., to standardize the information.

3. Third stage: Additional Information.
- Custom Questions: Allow adding a section of custom questions to evaluate candidates on specific topics related to the position.

Regarding its format for a website:
- Tabbed or Step Form: Present the three stages as tabs or visual steps (with a "progress bar" at the top) so that the builder user knows what phase they are in.
- Real-time validations: Validate fields as the user fills in the data to avoid errors when submitting the form.
- Allow tagging created positions with keywords or categories to facilitate internal management of multiple job descriptions (e.g. "Technical Position", "Sales Position", "Administrative Position").
- Temporary saving: Enable the option to save the form at any time so that users (from companies) can return to it later.

# Demonstration of the above suggestion:
I have prepared a demo with HTML and CSS of how the three steps of the form could look.

Notes:
In the buttons of each step/stage, I have purposely commented the HTML needed to implement with Google reCaptcha, version 3.
As it is a small demo, the files are .html instead of .php

To view the demo, you can download the repository, and from any location on your computer, leave the folder, and then access the file step_1.html via browser, from which you can view step_2.html and step_3.html, using the buttons at the bottom.

# AI Plugins in WordPress
I've seen WordPress plugins that use the OpenAI API to automatically generate content, and some of them could be perfectly suited for a company-oriented job description generator.
WP AI CoPilot: This plugin is very versatile and is designed to generate content using GPT-3/4. It offers direct integration with the WordPress editor, which would allow you to generate job descriptions based on a prompt, optimizing and customizing the content for your site. Additionally, the model parameters can be adjusted to adapt it to the needs of each company.

https://wordpress.org/plugins/ai-user-content-generator/#developers
https://wordpress.org/plugins/ai-co-pilot-for-wp/

AI Power: This is a complete package that includes tools for automatic content generation, chatbot, image creation, among other functionalities. It also uses the OpenAI API, which would allow you to generate job descriptions using custom prompts in more than 150 languages. It also offers advanced options like embeddings and SEO optimization.

https://wordpress.org/plugins/gpt3-ai-content-generator/

WP Wand: This plugin allows you to automatically generate content from the WordPress Gutenberg editor and is compatible with the OpenAI API. You could use it to generate job descriptions, and it also offers pre-designed templates to make the process easier.

https://wordpress.org/plugins/ai-content-generation/
