## FEATURE:

- Pydantic AI agent that has another Pydantic AI agent as a tool.
- Research Agent for the primary agent and then an email draft Agent for the subagent.
- CLI to interact with the agent.
- Gmail for the email draft agent, Brave API for the research agent.

## EXAMPLES:

In the `examples/` folder, there is a README for you to read to understand what the example is all about and also how to structure your own README when you create documentation for the above feature.
Use the folowing .md to guide you through setting this up.
<project.directory>`/README.md`


- <project.directory>`/examples/cli.py` - use this as a template to create the CLI
- <project.directory>/`examples/agent/` - read through all of the files here to understand best practices for creating Pydantic AI agents that support different providers and LLMs, handling agent dependencies, and adding tools to the agent.

Don't copy any of these examples directly, it is for a different project entirely. But use this as inspiration and for best practices.

## DOCUMENTATION:

Pydantic AI documentation: https://ai.pydantic.dev/

## OTHER CONSIDERATIONS:

- Include a 
    <project.directory>/.env.example
--  <project.directory>/README.md with instructions for setup including how to configure  
- Include the project structure in the README.md
- Check for an initialized Virtual Environment
     if Virtual environment has already been set up with the necessary dependencies.
     then note the architecture of the project page and determine type of project. (python, node ,react, vite, vue ... )  
    - Use python_dotenv and load_env() for environment variables with python
- Use appropriate security for the other frameworks
