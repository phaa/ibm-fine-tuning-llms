# Generative AI Advanced Fine‑Tuning for LLMs – IBM

This repository contains code, notebooks, and notes developed during the [Generative AI Advanced Fine‑Tuning for LLMs](https://www.coursera.org/learn/generative-ai-advanced-fine-tuning-for-llms) course offered by **IBM** through **Coursera**.

<p align="center">
  <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/assets/logos/SN_web_lightmode.png" title="IBM Skills Network" width="400" />
</p>

## About the Course

This is an **intermediate-level** course (~9 hours) that teaches advanced techniques for fine-tuning causal large language models (LLMs), including instruction tuning, reward modeling, PPO (Proximal Policy Optimization), and direct preference optimization (DPO) using frameworks such as Hugging Face and PyTorch.

- Instruction tuning and reward modeling pipelines
- Treating LLMs as probabilistic policies with Reinforcement Learning from Human Feedback (RLHF)
- Implementing PPO and configuring PPO trainers
- Applying DPO, including partition functions and optimal policy methods

## Repository Structure

Organized by modules following the course outline:
```
📁 Repository structure
├── 📁 Module 1 – Instruction Tuning & Reward Modeling
│ ├── 📝 Lab: Instruction Tuning with Hugging Face
│ ├── 📝 Lab: Reward Modeling and Loss Functions
├── 📁 Module 2 – RLHF, PPO & DPO
│ ├── 📝 Lab: PPO with Hugging Face
│ ├── 📝 Lab: Direct Preference Optimization (DPO)
├── README.md
```
## Technologies Used

- **Python**  
- **PyTorch**  
- **Hugging Face Transformers**  
- **Reinforcement Learning Libraries**  
- **Jupyter Notebooks**

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/phaa/ibm-fine-tuning-llms.git
cd ibm-fine-tuning-llms/
```

2. Activate the virtual environment (conda or venv):
   ```bash
   conda activate ibmenv
   ```
3. Run the notebooks in Jupyter lab:  
   ```bash
   jupyter lab
   ```
*Each notebook has a cell to install the necessary dependencies.* 

## Contributions  
This repository is a record of the course learning, but suggestions and improvements are always welcome!

