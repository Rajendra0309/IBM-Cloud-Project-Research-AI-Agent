# Prompts Used in Research AI Agent

This document contains all the prompt templates and configurations used in the IBM Watsonx Research Agent.

## Core Agent Description
```
AI agent that summarizes research papers, suggests hypotheses, drafts academic content, and formats citations in APA style. Specializes in academic research assistance with real-time web search capabilities.
```

## 1. Research Summarization Prompts

### Basic Summarization
```
Summarize recent research on: {topic} in under 200 words.

Focus on:
- Key findings and discoveries
- Research methodologies used
- Practical implications
- Current trends and developments

Format the summary with clear headings and bullet points for easy reading.
```

### Detailed Literature Review
```
Conduct a comprehensive literature review on: {topic}

Include:
1. Overview of current research landscape
2. Major research themes and approaches
3. Key researchers and institutions
4. Recent breakthrough findings
5. Identified research gaps
6. Future research directions

Limit to 500 words and include at least 5 recent studies.
```

## 2. Hypothesis Generation Prompts

### Basic Hypothesis Generation
```
Based on current research gaps in {topic}, suggest 3 specific, testable research hypotheses.

For each hypothesis:
- State the hypothesis clearly
- Explain the reasoning behind it
- Identify potential research methods
- Discuss expected outcomes
- Assess feasibility and significance

Format as numbered list with detailed explanations.
```

### Advanced Research Questions
```
Generate innovative research questions for {topic} that address:
1. Unexplored areas in current literature
2. Methodological improvements needed
3. Cross-disciplinary applications
4. Real-world problem-solving opportunities

Provide 5 research questions with justification for each.
```

## 3. Academic Content Drafting Prompts

### Abstract Writing
```
Write a structured abstract for a research paper on: {topic}

Include these sections:
- Background/Purpose (2-3 sentences)
- Methods (2-3 sentences)
- Results (2-3 sentences)
- Conclusions (2-3 sentences)

Keep within 250 words and use formal academic language.
```

### Introduction Drafting
```
Draft an academic introduction for a research paper on: {topic}

Structure:
1. Broad context and importance of the topic
2. Current state of research
3. Identified gaps or problems
4. Research objectives and questions
5. Brief overview of methodology
6. Significance of the study

Target 800-1000 words with proper academic tone and transitions.
```

### Research Proposal Outline
```
Create a detailed outline for a research proposal on: {topic}

Include:
1. Title and Abstract
2. Introduction and Literature Review
3. Research Questions/Hypotheses
4. Methodology
5. Timeline and Milestones
6. Budget Considerations
7. Expected Outcomes
8. References

Provide brief descriptions for each section.
```

## 4. Citation and Reference Prompts

### APA Citation Generation
```
Generate properly formatted APA citations for recent academic papers on: {topic}

Requirements:
- Include at least 10 recent citations (last 5 years)
- Mix of journal articles, books, and conference papers
- Ensure proper APA 7th edition formatting
- Include DOIs where available
- Alphabetical order by author surname

Verify all citation elements are complete and accurate.
```

### Reference List Creation
```
Create a comprehensive reference list for {topic} research including:
- Seminal works in the field
- Recent peer-reviewed articles
- Relevant books and book chapters
- Conference proceedings
- Government reports (if applicable)

Format in APA style with at least 20 references.
```

## 5. Specialized Research Prompts

### Methodology Recommendations
```
Recommend appropriate research methodologies for studying: {topic}

Consider:
- Quantitative vs. qualitative approaches
- Data collection methods
- Sample size and selection
- Statistical analysis techniques
- Ethical considerations
- Timeline and resource requirements

Provide detailed justification for recommendations.
```

### Data Analysis Guidance
```
Provide guidance for analyzing data related to: {topic}

Include:
- Appropriate statistical tests
- Data visualization techniques
- Software recommendations
- Common pitfalls to avoid
- Interpretation guidelines
- Reporting standards

Tailor advice to the specific research context.
```

## 6. Quick Start Questions

These are pre-configured questions users can select to get started quickly:

1. "Summarize recent research on artificial intelligence in healthcare"
2. "Generate 3 research hypotheses about climate change mitigation"
3. "Draft an introduction for a paper on machine learning ethics"
4. "Create APA citations for quantum computing research papers"
5. "Suggest methodologies for studying remote work productivity"
6. "Outline a research proposal on sustainable energy solutions"
7. "Analyze current trends in educational technology research"
8. "Identify research gaps in cybersecurity studies"

## 7. Advanced Prompt Engineering Tips

### Context Setting
Always provide context about:
- Research domain/field
- Target audience (undergraduate, graduate, professional)
- Publication type (journal article, thesis, report)
- Urgency and scope requirements

### Quality Control Prompts
```
Review and improve the following research content for:
- Academic writing standards
- Logical flow and coherence
- Citation accuracy
- Grammar and style
- Clarity and conciseness

Provide specific improvement suggestions.
```

### Multi-step Research Process
```
Execute a comprehensive research workflow for {topic}:

Step 1: Literature search and initial review
Step 2: Gap analysis and research question formulation
Step 3: Methodology selection and justification
Step 4: Preliminary outline creation
Step 5: Citation compilation and verification

Complete each step before proceeding to the next.
```

---

## Usage Notes

- Replace `{topic}` with specific research topics or questions
- Adjust word limits based on specific requirements
- Combine prompts for complex research tasks
- Test and refine prompts based on output quality
- Keep prompts updated with current research standards

## Customization Guidelines

1. **Domain-Specific Adaptations**: Modify prompts for specific fields (STEM, humanities, social sciences)
2. **Audience Targeting**: Adjust complexity and detail level based on user expertise
3. **Output Format**: Specify desired formats (bullet points, paragraphs, tables)
4. **Quality Standards**: Include specific criteria for evaluation and improvement

---
*These prompts are designed to work optimally with the LLaMA-3-70B-instruct model in IBM Watsonx Agent Lab.*