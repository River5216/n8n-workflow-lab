# n8n Workflow Lab

A personal lab for learning, building, and documenting automation workflows with n8n.

This repository records my exploration of workflow automation, local deployment, AI-assisted processing, and practical productivity systems.

---

## About This Project

`n8n-workflow-lab` is a hands-on repository for experimenting with automation workflows.

The goal is not only to learn how n8n works, but also to build reusable workflows that can support real tasks, such as form processing, information organization, content summarization, and course project management.

This repository will gradually include:

- Workflow ideas
- Startup SOPs
- n8n learning notes
- Exported workflow JSON files
- Screenshots of workflow structures
- Reflections on automation design

---

## Why n8n

n8n is a workflow automation tool that allows different services, APIs, databases, and AI tools to be connected through visual nodes.

For me, n8n is useful because it can help turn repeated manual tasks into semi-automatic or automatic workflows.

Possible use cases include:

- Collecting and organizing form responses
- Processing questionnaire data
- Summarizing long text materials
- Connecting AI tools with productivity systems
- Building lightweight personal automation tools
- Supporting course projects and research tasks

---

## Current Setup

My current local setup is based on:

- Windows
- Docker Desktop
- PowerShell
- Local n8n instance
- Browser-based workflow editing

The local n8n service is accessed through:

```text
http://localhost:5678
```

---

## Startup SOP

This is the basic process I use to start my local n8n environment.

### 1. Open Docker Desktop

Start Docker Desktop first and wait until it is fully running.

### 2. Open PowerShell

Open PowerShell on Windows.

### 3. Start the n8n Container

Run the following command:

```bash
docker start n8n
```

If the container starts successfully, n8n should become available locally.

### 4. Open n8n in Browser

Visit:

```text
http://localhost:5678
```

### 5. Start Building or Testing Workflows

After entering the n8n interface, I can continue building, editing, testing, or documenting workflows.

---

## Workflow Directions

This repository may include workflows related to the following directions:

### AI Form Analysis

Use AI to analyze form responses, extract key points, and generate structured summaries.

### Questionnaire Processing

Support questionnaire collection, cleaning, classification, and early-stage analysis.

### Content Collection and Summarization

Collect information from different sources and use AI to summarize or reorganize the content.

### Personal Knowledge Automation

Build workflows that help capture, classify, and reuse notes, ideas, and learning materials.

### Course Project Support

Use automation to reduce repetitive work in course projects, research tasks, and team collaboration.

---

## Learning Goals

Through this repository, I hope to gradually understand:

- How visual automation workflows are structured
- How different n8n nodes exchange data
- How triggers, conditions, and actions work together
- How AI tools can be integrated into workflows
- How to document workflows clearly
- How to design automation systems for real personal needs

---

## Planned Repository Structure

```text
n8n-workflow-lab/
├── workflows/
│   └── exported workflow JSON files
├── screenshots/
│   └── workflow structure screenshots
├── sop/
│   └── startup and operation guides
├── notes/
│   └── learning notes and reflections
└── README.md
```

---

## Current Status

This repository is currently in the early learning and experimentation stage.

At this stage, the focus is on:

- Setting up a stable local n8n environment
- Understanding basic workflow logic
- Testing simple automation cases
- Recording reusable SOPs
- Preparing for more complete workflow projects

More workflow examples, screenshots, and exported JSON files will be added later.

---

## Future Plans

Planned updates include:

- A complete form-analysis workflow
- A questionnaire-processing workflow
- Screenshots of workflow structures
- Exported n8n workflow files
- Notes on common node usage
- Reflections on AI + automation use cases

---

## Notes

This repository is part of my broader exploration of AI tools, automation workflows, and product-oriented building.

It is both a learning archive and a portfolio space for documenting practical automation experiments.
