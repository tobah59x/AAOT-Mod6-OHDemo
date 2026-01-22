# AAOT-Mod6-OHDemo

## n8n Brittle and Robust AI Agent Workflows
AI agent workflows created using n8n to highlight the difference between pilot and productions projects. The former usually succeed with clean data in a controlled environment, but fail when given messy data or in deployment. The 'brittle' agent represents the pilot project and the 'robust' agent represents a production/deployable project.

The key idea is the decoupling of design requirements. The pilot project is expected to both be a client interface and a data analyst, and so is friendly, but fails with messy data. The production project has a focus on data analysis, and so can handle the messy data without failing.

Even though the demo workflows contain JSON, this idea doesn't require coding skills. Precision in agent prompts leads to higher accuracy of results. So identifying the tasks required of the agent, and implementing them as different steps of a chain, or even as multiple agents, should lead to better results.

### Installation and Running
These workflows were run under Linux, using a local installation of n8n, in a Docker container. Docker - or an equivalent - are optional. The local installation of n8n allows unlimited use. Ollama was also installed, and n8n was started up with host networking so it could interact with Ollama from inside the Docker container.

### Notes
The JSON files have the messy data already uploaded into the relevant nodes for both workflows. To run them with clean data, copy it from the CleanData.txt file, and paste it over the messy data in the field within the appropriate node.

Feel free to contact me if you have questions or comments.