# OTTO - AWS User Group Vienna Taxonomy

## Overview

### Repository

This repository is part of the **InstructLab Taxonomy**, specifically focusing on the **AWS User Group Vienna**. The taxonomy provides structured Q&A pairs and context for AI models to generate meaningful responses about the AWS User Group Vienna, its events, sponsorships, and community engagement.

### Dataset

This dataset is structured to facilitate **synthetic data generation** and **fine-tuning** of models using the InstructLab framework.

## What is InstructLab Taxonomy?

InstructLab Taxonomy is a structured approach for organizing **Knowledge and Skills** for AI training. This allows AI models to generate better responses based on domain-specific datasets.

### Key Concepts:
- **Knowledge**: Structured facts about a specific topic.
- **Skills**: Capabilities or tasks an AI can perform.

## Data Structure

The taxonomy follows a structured format with **seed examples** that provide a context along with multiple **Q&A pairs**. The dataset is stored in YAML files (`qna.yaml`).

### Example Data Format
```yaml
version: 3
created_by: your_github_username
domain: aws_user_groups
seed_examples:
  - context: |
      Overview of the AWS User Group Vienna:
      The AWS User Group Vienna is a community of AWS enthusiasts and professionals in Austria.
      They come together monthly to learn, share knowledge, and network around AWS topics.
    questions_and_answers:
      - question: "What is the AWS User Group Vienna?"
        answer: "The AWS User Group Vienna is a monthly meetup in Vienna for anyone interested in learning and sharing knowledge about AWS."
      - question: "Who can attend AWS User Group Vienna meetups?"
        answer: "All AWS enthusiasts—beginners, experts, or anyone curious about AWS—are welcome at the AWS User Group Vienna events."
```

## Knowledge Directory Overview

The `knowledge/aws_community_information` directory contains structured content and Q&A pairs related to the AWS community ecosystem. Below is a summary of the files and folders within this directory:

### Files and Folders:
- **global_aws_community/**
  - `global_aws_community.md`: Overview of the global AWS community ecosystem.
  - `qna.yaml`: Q&A pairs about the global AWS community.

- **aws-community-programs/**
  - `aws_heroes.md`: Details about the AWS Heroes program.
  - `aws_community_builders.md`: Information on the AWS Community Builders program.
  - `aws_cloud_clubs.md`: Overview of AWS Cloud Clubs for students.
  - `qna.yaml`: Q&A pairs about AWS community programs.

- **user-groups/**
  - `aws_user_groups_overview.md`: Insights into the role of AWS User Groups globally.
  - `aws_user_groups_austria/`: Subdirectory for AWS User Groups in Austria.
    - `aws_ug_linz.md`: Information about the AWS User Group in Linz.
    - `aws_wug_vienna.md`: Details about the AWS Women’s User Group in Vienna.
    - `aws_ug_vienna.md`: Overview of the AWS User Group in Vienna.
    - `qna.yaml`: Q&A pairs about AWS User Groups in Austria.
  - `qna.yaml`: Q&A pairs about AWS User Groups globally.

- **personas/**
  - `ug_leader.md`: Persona description for a User Group Leader.
  - `ug_speaker.md`: Persona description for an Event Speaker.
  - `ug_first_timer.md`: Persona description for a First-time Attendee.
  - `ug_host.md`: Persona description for an Event Host or Sponsor.
  - `qna.yaml`: Q&A pairs about the different personas.

- **meetup-formats/**
  - `meetup_formats.md`: Details about meetup event formats and workflows.
  - `qna.yaml`: Q&A pairs about event formats and planning workflows.

- **logistics/**
  - `scheduling_logistics.md`: Information on scheduling logistics and agenda design.
  - `qna.yaml`: Q&A pairs about scheduling, timing, and logistics.

This directory provides a comprehensive taxonomy for understanding and engaging with the AWS community ecosystem.
