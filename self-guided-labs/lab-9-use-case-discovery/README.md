# Lab 7: Use Case Discovery

Welcome to Lab 7: Use Case Discovery! In this lab, you'll apply everything you've learned throughout the workshop to define and implement a real-world AI solution.

### Objectives

In this lab, your task is to:

1. **Discover and define a use case** that could benefit from AI, utilizing the knowledge gained in previous labs.
2. **Design a solution architecture** that combines the following key components:
    - **Prompt Engineering** using the **Prompt Lab**.
    - **Retrieval-Augmented Generation (RAG)** - chat with a vector store.
    - **AutoRAG** to automatically optimise your RAG pipeline and find the best parameters.
3. Build an **MVP solution** for the defined use case.
4. **Evaluate** your solution to assess its effectiveness.
5. **Present** your solution to the group in a *"show and tell"* format, showcasing how each of the AI tools and techniques were used to create the solution.

#### Step 1: Discover a Use Case

The first step is to discover a use case. Your goal is to identify a relevant problem in your industry or field of work that could be solved with AI, using the various techniques you've learned:
- **Prompt Engineering**: What problem requires a custom model prompt to solve? What prompt engineering techniques would be required?
- **RAG**: What is a scenario where combining retrieved information with generative capabilities could be beneficial?
- **AutoRAG**: How can automated optimisation help improve your solution?

#### Example Ideas!
1. **Oil reservoir analysis**: Use AI to summarise and analyse historical data from oil reservoirs, including geological, geophysical, and production data, to help the engineers understand the data better.

2. **Seismic data insights**: Use an Image model to analyse seismic data and identify potential drilling sites.

3. **Drilling insights**: Use AI to analyse real-time drilling data to suggest adjustments to drilling parameters.

4. **Energy consumption insights**: Build a solution to summarise energy consumption patterns across operations (drilling, production, refining). And identify inefficiencies and recommend energy-saving strategies.

#### Step 2: Define the Solution Architecture

Once you’ve identified the use case, the next step is to **define the solution architecture.**

- **Data Sources**: Where will the data come from? (documents, images, database, etc.)
- **Prompt Engineering**: What specific prompts will be required for the generative model to work effectively? Freeform, structured, multi-shot strategy?
- **RAG Implementation**: How will you augment the generation with relevant data from your sources? Define the retrieval process and integrate it with generative models.
- **AutoRAG Optimisation**: How can you use AutoRAG to optimise your solution and automatically adjust parameters for better performance?

> You can visualise your architecture using tools like diagrams.net (formerly draw.io), or simply describe it in textual format. Ensure to identify each module's role in the solution.

#### Step 3: Build the MVP

Now that you’ve defined your use case and architecture, it's time to build your Minimum Viable Product (MVP).

- **Configure Prompt Lab**: Implement the necessary prompts for your use case.
- **Implement RAG**: Set up your Elasticsearch index and use it in combination with the foundation models to enhance the AI’s response.
- **Use AutoRAG**: Leverage AutoAI's RAG optimisation to ensure you're using the best combination of model and pipeline configurations.
- **Evaluate Performance**: Test the MVP to assess its performance. Check if the AI-generated outputs align with expectations and solve the problem efficiently.

#### Step 4: Show and Tell

At the end of the lab, each team will present their MVP to the group in a show and tell session.

- **Overview**: Describe your use case, solution architecture, and key components.
- **Demonstration**: Showcase your MVP in action, showing how it solves the problem effectively.
- **Challenges**: Discuss any challenges you faced and how you overcame them.
- **Future Work**: Share any ideas for expanding or improving your solution after the workshop