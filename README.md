ai-studymate/
├── backend/                  # FastAPI
│   ├── app/
│   │   ├── main.py           # điểm khởi động, gắn các router
│   │   ├── core/             # config, bảo mật (JWT), kết nối DB
│   │   ├── models/           # bảng PostgreSQL (SQLAlchemy)
│   │   ├── schemas/          # định dạng dữ liệu vào/ra (Pydantic)
│   │   ├── routers/          # auth, documents, chat, summary, quiz, flashcards, planner, progress
│   │   ├── services/         # logic nghiệp vụ, router chỉ gọi vào đây
│   │   └── rag/              # phần lõi: pdf_loader, chunker, embedder, vector_store, retriever, llm_client, prompts
│   ├── tests/
│   ├── .env.example          # KHÔNG commit file .env thật (chứa API key)
│   └── requirements.txt
├── mobile/                   # Flutter
│   └── lib/
│       ├── main.dart
│       ├── core/             # theme, hằng số, http client, lưu token
│       ├── data/             # models + repositories gọi API
│       └── features/         # mỗi tính năng một thư mục: auth, chat_pdf, summary, quiz, flashcards, planner, progress
├── landing/                  # trang giới thiệu (HTML/CSS/JS)
├── docs/                     # sơ đồ kiến trúc, ERD, báo cáo, ảnh demo
├── rag_experiments/          # notebook/script thử RAG ở tháng 1
└── README.md
