# 3. Ideate With Prompty

The infrastructure is provisioned. The development environment is setup. It's time to ideate.

![Dev Workflow](./../../img/workshop-developer-flow.png)

!!! info "OPTIONAL READ: Skip ahead to get to the lab exercise, or take a minute to get some context."

---

## 3.1 What are we building?

The Contoso Chat sample has a _working prototype_ of the chat AI in the `src/contoso-chat/api/contoso_chat` folder. These are the components of that application. In this section, we're going to see how we can recreate that application from scratch.

```bash title="" linenums="0"
contoso-chat/
    product/
        product.prompty
        product.py
    chat.json
    chat.prompty
    chat_request.py    
```

---

## 3.2 How do we ideate?

Ideation is the process of iterating on the application till we get a functional prototype. To do this we start with a test question and a chat model to get the base response. Then we iterate on the application (prompt engineering) till the response meets the desired quality.

!!! info "We'll mimic the iteration process by creating a sandbox/ folder in which we will start with a `basic.prompty` and refine it till we get the `chat.prompty` version seen in the _contoso-chat_ application folder above.

---

## 3.3 What is Prompty?

We mentioned `chat.prompty` as our application prototype - so what exactly is it? 
    
[Prompty](https://prompty.ai) is an open-source project from Microsoft that defines a new file asset format (`.prompty`) with tooling (to create and manage assets) and runtimes (to execute them). It effectively brings the playground experience into your Visual Studio Code editor!

1. Create a prompty asset with frontmatter (metadata) and content (template)
2. Use metadata to configure the model parameters and prompt inputs
3. Use the template to provide system context, instructions and data (grounding)

Use the Visual Studio Code extension to _create_ new Prompty files, _execute_ them to view generated responses in the terminal, and _shape your data_ for RAG by using sample files (JSON) with placeholders for data that can be retrieved dynamically (e.g., from product search or customer database queries) later. **Let's see this in action!**