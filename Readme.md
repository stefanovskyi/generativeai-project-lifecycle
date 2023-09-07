## Generative AI Project Lifecycle


### Stage 1: Define Scope

- Accurate and narrow scope definition is crucial.
- Model abilities depend on size and architecture.
- Clarifying the functions and tasks the LLM will perform can save time and compute cost.

![Sequence diagramm](./images/sequence_diagram.png)

### Stage 2: Model Selection

- Decide between training a model from scratch or using an existing base model.
- Various considerations and rules of thumb will be covered for this decision.

### There are planty of typical tasks for LLMs, but the most common are:
| Task Name                        | Description                                                                                                                                                       |
|----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Chatbot Functions                | Serving as the core technology behind basic chatbots.                                                                                                             |
| Essay Writing                    | Generating essays based on provided prompts.                                                                                                                      |
| Conversation Summarization       | Summarizing dialogues based on the text provided as input.                                                                                                        |
| Translation Tasks                | Traditional translation between two different languages, such as French to German or English to Spanish.                                                          |
| Code Generation                  | Translating natural language into machine code. For instance, generating Python code based on a user prompt.                                                      |
| Information Retrieval            | Executing smaller tasks like fetching specific information.                                                                                                       |
| Named Entity Recognition         | Identifying people and places in a text, usually in the context of news articles or other written documents.                                                       |
| External Data and API Integration| Augmenting the model's capabilities by connecting it to external data sources or APIs to interact with the real world.                                             |
| Fine-Tuning for Specific Tasks   | Smaller models can be fine-tuned to excel at specific tasks, although the text doesn't explicitly say what these tasks could be.                                  |
| Language Understanding           | As the scale of foundation models grows, they gain a more refined understanding of language, which is encoded within their parameters.                            |

[Link to my Gist with most popular LLM tasks](https://gist.github.com/stefanovskyi/b27584057496bc6834d9a3497bce44d8)

![Flowchart diagramm](./images/flowchart_diagram.png)
### Stage 3: Performance Assessment and Training

- Use in-context learning and prompt engineering to improve performance.
- Fine-tuning may be needed for specific tasks.
- Supervised learning and fine-tuning will be covered in detail.

### Stage 4: Model Behavior

- Importance of ensuring the model aligns with human preferences.
- Reinforcement learning with human feedback for better behavior.

### Stage 5: Evaluation

- Metrics and benchmarks for model performance and alignment.
- The adapt and align stage is iterative and may involve multiple rounds of prompt engineering and fine-tuning.

### Stage 6: Deployment

- Optimize the model for deployment to make the best use of compute resources.

### Stage 7: Additional Infrastructure

- LLMs have fundamental limitations, like inventing information or limited reasoning.
- Techniques to overcome these limitations will be covered.

## Gantt Diagramm

Some of the stages could be run in parallel, but the order of the stages is fixed.


![Gantt diagramm](./images/gantt_diagram.png)