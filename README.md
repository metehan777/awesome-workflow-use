# Awesome Workflow Use

<p align="center">
  <img alt="Workflow Use logo - a product by Browser Use." src="https://raw.githubusercontent.com/browser-use/workflow-use/main/static/workflow-use.png" width="200">
</p>

<h1 align="center">A Collection of Community Workflows for <a href="https://github.com/browser-use/workflow-use">Workflow Use</a></h1>

[![GitHub stars](https://img.shields.io/github/stars/browser-use/workflow-use?style=social)](https://github.com/browser-use/workflow-use/stargazers)
[![Discord](https://img.shields.io/discord/1303749220842340412?color=7289DA&label=Discord&logo=discord&logoColor=white)](https://link.browser-use.com/discord)
[![Cloud](https://img.shields.io/badge/Cloud-☁️-blue)](https://cloud.browser-use.com)
[![Twitter Follow Gregor](https://img.shields.io/twitter/follow/Gregor?style=social)](https://x.com/gregpr07)
[![Twitter Follow Magnus](https://img.shields.io/twitter/follow/Magnus?style=social)](https://x.com/mamagnus00)

Welcome to **Awesome Workflow Use**! This repository is a community-curated collection of workflow examples and ideas designed to be built and executed with the [**Workflow Use**](https://github.com/browser-use/workflow-use) tool.

[**Workflow Use**](https://github.com/browser-use/workflow-use) is the easiest way to create and execute deterministic browser workflows with variables, which can intelligently fallback to [Browser Use](https://github.com/browser-use/browser-use) (an AI agent) if a step fails. You just _show_ the recorder the workflow, and it automatically generates the underlying automation.

## What's Inside This Repository?

This repository aims to provide a diverse set of conceptual workflows that you can bring to life using the `workflow-use` tool. Instead of fully fleshed-out JSON files (which are best created by recording your specific instance of a website), you'll find a collection of ideas detailing:

* **Name:** A descriptive name for the workflow.
* **Description:** What the workflow aims to achieve.
* **Target Website Category:** The type of websites it applies to (e.g., Social Media, E-commerce).
* **Target Website Examples:** Specific popular websites where this workflow could be used.
* **Core Idea:** The main goal of the automation.
* **Potential Inputs:** What dynamic information the workflow would likely need.
* **Conceptual Steps:** A high-level overview of the actions involved.

You can find these conceptual workflows in the `workflow_ideas.json` file in this repository.

## Example Conceptual Workflow Structure

Here's a snippet of how a workflow idea is structured in `workflow_ideas.json`:

```json
{
  "name": "Social Media Cross-Platform Post",
  "description": "Post the same update to multiple social media platforms.",
  "target_website_category": "Social Media",
  "target_websites_examples": ["Twitter", "Facebook", "LinkedIn"],
  "core_idea": "Share content across multiple social networks simultaneously.",
  "potential_inputs": ["post_content (string, required)", "image_url (string, optional)"],
  "conceptual_steps": [
    "Login to Platform 1",
    "Compose post with {post_content} and optional {image_url}",
    "Publish post on Platform 1",
    "Login to Platform 2",
    // ... and so on
  ]
}
