# Summer-Training-TRCS102
# TRCS102-Daily-Diary
# Day 1 – Introduction to AI Agents and Lovable AI

**Date:** 22-06-2026

Today marked the beginning of my training in Automation and Agentic AI. The session focused on understanding the concept of AI agents and how they differ from traditional AI models. I learned that AI agents are intelligent systems capable of receiving user input, making decisions, using external tools, and completing tasks with minimal human intervention. Unlike simple chatbots, AI agents can perform multi-step reasoning, access APIs, interact with databases, and automate complex workflows.

I was also introduced to **Lovable AI**, a platform that enables users to build AI-powered web applications using natural language prompts. Instead of writing the entire application manually, developers can describe their requirements, and the platform generates a functional web application. During the session, I explored the interface, learned how prompts influence the generated application, and understood the importance of writing clear and detailed instructions.

Overall, today's session provided a strong foundation in Agentic AI and demonstrated how modern AI development is becoming faster and more accessible through low-code and no-code platforms. This knowledge will be valuable for building intelligent applications throughout the training program.

# Day 2 – Building Web Applications with Lovable AI and Replit

**Date:** 23-06-2026

Today's training focused on creating AI-powered web applications using Lovable AI and Replit. I learned how Lovable AI can rapidly generate complete web applications from detailed prompts, making the development process much faster than traditional coding. The session emphasized writing structured prompts that clearly describe the application's features, layout, and functionality to achieve better results.

I was also introduced to Replit, a cloud-based integrated development environment that allows developers to write, edit, and deploy code directly from a web browser. I explored how Replit can be used to modify AI-generated projects, test code, debug applications, and collaborate with others without installing software locally.

During the practical session, I examined different web applications created using these platforms and understood how AI assists in frontend development, backend integration, and user interface design. I also learned the importance of testing generated applications and refining prompts to improve the quality of the output.

By the end of the day, I gained practical knowledge of AI-assisted web development and understood how platforms like Lovable AI and Replit can significantly increase productivity while reducing development time.

# Day 3 – Introduction to n8n, Webhooks, and Workflow Nodes

**Date:** 24-06-2026

Today's session introduced me to n8n, an open-source workflow automation platform used to connect different applications and automate repetitive tasks. I learned that n8n uses a node-based workflow system where each node performs a specific action, such as receiving data, processing information, making API requests, or sending responses.

One of the most important topics covered was the concept of webhooks. I learned that a webhook acts as an endpoint that receives data automatically whenever a specific event occurs. Unlike traditional APIs that require continuous polling, webhooks provide real-time communication between applications, making automation faster and more efficient.

The session also covered several commonly used nodes in n8n, including Trigger nodes, Set nodes, HTTP Request nodes, Edit Fields nodes, and Respond to Webhook nodes. I understood how data flows from one node to another and how workflows are executed step by step.

This session established a strong understanding of workflow automation and prepared me for building real-world automation projects using n8n in the upcoming training sessions.

# Day 4 – Student Registration Workflow in n8n

**Date:** 25-06-2026

Today, I built my first complete automation workflow in n8n by creating a Student Registration system. The objective was to automate the process of collecting student information through a web form and processing the submitted data within an automated workflow.

The workflow started with a Webhook Trigger node, which received the form submission. The incoming data was then processed using different nodes to organize and validate the information before storing or displaying it. Throughout the implementation, I learned how data moves between nodes, how JSON data is structured, and how each node contributes to the overall workflow.

While building the project, I also encountered minor issues related to data mapping and webhook execution. By testing each node individually and examining the execution logs, I was able to identify and resolve these problems. This practical exercise improved my debugging skills and helped me understand the importance of testing workflows during development.

Completing this project strengthened my understanding of workflow automation and gave me confidence in building more advanced applications using n8n.

# Day 5 – AI Travel Planner and AI Shopping Tracker Workflows

**Date:** 26-06-2026

Today's training focused on developing two practical AI-powered automation projects using n8n: an AI Travel Planner and an AI Shopping Tracker. These projects demonstrated how AI models can be integrated into workflows to generate intelligent responses based on user input.

For the AI Travel Planner, I learned how user preferences such as destination, budget, travel duration, and interests can be processed to generate personalized travel recommendations. The workflow collected user information, sent it to an AI model, and returned a customized travel plan.

The AI Shopping Tracker workflow introduced me to collecting shopping requirements such as product category, budget, and preferred features. AI was then used to analyze the request and provide useful product suggestions and recommendations.

These projects helped me understand prompt engineering, API integration, structured JSON responses, and AI-assisted decision-making. They also demonstrated how workflow automation can simplify everyday tasks while delivering personalized user experiences. Overall, today's session expanded my knowledge of integrating large language models into practical automation workflows.

# Day 6 – Building an AI Tutor Workflow

**Date:** 29-06-2026

Today's task was to design and build an AI Tutor workflow using n8n. The primary objective was to create an intelligent assistant capable of helping students understand various academic topics by generating explanations, answering questions, and supporting the learning process.

The workflow accepted a user's query through a form or webhook and forwarded it to an AI language model. The generated response was then returned to the user in a clear and organized format. During development, I focused on creating prompts that encouraged the AI to provide detailed yet easy-to-understand explanations.

I also learned the importance of structuring workflows so that user input is validated before being processed. Testing different questions helped me evaluate the quality of the AI's responses and understand how prompt wording affects the generated output.

This project demonstrated how AI can be applied in education to create personalized learning experiences. It also strengthened my understanding of workflow design, prompt engineering, and AI integration within automation platforms like n8n.

# Day 7 – IF, Merge, and Code Nodes with AI Customer Support and AI Fitness Coach

**Date:** 30-06-2026

Today's session introduced three important n8n nodes: the IF node, Merge node, and Code node. I learned that the IF node is used to create conditional logic by directing workflows based on whether a condition evaluates to true or false. The Merge node combines data from multiple workflow branches, while the Code node enables custom JavaScript programming for advanced data processing and workflow customization.

To apply these concepts, I built two AI-powered workflows. The first was an AI Customer Support assistant that responded to customer queries by analyzing user input and generating appropriate answers using an AI model. The second project was an AI Fitness Coach that provided workout suggestions and health recommendations based on user preferences and fitness goals.

These projects demonstrated how conditional logic and custom code can make workflows more intelligent and dynamic. By combining AI with automation, I gained practical experience in developing real-world solutions capable of handling different user scenarios efficiently.

# Day 8 – Switch Node, Number Guessing Game, and AI Expense Tracker

**Date:** 01-07-2026

Today's training focused on learning the Switch node in n8n and implementing it through practical automation projects. I learned that the Switch node allows workflows to follow different execution paths based on multiple conditions, making it more flexible than simple conditional branching.

To practice this concept, I created a Number Guessing Game workflow. The workflow compared the user's input with predefined conditions and generated different responses depending on whether the guessed number was correct, too high, or too low. This exercise helped me understand conditional routing and decision-making within automated workflows.

I also built an AI Expense Tracker that accepts expense details from users and uses AI to categorize transactions, summarize spending, and organize financial information. During development, I worked with AI prompts, JSON formatting, and workflow debugging. I also encountered temporary API availability issues, which highlighted the importance of implementing retries and testing automation workflows thoroughly.

Today's session strengthened my understanding of advanced workflow logic while demonstrating how AI and automation can be combined to build useful real-world applications.

# Day 9 – Scheduler Trigger, Gmail Integration, and AI News Report

**Date:** 02-07-2026

Today's training focused on automating scheduled tasks using the **Scheduler Trigger** node in n8n and integrating **Gmail** into workflows. I learned that the Scheduler Trigger allows workflows to execute automatically at predefined intervals, such as every hour, daily, weekly, or at a specific date and time. This feature is extremely useful for creating automated systems that run without manual intervention.

I also explored Gmail integration in n8n, which enables workflows to send emails automatically. I learned how to configure Gmail authentication, compose email messages, and deliver notifications or reports directly to recipients through automated workflows.

To apply these concepts, I built an **AI News Report** workflow. The workflow was designed to run on a schedule, collect the latest news from a news source, summarize the articles using an AI model, and send the summarized report via Gmail. This project demonstrated how multiple services can be connected to create a fully automated information delivery system.

By the end of the session, I gained practical experience in scheduling workflows, integrating email services, and combining AI with automation to generate and distribute useful daily reports without requiring any manual effort.

# Day 10 – AI Weather Update, AI Job Finder, and YouTube Video Summarizer

**Date:** 03-07-2026

Today's training focused on developing three practical AI-powered workflows using n8n: **AI Weather Update**, **AI Job Finder**, and **YouTube Video Summarizer**. Each project demonstrated how AI and automation can work together to solve different real-world problems efficiently.

The AI Weather Update workflow was designed to retrieve current weather information for a specified location and present it in a clear, user-friendly format. Through this project, I learned how external APIs can be integrated into workflows to provide real-time information and how AI can improve the readability of the results.

The AI Job Finder workflow accepted user preferences such as job role, skills, or location and processed the information to help identify relevant job opportunities. This project emphasized collecting user input, handling structured data, and generating meaningful responses.

The final project was a YouTube Video Summarizer, which accepted a YouTube video link, extracted the video's transcript, and used an AI model to generate a concise summary highlighting the main ideas and important points. This workflow demonstrated how AI can save time by converting lengthy video content into easy-to-read summaries.

Overall, today's session strengthened my understanding of API integration, AI-powered content processing, workflow design, and the practical application of automation in everyday tasks. These projects further enhanced my confidence in building intelligent, user-focused automation solutions using n8n.
