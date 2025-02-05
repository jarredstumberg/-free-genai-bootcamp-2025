## Functional requirements

The company wants to invest in owning their own server hardware due to cost increase concerns regarding 
managed services for GenAI solutions. There is also concern for the privacy of user data, and self-hosted 
infrastructure allows for greater control of user data. 

Self-hosting is the best option due to the fact that the user base is maximum 300 students in the local city 
of Dallas, TX. They can invest in 2 AI PCs and expanding their server capabilities to make this happen. 

## Assumptions

We are assuming the that Open-source LLMs that we choose will be powerful enough to run on hardware with an 
investment of $10-15K. 

We're going to connect the expanded single server in the office to the internet and we should have enough bandwidth
to server the total student capacity, not to exceed 300 people. 

## Data Strategy

Copyrighted materials handling is a concern so we plan on storing both free, open-source, and premium materials in our 
database for RAG access. 

## Technical Considerations

We're considering IBM Granite LLM because it's a truly open-source model with training data that is traceable so we 
can avoid copyright issues and champion transparency. 

https://huggingface.co/ibm-granite