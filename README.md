# OTTO - AWS User Group Vienna Taxonomy

## Overview

This repository is part of the **InstructLab Taxonomy**, specifically focusing on the **AWS User Group Vienna**. The taxonomy provides structured Q&A pairs and context for AI models to generate meaningful responses about the AWS User Group Vienna, its events, sponsorships, and community engagement.

This dataset is structured to facilitate **synthetic data generation** and **fine-tuning** of models using the InstructLab framework.

## What is InstructLab Taxonomy?

InstructLab Taxonomy is a structured approach for organizing **Knowledge and Skills** for AI training. This allows AI models to generate better responses based on domain-specific datasets.

### Key Concepts:
- **Knowledge**: Structured facts about a specific topic.
- **Skills**: Capabilities or tasks an AI can perform.

## Data Structure

The taxonomy follows a structured format with **seed examples** that provide a context along with multiple **Q&A pairs**. The dataset is stored in a YAML file (`qna.yaml`).

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

### Key Variables:
- **`context`**: Provides background information for AI to understand the Q&A pairs.
- **`questions_and_answers`**: Contains structured Q&A pairs to train AI models.

## Use Cases
This taxonomy is used to:
- Train AI assistants to answer AWS User Group-related questions.
- Enhance chatbot responses related to AWS community events.
- Provide structured data for community-driven AI training.

## Important Links and Resources
- [InstructLab Taxonomy Repository](https://github.com/instructlab/taxonomy)
- [AWS User Group Toolkit](https://github.com/aws-user-group-toolkit)
- [InstructLab Documentation](https://docs.instructlab.ai/)

For more details, refer to the official documentation and guidelines!

