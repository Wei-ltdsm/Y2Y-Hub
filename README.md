# Y2Y-Hub

Introduction:
Y2Y Hub is a collaborative online platform dedicated to supporting autistic adults in their English learning journey. Each week, new presentations and lesson materials are created and shared, ensuring that valuable resources are not wasted but instead made accessible to a wider community.

# System Architecture

                ┌───────────────────────┐
                │       Users            │
                │  (Learners/Viewers)    │
                └───────────┬───────────┘
                            │
                            ▼
                ┌───────────────────────┐
                │   User Interface       │
                │  - Browse resources    │
                │  - Search & download   │
                │  - View PDFs/PPT/Word  │
                └───────────┬───────────┘
                            │
                            ▼
                ┌───────────────────────┐
                │       Backend          │
                │   Flask Application    │
                │  - Routing             │
                │  - Authentication      │
                │  - Role management     │
                │  - File handling       │
                └───────────┬───────────┘
                            │
                            ▼
                ┌───────────────────────┐
                │       Database         │ 
                │  - Resources table     │
                │  - Roles (viewer/uploader/admin) │
                │  - File metadata       │
                └───────────────────────┘
                            ▲
                            │
                ┌───────────────────────┐
                │   Admin Interface      │
                │  - Password protected  │
                │  - Upload resources    │
                └───────────────────────┘

