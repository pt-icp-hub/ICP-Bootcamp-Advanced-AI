# 🤖 ICP Bootcamp - Advanced AI Challenge

Welcome to the **Internet Computer Protocol (ICP) Bootcamp - Advanced AI Challenge**! This challenge focuses on deploying AI-powered agents on the ICP. For this challenge, your task is to deploy AI models and agents that interact with the ICP blockchain.

## 📜 Table of Contents

- [🎯 Advanced Challenge](#-advanced-challenge)
- [💡 Freedom to Innovate](#-freedom-to-innovate)
- [📖 Learning Outcomes](#-learning-outcomes)
- [🔗 Resources & Documentation](#-resources--documentation)
- [📩 Submit Your Project!](#-submit-your-project)

---

## 🎯 Advanced Challenge

### ✅ **Challenge 1: Deploy GPT‑2 Fully on ICP**

**Task:**  
Deploy the GPT‑2 model on the Internet Computer blockchain using the example integration by DecideAI. This project implements GPT‑2 inference on ICP, providing a straightforward way to deploy and interact with the model.

#### What You’ll Do:
- **Set Up the Model:**  
  Use DecideAI’s GPT‑2 integration to deploy the model as an ICP canister.
- **Process AI Responses:**  
  Implement inference calls that process user input and generate text based on the GPT‑2 model.
- **Analyze Computational Costs:**  
  Explore the instruction counts and performance metrics based on varying input and generation lengths.

#### 💡 Tips:
- Refer to the DecideAI integration repository for detailed instructions:  
  [DecideAI - GPT‑2 on ICP](https://github.com/decide-ai/decide-ai-ic/tree/main/examples/gpt2)
- Review the provided analysis on instruction counts and performance to understand computational costs.
- Experiment with different input lengths and generation parameters to optimize performance.

---

### ✅ **Challenge 2: Implement an AI Agent with Blockchain Tools**

**Task:**  
Develop an AI agent that uses the **OpenAI GPT-4o Mini API** for processing natural language commands while integrating with the **ICP blockchain** to query balances and execute transfers. This implementation does **not** require a Trusted Execution Environment (TEE) for simplicity.

#### What You’ll Do:
- **Implement an AI Agent:**  
  Utilize the Anda framework to build an agent capable of handling blockchain interactions.
- **Enable ICP Ledger Interactions:**  
  Add tools to query account balances and execute token transfers on the ICP blockchain.
- **Process AI Commands:**  
  Allow users to interact with the agent via text-based inputs to retrieve blockchain-related information.

#### 🔧 **Anda Framework Configuration**
Before running your AI agent, make sure to add the following lines to your `.env` file:
```
MODEL_NAME='gpt-4o-mini'
MODEL_ENDPOINT='https://api.openai.com/v1'
```
To obtain the **OpenAI API Key**, please DM **Tiago or [Your Name]**. We have prepared keys specifically for this challenge.

For authentication, the **ID_SECRET** and **ROOT_SECRET** can be directly derived from one of your existing `dfx` identities. You can do this by specifying the path to your selected identity `.pem` file. For example, to use the principal address of your **default** identity, run:
```
./target/debug/anda_engine_cli agent-run -i ~/.config/dfx/identity/default/identity.pem -p 'Please check my PANDA balance'
```

#### 💡 Tips:
- Use the Anda framework for AI agent deployment:  
  [Anda Framework Repository](https://github.com/ldclabs/anda)
- Follow the example **ICP Ledger Agent** for blockchain integration:  
  [ICP Ledger Agent Guide](https://github.com/ldclabs/anda/tree/main/examples/icp_ledger_agent)
- OpenAI API for AI-powered reasoning and decision-making.
- Experiment with different interaction flows to optimize user experience.

---

## 💡 Freedom to Innovate

Feel free to modify, extend, or completely re-imagine these AI implementations. You may optimize performance, add new features, or experiment with alternative inference methods. The goal is to leverage the power of AI on ICP while addressing the unique challenges of deploying machine learning models on a decentralized platform.

---

## 📖 Learning Outcomes

- **Deploying Complex AI Models:**  
  Learn how to deploy a sophisticated machine learning model (GPT‑2) on ICP.
- **Building AI Agents on ICP:**  
  Develop AI-powered assistants that interact with the blockchain.
- **Integrating OpenAI APIs with ICP:**  
  Understand how to leverage AI models to process user inputs and execute on-chain transactions.
- **Using ICP Ledger Functions:**  
  Gain experience in querying balances and handling token transfers programmatically.
- **Exploring the Anda Framework:**  
  Learn how to develop AI-driven automation using the Anda framework.

---

## 🔗 Resources & Documentation

📚 [Official ICP Docs](https://internetcomputer.org/docs)  
📚 [Motoko Programming Guide](https://sdk.dfinity.org/docs/language-guide/motoko.html)  
📚 [DecideAI GPT‑2 on ICP Repository](https://github.com/decide-ai/decide-ai-ic/tree/main/examples/gpt2)  
📚 [Hugging Face GPT‑2 Open Instruct v1](https://huggingface.co/vicgalle/gpt2-open-instruct-v1/tree/main)  
📚 [Anda Framework Repository](https://github.com/ldclabs/anda)  
📚 [ICP Ledger Agent Guide](https://github.com/ldclabs/anda/tree/main/examples/icp_ledger_agent)  
📚 [OpenAI GPT-4o API Docs](https://platform.openai.com/docs/)

---

## 📩 Submit Your Project!

🎯 **Completed your challenge? Submit your project here:**  
📢 [Submission Form](https://formyfi.io/form/071b1e15-f475-4696-92d8-3c6cc2980a87)

📌 **Want to explore more challenges? Return to the index:**  
🔗 [ICP Bootcamp Index](https://github.com/pt-icp-hub/ICP-Bootcamp-Index?tab=readme-ov-file)

---

🚀 **Good luck, and welcome to AI-powered development on the Internet Computer!** 🚀

