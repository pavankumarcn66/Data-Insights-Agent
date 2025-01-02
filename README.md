# **Data Insights Agent**

## **Project Overview**
**Data Insights Agent** is an AI-powered assistant designed to provide comprehensive insights into your data through a conversational chat interface. Whether it's pre-processing, exploratory analysis, or advanced insights, this agent enables users to explore their data effortlessly. It leverages a Jupyter environment to ensure a seamless, flexible, and transparent experience for interactive data analysis.

### **Key Features**
- 📂 **Effortless Data Upload**: Upload Excel files directly to initiate the data analysis workflow.
- 💬 **Conversational Intelligence**: Interact with the assistant via natural language commands to perform a wide range of data-related tasks.
- 🛠️ **Data Cleaning & Preparation**: Handle missing values, normalize data, encode categorical features, and more.
- 📊 **Advanced Visualizations**: Create detailed visual representations such as histograms, scatter plots, heatmaps, and more.
- 🔍 **Exploratory Data Analysis (EDA)**: Gain insights into data with summary statistics, correlation matrices, and trend identification.
- 🖥️ **Interactive Jupyter Environment**: Execute and refine analysis in a dedicated Jupyter environment for flexibility and control.
- ✏️ **Customizable Analysis**: Access, review, and modify code to fine-tune operations or adapt to specific use cases.

### **How It Works**
1. 📥 **Upload Your Data**: Begin by uploading an Excel file through the user-friendly interface.
2. 💡 **Natural Language Interaction**: Use conversational commands to guide the AI through various data tasks, such as cleaning, visualization, and insights generation.
3. 🚀 **Step-by-Step Guidance**: The agent takes you through the entire analysis pipeline, allowing for real-time adjustments and feedback.
4. 📈 **Dynamic Visualization**: Instantly view visual outputs and analysis results in the chat interface.
5. 🔧 **Code Transparency**: Retrieve and modify the underlying code, ensuring adaptability and a hands-on experience.

### **Example Commands**
- "🧹 Clean the dataset and fill missing values."
- "📊 Visualize the distribution of the 'income' column."
- "🔍 Show me a correlation heatmap of the dataset."
- "🛠️ Encode categorical variables using one-hot encoding."

### **How to Run the Project**

#### **1. Clone the Repository**
```bash
git clone https://github.com/pavankumarcn66/Data-Insights-Agent.git
cd Data-Insights-Agent
```

#### **2. Add Your API Keys**
Create a `.env` file and add your OpenAI or Anthropic API key:
```env
OPENAI_API_KEY=your-api-key
```

#### **3. Run the Services Using Docker Compose**
```bash
docker-compose up -d
```

#### **4. Access the Interface**
Open your browser and navigate to:
```
http://localhost:8080
```

#### **5. Upload Your Data**
📂 Upload an Excel or CSV file through the interface and start exploring your data with the conversational AI assistant.
