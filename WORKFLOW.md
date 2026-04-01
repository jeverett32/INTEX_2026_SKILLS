## **=INTEX Web App Workflow**

### **1. Core Methodology: CRISP-DM & Research**
* **Skill:** `/crisp-dm-pipeline` + `/researcher`
* **Plugin:** `data`
* **Execution:** * Initiate **Business Understanding** to define objectives.
    * Perform **Data Understanding** and **Preparation**.
    * **Iterative Modeling:** Use `/researcher` during **Modeling** and **Evaluation** to optimize performance.
* **Installation:**
    * `npx claudepluginhub anthropics/knowledge-work-plugins --plugin data`

### **2. Technical Implementation: Full-Stack Development**
* **Skill:** `/full-stack-react-dotnet`
* **Plugin:** `cybersecurity-skills` + `data`
* **Execution:** * Generate **.NET** backend infrastructure.
    * Develop **React** frontend UI.
    * Integrate optimized models into the application logic.
* **Installation:**
    * `npx claudepluginhub mukul975/anthropic-cybersecurity-skills --plugin cybersecurity-skills`
    * `npx claudepluginhub anthropics/knowledge-work-plugins --plugin data`

### **3. Design & Quality Assurance**
* **Skill:** `/frontend-design` + `/webapp-testing`
* **Plugin:** `data` + `ui-ux-pro-max`
* **Execution:** * Apply UI/UX principles for intuitive user experience.
    * Run continuous **Testing** suites for API endpoints and model integration.
* **Installation:**
    * `npx claudepluginhub nextlevelbuilder/ui-ux-pro-max-skill --plugin ui-ux-pro-max`
    * `claude plugin install frontend-design@claude-plugins-official`

### **4. Deployment**
* **Plugin:** `vercel-plugin` + `supabase-plugin`
* **Execution:** Deploy the frontend to Vercel and manage the database/auth via Supabase.
* **Installation:**
    * `claude plugin install vercel@claude-plugins-official`
    * `claude plugin install supabase@claude-plugins-official`

### **5. Stakeholder Delivery**
* **Skill:** `Pptx-plugin`
* **Execution:** * Generate a final presentation summarizing CRISP-DM findings.
    * Demonstrate the web app solution to the core business problem.
* **Installation:**
    * `claude plugin marketplace add https://github.com/MiniMax-AI/skills` then `claude plugin install minimax-skills`

---

> **Note on Concurrency:** This workflow is non-linear. Data modeling often informs frontend requirements, and testing should occur iteratively throughout the development of both the model and the web app.
