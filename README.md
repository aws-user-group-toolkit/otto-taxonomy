---
markmap:
  colorFreezeLevel: 5
---

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



-----



---
markmap:
  colorFreezeLevel: 5
---

# AWS Community Taxonomy (aws_community_taxonomy.md)

## **1. AWS Community Ecosystem (aws_community_ecosystem.md)**
- *Understanding the structure and purpose of AWS Communities*
- **AWS Community Overview (aws_community_overview.md)**
- **AWS Community Purpose & Impact (aws_community_purpose.md)**
- **AWS Community Governance (aws_community_governance.md)**
- **AWS Open Source & Collaboration (aws_community_open_source.md)**

---

## **2. AWS User Groups (aws_community_user_groups.md)**

### **2.1 General AWS User Groups (aws_general_ugs.md)**
- *Regional organized groups fostering AWS knowledge-sharing and collaboration with mixed guests and no special topic focus*
- **[AWS User Group Vienna](https://www.meetup.com/amazon-web-services-aws-vienna/)** (`aws_ug_vienna.md`) - *open to join for everyone in Vienna, Austria*
- **[AWS User Group Linz](https://www.meetup.com/aws-user-group-linz/)** (`aws_ug_linz.md`) - *open to join for everyone in Linz, Austria*
- **[AWS User Group Kosice]()** (`aws_ug_kosice.md`) - *open to join for everyone in Kosice, Slovakia*
- **[AWS User Group Basilicata]()** (`aws_ug_basilicata.md`) - *open to join for everyone in Kosice, Slovakia*
- AWS User Group Munich
- AWS User Group Berlin
- ...

### **2.2 Special Focus AWS User Groups (aws_community_special_focus_ugs.md)**
#### *Special Groups focusing on specific technlogies or target groups*
#### **2.2.1 AWS Women’s User Groups** (`aws_womens_ugs.md`)
- *Focus on empowering Women in Cloud*
- **[AWS Women's User Group Vienna](https://www.meetup.com/aws-womens-user-group-vienna/)** (`aws_community_wug_vienna.md`) - *women and allies in Vienna, Germany*
- **[AWS Women's User Group Berlin](https://www.meetup.com/berlin-amazon-web-services-meetup-group/)** (`aws_community_wug_berlin.md`)
- **[AWS Women's User Group Munich](https://www.meetup.com/de-DE/aws-womens-user-group-munich/)**
- ...

#### **2.2.2 AWS Technology-Focused User Groups** (`aws_community_tech_ugs.md`)
- **[AWS User Group Budapest - Containers & AI/ML](https://www.meetup.com/aws-ug-containers/)** 

#### **2.2.3 AWS Industry-Specific Communities (aws_community_industry_ugs.md)**
- **AWS for Startups Community** (`aws_community_ug_startups.md`)
- AWS for Enterprise Community
- AWS for Public Sector Community
- ...
---

## **3. AWS Community Leadership & Engagement (aws_community_leadership.md)**
- *Leadership programs, volunteerism, and mentorship initiatives.*
- **AWS User Group Leader Program** (`aws_ug_leaders.md`)
- **AWS Heroes Program** (`aws_heroes.md`)
- **AWS Community Builders Program** (`aws_community_builders.md`)
- **AWS Cloud Club Captains** (`aws_cloud_clubs.md`)


---

## **4. AWS Community Events (aws_community_events.md)**
### *AWS community-led events, conferences, and networking opportunities.*

### **4.1 AWS Meetups & Local Events** (`aws_community_meetups.md`)
- **AWS User Group Meetups** (`aws_community_meetup_ugs.md`)
- **AWS Stammtisch** (`aws_community_meetup_stammtisch.md`)
- **AWS Hands-on Workshops** (`aws_community_meetup_workshops.md`)
- **AWS GameDays** (`aws_community_meetup_gamedays.md`)

### **4.2 AWS Community Days** (`aws_community_days.md`)
- **[AWS Community Day DACH](https://aws-community-day.de/)** (aws_community_day_dach.md)
- **[AWS Community Day CEE](https://awscommunity.eu/)** (aws_community_day_cee.md)
- **AWS Community Day Milano** (`aws_community_day_milano.md`)
- **AWS Community Day Romania** (`aws_community_day_romania.md`)
- **AWS Community Day Kosice** (`aws_community_day_kosice.md`)
- **AWS Community Day Prague** (`aws_community_day_prague.md`)

### **4.3 AWS Community Presence at AWS Global Events** (`aws_community_global_events.md`)
- **AWS Summit Community Stages** (`aws_community_summit_stages.md`)
  - **AWS Summit Hamburg Community Stage** *(organized by Förderverein AWS Community DACH)* (aws_community_stage_hamburg.md)
- **AWS re:Invent Community Tracks** (`aws_community_reinvent_tracks.md`)

### **4.4 AWS re:Invent Community-Led Events (aws_community_reinvent.md)**
- **AWS re:Invent Community Hike** (`aws_community_reinvent_hike.md`)
- **Women of Cloud Lunch** (`aws_community_reinvent_women_lunch.md`)
- **Women of Cloud Bus Trip** (`aws_community_reinvent_women_bus.md`)
- **Women Empowerment Sessions** (`aws_community_reinvent_women_empower.md`)

---

## **5. AWS Community Event Organization **(`aws_community_event_org.md`)
### *Guidelines for planning AWS meetups, Community Days, and securing sponsorships.*

### **5.1 Meetup Planning **(`aws_community_event_meetups.md`)
- **Meetup Scheduling & Venue **(`aws_community_meetup_scheduling.md`)
- **Meetup Agenda & Speaker Selection **(`aws_community_meetup_agenda.md`)
- **Catering & Refreshments** (`aws_community_meetup_catering.md`)

### **5.2 Large-Scale Event Planning** (`aws_community_event_large.md`)
- **AWS Community Day Planning** (`aws_community_event_cd_planning.md`)
- **AWS Summit Community Stage Planning** (`aws_community_event_summit_planning.md`)
- **AWS re:Invent Community Events Planning** (`aws_community_event_reinvent_planning.md`)

### **5.3 Sponsorship & Funding** (`aws_community_event_sponsorship.md`)
- **Sponsorship Opportunities** (`aws_community_event_sponsorship_types.md`)
- **Sponsorship Guidelines & Benefits** (`aws_community_event_sponsorship_guidelines.md`)

---
