# Online_Code_Compiler_API
Recommended Python Stack

Framework: FastAPI (fast + modern)

Execution: Docker (secure sandbox)

Async Tasks: Celery / BackgroundTasks (optional later)

Security: subprocess + timeout + container isolation

⚙️ Basic Architecture
User Code Request
        ↓
FastAPI Backend
        ↓
Execution Engine (Docker/Subprocess)
        ↓
Compile + Run
        ↓
Return Output / Errors
