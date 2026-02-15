# GitHub Labels Setup Guide

This document explains how to set up the required labels for the CZI-Central repository.

## Required Labels

The following labels should be created in the GitHub repository settings:

| Label Name | Color Code | Description |
|------------|------------|-------------|
| design | `#FF0000` (Red) | Design-related tasks and concepts |
| production | `#0000FF` (Blue) | Production, manufacturing, and supplier tasks |
| marketing | `#FFD700` (Gold) | Marketing campaigns and promotional activities |
| web | `#28a745` (Green) | Website updates and online presence |
| urgent | `#FFA500` (Orange) | Time-sensitive tasks requiring immediate attention |
| idea | `#800080` (Purple) | New ideas and concepts for consideration |

## How to Create Labels

1. Navigate to the repository on GitHub
2. Click on the "Issues" tab
3. Click on "Labels" button
4. Click "New label" for each label
5. Enter the label name, description, and color code
6. Click "Create label"

## Alternative: Using GitHub CLI

If you have GitHub CLI installed, you can create all labels with these commands:

```bash
gh label create "design" --color "FF0000" --description "Design-related tasks and concepts"
gh label create "production" --color "0000FF" --description "Production, manufacturing, and supplier tasks"
gh label create "marketing" --color "FFD700" --description "Marketing campaigns and promotional activities"
gh label create "web" --color "28a745" --description "Website updates and online presence"
gh label create "urgent" --color "FFA500" --description "Time-sensitive tasks requiring immediate attention"
gh label create "idea" --color "800080" --description "New ideas and concepts for consideration"
```

## Label Usage

Refer to the main README.md for guidance on how to use these labels effectively in your workflow.
