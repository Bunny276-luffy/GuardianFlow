GuardianFlow: Sovereign Agentic IDE

Democratizing Secure AI Orchestration on AMD Ryzen™ AI

GuardianFlow is a hardware-native, sovereign IDE designed to orchestrate and deploy secure AI agents directly on the AMD Ryzen AI NPU. By shifting the entire agentic pipeline—from logic verification to execution—onto local hardware, GuardianFlow eliminates the "Privacy-Performance Paradox," ensuring 100% local data residency and Zero-Cloud Egress.

🚀 Key Features
n8n-Style Workflow Canvas: A visual, node-based interface to orchestrate complex multi-agent logic with real-time observability.

On-Device AMD NPU Execution: Moves inference pipelines to local XDNA-V1 hardware, ensuring sensitive institutional data never leaves the device.

Sentinel Shield 2.1: An autonomous security layer that identifies and patches logic vulnerabilities and redacts PII before agent deployment.

Dual-Agent Red-Teaming: A built-in "Supervisor Agent" that audits the "Worker Agent" in real-time to neutralize bias and hallucinations.

Adaptive Power Profiles: Hardware-aware execution toggling between "Green Mode" (3.8W) for efficiency and "Performance Mode" for high-throughput tasks.

🛠️ The Sovereign Stack
Hardware: AMD Ryzen™ AI 300 Series (XDNA-V1 Architecture).

AI Optimization: AMD Ryzen AI Software Suite & INT8 Quantization Kernels.

Orchestration: FastAPI (Python), SQLite (Persistent Workspace), and Uvicorn.

Frontend: Tailwind CSS & Jinja2 Templates.

📁 Project Structure
Plaintext
GuardianFlow/
├── backend/            # FastAPI Orchestrator & Multi-Agent Logic
├── frontend/           # Tailwind/Jinja2 Visual Canvas
├── npu_kernels/        # INT8 Optimized Models & NPU Configs
├── sentinel_shield/    # Security Audit & PII Redaction Engine
├── workspace/          # Local SQLite History & Sovereign Reports
└── requirements.txt    # System Dependencies
🛠️ Getting Started
1. Prerequisites
Hardware: AMD Ryzen™ AI enabled laptop (e.g., HP Omen 17).

Software: AMD Ryzen AI Software Suite installed and configured.

2. Installation
Bash
git clone https://github.com/Bunny276-luffy/GuardianFlow.git
cd GuardianFlow
pip install -r requirements.txt
3. Run the IDE
Bash
python main.py
Access the dashboard at http://localhost:8000

🛡️ Sovereignty & Compliance
GuardianFlow is built to comply with strict global data residency laws (such as India's DPDP Act) by providing hardware-signed audit reports verifying that 0KB of data egressed to the cloud during agent execution.
