# 3. Ideate With Prompty

!!! warning "THIS SECTION IS FOR INFORMATION ONLY → If time is limited, skip to the next section for the lab."

The infrastructure is provisioned. The development environment is setup. It's time to ideate.

![Dev Workflow](./../../img/workshop-developer-flow.png)

---

## 3.1 What are we building?

The Contoso Chat sample has a _working prototype_ of the chat AI in the `src/contoso-chat/api/contoso_chat` folder. These are the components of that application. 

```bash title="" linenums="0"
contoso-chat/
    product/
        product.prompty
        product.py
    chat.json
    chat.prompty
    chat_request.py    
```
In this section, we'll recreate the application from scratch using the process of ideation.

---

## 3.2 What is ideation?

Ideation is the process of going from the first prompt, to a functioning prototype. To do this:

- We start with a test question (user prompt) and an LLM (chat model)
- We assess the model's response to the question to see if meets a desired quality.
- If not, we "engineer" the prompt or "configure" the model, and try again.

In this lab, we'll mimic iteration by starting with a `basic.prompty` asset, then renaming it to a new asset of the form `chat-n.prompty` to reflect the n-th round of iteration. The goal is to get to the same `chat.prompty` version seein in the finished application above.

---

## 3.3 What is Prompty?

We talked about `chat.prompty` as our application prototype. What exactly is a `.prompty` file?

[Prompty](https://prompty.ai) is an open-source project from Microsoft that defines a specification (`.prompty` file format) and provides tooling (to create assets) and runtimes (to execute assets). Think of Prompty as a technology that brings the _model playground_ experience to your Visual Studio Code editor!

With Prompty you can:

- Define the prompt template in a `.prompty` file using YAML syntax
- Configure app metadata and model configuration paramters in frontmatter
- Specify input types (with sample data) that map to template context
- Execute the prompt with a model invocation, right from the editor
- Convert the asset into executable code in a supported language (e.g, Python)

This lets us iterate rapidly within our development environment, to _shape_ the data for a RAG-based application and evaluate it for quality before deploying to production. **Let's see this in action!**