# IBM Watsonx Research Agent – Setup Guide

## Prerequisites
- IBM Cloud account (sign up for free at https://cloud.ibm.com/registration)
- Basic understanding of AI agents and research workflows

## Step-by-Step Instructions

### 1. Set Up IBM Cloud Account
1. Create a free IBM Cloud account: https://cloud.ibm.com/registration
2. Verify your email address
3. Complete the account setup process

### 2. Access Watsonx.ai
1. Navigate to the IBM Cloud dashboard
2. Search for "Watsonx.ai" in the catalog
3. Create a new Watsonx.ai service instance
4. Launch Watsonx.ai → Create empty project
5. Name your project (e.g., "Research-AI-Agent")

### 3. Configure Object Storage
1. Add Object Storage (Lite tier - free)
2. This will be used for storing documents and vector indices
3. Note the bucket name for later use

### 4. Create Your Research Agent
1. Open Agent Lab → Click "Create Agent"
2. Set the foundation model: **LLaMA-3-70B-instruct**
3. Enter agent description:
   ```
   AI agent that summarizes research papers, suggests hypotheses, 
   drafts academic content, and formats citations in APA style
   ```

### 5. Configure Agent Tools
1. **Add Google Search tool**:
   - Enable web search capabilities
   - Configure search parameters for academic content
   
2. **Add Vector Index (Optional)**:
   - Upload research PDFs to create a knowledge base
   - Enable document grounding for more accurate responses

### 6. Set Up Quick Start Questions
Add these sample questions to help users get started:
- "Summarize recent research on artificial intelligence in healthcare"
- "Generate 3 research hypotheses about climate change mitigation"
- "Draft an introduction for a paper on machine learning ethics"
- "Create APA citations for quantum computing research papers"

### 7. Configure Prompt Steps
Add the following prompt engineering steps:

#### A. Research Summarization
```
Summarize recent research on the given topic in under 200 words, 
focusing on key findings, methodologies, and implications.
```

#### B. Hypothesis Generation
```
Based on current research gaps, suggest 3 specific, testable 
research hypotheses with clear reasoning and potential impact.
```

#### C. Academic Content Drafting
```
Write an academic-style introduction/abstract for a research paper 
on the specified topic, following standard academic conventions.
```

#### D. APA Citation Formatting
```
Generate properly formatted APA citations for recent academic 
papers on the given topic, ensuring accuracy and completeness.
```

### 8. Test Your Agent
1. Save your agent configuration
2. Test with sample research queries
3. Verify all tools are working correctly
4. Adjust prompts based on initial results

### 9. Deploy and Share
1. Deploy your agent for production use
2. Generate shareable links if needed
3. Document any custom configurations

## Troubleshooting

### Common Issues:
- **Agent not responding**: Check model selection and prompt configuration
- **Search not working**: Verify Google Search tool is properly enabled
- **Poor results**: Refine prompts and add more specific instructions
- **Storage issues**: Ensure Object Storage is properly configured

### Performance Tips:
- Use specific, detailed prompts for better results
- Include context about your research domain
- Test with various query types to optimize responses
- Regular prompt refinement improves accuracy

## Advanced Configuration

### Custom Vector Index Setup:
1. Upload domain-specific research papers
2. Configure embedding parameters
3. Test document retrieval accuracy
4. Fine-tune relevance scoring

### Prompt Optimization:
1. A/B test different prompt variations
2. Monitor response quality metrics
3. Iterate based on user feedback
4. Document successful prompt patterns

## Support and Resources
- IBM Watsonx Documentation: https://www.ibm.com/docs/en/watsonx-as-a-service
- IBM Cloud Support: https://cloud.ibm.com/unifiedsupport
- Community Forums: IBM Developer Community

---
*Need help? Check the troubleshooting section or reach out to the IBM Cloud support team.*