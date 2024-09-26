├── LLM_Transformer_Architecture_with_no_pretrained_model/
│   ├── requirements.txt
│   ├── README.md
│   ├── .env
│   ├── manage.py
│   ├── vector_database/
│   │   ├── milvus_index.bin
│   │   ├── faiss_index.bin
│   │   └── db_config.py
│   ├── llm_app/
│   │   ├── urls.py
│   │   └── views.py
│   │   ├── models/
│   │   │   └── embedding_model.py
│   │   └── static/
│   │   ├── api/
│   │   │   ├── serializers.py
│   │   │   ├── urls.py
│   │   │   └── views.py
│   │   └── templates/
│   ├── scripts/
│   │   ├── generate_embeddings.py
│   │   ├── load_faiss_index.py
│   │   ├── train_custom_model.py
│   │   └── optimize_faiss_index.py
│   ├── data/
│   │   └── raw_text/
│   │   └── processed_text/
│   │   └── embedding_vectors/
