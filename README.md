# 🧠 Python, Pydantic & LangGraph Projects

A collection of hands-on Python projects and practical implementations exploring **Pydantic, LangGraph, StateGraph, and AI-powered workflow automation**.

This repository focuses on understanding structured data validation, graph-based workflows, state management, conditional routing, and building practical applications using LangGraph.

## 🚀 Projects Included

### 1. Pydantic Fundamentals
**Notebook:** `1-Pydantic/intro.ipynb`

- Introduction to Pydantic.
- Understanding Pydantic BaseModel.
- Data validation using Python type annotations.
- Defining structured data models.
- Comparing Pydantic models with Python dataclasses.

### 2. LangGraph Basic Projects

**Folder:** `2-LangGraph Basic/`

#### A. Simple Graph Workflow
**Notebook:** `simplegraph.ipynb`

- Introduction to LangGraph.
- Understanding StateGraph.
- Defining graph state using TypedDict.
- Creating nodes and edges.
- Implementing conditional edges.
- Building and executing graph workflows.

#### B. Employee Bonus Eligibility
**Notebook:** `employee_bonus_eligibility.ipynb`

- Employee information management using graph state.
- Performance score evaluation.
- Conditional routing based on eligibility.
- Generating bonus eligibility results.

#### C. Student Result Management
**Notebook:** `student_result_management.ipynb`

- Student information management.
- Evaluating examination marks.
- Implementing pass/fail conditions.
- Generating results through conditional graph execution.

#### D. AI Customer Support System
**Notebook:** `AI_Customer_Support.ipynb`

- Customer support ticket processing.
- Ticket validation.
- Automatic issue classification.
- Department-based routing (Billing, Technical, General).
- Priority assignment.
- Generating customer support responses.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pydantic | Data validation and structured schemas |
| LangGraph | Graph-based workflow orchestration |
| LangChain | Framework for LLM applications |
| TypedDict | Defining structured state schemas |
| Jupyter Notebook | Development and experimentation |

## 📂 Repository Structure

```text
python-pydantic-langgraph-projects/
│
├── 1-Pydantic/
│   └── intro.ipynb
│
├── 2-LangGraph Basic/
│   ├── AI_Customer_Support.ipynb
│   ├── employee_bonus_eligibility.ipynb
│   ├── simplegraph.ipynb
│   └── student_result_management.ipynb
│
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/python-pydantic-langgraph-projects.git
```

### 2. Navigate to the Project

```bash
cd python-pydantic-langgraph-projects
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows:**
```bash
venv\Scripts\activate
```

**Linux / macOS:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebooks and execute the cells to explore the implementations.

## 📚 Key Learning Outcomes

Through these projects, I explored:

- Understanding data validation using Pydantic.
- Working with structured data using TypedDict.
- Understanding LangGraph architecture.
- Creating nodes, edges, and conditional edges.
- Managing and updating graph states.
- Building decision-making workflows.
- Implementing conditional routing.
- Developing a practical AI customer support workflow.
